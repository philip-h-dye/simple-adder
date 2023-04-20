# Basic Usage

## Installation

To use Grammar Tool, first install it using pip:

```console
(.venv) $ pip install grammar-tool
```

## A very simple Lark grammar 'simple-adder' :  This is the end result.
```
start : add

add : num "+" num

?num : SIGNED_NUMBER

%import common.SIGNED_NUMBER
%import common.WS
%ignore WS

```

```
$ git clone https://github.com/philip-h-dye/simple-adder.git
...
$ cd simple-adder

```
Layout
$ find
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

To retrieve a list of random ingredients,
you can use the `lumache.get_random_ingredients()` function:

```{eval-rst}
.. autofunction:: lumache.get_random_ingredients
```

The `kind` parameter should be either `"meat"`, `"fish"`,
or `"veggies"`. Otherwise, {py:func}`lumache.get_random_ingredients`
will raise an exception.

```{eval-rst}
.. autoexception:: lumache.InvalidKindError
```

For example:

```pycon
>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']
```
