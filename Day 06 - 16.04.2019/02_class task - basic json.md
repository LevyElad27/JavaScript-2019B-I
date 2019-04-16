# Class task
* create an html page
* in the page add to the head a `script` tag
* in the `script` tag - create a new variable named `people`, that stores this json content:
```json
{"page":2,"per_page":3,"total":12,"total_pages":4,"data":[{"id":4,"first_name":"Eve","last_name":"Holt","avatar":"https://s3.amazonaws.com/uifaces/faces/twitter/marcoramires/128.jpg"},{"id":5,"first_name":"Charles","last_name":"Morris","avatar":"https://s3.amazonaws.com/uifaces/faces/twitter/stephenmoon/128.jpg"},{"id":6,"first_name":"Tracey","last_name":"Ramos","avatar":"https://s3.amazonaws.com/uifaces/faces/twitter/bigmancho/128.jpg"}]}
```
* run over `people.data` with `for-of` loop, and for each person print his name and age