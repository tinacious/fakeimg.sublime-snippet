# FakeImg.pl Placeholder Support for Sublime Text 2

I recently discovered the great placeholder website [fakeimg.pl](http://fakeimg.pl/).

The Snippet contains the following code:

```xml
<snippet>
	<content><![CDATA[
<img src="http://fakeimg.pl/${1:350}x${2:200}/${3:00CED1}/${4:fff}/?text=${5:img+placeholder}">
]]></content>
<tabTrigger>fakeimg</tabTrigger>
</snippet>
```

**tabTrigger** : `fakeimg`

This snippet tabs through all of the available options:

- horizontal size
- vertical size
- background color
- text color
- text

FakeImg.pl also has support for `&font=lobster` and possibly other fonts though options are not documented on the site.