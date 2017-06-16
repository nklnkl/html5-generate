# html5-generate
## A shell script for UNIX that creates a new html5 project directory

There are hundreds of these generators out there. I'm just putting this in a repo because I'd like to have my own, and that I know what it does. I could just also use someone else's and read the src code for peace of mind. But I'm too lazy to do that. Hence I have this.

## Requirements

You just need UNIX, that's all. And hopefully you're not having bash / alias related issues. If you are, can't help you. Google it.

## Installation

Make sure there isn't already an html5-generate folder in the '$HOME/bin' directory. If there is, move/delete it. Just get it out of there. Then clone this repo into your '$HOME/bin' directory.
`git clone https://github.com/nklnkl/html5-generate.git $HOME/bin`


Then give the shell file execution permissions
`chmod +X $HOME/bin/html5-generate/html5-generate.sh`


Then edit your $HOME/.bashrc
`nano $HOME/.bashrc`

And add this at the end
`alias html5-generate='~/bin/html5-generate/html5-generate.sh'`

You're done!


## Usage

Run html5-generate with the path of your project you're trying to create.
`html5-generate <nameOfYourProjectHere>`

For example if I want to make an html5 project called 'catroom' in my Documents folder, I would run
`html5-generate $HOME/Documents/catroom`
