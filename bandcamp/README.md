# Hugo Bandcamp Shortcode

## Installation

Copy `bandcamp.html` to `<site>/layout/shortcodes/` or `<site>/themes/<theme>/layout shortcodes/`.

## Usage

In your post file include a shortcode such as the following:

```html
{{< bandcamp id="1274104304" >}}
```

***

This one is a little silly since you need to use the album ID currently. This can be found near the bottom of the HTML that makes up an album page. Near the closing `<body>` tag you should see something like `<!-- album id 1274104304 -->`. At that point it might almost be easier to grab the code from the share section of the album page.

Maybe I'll try my hand at extending this to be able to use the Bandcamp search endpoint. It'd make it a bit easier to use and I could extend the code to take two variables, `artist` and `album`.
