[Tor Browser User Manual](index.html "Tor Browser User Manual") »

# Plugins, add-ons and JavaScript

## Flash Player

Video websites, such as Vimeo make use of the Flash Player plugin to display
video content. Unfortunately, this software operates independently of Tor
Browser and cannot easily be made to obey Tor Browser’s proxy settings. It can
therefore reveal your real location and IP address to the website operators,
or to an outside observer. For this reason, Flash is disabled by default in
Tor Browser, and enabling it is not recommended.

Some video websites (such as YouTube) offer alternative video delivery methods
that do not use Flash. These methods may be compatible with Tor Browser.

## JavaScript

JavaScript is a programming language that websites use to offer interactive
elements such as video, animation, audio, and status timelines. Unfortunately,
JavaScript can also enable attacks on the security of the browser, which might
lead to deanonymization.

Tor Browser includes an add-on called NoScript, accessed through the “S” icon
at the top-left of the window. NoScript allows you to control the JavaScript
(and other scripts) that runs on individual web pages, or block it entirely.

![](media/plugins/noscript_menu.png)

Users who require a high degree of security in their web browsing should set
Tor Browser’s [Security Slider](security-slider.html "Security Slider") to
“Safer” (which disables JavaScript for non-HTTPS websites) or “Safest” (which
does so for all websites). However, disabling JavaScript will prevent many
websites from displaying correctly, so Tor Browser’s default setting is to
allow all websites to run scripts in "Standard" mode.

## Browser Add-ons

Tor Browser is based on Firefox, and any browser add-ons or themes that are
compatible with Firefox can also be installed in Tor Browser.

However, the only add-ons that have been tested for use with Tor Browser are
those included by default. Installing any other browser add-ons may break
functionality in Tor Browser or cause more serious problems that affect your
privacy and security. It is strongly discouraged to install additional add-
ons, and the Tor Project will not offer support for these configurations.

## More Information

  * [Tor Browser User Manual](index.html "Tor Browser User Manual")

