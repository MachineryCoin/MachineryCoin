
Copyright (c) 2014-2015 MachineryCoin Developers


MachineryCoin 9.1.0 BETA

Copyright (c) 2014-2015 MachineryCoin Developers
Copyright (c) 2013 NovaCoin Developers
Copyright (c) 2011-2012 Bitcoin Developers
Distributed under the MIT/X11 software license, see the accompanying
file license.txt or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).


Intro
-----
MachineryCoin is a free open source project derived from NovaCoin, with
the goal of providing a long-term energy-efficient scrypt-based crypto-currency.
Built on the foundation of Bitcoin and NovaCoin, innovations such as proof-of-stake
help further advance the field of crypto-currency.

Setup
-----
After completing windows setup then run windows command line (cmd)
  cd daemon
  MachineryCoind
You would need to create a configuration file MachineryCoin.conf in the default
wallet directory. Grant access to MachineryCoind.exe in anti-virus and firewall
applications if necessary.

The software automatically finds other nodes to connect to.  You can
enable Universal Plug and Play (UPnP) with your router/firewall
or forward port 

23489 (TCP) to your computer so you can receive
incoming connections.  MachineryCoin works without incoming connections,
but allowing incoming connections helps the MachineryCoin network.

Upgrade
-------
All you existing coins/transactions should be intact with the upgrade.
To upgrade first backup wallet
MachineryCoind backupwallet <destination_backup_file>
Then shutdown MachineryCoind by
MachineryCoind stop
Start up the new MachineryCoind.



