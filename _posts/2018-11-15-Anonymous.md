---
layout: default 
title: anonymous
author: Mr. Hacking Tiger
tags: Anonymous
---

17 steps to being completely anonymous online

The default state of internet privacy is a travesty. But if you're willing to work hard, you can experience the next best thing to absolute internet anonymity.

￼

There is no real default privacy on the internet.

Even many of the tools explicitly designed to protect your privacy don’t work quite as well as advertised. Our personal information is eroded through a combination of user information-driven commerce (nearly every company sells your personal data), weak governmental protections, leaky products, hacked records and a society that, in general, feels meh toward privacy in the first place.
The end result is that it isn’t all that difficult for anyone to buy or see your personal information. You don’t have to be a government official with a legal warrant to peer into someone’s life. But just because your privacy isn’t protected by default doesn’t mean you can’t take steps to improve it. Here's how to take back a bit of your private life:

1. Find a safe country that values privacy

It’s good to be in a country that attempts to protect citizens from rampant government spying, at least without legal warrants and judicial oversight. It’s even better to be in a country that at least talks tough about protecting users' individual privacy and places limits on its commercial use.

The European Union’s General Data Protection Regulation (GDPR) is pushing the privacy bar a bit. It impacts any company in the EU or doing business with any citizen in the EU. That’s a lot of coverage. Expect more businesses and countries not in the EU to be moving toward more GDPR-like laws, although you will always have your laggards.

Of course, most of us don’t have the option of simply moving to another, more privacy-embracing country. If that's your situation and if you care about your privacy, be an agent of change. I recommend contributing to any organization that fights for your privacy. Certainly, the Electronic Privacy Information Center (EPIC) and the Electronic Frontier Foundation (EFF) are top organizations with lots of information and a track record of continued hard work and success.

2. Get an anonymizing operating system

Next, you'll need an anonymizing operating system that runs on a resettable virtual machine (VM) running on secure portable media. The portable media device should use hardware-based encryption or a secure software-based encryption program. One of the top products on that list is Ironkey Workspace. It offers good encryption, locks out users who enter too many bad passwords and comes with Microsoft's portable OS, Windows to Go, on several USB key models.

Many privacy advocates prefer a Linux Live distro, such as Tails or ZeusGuard. Live OSes are designed to be booted from removable media for each session, and Tails is one of the best, built for and focused on privacy and security. The U.S. National Security Agency has stated in an internal, leaked presentation that Tails and Live OSes like it are a threat to its eavesdropping mission. That's a ringing endorsement.

Whether or not you use a Live OS, make sure the OS doesn't store information that can be used against you. If you're not using read-only bootable media, consider using a VM solution that resets itself after every use. Better yet, do both. Use a Live OS stored in a VM. Let the VM assign random Dynamic Host Configuration Protocol (DHCP) and (Address Resolution Protocol) ARP addresses on every start.
Also, consider Qubes OS, a free operating system built from the ground up with security as the ultimate objective. It’s used and promoted by some of the world’s biggest privacy advocates. It really is leaps ahead of most operating systems, especially in compartmentalization, meaning that it’s far harder for one compromised program to lead to an entire OS compromise. I fully expect other, more popular OSes, to become more like Qubes in the future, but you can get that functionality now.

3. Use an anonymous VPN

Next, you'll need to connect to the internet using an anonymous method. The best approach would probably be to jump around different open wireless networks, public or otherwise, as much as possible, rarely repeating at the same connection point. Barring that method, you would probably want to use a virtual private network (VPN) or device built for such purposes. There are literally dozens, if not hundreds, of VPNs that are specifically built to make your internet connection more difficult to identify and track. They do this by replacing your computer’s originating IP address and metadata information with something else. Instead they substitute one of their IP addresses for yours and block your metadata information from traveling to the eventual endpoint. On top of that, many privacy-protecting VPNs also promise not to log your connection, so even if they get a legal search warrant from law enforcement, they will have less data that can assist in identifying you.

You can also consider using a device explicitly designed to protect your privacy, like Anonabox and ProxyGambit. Devices like Anonabox can use Tor (covered below) or anonymizing VPN services, which are always on to protect your connection. Devices like ProxyGambit go even a little further. I'll let ProxyGambit describe itself:

ProxyGambit is a simple anonymization device that allows you to access the internet from anywhere in the world without revealing your true location or IP, fracturing your traffic from the internet/IP through either a long-distance radio link or a reverse tunneled GSM bridge that ultimately drops back onto the internet and exits through a wireless network you're nowhere near. While a point to point link is possible, the reverse GSM bridge allows you to proxy from thousands of miles away with nothing other than a computer and internet with no direct link back to your originating machine.

