# CHANGELOG

## 1.1.7 - 2018-01-06

* The tests were fixed.

* Changes in documentation.

## 1.1.6 - 2017-11-09

* Implemented `PHP Mess Detector` to detect inconsistencies in code styles.

* Implemented `PHP Code Beautifier and Fixer` to fixing errors automatically.

* Implemented `PHP Coding Standards Fixer` to organize PHP code automatically according to PSR standards.

## 1.1.5 - 2017-11-02

* Implemented `PSR-2 coding standard` from all library PHP files.

* Implemented `PHPCS` to ensure that PHP code complies with `PSR2` code standards.

* Implemented `Codacy` to automates code reviews and monitors code quality over time.

* Implemented `Codecov` to coverage reports.

* Added `DataType/phpcs.ruleset.xml` file.

## 1.1.4 - 2017-10-19

* Autoloaded with `PSR-4` all library files and test files

* Dropped the use of a `JSON` file with mime types list and used `PHP` class instead.

* Deleted `Josantonius\MimeType\MimeType::_getFromFile()` method.

* Changed `Josantonius\MimeType\Test\MimeTypeTest` class to `Josantonius\MimeType\MimeTypeTest` class.

* Deleted `MimeType/src/bootstrap.php` file

* Deleted `MimeType/tests/bootstrap.php` file.

* Deleted `MimeType/vendor` folder.

* Deleted `MimeType/resources` folder

* Added `Josantonius\MimeType\MimeTypesCollection` class.
* Added `Josantonius\MimeType\MimeTypesCollection::all()` method.
* Added `Josantonius\MimeType\MimeTypesCollection::get()` method.

## 1.1.3 - 2017-09-10

* Unit tests supported by `PHPUnit` were added.

* The repository was synchronized with Travis CI to implement continuous integration.

* Deleted `Josantonius\MimeType\MimeType::load()` method.
* Deleted `Josantonius\MimeType\MimeType::getAll()` method.

* Added `Josantonius\MimeType\MimeType::get()` method.

* Added `Josantonius\MimeType\MimeType::get()` method.

* Deleted `Josantonius\MimeType\Tests\MimeTypeTest` class.
* Deleted `Josantonius\MimeType\Tests\MimeTypeTest::testGetMimeFromExtension()` method.
* Deleted `Josantonius\MimeType\Tests\MimeTypeTest::testGetMimeFromExtensionUndefined()` method.
* Deleted `Josantonius\MimeType\Tests\MimeTypeTest::testGetExtensionFromMime()` method.
* Deleted `Josantonius\MimeType\Tests\MimeTypeTest::testGetExtensionFromMimeUndefined()` method.
* Deleted `Josantonius\MimeType\Tests\MimeTypeTest::testGetAll()` method.

* Added `Josantonius\MimeType\Test\MimeTypeTest::_getFromFile()` method.
* Added `Josantonius\MimeType\Test\MimeTypeTest` class.
* Added `Josantonius\MimeType\Test\MimeTypeTest::testGetMimeFromExtension()` method.
* Added `Josantonius\MimeType\Test\MimeTypeTest::testGetMimeFromExtensionUndefined()` method.
* Added `Josantonius\MimeType\Test\MimeTypeTest::testGetExtensionFromMime()` method.
* Added `Josantonius\MimeType\Test\MimeTypeTest::testGetExtensionFromMimeUndefined()` method.

* Added `MimeType/src/bootstrap.php` file

* Added `MimeType/tests/bootstrap.php` file.

* Added `MimeType/phpunit.xml.dist` file.
* Added `MimeType/_config.yml` file.
* Added `MimeType/.travis.yml` file.

## 1.1.2 - 2017-07-16

* Deleted `Josantonius\MimeType\Exception\MimeTypeException` class.
* Deleted `Josantonius\MimeType\Exception\Exceptions` abstract class.
* Deleted `Josantonius\MimeType\Exception\MimeTypeException->__construct()` method.

## 1.1.1 - 2017-03-18

* Some files were excluded from download and comments and readme files were updated.

## 1.1.0 - 2017-01-31

* Compatible with PHP 5.6 or higher.

## 1.0.0 - 2017-01-31

* Compatible only with PHP 7.0 or higher. In the next versions, the library will be modified to make it compatible with PHP 5.6 or higher.

## 1.0.0 - 2016-12-19

* Added `Josantonius\MimeType\MimeType` class.
* Added `Josantonius\MimeType\MimeType::load()` method.
* Added `Josantonius\MimeType\MimeType::getMimeFromExtension()` method.
* Added `Josantonius\MimeType\MimeType::getExtensionFromMime()` method.
* Added `Josantonius\MimeType\MimeType::getAll()` method.

## 1.0.0 - 2016-12-19

* Added `Josantonius\MimeType\Exception\MimeTypeException` class.
* Added `Josantonius\MimeType\Exception\Exceptions` abstract class.
* Added `Josantonius\MimeType\Exception\MimeTypeException->__construct()` method.

## 1.0.0 - 2016-12-19

* Added `Josantonius\MimeType\Tests\MimeTypeTest` class.
* Added `Josantonius\MimeType\Tests\MimeTypeTest::testGetMimeFromExtension()` method.
* Added `Josantonius\MimeType\Tests\MimeTypeTest::testGetMimeFromExtensionUndefined()` method.
* Added `Josantonius\MimeType\Tests\MimeTypeTest::testGetExtensionFromMime()` method.
* Added `Josantonius\MimeType\Tests\MimeTypeTest::testGetExtensionFromMimeUndefined()` method.
* Added `Josantonius\MimeType\Tests\MimeTypeTest::testGetAll()` method.
