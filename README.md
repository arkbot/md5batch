# md5batch

`md5batch` is a tiny [bash](https://www.gnu.org/software/bash/manual/bashref.html) script for manually monitoring [bitrot](https://en.wikipedia.org/wiki/Bitrot).

<!-- TABLE OF CONTENTS -->

* [Features + Requirements](#features--requirements)
* [Installation Options](#installation-options)
* [General Usage](#general-usage)
* [Future Thoughts](#future-thoughts)
* [Bug Reports + Feature Requests](#bug-reports--feature-requests)
* [Further Notes](#further-notes)

<!-- FEATURES + REQUIREMENTS -->

### Features + Requirements

* Provides functionality for creating/verifying individual `.md5sum` files.
* Supports conversion between individual `.md5sum` files and traditional checklist formats.
* Requires the [GNU](https://www.gnu.org/) `md5sum` binary discoverable in `$PATH` (tested with version 8.20).

<!-- INSTALLATION OPTIONS -->

### Installation Options

* Download the [raw export](https://raw.github.com/arkbot/md5batch/master/bin/md5batch) or [package tarball](https://github.com/arkbot/md5batch/tarball/master).
* Clone GIT repository: `git clone git@github.com:arkbot/md5batch.git`

<!-- GENERAL USAGE -->

### General Usage

> TODO: include `--help` or `man` text here.

<!-- FUTURE THOUGHTS -->

### Future Thoughts

* Build packages for popular distributions ([`.deb`](http://www.debian.org/doc/manuals/debian-faq/ch-pkg_basics.en.html), [`.rpm`](http://en.wikipedia.org/wiki/RPM_Package_Manager), [`.pkg.tar.xz`](https://wiki.archlinux.org/index.php/Pacman), etc.)

<!-- BUG REPORTS + FEATURE REQUESTS -->

### Bug Reports + Feature Requests

* Submit an issue on the [GitHub Tracker](https://github.com/arkbot/md5batch/issues) for bug reports and feature requests.
* Please e-mail me before sending a pull request.

<!-- FURTHER NOTES -->

### Further Notes

* Released under the [MIT License](http://www.opensource.org/licenses/MIT) ([attached](https://github.com/arkbot/md5batch/blob/master/LICENSE.txt)).
* DISCLAIMER: NO WARRANTY OR RESPONSIBILITY EXPRESSED OR IMPLIED.