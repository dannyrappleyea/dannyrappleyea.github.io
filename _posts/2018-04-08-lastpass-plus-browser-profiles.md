---
layout: post
title: LastPass Identities + Browser profiles = Awesomeness
tags: security
comments: true
---

Using LastPass Identities with browser profiles (either Chrome People or Firefox profiles) can help keep online identities separate, and possibly safer in the event of a web attack.

It's a security best practice to keep passwords in a password vault, so passwords can be long and (hopefully) uncrackable. Many of mine are in LastPass for its sheer convenience.

But I like to keep online identities separate, using different browser profile for each part of my life. Each has a different set of passwords that I'd like to keep up with. For example:
* Personal
* Professional
* Financial
* Gaming
* Untrusted

Using LastPass Identities, I can. It's mostly seamless, with a few annoying bits, but awesome anyway. I haven't found another article describing this, so am throwing it out there to encourage everyone to try something similar.

I'm showing this using Chrome People, cause I tend to use Chrome. But it works with Firefox profiles, or even using a different browser for different identity.

<!--more-->

# What are Chrome People?
It's a way to have separate browser profiles, typically so two or more people can share a computer. Each has it's own set of cookies, history, browser extensions, etc. Chrome browser security isolates "people" so even going to bad or insecure web pages should prevent a computer hack from spreading beyond that person. (Disclaimer: Chrome security is amazingly good, but not perfect.)

[Share Chrome with others - Google Chrome Help](https://support.google.com/chrome/answer/2364824?hl=en)

# What are LastPass Identities?
A way for LastPass to store separate sets of passwords under one account. It's nice if you want to pay for LastPass once.

[LastPass - What are identities?](https://lastpass.com/support.php?cmd=showfaq&id=7366)

[LastPass - Using Folders for Organization](https://helpdesk.lastpass.com/your-lastpass-vault/grouping-sites/#h5)

# Using them together
I'm putting the quick instructions here. You can use the Chrome and LastPass links above to get additional details.

1. Create a new Chrome person / profile. [Google Chrome Help](https://support.google.com/chrome/answer/2364824?hl=en)
1. Install LastPass for your browser. [Download LastPass](https://lastpass.com/download)
1. Create a LastPass identity. [LastPass Identities](https://helpdesk.lastpass.com/your-lastpass-vault/grouping-sites/#h5)
1. Move any passwords over. [LastPass Identities](https://helpdesk.lastpass.com/your-lastpass-vault/grouping-sites/#h5)
1. Switch your identity from All to the newly created one. [LastPass Identities](https://helpdesk.lastpass.com/your-lastpass-vault/grouping-sites/#h5)

Here's what it looks like after you're set up. The Chrome person matches the LastPass identity.

![LastPass vault using personal identity](/assets/2018-04-07-lastpass-plus-browser-profiles/lastpass_personal.png)

# Helpful Hints
* I've made folders in LassPass for each identity, then subfolders for organization. Moving passwords between identities has an awkward interface, and this helps.

* Once you're using an identity, creating a new password automatically goes in that identity. If you're just starting with LastPass, create identities first, then add passwords.

* Making one more profile that logged into all LastPass identities may be useful to help keep things organized.

# The Rough Bits

* You'll have to login to Lastpass once for each person. With mutifactor turned on, trusting the computer, this means once every 30 days.

* There's no way to look at a password in LastPass and tell which identities it's in. You have to go into each identity and move things around. Grouping the passwords in folders first helps.

# FAQs

**Can I use Firefox profiles?**

I love Firefox profiles, even though it's rather a pain to use in practice

[Use the Profile Manager to create and remove Firefox profiles](https://support.mozilla.org/en-US/kb/profile-manager-create-and-remove-firefox-profiles)

**What about Firefox Multi-Account Containers**

Looks interesting. Cookies are separated into "containers" but other things like addons aren't. Haven't tried it with LastPass yet.

[Firefox Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)
