# PersonalPiholeListsPAllebone

Note: If you think I am missing any good lists, please let me know so I can add them :)

I have a list of over 8 million domains being blocked by adding each of the lists below. Primarily this list is to protect users from accessing sites that are dangerous. An allowlist is required when using all the lists as domains get blocked that are valid/needed by users on the network. An allowlist can be found at the end as a suggested allowlist to start with if you would like to avoid starting from scratch (If you dont use this expect to be in for a painful experience). This is for convenience and if you are happy to start with nothing thats fine too. My list has many common entries to save you time and updated reguarly. It unblocks things so that they work, and is less concerned with being tracked and more concerned with ensuring users are safe on the network from malicious sites/actors. If privacy is your primary concern rather than security, then just dont use the suggested allowlist and manage your own from scratch. For example, using my whitelist does make youtube work correctly, but I see adverts on youtube (banners and video ads sometimes) so obviously some functionality of the site is tied to domains I whitelisted. I dont know how to stop that and Im not overly concerned. I do worry about evil sites and want to block those however. If you need sites users might use to function, with blocking of most ads and malicious sites, and with privacy when it does not break things, then the suggested allowlist is fine to use to begin with and will save you a months work finding everything yourself that general users use on a network. You can then just add more as appropriate as time goes on. It normally takes about a month (actually in my own testing longer to be fair and tedious) or so to find all the bits and bobs users use if you start from nothing and allow sites as they crop up. If you want everything locked down and can manage the initial allowlist yourself then just use the blocklists and add users slowly to the filtering as mentioned.

In addition there is some IP lists for use on your firewalls to block users who attempt to circumvent the internal DNS with brief explanation on how to reroute/redirect DNS requests and log on the firewalls anyone who changes their DNS server, uses DOT, DOH, any other weird stuff they try etc and flag up in the firewall logs so the users can be reviewed and investigated. These lists and instructions are listed after the allowlist.


## Blocklists

https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt

https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt

https://v.firebog.net/hosts/static/w3kbl.txt

https://adaway.org/hosts.txt

https://v.firebog.net/hosts/AdguardDNS.txt

https://raw.githubusercontent.com/anudeepND/blacklist/master/adservers.txt

https://v.firebog.net/hosts/Easylist.txt

https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts

https://v.firebog.net/hosts/Easyprivacy.txt

https://v.firebog.net/hosts/Prigent-Ads.txt

https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt

https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt

https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt

https://s3.amazonaws.com/lists.disconnect.me/simple_malvertising.txt

https://bitbucket.org/ethanr/dns-blacklists/raw/8575c9f96e5b4a1308f2f12394abd86d0927a4a0/bad_lists/Mandiant_APT1_Report_Appendix_D.txt

https://phishing.army/download/phishing_army_blocklist_extended.txt

https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt

https://v.firebog.net/hosts/Shalla-mal.txt

https://gitlab.com/curben/urlhaus-filter/raw/master/urlhaus-filter-hosts.txt

https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt

https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-gambling-porn/hosts

https://raw.githubusercontent.com/notracking/hosts-blocklists/master/hostnames.txt

https://block.energized.pro/extensions/porn-lite/formats/hosts

https://block.energized.pro/blu/formats/hosts

https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&mimetype=plaintext

https://block.energized.pro/unified/formats/hosts

https://raw.githubusercontent.com/oneoffdallas/dohservers/master/list.txt

https://raw.githubusercontent.com/Sekhan/TheGreatWall/master/TheGreatWall.txt (Last update June 2020... new list needed if replacement can be found).

https://block.energized.pro/spark/formats/hosts

https://block.energized.pro/bluGo/formats/hosts

https://block.energized.pro/basic/formats/hosts

https://block.energized.pro/porn/formats/hosts

https://block.energized.pro/ultimate/formats/hosts

https://block.energized.pro/extensions/xtreme/formats/hosts

https://block.energized.pro/extensions/regional/formats/hosts

https://raw.githubusercontent.com/llacb47/mischosts/master/social/tiktok-block

https://raw.githubusercontent.com/llacb47/mischosts/master/tiktok-hosts

