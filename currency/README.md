# 3 Musketeers

**The 3 Musketeers is a program to convert money with the actual currency.**


- [🐣 Getting Started](#-getting_started)
- [🎯 Running the tests](#-running_the_tests)
- [🛣️ Related course](#related_course)
- [Licence]
- [About Jest](#about_jest)

### 🐣 Getting started

- Go to 3-musketeers/currency
- npm install
- node cli.js

By default, it displays the conversion of 1USD to bitcoin

if you want to change the currency and run other conversions, you can change the parameters:

- Go to index.js
- change the parameters at line 13

## 🎯 Running the tests

- Go to 3-musketeers/currency
- Install jest by running npm install --safe-dev jest
- Write npm test in terminal

It will display 'fail' for the failed tests and 'pass' for the passed tests.

Example - the following test is usefull to check if the conversion from 1USD to EUR is working. 
To do so, we compare the result to the currency given from the api.


                    describe('currency', () => {
                    test('convert 1 USD to EUR', async () => { result =>{
                        try {
                        expect(result).toBe(0.899);
                        
                        } catch (error) {
                        console.log(error);
                        }
                    }
                    });

## 🛣️ Related course

* [Course 6 - 3 Musketeers: RDD, CDD and TDD](https://github.com/92bondstreet/javascript-empire#-course-6---3-musketeers-rdd-cdd-and-tdd)

## Licence

[Uncopyrighted](http://zenhabits.net/uncopyright/)

 
