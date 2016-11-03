#MOJJO ANGULAR TEST#

This is a basic angular test in which you will have to create a directive to organize and display datas rendered by an API.

You can run this single page app simply using ```python -m SimpleHTTPServer``` at the root of this repository.

At the moment, this basic app is consuming serves data from the JSON file but it is only displaying first serve datas, we would like to be able to see it for each sets and also be able to choose between the first and second serves.


Write the directive ```serveGauge``` and then use it to display serve datas for both users, you need to respect those conditions:
* We want to be able to select the serve (first serve or second serve), using a button
* We want a graphic gauge that display the % of successful serves
* We want to display the name of the current player, and name of the current serve (first or second) on the left part

Here is a template of the ```serveGauge``` directive we would like to use on our page:

![directive]
(directive.png)


You already have bootstrap included, feel free to make this directive responsive.

