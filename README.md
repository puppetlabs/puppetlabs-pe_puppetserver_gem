# puppetlabs pe_puppetserver_gem module

This module provides management of Ruby gems for PE Puppet Server.


For PE Puppet Server:

    package { 'json':
      ensure   => present,
      provider => pe_puppetserver_gem,
    }

This uses gem as a parent and uses the PE version of the
`puppetserver gem` command for all gem operations.

## Deprecation for Puppet >= 4.0

As of Puppet 4.0, this module has been deprecated. Please use the puppet_gem provider instead.
