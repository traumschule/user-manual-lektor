[Tor Browser User Manual](index.html "Tor Browser User Manual") »

# About Tor Browser

Tor Browser uses the Tor network to protect your privacy and anonymity. Using
the Tor network has two main properties:

  * Your internet service provider, and anyone watching your connection locally, will not be able to track your internet activity, including the names and addresses of the websites you visit. 

  * The operators of the websites and services that you use, and anyone watching them, will see a connection coming from the Tor network instead of your real Internet (IP) address, and will not know who you are unless you explicitly identify yourself. 

In addition, Tor Browser is designed to prevent websites from “fingerprinting”
or identifying you based on your browser configuration.

By default, Tor Browser does not keep any browsing history. Cookies are only
valid for a single session (until Tor Browser is exited or a [New
Identity](managing-identities.html#new-identity "Changing identities and
circuits") is requested).

## How Tor works

Tor is a network of virtual tunnels that allows you to improve your privacy
and security on the Internet. Tor works by sending your traffic through three
random servers (also known as relays) in the Tor network. The last relay in
the circuit (the “exit relay”) then sends the traffic out onto the public
Internet.

![](media/how-tor-works.png)

The image above illustrates a user browsing to different websites over Tor.
The green middle computers represent relays in the Tor network, while the
three keys represent the layers of encryption between the user and each relay.

## More Information

  * [Tor Browser User Manual](index.html "Tor Browser User Manual")

