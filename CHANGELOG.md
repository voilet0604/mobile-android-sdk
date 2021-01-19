# DocuSign Android SDK Changelog

## [v1.1.0] - DocuSign Android SDK 10-09-2020

### Added
* Added Online Signing feature
* Added useTemplateOnline() api in TemplateDelegate to use template and EnvelopeDefaults for Online Signing
* Added useTemplateOffline() api in TemplateDelegate to use template and EnvelopeDefaults for Offline Signing 
* Added signOnline() api in SigningDelegate to sign document Online
* Added signOffline() api in SigningDelegate to sign document Offline
* Added API to download the completed envelope

### Removed
* Removed useTemplate() api in TemplateDelegate
* Removed sign() api in SigningDelegate

### Fixed
* Bug fixes and improvements
* Removed RAM requirements


## [v1.0.4] - DocuSign Android SDK 09-17-2020

### Added
* Partial support for branding feature
* Attaching a pdf file to the template documents before offline signing via templates
* Many bug fixes and enhancements

## [v1.0.3] - DocuSign Android SDK 08-30-2020

### Fixed
* Syncing envelope crash with different Locale
* Editing read only tabs issue
* Consumer Disclosure issue for JWT Token login
* Crash when using online signing

## [v1.0.2] - DocuSign Android SDK 07-20-2020

### Fixed
* Removed external library dependencies from sdk artifact.
* Syncing envelope issue for large files during different network conditions

## [v1.0.0] - DocuSign Android SDK 07-01-2020

### Added
* Initial release of DocuSign Android SDK.

