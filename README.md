# try-json-schema

What's dumb here, is that the `$ref` is [relative to the base url](https://json-schema.org/understanding-json-schema/structuring.html#ref) (e.g. the `$id`). By design, you can't "import"
a schema by URI as a subschema. WTFN?