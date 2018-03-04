# newman-html-report-template-verbose
a newman html report template which contains request and response details (body plus http headers) in the report.
(similar what you could get with the newman v2 -O out option)

The template is a modification from the original reporter file from https://github.com/postmanlabs/newman/blob/develop/lib/reporters/html/template-default.hbs
## How to use
* install newman
* call newman as follows:
```
newman run -e env-INTEG.json --reporters cli,html --reporter-html-template templates/htmlreqres.hbs --reporter-html-export nice_report.html mycollection.postman.json
```
