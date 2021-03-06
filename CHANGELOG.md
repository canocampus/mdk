Changelog
=========

v0.4
----

* New command `tracker` to fetch information from the tracker
* `alias` support arguments for bash aliases
* `alias` can update aliases
* `backport` works locally
* `backport` can update tracker Git info
* `behat` can limit features to test
* `behat` can disable itself
* `check` can fix problems
* `check` checks remote URLs
* `check` checks $CFG->wwwroot
* `check` checks the branch checked out on integration instances
* `create` accepts multiple versions
* `create` accepts multiple suffixes
* `phpunit` can limit testing to one file
* `pull` can download patch from the tracker
* `pull` can checkout the remote branch
* `push` checks that the branch and MDL in commit message match
* `rebase` can update tracker Git info
* `run` can list the available scripts
* Cached repositories are mirrors
* Removed use of Bash script to launch commands
* Deprecated moodle-*.py files
* Instances can be installed on https
* Improved debugging


v0.3
----

* New command `behat` which is equivalent to `phpunit`
* New command `pull` to fetch a patch from a tracker issue
* New script `webservices` to entirely enable the web services
* `push` now updates the Git information on the tracker issue (Thanks to Damyon Wiese)
* `phpunit` can also run the tests after initialising the environment
* `update --update-cache` can proceed with the updates after updating the cached remotes
* `info` can be used to edit settings ($CFG properties) in config.php
* `init` has been a bit simplified
* Basic support of shell commands in aliases
* The settings in config.json are read from different locations, any missing setting will be read from config-dist.json
* Bug fixes
