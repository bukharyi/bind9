# bind9 enabling dnsupdate

https://wiki.debian.org/DDNS
http://agiletesting.blogspot.my/2014/12/dynamic-dns-updates-with-nsupdate-new.html

modify the bind9 to run as root inside e.g. 
  ExecStart=/usr/sbin/named -f -u root -4
