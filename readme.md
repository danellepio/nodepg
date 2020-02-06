# nodepg
Pio, Danelle Veronica T. || BSIT - 2B || February 06, 2020

## This is my activity for the database 2. I have encountered
different errors and these are the following:

Problem #1 
$ node index.js (node:9112) DeprecationWarning: Implicit disabling of certificate verification is deprecated and will be removed in pg 8. Specify rejectUnauthorized: true to require a valid CA or rejectUnauthorized: false to explicitly opt out of MITM protection.

Problem #2:
npm ERR! file E:\pio\db2\nodepg\package.json
npm ERR! JSON.parse Failed to parse json
npm ERR! JSON.parse Unexpected string in JSON at position 267 while parsing '{
npm ERR! JSON.parse   "name": "nodepg",
npm ERR! JSON.parse   "version": "1.0.'

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\DanelleVeronicaPio\AppData\Roaming\npm-cache\_logs\2020-02-06T08_48_55_317Z-debug.log

## In case of error
Solutions:

Problem#1:
change the sll: true,
    to
    ssl: {
        rejectUnauthorized: false,
    }
    
Problem#2:
I encoded "pio-prob1": "node pio-prob1.js" script, inside the package.json file. With that, i was able to run the code.
