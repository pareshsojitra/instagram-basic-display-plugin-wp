
<a href="https://www.patreon.com/bePatron?u=38671402" data-patreon-widget-type="become-patron-button">Become a Patron!</a><script async src="https://c6.patreon.com/becomePatronButton.bundle.js"></script>
# WP-Instagram-API
Instagram Basic Display API plugin for Wordpress

## Setup
Create App instagram
Follow the directions here to create a Basic Display App for your Wordpress site:
https://developers.facebook.com/docs/instagram-basic-display-api/getting-started

### Change the following settings under Setting > Instagram setting

#### How to use shortcode 
Simple shortcode :
```
[instagram_feed class="your_css_class" number="number_posts_to_show"]

```
Advenced shortcode :
```
[instagram_feed number="number_posts_to_show"]
<div class='col-md-3'>
    <a href="{media_link}">
        <img src="{media_thumbnail}">
    </a>

</div>
[/instagram_feed]
```