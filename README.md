![GitHub last commit](https://img.shields.io/github/last-commit/hagezi/dns-blocklists)![GitHub issues](https://img.shields.io/github/issues/hagezi/dns-blocklists)![GitHub closed issues](https://img.shields.io/github/issues-closed/hagezi/dns-blocklists)![visitors](https://visitor-badge.glitch.me/badge?page_id=hagezi.dns-blocklists&left_color=grey&right_color=blue)[![shields.io Stars](https://img.shields.io/github/stars/hagezi/dns-blocklists)](https://github.com/hagezi/dns-blocklists/stargazers)
## DNS Blocklists - *For a better internet!*

### ***Multi - Cleans the Internet and protects your privacy!***
*An all in one DNS blocklist in **various versions (light, normal, pro and pro++)**. It can be used as a stand alone blocklist. For every region. Blocks ads, affiliate, tracking, metrics, telemetry, fake, phishing, malware, scam, coins and other "crap". Based on [various blocklists](usedsources.md).*

#### ***Multi blocklist version and size overview:***
| Version | Hosts | Pro | Normal | Light | [Fake](https://github.com/hagezi/dns-blocklists#fake---protects-against-internet-scams-traps--fakes) | [TIF](https://github.com/hagezi/dns-blocklists#threat-intelligence-feeds---increases-security-significantly) | [Bypass](https://github.com/hagezi/dns-blocklists#dohvpntorproxy-bypass---prevent-methods-to-bypass-your-dns) | [Safesearch](https://github.com/hagezi/dns-blocklists#safesearch-not-supported---prevent-the-use-of-search-engines-that-do-not-support-safesearch) | [DDNS](https://github.com/hagezi/dns-blocklists#dynamic-dns-blocking---protects-against-the-malicious-use-of-dynamic-dns-services) | [Personal](https://github.com/hagezi/dns-blocklists#personal---my-manually-maintained-blacklist) | 
|:--------|---:|:------:|:-----:|:----:|:---:|:------:|:----------:|:--------:|:--------:|:--------:|
| [Light](https://github.com/hagezi/dns-blocklists#multi-light---light-protection)             | 207361<br>92134     |   |   | = | X |   |   |   |   | X |
| [Normal](https://github.com/hagezi/dns-blocklists#multi-normal---all-round-protection)       | 919156<br>316812     |   | = | X | X | P |   |   |   | X |
| [Pro](https://github.com/hagezi/dns-blocklists#multi-pro---extended-protection)              | 1279445<br>445873         | = | X | X | X | P |   |   |   | X |
| [Pro++<br>(BETA)](https://github.com/hagezi/dns-blocklists#multi-pro---beta-experimental)    | 1587451<br>594823 | + | X | X | X | X |   |   |   | X |
           
*X = contains the named lists in the column header*       
*P = partially contains the named list in the column header*       
*+ = more sources, more aggressive*
              
---
         
### ***Multi LIGHT*** - **Light protection**
      
**Entries:** *207361 domains/hosts - 92134 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#light)         
         
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/light.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/light.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/light.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/light.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/light.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi NORMAL*** - **All-round protection**
      
**Entries:** *919156 domains/hosts - 316812 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#multi)        
          
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/multi.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/multi.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/multi.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/multi.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/multi.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi PRO*** - **Extended protection**
      
**Entries:** *1279445 domains/hosts - 445873 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#pro)        
           
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi PRO++*** - **BETA (experimental)**

*More aggressive version of the Multi PRO blocklist. It may contain false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains.*

**Entries:** *1587451 domains/hosts - 594823 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#proplus)    
                                                
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.plus.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.plus.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.plus.txt) | ~~AdGuard~~, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.plus.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.plus.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.plus.txt) | DNSCrypt, DNSCloak, YogaDNS, ...  |
                         
**Expires:** *24 hours (update frequency)*

---

### ***Fake - Protects against internet scams, traps & fakes!***
*An blocklist for blocking fake stores, -news, -science, -streaming, rip-offs, cost traps and co.*         
        
**Entries:** *13469 domains/hosts - 7013 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#fake)
       
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/fake.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/fake.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/fake.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/fake.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/fake.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/fake.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Threat Intelligence Feeds - Increases security significantly!***
*An blocklist for blocking malware, crypto, coin, scam, spam and phishing. Blocks domains known to spread malware, launch phishing attacks and host command-and-control servers.*         
        
**Entries:** *399530 domains/hosts - 340290 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#tif)
         
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/tif.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/tif.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/tif.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *24 hours (update frequency)*

---

### ***DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS!***
*An blocklist for blocking DNS over HTTPS, VPN, TOR, Proxies. Prevent method to bypass your DNS. To ensure the bootstrap is your DNS server you must redirect or block standard DNS outbound (UDP 53) and block all DNS over TLS (TCP 853) outbound.*         
        
**Entries:** *950 domains/hosts - 859 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#doh-vpn-proxy-bypass)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/doh-vpn-proxy-bypass.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/doh-vpn-proxy-bypass.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh-vpn-proxy-bypass.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh-vpn-proxy-bypass.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-vpn-proxy-bypass.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Safesearch not supported - Prevent the use of search engines that do not support safesearch!***
*An blocklist for blocking search engines that do not support safesearch.*         
        
**Entries:** *137 domains/hosts - 134 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#nosafesearch)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/nosafesearch.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/nosafesearch.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nosafesearch.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/nosafesearch.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/nosafesearch.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nosafesearch.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Dynamic DNS blocking - Protects against the malicious use of dynamic DNS services!***
*An blocklist for blocking dynamic DNS services to protect against malicious use in phishing campaigns and others.*         
        
**Entries:** *774 domains/hosts - 772 compressed domains* | [Sources](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#dyndns)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/dyndns.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/dyndns.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/dyndns.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/dyndns.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/dyndns.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/dyndns.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Personal - My manually maintained blacklist***
*Contains blockable hosts that I found during DNS monitoring. Ads, Tracking, Badware and more.*         
        
**Entries:** *268 domains/hosts - 187 compressed domains*
       
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/personal.txt) | PiHole, Diversion, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/personal.txt) | PiHole, AdAway, uMatrix, DNS66, GasMask, HostFileEditor              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal.txt) | AdGuard, AdGuard Home, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/personal.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/personal.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/personal.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Credits***

**A huge thank you to the following list maintainers of the [sources used](usedsources.md), alphabetical order:**

*abpindo, abpvn, abuse.ch, adguardteam, adroitadorkhan, amnestytech, assoechap, azorult-tracker.net, badmojr, barbblock, bigdargon, bongochong, botvrij.eu, cert-agid.gov.it, cmiksche, craiu, d3ward, dandelionsprout, davidonzo, developerdan, digitalside.it, drsdavidsoft, durablenapkin, easylist, easylist-lithuania, easylist-thailand, elliotwutingfeng, fademind, firebog.net, frogeye.fr, guardicore, hexxiumcreations, hole.cert.pl, hoshsadiq, hpthreatresearch, iam-py-test, infinitytec, jawz101, jkrejcha, joewein.net, kargig, kevinthomas0, kriskintel.com, laicure, laniksj, lassekongo83, latvian-list, malware-filter, marco-acorte, matomo-org, metamask, mitchellkrogza, netlab.360, nextdns, nitrohorse, notonmyshift, notracking, oisd.nl, olbat, oneoffdallas, paulgb, perflyst, phishing.army, piperun, polishfiltersteam, prodaft, quidsup, rescure.me, scafroglia93, shadowwhisperer, sjhgvr, stamparm, stanev.org, stevenblack, stopforumspam.com, systemjargon, t145, th3m3, tomasko126, ublockorigin, ultimate-hosts, wally3k, zerodot1, zoso.ro*

---

<p align="center"><a href="https://github.com/hagezi/dns-blocklists/graphs/contributors"><img src="https://contrib.rocks/image?repo=hagezi/dns-blocklists" /></a></p>
<p align="center"><i><b>"If the plan doesn‘t work, change the plan but never the goal."<br>There's no place like 127.0.0.1!</b></i></p>

*The blocklists were created for personal, private use and are based on [various sources](usedsources.md). They were designed to avoid [false positive domains](whitelist.txt) as much as possible and not to block any needed features. [Dead hosts](deadlist.txt) are regularly removed from the lists to keep them as small as possible. Please [report false positive](https://github.com/hagezi/dns-blocklists/issues) domains.*
                        
***If you like the project and you can benefit from it, leave a star (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)!***
         
<a href="https://www.buymeacoffee.com/hagezi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="30" width="163"></a>
         
***Thanks for your support!***

---

### ***Keep the internet clean!*** - Join the Matrix: [#dnsblocklists:matrix.org](https://matrix.to/#/#hagezi:matrix.org)

---
