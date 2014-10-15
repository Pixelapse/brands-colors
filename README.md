<img src="https://s3.amazonaws.com/pixelapse-assets/blog/colors-db/blog_colors_db.png" width="100%" height="auto" alt="Brands Color Database" title="Brands Color Database">
===============

This is the database of the colors for the brands used in [toolbelt.pixelapse.com/color](http://toolbelt.pixelapse.com/color). We compiled an original list of 160 brands with more than 200 colors for our color tool. With it, we hope to provide more information to designers to aid them in their color choices.

Feel free to add more brand colors to this list!


##Examples

You can easily search for colors used by various brands here: http://toolbelt.pixelapse.com/color. These are some examples of how the database of colors will be used in the tool:

* https://toolbelt.pixelapse.com/color/yc (single color)
* https://toolbelt.pixelapse.com/color/microsoft (multiple primary colors)
* https://toolbelt.pixelapse.com/color/apple%201976 (multiple primary colors)
* https://toolbelt.pixelapse.com/color/black (color used by multiple brands)



##Adding a brand

1. Fork this branch

2. Fill in the template below and append it to the end of `brand-color.json`.
  * At the very least, you need to have `name`, `url-web` and one `colors-primary`
  * Colors should be in hexadecimal format without '#' symbol
  * Bonus points for tracking down their elusive branding guidelines page
  * Remember to add commas to the trailing } of the brand before your's!

  ```
    {
      "name": "",
      "url-branding": "",
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

You are welcome to create your own little project based on this colors database! We would appreciate a link back here!
