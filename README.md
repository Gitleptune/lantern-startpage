<div align="center">
 <h6>An easily customisable, minimalist lightweight startpage for <a href="https://github.com/Gitleptune/lantern-theme">Lantern Theme</a>.<h6>
 <img src="https://user-images.githubusercontent.com/76597257/128608432-b86e8f3d-8ff8-47e6-933e-825784e86db0.png">
</div>

## Installing

### Vivaldi

Go into Settings -> Tabs -> New Tab Page -> Last Option (Enter either file location or url)

### Firefox

[r/startpages/how-to-set-a-custom-new-tab-page-in-firefox](https://www.reddit.com/r/startpages/comments/g3qndt/psa_how_to_set_a_custom_new_tab_page_in_firefox/)

### Other Chromium browsers

[chromestore/new-tab-redirect](https://chrome.google.com/webstore/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmna)

## Configuring

To do any configuration you should fork the repository and then edit the files.

### Changing Links

Go into index.html and add new entries with `<li><a href="new-link-url">text i want to see</a></li>`.

### Adding new link boxes

Go into index.html and add a new box with:

```html
<fieldset>
	<legend>text in the border of the box</legend>
	<ul>
		<li><a href="new-link-url">text i want to see</a></li>
	</ul>
</fieldset>
```

### Changing gif

Go into index.html file and change the image source like this: `<img src="new-gif-link.gif">`

### Changing colours

Colour configuration is done via changing 5 variables:

```css
:root {
	--background: #261b17; /* Affects the background of the page */
	--shadow: #1b110e; /* Affects the shadow under the link boxes */
	--accent: #e86420; /* Affects link on hover colour and heading shadow colour */
	--foreground: #e4cbb3; /* Affects the text colour */
	--accent-alt: #e01d1d; /* Affects link on click colour */
}
```
