
## 4.7.2 31/07/2021

### Added
- Added concurrency test.

## 4.7.1 20/06/2021

### Fixed
- Fixed type definitions.


## 4.7.0 17/06/2021

### Feature
- Added type definition file.
- Replaced config.cloneFiles = 'skip' with a new property, config.skipExistingFileName
## 4.6.0 10/06/2021

### Feature
- Added the ability to skip downloads if the same file name exists.

## 4.5.3 09/05/2021

### Fixed
- Improved cancellation and timeout handling, by encapsulating all request and error handling inside an async iterator.
No changes to the API.
- Fixed lodash vulnerability
