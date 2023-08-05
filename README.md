# Quarto extension for Cambridge University Press journals

> This is still underdeveloped WIP that I created without knowing
https://github.com/christopherkenny/cambridge-medium, which you should use
instead of this one.

## Creating a New Article

To create a new article using this format:


```bash
quarto use template mbojan/quarto-journal-cup
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:


```bash
quarto add mbojan/quarto-journal-cup
```

Then, add the format to your document options:

```yaml
format:
  cup-pdf: default
```    

