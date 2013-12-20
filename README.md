
# Slimrr: An easy static site framework

Got tired of building a whole application just for making static sites non-redundant?  There's an app for that, It's fairly simple to use and takes away the fiddly bits.

Moving on, let's get into it all.

How to use
-------------------------
<br>
Basic HTML files like `name.html` will be rendered as [Mustache](http://mustache.github.io/) templates when `example.com/name` is requested. Files ending in `name.php` will be `included`. It's expected that those PHP pages will return their content as a string.

Error files will also be looked for in the pages directory; to add a custom 404 page, for example, make `pages/404.html`.

If you put a config.php alongside the index.php, the parameters in the config will be passed along to the template. Note that you should *not* use this for data operations. Instead, make a PHP page than renders a template passing in the data. 

This is *not* made to be an MVC replacement, just a simple system for easily making static websites sane.

The application is based on the [Slim](http://www.slimframework.com/) framework.

Download links!
-------------------------------
Versions will be listed here when they are released/archived.



Thanking people for stuff
------------------------

This is a list of people who helped somehow with the project:

<table>
  <tr>
    <th>Name</th><th>Contribution</th><th>Twitter Handle</th>
  </tr>
  <tr>
    <td>Connor</td><td>Built it all.<td><a href="http://twitter.com/ConnorPeet"><div style="height:100%;width:100%">@ConnorPeet</div></a></td>
  </tr>
  <tr>
    <td>Andrew</td><td>Contributor</td><td><a href="http://twitter.com/CypherServers"><div style="height:100%;width:100%">@CypherServers</div></a></td>
  </tr>
    <tr>
    <td>Jonathan</td><td>Fixed the bloody README ;)</td><td><a href="http://twitter.com/JFKingsley"><div style="height:100%;width:100%">@JFKingsley</div></a></td>
  </tr>
</table>

Licensing
------------
This project is licensed under the MIT license so use it how you want, just don't sue me, and we can all be happy. 
