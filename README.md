slimrr
=======

Got tired of building a whole application just for making static sites non-redundant?  There's an app for that. Files like `name.html` will be rendered as [Mustache](http://mustache.github.io/) templates when `example.com/name` is requested, files ending in `name.php` will be `includ`ed. It's expected that those PHP pages will return their content as a string.

Error files will also be looked for in the pages directory; to add a custom 404 page, for example, make `pages/404.html`.

If you put a config.php alongside the index.php, the parameters in the config will be passed along to the template. Note that you should *not* use this for data operations. Instead, make a PHP page than renders a template passing in the data. 

This is *not* made to be an MVC replacement, just a simple system for easily making static websites sane.

The application is based on the [Slim](http://www.slimframework.com/) framework.

Licensed under the MIT license. Use it how you want, just don't sue me, and we can all be happy, k?
