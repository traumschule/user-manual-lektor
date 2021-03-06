[Tor Browser User Manual](index.html "Tor Browser User Manual") »

# Verify

This section is about verifying the signature for your downloaded file.

These instructions apply to Windows, Mac and Linux.

Why you should always verify files after downloading: How do you know that the
Tor program you have is really the one we made? Digital signatures ensure that
the package you are downloading was created by our developers. If the Tor
package has been modified by some attacker it is not safe to use. It doesn't
matter how secure and anonymous Tor is if you're not running the real Tor. For
details see the chapter Why to verify signatures in our verification guide. It
also explains, what digital signatures are and which software you need.

## Verify the downloaded Tor Browser archive

  1. Download the Tor Browser archive and its .asc signature file to your Desktop. It is important to downoad both to the same directory, so they can be found by your verification program. ![](media/verify/download-tbb-sig.jpg)

  2. Open a command prompt or Terminal: 

![](media/verify/cmd.jpg)

  3. Enter the following commands to verify the bundle: (Change the file name to the file you downloaded) 

  4. You should see Good signature from "Tor Browser Developers (signing key) if not, please retry these steps. 

![](media/verify/verify-bundle.png)

For details check out the verifying signatures guide on the Torproject
website.

## More Information

  * [Tor Browser User Manual](index.html "Tor Browser User Manual")

