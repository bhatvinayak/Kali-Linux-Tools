# Metasploit

The Metasploit Project is a computer security project that provides information about security vulnerabilities and aids in penetration testing and IDS signature development.
The console lets you do things like scan targets, exploit vulnerabilities, and collect data.

* To start the metasploit :

Type in the terminal

> msfconsole

* For help :

> help

* To view the options for a module :

> info <module name>
  
* Finding modules :

      Modules are the core components of the Metasploit Framework. A module is a piece of software that can perform a specific action, such as scanning or exploiting. Each task that you can perform with the Metasploit Framework is defined within a module.

There are a few types of modules. The module type depends on the purpose of the module and the type of action that the module performs. The following are module types that are available in the Metasploit Framework:

* Exploit :

      An exploit module executes a sequence of commands to target a specific vulnerability found in a system or application. An exploit module takes advantage of a vulnerability to provide access to the target system. Exploit modules include buffer overflow, code injection, and web application exploits.

* Auxiliary :

      An auxiliary module does not execute a payload. It can be used to perform arbitrary actions that may not be directly related to exploitation. Examples of auxiliary modules include scanners, fuzzers, and denial of service attacks.
      
* Post Exploitation :

      A post-exploitation module enables you to gather more information or to gain further access to an exploited target system. Examples of post-exploitation modules include hash dumps and application and service enumerators.

* Payload :

      A payload is the shell code that runs after an exploit successfully compromises a system. The payload enables you to define how you want to connect to the shell and what you want to do to the target system after you take control of it. A payload can open a Meterpreter or command shell. Meterpreter is an advanced payload that allows you to write DLL files to dynamically create new features as you need them.

*NOP generator :

      A NOP generator produces a series of random bytes that you can use to bypass standard IDS and IPS NOP sled signatures. Use NOP generators to pad buffers.
