# How to Install LCC.js on Windows

1. Install node
    1. open Terminal by clicking on the start menu, typing Terminal, and clicking on Terminal when it appears as a menu option
    2. run the following commands (for Windows):
        - `winget install Schniz.fnm`
        - close and reopen Terminal one time
        - `fnm env --use-on-cd | Out-String | Invoke-Expression` (you may need to run this again if `node` doesn't work)
        - `fnm install 22`
        - `node -v`
2. Install git
    1. Go to https://git-scm.com/downloads/win
    2. Click on `Click here to download`
    3. Run the installer and follow the install instructions (requires git to work)
3. clone lccjs from GitHub
    1. In Terminal again, type `cd C:\Users\USERNAME\Documents` (replace USERNAME with your actual username)
    2. Type `git clone https://github.com/avidrucker/lccjs.git` and then hit enter
    3. Test to see if it worked by:
        - typing `cd lccjs` and then enter, and then
        - `node ./src/core/lcc.js ./demos/demoA.a` to see if you can run the first demo (it should ask you to type your name and then hit Enter)

- if fnm doesn't work, try opening Powershell by selecting "Terminal" (not Powershell) from the start menu OR typing `cd ~` first to switch to the correct system directory