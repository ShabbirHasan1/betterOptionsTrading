# betterUpstox

June 4 21
I have stopped trading on Upstox so this script is not updated. I am told it doesn't work anymore.

This userscript adds simple features on https://pro.upstox.com/trading UI

* Problem: We have several positions open at one time and it gets difficult to only focus on position belonging to specific strategy.
* Solution: Create a 'watchlist', give it name of your strategy, add scripts part of the strategy in the watchlist and click on 'Filter' to only see the positions pertaining to that strategy. 
    * Once you filter, you can see number of positions in that strategy and total P&L

![usage](https://dl.dropbox.com/s/18ik0c8vffg1t4x/betterUpstoxUsageGif.gif?dl=0)
(if you can't see the image above, click here: https://dl.dropbox.com/s/18ik0c8vffg1t4x/betterUpstoxUsageGif.gif?dl=0)

# Installation

Follow below mentioned steps
* Install [Tempermonkey](https://www.tampermonkey.net/) for your browser (works on all browsers. Tested on Chrome, Vivaldi, Edge). [Chrome extension link](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
* Open [this link](https://github.com/amit0rana/betterOptionsTrading/raw/master/betterUpstox.user.js) in a new tab. Or copy paste <https://github.com/amit0rana/betterOptionsTrading/raw/master/betterUpstox.user.js>
* Tampermonkey will automatically identify the file as userscript and give you option to install.
* Click on 'Install' button.
* You can verify the installation by clicking on Tampermonkey icon (next to address bar) and then go to 'Dashboard'. You should see 'betterUpstox' installed. 
* Now just go to <https://pro.upstox.com> (if the page is already open, then refresh it) and start using.

![filter](https://dl.dropbox.com/s/yt8wc31kcqxjw6w/betterUpstoxFilter.png?dl=0)
(if you can't see the image above click here: https://dl.dropbox.com/s/yt8wc31kcqxjw6w/betterUpstoxFilter.png?dl=0)


# Note
* Steps to disable the script

![disable](https://dl.dropbox.com/s/pp7bqiyzwak6cjp/troubleshootDisableBetterUpstoxVideo.gif?dl=0)
(if you can't see the image above click here: https://dl.dropbox.com/s/pp7bqiyzwak6cjp/troubleshootDisableBetterUpstoxVideo.gif?dl=0)

* How to upgrade to next version. 

![upgrade](https://dl.dropbox.com/s/8urhzpu6x78yxhk/upgradeScriptBetterUpstox.png?dl=0)
(if you can't see the image above click here: https://dl.dropbox.com/s/8urhzpu6x78yxhk/upgradeScriptBetterUpstox.png?dl=0)
* Do not forget to refresh the page after update

* P&L doesn't update on realtime. It shows the P&L at the time of filter.