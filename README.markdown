# @ianpatrickhines’s Tweets

To see the tweets, clone the repository (or [download the .zip version](https://github.com/ianpatrickhines/tweets/archive/master.zip)) and open [index.html](https://github.com/ianpatrickhines/tweets/blob/master/index.html).

---

In the [data](https://github.com/ianpatrickhines/tweets/tree/master/data) folder, my Twitter archive is present in two formats: JSON and CSV exports by month and year.

* CSV is a generic format that can be imported into many data tools, spreadsheet applications, or consumed simply using a programming language.
* The JSON export contains a full representation of your Tweets as returned by [v1.1 of the Twitter API](https://dev.twitter.com/docs/api/1.1). 
* The JSON export is also used to power the archive browser interface ([index.html](https://github.com/ianpatrickhines/tweets/blob/master/index.html)).
* To consume the export in a generic JSON parser in any language, strip the first and last lines of each file.