# I found a little problem

When drawing web fonts on canvas, it seems that even though it is a single character, it may overlap many times.  
It does not occur on PC. You can check it on iOS.  
Not confirmed on Android. It might happen.  

[demo](https://yukioterasawa.github.io/webfontoverlapmanytimes/overlap.html)

Try drawing with Google Fonts' "M PLUS 1p".  
If you specify a weight font that has not been loaded, characters will overlap on iOS. No problem on PC.  

The solution is to load the specified weight.

[demo](https://yukioterasawa.github.io/webfontoverlapmanytimes/solution.html)
