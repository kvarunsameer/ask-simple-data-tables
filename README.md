# Simple Datatables

* Simple Datatables provides the following features:
* Simple json can convert to Data Table with search option.

## License

MIT License

## Dependencies
```js
"dependencies": {
"polymer": "^2.0.2"
} 

```

## Installation

The element can be installed using bower

```js 

bower install --save simple-datatables

```

### Importing component into page/component: 
```html
   
   <link rel="import" href="./bower_components/simple-datatables/simple-datatables.html" />

```
### Usage

```html

<simple-datatables></simple-datatables>

```

### Attributes

```html
Adding 'hasheading' as attribute to component will enbale heading.
ex. <simple-datatables hasheading="My Title"></simple-datatables>

Adding 'enablesearch' will enable universal search functionality.
ex. <simple-datatables enablesearch></simple-datatables>

```


### sample data
Adding data inside 'tabledata' attribute

```html
<simple-datatables tabledata="{{mydata}}"></simple-datatables>

```

```js

    static get properties () {
      return {
          mydata: {
              type: Array,
              value: [
                    {"Id": "CITI0546701","Date": "2017-08-12 20:28","Place": "Morriz resturant","Bank Name": "CITI BANK","Amount": "789.34","Status": "Debited"},
                    {"Id": "HDFC059701","Date": "2017-08-05 10:28","Place": "Golden Tulip","Bank Name": "HDFC BANK","Amount": "127","Status": "Debited"}, {"Id": "CITI0546788","Date": "2017-08-01 15:18","Place": "Sub Way","Bank Name": "CITI BANK","Amount": "251","Status": "Debited"},
                    {"Id": "ICICI001","Date": "2017-07-11 12:28","Place": "KFC","Bank Name": "ICICI","Amount": "286","Status": "Debited"},
                    {"Id": "CITI0546788","Date": "2017-06-08 10:15","Place": "Village Aaahar","Bank Name": "CITI BANK","Amount": "744.34","Status": "Pending"},
                    {"Id": "CITI0546789","Date": "2017-06-11 14:28","Place": "Village Aaahar","Bank Name": "CITI BANK","Amount": "744.34","Status": "Credited"},
                    {"Id": "HDFC00056","Date": "2017-08-01 12:28","Place": "Red fox resturant","Bank Name": "HDFC BANK","Amount": "1009","Status": "Debited"}
                ],
          }
      }
    }

```