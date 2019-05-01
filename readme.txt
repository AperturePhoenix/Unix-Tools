Clicking on the first link in the main text of a Wikipedia article, and then repeating the process for subsequent articles, will usually lead to the Philosophy article. After doing some research I found that many articles such as Mathematics has been updated and only clicking the first link on each page will get stuck in a loop. I have adapted this program so that if it finds itself in a loop, it will continue to click on the next link in the article until it breaks out of the loop. It is also important to note that this program does not handle disambiguation pages as they aren't webpages about a specifc topic.

This program accepts a word which will automatically get the wikipedia page on that topic.
Ex: sh wikipedia Existence will fetch the page https://en.wikipedia.org/wiki/Existence
Note: Remember to escape () with \( and \)

Some drawbacks to creating this program in unix is that it is difficult to create a regular expression that will remove all the unecessary information and return only the first link on a page. Especially since the way that HTML is written is not standarized even for a site such as wikipedia. There will always be HTML code that follows a different order, tags, etc. It is very difficult to create all-encompasing code for HTML.


