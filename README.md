Hugo In Action
===============

This code corresponds to section **8.5** of Hugo in Action.

You can see this live at https://ch08-3.hugoinaction.com.

You can see the changes made in this branch at https://github.com/hugoinaction/hugoinaction/compare/ch08-2...ch08-3

Changes for hosting
--------------------

* The `.gitignore` file for this repository contains `resources` and `docs` folder.
  * Ideally the `resources` folder caches the assets preprocessed by Hugo and they belong with the code base. The folder may get large and blot the repository size which is not ideal for sample code.
* `static / robots.txt` is present to disallow bots from tracking the branch. Needless links to subdomains with repeated code harm the search engine rankings of the website.

