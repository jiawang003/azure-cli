.. :changelog:

Release History
===============
2.0.8 (2017-06-13)
++++++++++++++++++
* Remove useless line-too-long suppression
* fix acs kube get-credentials ssh-key loading (#3612)
* Change a message so as not to confuse MacOS users. (#3568)
* Eliminating too-many-arguments pylint disable rule (#3583)
* Fix acs style
* Expand service principal testing somewhat. (#3114)
* Move all existing recording files to latest folder
* rbac: clean up role assignments and related AAD application when delete a service principal (#3610)
* Fix acs kube get-credentials ssh-key loading (

2.0.7 (2017-05-30)
++++++++++++++++++

* convert master and agent count to integer

2.0.6 (2017-05-09)
++++++++++++++++++

* Minor fixes.

2.0.5 (2017-05-05)
++++++++++++++++++

* Fix to use one of the loaded keys.

2.0.4 (2017-04-28)
++++++++++++++++++

* New packaging system.
* fix the master and agent count to be integer instead of string

2.0.3 (2017-04-17)
++++++++++++++++++

* expose 'az acs create --no-wait' and 'az acs wait' for async creation
* expose 'az acs create --validate' for dry-run validations
* remove windows profile before PUT call for scale command (#2755)

2.0.2 (2017-04-03)
++++++++++++++++++

* Fix kubectl version, always use latest stable. (#2517)
* [ACS] Adding support for configuring a default ACS cluster (#2554)
* [ACS] Provide a short name alias for the orchestrator type flag (#2553)

2.0.1 (2017-03-13)
++++++++++++++++++

* Add support for ssh key password prompting. (#2044)
* Reduce the default number of masters. (#2430)
* Add support for windows clusters. (#2211)
* Switch from Owner to Contributor role. (#2321)
* Remove acs - vm dependency (#2288)
* On scale, clear the service principal profile so that it will update


2.0.0 (2017-02-27)
++++++++++++++++++

* GA release
* Add customizable master_count for Kubernetes cluster create


0.1.2rc2 (2017-02-22)
+++++++++++++++++++++

* Rev compute package to 0.33.rc1 for new API version.
* Documentation fixes.


0.1.2rc1 (2017-02-17)
+++++++++++++++++++++

* Move acs commands from vm to acs module
* Rev kubectl default version
* Show commands return empty string with exit code 0 for 404 responses


0.1.1b3 (2017-02-08)
+++++++++++++++++++++

* Upgrade Azure Management Compute SDK from 0.32.1 to 0.33.0


0.1.1b2 (2017-01-30)
+++++++++++++++++++++

* Generate ssh key file if needed.
* Add help text for get credentials command.
* Add path expansion to file type parameters.
* Fix the double-browser problem with dcos browse.
* Add validation for SSH key format.
* Support Python 3.6.

0.1.1b1 (2017-01-17)
+++++++++++++++++++++

* Detect service principal errors and raise a message.
* Update service principal creation so that it is subscription specific.

0.1.0b11 (2016-12-12)
+++++++++++++++++++++

* Preview release.
