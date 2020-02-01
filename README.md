<div align="center">
    <h1>Codidact</h2>
    <h3>
        <a href="https://help.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file">
            Default Community Health Files
        </a>
    </h3>
</div>

This is the default community health files repository for Codidact projects.

## Table of Contents
1. [Why does this repository exist?](https://github.com/codidact/.github#why-does-this-repository-exist)
1. [Community Code of Conduct](https://github.com/codidact/.github#community-code-of-conduct)
1. [Contribution Guidelines](https://github.com/codidact/.github#contribution-guidelines)
1. [Security Vulnerability Disclosure Guidelines](https://github.com/codidact/.github#security-vulnerability-disclosure-guidelines)

## Why Does This Repository Exist?

As the name suggests, this repository is meant to hold the default
community health files for the Codidact organization. These default
files will be used for any public repository that does not already
contain one of these files. For example, while the Codidact Core
project has a `CONTRIBUTING.md` file, the Co-Design project does not.
With this repo, anyone who goes to open an issue or a pull request
will now see a link to the Codidact contribution guidelines, even
though the Co-Design project would normally need its own contributing
guidelines file.

We can leverage this functionality to use the repository as a single
source of truth for key project files without needed to resort to
submodules, scripts, or triggers. This is absolutely essential when
you consider that one of the files supported by this functionality
is the `SECURITY.md` file, in which we can delineate the process by
which security researchers and developers may discretely (but quickly)
report security vulnerabilities in our
[technology stack](https://github.com/codidact/docs/wiki/Technology-Stack).
We obviously cannot afford the risk of juggling different versions of
files containing critical information like that. That is why this
repository exists.

## [Community Code of Conduct](https://github.com/codidact/.github/blob/master/CODE_OF_CONDUCT.md)

The original Codidact community code of conduct may be found
[here](https://github.com/codidact/core/wiki/Codidact-Code-of-Conduct).
It has been transcribed to this repository to serve as a master
record of the official policies and procedures for interacting
with and amongst the Codidact community.

## [Contribution Guidelines](https://github.com/codidact/.github/blob/master/CONTRIBUTING.md)

The original contribution guidelines may be found
[here](https://github.com/codidact/core/blob/develop/CONTRIBUTING.md),
but unfortunately they were not as visible as would be ideal, and the
Core project is the only project where the guidelines were being
displayed when contributors opened new issues and pull requests.

For that reason, this repository will serve as the home of the official
Codidact community contribution guidelines.

## Security Vulnerability Disclosure Guidelines

Critical security vulnerabilities must be reported quickly and discretely
to ensure mitigations are put in place as expeditiously as possible while
a patch is developed upstream. We are committed to providing a clear
channel of communication to allow security researchers and developers to
report potential vulnerabilities as soon as possible.

While our current technology stack has been defined, our project is still
in its nascency, and a concrete security is thus being developed in step
with a formal organizational hierarchy.

Updates to the project security policy will be made public as soon as they
are available.

## Community

Questions regarding the Codidact contribution guidelines 
should be directed to Codidact Team Lead [ArtOfCode](https://github.com/ArtOfCode-),
Codidact Tech Lead [Marc Ranolfi](https://github.com/ranolfi), or
Documentation Lead [Monica Cellio](https://github.com/cellio).

Outright mistakes in the documentation should be blamed on
[@jflopezfernandez](https://github.com/jflopezfernandez),
who upon hearing about them will be disappointed but not
surprised, and who will make haste to correct them as
expeditiously as humanly possible.
