### JSON.parse order is not corrected

https://www.rfc-editor.org/rfc/rfc7159.txt

JSON parsing libraries have been observed to differ as to whether or
not they make the ordering of object members visible to calling
software.  Implementations whose behavior does not depend on member
ordering will be interoperable in the sense that they will not be
affected by these differences.
