# @dexagod/string_normalizer

Quick normalization script to make strings usable in applications such as search trees.

usage:

`
    
    var Normalizer = require('@dexagod/string_normalizer');
    
    let searchString = ("SearchString");
    
    let normalizedSearchString = Normalizer.normalize(searchString);
    
    console.log(searchString) // Returns "searchstring";
`

This script is based on the results i found on stackoverflow for removing diacritics from strings.
source: https://stackoverflow.com/questions/863800/replacing-diacritics-in-javascript

Next to this, it removes the standalone accents ' " \` ´ from strings, and replaces the symbols \- \_  with spaces in the string. 
