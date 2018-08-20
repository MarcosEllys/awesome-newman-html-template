# newman-html-report-template-verbose
a newman html report template which contains request and response details (body plus http headers) in the report.
(similar what you could get with the newman v2 -O out option)

The template is a modification from the original reporter file from https://github.com/postmanlabs/newman/blob/develop/lib/reporters/html/template-default.hbs

## Demo: 

http://awesome-newman-html-template.surge.sh/

## Advantages:

- Built with the world's most popular front-end component library.
- Powerful Report section.
- Amazing Requests section.
- Powerful Fuzzy search library.
- With a modern library to copy text to clipboard.

## Prints
* Report Tab
<p align="center">
  <img alt="Initial Screen" src="https://raw.githubusercontent.com/MarcosEllys/awesome-newman-html-template/master/prints/one.png">
</p>
* Request Tab
<p align="center">
  <img alt="Request opened" src="https://raw.githubusercontent.com/MarcosEllys/awesome-newman-html-template/master/prints/two.png">
</p>

* Request opened
<p align="center">
  <img alt="Requ2est opened" src="https://raw.githubusercontent.com/MarcosEllys/awesome-newman-html-template/master/prints/three.png">
</p>

## Libraries present
- [Bootstrap](http://getbootstrap.com/)
- [Clipboard JS](https://clipboardjs.com/)
- [Fuse JS](http://fusejs.io/)

## How to use
* install newman
* call newman as follows:
```
newman run -e env-INTEG.json --reporters cli,html --reporter-html-template templates/htmlreqres.hbs --reporter-html-export nice_report.html mycollection.postman.json
```
