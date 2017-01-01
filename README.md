A simple grammar for GameFAQs Formatted FAQs. This is largely inspired by the language-gfm package.

* Known Limitations
 * If you want to break it, you're going to break it.
 * Be careful with bolds/italics/underlines. ```'''''``` works for bold/italics, but don't do something like ```''Bold '''italic bold'' italic'''``` or you're asking for trouble.
 * The shortcut in which you drop ```=-=``` out of boxes doesn't display quite right. There is a form of support for the shortcut, but it takes the highlighting away from the next heading.
 * I went with the easiest implementation possible so there's probably more.
 * Inline spoilers actually display as bold-italics.
 * ```\\``` is an escape character. I give no flips about it and don't bother including it.

* Install Instructions
 * Since I don't intend to make this official in any respect, you need to jump through a small hoop.
 * Clone this to your preferred directly or unzip the file wherever you're going to keep it forever.
 * Bring up the [terminal (Apple)](http://lifehacker.com/launch-an-os-x-terminal-window-from-a-specific-folder-1466745514) or [command prompt (Windows)](http://www.techsupportalert.com/content/how-open-windows-command-prompt-any-folder.htm) in that folder and enter ```apm link```
