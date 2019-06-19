# Getting-to-Philosophy-Problem
Python script to check the "Getting to Philosophy" law.

Description:

Clicking on the first link in the main body of a Wikipedia article and repeating the process for subsequent articles would usually lead to the article Philosophy.

The program should receive a Wikipedia link as an input (Usually use https://en.wikipedia.org/wiki/Special:Random), go to another normal link and repeat this process until either Philosophy page is reached, or we are in an article without any outgoing Wikilinks, or stuck in a loop.

A "normal link" is a link from the main page article, not in a box, is blue (red is for non-existing articles), not in parentheses, not italic and not a footnote. print all visited links to the standard output.

For more information about it visit: https://en.wikipedia.org/wiki/Wikipedia:Getting_to_Philosophy
