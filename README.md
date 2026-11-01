# Retrozilla-Derma-710-s-fork-
This is a fork of RetroZilla. Ive did not invented RetroZilla.
This fork contains two extensions: NoScript and Adblock Plus, so sites will work better and the browser will be more secure.
To have better site compatibility, go to about:config.
In there, type accessibility.AOM.enabled. 
If you don t find that command, it is ok, you can create it.
Right Click, on the white space, New-Boolean.
Type: ”accessibility.AOM.enabled”.
Set to false.
Refresh the page.
Now, if you see accessibility.AOM.enabled, right click on it, New-String.
Now put: ”general.useragent.override”.
Press ok.
And press ok again.
Now refresh the page.
You will need to patch some sites that have bot verification.
Search for ”general.useragent.override”
Where is white space, right click, New-String. Don t right click on the ”general.useragent.override”.
Now type: ”general.useragent.override.mozillazine.org”   (mozillazine.org is a site that has bot verification and it can be patches)
Press ok.
Now put this command: ”Anubis/5.0 (%OS_SLICE%; rv:159.0) Gecko/20100101 Firefox/159.0”
Press ok.
This is a bypasser for the Anubis robot verification. Many people hate those robot verifications, since they will eat a lot of your time.
Refresh the page.
Now do the same think with general.useragent.override again and again. See this image and put how many commands you want.
<img width="1919" height="872" alt="Capture" src="https://github.com/user-attachments/assets/3f3df0ed-df6c-4937-9c15-95b076268fa7" />


IMPORTANT TO NOTICE: RetroZilla is based on Gecko 1.8.1. It is not the most secure browser. Those two extensions make the browser more secure, but not the most. Not as safe as modern Mozilla Firefox.
Since Gecko 1.8.1 is old and it was used in 2006-2010 by SeaMonkey and Firefox, not 100% of sites will work.
And also the ``accessibility.AOM.enabled`` was not included by that time in Gecko 1.8.1.



