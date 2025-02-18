### v1.1.6 (27 July 2021)

- [BUGFIX] Added an error object to the catch of isValidTimezoneIANAString for older JS (#131)

### v1.1.5 (27 July 2021)

- [BUGFIX] Fixing parsing IANA strings (#129)

### v1.1.4 (13 April 2021)

- [UPGRADE] Use Yarn berry
- [BUGFIX] Restore IE11 support (#112)

### v1.1.3 (27 February 2021)

- [BUGFIX] Support IANA timezones with a hyphen in the name! (#110)

### v1.1.2 (20 February 2021)

- [BUGFIX] Fix time zone offset around DST; thanks @bsvetlik & @yharaskrik! (#108, #99, #93)

### v1.1.1 (30 January 2021)

- [DOCS] Add `getTimezoneOffset` to TOC

### v1.1.0 (30 January 2021)

- [ENHANCEMENT] Add the `getTimezoneOffset` function (#100).
- [UPGRADE] Upgrade dependencies

### v1.0.12 (9 October 2020)

- [BUGFIX] Improve the #46 fix for `toDate` using the UTC timestamp for determining offset (#86).

### v1.0.11 (5 October 2020)

- [BUGFIX] Fix uctToZonedTime during timezone changes (#80).
- [BUGFIX] Fix `toDate` using the UTC timestamp for determining offset (#46).

### v1.0.10 (10 February 2020)

- [BUGFIX] Fix day wrapping when the result is midnight in new browsers supporting DTF `hourCycle` (#38, #41, #43).

### v1.0.9 (28 December 2019)

- [DOCS] Improve the documentation, particularly on the usage of `format`.

### v1.0.8 (12 October 2019)

- [BUGFIX] Not losing milliseconds when converting time zones. (#25)
- [BUGFIX] Fix missing `_lib/convertToFP/index.js`. (#20)
- [UPGRADE] Upgrade dependencies and match the `date-fns@2` build config.

### v1.0.6 (2 February 2019)

- [BUGFIX] Rewrite import paths in esm version to use esm version of date-fns. (#8 @pkaske)

### v1.0.3 (21 January 2019)

- [BUGFIX] Removed `const`, `let`, template string and arrow function syntax which is not transpiled in
  the ems build to fix for IE11.

### v1.0.0 (12 January 2019)

- [ENHANCEMENT] Typescript typings.

### v0.1.1 (13 November 2018)

Initial release.
