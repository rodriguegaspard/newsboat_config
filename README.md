# newsboat_config
My personal Newsboat configuration (URLs and config file). It's a very basic configuration that adds easy access to YouTube content and headings for clarity.
# What is Newsboat?
Newsboat is a highly customizable terminal-based Atom/RSS feed reader. All information (installation, documentation, and so on..) can be found here : https://newsboat.org/ and here : https://wiki.archlinux.org/index.php/Newsboat
# How to install?
Put the <code>urls</code> and the <code>config</code> files in <code>~/.newsboat</code>.

The default browser is set to elinks (http://elinks.or.cz/).
I've added vim keybinds for navigation.

Macros :
- (<code>,y</code>) : Open video links using mpv (https://mpv.io/) + yt-dlp (https://github.com/yt-dlp/yt-dlp)
- (<code>,p</code>) : Open link using a more modern browser (I use qutebrowser : https://www.qutebrowser.org/)
- (<code>,t</code>) : Open magnet link in transmission-remote.

