# New Project Template

This repository contains a template you can use to document a repository for a new open source project.

See at <https://www.eurecat.org/docs/releasing> for more information about releasing a new Eurecat open source project.

## Pusblishing steps

First ask your unit director whether the code in this project is susceptible for open source publishing.

If the code is a modification of an existing code already GPL or CC NC-ND-SA, or simply a snippet, then it can be directly uploaded to <https://github.com/eurecat>. Apply for it to the account administrator(s). Afterwards the pushes to that repository are freely granted for the developer. For repositories already existent, access request should be similarly required. 

Otherwise, the code still valid for open source has to apply for publishing to an internal committee X.	
MIT and Apache 2.0 licenses will be favoured.


## How to use this template

1. Check it out from GitHub (no need to fork it).
2. Copy these files to your repository folder.
3. Populate the copied README file with the correspoding [project info](#name-of-the-project).
4. Do not forget to delete this and other sections non-relevant for the project itself : ).
4. Modify the CONTRIBUTING file according to the project requirements or remove it for no 3rd-party contributions ahead.
5. Keep on coding! and documenting!


## General guidelines

- Use a descriptive name that makes others easily understand what the project is about.
- Use english as unique language for coding and documenting.
- Document the code and this readme often.


## Style guidelines

Currently there are no programming style guidelines regarding variable naming, indentatins, vertical aligment,... etc.	
In general follow the style already formatting the project and do your best.	
May be interesting to have a look to [programming style](https://en.wikipedia.org/wiki/Programming_style) or [naming convention](https://en.wikipedia.org/wiki/Naming_convention_\(programming\)).


# Project screening

Remove names, email address, IP addresses and in general sensible information including internal paths or filenames, unless explicit permission for that.

You may find useful this command:

```shell
egrep -r '\.eurecat\.com|@eurecat\.com|eurecat?/|([0-9]+\.){3}[0-9]+' <path-to-source-directory>
```


## Source Code Headers

EVERY file containing source code must include copyright and license information.

Apache header:

    Copyright 2018 Eurecat LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

See the documentation for instructions on using alternate license.	
You may find useful this [autogen](https://github.com/mbrukman/autogen) tool to generate license headers including some sample outputs. 


-------------------------------------------------

## Readme Contents

Populate this README file with the following sections.	
Remember to write `#` instead of `###` for every section ; )

### Name of the Project

- Use a descriptive name that makes others easily understand what the project is about.
- Add a brief descriptions in one sentence.
- Add bellow a more detailed description of what the project does.


### Dependencies

If the software uses 3rd-party dependencies please make a list of it.

- OpenCV 3.3.1
- CMake 3.2
- ...


### Contributors

List the name of all contributors and keep it updated.

- Franz Kafka.
- Goethe.
- Ptolomeus.


### Publications

Include a list of related publications if needed. Otherwise remove this section.


### Changelog

If the project requires versioning, maybe convinient to add changes after every release.


-----------------------

Eurecat (c) 2018 All rights reserved.