# Install jsdoc globally
$ npm install -g jsdoc

# Generate documentation

$ jsdoc yourJavaScriptFile.js

# Output

goes to `./out` but can be specified using `--destination`

# Configuration file
created a folder and file with preferences. To use it:
$ jsdoc -c ./conf/conf.json

# Run jsdoc

$ jsdoc -c /path/to/conf.json path/to/script.js

# Comments

- in js files, in order to be grabbed they have to follow this format:

```
/**
*
*/
somecode();
```

- allowed in JSDoc *.json files.

# Allow comments in .json files with VS Code

- click on the "json" button on the right side of the bottom blue bar
- select Configure Files Association for '.json'
- type in 'jsonc'
- selection "JSON  with Comments"

# To add readme.md to index.html

Use the -R/--readme option

```jsdoc --readme path/to/readme/README path/to/js```

