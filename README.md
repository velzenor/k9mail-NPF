# About This Fork

This is a fork of the K-9 Mail app v6.603. I have modified the notifications delivered from this app. Now, when a new email is received, neither the contents nor the sender of the received email will be displayed in the notification. This is preferred in cases where the received email has sensitive information.

This is achieved by modifying these files:
\app\core\src\main\java\com\fsck\k9\notification\NotificationContentCreator.kt


# Original README below:
# K-9 Mail

[![Latest release](https://img.shields.io/github/release/thundernest/k-9.svg?style=flat-square)](https://github.com/thundernest/k-9/releases/latest)
[![Latest beta release](https://img.shields.io/github/v/release/thundernest/k-9.svg?include_prereleases&style=flat-square)](https://github.com/thundernest/k-9/releases)

K-9 Mail is an open-source email client for Android.

## Download

K-9 Mail can be downloaded from a couple of sources:

- [Google Play](https://play.google.com/store/apps/details?id=com.fsck.k9)
- [F-Droid](https://f-droid.org/repository/browse/?fdid=com.fsck.k9)
- [Github Releases](https://github.com/thundernest/k-9/releases)

You might also be interested in becoming a [tester](https://forum.k9mail.app/t/how-do-i-become-a-beta-tester/68) to get an early look at new versions.

## Release Notes

Check out the [Release Notes](https://github.com/thundernest/k-9/wiki/ReleaseNotes) to find out what changed
in each version of K-9 Mail.

## Need Help?

If the app is not behaving like it should, you might find these resources helpful:

- [User Manual](https://docs.k9mail.app/)
- [Frequently Asked Questions](https://forum.k9mail.app/c/faq)
- [Support Forum](https://forum.k9mail.app/)

## Translations

Interested in helping to translate K-9 Mail? Contribute here:

- [K-9 Mail localization](https://explore.transifex.com/k-9/k9mail/)

## Contributing

Thank you for contributing! If you're unfamiliar with the code, start by reading the [developer documentation](docs/DESIGN.md)

Please fork this repository and contribute back using [pull requests](https://github.com/thundernest/k-9/pulls).

Any contributions, large or small, major features, bug fixes, unit/integration tests are welcomed and appreciated
but will be thoroughly reviewed and discussed.
Please make sure you read the [Code Style Guidelines](https://github.com/thundernest/k-9/wiki/CodeStyle).

## Communication

Aside from discussing changes in [pull requests](https://github.com/thundernest/k-9/pulls) and
[issues](https://github.com/thundernest/k-9/issues) we use the following communication services:

- Matrix: [#k9mail:matrix.org](https://matrix.to/#/#tb-android:mozilla.org)
- IRC: [#k9mail on Libera Chat](https://web.libera.chat/#k9mail)
- [Developer mailing list](https://groups.google.com/forum/#!forum/k-9-dev)

## License

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
