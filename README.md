# Newman HTML Report Template

a newman html report template which contains request and response details (body plus http headers) in the report.
(similar what you could get with the newman v2 -O out option)

The template is a modification from the [original reporter file](https://github.com/postmanlabs/newman-reporter-html/blob/develop/lib/template-default.hbs)

## Demo: 

[Awesome Newman Html Template](https://marcosellys.github.io/awesome-newman-html-template/)

## Collection of tests

[Postman Echo](https://www.getpostman.com/collections/631643-f695cab7-6878-eb55-7943-ad88e1ccfd65-JsLv?referrer=https%3A%2F%2Fdocs.postman-echo.com%2F#)

## Advantages:

- Built with the world's most popular front-end component library.
- Powerful Report section.
- Amazing Requests section.
- Powerful Fuzzy search library.
- With a modern library to copy text to clipboard.

## Prints

### Report Tab

<p align="center">
  <img alt="Initial Screen" src="https://raw.githubusercontent.com/MarcosEllys/awesome-newman-html-template/master/prints/one.png">
</p>

### Request Tab

<p align="center">
  <img alt="Request opened" src="https://raw.githubusercontent.com/MarcosEllys/awesome-newman-html-template/master/prints/two.png">
</p>

### Failures Tab

<p align="center">
  <img alt="Requ2est opened" src="https://raw.githubusercontent.com/MarcosEllys/awesome-newman-html-template/master/prints/three.png">
</p>

## Libraries present
- [Bootstrap](http://getbootstrap.com/)
- [Clipboard JS](https://clipboardjs.com/)
- [Fuse JS](http://fusejs.io/)

## How to use
* [Install Newman](https://github.com/postmanlabs/newman-reporter-html)
* [Install Report HTML](https://github.com/postmanlabs/newman-reporter-html)
* Call newman as follows:
```
newman run -e my.environment.json -g my.globals.json --reporters cli,html --reporter-html-template templates/htmlreqres.hbs --reporter-html-export my_report.html my.collection.postman.json
```
## Contributing

Please review the [Contribution to Awesome guide](https://github.com/MarcosEllys/awesome-newman-html-template/blob/master/CONTRIBUTING.md) for information on how to get started contributing to the project.
