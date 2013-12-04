jekyll-round-filter
===================

Round a float to a given precision in decimal digits.

This is a [Liquid](http://liquidmarkup.org/) filter intended to be used with [Jekyll](http://github.com/mojombo/jekyll) static site generator.



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
