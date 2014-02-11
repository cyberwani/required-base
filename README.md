# required+ Base
__a fork from the awesome: [hm-base](https://github.com/humanmade/hm-base)__

Standard WordPress layout for required+ projects.

### Setup Instructions.

1. Create an empty directory for your project and go there:
```
mkdir <PROJET_NAME>
cd <PROJECT_NAME>
```
2. Clone the repository incl. the WordPress submodule when in the `<PROJECT_NAME>` directory
```
git clone --recursive git://github.com/neverything/required-base.git .
```
3. Remove the required-base remote.
```
git remote rm origin
```
4. Add the remote for your new project
```
git remote add origin <REPOSITORY_URL>
```
5. Push to the new remote
```
git push origin master
```
6. Add your database settings
```
# Local site:
mv wp-config-sample.php wp-config-local.php
# Now add your local database settings there

# Live site: Production database settings should be added to wp-config.php.
```
Boom, done!

## Contribution guidelines ##

see https://github.com/neverything/required-base/blob/master/CONTRIBUTING.md
