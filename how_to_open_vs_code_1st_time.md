# 1st Time Opening VS Code to Write an Assembly Program

For the first time opening VS Code, in order to create, edit, and save assembly programs, please do the following:

1. Open up VS Code (go to the start menu, type "VS Code", and click on it when it appears as a menu option).
2. Click on the "File" menu in the top left corner of the window.
3. Click on "Open Folder"
4. Navigate to your Documents folder and select it.
5. Double click on the lccjs folder
6. Click on the "Select Folder" button in the bottom right corner of the window.

7. Click on the "File" menu in the top left corner of the window again.
8. Click on "New File"
9. Type in the name of your assembly program (e.g., "new.a") and hit enter.
10. Now you can type in your first program, such as: (don't forget to add 1 or 2 blank spaces at the beginning of each line)
```arm
    mov r0, 25
    dout r0
    halt
```
11. To save your program, click on the "File" menu in the top left corner of the window again and click on "Save", or, use the shortcut Ctrl+S (Windows).
12. Now that you've written and saved your program,  you can go back to the terminal and run it by typing:
```bash
    node ./src/core/lcc.js ./new.a
```

Note: You may need to input your full name again, and, notice that the program this time should be located in the main lccjs project folder (not the demos folder).