# Description 
This is a small tool written in python3, which will automate your work for browsering .. user will not necessary to open browser every time and open new tab every time .. just directly run both desired browser and search engine with search quiry from command line .. 
You can modify this tool as u want .. 
# Requirements 
* Firefox or Chromium
## installation 
Installation is really easy You don't need to over think ? 
* git clone https://github.com/TheLinuxGuy001/google.git
* cd google
* chmod 700 google -> used to make it executable 
* sudo cp google /usr/bin/ -> remove sudo if u are super user
* done 
* use it from anywhere on command line .. 

### Usages 
This is small tool , so its easy to use. Dont over think .. 
===
usage: google [-h] -s SEARCH [-b {chromium,default}] [-e {google,bing,duckduckgo,none}] -t {open,open_new,open_new_tab}

optional arguments:
  -h, --help            show this help message and exit
  -s SEARCH, --search SEARCH
                        string text
  -b {chromium,default}, --browser {chromium,default}
                        select browser [default = firefox]
  -e {google,bing,duckduckgo,none}, --engine {google,bing,duckduckgo,none}
                        select engine [none will open in url bar]
  -t {open,open_new,open_new_tab}, --type {open,open_new,open_new_tab}
                        select type

#### Description 
* -s -> you need to input string as a input here like if you want to search for text apple then syntax will be : -s apple or -s "apple"
* -b -> browser selection [ default means firefox ] you have only two options for this tool
* -e -> Search engine selections , you will get 3 options only , 4th one is none because some time u need to input url manually like http://127.0.0.1
* -t -> tabs selection like open, open_new , open_new_tab , this is not a big deal .. 

##### Example usages 
* google -s "pine apple" -b chromium -e bing -t open_new -> this will search "pine apple" on google using chromium browser
* google -s "pine apple related: fruits" -e google -b chromium -t open_new -> like wise we can also use google dorks here
* google -s "https://www.facebook.com" -e none -b chromium -t open_new -> this will open url directly on browser

Well these are some usages of this tool , have a fun .. 
