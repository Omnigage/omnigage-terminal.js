# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.3.1] - 2018-07-20
### Added
- Added `.on()` to the JavaScript API for subscribing to `render`, `dial`, `hangup`, `voicemailDrop` and `playDrop` events
- Added `.perform()` to the JavaScript API for sending the following actions:  `dial`, `hangup`, `voicemailDrop` and `playDrop`

### Changed
- Renamed JavaScript API config option `show` to `render`
- Renamed JavaScript API method `show` to `render`

## [0.3.0] - 2018-07-13
### Added
- Browse caller IDs, add, edit, and delete (archive). Includes collaborators browse, add, edit, and delete.
- Workflow for creating a caller ID on the dialer. Once caller ID is validated, Terminal redirects back to the dialer and automatically selects new caller ID.
- Can choose tags when creating a voice template.
- Ability to filter by tags on voice templates collection.
- Added additional JavaScript API configuration: `show`, `color`, `theme`.
- Added `isAuthenticated` to JavaScript API.
- Expanded JavaScript API to include ability to `.show()`: `callerIds`, `callerIdsAdd`, and `callerIdsEdit`

## [0.2.0] - 2018-06-29
### Added
- Added ability to browse engagements, add, edit, and delete (archive).
- Engagements activities including voice, text, email, and click-to-dial.
- Engagement workflow including delivery settings, compliance review and submit for processing.
- Engagement results including queues and metrics.
- Expanded JavaScript API to include ability to `.show()`: `engagements`, `engagementsAdd`, and `engagementsEdit`
- JavaScript API `.inputs()` supports `engagementsAdd` and `engagementsEdit` with `name` key/value pair
- Additional `.config()` options for the JavaScript API including `isAnchored`, `appendTo`, `width`, `height`, `heightCollapsed`, `zIndex`, and `init`

## [0.1.1] - 2018-06-18
### Changed
- Pruned fonts from build process to reduce overall release archive from 5.6 MB to 3.1 MB.

## [0.1.0] - 2018-06-15
### Added
- Dialer with caller ID selection, agent phone number and phone number to call. Includes parent and child call leg management.
- Ability to send texts with phone number selection, phone number to send the message to and the body of the message.
- Ability to send emails view with email ID selection, recipient, subject and body.
- Voice recordings collection browsing, add, edit and archive. Ability to call yourself to record a message, record natively in browser or upload a recording. Includes revisions and ability to manage collaborators.
- JavaScript API methods `.ready`, `.config`, `.show` and `.inputs`
- Embed script for placing application in iframe and exposing the JavaScript API.
- Engagements collection browsing.

[0.2.0]: https://github.com/omnigage/omnigage-terminal.js/releases/tag/0.2.0
[0.1.1]: https://github.com/omnigage/omnigage-terminal.js/releases/tag/0.1.1
[0.1.0]: https://github.com/omnigage/omnigage-terminal.js/releases/tag/0.1.0
