# Intro to Graphic Design

## Terms

1. Design
2. Development
3. Sitemap
	- List of pages and sections on our website (sitemap.xml)
4. Wireframe
5. Design System
	- It is a set of rules and components that we build for our website
	- Basic Design System rules - Color, Typography, Spacing, Buttons, Forms, Images, Cards
6. Token
	- Token is a single rule about your design
	- **name = value** (Eg: page-background = white, padding-large = 32px)
7. Primitive Token
	- Single raw value (for Token)
	- Eg: brand-blue = #2684FC
8. Sematic Token
	- Sematic Token references Primitive Token
	- Eg: button-color = brand-blue
9. Absolute Sizing
	- When element has a strict size which is unaffected by anything else in the design
10. Relative Sizing
	- When size of an element varies depending on the size of another element
11. Responsive Design
	- Change the element size responsive to screen
12. Adaptive
	- Properties the use for responsive and adoptive
13. Viewport Height (VH)
	- VH is a percentage % of the measurements of the Height an element takes up relative to the viewport
14. Viewport Width
	- VW is a percentage % of the measurements of the Width an element takes up relative to the viewport
15. CSS
16. Viewport
	- Just what the browser can see at any one time
	- Using viewport can be great for big sections you want to let take up the entire page
17. em
	- em is a size that relative to parent element font size
18. rem
	- stand for root em
	- It size relative to the root font size of your browser
