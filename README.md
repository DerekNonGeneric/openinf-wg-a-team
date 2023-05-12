<div align="center">

## @OpenINF/wg-a-team

Home of the Engineering Productivity <abbr title="Working Group">WG</abbr>, a.k.a. the A-Team

<br />

[!['View on npm'][npm-badge--shields]][npm-badge-url]
[!['License: MIT/Apache-2.0'][license-badge--shields]][license-badge-url]
!['Project Status: Under construction'][project-status-badge]

</div>

<br />

We are the A-Team, focused on enhancing productivity for OpenINF’s engineering
teams. Our experts develop and support tools and automation to achieve this
goal. Contact us for assistance or to share your ideas.

<br />

<div align="center">

[![Code Style: Prettier][prettier-badge]][prettier-url]
[![Commit Style: Conventional Commits][conventional-commits-badge]][conventional-commits-url]
[![Chat on Matrix][matrix-badge--shields]][matrix-url]

</div>

<br /><br />

---

<br />

### Table of Contents

- [Ahoy!](#ahoy)
- [Our Mission](#our-mission)
- [Connecting with the Team](#connecting-with-the-team)
- [A-Team Collaborators](#a-team-collaborators)
- [What We Work On](#what-we-work-on)
- [What We Do Not Work On](#what-we-do-not-work-on)
- [Meetings](#meetings)
- [Goals and Projects](#goals-and-projects)
- [Getting Involved](#getting-involved)
- [Contributing](#contributing)
- [License](#license)

<br /><br />

---

<br />

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/info.svg">
  <img alt="Info" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/info.svg">
</picture><br>

As of 2023-02-14, _the Engineering Productivity group, a.k.a. the A-Team_, is no
longer a discrete team. Its operations are split between the new Product
Integrity WG meta-team and Engineering Operations. For now, many discussions
around the test and automation work that was formerly under Engineering
Productivity may [continue in our Matrix channel][].

</section>

<br />

<section>

### Ahoy!

Welcome to the homepage of the Engineering Productivity
<abbr title="Working Group">WG</abbr> (called “the A-Team” for nostalgic
reasons). Although previously formally known as the Automation and Tools team,
we often still use the nickname “A-Team”, and you’ll see A-Team references
scattered throughout our codebases. Although we are proud to now finally be
recognized as an officially chartered WG (Working Group), we still prefer the
“A-Team” nickname from our humble beginnings. Please preserve all instances of
this esoteric usage you may find while spelunking in our codebases by leaving
them as-is and untouched.

We’re a group of programmers who develop and support a wide range of services,
tools, and automation that serve the engineering teams at OpenINF, with a
specific focus on work that increases the productivity of those teams.

We are part of the [Release & Productivity meta-team][wg-release-n-productiv-meta].

</section>

<br />

<section>

### Our Mission

The Engineering Productivity WG is a diverse group of engineers passionate about
improving engineering quality and productivity at OpenINF. We are experts in
various coding languages and tools and are always looking for new ways to make
engineering more efficient and effective. We work with others in a responsive
and agile manner, striving to be a model of open development. We create,
maintain, and extend a diverse array of sustainable tools and systems that
derive and deliver information on the quality of OpenINF’s products and enhance
the impact and effectiveness of the OpenINF community.

</section>

<br />

<section>

### Connecting with the Team

We’re a friendly bunch of people happy to help you; we want to hear about your
ideas and problems. Please let us know what you think we can do to help you work
more productively.

See our team rosters below for a list of folks on “the A-Team”&hellip;

</section>

<br />

<section>

### A-Team Collaborators

#### Persons Roster

| Name            | Organization             | Engineering Role   | GitHub Handle        |
| --------------- | ------------------------ | ------------------ | -------------------- |
| Derek Lewis     | AMPHTML, OpenINF, et al. | Development        | [@DerekNonGeneric][] |
| Milena Mitrovic | OpenINF                  | Design / UI / UX   | [@emmitrovic][]      |
| Jorge Bucaran   | OpenINF, et al.          | Quality Assurance  | [@jorgebucaran][]    |
| Sora Morimoto   | TC39, OpenINF, et al.    | Product Management | [@smorimoto][]       |

#### AI Non-Persons Roster

| Name    | Organization | Engineering Role     |
| ------- | ------------ | -------------------- |
| Bard    | Google AI    | Large Language Model |
| ChatGPT | OpenAI       | Large Language Model |
| Claude  | Anthropic    | Large Language Model |

</section>

<br />

<section>

### What We Work On

We work on various things that will vary from quarter to quarter, but the lists
below represent the general scope of our activities.

#### Services

- Autoland
- Treeherder/Perfherder
- TestInformant

#### Automation

- [web-platform-tests][]
- CI integration ([openinfbot][]/[Taskcluster][]),
- JS specification ([TC39 AssertionError
  Proposal][tc39-proposal-assertion-error])
- new test harnesses as needed

#### Tools

- [mach][]
- GitHub Actions
- code coverage

</section>

<br />

<section>

### What We Do Not Work On

We don’t own [asbuild][], [Taskcluster][], or [depot_tools][] (those belong to
our Release Engineering team, the Mozilla Taskcluster team, and a few select
owners in the Chromium project, respectively). However, we occasionally help
with those projects as well.

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/tip.svg">
  <img alt="Tip" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/tip.svg">
</picture><br>
    
We don’t write unit tests run in the test harnesses we own;
developers are best suited for &mdash; and responsible &mdash; for that.

We generally don’t write functional tests run in the harnesses we own. However,
we may help here occasionally, mainly when this is done in conjunction with
developing a new harness. Our interests here are empowering developers to write
tests independently, but we sometimes contribute tests here as part of the
bootstrapping process. As with unit tests, developers are best suited to writing
functional tests as they understand overall test coverage and design.

</section>

<br />

<section>

### Meetings

We have a fortnightly meeting every other Tuesday at noon US Pacific Time. We
typically discuss status, and new projects, have demonstrations of the latest
tools & features, and sometimes even engage in bikeshedding. All are welcome;
please join us!

<details>

<summary><h4>Planning for Past &amp; Future Events</h4></summary>

#### Dates &amp; Times

| Date       | Day of Week | Time         |
| ---------- | ----------- | ------------ |
| 2023-02-14 | Tuesday     | 12:00 PM PDT |
| 2023-02-28 | Tuesday     | 12:00 PM PDT |
| 2023-03-07 | Tuesday     | 12:00 PM PDT |
| 2023-03-21 | Tuesday     | 12:00 PM PDT |
| 2023-03-28 | Tuesday     | 12:00 PM PDT |
| 2023-04-04 | Tuesday     | 12:00 PM PDT |
| 2023-04-18 | Tuesday     | 12:00 PM PDT |
| 2023-05-02 | Tuesday     | 12:00 PM PDT |
| 2023-05-16 | Tuesday     | 12:00 PM PDT |
| 2023-05-30 | Tuesday     | 12:00 PM PDT |
| 2023-06-13 | Tuesday     | 12:00 PM PDT |
| 2023-06-27 | Tuesday     | 12:00 PM PDT |
| 2023-07-11 | Tuesday     | 12:00 PM PDT |
| 2023-07-25 | Tuesday     | 12:00 PM PDT |
| 2023-08-08 | Tuesday     | 12:00 PM PDT |
| 2023-08-22 | Tuesday     | 12:00 PM PDT |
| 2023-09-05 | Tuesday     | 12:00 PM PDT |
| 2023-09-19 | Tuesday     | 12:00 PM PDT |
| 2023-10-03 | Tuesday     | 12:00 PM PDT |
| 2023-10-17 | Tuesday     | 12:00 PM PDT |
| 2023-11-07 | Tuesday     | 12:00 PM PDT |
| 2023-11-21 | Tuesday     | 12:00 PM PDT |
| 2023-12-05 | Tuesday     | 12:00 PM PDT |
| 2023-12-19 | Tuesday     | 12:00 PM PDT |

</details>

</section>

<br />

<section>

### Goals and Projects

We set and deliver quarterly goals, which is usually an excellent place to see
what we’re up to. If you’d like us to incorporate some work into our plans, fill
out our project request form.

For a list of projects we own, see the [Project Central wiki page][].

</section>

<br />

<section>

### Getting Involved

We love contributors! We see community members as one of the keys to our success
and actively encourage their contributions. Working on the tooling, automation,
testing, and build systems at OpenINF is a fantastic introduction to OpenINF
development. There are two great ways to help: joining an existing project or
taking on one of our _starter_ projects to help rev up to speed.

<dl>

<dt>

[Quarter of Contribution][]

</dt>

<dd>

Longer-running, scoped contributing opportunities with definite goals, mentors,
and timelines

</dd>

<dt>

[Existing Projects][]

</dt>

<dd>

Look over our list and see if there is anything that you’d like to help with

</dd>

</dl>

If you have questions or want to sign up, please find us on Matrix or Twitter.

</section>

<br /><br />

---

<br />

### Contributing

Pull requests are welcome. For major changes, please open an issue first to
discuss what you would like to change. If for whatever reason you spot something
to fix but cannot patch it yourself, please [open an issue][].

<br />

### License

This project is licensed under either of

- [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
- [MIT license](https://opensource.org/licenses/MIT)

at your option.

The [SPDX](https://spdx.dev) license identifier for this project is
`MIT OR Apache-2.0`.

<br /><br />

---

<br />

<div align="center">

### Show Your Support

<br />

If you like the project (or want to bookmark it)&nbsp;&mdash;<br />
&mdash;&nbsp;[give it a star ⭐️][]&nbsp;&mdash;&nbsp;it will greatly encourage
us.

<br /><br />

<a title="The OpenINF website" href="https://open.inf.is" rel="author">
  <img alt="The OpenINF logo" height="32px" width="32px" src="https://raw.githubusercontent.com/openinf/openinf.github.io/live/assets/img/svg/logo.svg?sanitize=true" />
</a>

</div>

<br /><br />

<!-- BEGIN LINK DEFINITIONS -->

[**@OpenINF**]: https://github.com/OpenINF
[@DerekNonGeneric]: https://github.com/DerekNonGeneric 'GitHub profile of Derek Lewis'
[@emmitrovic]: https://github.com/emmitrovic 'GitHub profile of Milena Mitrovic'
[@jorgebucaran]: https://github.com/jorgebucaran 'GitHub profile of Jorge Bucaran'
[@smorimoto]: https://github.com/smorimoto 'GitHub profile of Sora Morimoto'

<!-- 3P Tools -->

[asbuild]: https://github.com/OpenINF/openinf-asbuild
[depot_tools]: https://commondatastorage.googleapis.com/chrome-infra-docs/flat/depot_tools/docs/html/depot_tools.html
[mach]: https://firefox-source-docs.mozilla.org/mach/index.html
[openinfbot]: https://github.com/OpenINF/openinfbot
[Taskcluster]: https://taskcluster.net
[web-platform-tests]:
  https://firefox-source-docs.mozilla.org/web-platform/index.html

<!-- Misc. doc links -->

[`openinf-auto-tooling` mailing list]:
  https://groups.google.com/g/openinf-auto-tooling
[tc39-proposal-assertion-error]:
  https://github.com/DerekNonGeneric/proposal-assertion-error
[`AssertionError` Proposal]: https://github.com/DerekNonGeneric/proposal-assertion-error
[i-gfi]:
  https://github.com/search?q=org%3Aopeninf+is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
[i-help]:
  https://github.com/search?q=org%3Aopeninf+is%3Aissue+is%3Aopen+label%3A%22help+wanted%22
[`openinf-auto-tooling` mailing list]: https://groups.google.com/g/openinf-auto-tooling
[Project Central wiki page]: https://github.com/OpenINF/wg-a-team/wiki/Project-Central
[projects]: https://github.com/OpenINF/wg-a-team/wiki/Project-Central
[pr-help]:
  https://github.com/search?q=org%3Aopeninf+is%3Apr+is%3Aopen+label%3A%22help+wanted%22
[Existing Projects]: https://github.com/OpenINF/wg-a-team/wiki/Project-Central
[Project Central wiki page]:
  https://github.com/OpenINF/wg-a-team/wiki/Project-Central
[Quarter of Contribution]:
  https://github.com/OpenINF/wg-a-team/wiki/Auto-Tooling#quarter
[wg-release-n-productiv-meta]: https://github.com/OpenINF/wg-release-n-productiv-meta
[Release Engineering team]: https://github.com/OpenINF/wg-release-engineering
[Release and Productivity meta-team]: https://github.com/OpenINF/wg-release-n-productiv-meta
[Release Engineering team]: https://github.com/OpenINF/wg-release-engineering
[skills and areas]:
  https://github.com/OpenINF/wg-a-team/wiki/Auto-Tooling#skills-and-areas

<!-- Readme template links -->

[continue in our Matrix channel]: https://view.matrix.org/room/!JmqxeUehJySSTeTxsq:mozilla.org
[conventional-commits-badge]:
  https://img.shields.io/badge/commit%20style-Conventional-%23fa6673?logoColor=white&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzMCAzMCI+PHBhdGggc3R5bGU9ImZpbGw6ICNGRkYiIGQ9Ik0xNSwyQTEzLDEzLDAsMSwxLDIsMTUsMTMsMTMsMCwwLDEsMTUsMm0wLTJBMTUsMTUsMCwxLDAsMzAsMTUsMTUsMTUsMCwwLDAsMTUsMFoiLz48L3N2Zz4K
  'Commit Style: Conventional Commits'
[conventional-commits-url]:
  https://www.conventionalcommits.org
  'Commit Style: Conventional Commits'
[give it a star ⭐️]: https://github.com/OpenINF/wg-a-team/stargazers
[license-badge--shields]:
  https://img.shields.io/badge/license-MIT%2FApache--2.0-blue.svg?logo=github
  'License: MIT/Apache 2.0'
[license-badge-url]: #license 'License: MIT/Apache 2.0'
[matrix-badge--shields]:
  https://badgen.net/matrix/members/openinf-space/mozilla.org
  'Chat on Matrix'
[matrix-url]:
  https://matrix.to/#/#openinf-space:matrix.org
  "You're invited to talk on Matrix"
[npm-badge--shields]:
  https://img.shields.io/badge/packages-6-2a2a2a.svg?logo=npm
  'View our packages on npm'
[npm-badge-url]:
  https://www.npmjs.com/org/openinf
  "View all of OpenINF's packages published to the npm registry"
[open an issue]: https://github.com/OpenINF/wg-a-team/issues
[prettier-badge]:
  https://img.shields.io/badge/code_style-Prettier-ff69b4.svg?logo=prettier
  'Code Style: Prettier'
[prettier-url]: https://prettier.io/playground 'Code Style: Prettier'
[project-status-badge]: https://img.shields.io/badge/project%20status-under%20construction-orange 'Project Status: Under construction badge'

<!-- END LINK DEFINITIONS -->
