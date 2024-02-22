# Handshake-Domains---TLD-web-3.0

About Handshake and Namebase
Handshake decentralizes the root DNS zone and improves security of the internet

Handshake
Handshake is a naming protocol that’s backwards compatible with the existing DNS system. It does not replace the DNS protocol, but instead decentralizes the root zone file where TLD ownership information is stored by adding a distributed and decentralized blockchain-based system that no one controls and anyone can use. This allows for a root zone that is uncensorable, permissionless, and free of gatekeepers like ICANN.
Every peer in the Handshake network cryptographically validates and manages the root zone, which completely removes the need for the Certificate Authority system (CAs). Names are logged on the Handshake blockchain, which is essentially one big distributed zone file to which anyone can add an entry.

True name ownership  
In the existing internet infrastructure, no one actually owns their name. Namespaces are controlled by centralized organizations such as ICANN, Verisign, Facebook, Twitter, and Google, who can delete and take away your domain, name, account, and/or identity at will.
Current domain registrars have built their businesses on leasing models, charging website owners an annual fee to rent a subdomain from the registrars' top-level domains. These fees are subject to price hikes and recently ICANN was in the spotlight for approving a deal that would have removed price caps from protected TLDs like .org. Furthermore, if a website is deemed to be harmful, even wrongly, internet service providers can block it, and domain registrars can seize its domain.

Complete control
Handshake name owners have complete control over their data and can use their TLDs as they wish — from simply hosting a website to becoming a registrar that sells subdomains to others. Only name owners can update or transfer their names. As long as name owners control their private keys, because the DNS records are on the decentralized Handshake blockchain, their names cannot be seized or tampered with. And because governance on Handshake is truly decentralized, no one person or entity can make a governance decision that would impact domain owners or the network the same way the ICANN deal would have for .org domain owners. 

Renewal fees
Handshake domain names provide true ownership, which means there are no yearly rental fees. Handshake TLD owners need only submit a biennial "heartbeat transaction" (a mining fee) to prove they still have access to their name. In the event a TLD owner loses access to their name and are unable to submit the RENEW transaction, said name will revert to the "auction-able names" pile. However, if you use Namebase you don't need to remember to perform these transactions because our system does this automatically for you.

Endless top-level domains
At the root of the DNS hierarchy is a file called the root zone where top-level domain ownership info is recorded. This root zone is managed by ICANN, who determines what top-level domains are allowed. In other words, the entire traditional domain name system is controlled at the root by a single entity, ICANN. ICANN charges a $185,000 evaluation fee for new TLD applications, which may or may not get approved, thus artificially restricting the availability of domains for website owners and developers.

Register in the namebase.io
Here you can get acquainted with the domain names offered for sale and divided into thematic sections:

Please bookmark this blog, the list of domains is constantly updated!

Unrestricted
By contrast, anyone can register Handshake names. They are distributed through public decentralized Handshake name auctions that are open to anyone, and the market determines the price of any given TLD, not Namebase, Handshake, or ICANN. 

Any name
Handshake names can be virtually anything, from English letters and decimal numbers to Chinese characters and even emojis! They can be used like a traditional TLD with a subdomain (my.home/, my.家/, my.🏡/) or as a standalone name (home/, 家/, 🏡/). 

Existing domains
All of the ~1,500 TLDs that already exist in the ICANN root zone (e.g. .com, .org, .io) are reserved for backwards-compatibility, and can be claimed by the owners of those names. This means that you can use Handshake domains without disrupting usual access to traditional domains like .com. Additionally, the top 100,000 most visited websites as determined by Alexa are also reserved for their owners (e.g. bitcoin/ on Handshake is set aside for the owner of bitcoin.com, and google/ is set aside for Google). You can see the full list of already claimed Handshake names on dns.live. 
If you own an Alexa top 100k website, you can use these instructions to claim your name.

