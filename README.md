# what-I-learned-in-week-10

### object
1. creaste an object: const obj = {}; 
2. property and value pair
    - obj.property === obj[property]
3. function return object.
    function(){ \
        \\\operation here \
        return{
            property1: value1,\
            property2: value2,\
        }\
}

## JSON(JavaScript Object Notation) 
### method
JSON.parse(): transform JSON as a string.
JSON.stringify(): transform string to JSON file.
## Node modules and methods
### readline module
- readline module provides an interface for reading data from a Readable stream 
1. createInterface(*input*, *output*)
2. *interface*.question(query, callback):
    - query: sting to ask the question
    - callback: function to handle the answer(just the function name, **do not** call the function).
3. *interface*.close: *Event* close the interface. 
### fs module(*File System*)
1. fs.readSync(*file direction*,*encoding option*)
    - Synchronously read data from the *file direction*.
    - Choose *encoding option* like  'utf8'.
2. fs.writeSync(*target file ditection*,*data*)
    - Synchronously writes data to a file, replacing the file if it already exists.
    - Encoding option defaults to 'utf8'.
