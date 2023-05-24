<!--
    A styling & format guide for release notes.
    Copyright (C) 2023  Dishant B. (@dishb) <code.dishb@gmail.com> and
    contributors.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
-->

<div align = 'center'>
    <h1> release-notes </h1>
    A styling &amp; format guide for release notes.
</div>

## Format:

📦 \<name\> - \<version\>

Example: `📦 release-notes - v1.2.3`

## Titles:

Titles should include an emoji, the repository/project name, dash (-) as a separator, and then the version. For the version number, follow the guidelines of Semantic Versioning. More information on Semantic Versioning can be found on the [official website](https://semver.org). The summary gives a quick and basic overview of the system.

## Tags:
Tags should always be the version number of the release. They too, should follow Semantic Versioning.

## Content:
At the top of the release notes should be a summary of why this release was made. This would include things like new features, why the features were added, or if any bugs were fixed. An optional piece would be a list every new commit (by commit name/ID) since the last release and the commits' titles. Under that should be a list of features the project currently has. This should include every feature, even old ones that have existed since previous releases. There should be a list of all the contributors of the project. At the bottom should be a section that states the project's license and where it can be found in the project or online.

## Examples:
An example/template file can be found in `./TEMPLATE.md`.

## Emojis:

- 📦 (package) : releases
