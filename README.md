# blockchain-journalist

### Intro

![Good News](http://www.memegasms.com/media/created/vhyfxm.jpg)

Good news, everyone. Are you tired of keeping up with Blockchain news? Are you ready to create your own click-bait attempt at "shocking blockchain news"? Are you tired of hearing this in Professor Farnsworth's voice?

### Instructions

This Chrome extension allows you to generate 'mini-stories' about the great big blockchain in the sky.
Install the extension, open it and use the options to generate the title and story.
Once you click Generate Output, the article will be generated and copied to your clipboard.

### Screenshots

![Initial State](https://i.imgur.com/pDK4td3.png)
The initial state when opening the app.

![Options](http://i.imgur.com/pOi6vx7.png)
Options after selecting your article requirements.

![Generation](https://i.imgur.com/flGUhTL.png)
Generation options available as soon as you open sufficient options to have a title/article generated.

### Modifications
The easiest modification is to add additional lines of "story", or alternatively to add better titles or more options.

The data.json file under configs controls everything, from options that are allowed, to titles that can be used, to even the text and how's it used.

The format is pretty explanatory. When the title is built, the best title is picked from the closest "reqs sets" compared to the options you have selected. The same is done when piecing together the article.