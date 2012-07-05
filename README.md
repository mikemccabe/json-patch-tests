json-patch-tests
================

Test cases for implementations of json-patch:

http://tools.ietf.org/html/draft-ietf-appsawg-json-patch-02

Test format
-----------

The test file contains a list of test records, each with a few
fields that defines a test.

- doc: The JSON document to test against
- patch: The patch(es) to apply.
- expected: The expected resulting document, OR
- error: A string describing an expected error
- comment: A string describing the test
- disabled: True if the test should be skipped.

All fields except 'doc' and 'patch' are optional.

This test set is not complete - additions are welcome!
