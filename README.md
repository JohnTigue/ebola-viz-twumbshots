# ebola-viz-twumbshots

Twitter card friendly thumbnails of ebola visualizations from around the Web. These are useful for blogging about ebola vizualizations or maintaining a [Gallery of Ebola Visualizations Found Across the Web](https://github.com/JohnTigue/EbolaMapper/wiki/Gallery-of-Ebola-Visualizations-Found-Across-the-Web).

These images are intended to work well in [Twitter cards](https://dev.twitter.com/cards/overview). I needed a name for `images intended for inclusion in Twitter cards` but did not find one so `twumbshots` it is.

## Etymology
There seems to be no real definitional distinction between [thumbnails v. thumbshots](http://en.wikipedia.org/wiki/Talk:Thumbshot#How_is_.22thumbnail.22_different.3F). 
- `Thumbnails` are etymologically rooted in images literally the size of a human thumbnail. 
- `Thumbshots` imply screenshots which is a more technical term for preview. 

Personally, to choose between the two? `thumbshots`. Really, I don't like either but they are both `thumb-things`. 

So, these `thumb-things` are intented to be used in the context of Twitter feeds and the subsequent blog posts that Twitter will link through to, so these are `Twit-things` and well as `thumb-things`. `Twitter + thumbs = twumbs`. So, `twumbshots` it is, which is pretty rare on the Web [(31 hits on 2014-11-22 as I write this)](https://www.google.com/search?q=twumbshots&oq=twumbshots#q=twumbshots). The domain is available if you are into that sort of thing.

## Dimensions of images
- https://dev.twitter.com/cards/types/photo
	- Web: maximum height of 375px, maximum width of 435px
  - Mobile (non-retina displays): maximum height of 375px, maximum width of 280px
  - Mobile (retina displays): maximum height of 750px, maximum width of 560px
         
So, mobile is 280x375 (or double that) and web is 435x375 yet they maintain aspect ratio on resize... If only one aspect ratio (I do not want to deal with resizing) then mobile I guess and go big. So all images will have height=750px, width=560px and weigh in at less than a megabyte.


