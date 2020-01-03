Bootstrap Big Grid
==================
A set of larger grid options for Bootstrap.

Documentation and Tests
-----------------------
http://benwhitehead.github.io/bootstrap-big-grid/

Motivation
----------
Bootstrap's grid only provides a grid up to 1200px wide, this project provides more grids for common higher resolutions all the way up to 8K.

Changelog
---------
03/01/2020 Replaced Bower with Yarn

02/01/2020 Updated for Bootstrap 3.4.1

09/10/2017 Updated grid class names and sizes for a more even spread of breakpoints at higher resolutions and to ensure class compatibility with Bootstrap 4.
* `col-xlg-*`: renamed to `col-hd-*`
* `col-uhd-*`: renamed to `col-4k-*`
* `col-4k-*`: renamed to `col-5k-*`, changed breakpoint from 4096px to 5120px
* `col-8k-*`: changed breakpoint from 8192px to 7680px

28/07/2017 Updated for Bootstrap 3.3.7

Usage
-----
The easiest way to use Bootstrap Big Grid is with Yarn.
```bash
yarn add https://github.com/thedutchess/bootstrap-big-grid#bootstrap-3
```

Alternatively download a [release](https://github.com/thedutchess/bootstrap-big-grid/releases) and use the CSS files in the dist directory.

Then link it into your page after the main Bootstrap CSS:

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css" integrity="sha384-HSMxcRTRxnN+Bdg0JdbxYKrThecOKuH5zCYotlSAcp1+c8xmyTe9GYg1l9a69psu" crossorigin="anonymous">
<link rel="stylesheet" href="bower_components/bootstrap-big-grid/dist/css/bootstrap-big-grid.min.css"/>
```

New Classes
-----------
### New Grid Classes
| Class        | Resolution  |
| :------------|:------------|
| `col-hd-*`   | 1366 × 768  |
| `col-fhd-*`  | 1920 × 1080 |
| `col-rt-*`   | 2560 × 1600 |
| `col-rt15-*` | 2880 × 1800 |
| `col-4k-*`   | 3840 × 2160 |
| `col-5k-*`   | 5120 × 2880 |
| `col-8k-*`   | 7680 × 4320 |

### New Responsive Utilities Classes
`.visible-hd`  
`.visible-fhd`  
`.visible-rt`  
`.visible-rt15`  
`.visible-4k`  
`.visible-5k`  
`.visible-8k`  
  
`.hidden-hd`  
`.hidden-fhd`  
`.hidden-rt`  
`.hidden-rt15`  
`.hidden-4k`  
`.hidden-5k`  
`.hidden-8k`  

Project Status
--------------
Unfortunately I no longer work on UI projects and as such I don't have the time required to keep this project always up to date with the latest version of bootstrap.  If you would like to submit a PR i'd be happy to merge it as long as it doesn't break existing functionality. Or, if you'd like feel free to fork the repo and start making improvments.

Thanks for your understanding.

Copyright and License
---------------------
Copyright 2013-2014 Ben Whitehead under the Apache 2.0 license.
