# eBlocker's FAQ and knowledge base

To re-create the HTML files from the JSON source files, go to this directory and run:

    bin/zendesk2html

Please note that some HTML files have been modified manually:

*   `docs/de/index.html`
*   `docs/en-us/index.html`

To create an XML file that can be imported into WordPress, run:

    bin/zendesk2html -wp

This writes all articles to a file named `wp-import.xml`.