https://justdomains.github.io/blocklists/lists/easylist-justdomains.txt

https://justdomains.github.io/blocklists/lists/easyprivacy-justdomains.txt

https://justdomains.github.io/blocklists/lists/adguarddns-justdomains.txt

https://justdomains.github.io/blocklists/lists/nocoin-justdomains.txt

https://github.com/marcusminus/Orthrus-BlockList/raw/master/hosts.txt

https://www.github.developerdan.com/hosts/lists/tracking-aggressive-extended.txt

https://raw.githubusercontent.com/durablenapkin/scamblocklist/master/hosts.txt

https://raw.githubusercontent.com/smed79/blacklist/master/hosts.txt

https://raw.githubusercontent.com/notracking/hosts-blocklists/master/dnscrypt-proxy/dnscrypt-proxy.blacklist.txt

https://raw.githubusercontent.com/mkb2091/blockconvert/master/output/domains.txt

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Ads

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Adult

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Malware

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Risk

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Scam

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Tracking

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Tunnels

https://raw.githubusercontent.com/tg12/pihole-phishtank-list/master/list/phish_domains.txt

https://anti-ad.net/domains.txt

https://raw.githubusercontent.com/Amdromeda/Blocklist-Pi-Hole/master/Ads%20and%20trackers.txt

https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts

https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt

https://someonewhocares.org/hosts/zero/hosts

https://winhelp2002.mvps.org/hosts.txt

https://v.firebog.net/hosts/neohostsbasic.txt

https://raw.githubusercontent.com/RooneyMcNibNug/pihole-stuff/master/SNAFU.txt

https://paulgb.github.io/BarbBlock/blacklists/hosts-file.txt

https://v.firebog.net/hosts/Admiral.txt

https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext

https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts

https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts

https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts

https://hostfiles.frogeye.fr/firstparty-trackers-hosts.txt

https://hostfiles.frogeye.fr/multiparty-trackers-hosts.txt

https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt

https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt

https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/AmazonFireTV.txt

https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt

https://v.firebog.net/hosts/Prigent-Crypto.txt

https://raw.githubusercontent.com/Spam404/lists/master/main-blacklist.txt

https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts

https://urlhaus.abuse.ch/downloads/hostfile/

https://v.firebog.net/hosts/Prigent-Malware.txt

https://raw.githubusercontent.com/HorusTeknoloji/TR-PhishingList/master/url-lists.txt

https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser

https://raw.githubusercontent.com/chadmayfield/my-pihole-blocklists/master/lists/pi_blocklist_porn_all.list

https://gitlab.com/The_Quantum_Alpha/the-quantum-ad-list/-/raw/master/For%20hosts%20file/The_Quantum_Ad-List.txt

https://blocklist.cyberthreatcoalition.org/vetted/domain.txt

https://raw.githubusercontent.com/sk-cat/fluffy-blocklist/main/domains

https://blocklistproject.github.io/Lists/abuse.txt

https://blocklistproject.github.io/Lists/ads.txt

https://blocklistproject.github.io/Lists/crypto.txt

https://blocklistproject.github.io/Lists/drugs.txt

https://blocklistproject.github.io/Lists/fraud.txt

https://blocklistproject.github.io/Lists/gambling.txt

https://blocklistproject.github.io/Lists/malware.txt

https://blocklistproject.github.io/Lists/phishing.txt

https://blocklistproject.github.io/Lists/porn.txt

https://blocklistproject.github.io/Lists/ransomware.txt

https://blocklistproject.github.io/Lists/scam.txt

https://blocklistproject.github.io/Lists/tiktok.txt

https://blocklistproject.github.io/Lists/tracking.txt

https://raw.githubusercontent.com/kboghdady/youTube_ads_4_pi-hole/master/youtubelist.txt

https://raw.githubusercontent.com/tg12/pihole-phishtank-list/master/full_grav_list/gravity.txt

https://hosts.oisd.nl/

https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt

https://raw.githubusercontent.com/llacb47/mischosts/master/blacklist

https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt

