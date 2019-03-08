<a id="markdown-template-travis" name="template-travis"></a>
# template-travis - Standard Travis file template for Atlassian Security

<https://github.com/asecurityteam/template-travis>

- [template-travis - Standard Travis file template for Atlassian Security](#template-travis)
    - [Overview](#overview)
    - [Quick Start](#quick-start)
    - [Configuration](#configuration)
    - [Status](#status)
    - [Contributing](#contributing)
        - [Building And Testing](#building-and-testing)
        - [Quality Gates](#quality-gates)
        - [License](#license)
        - [Contributing Agreement](#contributing-agreement)

<!-- /TOC -->

<a id="markdown-overview" name="overview"></a>
## Overview<!-- TOC -->

This project contains our standard .travis.yml file that we include with all
Go project. It leverages our standard repository Makefile and reports coverage
to CodeCov.

<a id="markdown-quick-start" name="quick-start"></a>
## Quick Start

Using our SDCLI helper:

```sh
sdcli repo go add-travis
```

Using cookiecutter (our template engine) directly:

```sh
pip install cookiecutter
cookicutter gh:asecurityteam/template-go-travis
```

<a id="markdown-status" name="status"></a>
## Status

This project is in incubation which means we are not yet operating this tool in production
and the interfaces are subject to change.

<a id="markdown-contributing" name="contributing"></a>
## Contributing

<a id="markdown-license" name="license"></a>
### License

This project is licensed under Apache 2.0. See LICENSE.txt for details.

<a id="markdown-contributing-agreement" name="contributing-agreement"></a>
### Contributing Agreement

Atlassian requires signing a contributor's agreement before we can accept a
patch. If you are an individual you can fill out the
[individual CLA](https://na2.docusign.net/Member/PowerFormSigning.aspx?PowerFormId=3f94fbdc-2fbe-46ac-b14c-5d152700ae5d).
If you are contributing on behalf of your company then please fill out the
[corporate CLA](https://na2.docusign.net/Member/PowerFormSigning.aspx?PowerFormId=e1c17c66-ca4d-4aab-a953-2c231af4a20b).
