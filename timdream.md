# Week of Apr 19, 2016

(Excluding management-related tasks)

## Firefox QX

* [Bug 1266372](https://bugzil.la/1266372) - The close reader mode button on page should behave the same as bug 1184950
 * Proposed a patch to share code. Likely to be depend on bug 1264805.
* [Bug 1264805](https://bugzil.la/1264805) - Leaving Reader Mode should not reload on Fennec
 * r+'d, need to figure out test situration before landing
* [Bug 1184950](https://bugzil.la/1184950) - Leaving Reader Mode should not reload
 * FIXED
* [Bug 1229727](https://bugzil.la/1229727) - Mac OS X full screen warning
 * FIXED

## Firefox

* [Bug 1263760](https://bugzil.la/1263760) - TabSwitchDone does not fire when a dialog is opened
 * bug caused by quirky behavior of nested event loop 
 * r+'d, to be checked in when Try turns green.
* [Bug 1243729](https://bugzil.la/1243729) - Username is overwritten with a blank one when updating the password for a Twitter account
 * FIXED
 * Preparing patch for beta uplift
* [Bug 1243722](https://bugzil.la/1243722) - Wrong doorhanger when updating password on Facebook
 * FIXED
 * Preparing patch for beta uplift