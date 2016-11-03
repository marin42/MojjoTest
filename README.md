#MOJJO ANGULAR TEST#

This is a basic angular test in which you will have to create a directive to organize and display datas rendered by the an API.

You can run this single page app simply using ```python -m SimpleHTTPServer``` at the root of this repository.

As you will see, this basic app is consuming serves data from the JSON file, but we now need to organize it.

What we would like is to wrap those datas in a directive, that we could reuse for both players and also select the first or second serve datas for each player.

Here is a template of the directive:

![directive]
(directive.png)

Write the directive ```serveGauge``` and then use it to display serve datas for both users.

You already have bootstrap included, feel free to make this directive responsive.

