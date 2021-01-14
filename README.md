### JSON.parse order is not corrected

https://www.rfc-editor.org/rfc/rfc7159.txt

JSON parsing libraries have been observed to differ as to whether or
not they make the ordering of object members visible to calling
software.  Implementations whose behavior does not depend on member
ordering will be interoperable in the sense that they will not be
affected by these differences.

https://stackoverflow.com/questions/7214293/is-the-order-of-elements-in-a-json-list-preserved

An object is an unordered collection of zero or more name/value pairs, where a name is a string and a value is a string, number, boolean, null, object, or array.
`An array is an ordered sequence of zero or more values.`
