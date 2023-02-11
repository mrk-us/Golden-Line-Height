![Golden Line Height Cover Image](https://s3-alpha-sig.figma.com/plugins/1203442582691456980/47654/94334941/03b859dc-6da8-4d11-a324-a73437e99f15-cover?Expires=1676851200&Signature=ieaSpEPClMhp2R0qah59K~Qw8PergKvZ3LUe0vSv20DCnD7~64JmDmCRRr3F-a5mm3Yj94xo77J5oXezhBPvg0bD17iw3~v6iz33UJVtkXTZSuDIWNG-fVbnNtPR~z4hNN6XB~FZJzGDqg-LzZeQK5uzK-cXpso0mmMaPyv7clRpRbctDhhANXQTFLPqzSsuCg4BXdudwimkTOUGokBoOEVX9NmkRh6MmgYxxCS9554bEZWgPrAVjAEDiChBUa-0zNBKQfLAQmcxBcxTOOGeO5jLSbyHsEWjARvUuzNxNMsphDf0mrdoaz9Z8bAP6VHAEda3e4g9zR~x1~wkzjcn3Q__&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4 'Cover Image')

## Description

A Figma plugin that automatically determines the line height of one or more text layers using the Golden Ratio, with an option to round to the nearest number divisible by 8 for integration into an 8pt grid.

The plugin takes into consideration both the font size and line width to determine the ideal line height.

Made by Markus Wilson (hi@mrk.us)

---

Below are the steps to get your plugin running. You can also find instructions at:

https://www.figma.com/plugin-docs/setup/

This plugin template uses Typescript and NPM, two standard tools in creating JavaScript applications.

First, download Node.js which comes with NPM. This will allow you to install TypeScript and other
libraries. You can find the download link here:

https://nodejs.org/en/download/

Next, install TypeScript using the command:

npm install -g typescript

Finally, in the directory of your plugin, get the latest type definitions for the plugin API by running:

npm install --save-dev @figma/plugin-typings

If you are familiar with JavaScript, TypeScript will look very familiar. In fact, valid JavaScript code
is already valid Typescript code.

TypeScript adds type annotations to variables. This allows code editors such as Visual Studio Code
to provide information about the Figma API while you are writing code, as well as help catch bugs
you previously didn't notice.

For more information, visit https://www.typescriptlang.org/

Using TypeScript requires a compiler to convert TypeScript (code.ts) into JavaScript (code.js)
for the browser to run.

We recommend writing TypeScript code using Visual Studio code:

1. Download Visual Studio Code if you haven't already: https://code.visualstudio.com/.
2. Open this directory in Visual Studio Code.
3. Compile TypeScript to JavaScript: Run the "Terminal > Run Build Task..." menu item,
   then select "npm: watch". You will have to do this again every time
   you reopen Visual Studio Code.

That's it! Visual Studio Code will regenerate the JavaScript file every time you save.
