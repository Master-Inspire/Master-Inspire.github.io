## Animus Blog

* * *

#### What?

A simple yet beautiful and powerful static Blog website.

* * *

#### Where?

> ***[Animus](https://en.wikipedia.org/wiki/Animus)***: A device in the `Assassin's Creed` series able to re-live the genetic memories of its user's ancestors.


* * *

#### How?

All articles are located in the **Articles** folder.

The file which named **list.txt** contains all articles - It's absolute url path line by line.

If the url contains a `search` part, and has a key named `which` with a zero-based numeric value `n`, then the url in the nth-line of the **list.txt** will be requested and show.

The `articleIndex` is used as initial content if `which` is not specified.

If the `Show Me the Code` button is clicked, then a random article will be show.

Local Storage keys:

* `allArticles`: the content of **list.txt**.
* `contentCache + index`: the content of each article, the index is used to distinguish between them.
* `articleIndex`: the current index.
* `articleName`: the current article absolute url.
* `cacheExpiration`: after 3 days from this day, all Local Storage will be cleared.

Shortcuts:

* Press `Left Arrow` or `Right Arrow` key to show the previous or next article.
* Press `Enter` key to show a random article.
* Press `Esc` key to close the modal.
* Press `Up Arrow` or `Down Arrow` key to scroll one line up or down.
* Press `Home` or `End` key, you know it.
* Press `Page Up` or `Page Down` key, you know it.

Touch events:

* `Swipe Left`: same as `Left Arrow` key.
* `Swipe Right`: same as `Right Arrow` key.
* `Double Tap`: same as `Enter` key.

* * *

#### Who?

Some contents are collected from somewhere.

**If you are using an ~~out dated browser~~, then you are NOT welcome to this place.**

You (the general public) can do whatever you want with the repo except claim it as your own work :).

Copyright 2015. Developed by ***[Master Inspire](https://github.com/Master-Inspire/)***.
