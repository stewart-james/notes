
## Purpose

When MSBuild attempts to resolve file references, as with windows, it has a directory search order priority [[Resolving File References]]. The HintPath metadata a


### Interaction with .props & .targets

This field works with `.props` and `.targets` files.


**Caveats**
* Relative paths will be relative to the location of the `.props` or `.targets` file.