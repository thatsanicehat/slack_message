# Changelog

## [Unreleased]

## [1.8.0] - 2021-10-07
- Added the ability to test in RSpec

## [1.7.1] - 2021-10-06
- Fixed literally a syntax issue.
- Fixed specs.
- Fixed API to include JSON since consumers may not have loaded it.

## [1.7.0] - 2021-10-06
- THIS RELEASE IS BADLY BROKEN.
- Added new error messages when API configuration is wrong / missing.
- Fixed issue with `instance_eval` and using methods within block.
- Fixed issue with sectionless `list_item`.

## [1.6.0] - 2021-10-04
- Added `:default_channel` and `post_as` to deal with repetitive channel usage.

## [1.5.0] - 2021-10-01
- Added `ol` and `ul` to sections w/ some formatting.

## [1.4.0] - 2021-09-27
- Changed `image` to `accessory_image` to differentiate between the image block
  and the accessory image within a block.

## [1.3.0] - 2021-09-27
- Added ability to use custom names when posting.
- Added ability to post images within sections.
- Added warnings for potentially invalid URLs.

## [1.2.0] - 2021-09-26
- Fixed gemspec, which was entirely broken.

## [1.1.0] - 2021-09-26
- Expanded the README significantly w/ usage instructions.
- Added lots of error handling to requests.

## [1.0.0] - 2021-09-25
- Added the base gem w/ a DSL for constructing blocks using sections.
- Added a changelog, apparently.