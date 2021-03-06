# html-to-pdf-tests
Testing ground for wkhtmltopdf, PrinceXML, and DocRaptor

|   | WkHtmlToPdf  |  PrinceXML | DocRaptor  |
|---|---|---|---|
| **Price**  | Free  | US$ 3800 / server license  | US$ 1000 / month for 40’000 production pdfs  |
| **Site**  | http://wkhtmltopdf.org/  | http://www.princexml.com/  | https://docraptor.com  |
| **How**  | Uses webkit to render page and generate PDF  | Mysterious closed source  | Uses PrinceXML and a Javascript preprocessor. <br> NOTE: Documents are generated by the DocRaptor servers. You request for a PDF to be generated via POST request.  |

## WkHtmltoPdf
##### Pros
- Best 'out-of-the-box' CSS and JS rendering

##### Known Cons
- Jquery sizing can cause glitches
- Only a small team actively working on it
- Many known bugs
- Replies to questions are not guaranteed
- Highlighting text in PDF looks bad (try downloading one of the test WK pdfs to see what I mean)

## PrinceXML
##### Pros
- Includes upgrades and email support for 1 year

##### Known Cons
- Poor Javascript support. Cannot handle highcharts
- CSS for fonts is not as good as WkHtmlToPdf

## DocRaptor
##### Pros
- Best highcharts rendering
- Provide support through DocRaptor site (chat bubble interface like what we have on the ninjacat site)

##### Known Cons
- Better JS support than Prince, but not great (will fail to build PDF if *anything* is written to the console)
- CSS for fonts is not as good as WkHtmlToPdf
