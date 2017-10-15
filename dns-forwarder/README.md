Architecture:

192.168.44.61 (dns-gloster.com) <---------> 192.168.44.62 (dns-forwarder) <---------> 192.168.44.63 (dns-nhs-uk) <---------> 192.168.44.60 (client)

Commands:

sudo yum install bind
sudo yum install bind-utils
sudo netstat -tunap
sudo systemctl start named
sudo tcpdump -vv -x -X -s 1500 -i eth1 'port 53'
