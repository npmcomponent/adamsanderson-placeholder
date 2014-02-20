*This repository is a mirror of the [component](http://component.io) module [adamsanderson/placeholder](http://github.com/adamsanderson/placeholder). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/adamsanderson-placeholder`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# placeholder.css

  Simple CSS image placeholders.

## Installation
Either install placeholder.css as a component:

    $ component install adamsanderson/placeholder

Or link to it after your normal styles:

    <link rel="stylesheet" href="placeholder.css">

## Usage

Include `placeholder.css` in your project, and then markup your images like this:

    <img class='placeholder' width='50%' height='100'/>

If you include a `title`, that text will be displayed on the placeholder image.

## Browser Support

Internet Explorer 8 and 9 will display the placeholder with an image icon instead of the placeholder's dimensions.  
Doubtless there is a workaround, but I haven't found it yet.

## License

  MIT

----

Adam Sanderson - http://monkeyandcrow.com