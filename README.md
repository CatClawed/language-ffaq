A simple grammar for GameFAQs Formatted FAQs. This is largely inspired by the language-gfm package.

If you save your file with the .ffaq extention it should automatically detect.

* Known Limitations / Quirks
 * If you want to break it, you're going to break it.
 * Be careful with bolds/italics/underlines. ```'''''``` works for bold/italics, but don't do something like ```''Bold '''italic bold'' italic'''``` or you're asking for trouble.
 * Inline spoilers actually display as bold-italics.
 * ```\\``` is an escape character. I give no flips about it and don't bother including it.
 * This is a simple implementation and doesn't 100% follow the rules of GFAQs. It gets close enough.
 * Some themes, such as Seti, won't display correctly. I don't know how to fix this.

* Install Instructions
 * Since I don't intend to make this official in any respect, you need to jump through a small hoop.
 * Clone this to your preferred directory or unzip the file wherever you're going to keep it forever.
 * Bring up the [terminal (Apple)](http://lifehacker.com/launch-an-os-x-terminal-window-from-a-specific-folder-1466745514) or [command prompt (Windows)](http://www.techsupportalert.com/content/how-open-windows-command-prompt-any-folder.htm) in that folder and enter ```apm link```

![Example](https://github.com/CatClawed/language-ffaq/blob/master/Example.png)
