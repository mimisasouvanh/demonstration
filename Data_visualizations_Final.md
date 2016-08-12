
# Data visualization style guidelines for Office Add-ins

Good data visualizations help users find insights in their data. They can use those insights to tell stories that inform and persuade. This article provides guidelines to help you design effective data visualizations in your add-ins for Excel and other Office apps.

We recommend that you use [Office UI Fabric](http://odux/fabric/?page=overview) to create the chrome for your data visualizations. Office UI Fabric includes styles and components that integrate seamlessly with the Office look and feel. The following figure shows a data visualization in an add-in that uses Fabric.

[![Title: images/msohtmlclipclip_image001.png - Description: C:\Users\lauragra\AppData\Local\Packages\Microsoft.Office.OneNote_8wekyb3d8bbwe\TempState\msohtmlclipclip_image001.png](https://raw.githubusercontent.com/mimisasouvanh/demonstration/master/images/msohtmlclipclip_image001.png - Description: C:\Users\lauragra\AppData\Local\Packages\Microsoft.Office.OneNote_8wekyb3d8bbwe\TempState\msohtmlclipclip_image001.png)](https://raw.githubusercontent.com/mimisasouvanh/demonstration/master/images/msohtmlclipclip_image001.png)

## Data visualization elements

Data visualizations share a general framework and common visual and interactive elements, including titles, labels, and data plots, as shown in the following figure.

### Chart titles

Follow these guidelines for chart titles:

*   Make your chart titles easily readable. Position them to create a clear visual hierarchy in relation to the rest of the chart.
*   In general, use sentence capitalization (capitalize the first word). To create contrast or to reinforce hierarchies, you can use all caps, but all caps should be used sparingly.
*   Incorporate the [Office UI Fabric type ramp](http://odux/fabric/?page=features) to make your charts consistent with the Office UI, which uses Segoe. You can also use a different typeface to differentiate chart content from the UI.
*   Use sans-serif typefaces with large counters.

The following examples show serif and sans-serif typefaces used in chart titles. Notice how the scale contrast and effective use of white space create a strong visual hierarchy.

### Axis labels

Make your axis labels dark enough to read clearly, with adequate contrast ratios between the text and background colors. Make sure that they are not so dark that they compete with data ink.

Light grays are most effective for axis labels. If you’re using Fabric, see the [Neutral Colors palette](http://odux/fabric/?page=features).

### Data ink

The pixels that represent the actual data in a chart are referred to as data ink. This should be the central focus of the visualization. Avoid the use of drop shadows, heavy outlines, or unnecessary design elements that distort or compete with the data. Use gradients only when data values are tied to color values. Avoid three-dimensional charts unless a measurable, objective value is bound to a third dimension.

### Color

Choose colors that follow operating system or application themes rather than hardcoded colors. At the same time, make sure that the colors you apply do not distort the data. Misuse of color in data visualizations can result in data distortion and incorrect reading of information.

For best practices for use of color in data visualizations, see the following:

[Why rainbow colors aren't the best option for data visualizations](http://www.poynter.org/2013/why-rainbow-colors-arent-always-the-best-options-for-data-visualizations/224413/)

[Color Brewer 2.0: Color Advice for Cartography](http://colorbrewer2.org/)

[I Want Hue](http://tools.medialab.sciences-po.fr/iwanthue/)
