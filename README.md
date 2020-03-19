# Linux Expect script for FTP download
This is a linux bash shell script which will download files from an ftp site by answering prompts and checking the "expected" results.  It can be easily modified to also upload files using "mput".

# Prerequisites
* Linux OS with Bash shell

# Instructions
Remember to make sure that the script has "execute" privileges.  The script takes a number of prompts:

* <b>user</b> - Username for the ftp site
* <b>password</b> - Password for the ftp site
* <b>host</b> - Hostname/IP of the ftp site
* <b>source</b> - Location where the files will be downloaded from
* <b>destination</b> - Location where the files will be downloaded to
* <b>files</b> - Name of the files to download (wildcards supported)

Usage:
```
linux_expect user@site.com password123 ftp.site.com /home/files C:\myfolder testfiles*.txt
```

# Disclaimer
No Support and No Warranty are provided by SMA Technologies for this project and related material. The use of this project's files is on your own risk.

SMA Technologies assumes no liability for damage caused by the usage of any of the files offered here via this Github repository.

# License
Copyright 2020 SMA Technologies

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Contributing
We love contributions, please read our [Contribution Guide](CONTRIBUTING.md) to get started!

# Code of Conduct
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code-of-conduct.md)
SMA Technologies has adopted the [Contributor Covenant](CODE_OF_CONDUCT.md) as its Code of Conduct, and we expect project participants to adhere to it. Please read the [full text](CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.