https://raw.githubusercontent.com/MetaMask/eth-phishing-detect/master/src/hosts.txt

https://raw.githubusercontent.com/neodevpro/neodevhost/master/host

https://raw.githubusercontent.com/ookangzheng/blahdns/master/hosts/blacklist.txt

https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/malware/domains

https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/doh/domains (Possible replacement for GreatWall).

https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts

https://raw.githubusercontent.com/dibdot/DoH-IP-blocklists/master/doh-domains.txt (Possible replacement for GreatWall).

https://raw.githubusercontent.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites/master/hosts

https://raw.githubusercontent.com/ftpmorph/ftprivacy/master/blocklists/smartphone-ads-tracking.txt

https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt

https://raw.githubusercontent.com/CleanMachine1/AdlistTXTS/main/list.txt

https://raw.githubusercontent.com/cbuijs/accomplist/master/doh/plain.black.hosts.list

https://raw.githubusercontent.com/cbuijs/accomplist/master/doh/optimized.black.domain.list

https://raw.githubusercontent.com/cbuijs/accomplist/master/malicious-dom/plain.black.domain.list

https://raw.githubusercontent.com/cbuijs/accomplist/master/oisd/plain.black.top-n.domain.list

https://raw.githubusercontent.com/cbuijs/accomplist/master/family-safe/plain.black.top-n.domain.list

https://raw.githubusercontent.com/cbuijs/accomplist/master/doh/plain.black.top-n.domain.list

https://raw.githubusercontent.com/badmojr/1Hosts/master/Pro/domains.txt

https://raw.githubusercontent.com/stamparm/aux/master/maltrail-malware-domains.txt

https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/fake.txt

https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/multi.txt

https://gitlab.com/andryou/block/raw/master/senpai-strict-domains

https://www.stopforumspam.com/downloads/toxic_domains_whole.txt

https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/newhosts-final.hosts

https://raw.githubusercontent.com/TheAntiSocialEngineer/AntiSocial-BlockList-UK-Community/main/UK-Community.txt

https://raw.githubusercontent.com/Clefspeare13/pornhosts/master/127.0.0.1/hosts

https://kriskintel.com/feeds/ktip_covid_domains.txt

https://kriskintel.com/feeds/ktip_malicious_domains.txt

http://phishing.mailscanner.info/phishing.bad.sites.conf

https://raw.githubusercontent.com/matomo-org/referrer-spam-list/master/spammers.txt

https://rescure.me/covid.txt

https://rescure.me/rescure_domain_blacklist.txt

https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/extra.txt

https://raw.githubusercontent.com/mypdns/porn-records/master/submit_here/adult.mypdns.cloud/domains.list

https://raw.githubusercontent.com/mypdns/porn-records/master/submit_here/adult.mypdns.cloud/hosts.list

https://raw.githubusercontent.com/mypdns/porn-records/master/submit_here/adult.mypdns.cloud/mobile.list

https://raw.githubusercontent.com/mypdns/porn-records/master/submit_here/adult.mypdns.cloud/snuff.list

https://raw.githubusercontent.com/mypdns/porn-records/master/submit_here/adult.mypdns.cloud/wildcard.list

https://raw.githubusercontent.com/mypdns/porn-records/master/submit_here/adult.mypdns.cloud/wildcard.rpz-nsdname

https://raw.githubusercontent.com/KitsapCreator/pihole-blocklists/master/ads.txt

https://raw.githubusercontent.com/KitsapCreator/pihole-blocklists/master/general.txt

https://raw.githubusercontent.com/KitsapCreator/pihole-blocklists/master/malware-malicious.txt

https://raw.githubusercontent.com/KitsapCreator/pihole-blocklists/master/scam-spam.txt

https://raw.githubusercontent.com/Bon-Appetit/porn-domains/master/block.txt

https://raw.githubusercontent.com/iam-py-test/my_filters_001/main/Alternative%20list%20formats/antimalware_domains.txt

https://orca.pet/notonmyshift/hosts.txt


Blocklist list section complete. 152 entries.

## Allowlist:

