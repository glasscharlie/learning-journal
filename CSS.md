# CSS Notes

## Understanding CSS
- Key to understanding CSS is to imagine there is an invisible box around every HTML element

- CSS Allows you to create rules that control the way each individual box works (and the content within that box)

### How it works
- CSS works by associating rules with HTML elements. These rules govern how conent of specified elements should be displayed. 

- A CSS rule contains two parts
> Seletors: indicate which elements the rule applies to

> Declarations: indicate how the elements reffered to in the selector should be styled

- CSS properties affect how elements are displayed. CSS delarations sit in curly brackets and is made up of two parts
> properties: indicate the aspects of the element you want to change

> Values: specify the settings you want to use for the chosen properties



### External CSS
- <link> - shows an HTML document where to find the CSS file

- href - specifies the path to the CSS file

- type - Specifies the type of document being linked to

- rel - specifies the relationship between the HTML page and the file it is linked to

### Internal CSS
- <stle> can use CSS rules within an HTML page by placing it within style element (usually inside the head element)

- Shouldn't be used if website has more than one page

- CSS selectors allow you to target rules to specify documents inside an HTML document

### Types of CSS Selectos
- Universal - applies to all elements in document

- Type - matches element names

- Class - Matches element whose class atribute matches one that is specided after the period symbol

- ID - matches element whose id attribute has value that matches the one after the pound symbol

- Child - matches element that is a direct child of another

- descendent - matches element that is descendent of another specified element

- adjacent sibling - matching element that is the next sibling of another

- General sibling - matches element that is a sibling of another, although it does not have to be directly preceding

## Color
- Important to make sure he contrast is enough for the text to be readable

### Forground color
- RBG values - express color in terms of how much red, green, blue are ued

- Hex Codes - six digit codes that represent amount od red, blue, green in color proceded bu a pound or hash # sign

- Color names - there are 147 predefined color names that are recognized by browsers

### Backround color
- CSS treats each HTML element as if it appears in a box, background color sets color of background for that box

- Can specify color in same three ways as foureground color (RBG, HEX codes, Color names)

- By default most browser windows have a white background

### CSS
- Can set opacity using a value between 0.0 and 1.0 (.5 is half opacity)

- Introduced three new ways to specify color
> Hue- the colloquial idea of a color

> Saturation - Amount of grey in a color, represented by a percentage

> Lightness - Amount of white or black in a color. 0% is white, 100% is black


### Selectors

- .class	.intro	Selects all elements with class="intro"
- #id	#firstname	Selects the element with id="firstname"
- *	*	Selects all elements
- element	p	Selects all <p> elements
- element,element,..	div, p	Selects all <div> elements and all <p> elements
