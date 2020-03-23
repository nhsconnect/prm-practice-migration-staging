## How to deploy

There are 2 environments: 
  * staging or living version - all new changes go here: https://nhsconnect.github.io/prm-practice-migration-staging/
  * live version - it changes less often when the changes have been approved:
  https://nhsconnect.github.io/prm-practice-migration/
  
There is an underlying issue with Jekyll being able to cope with the same website being deployed on the same host on 2 different urls - like there is the case for the migration guide (see `/prm-practice-migration-staging` vs `/prm-practice-migration-staging` ). To get around it `baseurl` parameter in `_config` needs to always be set to the appropiate value(ie. `prm-practice-migration-staging` for staging, `prm-practice-migration` for live) 

To deploy we will use a local repo with 2 remotes: 
* `git@github.com:nhsconnect/prm-practice-migration.git` - named `live` - the live one
* `git@github.com:nhsconnect/prm-practice-migration-staging.git` - named `origin` - the staging one

There will be 2 branches: 
* `master` following the `master` branch of the staging remote
* `to-live` following the `master` branch of the live remote

The only difference between the `to-live` and `master` is the `_config.yml` and more precisely the `baseurl` value.

All changes will happen as usual on `master` and pushed onto the `master` branch of the staging repo. However might need to run: `git push --set-upstream origin master:master`

Deploying to live:
* move to `to-live` branch: `git checkout to-live`
* merge  `master` in `to-live`: `git merge master`
* push only the `to-live` branch into the `master` branch of the live version: `git push --set-upstream live to-live:master` where `live` is the name of the remote for live
