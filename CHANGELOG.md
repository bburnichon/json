Changelog
=========

* 1.1.0 (2015-12-11)

 * added `IOException` and better error handling in `JsonEncoder::encodeFile()`
   and `JsonDecoder::decodeFile()`
 * `JsonEncoder::encodeFile()` now creates missing directories on demand
 * `JsonEncoder` now throws an exception on all PHP versions when binary values 
   are passed
 * added support for disabled slash escaping on PHP below 5.4

* 1.0.2 (2015-08-11)

 * fixed decoding of `null`

* 1.0.1 (2015-06-04)

 * fixed detection of the JSONC library in `JsonDecoder::decodeJson()`

* 1.0.0 (2015-03-19)

 * flipped `$data` and `$file` arguments of `JsonEncoder::encodeFile()`

* 1.0.0-beta (2015-01-12)

 * renamed `SchemaException` to `InvalidSchemaException`
 * changed `JsonValidator::validate()` to return the discovered errors instead
   of throwing an exception

* 1.0.0-alpha1 (2014-12-03)

 * first alpha release
