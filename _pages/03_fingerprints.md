---
layout: page
title: Fingerprints
permalink: /fingerprints/
---

I'll try to keep the fingerprints on this page up-to-date to within about a day or two
of them being updated on the server. If you're connecting through Tor you'll get a 
security warning pop up around once every 3 months, when the LetsEncrypt certificate 
expires and is renewed. If I haven't updated the fingerprint on this page, you can 
check the fingerprint in your browser and compare that with what the XMPP server is
reporting. They should be identical. 
 
OTR Fingerprint: graffen.dk/Qubes: `{{ site.fingerprints.otr }}`

TLS certificate for this site and the XMPP server is issued by [LetsEncrypt][LetsEncrypt] to _triton.xmpp.dk_
 
SHA-256: 

> `{{ site.fingerprints.tls.sha-256 }}`

SHA-1:   

> `{{ site.fingerprints.tls.sha-1 }}`

Expiry (dd/mm/yy): 29/03/2017

[LetsEncrypt]: https://www.letsencrypt.org
