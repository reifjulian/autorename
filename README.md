# AUTORENAME: rename variables using a row of data

- Current version: `1.0.1 8jul2009`
- Jump to: [`updates`](#recent-updates) [`install`](#install) [`description`](#description) [`author`](#author)

-----------

## Updates:

* **July 8, 2009**
  - Added `nodestring` options

## Install:

Type `which autorename` at the Stata prompt to determine which version you have installed. To install the most recent version of `autorename`, copy/paste the following line of code:

```
net install autorename, from("https://raw.githubusercontent.com/reifjulian/autorename/master") replace
```

To install the version that was uploaded to SSC, copy/paste the following line of code:
```
ssc install autorename, replace
```

These two versions are typically synced, but occasionally the SSC version may be slightly out of date.

## Description: 

`autorename` is a [Stata](http://www.stata.com) command that renames variables using a row of data. This can be useful when reading oddly formatted datasets.

For more details, see the Stata help file included in this package.

## Author:

[Julian Reif](http://www.julianreif.com)
<br>University of Illinois
<br>jreif@illinois.edu
