# CSS
CSS is the language that allows you to control the visual elements of websites. HTML acts as the structure and content of your website, while CSS allows you to change visual elements beyond the basic functions of HTML. You can control exactly how HTML elements look. HTML is the document itself, CSS is how you present that document to a user. CSS is defined in modules.

## CSS Syntax
CSS is a rule based language where you define rules that indicate which styles should apply to which elements or groups of elements. 

If we wanted to make our header red, we would type:
> ``h1 {
    color: red;
    font size:5em;
}

In this piece of code, the first item is a "selector", which selects the HTML element we are going to style. In this case, it is "h1". 

Next, we have braces ``{}`` which enclose our "declarations". Declarations take the form of property/value pairs. In our example, color is the property and red is the value. CSS stylesheets will often contain many rules similar to this one. 

## Other notes
* CSS stylesheets can be written in any text editor but must be saved with a ``.CSS`` extension. 
* We link to the CSS stylesheet with a ``link element`` inside of the ``head``section of an HTML document.
* Color can be a set a few different ways. We can use a HEX value, RGB value, or RGBA value. The value appears before the color. For example ``{color: rgb(201, 76, 32);}