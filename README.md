# Project structure recommendation

In order to automate some build tasks and to be able to analyze software, a basic folder structure is required and some tools for management.

#### Folder structure

``` shell
.
+ .git/
+ .github/
+ .reuse/
+ .vscode/
+ archive/
+ build/
+ docs/
+ input/
+ installer/
+ LICENSES/
+ output/
+ release/
+ source/
+ temp/
+ test/
+ vendor/
- .gitignore
- build.cmd
- build.sh
- LICENSE
- mkdocs.yml
- README.md
- version.ini
```

#### .git/

Is recommended that project use a version-control system, preferably [Git](https://git-scm.com/)

#### .github/

This folder has [GitHub](https://github.com/) recommended information and templates

#### .reuse/

Folder used by [reuse software tool](https://reuse.software/), contain license and copyright specifications

#### .vscode/

Folder used by [Visual Studio Code](https://code.visualstudio.com/), should contain basic build tasks to be used from editor

#### archive/

Contains archives of source at different versions

#### build/

This folder contains build scripts

#### docs/

Project documentation

#### input/

Project input data or source code

#### installer/

Project generated installers

#### LICENSES

Licenses used by the project, checked by [reuse software tool](https://reuse.software/)

#### output/

This folder contain build output

#### release/

Project release

#### source/

Project source code

#### temp/

Temporary objects created by the build process

#### test/

Scripts/utilities/source used for test

#### vendor/

External project requirements, like libraries

#### .gitignore

Folders or files to be ignored (for example temp folder)

#### build.cmd, build.sh

Main entry point for build

#### LICENSE

Project license

#### mkdocs.yml

File with configuration for documentation build system

#### README.md

Information about the project

#### version.ini

A version information file, using specification from [Semantic Versioning](https://semver.org/)

- - -

The project should use the following recommendations or/and tools:

[Semantic Versioning](https://semver.org/) \- https://semver.org/

[REUSE Software](https://reuse.software/) \- https://reuse.software/

[Git](https://git-scm.com/) \- https://git-scm.com/

[Visual Studio Code](https://code.visualstudio.com/) \- https://code.visualstudio.com/

[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) \- https://squidfunk.github.io/mkdocs-material/

- - -

MIT License

Copyright (c) 2021-2022 Grigore Stefan <[g\_stefan@yahoo.com](mailto:g_stefan@yahoo.com)>
