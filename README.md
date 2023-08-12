![Screenshot (195)](https://github.com/shweta-sharma-1009/Css-Properties-/assets/128416925/f964a489-2a40-4810-b1d8-c7efdb01191f)
![Screenshot (196)](https://github.com/shweta-sharma-1009/Css-Properties-/assets/128416925/1fddd7c5-b9ce-40c7-baa2-9304a3ab3997)
![Screenshot (197)](https://github.com/shweta-sharma-1009/Css-Properties-/assets/128416925/98257425-ea22-48c8-b04a-c1b4d6fad56c)
![Screenshot (198)](https://github.com/shweta-sharma-1009/Css-Properties-/assets/128416925/dcd68313-8841-4de5-a17f-94fd702f1a45)
![Screenshot (199)](https://github.com/shweta-sharma-1009/Css-Properties-/assets/128416925/34d7cc74-9b8b-41ff-81e8-eaae62c6d408)
![Screenshot (200)](https://github.com/shweta-sharma-1009/Css-Properties-/assets/128416925/43640830-7645-4903-ae4a-00ce9b67c718)
![Screenshot (201)](https://github.com/shweta-sharma-1009/Css-Properties-/assets/128416925/d8d9dfcb-4e78-4782-9806-e2866e8ec599)

HTML - 
<body>: This tag marks the beginning of the body content of a webpage. Everything that is displayed on the webpage, such as text, images, and other elements, is placed inside this tag.

<div class="offer">: This is a division element that is given a class attribute named "offer". It's often used to group and style specific sections of content. In this case, it might contain information about special offers.

<h4>: This is a heading tag that represents a level 4 heading. It's used to display text in a larger, bold font to create headings or subheadings.

<nav>: This tag represents a navigation section on the webpage. It's used to define a block of navigation links that typically help users move around the website.

<h5>: This is a heading tag similar to <h4>, but representing a level 5 heading. It's commonly used for subheadings under <nav>.

<input type="text">: This is an input element that provides a text input field where users can type in text. It's commonly used for search bars or text entry.

<span>: This tag is used to apply specific styles or behaviors to a small section of text or inline content. In this case, it's used to display an emoji icon, 🔍, which represents a magnifying glass.

<main>: This tag defines the main content of the webpage. It typically contains the central content that the webpage is focused on, such as articles, sections, or other relevant content.

<section class="sale">: This is a section element with a class attribute "sale". It's used to structure and style content within a section, in this case, possibly displaying information about a sale.

<header>: This tag represents the header section of a section or article. It typically contains headings, subheadings, and introductory content for the section.

<h1>: This is a heading tag that represents the highest level of heading (level 1). It's often used for the main title of a page or a major section.

<p>: This tag represents a paragraph of text. It's used to display blocks of text, like descriptions or explanations.

<img>: This tag is used to display images on the webpage. The src attribute specifies the image source (URL or encoded data), and alt provides alternative text that describes the image for accessibility.

<section class="category-1">: Similar to the previous section, this defines a section with a class attribute "category-1". It's used to structure content, possibly for a specific category.

<h1>: Another heading tag for a level 1 heading.

<div class="c1_sub">: A division element with the class attribute "c1_sub". This could represent a subsection within the category.

<h1>: Another heading tag for a level 1 heading, possibly describing a subsection title.

<div class="tr">: Another division element with a class attribute "tr". This might represent a container for a product item.

<p>: A paragraph of text that could describe the product, in this case, a pair of shoes.

Repeat of the above steps for other product items, each containing an image and description.

These HTML tags are used to structure and format the content of a webpage, making it visually appealing and easy to navigate for users.

CSS -
* { ... }: This block sets some basic styles for all elements in the webpage. It ensures that there is no margin or padding by default, and the box-sizing is set to border-box. This means that the element's total width and height will include padding and borders.

.offer { ... }: This block styles an element with the class "offer". It gives it a background gradient from black to a red color (#e74c3c), makes the text white, centers the text, and adds padding on top and bottom.

nav { ... }: This block styles a navigation element. It gives it a black background color with full opacity, centers the text, adds padding on top and bottom, makes it stick to the top of the page (position: sticky), and changes the text color to white.

nav > h5 { ... }: This styles the <h5> elements within the navigation. It makes them display as inline-block, giving them some spacing from the edges of the navigation.

nav > input { ... }: This styles the input element within the navigation. It sets its width to 30%, removes the border, and increases the font size.

nav > input:focus { ... }: This styles the input element when it's in focus (clicked or selected). It removes the default outline.

nav > span { ... }: This styles a <span> element within the navigation. It gives it a light black background color with slight transparency and adds some padding.

.sale { ... }: This styles an element with the class "sale". It sets the padding, font size, and applies a background image. The image is centered, doesn't repeat, and covers the entire element. The text color is white.

.sale > header { ... }: This styles the header element within the "sale" element. It sets the width, adds a semi-transparent black background, and adds some padding.

.category-1 { ... }: This styles an element with the class "category-1". It sets padding and a slightly transparent black background.

.c1_sub { ... }: This styles an element with the class "c1_sub", which appears to be repeated twice. It sets padding, a semi-transparent black background, and adjusts the margin and text color.

.tr { ... }: This styles elements with the class "tr". It sets dimensions, a semi-transparent black background, white text color, and a small amount of padding.

.category-2 { ... }: This styles an element with the class "category-2" using a gradient that goes from black to a darker gray color.

.container { ... }: This styles an element with the class "container". It sets its dimensions to cover the entire viewport height, makes it relative, and hides any overflowing content.

.shoe { ... }: This styles an element with the class "shoe", which seems to represent a shoe image. It sets its dimensions, adds padding, centers it horizontally, adds a margin at the top, and applies a gray box shadow.

.des { ... }: This styles an element with the class "des" (likely for description). It sets the maximum width and text color.

.des > h1 { ... }: This styles <h1> elements within the "des" class. It sets the font size and margin at the bottom.

.des > p { ... }: This styles <p> elements within the "des" class. It sets the font size, margin at the bottom, and line height.

.shoe-1 { ... }: This styles an element with the class "shoe-1", possibly representing another shoe image. It sets its position, dimensions, border radius, and applies a white box shadow.

.shoe-1:hover { ... }: This styles the "shoe-1" element when hovered. It changes its position, dimensions, and adds more width and height when hovered over.

In simple terms, this CSS code helps control the appearance of various elements on a webpage, such as backgrounds, colors, sizes, and positions. It's used to create a visually appealing layout for the webpage, especially for showcasing products like shoes.



