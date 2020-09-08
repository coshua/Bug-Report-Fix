When you try to pull but get a message **fatal: refusing to merge unrelated histories**, it says your histories for local and github repo are different.
I got this error when I tried to pull my github repo where I created 'Readme.md' file manually.

To fix this, enter `git pull <origin> <master> --allow-unrelated-histories`
