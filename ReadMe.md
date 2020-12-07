### OpenToNord
____________________
🔸I made this to bypass a Unity3D block when trying to run Unity3D with NordVPN connection. Connecting to NordVPN servers through OpenVPN GUI fixes this 'unity block' issue, **but there are two major problems:** OpenVPN GUI can't be configured to run and connect on startup, and there isn't a way to find the 'best' server to connect to.
**OpenToNord fixes these two issues!**
_____________________
### Contact Me

[GitHub](http://github.com/FakeSmileUX)

[Telegram](http://t.me/FakeSmileUX)
_____________________
### Install OpenVPN from 
___________________
  
      a. https://nordvpn.com/tutorials/windows-7/openvpn/
  
      b. https://nordvpn.com/tutorials/windows-10/openvpn/
      
### Download and Extract The Compiled OpenToNord.zip version
___________________
      a. make sure you extract it to a good place, like `C:\Programs\OpenToNord` 
      ## **DO NOT HAVE SPACES OR PARENTHESIS IN THE DIRECTORY!**

**NOTE: Make sure to run `RunOnStartup (Run Me!).bat` again if you change the project directory!**
___________________
### Build It Yourself
___________________
TODO cleanup, make more newbie friendly. 
1. install python 3.x, most versions should be compatible
2. download source and extract source
3. pip install requests and pip install cx_freeze (or look up how to install requests and cx_freeze)
4. modify a couple lines in setup.py so they point to your python directory
5. run "python setup.py build" in terminal at the project directory (that has setup.py)
6. move all the files in `move_to_build_directory` to the newly made build directory (same path as OpenToNord.exe)
      
### Make sure you extract the config_files.zip so that the config_files folder appears in the same directory, and is full of .ovpn file

### How It Works
___________________
* **`RunOnStartup (Run Me!).bat`** creates a windows Task Scheduler to run **OpenToNord** on every boot. It calls `XML_Stuff.bat` which does some batch modifications of `task_info.xml` so it's customized to your system, and then creates a new Task with this new XML named `newtext.xml`.

* **`StopStartup.bat`** deletes the task named **OpenToNord**. Basically stops OpenToNord from running on boot.

* **`ScheduleFixer_donotrun.bat`** is a quick fix for Task Scheduler so it runs in the proper directory

* **`data.txt`** takes user input to modify how they want **OpenToNord** to run.

* **`login_info.txt`** takes an email on the first line and password on the second; used to automatically connect to NordVPN's servers.

* **`config_files`** is a list of server config files given from NordVPN's website

If you are getting config errors, replace the files inside the config_files folder with the .ovpn files from https://downloads.nordcdn.com/configs/archives/servers/ovpn.zip (might make a quick script to do this automatically later)

And you're done! Let me know if there are any problems.
_____________________
### Languages and Tools:

![](https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif)

<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />
<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />
<img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />
<img align="left" alt="Sass" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sass/sass.png" />
<img align="left" alt="JavaScript" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />
<img align="left" alt="React" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png" />
<img align="left" alt="Gatsby" width="26px" src="https://raw.githubusercontent.com/github/explore/e94815998e4e0713912fed477a1f346ec04c3da2/topics/gatsby/gatsby.png" />
<img align="left" alt="GraphQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/graphql/graphql.png" />
<img align="left" alt="Node.js" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" />
<img align="left" alt="Deno" width="26px" src="https://raw.githubusercontent.com/github/explore/361e2821e2dea67711cde99c9c40ed357061cf27/topics/deno/deno.png" />
<img align="left" alt="SQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" />
<img align="left" alt="MySQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png" />
<img align="left" alt="MongoDB" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mongodb/mongodb.png" />
<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />
<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />
<img align="left" alt="Terminal" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />

<br />
<br />
