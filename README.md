# BasePairs
FreeCode Camp - DNA Pairing

- The DNA strand is missing the pairing element. 
- Take each character, get its pair, and return the results as a 2d array.
- Return the provided character as the first element in each array.
- The character and its pair are paired up in an array, and all the arrays are grouped into one encapsulating array.

- pairElement("ATCGA") should return [["A","T"],["T","A"],["C","G"],["G","C"],["A","T"]].
- pairElement("TTGAG") should return [["T","A"],["T","A"],["G","C"],["A","T"],["G","C"]].
- pairElement("CTCTA") should return [["C","G"],["T","A"],["C","G"],["T","A"],["A","T"]].

Helpful links:

[Array.prototype.push()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push)

[String.prototype.split()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split)
