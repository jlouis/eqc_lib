# Erlang QuickCheck Library

The `eqc_lib` library is a drop-in library for QuickCheck test cases. It contains some generators which has been tuned to uncover trouble, as well as some helper functions which has proved to be useful in many situations.

The library is not meant to be "included" as a separate application, but rather "dropped" into a test case directly. There is a `-vsn(…)` field to verify exactly what version you have. The versioning is semantic, of the `X.Y.Z` kind.
