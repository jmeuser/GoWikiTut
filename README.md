# GoWikiTut
A wiki in Go from https://golang.org/doc/articles/wiki/

$ go run wiki.go

In your favorite browser navigate to: http://localhost:8080/view/test

To do:
* Store templates in tmpl/ and page data in data/.
* Add a handler to make the web root redirect to /view/FrontPage.
* Spruce up the page templates by making them valid HTML and adding some CSS rules.
* Implement inter-page linking by converting instances of [PageName] to
* <a href="/view/PageName">PageName</a>. (hint: you could use regexp.ReplaceAllFunc to do this)
