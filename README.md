### purpose

- I choose to do the vary popular website for learning and practicing purpose
  not to replacing or making many of them.

### Create the index.html and style.css files

- In index.html file write `!` then press `Tab key` to give you `html boilerplate`.
- In the head part of the index.html file add a link to relate the index.html file with the style.css file by adding
  <link rel="stylesheet" href="style.css" />
- Start writing html code inside the body tag.

### Emmet plugin

- Emmet is a set of plug-ins for text editors that allow for high-speed coding and editing in HTML.
  For more reading: `https://emmet.io/`

eg. `ul.activities*2>(p^li*3)` then `Tab key` will create for you this html skeleton

<ul class="activities">
  <p></p>
  <li></li>
  <li></li>
  <li></li>
</ul>
<ul class="activities">
  <p></p>
  <li></li>
  <li></li>
  <li></li>
</ul>

### Lorem Ipsum

-it gives a placeholder text commonly used to demonstrate the visual form of a document

eg. `p>lorem5` then `Tab key`

 <p>Lorem ipsum dolor sit amet.</p>

### Font Awesome

1. Downloading and hosting Font Awesome yourself.
2. The `/css/all.css` file contains the core styling plus all of the icon styles that you’ll need when using Font Awesome. The `/webfonts` folder contains all of the typeface files that the above CSS references and depends on.
3. Copy the entire `/webfonts` folder and the `/css/all.css` into your project’s static assets directory (or where ever you prefer to keep front end assets or vendor stuff).
4. Add a reference to the copied `/css/all.css` file into the `<head>` of each template or page that you want to use Font Awesome on.

### Animista CSS animation is used for the animation part

- This is the link for animista website `https://animista.net`

### Performance consideration for animation

Animating properties is not free, and some properties are cheaper to animate than others. For example, animating the `width` and `height` of an element changes its geometry and may cause other elements on the page to move or change size. This process is called layout (or reflow in Gecko-based browsers like Firefox), and can be expensive if your page has a lot of elements. Whenever layout is triggered, the page or part of it will normally need to be painted, which is typically even more expensive than the layout operation itself.

Where you can, you should avoid animating properties that trigger layout or paint. For most modern browsers, this means limiting animations to `opacity` or `transform`, both of which the browser can highly optimize; it doesn’t matter if the animation is handled by JavaScript or CSS.

More information check this link: `https://developers.google.com/web/fundamentals/design-and-ux/animations/animations-and-performance`

#### General syntax of the background property

background: [background-image][background-position] / [background-size][background-repeat] [background-attachment][background-origin] [background-clip][background-color];
