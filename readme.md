# Public network-Info  

For safe keeping, education and maybe someone needs it?  


## DNSBL blocklist-feeds


### What is it?
Lists with ip-addresses/urls/domains that are 
https://en.wikipedia.org/wiki/Domain_Name_System-based_Blackhole_List  


### Why use it?  
Block the bad stuff that exist on internet.  


### Inspiration  

https://supratim-sanyal.blogspot.com/2017/04/pfsense-pfblockerng-ultimate-list-of-ip.html


### Lists


#### Level 1 - General  

https://someonewhocares.org/hosts/hosts  
https://raw.githubusercontent.com/firehol/blocklist-ipsets/master/firehol_level1.netset  
https://rules.emergingthreats.net/blockrules/compromised-ips.txt  
https://rules.emergingthreats.net/fwrules/emerging-Block-IPs.txt  
http://www.abuseat.org/iotcc.txt  
https://raw.githubusercontent.com/firehol/blocklist-ipsets/master/cybercrime.ipset  
https://raw.githubusercontent.com/Dawsey21/Lists/master/main-blacklist.txt  
http://s3.amazonaws.com/lists.disconnect.me/simple_malvertising.txt  


#### Level 2 - Malware/cybercrime  

https://raw.githubusercontent.com/firehol/blocklist-ipsets/master/firehol_level2.netset  
http://cinsscore.com/list/ci-badguys.txt  
https://feodotracker.abuse.ch/downloads/ipblocklist.txt  
https://www.malwaredomainlist.com/hostslist/ip.txt  
https://openphish.com/feed.txt  


#### Level 3 - Outgoing (Only outgoing traffic allowed)  

https://raw.githubusercontent.com/firehol/blocklist-ipsets/master/firehol_level3.netset  
http://danger.rulez.sk/projects/bruteforceblocker/blist.php  
https://lists.blocklist.de/lists/all.txt  


#### Level 4 - Ads  

https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt  
https://pgl.yoyo.org/adservers/serverlist.php?hostformat=;showintro=0  
http://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt  
http://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt  
http://sysctl.org/cameleon/hosts  


#### Level 5 - Aggressive (may contain lists that give a lot of false positives)  

https://raw.githubusercontent.com/firehol/blocklist-ipsets/master/firehol_level4.netset  
