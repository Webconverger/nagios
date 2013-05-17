# Webconverger Nagios configuration

For monitoring [Webconverger services](http://webconverger.org/servers/).

Could it be better? Simpler? Please let me know!

## Installation on a stable Debian server

	apt-get install nagios3

	git clone CLONE_URL /etc/nagios3/conf.d

## Command definitions

`check_http` commands are defined in `/etc/nagios-plugins/config/http.cfg`

## Mailing out alerts to root by default

	grep ^root /etc/aliases

To see who is on that distribution list.
