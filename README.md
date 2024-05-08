## THE DEFINITIVE GUIDE TO KEYBOARD PRODUCTIVITY ON WINDOWS

I don't use Windows (I use Arch btw,) but I took a quick tour of someone else's Windows computer to
explore how the multitasking features work and create an index of the available keyboard shortcuts.

Anyone considered computer literate would be aware of the following common shortcuts which are
available in many applications and on all major operating systems.

Ctrl + A	Select all content.\
Ctrl + C (or Ctrl + Insert)	Copy selected items to clipboard.\
Ctrl + X	Cut selected items to clipboard.\
Ctrl + V (or Shift + Insert)	Paste content from clipboard.\
Ctrl + Z	Undo an action.\
Ctrl + Y	Redo an action. (Sometimes Ctrl + Shift + Z)

We should optimize the tasks which we perform the most often. If you're using a computer for more
than just web browsing then it would be wise to familiarize yourself with the keyboard shortcuts for
switching between open windows and launching new applications.

Alt-Tab will open the task-switcher for changing the focused window. Pressing tab successively moves
forward through this list and Shift-Alt-Tab will move backwards. This is fine but if you have several
open apps this 'Task View' becomes unmanageable with too many apps to cycle through and always in a
different order.

The solution is to use the `Virtual Desktop` feature. You can press Win-Tab to open the virtual desktop
menu and add a new virtual desktop. This menu provides a view of the workspaces/desktops you have made
and you can use the mouse to create new ones and switch between them. The easiest way to switch between
the workspaces/virtual desktops you create is to use the Win-Ctrl-Left and Win-Ctrl-Right to cycle back
and forth.

Another convenient feature to make use of in Windows is the task bar. Add the applications you use the
most often to the task bar, and also consider the ordering they are arranged. Apps added to the taskbar
can instantly launched, or (if already open) switched to. Obviously you can click on the icons in the
task bar to launch the application, but another option is to use the `Windows key` + `number` to open
the application at that position in the task bar. 'Windows key' + 'Alt' + 'number' opens the jump menu
for that particular application.

I would try to use just 1-3 apps per each virtual desktop so that the Alt-Tab feature is less cluttered.
"Alt-Tabbing" should only cycle between the applications which are 'in your current workspace' but this
setting can be adjusted in Settings > System > Multitasking. I think it's most useful set as described.

If you find the task-switcher menu distracting (as I do) when switching between applications, Alt-Escape
may accomplish the same without the visual clutter.

Sometimes I like to put windows side-by-side so I can see two open apps at once. You can grab a window
and drag it to the edge of the screen, it should snap to take half the view of your screen. The same can
be achieved with the keyboard simply use Win-Left and Win-Right to move the position of the focused app.

Using the `Windows key` with the 'arrow keys' works well for changing the size and position of windows.
Just using up, down, left, and right you can make any application take up half or a quadrant of your
screen space and can even fullscreen and minimize windows using 'Win' + 'Up' and 'Win' + 'Down'.

Win-Ctrl-(Left/Right)  -- change between virtual desktops\
Alt-Tab / Alt-Shift-Tab  -- change between windows on current desktop\
Alt-Escape  -- change between recent apps cleanly\
Win-Tab  -- open virtual desktop menu\
Win-ArrowKeys  -- change position/size of focused window

Launching a new application is pretty easy and in my opinion it would be pretty silly to rely on a mouse
to do so. Press Win-Q or Win-S (or just Win) to open the search menu to launch an app. Start typing the
name of the app then Enter when it appears. Apps pinned to the task bar are of course tempting to click
on, so try *right* clicking one to see what`s inside the jump menu for that app, might be useful.

Win-`Number`  -- launch an app at position `Number` in taskbar\
Win-Alt-`Number`  -- open the "jump menu" for application at associated index `Number` in taskbar

Win-D  -- show the desktop\
Win-V  -- show the clipboard (copy-paste) history/menu (you can have more than one item copied at a time)\
Win-. or Win-;  -- access emojis

You can press Win-E to open the File (E)xplorer. You can also create custom shortcuts to launch your most
used app with ease. Instructions for doing so: first pin the app to your taskbar (right click add to task
bar). If you don't want to add it to the taskbar that's okay, you can find the `properties` menu with a
right-click on the icon then set the shortcut.

Once you have pinned the app to your taskbar follow these steps:\
  -- right click the desired icon\
  -- above "unpin", right click the name of the program\
  -- left click properties\
  -- left click "shortcut key" box\
  -- type in your desired keyboard combination\
  -- left click ok

I like to have a keyboard shortcut for my web browser and terminal. Set it to something easy to remember
like Ctrl-Shift-W for (W)eb browser. Many applications can be closed instantly by just pressing Ctrl-W.

## Inside File Explorer
-- change the view between list/icons/detailed with Ctrl-Shift-'Numbers 1-8`\
-- Alt-Left or Alt-Right: go forward or back through your file-exploring history\
-- Alt-Up: move up the directory tree hierarchy\
-- Ctrl-W: close the window\
-- Ctrl-T: open new tab\
-- Ctrl-Shift-N: create new folder\
-- Ctrl-Z: Undo an action, including undelete files (limited).\
-- Ctrl-Y: Redo an action

## Inside the web browser
-- Alt-Left: move back in history\
-- Alt-Right: move forward through history\
-- Ctrl-T: new tab\
-- Ctrl-W: close tab\
-- Ctrl-Shift-T: reopen closed tab\
-- Ctrl-F: find in page\
-- Ctrl-J: view DOWN loads\
-- Ctrl-K: look UP something with Google Search

Once you have tried out the commands listed above and have explored configuring your taskbar and keyboard
shortcuts, open up Powershell or Windows Command Prompt in Administrator mode to initiate the final step
towards keyboard mastery: installing a Unix Shell.

Search for "Command Prompt", right-click, select: "Run as administrator" then enter the following command:
```
wsl --install
```

Follow the steps through then restart your computer. When it reboots you will be able to access your new
shell: Just open Command Prompt (or Powershell) again and type "bash" then Enter. Congratulations you are
now a Linux User.