19. clamp
	- Clamp are the easiest way to scale an element relative to the viewport size without getting so huge or small that they break your design
	- clamp(2rem, 7vw, 6rem) // Syntax clamp(min value, relative value, max value)
	- Visit [Clamp() Function Calculator | Marc Bacon](https://www.marcbacon.com/tools/clamp-calculator/)
20. Stylesheet
21. Selector
22. Property
23. Value
	- Example of selector, property & value
	- `selector { property: value }`
24. User Experience / UX
	- What do you want visitor to do on your website?
	- How can you make it easier or more enjoyable?
	- Answer: Simple and enjoy as possible

---

Below Lessons are from **[GCF Global](https://edu.gcfglobal.org/en/beginning-graphic-design/)**

## Typography [^1]

Typography is the style or appearance of text.

**Some Common Types of Fonts**

- Serif
	- Classic Look
	- Use for: Traditional Projects like Print Publications (magazine, newspaper)
- Sans Serif
	- Clean & Modern
	- Use for: Computer Screen, tablets or smartphones
- Display
	- Decorative nature
	- Use for: small amount of text like in title, headers or more graphic heavy designs
	- Check Fonts like: Script, Blackletter, ALL CAPS, Plain fancy

![Typography Example](../assets/Typography-Example.jpg)

> [!tip] When deciding which font to use for a project - **Less is more**

- It is best to limit yourself to one or two fonts per project.
- If you need more contrast, try repeating one of your fonts in different size, weight or style.
- Opposite Attracts is also true for font / Different but complementary
	- For examples: San Serif with Serif, Short with Tall, Decorative with Simple

### Typography Terms

1. Hierarchy
	- Used to guide the reader's eye to whatever is most important (using different level of emphasis)
2. Leading
	- space between lines of text (aka: Line Spacing)
3. Tracking
	- Character spacing
4. Kerning
	- Space between specific characters

## Color / Color Theory [^2]

The Basics: The mix of primary, secondary and Tertiary colors make a color wheel.

Primary Colors: <span style="color:rgb(255, 0, 0)">Red</span>, <span style="color:rgb(0, 112, 192)">Blue</span>, <span style="color:rgb(255, 225, 0)">Yellow</span>
Secondary Colors: <span style="color:rgb(255, 192, 0)">Orange</span>, <span style="color:rgb(0, 176, 80)">Green</span>, <span style="color:rgb(112, 48, 160)">Purple</span>
Tertiary Colors: <span style="color:rgb(199, 21, 133)">Red Violet</span>, <span style="color:rgb(138, 43, 226)">Blue Violet</span>, <span style="color:rgb(13, 152, 186)">Blue Green</span>, <span style="color:rgb(154,205,50)">Yellow Green</span>, <span style="color:rgb(255,174,66)">Yellow Orange</span>, <span style="color:rgb(255, 83, 73)">Red orange</span>

### Color Terms

1. Hue
	- Just another words for **"Color"**
2. Saturation
	- Refers to Intensity (which appears subtle or Vibrant)
3. Value
	- How dark or light the color is from Black to White
4. Tones
	- Lighter
	- Darker
	- Desaturated
5. Sade
6. Tint

> [!tip] How to choose a correct color for your project! Use **Color Harmony**

### Color Harmony

Color Harmony is a tried and true formula which applied in color wheel

#### Color Harmony Formulas

1. Monochromatic
	- It use one color (or) Hue
	- With different level of saturations or values
2. Analogous
	- Uses colors that are next to each other on the wheel
3. Complementary
	- Are opposite each other
4. Split Complementary
	- Uses the color on either side of the compliment
5. Triadic
	- Uses three color that are evenly spaced, forming a perfect triangle △
6. Tetradic
	- Form a rectangle ▭ on the wheel (using not one but two complementary color pairs)
	- This formula works best if you let one color dominate while the others serve as an accent

### Color Theory - Dos & Don'ts

- Don't use Vibrate colors
	- The Solution is start with one color and try adjusting it lightness, darkness or saturation
- Readability
	- Color shout be legible, engaging & easy on the eyes

### Color Theory Tips

- Every Color sends a message
	- Bright colors - Tends to have a fun or modern vibe
	- Desaturated Color - Often appear more business-like
- Find ideas from all kind of places
	- Example - Advertising, Branding, Famous work of art

## Layout & Composition [^3]

- Layout & Composition are foundation of Design
- To master Layout & Composition - **Think like a designer**

### Five Basic Principles

1. Proximity
	- Use visual space to show relationship in your content
	- Make sure that related items grouped together
	- Non related items to be separated
2. White space
	- It's an important part of every composition
	- It also means negative spaces between image, lines and so on
3. Alignment
	- The important thing is to be consistent
	- Make a "Grid" and arrange your content
4. Contrast (also closely tied to [[Graphic-Design#Typography Terms|Hierarchy]])
	- Simply means that one item is different from another
	- Catch the reader's eye, create emphasis or call attention to something important
	- Some Strategies to create contrast
		- You can use color
		- Adjust size, shape or visual weight of an object
		- Use contrasting styles of text
5. Repetition
	- Every project should have a consistent look and feel
	- Repeating or echoing certain elements

## Images [^4]

- Images are more than just decoration
- It's a hook that draws the viewer in

**Tips**

- Find _High-Quality images_ for any type of project
	- Sharp
	- Clear
	- No distortion
- Cosmetic adjustment let you enhance certain image quality
	- Like Brightness
	- Contrast
	- Saturation
	- Color

Better watch the actual video - [Beginning Graphic Design: Images](https://youtu.be/MELKuexR3sQ?si=P234Y1QPmBRNPb-o)

## Fundamental of Design [^5]

- It is a basis of every digital medium

### Elements of Design

1. Line
	- It can be Fat, Thin, Wavy, Jagged
	- It used as emphasis, or divide, or organize content, or even guide the viewer's eye
	- Pay attention to things like **Weight**, <span style="color:rgb(0, 176, 80)">Color</span>, Texture, Style
2. Shape
	- Shape is any Two Dimensional area with recognizable boundary
	- It falls into 2 different categories
		- Geometric / Regular
		- Organic / Free form
	- It's a vital part of communication ideas visually
	- It can help us to organize, or Separate content, or Create simple illustrations
3. Form
	- When shape become a 3D we call it a Form
	- It can be exist in real world / It can be create using techniques like light, shadow & Perspective to create the illustration depth
4. Texture
	- It is a physical quality of a surface
	- In design it adds depth and Tactility
5. Balance
	- It is a equal distribution of visual weight
	- It can be effected by many things including Color, Size, Number or Negative Space

**Tips**

- **Rule of Thirds** - Many people use this strategy, it divide the work area into a 3x3 Grid

![3x3 Grid](../assets/balance_rule_thirds.jpg)

![Scientific Path](../assets/balance_thirds_path.jpg)

- Better watch the YouTube video [Beginning Graphic Design: Fundamentals of Design]([Beginning Graphic Design: Fundamentals - YouTube](https://www.youtube.com/watch?v=YqQx75OPRa0))

## Branding & Identity [^6]

**Branding** is what other people think
- About you
- Your company
- Your product
- Your service

**Visual Identity** is what that brand looks like
- From your logo to your color of choices
- Understand visual identity can help you make more thoughtful design decisions
- Visual Identity is kind a like preview of your brand
- Visual Identity isn't just a marketing tool

### Main components of Visual Identity

1. Logo
	- What identifies your brand using particular mark, type design or both
	- Effective logo tends to be simple
2. Color
	- Helps define your brand in a very powerful way
	- Main color derived from company logo
	- Define your brands personality and style
3. Typography
	- Text is one of the simpler aspect of identify but it can be surprising expressive 
	- Most brand choose 2 to 3 fonts (often inspired by logo)
4. Images
	- Images are huge part of building a unique identity
	- In professional - Images are created for the brand

[^1]: [Beginning Graphic Design: Typography](https://edu.gcfglobal.org/en/beginning-graphic-design/typography/1/)
[^2]: [Beginning Graphic Design: Color](https://edu.gcfglobal.org/en/beginning-graphic-design/color/1/)
[^3]: [Beginning Graphic Design: Layout and Composition](https://edu.gcfglobal.org/en/beginning-graphic-design/layout-and-composition/1/)
[^4]: [Beginning Graphic Design: Images](https://edu.gcfglobal.org/en/beginning-graphic-design/images/1/)
[^5]: [Beginning Graphic Design: Fundamentals of Design](https://edu.gcfglobal.org/en/beginning-graphic-design/fundamentals-of-design/1/)
[^6]: [Beginning Graphic Design: Branding and Identity](https://edu.gcfglobal.org/en/beginning-graphic-design/branding-and-identity/1/)