# DNS-over-HTTPS
Resources for DNS over HTTPS. Encrypted DNS setup and helpful tips. #DOH #Privacy 

Basic knowledge
DNS over HTTPS(DoH) protocol is that the communication is encrypted using built-in application HTTPS standards. It was first introduced in October 2018 (IETF RFC 8484) with a goal of increasing user security and privacy. With DNS over HTTPS (DoH), DNS queries and responses are encrypted and sent via the HTTP or HTTP/2 protocols. DoH ensures that attackers cannot forge or alter DNS traffic. DoH uses port 443, the standard HTTPS traffic port, to wrap the DNS query in an HTTPS request.
<img width="455" alt="image" src="https://user-images.githubusercontent.com/51909803/215741571-81bfe9b1-827a-4c40-a76b-55763c3fc39a.png">

<img width="320" alt="image" src="https://user-images.githubusercontent.com/51909803/215741620-a52a7ade-a17f-4003-b98e-9e3989337856.png">

Pros of DoH
*	Encrypting DNS name resolution traffic helps to hide your online activities.
*	Prevent DNS spoofing and man-in-the-middle (MitM) attacks
*	Protect sensitive information that DNS hijacking methodologies employ and obfuscate data that could be sniffed by third-party observers and ISPs.
*	load time performance is typically improved.


Cons of DoH
*	Overrides any sort of DNS filtering your network is doing to provide insight into security and your network info
*	False-negative security flags and blocked queries can be generated if the system administrator is unfamiliar with DoH or similar protocols


News & Blog post
[Encryption to See Rise in Adoption Across All Verticals](https://www.thefastmode.com/technology-solutions/30042-encryption-to-see-rise-in-adoption-across-all-verticals-according-to-versa-networks-sunil-ravi)
