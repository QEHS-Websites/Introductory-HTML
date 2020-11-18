# Image Lesson and Ideas
Progressions, URLs, and Hints

**UNDER CONSTRUCTION**
General Steps
1. Create a GitHub Repository for this lesson set
  - Images / Original Images : for downloaded images not ready for Hosting Yet
2. Attain some images
  - Download from the Internet
    - Must have cite attribute `<blockquote cite="">`
    - Must have original URL `<!-- Date Accessed -->`
    - Must have space for aspect ratio `<!-- Aspect Ratio: Width:XX Height:XX -->`
  - Use phone or other device and get images to project folder (i.e. email)
3. Inspect Images for overall memory size and cropping
  - Using an online tool
  - http://webresizer.com/
  - http://resizeimage.net/
  - Demo: image memory size and cropping
4. Aspect Ratio Calculations
  - Inspect Aspect Ratio in Image / Folder Properties / Details
  - Record both numbers in webpage
  - Display Image in website
  - Calculate Scale factor: larger or smaller (i.e. guess and check)
  - Change display attributes until correct
5. Example Calculations for Scale Factor in Aspect Ration
  - Put these numbers in the HTML Tag Attributes
  - Bigger: scale factor of 1.5 (half bigger)
    - Width: 625x1.5=
    - Height: 352x1.5=
  - Smaller: scale factor of 0.5 (half smaller)
    - Width: 625x0.5=
    - Height: 352x0.5=
6. Create HTML4 Tag, <a href="">Click Here</a>
  - Explore img, HTML4 introduction to backwards capability, with downloaded image referenced in alt, examples below
  - displaying image with alternate pathway
  - adding style override
  - adding clickable link
  - adding the image as a clickable map (create the shape at (0,0) then move the shape, then resize with width and height or diameter)
  - changing the image as a floating image or inline block image
  - adding the image to the background of a page (CAUTION: decreases contrast)
  - adding the image to the background of a paragraph tag (CAUTION: decreases contrast)

## Getting an Image Ready for Hosting, thoughts and considerations
- Rule of Third's
- Use of Colour
- Foreground and Background considerations when cropping
- CSS Properties will handle images a lot better than hardcoding aspect ratio

---

## Creating HTML4 and HTML5 Full Legacy Tags in Steps

### Example: displaying image with alternate pathway
- img: src and alt are required
- alt can store URLs, Pathways, and image descriptions
- alt is used to load image from Internet or Folder/Pathway
- Question: can more than one alt be added?

```HTML
<img src="[directory/fileName.extension]" alt="[directory/fileName.extension] | [Image Description]" title="[HoverOver Display]]" height="[Number in Pixels, i.e. 100]" width="100"/>
```

### Example: adding style override
- Note: here the style sheet will override the image height and weight attributes
- For example {width: 100%}

```HTML
<img src="[directory/fileName.extension]" alt="[directory/fileName.extension] | [Image Description]" title="My Profile" style="height:100px;width:100px"/>
```
- Note: using the style attribute here prevents the index.css from changing the image
- **Excellent use of attributes for hardcoded aspect ratio**

### Example: adding clickable link
- Image as a link, this is just an example, makes it a clickable link
- Note: the default.asp is like a literal template, makes all links the same prefix

```HTML
<a href="default.asp">
  <img src="[directory/fileName.extension]" alt="[directory/fileName.extension] | [Image Description]" title="My Profile" style="height:100px;width:100px">
</a>
```

### Example: adding the image as a clickable map (create the shape at (0,0) then move the shape, then resize with width and height or diameter)
- image maps are images with clickable areas
- to figure out the coordinates, the notations are like Processing-JAVA, see summary notes below
- able to guess and check in browser with mouse-over, also see debugging hint
- CAUTION: in img use style here since .css tag or separate file can override img tag width and height, causing issues with hardcoded mapping
  - needs to be tested when writing CSS Files
- might need to add inline or floating, see more examples below

