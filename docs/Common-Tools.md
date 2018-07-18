# Common Tools and Commands
These are common tools that will help  create hard, soft links, and list, create, delete, copy and move files and directories.
### Tools & Commands: ``` pwd, cd, ls, touch, cp, mv, ln, rm, mkdir, rmdir, alias, find, locate ```

## pwd
Prints the current directory that you are in.

**Example:**

Lets say you're in `/etc/dhcp/dhclient.d` but you forgot where you are. You can print your current directory by using the command `pwd`

![Step1](/imgs/common-commands/pwd.png)


## cd

Short for change directory. Commonly used to change to and navigate directories.

**Example:**

Lets say you want to move from `/etc` to `/etc/dhcp`

**Step 1:**

Use command `cd /etc/dhcp`


![Step1](/imgs/common-commands/cd1.png)

**Step 2:**

Verify that you've moved to new location using `pwd`

![Step1](/imgs/common-commands/cd2.png)


## ls

Linux shell command that lists directory contents of files and directories. Can also be used to list security privileges of files & directories.

 There are several flags/options for `ls` to view them use the command `ls --help`. 
The most common options are:

 ``` -a, -l, -Z, and --color=auto ```


<b>-a:</b> Will list everything including hidden files. <br><br>
<b>-l:</b> Will list all security privileges.<br> <br>
<b>-Z:</b> Will list all security privileges and context<br> <br>
<b>--color=auto:</b> Will help colorize by files and directories. Usually automatically set up as an alias already. Use command `alias` to see if it's already there.
<br><br>

### Examples

<br>

<b>Example 1:</b><br><br>
![Example1](/imgs/common-commands/ls1.png)
<br>
Using `ls` alone in root folder, you can see that anaconda-ks.cfg is listed, but as you use `ls -a` you will notice hidden files are listed.<br><br>

<b> Example 2:</b> <br><br>
![Example2](/imgs/common-commands/ls2.png)<br>
Using `ls -l` lists security privileges <br>

<b>Example 3:</b><br><br>
![Example3](/imgs/common-commands/ls3.png)<br>

Using `ls -Z` will list all security privileges and context. 
<br><br>

<b> Example 4:</b> <br><br>
![Example4](/imgs/common-commands/ls4.png)<br>
Using `alias` you can see that `ls --color=auto` is already there.
