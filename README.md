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

## Wix Integration
To add the custom code given to you by an FP Pro Admin, follow the steps here:
https://support.wix.com/en/article/about-tracking-tools-analytics
And Select the 'Custom Code' option.

Be sure to add the fp_widget element as well.

To do so, Open up add html element and just put your html code into it.

To do so click
```html
[Add]-[More]-[Html Code]
```
on your left-hand panel.

## Help
If you need help with your integration, please don't hesitate to reach out.
