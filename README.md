Lipsum.js
============
Lipsum is a simple "Lorem Ipsum" plugin for JQuery. It fills any provided DOM element with the standard "Lorem Ipsum" text provided by [http://www.lipsum.com/] . 

Usage
--------
Usage is very simple and follows the syntax
    .lipsum( properties );
where `properties` is a map of options used to determine how the text is displayed. There are three options you can use: `type`, `number`, and `spaces`; `type` lets you specify whether you are viewing pargraphs or words, `number` dictates the number of pargraphs or words, and `spaces`, which is only applicable on `type: 'words'`, displays text with no whitespace. The default setting for this plugin is to display the entire "Lorem Ipsum" text in 5 paragraphs.

Examples
---------
A demo is provided in `index.html`, but here are some examples of usage anyway.

- `$(this).lipsum();` displays 5 paragraphs of "Lorem Ipsum".
- `$(this).lipsum({ type: 'paragraphs', number: '13' });` displays 13 paragraphs of "Lorem Ipsum".
- `$(this).lipsum({ type: 'words', number: '500' });` displays 500 words of "Lorem Ipsum" in non-pargraph format.
- `$(this).lipsum({ type: 'words', number: '500', spaces: 'false' });` displays 500 words of "Lorem Ipsum" in non-pargraph format, without spaces between words.

Notes
------