# Core Modules Assignment 3
---
**Q1.** In CSS, a media query is a feature that allows you to apply specific styles to a web page based on certain conditions, such as the characteristics of the device or the viewport size. It enables you to create responsive designs that adapt to different screen sizes and devices.

The purpose of using media queries is to create styles that are tailored to different devices or conditions, ensuring optimal user experience across various screen sizes and orientations. By applying different styles based on the media query conditions, you can adjust the layout, typography, colors, and other visual aspects of your website or application.


**Q2.** To define a media query in CSS, you use the `@media` rule followed by one or more conditions enclosed in parentheses. Here's the general syntax:
```css
@media <media-condition> {
  /* CSS rules to apply when the media condition is true */
}
```
The `<media-condition>` part is where you specify the conditions that determine when the styles within the media query block should be applied. Media conditions consist of one or more media features and their corresponding values.

Here's an example of a media query that targets devices with a maximum width of 600 pixels:
```css
@media (max-width: 600px) {
  /* CSS rules to apply for devices with a maximum width of 600px */
}
```
In the example above, `(max-width: 600px)` is the media condition. It uses the `max-width` media feature, which represents the maximum width of the viewport, and sets the value to `600px`. The CSS rules within the media query block will be applied only when the viewport width is 600 pixels or less.

You can also combine multiple conditions using logical operators `(and, or, not)` to create more complex media queries. Here's an example of a media query that targets devices with a maximum width of 600 pixels in portrait orientation:

```css
@media (max-width: 600px) and (orientation: portrait) {
  /* CSS rules to apply for devices with a maximum width of 600px in portrait orientation */
}
```

**Q3.** In responsive web design, breakpoints are specific points or ranges of viewport widths where the layout of a web page is adjusted to accommodate different screen sizes. Breakpoints serve as markers where the design `"breaks"` or changes to adapt to the available space on various devices.

Media queries are used in conjunction with breakpoints to apply specific styles or adjust the layout of elements based on different viewport sizes. By defining breakpoints and using media queries, you can create a responsive design that provides an optimal user experience across a range of devices.

Here's how breakpoints and media queries work together:

**Determining breakpoints:** Breakpoints are typically determined by analyzing common screen sizes and considering the content and layout of your web page. For example, you might choose breakpoints to target small mobile devices, tablets, and desktop screens.

**Defining media queries:** Once you've determined your breakpoints, you can use media queries to apply specific styles at each breakpoint. Each media query consists of a condition that evaluates to true when the viewport matches the specified criteria.

**Applying styles at breakpoints:** Within each media query block, you define the CSS rules that should be applied when the corresponding condition is met. These rules typically involve adjusting the layout, positioning, typography, or other visual aspects of your web page.

Here's an example that demonstrates the use of breakpoints and media queries:

```css
/* Styles for mobile devices */
@media (max-width: 480px) {
  /* CSS rules for small mobile screens */
}

/* Styles for tablets */
@media (min-width: 481px) and (max-width: 768px) {
  /* CSS rules for tablets */
}

/* Styles for desktop screens */
@media (min-width: 769px) {
  /* CSS rules for desktop screens */
}
```

**Q4.** The purpose of using media queries for print media includes:

**Adjusting layout:** Media queries for print media enable you to modify the layout of your web page when it is printed. This can involve removing unnecessary elements that are not suitable for print, rearranging content for better readability, or creating a simplified version of the page optimized for the printed format.

**Controlling typography:** Print media queries allow you to specify different font sizes, line heights, and other typographic properties to improve legibility when content is printed. You can adjust the font styles and sizes to ensure that the text is clear and easy to read on paper.

**Managing colors:** When content is printed, colors may appear differently compared to on-screen display. Media queries for print media enable you to define specific color adjustments, such as changing background colors to white or light shades and adjusting text colors to ensure optimal contrast for printed output.

**Hiding or showing elements:** Media queries for print media can be used to hide or show specific elements selectively when the page is printed. This allows you to control which parts of the web page are included in the print output. For example, you might choose to hide navigation menus, advertisements, or other elements that are not relevant or useful in a printed document.

**Q5.** The orientation media feature in CSS allows you to target styles based on the orientation of the device's viewport. It helps you customize the layout and presentation of your web page depending on whether the device is in a portrait or landscape orientation.

The purpose of the orientation media feature is to provide a more tailored and optimized user experience based on how the user holds or views their device. By utilizing this feature, you can make specific adjustments to the design, layout, or content placement to enhance usability and readability.

Here are a few examples of how the orientation media feature can be useful:

**Responsive layout adjustments:** You can use the orientation media feature to modify the layout of your web page to accommodate the available screen space in portrait or landscape mode. For instance, you might choose to stack elements vertically in portrait mode and display them side-by-side in landscape mode.

**Image and media handling:** By targeting the orientation media feature, you can optimize the presentation of images or media elements based on the available space. For example, you could adjust the dimensions, alignment, or scaling of an image to ensure it fits appropriately in either portrait or landscape mode.

**Typography and readability:** Depending on the orientation, the width and height proportions of the viewport change. You can leverage the orientation media feature to adjust the typography, line lengths, or spacing to maintain readability and legibility of your content.

**Q6.** 
## [One Card Clone Code](https://github.com/vyomPundhir/One_Card_HomePage)

**Q7.**
## [Grid Layout Code](https://github.com/vyomPundhir/Grid_Layout_Page)

**Q8.**
## [One Card Clone Code After Adding Fee Section](https://github.com/vyomPundhir/One_Card_HomePage)

**Q9.**
## [One Card Clone Code After Adding Footer](https://github.com/vyomPundhir/One_Card_HomePage)

**Q10.** 
## [Student Dashboard Table Code](https://github.com/vyomPundhir/Student_Dashboard)