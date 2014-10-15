Companies Color Database
===============

This is the database of the colors for the companies used in [toolbelt.pixelapse.com/color](http://toolbelt.pixelapse.com/color). Feel free to add new company colors to this list!


##Examples

You can easily search for colors used by companies here: http://toolbelt.pixelapse.com/color. These are some examples of how the database of colors will be used in the tool:

* https://toolbelt.pixelapse.com/color/twitter (single color)
* https://toolbelt.pixelapse.com/color/microsoft (multiple primary colors)
* https://toolbelt.pixelapse.com/color/Apple%201976 (multiple primary colors)


##Adding a company

1. Fork this branch

2. Fill in the template below and append it to the end of `colordata.json`.
  * At the very least, you need to have `name`, `url-web` and one `colors-primary`
  * Colors should be in hexadecimal format without '#' symbol
  * Bonus points for tracking down their elusive branding guidelines page
  * Remember to add commas to the trailing } of the company before your's!

  ```
    {
      "name": "",
      "url-brand": "",
      "url-web": "",
      "url-logo": "logos/",
      "year-start": "",
      "year-end": "",
      "notes": "",
      "colors-primary": [
        ""
      ],
      "colors-secondary": [
        ""
      ]
    }
  ```

3. Find a high-resolution image of the company's logo and include it in `logos` folder. PNG and SVG are preferred over JPEG.

4. Submit a pull request!


##Improvements and Bugs

Please feel free to open a new issue if you notice that there are colors that are wrong. We welcome your suggestions or any other bugs which you may have come across.


##Extensions

You are welcome to create your own little project based on this colors database! Will appreciate a link back here.
