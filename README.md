# rot-13

### master readme

### Overview
You will be implementing a version of ROT13 https://en.wikipedia.org/wiki/ROT13.

This version will allow a dynamic rotation. 13 is the default value, but the caller can use any integer > 0 for n.

### CLI
This will be a terminal-based or CLI application.

### Languages
- Javascript
- Java

### Instructions
You can choose to implement your app in any one of the langauges mentioned above. Each language has its own subdirectory.
Just `cd` into your language of choice and begin. Each langauge subdirectory has a `README.md` file that is specific to that langauge,
so be sure to read that file for detailed instructions on how to proceed.

### Requirements
- The app shall be executed from the command line
- The app shall take an input string from the command line, like "hello world" and encode it using a default rotation of 13.
- The app shall output the string to encode, the rotation value, and the encoded string.
- The app shall read in an environmental variable called `ROT` which is the rotation value to use during the encoding process. If this value is not present then use 13 as the default.
- The app shall accept any rotation value greater than 0 and reject otherwise.
- The app shall use a default input string if one is not provided by the user.
- The app shall only rotate lowercase and uppercase ASCII characters. Let all other characters pass through unchanged.
- Organize your code into files, classes, functions as appropriate.
- Unit tests shall be written to validate the requirements.
- The code is inside a git repository, commit your code, using appropriate commit messages as you progress.
