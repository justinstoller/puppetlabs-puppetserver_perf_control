# A Puppetfile for a control repo that can be used for Puppet Server / PE perf testing

mod 'stahnma/epel', '1.3.1'

# Modules that have been extracted from core Puppet
mod 'puppetlabs/augeas_core', '1.0.5'
mod 'puppetlabs/sshkeys_core', '1.0.3'
mod 'puppetlabs/yumrepo_core', '1.0.4'

# Modules required to get a tomcat server up and running
mod 'puppetlabs/tomcat', '3.1.0'
mod 'puppetlabs/stdlib', '6.1.0'
mod 'nanliu/staging', '1.0.3'
mod 'puppetlabs/concat', '6.1.0'
mod 'puppetlabs/java', '6.0.0'

# Modules required to get a postgres server up and running
mod 'puppetlabs/postgresql', '6.2.0'
mod 'puppetlabs/apt', '7.2.0'

# Seeing issues with latest version of gatling
#mod 'rampup_profile_gitlab',
#  :git    => 'https://github.com/Puppet-RampUpProgram/rampup_profile_gitlab',
#  :commit => '4a5599882c0e2d716be53b0f543be2af90ec6a94'
mod 'golja/influxdb', '4.0.0'
mod 'vshn/gitlab', '1.15.2'
mod 'puppetlabs/apache', '5.2.0'

##################################################################################
## MODULES BELOW THIS LINE ARE NOT USED BY ANY ROLES/PROFILES
##################################################################################

# Enable collection of Puppet api-endpoint metrics
mod 'npwalker-pe_metric_curl_cron_jobs', '4.6.0'

# Extra modules just to increase the total amount of code in the puppet environment
## "Additional modules to complement PE installation"
mod 'hunner/hiera', '2.0.2'
mod 'puppetlabs/puppetserver_gem', '1.1.1'
mod 'puppetlabs/inifile', '4.0.0'
mod 'puppetlabs/hocon', '1.1.0'
mod 'puppetlabs/vcsrepo', '3.0.0'
mod 'puppet/archive', '4.4.0'

## Basic linux host management
mod 'puppetlabs/accounts', '6.0.0'
mod 'jlambert121/yum', '0.2.1'
mod 'puppetlabs/ntp', '8.1.0'
mod 'puppetlabs/firewall', '2.1.0'
mod 'saz/rsyslog', '5.0.0'

## Advanced linux host management
mod 'garethr/docker', '5.3.0'

## Common tools in an infrastructure
mod 'camptocamp/openldap', '1.17.0'
mod 'arioch/redis', '3.3.0'
mod 'saz/memcached', '3.4.0'
mod 'puppetlabs/haproxy', '4.1.0'
mod 'jfryman/nginx', '999.999.999'
mod 'rtyler/jenkins', '1.7.0'
mod 'sensu/sensu', '3.11.0'
mod 'bfraser/grafana', '2.5.0'

mod 'elasticsearch/elasticsearch', '0.16.2'
mod 'elasticsearch/logstash', '0.6.6'
mod 'elasticsearch/logstashforwarder', '0.1.1'

mod 'puppetlabs/java_ks', '3.0.0'

## Basic Windows host management
mod 'puppetlabs/acl', '3.0.0'
mod 'puppetlabs/reboot', '2.2.0'
mod 'chocolatey/chocolatey', '1.2.6'
mod 'puppetlabs/powershell', '2.3.0'
mod 'puppetlabs/registry', '3.0.0'
mod 'puppetlabs/wsus_client', '3.0.0'
mod 'badgerious/windows_env', '999.999.999'
mod 'puppet/windows_firewall', '2.0.2'
mod 'puppet/windows_autoupdate', '3.0.0'
mod 'puppet/dotnet', '2.0.2'
mod 'puppet/windowsfeature', '3.2.2'
mod 'puppet/windows_eventlog', '2.0.2'

## Advanced Windows host management
mod 'chocolatey/chocolatey_server', '0.0.5'
# this apparently requires a PE license
#mod 'puppetlabs/sqlserver', '1.1.2'
mod 'puppet/iis', '3.1.0'
mod 'puppet/graphite_powershell', '3.0.2'

## And while we're at it, lets do this all in the cloud
mod 'puppetlabs/aws', '2.1.0'

## i18n, just putting this here created a perf issue in the past
mod 'eputnam-i18ndemo', '0.3.0'
