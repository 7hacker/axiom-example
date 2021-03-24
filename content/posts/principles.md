+++
date = 2021-03-23T17:00:00Z
lastmod = 2021-03-23T17:00:00Z
author = "7hacker"
title = "Guiding Principles"
subtitle = "The guiding principles at Signet Blocks."
toc = true
+++

## Motivation

Signet Blocks exists to contribute & improve open source software & systems in the bitcoin & lightning network ecosystem, by reporting issues found while testing with signet.

To achieve that effectively, Signet Blocks aims to adhere to the following guiding principles in its day-to-day operations and activities.

## Scope

### Open Source only

Work only with open source projects.

### Bitcoin only

Work only on bitcoin (and lightning network) open source projects.

### Focus on user-flows and interface integrations

There's many kinds of exciting tests one can dig into, such as memory profiling, stress & torture tests, symbolic execution tests etc. However Signet Blocks prioritizes the following kinds of tests, first & foremost:

1. User flows that run through the set of features offered by the software.

2. Interfaces that exist between other software / libraries where implementation details can vary.


### Leverage signet

Leverage bitcoin signet to generate unique and predictable network conditions in a safe & sandboxed environment. [Learn more about signet here](/signet-101).

## Reporting

### Top of tree & build from source

Rather than choose to test with specific feature branches or release branches, Signet Blocks will aim to:

1. Use "top of tree" or the "master" branch that represents the bleeding edge changes in the software.

2. Prioritize building from source directly.

### Replicable steps, logs, screenshots

Signet Blocks strives to provide developers with sufficient data to assist in quick resolution of Issues that are found:

1. Enumerated scenario & steps that lead to the Issue reported

2. If the software can run in debug mode, debug logs may be attached

3. Screenshots of UI/UX wherever required

### Follow up and verification

In the process of Issue resolution, Signet Blocks can accept patches to verify or recreate the issue.

## Communication

### Dev's get first call

Developers will always be notified first and at their projects Github/Gitlab or public repository's Issue page or mailing list.

### High security issues

While our focus is not on high security issues, if we do stumble upon them, we will aim to directly reach out in private over Twitter/Email or similar.

### Spreadsheet, Twitter & Blogs

Signet Blocks will lastly share its progress on <a href="https://twitter.com/_7hacker_/" target="_blank">Twitter</a> or blog any interesting findings. The purpose will be to share progress & improvements in the space. We do not aim to negatively increase visibility of Issues found, more than what's already reported on the repository.  

We also maintain a spreadsheet that enumerates the issues found and can be found <a href="https://docs.google.com/spreadsheets/d/1l2OeWwU2Nb1o8dGUvyS9biP2Z0quEWPqrnWNKEcGEbo/edit?usp=sharing" target="_blank">here.</a>

Entries in the spreadsheet will be added only after an action has been performed on the reported Issue by the owners/developers of the software repository. This could be an acknowledgement/comment, label/tag assignment, resolution, check-in addressing the issue, etc. 

Spreadsheet entries will not be created for unacknowledged issues or issues that are closed immediately upon reporting. Spreadsheet entries will not be created before Issue create date.

## Contributing Back

### Automation & Test rigs

The focus is on testing and reporting however any automation / software developed by Signet Blocks will also be open sourced.

### Blogging and sharing

We will occasionally blog about interesting issues that we find in the context of their resolution, or how to effectively use signet for finding issues or other orthogonal technical articles on bitcoin and lightning network.

## Contact us

[Our contact page](/contact).

