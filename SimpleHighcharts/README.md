##### Link to HTML
http://htmlpreview.github.io/?https://github.com/asemahle/html-to-pdf-tests/blob/master/SimpleHighcharts/highcharts.html

##### WkHtmlToPdf
- Chart not sized correctly. This is a known bug. The solution is to hardcode the pixel height and width.

##### PrinceXML
- Rendered only one chart, which was rendered too large
- In general, I do not think we can count on PRINCE to render highcharts: http://www.princexml.com/forum/topic/3003/prince-10-released
- WORKAROUND: do what we currently do. Ie. render highcharts ourselves and insert into doc


##### DocRaptor
- Works.
