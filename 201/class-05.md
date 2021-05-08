# **Class 01 Developer Payne's First Adventure**

## **Section Selector**:
  - [**Food For Thought**](#food-for-thought)
  - [**Images**](#images)
  - [**Color**](#color)
  - [**Text**](#text)

---

## **Food For Thought**
- Text

---

## **Images**
- Great images help make the difference between an average-looking site and a really engaging one
- Save Images In the Right Format
- Save images at the right size
- Use the correct resolution
- it is good practice to create a folder for all of the images the site uses.
- Whenever you have many different
colors in a picture you should use a JPEG.
- Use GIF or PNG format when saving images with few colors or large areas of the same color.
- Images you use on your website should be saved at the same width and height that you want them to appear on the page.
- When cropping images it is important not to lose valuable information. It is best to source images that are the correct shape if possible
- Images created for the web should be saved at a resolution of 72 ppi
- Vector images differ from bitmap images and are resolution-independent
- Vector images are commonly created in programs such as Adobe Illustrator.
- Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations

## **Key Takeaways**
- The <img\> element is used to add images to a web page.
- You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
- You should save images at the size you will be using them on the web page and in the appropriate format.
- Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

---

## **Color**
* color: Specify the color of text inside the tag
* 3 types of ways to write the color value
* RGB Values: express colors in terms of how much red, green and blue ex:(100,100,90)
* Hex Codes: six digit codes that represent the amount of red green and blue preceded by a pound or hash
* Color names: 147 predefined color names that are recognized
* You can use * & * at the start and end in css to add a comment 
* background-color: is the code to change the background
+ Css treats each HTMl element as if it appears in a box and background-color property sets that color
+ The same 3 values for color can be used for background color
+ if no background is listed it will be transparent 
+ most browsers have white as default but be careful to not assume and check that before you submit something
+ padding is used to separate the text from the edges of the box  
+ When Picking foreground and background colors it is important to ensure that there is enough contrast for the text to be legible
+ A lack of contrast is particularly a problem for those with visual impairments and color blindness
+ If you want people to read a lot of text on your page, however, then too much contrast can make it harder to read
+ For long spans of text, reducing the contrast a little bit improves readability
+ You can reduce contrast by using dark gray text on a white background or an off-white text on a dark background
+ CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
+ The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child elements).
+ Because some browsers will not recognize RGBA colors, you can offer a fallback so that they display a solid color. If there are two rules that apply to the same element, the latter of the two will take priority  
+ To create the fallback, you can specify a color as a hex code, color name or RGB value, followed by the rule that specifies an RGBA value. If the browser understands RGBA colors it will use that rule. If it doesn't, it will use the RGB value  
+ CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values
+ Hue: Hue is the colloquial idea of color HSL represents this as a color well although it may be shown as a slider it will be expressed as an angle between 0 and 360 degrees
+ Saturation: This is the amount of gray in color normally represented as a % 100% is full saturation and 0% is a shade of gray
+ Lightness: this is the amount of white (lightness) or black (darkness) in a color
+ Lightness is represented as a percentage 0% lightness is black and 100%  50% would be considered normal 
+ Lightness is a different concept to brightness. Graphic design software (such as Photoshop and GIMP) have color pickers that use hue, saturation, and brightness — but brightness only adds black, whereas lightness offers both white and black.
+ HSL: The value of the property starts with the letters hsl, followed by individual values inside parentheses for
+ HSLA: color property allows you to specify color properties using hue, saturation, and lightness as above, and adds a fourth value which represents transparency 
+ Alpha: is expressed as a number between 0 and 1.0 0.5 represents 50% Transparency and a 0.75 represents 75%
+ Because older browsers do not recognize HSL and HSLA values, it is a good idea to add an extra rule which specifies the color using a hex code, RGB value, or color name. This should appear before the rule that uses the HSL or HSLA value
+ This means that if the browser understands HSL and HSLA colors, it will use that rule; and if it does not, it will use the first rule 

## **Key Takeaways**
- Color not only brings your site to life, but also helps convey the mood and evokes reactions.
- There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
- Color pickers can help you find the color you want.
- It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
- CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.

---

## **Text**
**Serif**: Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs  
**Sans-Serif**: Sans-serif fonts have straight ends to letters and therefore have a much cleaner design  
**Monospace**: Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts have different widths.)
- When choosing a typeface, it is important to understand that a browser will usually only display it if it's installed on that user's computer 
- 



## **Key Takeaways**
- There are properties to control the choice of font, size, weight, style, and spacing.
- There is a limited choice of fonts that you can assume most people will have installed.
- If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
- You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.
- You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.

---

## [**Code 201 Reading Notes**](/201/201homepage.md)
  1. [Class 00](/201/class-01.md)
  2. [Class 01](/201/class-02.md)
  3. Day 02
  4. Day 03
  5. Day 04
  6. Day 05
  7. Day 06
  8. Day 07
  9. Day 08
  10. Day 09
  11. Day 10
  12. Day 11
  13. Day 12
  14. Day 13
  15. Day 14
<!-- DrP E-Sign Up, Up, Down, Down, Left, Right, Left, Right, B, A, Start -->
