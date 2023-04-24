#  MLFlow Tracking Server For Anaconda Enterprise

Overview
--------
Provides a hosted MLFlow Tracking Server meant for deployment into an Anaconda Enterprise environment.

Articles
--------

* [High Level Concepts](docs/source/high_level_concepts.md)
* [MLFlow Tracking Server Overview](docs/source/server_overview.md)
* [Installation Guide](docs/source/installation_guide.md)

Development Requirements
--------
* conda
* anaconda-project

Development Environment Setup
--------
> anaconda-project prepare --env-spec development

Anaconda Project Development Commands
--------
These commands are used during develop for solution management.

| Command          | Environment  | Description                                               |
|------------------|--------------|:----------------------------------------------------------|
| bash             | Development  | Enters a bash shell within the `development` environment. |
| test:unit        | Development  | Runs unit tests                                           |
| test:integration | Development  | Runs integration tests                                    |
| coverage         | Development  | Generates code coverage report                            |
| clean            | Development  | Cleanup temporary project files                           |
| lint             | Development  | Perform code linting check                                |
| lint:fix         | Development  | Perform automated code formatting                         |

Contributing
------------
1. Fork the repository on GitHub
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using GitHub

License and Authors
-------------------
Copyright (c) 2023 Anaconda, Inc.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

1. Redistributions of source code must retain the above copyright
notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright
notice, this list of conditions and the following disclaimer in the
documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
contributors may be used to endorse or promote products derived from
this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS
IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED
TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED
TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

