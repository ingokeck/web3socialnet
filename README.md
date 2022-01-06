# web3socialnet
a web3 social network built with web1 technologies

# why
The social networks of web2 are clearly broken for their users. The central power of the companies that run them allow then to cancel anyone, to restrict its use, to change the visibility of content as they seem fit.

This is a drastic change from web1, where the user was in power. Or rather the initial idea of the internet - one human, one voice.

# what
Web1 started out with the idea that everyone can host his/ her own content. Everyone is free to write what he/she wants, and everyone is also free to read it or to ignore it. Instead of centralized platforms, web1 and what came before - let's call it the original internet - was all about open protocols, published in RFCs: Requests for comments.

The internet today still depends on technologies previous to web1. Email (SMTP, POP3, IMAP). IRC. DNS. Even HTTP/HTTPS. USENET (NNTP). MIME. You may not know or may not see them, but they are still out there. The big players that got ritch with web2 tried to ursurp them, but in many parts they failed because they were just working too well. So why does it look like web2 has won? Publicity. And the platform effect. The platform effect is massive, but it can sucessfully be fought with open protocols.

# how
Imagine a new decentralized social web. Everyone is his/her own publisher. No-one can censor you, but everyone can decide to read, see or hear your content. Or not to. No central power that decides which voices are to be amplified. Building on open protocols, this is possible. But there is one catch. No central control means no central platform. No free "we take care of everything, just trust us with all your data that we will sell off". That means users will need to run a local client to find and access the content. This is the price to pay for liberty.

What is needed:
* a place where you publish your content. everything is possible, if there is a common way to access it. e.g. if it has an URL
* a way to find content. A decentralized search engine, so that no central censorship is possible.
* a way to get notified of updates. 

What would be nice:
* a messaging system that has small messages with self containing content that is restricted in the possibilities so that it cannot do harm. I.e. small selfcontained html pages that cannot connect to external sources.

# plan
In a first iteration, the system could just be a webscraper, that monitors a set of URLs the user gives it. E.g. a Blog. New content is registerd in an internal database and can be searched. The user may have this content filtered or analyses at will, so that relevant stuff is readily presenten.

In a second iteration, the search enginge database content could be shared between users, so that the effort to build the system is reduced. Content creators should however be able to stop this sharing if their security is at risk. Content may be encrypted. Users may also want to start trusting each other and forward some content in risk of being censored - though that probably should be a thing for dedicated systems like freenet. After all, all you need to access the content is the URL and a key in case of encryption.

In a third iteration, why not include a simple social network microblogging system in it? Small, selfcontained html pages that cannot connect to anything outside. These messages could be again saved on an included distributed file system - freenet, some ipfs clone over i2p, whatever. 

# who benefits
With such a system we could bring discussion and interaction in society back into a censorship safe place on the internet. Basically restore the human rights situation to the level we had in the analogue world. Still, bots can be created and messages can be monitored. But it will be much more difficult if the monitoring powers need to infiltrate every circle to get everything.
