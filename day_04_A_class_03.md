# Orange County Community College CIT-118

## CIT 118 - Operating Systems - 3 Credits

---

## To-Do's

- [x] Confirm that we cannot currently access Brightspace at NFA without either our phones or OCCC special whitelisting permissions
- [x] Take attendance
- [x] Talk briefly about office hours (confirmed that folks aren't generally available until afterschool (2:18 on))
- [x] Discuss OS's at a high level, why they are important in general, how are they relevant to cybersecurity [10 min]
  - [x] Look at [FigJam diagram](https://www.figma.com/board/AvrjZWL4y0wPxpgiHOnpRX/Operating-Systems-S2025?node-id=0-1&p=f&t=21Jzk8TTrhjTW3p0-0)
- [x] Finish installing lcc.js on laptops
  - [x] see day 03 instructions
- [x] Go over negative binary number representation (2's complement)
- [o] Introduce assembly using lccjs
- [ ] Present one history POC techie
- [ ] Bonus: Try booting computers in Linux [25 min]

## Homework for Avi

- [x] Ask Bruce about getting Brightspace access for the class and myself, want to use discussion board, announcements, file sharing, etc.
  - [x] Send email
  - [x] Confirm

- [ ] get everyone's NFA school email addresses for announcements (backup or main, tbd)

- [x] Q: is ChromeOS a flavor of Linux or is it something else?
  - A: Yes, it's a flavor/distribution of Linux.

- [ ] (once you have link sharing capabilities) share with the class the video on how chips are made

---

## Notes for Avi

- Folks still have not yet received their textbooks
- In other classes at NFA folks are using Google Drive for file sharing, email for announcements (NFA school email)
- A bunch of the computers are not configured to work with non standard file extensions (macOS textedit adds .rft and other invisible markdown by default, and Windows notepad adds .txt extension), installing VS Code would be ideal

---

## Installing LCC.js

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

---

## Attendance (and hobbies) TuTh

- Justin Viera: fighting (boxing, jiujitsu, muay thai)
- Jack Zhingri: going to the gym
- (pronounced"Janella") Janeilla Stewart: reading (mostly romance)
- Jordan Oates: playing games (any genre)
- Jayden Channer: playing games
- Joe Soto: reading light novels and manhwa (Korean comics)
- Alexis Vaquero: ???
- Chris Bacon-King ABSENT
- Josiah Burden-Ortiz: interested in martial arts (wing chun)
- Kimora Johnson: shopping (shoes, in-person or online)
- Sydney King: drawing (both traditional and digital)
- Zion Shaib: basketball
- Eric Amaya: video games (card)
- Litzy Bravo: baking (more into cakes and pastries)
- Emily Pham: playing RPGs
- Amani Learry: drawing, crocheting
- Aaron Villano: boxing 
- Yahir Rosas: gaming (action/horror)