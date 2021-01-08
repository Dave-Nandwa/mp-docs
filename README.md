# Marketplace Widgets: Developer Guide

Here's a quick guide on how to add the Financial Professional Widget on to your site.

## Installation

You should've received a script like this from an FP Administrator:

```html
<script type="text/javascript">
    window.widgetId = 'YOUR UNIQUE ID HERE';
</script>
<script type="text/javascript" src="https://dl.dropboxusercontent.com/s/mk5kn7jalzx7py5/widget.js?dl=0"></script>
```
Add it to the bottom of your HTML file, right above the body or in the custom scripts section of your CMS.
## Integration

To activate the widget and sync it with the main marketplace all you need to do is add a div with this class to the corresponding page.
```html
<div class="fp_widget"></div>
```

## Wordpress Integration

To add the Widget to your Wordpress Site, kindly follow the simple steps outlined here:
```html
https://www.wpbeginner.com/wp-tutorials/how-to-easily-add-javascript-in-wordpress-pages-or-posts/
```
Don't forget to add the fp_widget div as well! :)
```html
<div class="fp_widget"></div>
```
## Wix Site Integration

To add the Widget to your Wix Site, all you need to do is click on the '+' icon on your left, and then the Embed option, and select Embed a Custom Element, Paste in the code link below whilst replacing the wildcard below with your unqiue Widget ID, and it should be live immediately and it should work immediately:
```html
https://marketplace.financialprofessional.com/widget/{{YOUR WIDGET ID HERE}}
```

## Google Sites Integration

To add the Widget to your Google Site, all you need to do is paste the link below in the embed section,
whilst replacing the wildcard below with your unqiue Widget ID, and it should be live immediately:
```html
https://marketplace.financialprofessional.com/widget/{{YOUR WIDGET ID HERE}}
```
## Webflow Integration

For Webflow you have two options, you can create a container and add this Custom Code Component Inside:
```html
<div class="fp_widget"></div>
<script type="text/javascript">
    window.widgetId = 'REPLACE WITH YOUR WIDGET ID';
</script>
<script type="text/javascript" src="https://dl.dropboxusercontent.com/s/mk5kn7jalzx7py5/widget.js?dl=0"></script>
</div>
```
# Or you can simply add Custom Code Container and paste the following:
```html
<div style="position:relative;width:100%;height:800px" class="fp_container">
<div class="fp_widget"></div>
<script type="text/javascript">
    window.widgetId = 'REPLACE WITH YOUR WIDGET ID';
</script>
<script type="text/javascript" src="https://dl.dropboxusercontent.com/s/mk5kn7jalzx7py5/widget.js?dl=0"></script>
</div>
```
# With the first approach you can utilise Webflow's No-Code Tools to modify the conatiner's width and height, and the widget will conform to the dimensions you set.

# The benefit of the second approach is being able to modify the dimensions directly from the HTML.

## Compound Interest Calculator Widgets: Guide

To activate the CIC Widget and sync it with the main site all you need to do is add a div with this class to the corresponding page.
```html
<script type="text/javascript">
    window.widgetId = 'YOUR UNIQUE ID HERE';
</script>
<script type="text/javascript" src="https://dl.dropboxusercontent.com/s/mk5kn7jalzx7py5/cic_widget_encrypted.js?dl=0"></script>
```

## Help
If you need help with your integration, please don't hesitate to reach out.
