# aprilFools.css ☺

_by Wes Bos_ [<img src="http://wes.io/Ntgi/content">](http://twitter.com/wesbos)

Put these CSS definitions into your co-workers css overriding file.  They will be applied to every website they visit. They are commented out by default, so make sure to uncomment your favourite ones! 

Most will work in both firefox and chrome. The `-webkit` only ones are specific to chrome or dev tools features. Please feel free to add more via PR.

**Mac Chrome**: `~/Library/Application Support/Google/Chrome/Default/User StyleSheets/Custom.css`

**Windows Chrome**: `C:/Users/YourUsername/AppData/Local/Google/Chrome/User Data/Default/User StyleSheets/Custom.css`

**Linux (Chromium)**: `~/.config/chromium/Default/User StyleSheets/Custom.css`

**Firefox** - Windows, Mac & Linux: `YOUR_FIREFOX_PROFILE/chrome/userContent.css`

	/*
	  Turn every website upside down.
	  Available: Chrome, Firefox
	*/
	body {
	  -webkit-transform: rotate(180deg);
	}

![](http://wes.io/NuBm/content)

	/*
	  blur every website for a split second every 30 seconds
	  Available: Chrome
	*/
	body {
	  /*-webkit-animation: blur 30s infinite;*/
	}

![](http://wes.io/Ntu2/content)

	/*
	  Spin every Website
	  Available: Chrome, Firefox
	*/ 
	body {
	  /*-webkit-animation: spin 5s linear infinite;*/
	}

![](http://wes.io/Ntsb/content)

	/*
	  Flip all images upside down
	  Available: Chrome, Firefox
	*/
	img {
	  /*-webkit-transform: rotate(180deg);*/
	}

![](http://wes.io/Nti1/content)


## See them all in your [aprilFools.css](https://github.com/wesbos/aprilFools.css/blob/master/aprilFools.css)