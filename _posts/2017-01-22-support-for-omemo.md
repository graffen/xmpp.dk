---
title: OMEMO, OTR and GPG suppprt
layout: post
---
The XMPP foundation has begun standardizing the [OMEMO end-to-end encryption protocol][omemo-xep]. Therefore, 
I decided it would be a good time to include support for this interesting new protocol on the xmpp.dk server. 

In practice, this means I have installed a new plugin, mod_e2e_policy, which enables support for the three major
e2e encryption standards on XMPP nowadays, namely OTR (which you already know quite well), OMEMO and OpenPGP/GPG. 

OMEMO provides several advantages over OTR. Among other things, it supports offline messages, group chats (which means
I can also start looking into enabling MUC conferences on the server at some point) and also it does away with 
user-based fingerprints and instead uses device-based keys. This is especially useful if you're connected on multiple
devices simultaneously. As you know, this was problematic with OTR, but with OMEMO you can get end-to-end encryption
on all of your devices and hopefully never lose a message.

As always, if you have any trouble or want to ask questions, you can always [contact me directly](/contact/) over Jabber 
or you can reach out on our [Twitter][twitter]. 


[omemo-xep]:https://conversations.im/omemo/ 
[twitter]:https://twitter.com/xmppdk