Unstoppable and private
Although the entire world relies on DNS infrastructure, only a few organizations at the top of the hierarchy control it. The centralized nature of internet names makes it trivial for governments and institutions to censor websites and content through DNS filtering and redirection. Turkish citizens were banned from Wikipedia for almost four years and are still blocked from the encrypted email provider ProtonMail. Iran recently censored Facebook and Twitter before shutting off their Internet entirely, and the services blocked in China are legion, including Facebook, Twitter, and Google.  
The current centralized nature of internet names also results in privacy loss. Even if your domain registrar offers WHOIS protections, your ownership information is stored in centralized databases which can be subpoenaed from a domain registrar. This makes it difficult for people to create politically sensitive websites without compromising their safety. Malicious actors can spy on and tamper with your browsing activity, and DNS providers, including ISPs, can collect and sell your web browsing history. As a workaround, people resort to VPNs and centralized resolvers like Cloudflare’s 1.1.1.1 which can be shut down at any time (and still require trusting the VPNs and resolvers themselves).

Uncensorable
Handshake ensures DNS records can be modified only by the name's owner, which prevents Handshake domains from being censored or maliciously redirected. Handshake DNS data is distributed across all the nodes in its blockchain network instead of being housed on a single centralized server. As long as you can connect to any node in the distributed network, you'll be able to resolve Handshake names, making Handshake names virtually impossible to censor.

Privacy preserving
Your privacy is protected when you register a Handshake domain because no personal information is required. Ownership of names is determined by public-key cryptography, so it’s easy to verify name owners by having them sign a message with their private key. Privacy is a core feature of Handshake names; there is no WHOIS lookup or any other public database where ownership or contact information can be accessed. Unlike traditional domain registrars, Namebase does not charge annual fees to keep your personal details away from prying eyes.
It is possible to register Handshake names on Namebase completely privately without revealing any personal information.

A more secure internet
Browsers trust certificate authorities to prove that websites are who they say they are. However, certificate authorities have sometimes compromised the security of SSL (Secure Sockets Layer is tech that protects transmitted data from being read or modified) by issuing bad certificates or cooperating with governments to spy on and censor traffic. Insecure websites put everyone at risk. Vint Cerf, the “Father of the Internet,” expands on this in his article about self-authenticating identifiers.
Your browser encrypts traffic to websites using TLS (Transport Security Layer), which relies on public key cryptography. Public key cryptography is a method of asymmetric encryption using a pair of keys: a public key and a private key pair (as opposed to symmetric encryption with only one key). The public key is shared publicly and is used to verify signatures. The private key is used to decrypt messages encrypted by the public key. The private key is never shared.
When the browser makes an HTTPS request to Google, it initiates a TLS Handshake with Google and receives Google's public key. The browser then uses Google’s public key to verify that the rest of the messages in the TLS Handshake are initiated by Google, because only Google has the private key for its public key. This way, even if intermediate networks spy on the request, they won't be able to decrypt its contents. If an intermediary routes the request to another server pretending to be Google, the browser will know because that server won't be able to respond to the request.
How do you know that Google's public key is actually Google's? When you make that first request to Google, an intermediate network may have intercepted your request and returned a fake public key for Google. Certificate authorities (CAs) attempt to solve this problem. CAs are trusted third parties that verify the authenticity of public keys for websites. Your operating system ships with a list of vetted CAs by default, and when a website wants to support HTTPS requests, they register their public key with the vetted CAs. You verify that the public key you receive from Google is truly Google's public key by checking it with your CAs.
Hundreds of CAs are installed on your computer by default — Microsoft Windows comes with 390 certificates, and Mac OS X comes with 170 certificates. To browse the web "securely", you must trust all of these CAs plus the many intermediaries to whom they delegate trust. If even a single one of these entities acts maliciously or gets hacked, then all of your HTTPS internet browsing traffic is compromised and vulnerable to MITM (man in the middle) attacks. In the DigiNotar attack, the Iranian government hacked a Dutch CA and used it to MITM attack 300,000 Iranian citizens.

Replacing CAs
Handshake names are their own root of trust and have their TLS keys pinned to themselves. Rather than relying on an arbitrary centralized list of hundreds of certificate authorities to verify public key authenticity, Handshake makes it possible for anyone to verify key authenticity by shifting the root of trust to a cryptographically backed distributed root of trust: its blockchain. Unlike with traditional domains where it takes but a single bad certificate authority to compromise your security, with Handshake it would require the entire Handshake blockchain to be compromised.

Based on the materials of the author of the article. Original article
