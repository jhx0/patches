# patches
A various collection of patches I wrote for fun. In general, they are supposed to be enhancements.

## Usage
1. Clone/download this repository
2. Unpack/cd into the directory
3. Apply the given patches to the projects they are for
```Bash
$ patch -p1 < example.patch
```

## About
**gnu-coreutils/fold-cut-line-feature.patch:** Adds '-c' as an option which cuts off a line at WIDTH (Example: -w80) instead of breaking up the line.

## Hacking
If you like to improve the given patches make sure you have run/tested them against the projects there are for.

## Note
Don't supply these patches to the projects they are made for! (I in fact did so before)   
They are only used for myself (or you) locally in the end.
