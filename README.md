JSON Patch Tests
================

These are test cases for implementations of the [IETF JSON Patch
draft](http://tools.ietf.org/html/draft-ietf-appsawg-json-patch).


Test Format
-----------

Each test file is a JSON document that contains an array of test records. A
test record is an object with the following members:

- doc: The JSON document to test against
- patch: The patch(es) to apply
- expected: The expected resulting document, OR
- error: A string describing an expected error
- comment: A string describing the test
- disabled: True if the test should be skipped

All fields except 'doc' and 'patch' are optional. Test records consisting only
of a comment are also OK.

These tests are not complete, or even correct - help welcome!

Credits
-------

The seed test set was adapted from Byron Ruth's
[jsonpatch-js](https://github.com/bruth/jsonpatch-js/blob/master/test.js) and
extended by [Mike McCabe](https://github.com/mikemccabe).
