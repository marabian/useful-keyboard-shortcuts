# useful-keyboard-shortcuts
A random list of useful keyboard shortcuts for different applications/operating systems.

## Visual Studio Code

* Toggle sidebar - `cmd b`

* Open file on right side - `cmd \` 

* Switch focus between editors (ordered by number) - `cmd <number>`

* Switch tab within an editor (ordered by number) - `ctrl <number>`
  
* Toggles right editor(s) between horizontal/vertical mode (must have more than 1 open) - `cmd option 0`

* Switch tab forward/backward - `cmd option <right arrow>/<left arrow>`

* Search for files to open (opens in focused editor if have multiple open) - `cmd p`

* Moves the currently editor left/right - `cmd k <left arrow>/<right arrow>`

* Open file in "keep it open" mode - `double click on a file in sidebar`

* Switch between tabs in focused window - `ctrl tab`

* Open **Command Palette** - `cmd shift p`

* **Rename variable** in file - `click on a variable then press f2`

* Place **multiple cursors** - `option click` (press escape to cancel)

* Open new editor (but without any file opened). The *number* must be +1 current number of editors opened - `cmd <number>`

* List out every symbol in the code - `@ in Command Palette` or `control shift .` (this view is better)

* Find a symbol (e.g. function name) across project - `# <symbol name> in Command Palette` (also e.g. type "NAR" to find "NextApiRequest", useful for long class names, works for all camel cased words).

* **Go to Symbol in File** - `cmd shift o`

* Show All Commands - `cmd shift p`

* Quick Fix - `cmd .`

* Open a new window - `cmd shift n`

## Chrome

* Open **Bookmark Manager** - `cmd option b`

* Open **Downloads** - `cmd option l`
 
* Place focus on **address bar** - `cmd l`

* Navigate backward/forward - `cmd [` and `cmd ]` or `cmd <left arrow>/<right arrow>`

* Change tab backward/forward `cmd option <left arrow>/<right arrow>`

* Toggle bookmark bar - `cmd shift b`

* Bookmark current tab - `cmd d`

* Bookmark all tabs - `cmd shift d`

* Navigate to next tab - `ctrl tab` or `option cmd <right arrow>`

* Navigate to previous tab - `ctrl shift tab` or `option cmd <left arrow>`

* Close current tab - `cmd w`

* Close all tabs in window - `cmd shift w`

* Opens last tab (or window) you closed - `cmd shift t`

* Search all files in workspace for text - `cmd shift f`

* Search current file for text - `cmd f` 

* Open **Settings** - `cmd ,` (works in most MacOS apps)

* Open **Print** - `cmd p`

## MacOS

* Delete prevous word - `option backspace`

* Delete everything before cursor - `cmd backsapce`

* Forward character delete - `FN backspace`

* Three finger swipe-up (custom keybinding) - `option s`

* *Recantgle*
  - Maximize - `ctrl option backspace`
  - Move to left/right side - `ctrl option <left arrow>/<right arrow>`
  - Move to left 1/3 - `ctrl option d`
  - Move to middle 1/3 - `ctrl option f`
  - Move to right 1/3 - `ctr option g`
  - Move to last 2/3 - `ctrl option t`
  - Move to first 2/3 - `ctrl option e`

* *Alfred*
  - Alfred Hotkey - `cmd space`
  - Search on YouTube - `yt <query>`
  - Search on Google - `g <query>`
  - Search on Gmail - `gmail <query`
  - Search on Google Drive - `dr <query>`
  - Open Google Drive `dr`
  - Open ChatGPT - `chat`
  - Open **clipboard history** (also configured to show [snippets](https://www.alfredapp.com/help/features/snippets/)) - `option cmd c`
  - Open **Useful Commands** Google Doc file - `useful`

## Vim

* In general, d<motion> will delete from current position to ending position after <motion>. This means that:

  - `d<leftArrow>` will delete current and left character
  - `d$` will delete from current position to end of line
  - `d^` will delete from current backward to first non-white-space character
  - `d0` will delete from current backward to beginning of line
  - `dw` deletes current to end of current word (including trailing space)
  - `db` deletes current to beginning of current word
  - Read [this](https://vimdoc.sourceforge.net/htmldoc/motion.html#motion.txt) to learn all the things you can combine with the 'd' command.

* Global search and replace - `:%s/old/new/g`
