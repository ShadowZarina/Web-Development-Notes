# CSS BOOTSTRAP

## WHAT IS BOOTSTRAP?
- Bootstrap is a free, open-source front-end CSS framework used by developers to build responsive, mobile-first websites quickly. Originally developed at Twitter in 2011, it serves as a giant package of pre-written CSS and JavaScript code.
- Instead of writing style rules from scratch, you apply predefined Bootstrap classes directly to your HTML elements.
- Bootstrap is the most popular CSS Framework for developing responsive and mobile-first websites.
- Bootstrap 5 is the newest version of Bootstrap.

### Core Features
- 12-Column Grid System: Simplifies responsive page layouts by dividing screens into columns that automatically resize.
- Pre-styled Components: Includes ready-to-use elements like Bootstrap Buttons, dropdowns, navigation bars, cards, and forms.
- Utility Classes: Offers fast shorthand helper classes for margins, padding, text alignment, and colors.
- Responsive Breakpoints: Uses CSS media queries automatically to change web designs seamlessly between mobile, tablet, and desktop viewports.
- JavaScript Plugins: Power interactive components like pop-up modals, image carousels, and dismissible alerts.

## BOOTSTRAP CLASSES

For a comprehensive list of all Bootstrap classes, refer to [this link!](https://www.w3schools.com/bootstrap/bootstrap_ref_all_classes.asp)<br>

## EXAMPLE SYNTAX

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content>
    <meta name="author" content>
    <link rel="icon" href="/docs/4.0/assets/img/favicons/favicon.ico">
    <title>Album example for Bootstrap</title>
    <link rel="canonical" href="https://getbootstrap.com/docs/4.0/examples/album/">
    
    <link href="../../dist/css/bootstrap.min.css" rel="stylesheet">
    
    <link href="album.css" rel="stylesheet">
</head>
<body>
    <header>
        <div class="bg-dark collapse" id="navbarHeader" style>...</div>
        
        <div class="navbar navbar-dark bg-dark box-shadow">...</div>
    </header>
    
    <main role="main">
        <section class="jumbotron text-center">
            <div class="container">
                <h1 class="jumbotron-heading">Album example</h1>
                
                <p class="lead text-muted">
                    "Something short and leading about the collection below–its contents, the creator, etc. 
                    Make it short and sweet, but not too short so folks don't simply skip over it entirely."
                </p>
                <p>
                    <a href="#" class="btn btn-primary my-2">Main call to action</a>
                    
                    <a href="#" class="btn btn-secondary my-2">Secondary action</a>
                </p>
            </div>
        </section>
        
        <div class="album py-5 bg-light">
            <div class="container">
                <div class="row">...</div>
            </div>
        </div>
    </main>
    
    <footer class="text-muted">
        <div class="container">
            <p class="float-right">
                <a href="#">Back to top</a>
            </p>
            <p>
                "Album example is © Bootstrap, but please download and customize it for yourself!"
            </p>
            <p>
                "New to Bootstrap? "
                <a href="../../">Visit the homepage</a>
                " or read our "
                <a href="../../getting-started/">getting started guide</a>
                "."
            </p>
        </div>
    </footer>
    
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script>
        window.jQuery || document.write('<script src="../../assets/js/vendor/jquery-slim.min.js"><\/script>')
    </script>
    
    <script src="../../assets/js/vendor/popper.min.js"></script>
    
    <script src="../../dist/js/bootstrap.min.js"></script>
    
    <script src="../../assets/js/vendor/holder.min.js"></script>
    
    <div id="screenity-ui">...</div>
    <svg xmlns="http://www.w3.org/2000/svg" width="404" height="225" viewBox="0 0 405 225" preserveAspectRatio="none" style="display: none; visibility: hidden; position: absolute; top: -100%; left: -100%;">...</svg>
</body>
</html>
```

## REFERENCES

[Introduction to Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/)<br>
[What is Bootstrap?](https://www.w3schools.com/whatis/whatis_bootstrap.asp)
[All Bootstrap Classes](https://www.w3schools.com/bootstrap/bootstrap_ref_all_classes.asp)<br>
[Examples of Bootstrap Components](https://getbootstrap.com/docs/4.0/examples/)
