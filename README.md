# cldr-json

JSON distribution of [CLDR](http://cldr.unicode.org/) locale data for internationalization

### Latest Release
[![Latest Official Release](https://img.shields.io/github/v/tag/unicode-org/cldr-json?sort=semver)](https://github.com/unicode-org/cldr-json/releases/latest)

Although XML (not JSON) is the "official" format for all CLDR data, this data is programatically generated from the
corresponding XML, using the CLDR tooling.

This JSON data is generated using only data that has achieved
`draft="contributed"` or `draft="approved"` status in the CLDR. This is the same threshold
as is used by the [ICU](https://icu.unicode.org) (International Components for Unicode).

See [UPDATING.md](./UPDATING.md) for details on building or customizing this data yourself.

### Who uses cldr-json?

See [USERS.md](./USERS.md) for a list of libraries
which use this data.

## Package Organization

Because the CLDR is so large and contains so many different types of information, the JSON data
here is grouped into packages by functionality.

See [PACKAGES.md](./PACKAGES.md) for the full package list and details of each package.

## Downloading
### Tagged Releases

See the [releases](https://github.com/unicode-org/cldr-json/releases) page for a list of cldr-json releases. As of v38, all
JSON data is contained in this single repository.

The GitHub release page also contains .zip files where you can download all full or modern data in a single .zip.

## npm packages

Installation using [npm](https://www.npmjs.com):

    $ npm install <package-name> , where <package-name> is one of the package names mentioned above, for example:

    $ npm install cldr-dates-full

(Note that bower is deprecated, please use npm.)

## Bug reports / Contributing

CLDR does not use Github's issue tracking system to track bugs.  If you find an error in
the data contained here, please file a new ticket at [Unicode Jira](https://unicode-org.atlassian.net/projects/CLDR/issues)

### Copyright & Licenses

Copyright © 2015-2024 Unicode, Inc. Unicode and the Unicode Logo are registered trademarks of Unicode, Inc. in the United States and other countries.

A CLA is required to contribute to this project - please refer to the [CONTRIBUTING.md](./CONTRIBUTING.md) file (or start a Pull Request) for more information.

The contents of this repository are governed by the Unicode [Terms of Use](https://www.unicode.org/copyright.html) and are released under [LICENSE](./LICENSE).
