# Issue:

Reproducble sammple for issue: https://github.com/dart-lang/test/issues/1977

This is a dart package with no depdency to flutter nor its sdk packages (like flutter_test).

pubspec.lock is not checked in.

When running `flutter test` it fails with:

```
00:00 +0 -1: loading .../something/test/src/something_test.dart [E]                                                                                                                                                                                                                                                                                                                                  
  Failed to load ".../something/test/src/something_test.dart": type 'Null' is not a subtype of type 'Object' in type cast
  package:test_api  RemoteListener.start.<fn>.<fn>
  

To run this test again: ...
00:00 +0 -1: Some tests failed.    
```