Summary Notes for Mapped Images
- Possible Shapes: ```<area shape="default|rect|circle|poly">```
  - See Mapping Image / index.html for additional notes and format
  - default: entire region of image
  - rect: x1,y1,x2,y2	... Specifies the coordinates of the top-left and bottom-right corner of the rectangle (shape="rect")
  - circle: x,y,radius ... Specifies the coordinates of the circle center and the radius (shape="circle")
  - poly: x1,y1,x2,y2,..,xn,yn	Specifies the coordinates of the edges of the polygon. If the first and last coordinate pairs are not the same, the browser will add the last coordinate pair to close the polygon (shape="poly")
- Possible Targets ```<area target="_blank|_self|_parent|_top|framename"> ```
  - ```_blank```: opens a new window, uses browser navigation
  - ```_self```: opens in the same frame, still uses browser navigation
  - others are useful for researching
- To Create Mapped Images using online tools: Image Map Generator at <a href="https://www.image-map.net/">https://www.image-map.net/</a>

Debugging Hint: use ```shape=```, ```coords=```, ```alt=""```, ```href=""``` and ```target="_blank"```
- Will open the hyperlink in another window
- Will show the outline of the frame in the mapped image for adjustments
- Hint: will help debug polygons

```HTML
<!DOCTYPE html>
<html>
<body>
<h2>Image Maps</h2>
<p>Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:</p>
<img src="[directory/fileName.extension]" alt="[directory/fileName.extension] | [Image Description]" title="My Profile" usemap="#workmap" style="height:400px;width:379px">
<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>
</body>
</html>
```

### Example: changing the image as a floating image or inline block image
- For example: to make the image float to the left or right of some text

```HTML
<!DOCTYPE html>
<html>
<body>
<h2>Floating Images</h2>
<p><strong>Float the image to the right:</strong></p>
<p>
<img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
A paragraph with a floating image. A paragraph with a floating image. A paragraph with a floating image.
</p>
<p><strong>Float the image to the left:</strong></p>
<p>
<img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
A paragraph with a floating image. A paragraph with a floating image. A paragraph with a floating image.  
</p>
</body>
</html>
```

- Displaying the image as an inline block

```HTML
<style>img {display: inline-block;}</style>

<p>Some text <img src="smiley.gif" alt="Smiley face" width="42" height="42"> some text.</p>
```

```HTML
<!-- Original Inline Example -->
<!DOCTYPE html>
<html>
<head>
<style>
img {
    display: inline-block;
}
</style>
</head>
<body>

<p>An img element is displayed like this:</p>

<p>Some text <img src="smiley.gif" alt="Smiley face" width="42" height="42"> some text.</p>

<p>Change the default CSS settings to see the effect.</p>

</body>
</html>
```

### Example: adding the image to the background of a page (CAUTION: decreases contrast)
- Using a background image
- Image will repeat itself if smaller than the background

```HTML
<body style="background-image:url('clouds.jpg')">
```

### Example: adding the image to the background of a paragraph tag (CAUTION: decreases contrast & readability)
- Adding a background image to a paragraph

```HTML
<p style="background-image:url('clouds.jpg')">
```

### Example: Finally, using the HTML5 picture tag and backwards compatibility of img tag
- Using the <picture> TAG in HTML5
- Requires the meta tag, viewport
- Will show various sized images given different viewports
- img TAG is needed for backwards compatibility to HTML4 and less
- When the browser is resized, different images are shown, originally different sizes

```HTML
<picture>
  <source media="(min-width: 650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width: 465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
</picture>
<p>Resize the browser to see different versions of the picture loading at different viewport sizes.
The browser looks for the first source element where the media query matches the user's current viewport width,
and fetches the image specified in the srcset attribute.</p>
<p>The img element is required as the last child tag of the picture declaration block.
The img element is used to provide backward compatibility for browsers that do not support the picture element, or if none of the source tags matched.
</p>
<p><strong>Note:</strong> The picture element is not supported in IE12 and earlier or Safari 9.0 and earlier.</p>
```

---

# Ideas to Include
Use boarder around image DIVs

---
