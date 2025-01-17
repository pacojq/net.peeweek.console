# Console Changelog

## [2021-02-08] - 1.3.0

* Added a `onConsoleToggle` event to hook into when the console visibility changes.
* Added API & Functionality for debug views.

## [2021-01-13] - 1.2.0

Minimal version is now 2019.4

* Added a `Console.ExecuteCommand(string command)` to execute a command from script.
* Fixed namespace in `ConsoleUtility.cs` preventing to Reference `Console.Alias` directly in custom classes.

## [2019-08-24] - 1.1.0

* No more preview label for the package
* Got rid of UGUI ScrollBar, only displays one TextField
* Scrolling uses PageUp/PageDown and custom scrolling system to reduce text rendering overhead
* In order to avoid using `Console.Console` even when `using Console;`due to ambiguous calls, `Console` namespace has been renamed to `ConsoleUtility`
* Ensure command repeat history do not store contiguous duplicates.

## [2019-04-10] - 1.0.1-preview

* Make Console Log Stacktraces on Error/Exception
* Disabled EventSystem GameObject (Can be enabled if used locally)
* Fixed Time Digits

## [2019-01-15] - 1.0.0-preview

* Initial Release
