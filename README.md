npm-install-missing
===================

An NPM module to reinstall missing dependencies.

[![Build Status](https://travis-ci.org/AlexCline/npm-install-missing.png?branch=master)](https://travis-ci.org/AlexCline/npm-install-missing)


Installation
------------
To be able to use this tool system-wide to install missing dependencies for all your node projects, install it globally.

    npm install -g npm-install-missing


Usage
-----
Within your project directory:

    npm-install-missing
    
The script will check the current project directory for missing dependencies and install them automatically.


Dependencies
------------
This module depends on the following modules:

* async
* npm


Testing
-------
To install the devDependencies and run the test framework:

    cd npm-install-missing
    npm install
    npm test


Support
-------
Please file tickets and issues using [GitHub Issues](https://github.com/AlexCline/npm-install-missing/issues)


License
-------
Copyright 2013 Alex Cline alex.cline@gmail.com

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
