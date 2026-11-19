# A Summary about Plain Text

__PUBLIC__


## ASCII

Media Type: `text/plain; charset=us-ascii`

Canonical:

* Line-Break: CRLF
* Page-Break: FF

Line Length Limit:

* Hard Limit: 998
* Soft Limit: 78

Each line of characters MUST be no more than 998 characters, and SHOULD be no more than 78 characters, excluding the CRLF.

## Unicode

Media Type: `text/plain; charset=utf-8`

Unicode Separators:

* Line      Separator : U+2028
* Paragraph Separator : U+2029
* Next Line           : U+0085

## Other End-Of-Line Characters

* MacOS 9.x and earlier  : CR
* MacOS X                : LF
* Unix                   : LF
* Windows                : CRLF
* EBCDIC-based OS        : NEL

## References

* RFC 5322: Internet Message Format <https://www.rfc-editor.org/info/rfc5322>
* RFC 2046: Multipurpose Internet Mail Extensions (MIME) Part Two: Media Types <https://www.rfc-editor.org/info/rfc2046>
* ASCII-CODE.COM <https://www.ascii-code.com>
* Unicode Standard Annex #44 - General Category Values <https://www.unicode.org/reports/tr44/#General_Category_Values>
* Unicode 18.0.0 - 5.8 Newline Guidelines <https://www.unicode.org/versions/Unicode18.0.0/core-spec/chapter-5/#G10213>




------------------------------------------------------------------------------

- Kyle Chinn / 秦凯
- Founder of Leismore
- [leismore.co](https://www.leismore.co)
- 19 November 2026

