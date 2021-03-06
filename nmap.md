# NMAP

Nmap is a free and open-source network scanner created by Gordon Lyon. Nmap is used to discover hosts and services on a computer network by sending packets and analyzing the responses. Nmap provides a number of features for probing computer networks, including host discovery and service and operating system detection.
[Official website](https://nmap.org/)

## Syntax

> # nmap [scan_type] [options] target_specification

## First we'll take a look at `target_specification` :

* With the IP :

 > nmap IP

* With range of IP :

> nmap IP/subnet_mask

* Multiple IP :

> nmap IP1, IP2, IP3 ...

## Now it's time for `scan_type` :

* No port scan :

> nmap -sn IP

* No ping scan :

> nmap -Pn IP

* TCP SYN Scan :

> nmap -sS IP

* TCP connect scan :

> nmap -sT IP

* UDP scan :

> nmap -sU IP


## At last we are looking at `options` :

* Only scan specified ports :

> nmap -p <port ranges> IP
 
* Fast (limited port) scan :

> nmap -F IP

* Aggressive Scan :

> nmap -A IP

* Version detection :

> nmap -sV IP

* Enable OS detection :

> nmap -o IP

* Script scan using the default set of scripts :

> nmap -sC IP

* Spoof source address :

> nmap -S IP_Address_to_spoof Target_IP

* For Help :

> nmap -h

