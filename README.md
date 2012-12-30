Xcode 4 Templates
=================

A collection of the default Xcode 4 templates, edited to fit my preferred coding environment.

- Added `-dealloc` methods to all of the classes
- Added an `NSMutableArray *datasource` to the UITableViewControllers
- Added the default `if (cell == nil) … initialise cell …` to the UITableViewController `-cellForRowAtIndexPath` method
- Renamed `CellIdentifier` to `reuseIdentifier` in the `-cellForRowAtIndexPath` method in the UITableViewControllers 
- Removed the commented delegate methods in the UITableViewControllers i.e. `-willCommitEditingStyle` etc
- Added `-prepareForReuse` and `-reuseIdentifier` to the UITableViewCell subclass template

NB: I haven't edited the iPad classes as I don't develop for iPad.

Enjoy!

