# Basic Commands
#### The _vuw_ Commands

In an effort to make using raapoi just a bit easier, CAD staff have created commands to help you view useful information.  We call these the _vuw_ commands.  This is because all the commands begin with the string _vuw_.  This makes it easier to see the commands available to you.  If, at a command prompt you type _vuw_ followed immediately by two _TAB_ keys you will see a list of available commands beginning with _vuw_.  Go ahead and type vuw-TAB-TAB to see for yourself.

The commands available as of this update are:

* _vuw-help_:            Prints this help information
* _vuw-job-report_:      Provides some summary information about a job
* _vuw-quota_:           Prints current storage quota and usage
* _vuw-partitions_:      Prints a list of available partitions and the availability of compute nodes
* _vuw-alljobs_:         Prints a list of all user jobs
* _vuw-myjobs_:          Prints a list of your running or pending jobs
* _vuw-job-history_:     Show jobs finished in last 5 days


#### Linux Commands

Raapoi is built using the Linux operating system. Access is primarily via command line interface (CLI) as opposed to the graphical user interfaces (GUI) that you are more familiar with (such as those on Windows or Mac) Below are a list of common commands for viewing and managing files and directories (replace the file and directory names with ones you own):

**ls** - This command lists the contents of the current directory
* _ls -l_ This is the same command with a flag (-l) which lists the contents with more information, including access permissions
* _ls -a_ Same ls command but this time the -a flag which will also list hidden files. Hidden files start with a . (period)
* _ls -la_ Stringing flags together

**cd** - This will change your location to a different directory (folder)
* _cd projects/calctest_proj_
* Typing _cd_ with no arguments will take you back to your home directory

**mv** - This will move or rename a file

* _mv project1.txt project2.txt_
* _mv project2.txt projects/calctest_proj/_

**rm** - This will delete a file

* _rm projects/calctest_proj/projects2.txt_
* _rm -r projects/calctest_proj/code_
The _-r_ flag recursively removes files and directories

**mkdir** - This will create a new directory
* _mkdir /nfs/home/myusername/financial_

Other Commands you may use: _alias, awk, cat, export, for, grep, gzip, if, less, sed, tar, while_

#### Learning the Linux Shell

A good tutorial for using linux can be found here:
[Learning the linux shell](http://linuxcommand.org/lc3_learning_the_shell.php)