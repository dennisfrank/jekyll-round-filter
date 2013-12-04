jekyll-round-filter
===================

This [Liquid](http://liquidmarkup.org/) filter lets you round floats in [Jekyll](http://jekyllrb.com/) templates to a given precision in decimal digits.


## Installation

Copy `jekyll-round-filter.rb` file into `_plugins` directory.

## Usage

```
{{ float | round: precision }}
```

## Examples:

```
{{ 512.4562 | round }}      => 512
```

```
{{ 512.4562 | round: 2 }}   => 512.46
```

## Reference:

http://ruby-doc.org/core-1.9.3/Float.html#method-i-round
