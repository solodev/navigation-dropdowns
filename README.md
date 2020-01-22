# navigation-dropdowns
A primary/main navigation is one of the first things you tackle when developing a website. Dropdowns can be tricky; fortunately, bootstrap helps with some default classes you can tap into.

## Tutorial
For detailed instruction's, view Solodev's [How to Create Simple Navigation Dropdowns with Bootstrap](https://www.solodev.com/blog/web-design/how-to-create-simple-navigation-dropdowns-with-bootstrap.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/7vkqp92f/).

## HTML
The tutorial contains the following basic HTML markup.

```
<nav aria-label="Main Navigation" role="navigation">
      <ul class="nav d-flex align-items-center justify-content-center text-uppercase font-weight-bold">
        <li class="nav-item dropdown">
          <a href="#" aria-haspopup="true" aria-expanded="false">Products</a>
          <ul class="dropdown-menu">
            <li class="nav-item"><a href="#">VALKYRIE-1</a></li>
            <li class="nav-item"><a href="#">TALON-2</a></li>
            <li class="nav-item"><a href="#">LUNAR EXPLORER</a></li>
          </ul>
        </li>
      </ul>
</nav>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```