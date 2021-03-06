# csvjson
A JavaScript library to parse csv files and trasform the content in JSON Format. 

The library infers the column separator and uses it to parse the CSV content.

In addition, the library embeds a set of heuristics to check whether the csv input is well-formed. This feature is particularly useful for applications that need to import well-formed csv files. 

The last version of the library checks and give a feedback for:

* Empty first row (empty header);
* Empty rows within the CSV file;
* Header (first row) without names;
* Rows with different number of columns;
* Header with duplicated column captions (warning).

In brief, csvjson is NPM based, developed with a test-driven process (see qunit tests), ES6 module ready. 

## installation via npm 

The prefered way to install csvjson is by using npm. Assuming that you are in your project dir, run the following command:

> npm install https://github.com/donpir/csvjson.git --save

In order to check whether the installation was successful, open your package.json you should see the csvjson dependency ander the key "dependencies". Moreover check the content of dir node_modules, there should be a new dir named "csvjson". Well, I'm sure that worked fine until now!

### update csvjson via npm

In order to update your local version of the libary with last version available on the git repository, run the following npm command:

> npm update csvjson

### unistall via npm

> npm unistall csvjson --save

## how to use csvjson as ES6 module








