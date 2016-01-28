#						whohassocket


###  What is it?
  -----------
Very usefull script for Solaris OS. Script that shows what process holds the network port. 
Output is in human-readable and command line pereprocessor format. 
Script can select data by port, prosess-id or user-id.

###  The Latest Version
  ------------------
	version 1.1

###  Documentation
  -------------

###  Installation
  ------------

###  Usage
  ------------

```
# ./whohassocket.sh
What process has socket?
Usage: ./whohassocket.sh { all | port >port_num< | pid >proc_id< | user >username< }
# ./whohassocket.sh user korolev
SOCK_TYPE       PROTOCOL        IP      PORT    PID     USER    COMMAND
sockname:       AF_INET6        ::ffff:10.0.2.5 22        577  korolev /usr/lib/ssh/sshd
peername:       AF_INET6        ::ffff:10.77.44.115     3881      577  korolev /usr/lib/ssh/sshd
sockname:       AF_INET6        ::ffff:10.0.2.5 21       6229  korolev in.ftpd -a
peername:       AF_INET6        ::ffff:10.77.44.115     1572     6229  korolev in.ftpd -a
sockname:       AF_INET6        ::ffff:10.0.2.5 21       6229  korolev in.ftpd -a
peername:       AF_INET6        ::ffff:10.77.44.115     1572     6229  korolev in.ftpd -a
sockname:       AF_INET6        ::ffff:10.0.2.5 22      13687  korolev /usr/lib/ssh/sshd
peername:       AF_INET6        ::ffff:10.77.44.115     1484    13687  korolev /usr/lib/ssh/sshd
# ./whohassocket.sh port 22
SOCK_TYPE       PROTOCOL        IP      PORT    PID     USER    COMMAND
sockname:       AF_INET6        ::      22       4240     root /usr/lib/ssh/sshd
sockname:       AF_INET6        ::ffff:10.0.2.5 22      13672     root /usr/lib/ssh/sshd
peername:       AF_INET6        ::ffff:10.77.44.115     1484    13672     root /usr/lib/ssh/sshd
sockname:       AF_INET6        ::ffff:10.0.2.5 22      14062     root /usr/lib/ssh/sshd
peername:       AF_INET6        ::ffff:10.77.44.141     29837   14062     root /usr/lib/ssh/sshd
sockname:       AF_INET6        ::ffff:10.0.2.5 22        577  korolev /usr/lib/ssh/sshd
peername:       AF_INET6        ::ffff:10.77.44.115     3881      577  korolev /usr/lib/ssh/sshd
...```
	

###  Licensing
  ---------
	GNU

###  Contacts
  --------

     o korolev-ia [at] yandex.ru
     o http://www.unixpin.com















	