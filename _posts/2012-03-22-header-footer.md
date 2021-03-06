---
permalink: /manual/header-footer.html
layout: post
title: "How to Customize the Header and Footer of Your Results Page"
tags: how-to user-interface
---
[USASearch](http://usasearch.howto.gov/) > [Admin Center](http://search.usa.gov/affiliates/home) > YourSite > Header and Footer

Select how you'd like to customize your header and footer. The fields that appear on the page will change based on the option you select.

## Option 1. Use a managed header and footer

Fill out the fields to generate a predefined header and footer.

**Color.** Customize the color of your header background and text by clicking on the color picker text field. Enter a valid three- or six-digit hex value or pick a color by dragging the cross-hair icon ![crosshair icon](http://search.usa.gov/javascripts/jscolor/cross.gif) inside the color picker window. Drag the triangle icon ![arrow icon](http://search.usa.gov/javascripts/jscolor/arrow.gif) to control the color saturation. When you are done, click anywhere outside the color picker window.

**URL.** Provide us with the URL for your website's homepage. We'll use it to provide a link back to you from your header text, image, or both.

**Text.** Fill out the text you'd like to appear in your header. We've pre-populated this field with your [site name](/manual/site-information.html). Edit the same name, or delete it, if you don't want this text to appear in your header.

**Image.** Use the Browse... option to upload the logo or image that you'd like to appear in the header, if any. If you don't have header text, the image will be center-aligned. If you do have header text, the image will be right-aligned. Click on the option, Mark header image for deletion, to delete an uploaded image.

**Header and footer navigation.** Fill out the titles and URLs if you'd like to add navigation to your header and footer. Use the arrows on the left to rearrange the display order of the links. See the sample results page below that includes navigation.

![Managed header with navigation on Sussex County's search results page](http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_m1ar9q6nXN1qid15q.png)

## Option 2. Use CSS and HTML code to create a custom header and footer

Use this option to more closely replicate the exact header and footer on your website.

In the first box, enter CSS to customize the header and footer of your search results page. We'll run a validation check to ensure your CSS is valid.

In the second box, enter HTML to customize the header of your search results page. In the third box, enter HTML to customize the footer of your search results page. Be sure to enter [absolute hyperlinks](http://webdesign.about.com/od/beginningtutorials/a/aa040502a.htm), not relative links.

Click on the link, Validate, to check your HTML markup at <http://validator.w3.org/nu>. We'll also run a validation check to ensure that no JavaScript is included in your HTML code. We'll also check to ensure no CSS style or link elements are included. To include CSS, specify inline CSS within an opening tag.

### Invalid CSS

    <html>
    <body>
    <style> h1 { color: blue } </style>
    <link href="http://www.yoursite.gov/custom.css" type="text/css" />
    </body>
    </html>

### Valid CSS

    <h1 style="color: blue;">Your Heading</h1>

## <a id="mobile"></a> Customize your mobile header

We use device detection to show mobile-friendly search results on mobile phones. (Searchers using tablets and desktop computers see the full, classic header as you set it up above.)

### Default mobile header

By default, searchers on mobile phones see the header, *YourSiteName Mobile*. If you list only one domain on the [Domains](/manual/domains.html) page, we link your header to this domain. See the sample default mobile header below for [HowTo.gov](http://www.howto.gov).

![HowTo.gov mobile search results page](http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_meazaml0781qid15q.png)

### Custom mobile header

You can customize your mobile header to include a logo. You can also edit or add your mobile homepage URL.

The logo must be less than 56&#160;KB. We recommend it be no wider than 320 pixels.

You can link to your classic homepage (e.g., http://www.agency.gov) or to your specific mobile homepage (e.g., http://m.agency.gov). If you use device detection on your website, we recommend that you link to your classic homepage for a more seamless mobile experience.

See the sample custom mobile header below for the [m.USA.gov](http://m.usa.gov) results page.

![USA.gov mobile search results page](http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_meazs7WsWk1qid15q.png)

---

***Troubleshooting tip:*** You can implement a drop-down menu using CSS (and without using JavaScript). For more information, A List Apart's tips on [drop-down menus and horizontal style](http://www.alistapart.com/articles/horizdropdowns).