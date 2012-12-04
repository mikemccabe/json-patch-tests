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

All fields except 'doc' and 'patch' are optional.  Test records consisting only of a comment are also OK.

This test set is not complete, or even correct - help welcome!

Credits
-------

The seed test set was adapted from https://github.com/bruth/jsonpatch-js/blob/master/test.js .


License
-------

 Copyright 2012 Michael McCabe
 
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

