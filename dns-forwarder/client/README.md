Once everything is configured there should be answers like:

[vagrant@client ~]$ nslookup first.nhs.uk
Server:         192.168.44.63
Address:        192.168.44.63#53

Name:   first.nhs.uk
Address: 192.0.2.1

[vagrant@client ~]$ nslookup first.gloster.com
Server:         192.168.44.63
Address:        192.168.44.63#53

Non-authoritative answer:
Name:   first.gloster.com
Address: 172.0.2.1
