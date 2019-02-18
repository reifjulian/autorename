# SORTOBS: sort observations into a specified order

- Current version: `1.1 16sep2010`
- Jump to: [`updates`](#recent-updates) [`install`](#install) [`description`](#description) [`author`](#author)

-----------

## Updates:

* **September 16, 2010**
  - Added `before()` and `after()` options

## Install:

Type `which sortobs` at the Stata prompt to determine which version you have installed. To install the most recent version of `sortobs`, copy/paste the following line of code:

```
net install sortobs, from("https://raw.githubusercontent.com/reifjulian/svret/master") replace
```

To install the version that was uploaded to SSC, copy/paste the following line of code:
```
ssc install sortobs, replace
```

These two versions are typically synced, but occasionally the SSC version may be slightly out of date.

## Description: 

`sortobs` is a [Stata](http://www.stata.com) command that sorts observations into an order specified by the user.

For more details, see the Stata help file included in this package.

## Author:

[Julian Reif](http://www.julianreif.com)
<br>University of Illinois
<br>jreif@illinois.edu
