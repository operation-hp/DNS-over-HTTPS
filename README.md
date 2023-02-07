# DNS-over-HTTPS
Resources for DNS over HTTPS. Encrypted DNS setup and helpful tips. #DOH #Privacy 

# Contents
* [Basic knowledge](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#basic-knowledge)
* [News & Blog post](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#news--blog-post)
* [Set-up on devices](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#set-up-on-devices)
    1. On Browsers
        -	[Firefox](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#firefox)
        -	[Chrome](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#chrome)
        -   [Edge](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#edge)
    2. On Operating Systems
        -	[Windows 10](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#windows-10)
        -	[Androids](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#androids)
        -   [IOS](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#ios)
        -   [Openwrt](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#ios)
    3.	Own DNS-over-HTTPS (DoH) server (Open Source)
* [Useful Websites](https://github.com/operation-hp/DNS-over-HTTPS/edit/main/README.md#useful-website)



## Basic knowledge
DNS over HTTPS(DoH) protocol is that the communication is encrypted using built-in application HTTPS standards. It was first introduced in October 2018 (IETF RFC 8484) with a goal of increasing user security and privacy. With DNS over HTTPS (DoH), DNS queries and responses are encrypted and sent via the HTTP or HTTP/2 protocols. DoH ensures that attackers cannot forge or alter DNS traffic. DoH uses port 443, the standard HTTPS traffic port, to wrap the DNS query in an HTTPS request.

<img width="455" alt="image" src="https://user-images.githubusercontent.com/51909803/215741571-81bfe9b1-827a-4c40-a76b-55763c3fc39a.png">

<img width="320" alt="image" src="https://user-images.githubusercontent.com/51909803/215741620-a52a7ade-a17f-4003-b98e-9e3989337856.png">

### Pros of DoH
*	Encrypting DNS name resolution traffic helps to hide your online activities.
*	Prevent DNS spoofing and man-in-the-middle (MitM) attacks
*	Protect sensitive information that DNS hijacking methodologies employ and obfuscate data that could be sniffed by third-party observers and ISPs.
*	load time performance is typically improved.


### Cons of DoH
*	Overrides any sort of DNS filtering your network is doing to provide insight into security and your network info
*	False-negative security flags and blocked queries can be generated if the system administrator is unfamiliar with DoH or similar protocols


## News & Blog post

* [Encryption to See Rise in Adoption Across All Verticals](https://www.thefastmode.com/technology-solutions/30042-encryption-to-see-rise-in-adoption-across-all-verticals-according-to-versa-networks-sunil-ravi)
* [What Is Encrypted DNS? 4 Top Providers to Improve Online Privacy and Security](https://www.makeuseof.com/what-is-encrypted-dns-top-4-providers-to-improve-online-privacy-and-security/)
* [DNS Over HTTPS: Facts You Should Know](https://securityboulevard.com/2022/05/dns-over-https-facts-you-should-know/)
* [Android 13 finally adds native support for DNS over HTTPS](https://www.xda-developers.com/android-13-dns-https-support/)
* [DNS Over HTTPS: 3 Strategies for Enterprise Security Monitoring](https://insights.sei.cmu.edu/blog/dns-over-https-3-strategies-for-enterprise-security-monitoring/)

## Set-up on devices
### On Browsers
#### Firefox
[Firefox DNS-over-HTTPS](https://support.mozilla.org/en-US/kb/firefox-dns-over-https)  Guideline by Firefox Official website 
##### Chrome
[Enable DNS Over HTTPS (DoH) in Chrome](https://www.technipages.com/enable-dns-https-chrome)  Guidelines for enabling DoH in Chrome by technipages.com.
#### Edge
[Enable DoH in Microsoft Edge](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/#:~:text=%E2%80%8B%E2%80%8B%20Microsoft%20Edge,Select%20Choose%20a%20service%20provider.)  Guidelines provided by Cloudflare

### On Operating Systems
#### Windows 10
[Enabling DNS over HTTPS via Windows 10 Settings](https://heimdalsecurity.com/blog/dns-over-https-doh/)  Guidelines of setting up DoH in Windows 10
#### Androids
[Android set up DoH](https://www.androidpolice.com/android-dns-over-https-mainline/) - Guidelines of setting up DoH in Android
#### IOS
[IOS set up DoH](https://support.quad9.net/hc/en-us/articles/360057889591-Setup-iOS-DNS-over-HTTPS-or-DNS-over-TLS)  Guidelines of setting up DoH in IOS  by Quad9
[encrypted-dns-configs](https://github.com/paulmillr/encrypted-dns)  – Configuration file of DoH in IOS provided by Github
#### Openwrt
[Method for setting up DoH on OpenWrt](https://openwrt.org/docs/guide-user/services/dns/doh_dnsmasq_https-dns-proxy)  It describes the method for setting up DNS over HTTPS on OpenWrt.

### Own DNS-over-HTTPS (DoH) server (Open Source) 
[DNS-over-HTTPS in Github](https://github.com/m13253/dns-over-https)  Guidelines for setting up your own DoH server.
[DNS Proxy Server](https://github.com/AdguardTeam/dnsproxy)  DNS proxy server that supports DNS protocols including DNS-over-TLS, DNS-over-HTTPS.

## Useful Website
* [APNIC](https://www.apnic.net/) - Regional Internet Registry administering IP addresses for the Asia Pacific
* [ITECHTICS](https://www.itechtics.com/) - Technology blog focusing on Windows news and updates, latest downloads, software tips and tricks, and troubleshooting guides.
* [Cloudflare](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/) - One of the world's largest networks that powers more than 10 trillion requests per month.
* [Security Boulevard](https://securityboulevard.com/) - Serve the security and related communities by providing a single destination for information, education and discourse on the leading topics and issues facing the security
* [Microsoft Learn](https://learn.microsoft.com/en-us/)
* [Google Public DNS](https://developers.google.com/speed/public-dns)

