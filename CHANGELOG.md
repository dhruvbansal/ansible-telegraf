dj-wasabi.telegraf
------------------

Below an overview of all changes in the releases.

Version (Release date)

0.x.x (2016-01-13)

  * Fixed test for test-kitchen
  * Added travis-ci test for testing default installation when PR is made

0.3.0 (2016-01-13)

  * Made it work with telegraf 0.10.0
  * Default installation: 0.10.0

0.2.0 (2015-11-14)

  * Fixed kitchen test setup
  * Adding "net" to the telegraf_plugins_default property
  * Update etc-opt-telegraf-telegraf.conf.j2 #2 (By pull request: aferrari-technisys (Thanks!))
  * Improvement and upgrade for v0.2.0 of telegraf #1 (By pull request: aferrari-technisys (Thanks!))

0.1.0 (2015-09-23)

  * Updated `telegraf_agent_version` to 0.1.9
  * Added restart when package is changed (When updated for example)
  * Added several plugin options:
    * pass
    * drop
    * tagpass
    * tagdrop
    * interval
  * Updated documentation
  

0.0.2 (2015-09-20)

  * Updated README dus to missing colon
  * Forgot to update the meta file
  * Added Changelog file

0.0.1 (2015-09-20)

  * Initial release
