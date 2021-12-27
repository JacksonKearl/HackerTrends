# HackerTrends

Google Trends, but for HN comments, in less than 100 lines of HTML. Powered by Agolia's [Hacker News Search API](https://hn.algolia.com/api).

## Why?

Someone asked if the from "So you think", followed by a strawman argument, was a pattern new to HN.
I tried to deduce this using Agolia's [HN search page](https://hn.algolia.com/), but their date picker implementation made such querying painful.
Luckliy, Agolia provides a CORS-friendly API to their search engine, and I was going to be in flights all afternoon, so I spent some of that high time to answer that question.


### The answer

Inconclusive. Try for yourself:

## Examples

Editor wars (vscode, vim, emacs, sublime, atom):
![chart of editor populatiry in HN comments](examples/editors.png)

Language wars (rust, javascript, ruby):
![chart of language populatiry in HN comments](examples/languages.png)