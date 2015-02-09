# boxstarter-dev-machine
Boxstarter script for a development machine

To kick it off, run the following line from a Powershell prompt:

`START http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/groovyghoul/boxstarter-dev-machine/master/bytemares.BoxstarterDev/tools/ChocolateyInstall.ps1`

Troubleshooting:

### Problem:
Stuck on Windows "Restarting..." screen
### Solution:
Either be patient, it may just be taking a long time to do an update...just leave it be, or power down the machine and power back on again. It seems to be stuck in the middle of a Windows update. I did this and after logging back in, everything kicked back in at the next installation step.

[![GoogleAnalyticsTracker Nightly Build Status](https://www.myget.org/BuildSource/Badge/bytemares-boxstarter?identifier=1f0ae702-f4ce-4616-b096-9a173ff58a0d)](https://www.myget.org/gallery/googleanalyticstracker)

Thanks to:

- http://blog.zerosharp.com/provisioning-a-new-development-machine-with-boxstarter/ for the initial script
- https://github.com/gep13/ChocolateyPackages for the layout idea
