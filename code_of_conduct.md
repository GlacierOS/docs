# GlacierOS Code Of Conduct

### Clause 0 - The Community Build Act
#

| __Act 1__: Link shorteners that leads to advertisement are not allowed.

>__Act 1__.2: However, it is allowed to request for donation for the hard work.

| __Act 2__: Do not publish a community build if there is already an active maintainer for the particular device.

>__Act 2__.2: The act above could be overruled by the maintainer.
>
>In addition, a community build maintainer can be appointed to maintain on the occasion that the official maintainer cannot publish a build for that particular month.
---
### Clause 1 - The Community Well-Being Act
#

| __Act 1__: Maintainer must maintain a good reputation with the community.

| __Act 2__: Maintainer must not act disrespectful toward others.

| __Act 3__: Maintainer must maintain a good reputation with the other maintainers.

---
### Clause 2 - The Build Act
#
| __Act 1__: Maintainer must not modify ROM sources in any way when releasing builds as OFFICIAL. If caught doing so, maintainership will be revoked without warning.

>__Act 1.2__: Maintainer can modify ROM source if allowed to.
>
>[By this term it mostly mean modify source to support the device and not with the purpose to add features to the ROM source]

| __Act 2__: Maintainer device's tree must not have any changes that interfere with features directly.

| __Act 3__: Kernel that is provided with the ROM must be opensource as per GPLv3 requirement.

| __Act 4__: Maintainers are not allowed to block anything from working in their build

---
### Clause 3 - The Release Act
#
| __Act 1__: Maintainer must upload their build, and wait for it to be mirrored before making a pull request or releasing the build.

| __Act 1.2__: If the maintainer released a build with RC, Beta, or Alpha tag, the maintainer will be allowed to use Google Drive for publishment but will not be pushed to OTA system.

| __Act 1.3__: Maintainer can only upload flashable "ROM.zip" or fastboot ROM into the project's SourceForge and is not allowed to upload anything other than that.

| __Act 2__: Maintainer reserves rights to pull-back the builds in any case.

| __Act 3__: Maintainer must test their build before releasing, if found untested then the maintainer will be warned, and on the second offend, the right to maintainship will be revoked.

| __Act 4__: Maintainer must follow the following format whenever the maintainer pull request to the [official_devices](https://github.com/GlacierOS/official_devices) repo.

```Device_Codename: Month/Day/Year Update```

| __Act 5__: Maintainer must make sure their changelogs is appropriate to everyone.

---
### Clause 4 - The Trees Act
#
| __Act 1__: Maintainer's device(s) trees must be in the device organization

>__Act 1.2__: Act 1 is amendable if the maintainer decides to provide the tree source to the project members to scan.

| __Act 2__: Maintainers must keep the authorship of commits, force-pushes are acceptable.

| __Act 3__: Maintainers must do the command down below in/against their build environment whenever building OFFICIAL so the build will ship OTA Updater, GApps and will be releaseable.

`export EVO_BUILD_TYPE=OFFICIAL - in the scripts`

`EVO_BUILD_TYPE := OFFICIAL - in the Makefile` [Not recommended]

| __Act 4__: Please make sure that the device tree does not contain any copyrighted blobs [Example : megvii]

---
### Clause 5 - The Languages Act
#
| __Act 1__: Maintainer's English skill must be understandable.

| __Act 2__: Maintainer's main language when talking to users shall be in English.

---
### Clause 6 - The Group Act
#
| __Act 1__: Maintainer is strictly prohibited from forwarding any messages from the Maintainer Group without the message(s)'s sender consent.

---
### Clause 7 - The Rights Act
#
| __Act 1__: Maintainer reserves rights to be treated like a human being.

| __Act 2__: Maintainer reserves rights to vote, and give opinions.

| __Act 3__: Maintainer reserves rights to leave the project on their own reasons.

| __Act 4__: Maintainer reserves rights to be become Federation Administrator after 3 months of being a good maintainer.

---
### Clause 8 - The Device Group Act
#
| __Act 1__: Maintainer is allowed to make their own device group using the format EvolutionX{codename} OR other applicable formats endorsed by the project. Be aware that community maintainer cannot use this format.

| __Act 2__: Maintainer's device group must use Sophie Bot as the group's only group management bot for utility purposes.

>__Act 2.2__: Sophie bot MUST be connected to our federation

| __Act 3__: Device group MUST NOT be used with other ROMs and should not represent maintainer's personal project or used for any personal interests.

| __Act 4__: Administrators of the group must not be one of the project's blocklisted individual.

| __Act 5__: Maintainers can add additional bots in their group as long as it does not conflict with any clauses and acts of this CoC and is deemed appropriate.

| __Act 6__: Promotion of other ROMs in the device group is strictly prohibited.

| __Act 7__: No piracy, no encouraging illegal behaviors, and such in the device group.

---
### Clause 9 - The Federation Act
#
| __Act 1__: Maintainer must not fedban anyone without a proper reason and evidences.

| __Act 2__: Maintainer must not fedban anyone due to a personal fights.

| __Act 3__: Maintainer will be revoked fedban access if they are found violating the above acts.

---
### Clause 10 - The Upload Act
#
| __Act 1__: Maintainer must not abuse the project's SourceForge by deleting files, etc. If found maintainer access will be revoked without warning.

| __Act 2__: Maintainer must not upload any other files apart from ROM.zip to project's SourceForge. If found maintainer access will be revoked without warning.

| __Act 3__: Maintainer must wait for SourceForge to mirror their build before Pull Requesting.

---
### Clause 11 - The Media Act
#
| __Act 1__: You are not allowed to "short ads" or "pling" our builds link, but you're allowed to monetize your content.

---

The project have full rights to revoke the maintainer's maintainship if you violated any of these clauses and acts.

The project reserves rights to change Code Of Conduct any times, it's the maintainer's responsibility to check the CoC themselves.

By being the project's maintainer, you have agreed to the following clauses and acts.

See anything wrong? Have a question regarding our CoC? Please create an issue in this repo.