# Kryeion

A mid-sized CSS library for quick application of custom UI styles. However, it depends on the classes generated by **Modernizr** and **Browsengine** JavaScript libraries to function well. Unlike [**Bulma.io**](https://www.github.com/jgthms/bulma) or [**Bootstrap**](https://www.github.com/twbs/bootstrap), it also supports both **float-based** and **flexbox-based** layouts and widgets. It also comes in a modular structure and is geared towards _progressive enhancement_ with support for browsers like _old IE_, _old Firefox_ and _Opera Mini_. It also has **utility and helper classes** for quick but apt UI effects e.g. flipping an element 90 degrees or having a fancy header.

## About

Kryeion makes it really easy to create custom widgets and simple no-tween effects by simply adding a class or set of classes to your HTML. It's really that simple. It works great with [**Modernizr**](https://github.com/Modernizr/Modernizr) classes, [**Browsengine**](https://github.com/isocroft/browsengine). It is still in active development.

## How to Use

```html
<html class="full-height">
    <head>
        <link rel="stylesheet" media="screen" href="path/to/kryeion.css">
    
        <script src="path/to/browsengine.js" type="text/javascript"></script>
        <script src="path/to/modernizr.js" type="text/javascript"></script>
    </head>
    <body>
    
        <section class="card">
            <h1 class="heading-box text-centered">
                <small class="fancyheading-pane">
                        <strong class="fancyheading-pane-placeholder">New Intakes</strong> 
                </small>
            </h1>
            <ul>
                <li>
                    <div class="persona-box">
                        <span class="persona-avatar-box">
                            <a href="/" class="persona-avatar"><img src="" alt="Avatar"></a> 
                        </span>
                        <div class="persona-info">
                            <h3>Henry Backer</h3>
                            <p>I know about what to do and what not.</p>
                        </div>
                    </div>
                </li>
                <li>
                    <div class="persona-box">
                        <span class="persona-avatar-box">
                            <a href="/" class="persona-avatar"><img src="" alt="Avatar"></a> 
                        </span>
                        <div class="persona-info">
                            <h3>Susan Flowy</h3>
                            <p>I don't know what i think i should do.</p>
                        </div>
                    </div>
                </li>
            </ul>
        </section>
    
    </body>
</html>
```

## License

MIT

## Contributing

We would love to have you contribute to this project. This project was created by **CoolCodes** <img src="./logo-coolcodes.png">
