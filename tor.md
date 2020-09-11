# Tor

Tor is free and open-source software for enabling anonymous communication. 
The name derived from the acronym for the original software project name `The Onion Router`.
Tor directs Internet traffic through a free, worldwide, volunteer overlay network consisting of more than seven thousand relays to conceal a user's location and usage from anyone conducting network surveillance or traffic analysis. 
Using Tor makes it more difficult to trace Internet activity to the user: this includes "visits to Web sites, online posts, instant messages, and other communication forms". 
Tor's intended use is to protect the personal privacy of its users, as well as their freedom and ability to conduct confidential communication by keeping their Internet activities unmonitored.

In penetration testing, there might be a need to conduct a full-fledged black-box test. This is a form of testing in which security professionals have to deal with such things as firewalls and other mechanisms of restriction on the customer’s side.
In this case, the Tor network can be used in order to constantly change IP and DNS addresses and therefore successfully overcome any restrictions


# Installation :

Type in command prompt (make sure you are root user)

> apt-get install tor

# Starting Tor :

>  service tor start

# To check availibility :

> service tor status

# To stop Tor :

> service tor stop
