# JavaScript JSON Schema to JSON Transformer
## Generate example payloads for a given JSON schema.

There are a lot of libraries out there to achieve the same requirement.
But they require us to define a lot of meta information in the schema.
Ex:- We need to define the string we need is a name, country etc..

But if you don't have any control over the JSON schema or you don't  need that additional complexity of adding meta information

## This is the right solution for you!

You can preview a working example @ https://gdlmadushanka.github.io/JSONSchemaTransformer/

## Usage instructions

1. Import the JS file
```
<script type='text/javascript' src='js/SchemaToJson.js'></script>
<script type='text/javascript' src='js/randexp.min.js'></script>
```
2. Call the "convertSchemaToJson" as in the following sample
```
function transform(){
 var input = document.getElementById("mytextarea").value;
 var output = convertSchemaToJson(JSON.parse(input));
 document.getElementById("mytextarea2").value = output;
}
```
## Contribute

Feel free to report issues and do the necessary improvements.

## Blog
https://lahirumadushankablog.wordpress.com/2019/01/27/javascript-json-schema-to-json-transformer/