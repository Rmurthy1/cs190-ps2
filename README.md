# CS 190 Problem Set #2&mdash;Accepting Digit Entry

In this problem set, you will complete a keyboard that enters digits into calculator registers A and B as the user presses the buttons.

Course Home Page: http://physics.stmarys-ca.edu/classes/CS190_S16/index.html.

My St. Mary's Home Page: http://physics.stmarys-ca.edu/lecturers/brianrhill/index.html.

Due: By the beginning of class, Tuesday, February 23rd, 2016.
## Reading that Might be Helpful for this Problem Set

* iOS Technology (Windows and Views):
 * https://developer.apple.com/library/ios/documentation/WindowsViews/Conceptual/ViewPG_iPhoneOS/Introduction/Introduction.html
* iOS Technology (Creating an Outlet Connection):
 * https://developer.apple.com/library/ios/recipes/xcode_help-IB_connections/chapters/CreatingOutlet.html (Unfortunately the code examples in this document are Objective-C)
* More Advanced iOS Technology (if you want to see how I made the display flicker):
 * https://developer.apple.com/library/ios/documentation/QuartzCore/Reference/CADisplayLink_ClassRef/index.html.
* Computer Science (Objects and Protocols in the Swift language):
 * https://itunes.apple.com/us/book/the-swift-programming-language/id881256329.

## Directions Specific to this Problem Set

THIS IS A WORK IN PROGRESS. IF YOU ARE READING THIS IN YOUR FORK, THEN YOU FORKED BEFORE I FINISHED WRITING THE PROBLEM SET. PLEASE DELETE YOUR FORK AND THEN FORK AGAIN AFTER I HAVE FINISHED WRITING IT UP.

1. (2 pts) The keyboard is incomplete. Add the nine missing buttons. Make sure they align nicely with the buttons that are already present and that the view constraints do not generate warnings, and work reasonably in portrait mode only with a couple of different iPhone simulations.

2. (2 pts) Connect the new buttons up using the target-action method defined on the view controller. You can check your work by setting a breakpoint in the debugger and making sure that it is hit each time you press a button.

3. (6 pts) The only two keys on the keyboard that do anything right now are the Enter Key, the 0 key, and the Pi key. What The Pi key does is exactly as if you had typed 3.141592654 and then pressed Enter, but the Pi just goes straight to the result. Your job is to make the CHS, EEX, CLX, 1, 2, 3, 4, 5, 6, 7, 8, 9 and Decimal Point keys all work. To do this, you will have to read and understand the way the calculator holds data in Registers A, B and C. The relevant references for this are in the comments in the code. You can QA your work by comparing what happens when you hit the ENTER, CHS, EEX, CLx, 0, DecimalPoint, Pi, 1, 2, 3, 4, 5, 6, 7, 8 and 9 keys. There should be perfect agreement in what is displayed. If there isn't, well, Houston, we have a problem.

If you want to see a real Hewlett-Packard 35, I can bring one to office hours.

## General Directions for all Problem Sets

1. Fork this repository to create a repository in your own Github account. Then clone your fork to whatever machine you are working on. More detailed directions for this step were given in the README for Problem Set #1: https://github.com/brianhill/cs190-ps1.

2. These problem sets are created with the latest version of Xcode and Mac OS X: XCode 7.2.1 and OS X 10.11.3. Do not run beta versions of Apple's software. During the term, we will probably move to Xcode 7.3, depending on Apple's release schedule. Currently Xcode 7.3 is in beta.

3. Under no circumstances copy-and-paste any part of a solution from another student in the class. Also, under no circumstances ask outsiders on Stack Exchange or other programmers' forums to help you create a solution. It is however fine&mdash;especially when you are truly stuck&mdash;to ask others to help you with your solution, provided you do all of the typing. They should only be looking over your shoulder and commenting.

4. Your solution should be clean and exhibit good style. At minimum, Xcode should not flag warnings of any kind. The style should match Apple's as shown by their examples and declarations. Use the same indentation and spacing around operators as Apple uses. Use their capitalization conventions. Use parts of speech and grammatical number the same way as Apple does.  Use descriptive names for variables, not acronyms or abbreviations. In the Xcode preferences pane, set a page guide at Column 120 and don't exceed it.

5. When completed, and before the time the problem set is due, commit your changes to your fork of the repository. More detailed directions for this step were also given in the README for Problem Set #1. I should be able to simply clone your fork, build it and execute it in my environment without encountering any warnings, adding any dependencies or making any modifications.

###### _The contents of this repository are licensed under the_ [Creative Commons Attribution-ShareAlike License](http://creativecommons.org/licenses/by-sa/3.0/)
