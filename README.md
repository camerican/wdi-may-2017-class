Create a webpage about yourself with the following features:

## 1. using cam.html as a baseline, name your profile page after yourself:

* benjamin.html
* logan.html
* nick.html
* victor.html
* james.html
* tommy.html
* hans-sebastian.html
* neil.html
* katy.html
* asyifa.html
* jace.html
* steven.html
* erin.html
* david.html

## 2. Create a css file named after yourself, also:

* benjamin.css
* logan.css
* nick.css
* victor.css
* james.css
* tommy.css
* hans-sebastian.css
* neil.css
* katy.css
* asyifa.css
* jace.css
* steven.css
* erin.css
* david.css

## 3. Include a link to the css file from the html file

## 4. Add in an image that is left floated and whose source references your profile photo on Slack

If you view your Slack profile in a browser, you can inspect the image and copy the location referened in the `background-image` property.

## 5. Replace the content with your own biographical information.

## 6. Add a class to your body tag named after yourself (e.g. Cam would add a class of cam to the body)

## 7. Customize the styling in your page with selectors that are found within the body class you just added

We do this so that we can combine our stylesheets into one later without them conflicting.  We'll want to prefix our rules in our css document with this class now, so that our different stylesheets will play nicely with each other.  For example, if I wanted to target the h2s in my page to be blue, I would nest the rule under `body.cam`:

```css
body.cam h2 {
	color: #0000ff;
}
```

This means that if I was Oliver and wanted red h2s, they wouldn't be overridden by Cam's rules.

```css
body.oliver h2 {
	color: #ff0000;
}

## 8. For your gallery and portfolio pages, create files that are named as follows: 

* benjamin_gallery.html       benjamin_porfolio.html
* logan_gallery.html       logan_porfolio.html
* nick_gallery.html       nick_porfolio.html
* victor_gallery.html       victor_porfolio.html
* james_gallery.html       james_porfolio.html
* tommy_gallery.html       tommy_porfolio.html
* hans-sebastian_gallery.html       hans-sebastian_porfolio.html
* neil_gallery.html       neil_porfolio.html
* katy_gallery.html       katy_porfolio.html
* asyifa_gallery.html       asyifa_porfolio.html
* jace_gallery.html       jace_porfolio.html
* steven_gallery.html       steven_porfolio.html
* erin_gallery.html       erin_porfolio.html
* david_gallery.html       david_porfolio.html
