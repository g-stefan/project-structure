# Project  structure recommendation

In order to automate some build tasks and to be able to analyze software, a basic folder structure is required and some tools for management.

#### Folder structure

```shell
.
+ .git/
+ .github/
+ .reuse/
+ .vscode/
+ build/
+ docs/
+ LICENSES/
+ output/
+ source/
+ temp/
+ vendor/
- .gitignore
- build.cmd
- build.sh
- LICENSE
- mkdocs.yml
- README.md
- version.ini
```

#### README.md

Information about the project

#### LICENSE

Project license

#### source/

Project source code

#### docs/

Project documentation

#### build/

This folder contains build scripts

#### output/

This folder contain build output

#### build.cmd, build.sh

Main entry point for build

#### temp/

Temporary objects created by the build process

#### vendor/

External project requirements, like libraries

#### version.ini

A version information file, using specification from [Semantic Versioning](https://semver.org/)

#### .git/

Is recommended that project use a version-control system, preferably [Git](https://git-scm.com/)

#### .gitignore

Folders or files to be ignored (for example build folder)

#### .vscode/

Folder used by [Visual Studio Code](https://code.visualstudio.com/), should contain basic build tasks to be used from editor

#### .github/

This folder has [GitHub](https://github.com/) recommended information and templates

#### mkdocs.yml

File with configuration for documentation build system

#### .reuse/

Folder used by [reuse software tool](https://reuse.software/), contain license and copyright specifications

#### LICENSES

Licenses used by the project, checked by [reuse software tool](https://reuse.software/)

---

The project should use the following recommendations or/and tools:

[Semantic Versioning](https://semver.org/) -  https://semver.org/

[REUSE Software](https://reuse.software/) - https://reuse.software/

[Git](https://git-scm.com/) - https://git-scm.com/

[Visual Studio Code](https://code.visualstudio.com/) - https://code.visualstudio.com/

[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - https://squidfunk.github.io/mkdocs-material/

---

MIT License

Copyright (c) 2021 Grigore Stefan <<g_stefan@yahoo.com>>

