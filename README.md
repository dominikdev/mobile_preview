Mobile Preview Framework
==============
This is a bare bones framework that i developed to help show how responsive websites are displayed on a mobile device. I find it useful when previewing responsive website designs for my clients, or when creating informational pages about personal projects. It allows me to display both versions on a non mobile device. 

This is not intented to be a replacement for actual mobile testing of a website as it only forces the website to display at a resolution of 320px by 568px (Non-Retina Iphone 5). There is many more factors that must be accounted for when optimizing a website for mobile.

View Project Page: [Mobile Preview Framework](http://bit.ly/mobpreview)

Screenshot
--------------
![Screenshot](http://dominikdev.com/resources/github/screenshots/mobile_preview.png "Screenshot")

Dynamic Preview
--------------
The dynamic preview has an input field to display any URL you choose. This input will also accept the preview of local files. This is useful to help you visualize a page that you are working on. However if you intend to display a certain website to a different party you will want to use the static preview.

Static Preview
--------------
The static preview is extremely simplistic. This is the full extent of the HTML code:

```HTML
<div class="wrapper">
    <div id="mobile-preview-outer" class="iphone">
           <div id="mobile-preview-inner">
                    <iframe class="mp-iframe" src="YOUR URL HERE"></iframe>
           </div>
    </div>
</div>
```

Previewing your website is extremely simple. Just replace **YOUR URL HERE** with a URL of your choice, upload the HTML and CSS files, and you're ready to go!

Project Notes
--------------
- *Please note that this framework will only work on RESPONSIVE websites and not mobile websites.*

- *This should not be used as a replacement for actually testing your design on a mobile device. It only mimics the screen resolution of a mobile device, not the characterstics of a mobile browser*

License
--------------
Free to use in any way you desire! 