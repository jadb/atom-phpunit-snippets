# PHPUnit Snippets

Snippets to help you writing [PHPUnit](http://phpunit.de) tests in [Atom.io](http://atom.io).

```php
// assertArrayHasKey + [TAB]
$this->assertArrayHasKey($key, $array, "message");

// assertArrayNotHasKey + [TAB]
$this->assertArrayNotHasKey($key, $array, "message");

// assertContains + [TAB]
$this->assertContains($needle, $haystack, "message", $ignoreCase = false, $checkForObjectIdentity = true, $checkForNonObjectIdentity = false);

// assertAttributeContains + [TAB]
$this->assertAttributeContains($needle, $haystack, "message", $ignoreCase = false, $checkForObjectIdentity = true, $checkForNonObjectIdentity = false);

// assertNotContains + [TAB]
$this->assertNotContains($needle, $haystack, "message", $ignoreCase = false, $checkForObjectIdentity = true, $checkForNonObjectIdentity = false);

// assertAttributeNotContains + [TAB]
$this->assertAttributeNotContains($needle, $haystack, "message", $ignoreCase = false, $checkForObjectIdentity = true, $checkForNonObjectIdentity = false);

// assertContainsOnly + [TAB]
$this->assertContainsOnly($type, $haystack, $isNativeType = NULL, "message");

// assertContainsOnlyInstancesOf + [TAB]
$this->assertContainsOnlyInstancesOf($classname, $haystack, "message");

// assertAttributeContainsOnly + [TAB]
$this->assertAttributeContainsOnly($type, $haystackAttributeName, $haystackClassOrObject, $isNativeType = null, "message");

// assertNotContainsOnly + [TAB]
$this->assertNotContainsOnly($type, $haystack, $isNativeType = null, "message");

// assertAttributeNotContainsOnly + [TAB]
$this->assertAttributeNotContainsOnly($type, $haystackAttributeName, $haystackClassOrObject, $isNativeType = null, "message");

// assertCount + [TAB]
$this->assertCount($expectedCount, $haystack, "message");

// assertAttributeCount + [TAB]
$this->assertAttributeCount($expectedCount, $haystackAttributeName, $haystackClassOrObject, "message");

// assertNotCount + [TAB]
$this->assertNotCount($expectedCount, $haystack, "message");

// assertAttributeNotCount + [TAB]
$this->assertAttributeNotCount($expectedCount, $haystackAttributeName, $haystackClassOrObject, "message");

// assertEquals + [TAB]
$this->assertEquals($expected, $actual, "message", $delta = 0, $maxDepth = 10, $canonicalize = false, $ignoreCase = false);

// assertAttributeEquals + [TAB]
$this->assertAttributeEquals($expected, $actualAttributeName, $actualClassOrObject, "message", $delta = 0, $maxDepth = 10, $canonicalize = false, $ignoreCase = false);

// assertNotEquals + [TAB]
$this->assertNotEquals($expected, $actual, "message", $delta = 0, $maxDepth = 10, $canonicalize = false, $ignoreCase = false);

// assertAttributeNotEquals + [TAB]
$this->assertAttributeNotEquals($expected, $actualAttributeName, $actualClassOrObject, "message", $delta = 0, $maxDepth = 10, $canonicalize = false, $ignoreCase = false);

// assertEmpty + [TAB]
$this->assertEmpty($actual, "message");

// assertAttributeEmpty + [TAB]
$this->assertAttributeEmpty($haystackAttributeName, $haystackClassOrObject, "message");

// assertNotEmpty + [TAB]
$this->assertNotEmpty($actual, "message");

// assertAttributeNotEmpty + [TAB]
$this->assertAttributeNotEmpty($haystackAttributeName, $haystackClassOrObject, "message");

// assertGreaterThan + [TAB]
$this->assertGreaterThan($expected, $actual, "message");

// assertAttributeGreaterThan + [TAB]
$this->assertAttributeGreaterThan($expected, $actualAttributeName, $actualClassOrObject, "message");

// assertGreaterThanOrEqual + [TAB]
$this->assertGreaterThanOrEqual($expected, $actual, "message");

// assertAttributeGreaterThanOrEqual + [TAB]
$this->assertAttributeGreaterThanOrEqual($expected, $actualAttributeName, $actualClassOrObject, "message");

// assertLessThan + [TAB]
$this->assertLessThan($expected, $actual, "message");

// assertAttributeLessThan + [TAB]
$this->assertAttributeLessThan($expected, $actualAttributeName, $actualClassOrObject, "message");

// assertLessThanOrEqual + [TAB]
$this->assertLessThanOrEqual($expected, $actual, "message");

// assertAttributeLessThanOrEqual + [TAB]
$this->assertAttributeLessThanOrEqual($expected, $actualAttributeName, $actualClassOrObject, "message");

// assertFileEquals + [TAB]
$this->assertFileEquals($expected, $actual, "message", $canonicalize = false, $ignoreCase = false);

// assertFileNotEquals + [TAB]
$this->assertFileNotEquals($expected, $actual, "message", $canonicalize = false, $ignoreCase = false);

// assertStringEqualsFile + [TAB]
$this->assertStringEqualsFile($expectedFile, $actualString, "message", $canonicalize = false, $ignoreCase = false);

// assertStringNotEqualsFile + [TAB]
$this->assertStringNotEqualsFile($expectedFile, $actualString, "message", $canonicalize = false, $ignoreCase = false);

// assertFileExists + [TAB]
$this->assertFileExists($filename, "message");

// assertFileNotExists + [TAB]
$this->assertFileNotExists($filename, "message");

// assertTrue + [TAB]
$this->assertTrue($condition, "message");

// assertNotTrue + [TAB]
$this->assertNotTrue($condition, "message");

// assertFalse + [TAB]
$this->assertFalse($condition, "message");

// assertNotFalse + [TAB]
$this->assertNotFalse($condition, "message");  

// assertNotNull + [TAB]
$this->assertNotNull($actual, "message");

// assertNull + [TAB]
$this->assertNull($actual, "message");

// assertClassHasAttribute + [TAB]
$this->assertClassHasAttribute($attributeName, $className, "message");

// assertClassNotHasAttribute + [TAB]
$this->assertClassNotHasAttribute($attributeName, $className, "message");

// assertClassHasStaticAttribute + [TAB]
$this->assertClassHasStaticAttribute($attributeName, $className, "message");

// assertClassNotHasStaticAttribute + [TAB]
$this->assertClassNotHasStaticAttribute($attributeName, $className, "message");

// assertObjectHasAttribute + [TAB]
$this->assertObjectHasAttribute($attributeName, $object, "message");

// assertObjectNotHasAttribute + [TAB]
$this->assertObjectNotHasAttribute($attributeName, $object, "message");

// assertSame + [TAB]
$this->assertSame($expected, $actual, "message");

// assertAttributeSame + [TAB]
$this->assertAttributeSame($expected, $actualAttributeName, $actualClassOrObject, "message");

// assertNotSame + [TAB]
$this->assertNotSame($expected, $actual, "message");

// assertAttributeNotSame + [TAB]
$this->assertAttributeNotSame($expected, $actualAttributeName, $actualClassOrObject, "message");

// assertInstanceOf + [TAB]
$this->assertInstanceOf($expected, $actual, "message");

// assertAttributeInstanceOf + [TAB]
$this->assertAttributeInstanceOf($expected, $attributeName, $classOrObject, "message");

// assertNotInstanceOf + [TAB]
$this->assertNotInstanceOf($expected, $actual, "message");

// assertAttributeNotInstanceOf + [TAB]
$this->assertAttributeNotInstanceOf($expected, $attributeName, $classOrObject, "message");

// assertInternalType + [TAB]
$this->assertInternalType($expected, $actual, "message");

// assertAttributeInternalType + [TAB]
$this->assertAttributeInternalType($expected, $attributeName, $classOrObject, "message");

// assertNotInternalType + [TAB]
$this->assertNotInternalType($expected, $actual, "message");

// assertAttributeNotInternalType + [TAB]
$this->assertAttributeNotInternalType($expected, $attributeName, $classOrObject, "message");

// assertRegExp + [TAB]
$this->assertRegExp($pattern, $string, "message");

// assertNotRegExp + [TAB]
$this->assertNotRegExp($pattern, $string, "message");  

// assertSameSize + [TAB]
$this->assertSameSize($expected, $actual, "message");

// assertNotSameSize + [TAB]
$this->assertNotSameSize($expected, $actual, "message");

// assertStringMatchesFormat + [TAB]
$this->assertStringMatchesFormat($format, $string, "message");

// assertStringNotMatchesFormat + [TAB]
$this->assertStringNotMatchesFormat($format, $string, "message");

// assertStringMatchesFormatFile + [TAB]
$this->assertStringMatchesFormatFile($formatFile, $string, "message");

// assertStringNotMatchesFormatFile + [TAB]
$this->assertStringNotMatchesFormatFile($formatFile, $string, "message");

// assertStringStartsWith + [TAB]
$this->assertStringStartsWith($prefix, $string, "message");

// assertStringStartsNotWith + [TAB]
$this->assertStringStartsNotWith($prefix, $string, "message");

// assertStringEndsWith + [TAB]
$this->assertStringEndsWith($suffix, $string, "message");

// assertStringEndsNotWith + [TAB]
$this->assertStringEndsNotWith($suffix, $string, "message");

// assertXmlFileEqualsXmlFile + [TAB]
$this->assertXmlFileEqualsXmlFile($expectedFile, $actualFile, "message");

// assertXmlFileNotEqualsXmlFile + [TAB]
$this->assertXmlFileNotEqualsXmlFile($expectedFile, $actualFile, "message");

// assertXmlStringEqualsXmlFile + [TAB]
$this->assertXmlStringEqualsXmlFile($expectedFile, $actualXml, "message");

// assertXmlStringNotEqualsXmlFile + [TAB]
$this->assertXmlStringNotEqualsXmlFile($expectedFile, $actualXml, "message");

// assertXmlStringEqualsXmlString + [TAB]
$this->assertXmlStringEqualsXmlString($expectedXml, $actualXml, "message");  

// assertXmlStringNotEqualsXmlString + [TAB]
$this->assertXmlStringNotEqualsXmlString($expectedXml, $actualXml, "message");

// assertEqualXMLStructure + [TAB]
$this->assertEqualXMLStructure($expectedElement, $actualElement, $checkAttributes = false, "message");

// assertSelectCount + [TAB]
$this->assertSelectCount($selector, $count, $actual, "message", $isHtml = true);

// assertSelectRegExp + [TAB]
$this->assertSelectRegExp($selector, $pattern, $count, $actual, "message", $isHtml = true);

// assertSelectEquals + [TAB]
$this->assertSelectEquals($selector, $content, $count, $actual, "message", $isHtml = true);

// assertTag + [TAB]
$this->assertTag($matcher, $actual, "message", $isHtml = true);

// assertNotTag + [TAB]
$this->assertNotTag($matcher, $actual, "message", $isHtml = true);

// assertThat + [TAB]
$this->assertThat($value, $constraint, "message");

// assertJson + [TAB]
$this->assertJson($actualJson, "message");

// assertJsonStringEqualsJsonString + [TAB]
$this->assertJsonStringEqualsJsonString($expectedJson, $actualJson, "message");

// assertJsonStringNotEqualsJsonString + [TAB]
$this->assertJsonStringNotEqualsJsonString($expectedJson, $actualJson, "message");

// assertJsonStringEqualsJsonFile + [TAB]
$this->assertJsonStringEqualsJsonFile($expectedFile, $actualJson, "message");

// assertJsonStringNotEqualsJsonFile + [TAB]
$this->assertJsonStringNotEqualsJsonFile($expectedFile, $actualJson, "message");

// assertJsonFileNotEqualsJsonFile + [TAB]
$this->assertJsonFileNotEqualsJsonFile($expectedFile, $actualFile, "message");

// assertJsonFileEqualsJsonFile + [TAB]
$this->assertJsonFileEqualsJsonFile($expectedFile, $actualFile, "message");
```

## Patches & Features

* Fork
* Mod, fix
* Test - this is important, so it's not unintentionally broken
* Commit - do not mess with license, todo, version, etc. (if you do change any, bump them into commits of their own that I can ignore when I pull)
* Pull request - bonus point for topic branches

## Bugs & Feedback

http://github.com/gourmet/common/issues

### Known bugs

* Snippets with more than 10+ placeholders - tabs don't work as expected yet.

## License

Copyright 2014, [Jad Bitar](http://jadb.io)

Licensed under [The MIT License](http://www.opensource.org/licenses/mit-license.php)

Redistributions of files must retain the above copyright notice.
