# required+ Base
__a fork from the awesome: [hm-base](https://github.com/humanmade/hm-base)__

Standard WordPress layout for required+ projects.

### Setup Instructions.

* Create an empty directory for your project. In terminal, navigate to this directory.
* Clone the repository `git clone --recursive git://github.com/neverything/required-base.git .`
* Remove the hm-base remote. `git remote rm origin`
* Add the remote for your new project `git remote add origin [url]`
* Push to the new remote `git push origin master`

* Add your database settings.

	* Local site: `mv wp-config-sample.php wp-config-local.php`, then add your local database settings.
	* Live site: Production database settings should be added to `wp-config.php`.

Done!

## Contribution guidelines ##

see https://github.com/neverything/required-base/blob/master/CONTRIBUTING.md