If you are truly concerned about your privacy, then consider using a VPN or anonymizing device to protect your internet surfing.

4. Use Tor

Whatever Live OS and internet connection method you use, make sure to go with an anonymizing browser, such as the Tor browser. Tor is actually an entire system — tools, browsers, APIs and network — dedicated to helping you and your connection remain anonymous.

Once you enter a Tor network path, the traffic to and from your destination will be routed through a random set of "Tor nodes." Although Tor's anonymity can be defeated, it remains one of the best ways to stay anonymous when combined with these other recommendations. You can even buy hardware-based Tor solutions like Anonabox.

￼Tor.org

When using the Tor browser, it’s best to keep it at its default windows size for maximum security.

5. Don't use plug-ins

It's very important to remember that many of today's browser plug-ins, particularly the most popular ones, leave clues that reveal your identity and location. Don't use them if you want to preserve your anonymity.

One possible exception would be plug-ins designed to enhance privacy, like Privacy Badger offered by the Electronic Freedom Foundation (EFF). Available for Chrome and Firefox, it stops advertisers and third-party trackers from tracking your web browsing, including what pages you visit. It watches third-party domains that place images, scripts and advertising in web pages you visit, and stops them from tracking you.

Click the Privacy Badger icon in your browser when you’re on a site, and it shows you a list of all the trackers it found.  Each tracker is shown as green, red or yellow --- green for those that appear to be safe, red for those that the add-in completely blocked, and yellow for those it partially blocked. The more you browse, the more effective Privacy Badger becomes, because it learns more about the trackers, and so blocks more of them.

Note that Privacy Badger is not a traditional ad blocker, because its intent is to protect your privacy rather than block ads. So, it does block ads that are also used as trackers, but not ads that aren’t related to trackers.

￼Privacy Badger

Privacy Badger stops websites and third parties from tracking your browsing habits.

Another EFF plug-in for Chrome, Firefox, and Opera is also worth using. HTTPS Everywhere was written in collaboration with the privacy-focused Tor Project. The plug-in solves a problem with sites that use what should be the secure HTTPS privacy protocol. Some sites that use HTTPS don’t use it properly, so they can default to the unencrypted HTTP protocol. HTTPS Everywhere solves the problem by ensuring they use encrypted HTTPS when you use the plug-in. Note that the plug-in won’t turn normal HTTP connections into encrypted HTTPS connections. It only makes sure that HTTPS connections use encryption properly

6. Stick with HTTPS

When you connect somewhere on the internet, try to use HTTPS. This used to be harder to do, but now the most popular websites use HTTPS by default, and those that don’t can be defeated by using one of the anonymizing VPN services or devices used above. When working with HTTPS, use only handpicked, trusted certificate authorities that don't issue "fake" identity certificates.

7. Avoid the usual applications

Don't install or use normal productivity software, like word processors or spreadsheets. If it’s super popular, they probably don’t care about your privacy. Many "dial home" each time they're started and reveal information. If it’s free and isn’t explicitly designed to protect your privacy, don’t expect any. As computer security guru Bruce Schneier says in his seminal book, Data and Goliath: The Hidden Battles to Collect Your Data and Control Your World, “If something is free, you’re not the customer; you’re the product.”

8. Set up anonymous burner accounts

You'll need a different password and password question answers for each website where you create a logon account. (Note: these steps are not only for privacy nuts and should already be practiced by everyone.)  The very paranoid will also want to create different email addresses for each website. These "burner" email accounts are expendable and are much harder to trace back to the real you. Use email services that explicitly advertise as being anonymous. You’ll find free and commercial versions. Always connect to them using other anonymity apps and connections, and switch among burner accounts, even when speaking to the same people.

9. Never use credit cards

If you plan to buy anything on the internet, you can't use a normal credit card and stay anonymous. You can try to use online money transfer services such as PayPal, but most have records that can be stolen or subpoenaed. Better, use an e-currency such as bitcoin or one of its competitors. E-currencies are starting to gain widespread validity and are accepted in more and more places every day.  You'll need a bank or service to convert your real money into one of these alternative forms (and to get it back out), but once you're using the currency, buying anonymity is easier to maintain.

10. Test for DNS leaks and browser tracking

