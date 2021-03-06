Linux Update Manager
====================

Update multiple Linux OS Distributions from a single server

### Installation

1. Clone this script from github or copy the files manually to your preferred directory.

2. Create 'updateall.lst' from the included 'updateall.lst.example',

```
cp updateall.lst.example updateall.lst
```

and fill it with your servers list (one in a row):

```
Hostname Port OS
```

for example (leave a blank line in the end of the file):

```
10.0.0.2 22 CentOS
10.0.0.3 220 Ubuntu
```

Note: You should generate and copy the server ssh public code of the computer running this script to the other computers to prevent the script asking for password.

#### Supported OS parameter options
* Cent0S
* Debian
* OracleLinux
* RHEL
* Solaris
* Ubuntu

Authors: [RaveMaker][RaveMaker] & [ET][ET].

[RaveMaker]: http://ravemaker.net
[ET]: http://etcs.me