Please open AllowlistOptional.txt in files above and add these entries to pihole if appropriate.

How to add all in addition to what you already have:

Copy list to notepad++

Remove carridge returns and replace with a space by finding '\r\n' (do not include ' in search) and replacing with a single space.

Notepad++ now has a list of domains with a space between each entry.

Copy this to clipboard. 

On pihole run command 'pihole -w -nr PastedListOfDomainsFromClipboard'

PastedListOfDomainsFromClipboard is the list you copied to your clipboard. Allowlist now has all entries added.  
 

## other stuff etc to be continued as I get time...sorry I have a day job.

Setup Overview

Client DNS set to PIHOLE ---> Pihole DNS set to OPNsense Firewall with relevant forwarders for domain etc configured (if using AD) ---> Opnsense DNS set to 1.1.1.2 and 1.0.0.2 (cloudflare DNS with malware blocking).
A seperate windows DNS (AD) server is on the network that can resolve AD DNS for internal clients. This has pihole as a forwarder and itself as DNS/other AD controllers as per normal.

Typical workflow will be client - pihole - relevant DNS (either ADDNS server or firewall depending on domain/rdns queried). 

This setup allows normal internal DNS while also providing pihole blocking and in addition the firewall DNS is filtered for malware by cloudflare.

A firewall rule only allows DNS ports 53, and 853 from 2 machines - the Pihole and itself on the LAN interface.

More to follow....


IP Blocklists for DOH blocking (add to opnsense):

https://raw.githubusercontent.com/dibdot/DoH-IP-blocklists/master/doh-ipv4.txt

https://raw.githubusercontent.com/Sekhan/TheGreatWall/master/TheGreatWall_ipv4

https://raw.githubusercontent.com/oneoffdallas/dohservers/master/iplist.txt

https://raw.githubusercontent.com/jpgpi250/piholemanual/master/DOHipv4.txt

https://raw.githubusercontent.com/cbuijs/accomplist/master/doh/plain.black.ip4cidr.list

Manual added DOH IP's:
1.1.1.1,1.0.0.1,1.1.1.2,1.0.0.2,1.1.1.3,1.0.0.3,104.17.64.4,104.17.65.4,203.107.1.4,193.161.193.99

Manuak added DOH ranges:
101.36.166.0/24,203.107.1.0/24

Unfortunatly some DOH IP's also serve other traffic (CDN or other services etc). This means you most probably will want a Allowlisting rule that allows out clients on the network to certain ip/ports that are blocked via the IP blocklists above.
On my opnsense I have a rule for each port/service (EG: Allow out LAN NET to allowlisted IP on port 443).

This is the ip/port combination I have so far:

Allow out port 443: 
151.101.66.133,
151.101.2.133,
151.101.130.133,
172.67.75.103,
104.26.2.13,
185.199.108.153,
185.199.109.153,
185.199.110.153,
185.199.111.153,
104.26.3.13,
151.101.194.133,
216.239.34.21,
44.235.246.155,
151.101.65.195,
104.26.4.174,
172.67.70.80,
104.21.39.13,
172.67.170.203,
151.139.128.10,
104.26.5.174,
151.101.1.195,
141.193.213.21,
172.67.212.2,
104.21.85.239,
44.236.72.93,
104.16.132.229,
141.193.213.20,
217.64.148.8,
104.21.68.104,
96.126.123.244,
45.33.20.235,
44.236.48.31,
216.239.36.21

Allow out port 123:
69.1.1.251,
129.250.35.250,
129.250.35.251,
162.248.241.94,
194.36.144.87,
95.216.24.230,
45.76.113.31,
94.16.114.254

Allow out port 80:
151.101.66.133,
151.101.194.133,
151.101.2.133,
151.101.130.133,
141.193.213.20,
172.67.70.80,
104.26.4.174,
184.168.131.241

Obviously this will allow out to these IP's in order to fix certain webpages/other services loading at the expense of potentially blocking a DOH server. Your call if you want functionality over security. 
If you use a second (or more) layer to capture DOH (eg: sensei) then this can be done as your second layer of prevention should hopefully capture it.

----End----