One way to test whether you’re keeping yourself anonymous is to check whether you have a domain name server (DNS) leak. DNS servers translate domain names such as csoonline.com to the numeric IP addresses the Internet uses, such as 151.101.0.230. Internet servicepProviders (ISPs) generally use their own DNS servers, and those servers can be used to identify your and log and track its Internet activities.

VPNs like Tunnel Bear and CyberGhost VPN use DNS servers that protect your anonymity. If you want to make sure you’re protected against DNS leaks, go to www.DNSLeakTest.com. Run the extended test. If you see your ISP’s DNS servers, you’ve got a DNS leak. (The servers should have their name on them --- the leak test identifies them.)  If you see the DNS servers run by your VPN provider, you’re safe. If you want help in tracking down and fixing a DNS leak, head to the DNSLeakTest.com page How can I fix a DNS leak? for advice on how to fix it.

￼DNS Leak Test

Uh, Oh! You’re not protected.

11. Test your overall privacy protection

How well are your privacy actions working? There’s a way to find out by testing how protected you are against being tracked as you browse the web. To do it, head to the EFF’s Panopticlickpage and click the big Test Me button. It checks whether your browser is blocking tracking ads and invisible trackers, and whether your browser has a unique fingerprint. Based on the results of what you find on DNSLeakTest.com and Panopticlick, you can rejigger the way you’re trying to protect your anonymity and see how it works, by retesting.

12. Share files anonymously

The cloud storage service Dropbox, designed to let you share files with others is, in the words of Edward Snowden, “very hostile to privacy.” If you’re looking for a free alternative that lets you anonymously share files of any size, try the open source OnionShare, which was written by Micah Lee, who works with the journalist Glenn Greenwald who was the recipient of the NSA files from Snowden. It’s available for Windows, Mac OS X, and Ubuntu.

13. Use a search engine that doesn’t track your behavior

Popular search engines like Google and Bing keep track of your searches so they can target ads at you. For maximum security, use one that won’t keep track of your results. DuckDuckGois a great choice. It offers plenty of useful features including region-specific searching; Safe Search, which omits potentially objectionable material; keyboard shortcuts; and more. I particularly like the Instant Answers feature that displays information across the top of the screen in addition to the normal search results for recipes, weather and other topics. Search for “Weather Boston,” for example, and you’ll see the weather report across the top of the page for the next several days or “recipe chocolate chip cookies” and you’ll see thumbnail pictures of the cookies, with links to different recipes.

14. Turn off your location

Web sites can get location data from your PC, and use that to determine your location, target ads at you and help identify you. There’s a way to turn that off, though. In Windows 10 go to Settings > Privacy > Location. Click the Change button and move the slider that appears from On to Off. That by itself isn’t enough, because sites can still look into your location history. So, you should clear that out. To do it, scroll down to Location History and click the Clear button underneath “Clear history on this device.”

￼Microsoft

Here’s where to go in Windows 10 to stop websites from snooping on your location.

15. Block Javascript

JavaScript can be a privacy invader, allowing web servers to find out information about you such as what plug-in you have enabled, the size of your monitor, and more. This makes it easier to track your behavior. For maximum safety, disable JavaScript. That can be problematic, though, because JavaScript provides the power and features for many web sites. Turn off Javascript and the site becomes usable. You can turn if off on some sites and keep it on others. If you use Firefox, the NoScript extension will do the trick, and if you’re a Chrome user, turn to ScriptSafe. They both let you decide which sites should load Javascript.

16. Keep your webmail private

When you send email using webmail services like Gmail or Outlook.com, they can be snooped upon. Protect them with encryption. Several free solutions will help you do that. A great one is ProtonMail,  which encrypts all of your email with end-to-end encryption. It doesn’t keep IP logs that can be tracked to your account, and doesn’t require that you give any information to create your anonymous account. There are also apps for Android and iOS, so you can use it with your mobile devices.

17. Delete cookies and your browsing history

It’s a good idea to regularly clean out cookies that website use to track you, and your browsing history, which can be used to identify where you’ve been.

The hard work of privacy

Each of these anonymizing methods can be defeated, but the more of them you add to your privacy solution, the harder it will be for another person or group to identify you. Of course, everything you do to protect your privacy causes inconvenience in your online life. Serious privacy advocates don't mind going to this trouble, but most of us aren't willing to do what it takes to accomplish even a modicum of privacy, such as configuring settings in our OS or on social media sites. Most people simply accept the defaults — which rarely protect privacy.

The people who hack and monitor us for a living hope the majority of us will take the easy way out and do little or nothing to prevent our online identities from being discovered, hacked, and revealed. You can be part of the solution.

