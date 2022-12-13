CV

## John Doe

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Middle Fullstack Developer

## Contacts

- email: js@mail.js.ru
- phone: +345678(9)67
- telegram @telegram_nick

## Skills  

- html/css
- javascript
- php, laravel
- mysql/postgresql
- vue js
- git, docker
- english B2

## Education

1. The Best University Of City, 2010-2014
2. The Best Courses of The Best, 2016
3. One More The Best University Of The Best, 2015-2019

## Code example

```js
class PaginationHelper {

	constructor(collection, itemsPerPage) {
        this.collection = collection;
        this.itemsPerPage = itemsPerPage;
	}
                        
	itemCount() {
	    return this.collection.length;
	}
                        
	pageCount() {
        return Math.ceil(this.itemCount() / this.itemsPerPage);
	}
                        
	pageItemCount(pageIndex) {
        if (pageIndex < 0 || pageIndex >= this.pageCount()) {
            return -1;
        }
                              
        if (pageIndex < this.pageCount() - 1) {
            return this.itemsPerPage;
        }
                              
        return this.itemCount() - this.itemsPerPage * (this.pageCount() - 1);
	}
                        
	pageIndex(itemIndex) {
        if (itemIndex < 0 || itemIndex >= this.itemCount()) {
            return -1;
        }
                          
        return parseInt(itemIndex / this.itemsPerPage);
	}
}
```

Last updated at 09.12.2022
