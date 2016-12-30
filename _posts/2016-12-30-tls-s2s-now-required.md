---
title: TLS is now required for S2S connections
layout: post
---

Coming to the end of 2016 I've been really happy with how much traffic this service is receiving. As I don't log anything, I haven't really 
got a way to see exactly how much you guys have been chatting through xmpp.dk. But I can see from the traffic stats that the server is at least
generating a fair amount of traffic so that's awesome!  
  
Since we are at the end of 2016 and there is an ever-growing push for more and more privcay, I have decided that now is the time to take the next step.
Up until now, the server has been configured to _prefer_ but not _require_ TLS when connecting to other XMPP servers. That means that even though OTR is 
required and your messages aren't being transmitted in cleartext, the XMPP messages themselves might have been.  
But from today, the server's configuration has been changed so that TLS is now a _full requirement_ when another XMPP server wants to connect to us.  
  
This decision does come with some problems, however. There are _lots_ of XMPP servers out there that do not support TLS. Unfortunately, this means that you 
as a user will no longer be able to talk to people who use these servers.  
  
If you're having trouble reaching some of your contacts now, you should either get your friends to persuade their providers to start using TLS for everyone's 
increased privacy, or talk your friends into switching to a provider that already does. There are lots of free Jabber servers out there that do support 
encrypted communications, so take a look at [xmpp.net][xmppnet] and look for servers that have at least an "A" grade in both C2S (client-to-server) and S2S (server-to-server).  
  
Happy new year everyone!  
  
/Graffen


[xmppnet]: https://xmpp.net/directory.php