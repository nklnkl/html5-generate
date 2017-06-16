# html5-generate
## A shell script for UNIX that creates a new html5 project directory

There are hundreds of these generators out there. I'm just putting this in a repo because I'd like to have my own, and that I know what it does. I could just also use someone else's and read the src code for peace of mind. But I'm too lazy to do that. Hence I have this.

## Requirements

You just need UNIX, that's all. And hopefully you're not having bash / alias related issues.

## Installation

Make sure there isn't already an html5-generate folder in the '$HOME/bin' directory. If there is, move/delete it. Just get it out of there. Then clone this repo into your '$HOME/bin' directory.

`$ git clone https://github.com/nklnkl/html5-generate.git $HOME/bin`


Then give the shell file execution permissions

`$ chmod +X $HOME/bin/html5-generate/html5-generate.sh`


Then edit your $HOME/.bashrc

`$ nano $HOME/.bashrc`

And add this at the end

`$ alias html5-generate='~/bin/html5-generate/html5-generate.sh'`

You're done!


## Usage

Go to the directory where you want to create your new project folder and rn 'html5-generate' with the name of your project

`$ html5-generate <nameOfYourProjectHere>`

For example if I want to make an html5 project called 'catroom' in my Documents folder, I would run

`$ cd ~/Documents`
`$ html5-generate catroom`


## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
