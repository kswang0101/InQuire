## Super Search

Super search can assist users to query information from Subscription,
Issue Tracking, CODE and WIKI services via key word.

![super-search](/assets/image12.png)

## SVN logs

The result of SVN logs are based on `Google Enterprise Search`, a user can use some tips that produce more efficient search results.

### Basic Search Concepts

#### Spelling

For U.S. English searches, a single spelling suggestion is returned with the results for queries where the spell checker has detected a possible spelling mistake. The spell checker feature is context sensitive. 

#### Capitalization

Google searches are not case sensitive. All letters, regardless of how you enter them, are handled as lower case. For example, searches for "george washington," "George Washington," and "George washington" return the same results.

#### Common Words

Google ignores common words and characters, such as "where" and "how," as well as certain single digits and single letters, because they tend to slow down your search without improving the results. Google indicates that a common word has been excluded by displaying details on the results page.

If a common word is essential to getting the results you want, you can include it by putting a plus ("`+`") sign in front of it. Include a space before the "`+`" sign, but not after it. For example, to search for documents about Star Wars I, type the following:

> Star Wars +I

Alternatively, you can enclose a series of words with quotation marks and do a [phrase search](#phrase-searches).


#### Date Sort

By default, search results are sorted by relevance, with the most relevant result appearing at the top of the page. If you want to sort the documents by date instead, click the Sort by Date link. The most recent document appears at the top of the page and the date of each file is returned in the results. Results that do not contain dates are displayed at the end and are sorted by relevance.

#### Numbers

When you search for numbers, do not use exponential numbers, such as "1e10," or negative integers, such as "-12."

Numbers that are separated by commas are treated as separate figures, not fractional numbers; that is, the comma is treated as a term separator, not a decimal separator. For example, if you type "3,75", the search query is treated as a search for two separate terms, "3" and "75", not the decimal fraction, "three and three quarters." Commas that separate every three digits are ignored and are not necessary. For example, both "10,000" and "10000" are treated alike.


### Expanding Your Search

You can expand your search by using the `OR` operator. To retrieve pages that include either word A or word B, use an uppercase `OR` between terms. For example, to search for an office in either London or Paris, type the following:

>  office london OR paris

### Refining Your Search

#### Word Exclusion

If your search term has more than one meaning, you can focus your search by adding a minus sign ("`-`") in front of words related to the meaning you want to avoid. Make sure you include a space before the minus sign. You can daisy chain a list of words you want to exclude.

For example, to search for the planet Saturn and exclude search results about the car company or Roman god, type the following query:

> Saturn -car -god

Google will return pages about Saturn that do not contain the word "car" or "god." 

#### Phrase Searches

Phrase searches are useful when you are searching for famous sayings or specific names. You can search for an exact phrase or name in the following ways:

* By enclosing the phrase in quotation marks. Google will return only documents that includes the exact phrase you entered.
* By using phrase connectors—such as hyphens, slashes, periods, equal signs, and apostrophes—in between every word of your search query.

Phrase connectors and quotation marks join your search words as a single unit. For example, if you type the following query, Google treats it as a phrase search even though the search words are not enclosed in quotation marks.

> father-in-law


#### Range Searches

You can confine your search query within a certain range. You can set ranges for dates, weights, prices, meta tags, and so on. The following subsections describe ways you can refine your searches with ranges.

##### Number Ranges

To search for documents or items that contain numbers within a range, type your search term and the range of numbers separated by two periods ("`..`"). You can set ranges for weights ("250..500 g carbon fork"), dimensions ("90..100 mm stem"), years ("tour de france 2000..2006"), prices in dollar currencies only ("bike lights $10..$30"), and so on. Be sure to specify a unit of measurement or some other indicator of what the number range represents.

For example, to search for pencils that costs between $1.50 and $2.50, type the following: 

> pencils $1.50..$2.50

Each number in the range should not include more than six significant digits. For example, if you were to type the search query, "1..1234567 ton truck," only the first six significant digits in the "1234567" would be included in the range search; that is, it is as though you have just typed, "1..1234560 ton truck." 

##### Date Ranges

You can search for documents that contain dates that fall within a time frame. To use date range search, type all of the following:

* The search term
* The daterange: operator
* The start date
* The range separator (which is two periods if you are using a YYYY-MM-DD format or a hyphen if you are using a Julian format)
* The end date

Do not add a space between the search operator and the date range. The dates could be in either of the following formats:

* The YYYY-MM-DD (ISO 8601) format. Date ranges using this format should be separated by two periods ("..").
* The Julian format. The Julian date is calculated by the number of days since January 1, 4713 BC. For example, the Julian date for August 1, 2001 is 2452122. Date ranges in this format should be separated by a hyphen ("-").

For example, to search for a document about Harry Potter that was modified within a specific two-year period, type the following:

> Harry Potter daterange:2004-01-13..2006-01-13

The earliest date that you can use in your date range search is January 1, 1990; and the latest date, November 9, 2034.
