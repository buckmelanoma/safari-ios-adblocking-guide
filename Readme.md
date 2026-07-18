Hello all.  I often see questions about what the best ad blocking setup is on iOS/macOS, especially with regard to YouTube ads and ads in apps/games so I wrote up this quick guide.  The guide is written for Safari but you can also substitute with Firefox if desired:

1. Make sure you’re on the latest Safari version by going to Settings -> General -> Software Update
2. Download [uBlock Origin Lite](https://apps.apple.com/us/app/ublock-origin-lite/id6745342698)
3. Enable it in Safari:
  * On iOS: Go to Settings -> Apps -> Safari -> Extensions and toggle all uBlock Origin Lite permissions to ON
  * On macOS: Open Safari, click Safari in the menu bar -> Settings -> Extensions, and check the box for uBlock
  * Also be sure to check the box for Allow in Private Browsing
4. Click the Settings button for the uBlock extension
5. It will open a page with filtering modes, set it to Optimal
6. By default this should block most ads and ads in YouTube.  If you want you can click on the Filter Lists tab to set optional lists which block things such as cookie notices, AI widgets and other annoyances

For the next part we will enable DNS blocking to take care of ads that appear in apps and games:
1.  Head over to [NextDNS](https://nextdns.io/?from=j3h7c4a3) and create an account
2.  Once logged in, on the Setup page get the app for iOS or macOS
3.  Once you have the app, open it 
  * On iOS: follow the instructions for Finish DNS Setup, then add your Profile ID to the app from your account (should be a 6 character ID)
  * On macOS: Click on Preferences in the app status bar menu and go to the Configuration tab, check "Use Custom Configuration" and enter your ID (should be a 6 character ID)
5.  Make sure the switch in the app is toggled on and you should now be completely ad free!
6.  You can take it a step further and install the NextDNS app on your other computers and phones to block ads on them

Bonus step: Install the [SponsorBlock](https://apps.apple.com/us/app/sponsorblock-for-safari/id1573461917) extension for Safari which blocks sponsor segments and filter content in YouTube videos.   
