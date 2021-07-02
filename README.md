# Node.js (Challenge Phase 1)

Create an Node.js app capable of reading a `JSON` file to then output specific information about the data input:
- Total price amount
- List of categories with the sum of prices for each category

_To have in mind:_
- _Create the project using a Github repository_
- _Use ES Modules in Node_

## CLI Interface:

`node app.js <path-to-file>`

## Usage Examples (Should be capable of receiving relative and absolute paths):

```node app.js products.json```

```node app.js ./products.json```

```node app.js $HOME/Desktop/products.json```

## Data Input (JSON file):

```
{
  "products": [
    {
      "name": "",
      "category": "",
      "price": ""
    },
    ...
  ]
}
```

## Output Example (Use console.log):

```
Total:
150.00

Categories:
Food 35.00
Electronics 838.36
Plants 60.50
```
