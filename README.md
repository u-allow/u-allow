# uAllow - Allow-Lists for the Vulnerable 

This is a base repository for the uAllow project aimed at providing uBlock
**allow-lists** for the vulnerable among us to provide a safer web browsing 
experience and avoid scams. 

While people are constantly educated about being careful about opening
*"suspicious links"* this advice fundamentally misses that:

* Reading URL's is hard
* Knowing which domains are trustworthy is even harder
* You are not always shown the (full) URL 

Since people who lack the ability to come over these obstacles tend to 
visit a limited number of sites, it's logical to provide them technical means 
to restrict their browsing to those trusted sites, so they don't accidentally
wander off to dangerous territory like phishing sites. 


## Help Your Peers

If you have enough experience with technology you can help your friends and
relatives by installing the appropriate allow-list(s) for them. Here you can
find browser-specific instructions to do so.

### Firefox

Install the [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) add-on.

A new shield icon should appear next to the address bar of Firefox or among the add-ons 
(puzzle icon). Click it to open up uBlock's primary controls!

![The shield of uBlock and the general Add-Ons menu](img/shields.png)

Click the gears in uBlock's control window to open uBlock settings.

Open the My Filters tab and copy the contents of the allow-list there. 

![Allow-list pasted under My Filters](img/my-filters.png)

Congratulations, you are done!


### Chrome / Edge

TBD

### Safari

TBD


## Help the Community

Geographic locality seems like an important factor to determine which domains
should be allowed. For example, people are mostly interested in local news and 
use the local branches of their banks.

You can create your localization of the [sample
repository](https://github.com/u-allow/sample) either by forking it or creating
an independent copy. You are also welcome to create thematic lists (e.g.
"Gardening in Spanish") that would work for a more global audience. Our goal is
not any kind of profit but to provide tools for safe web browsing as widely as
possible.

What we provide:

* A general purpose [template](template.txt) for allow-listing
* General documentation about configuration and intended purpose (you are
  reading this now)
* Discoverability for [local groups](#local-groups)


## Local Groups

* [Sample from Similarweb data](https://github.com/u-allow/sample)
* [Cloudflare top domains](https://github.com/u-allow/u-allow-cf) 
* [Hungary](https://github.com/u-allow/u-allow-hu)
* Your group comes here!


## FAQ

### Can we make this more international?

Absolutely! Since maintaining a global list of safe domains is hard work, we
distribute the problem to [local groups](#local-groups) who should maintain their
own forks of the [sample repository](https://github.com/u-allow/sample). 

### An important domain is missing from the list!

Please open an issue at the repository of your relevant [local
groups](#local-groups)!

### What about domains of adult content?

As these are hugely popular it's impractical to filter them from our list if we
want good coverage so as a general rule we let these pass.

Lists can be customized to prevent access to sensitive content, but we consider
our target audience as responsible adults who can decide what content they want
to consume.

### Do you want to control the Internet use of the differently abled?

Absolutely not, see the next question! 

### Can users of these lists shoot themselves in the foot?

Absolutely. We expect all users to be grown adults who can ignore or 
disable warnings, this is not like parental controls or MDM. Note that they can
also invite strangers into their homes and give them hard cash out of mere
generousity. 

### What is uBlock?

uBlock Origin is a reputable
[ad-blocker](https://en.wikipedia.org/wiki/Ad_blocking) that coincidentally also
provides the features we need to allow-list websites. The ad-blocking
functionality of uBlock in itself is also useful to avoid malware and scams
[delivered via online
advertisement](https://en.wikipedia.org/wiki/Malvertising). 

We are not affiliated with uBlock in any way. 


## License 

uAllow © 2026 by The uAllow Project is licensed under CC BY-NC-SA 4.0. 
To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/
