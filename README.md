# pixelhaze-tooltips-plugin
A tooltips plugin for Squarespace.

This plugin enables the creation of tooltips for specified keywords on your Squarespace site using jQuery. When users hover over keywords wrapped in <strong> tags, a tooltip with a description is displayed.

Features:
1. Automatically generates tooltips for predefined keywords.
2. Easily configure your keywords and their associated descriptions.
3. Minimal impact on site performance.
4. No additional dependencies required beyond jQuery.

Installation:
1. Add custom CSS to style the tooltips and trigger elements. This ensures your tooltips are visually appealing and properly positioned.
2. Include the jQuery library in the header of your site using Squarespace's Code Injection feature.
3. Copy and paste the JavaScript code into the footer of your site under Code Injection. This script initializes the tooltip functionality and dynamically assigns tooltips to <strong> tags containing your predefined keywords.

How to Use:
1. In the website editor in Squarespace, make the word you wish to become a tooltip BOLD.
2. Update the yourKeywords object in the JavaScript code with your desired keywords and descriptions. 
3. Visitors to your site can hover over the keywords to see the tooltips.
