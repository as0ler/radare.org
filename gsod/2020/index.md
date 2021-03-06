# Introduction

The [radare](http://rada.re/) project started in February 2006 aiming to provide a free and simple command line interface for a hexadecimal editor supporting 64-bit offsets to search within and recover data from hard-disks.
Since then, the project has grown with the new aim of providing a complete framework for analyzing binaries with some basic \*NIX concepts in mind like everything is a file, small programs that interact together using stdin/out, and keep it simple.
[Radare2](https://github.com/radareorg/radare2) is a complete [LGPL]( https://opensource.org/licenses/lgpl-license ) rewrite of the original project to remove design issues of the first iteration, and to make it more modular and easier to script and maintain. Radare2 features a test suite that aims to cover as many cases as possible in order to catch regressions.

Radare2 is composed of a hexadecimal editor as central point, with several assemblers/disassemblers, code analysis capabilities, scripting features, visualization of code and data through graphs and other means, a visual mode, easy Unix integration, a diff engine, a shellcode compiler, and much more.

This year Radare2 project applied for participation in [Google Season of Docs](https://developers.google.com/season-of-docs), the program aiming to bring technical writers closer to the open source community, to raise the quality of documentation for the corresponding projects. For years
we maintain the reference manual - [radare2 book](https://radare.gitbooks.io/radare2book/content).
But as it is often the case, the writing is done by developers themselves, thus of substandard
quality and hard to read. We hope participation in GSoC will help our users for a better understanding
of the framework and grasp the vast feature set provided by the toolkit.

![graph](http://radare.org/img/radare2_graph.jpg)

If you have questions or comments, visit our IRC channel #radare on Freenode.

# Schedule

- June 9 - Begin applications
- July 9 - End of application acceptance
- August 16 - Announce the selected technical writer projects
- August 17 - Community bonding
- September 14 - Documentation development begins!
- November 30 - December 3 - Evaluation period
- January 6, 2021 - Results announcement

# Mentors

Members of the radare2 core team have volunteered to guide technical writers for GSoD’19. They were already guiding the students for GSoC'18 - GSoC’15, RSoC'16, RSoC’15 and RSoC’14. Please feel free to reach out to any of them in case you need any help in selecting a project.

- Sergi Alvarez IRC: pancake -- [@trufae](https://twitter.com/trufae)
- Anton Kochkov IRC: xvilka -- [@akochkov](https://twitter.com/akochkov)
- Maxime Morin tg: @Maijin -- [@Maijin212](https://twitter.com/Maijin212)
- Itay Cohen tg: @Megabeets [@Megabeets\_](https://twitter.com/Megabeets_)

# Development methodology

Radare2 is very portable framework and toolkit in C, thus it is very easy to setup a local copy.
Currently, all repositories are hosted on GitHub [main](https://github.com/radareorg/) organization account, bugs are tracked on GitHub [issues](https://github.com/radareorg/radare2/issues) too. We are mostly using [HackMD](https://hackmd.io), IRC, and Telegram ([telegraph#radare](https://t.me/radare)) for communication.
We have a [testsuite](https://github.com/radareorg/radare2/tree/master/test) (that is running on [Travis CI](https://travis-ci.com/radareorg/radare2/), [AppVeyor](https://ci.appveyor.com/project/radareorg/radare2), and [SourceHut](https://sr.ht)) to test and verify that all the features are still working and that a pull requests or commits don't break anything, and to find regressions.
We believe some test cases can inspire for writing documentation.

Radare2 book itself is written using Markdown and compiled using
[GitBook](https://www.gitbook.com). It targets both eBook and printed version formats.
For those who want to get introduced to the radare2 book, we recommend picking one of the [easy](https://github.com/radareorg/radare2book/labels/good%20first%20issue) issues to start with.

# License

Radare2 book is distributed and developed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) license. Radare2 itself is under [LGPL3](https://www.gnu.org/licenses/lgpl.html).

## Required experience

Most of the radare2 workflow happens in the command line. And the target domain is software reverse engineering. So some experience with UNIX-like command line is expected. And basic knowledge about the process of software debugging can be helpful as well.

## Recommended steps

1. Read [Google's instructions](https://developers.google.com/season-of-docs/docs/tech-writer-guide) for participating
2. Grab any of the projects from [list of ideas](https://radare.org/gsod/2020/ideas.html)  that you're interested in (or propose your own).
3. Write your application and submit it using Google's web interface.

## Application proposal guidelines

1. Try to split GSoD period into tasks, and each task into subtasks. It helps us to understand how you plan to accomplish your goals, but more importantly, it'll help you to understand the task deep enough before starting and prioritize important things to do first.
2. Please, note, how much time a day/week you are able to spend on this project.
3. Specify your timezone, since so we can assign you a mentor in the same one, to ease communication.
4. Submit your proposal early, not the last minute!
