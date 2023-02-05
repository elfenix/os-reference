
# What is this?

This is a collection of low level operating system implementations. By
"operating system implementation" - I'm focusing mostly on the OS kernel
itself, but this collection does include other software elements critical to
the user concept of an operating system.

# How to use?

Simply clone this repository recursively with submodules. Be warned,
this will eat up a _LOT_ of hard drive space and network traffic. You
can mitigate this by either doing a shallow recursive clone or by cloning
only the repositories you find interesting. I maintain a full clone on
my local disk, and it does eat up some fairly substantial space.

Please be kind to hosting providers (especially github) - and avoid 
repeated recursive clones of this repo.

Recommended Clone Command:
   `git clone --recurse-submodules --shallow-submodules https://github.com/elfenix/os-reference`

Give it some time.

# Why do this?

Over the years, I've written multiple Hobby Operating Systems. Largely out
of curiosity for how various paradigms might "work". Sometimes out of egotism
that I alone could make "the next big thing". I find tracking other projects
similar in nature to be interesting.

For a really extended time, my ability to work on OSS has been severely
curtailed by employment agreements limiting what all I could do online. This
has largely meant 0 allowance for OS development unless my submissions were
done at the dayjob and released back for licensing reasons. Now that I
_can_ consider doing this sort of hobby work openly, I wanted to survey
how the landscape has changed.

# You a-hole my project isn't not included!

Send me a pull request or enter a bug report.

This list intentionally omits Linux-based operating systems. Largely,
that's because there are a LOT and their is only moderate substantive
variation from an OS design standpoint. I do include the Linux kernel
here for completeness. Also, it's worth mentioning that the Linux kernel
does allow dramatically different operation from a user or even system
design perspective. But, projects accomplishing that goal tend to do
so via radically different configuration of the same source all major
distributions are using in the first place.

I included my favorite 2 BSD variants. Apologies, but there are
(again) too many of these that are too similar for this project.

In general, projects that I perceived as 'dead' or that hadn't hit a
minimal level of 'OS-ness' were excluded. If your project doesn't boot
in a VM and provide some minimal level of UI, it likely wasn't added.
If your project hasn't had a commit within the past year and wasn't
widely known in the hobbyist community, it likely wasn't added.

This repository intentionally avoids legally restricted projects that
might be especially problematic for copyright reasons. The exception
is implementations of historic interest (such as Microsoft's released
MS-DOS) source.

As this repository uses Git Submodules, projects without a git mirror
were excluded for technical limitations. Some projects, I sought out
mirrors (9front). There are some projects I'm considering mirror on
github, and many that I can't for legal reasons.

# You a-hole my project is in the 'hobby' not mainstream directory!

I tried my best to categorize operating systems for casual users. In
general, 'mainstream' repos are intended to reflect operating systems major
enough to have paid users / developers / general developer knowledge. These
categories are definitely fuzzy, and no judgement is intended on technical
merit.

# So, does this exist for people to copy paste code?

Code repositories linked all have open enough licensing that the project
can be legally downloaded. However, pretty much everything here requires
at least attribution. Porting newlib / BSD code into a new kernel is
a really solid way to concentrate on the portions of development that
one finds interesting, and - most of these kernels have very open 
licensing that just requires you copy/paste a disclaimer and copyright
notice. If you want to utilize code from these projects, make sure
you follow license for that project.

Note that this repository does include projects using GPLv3 and restricted
non-free licenses. It is _*your*_ responsibility to follow licenses
as appropriate!

# Any future plans for this repository?

Most submodules right now are using uncurated versions. I'd like to
go through and make sure releases are tied to snapshots that
developers intended to be utilized. I did go through and update
these manually before the initial push. I hope to try to keep
these projects updated as development on them continues.

