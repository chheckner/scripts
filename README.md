Just a few simple scripts, that make my life a little easier.
Most of them utilize the fzf fuzzy-finder.
More descriptions in the files

For Beginners:
make a script executable with chmod
eg:
$ chmod +x ft

then copy into a directory, that is in your systems Path
to find out: 
$ echo $PATH

if you want to add a directory to Path:
temporarily:
$ export PATH=$PATH:/path/to/dir
common choices are /home/bin/ oder /home/.local/bin
if you want to add it permanently, add this line into your .bashrc or .profile, then
$ source .bashrc
to reload the configuration
