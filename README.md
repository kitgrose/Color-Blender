This project is a fork of [the original Color Blender app][1] which I've been
using since forever.

Since macOS v10.13.4, launching Color Blender would raise the warning that the
app needed updating to remain compatible with future major releases of macOS
because Color Blender v1.2 was never compiled for 64-bit. The developer's
website as listed in the app's About dialog (http://mabblog.com/) has fallen to
squatters, so it wasn't clear if a later version existed until I found the open-
source repo the author posted.

I've therefore forked the app and done the barest minimum work to make it 64-bit
compatible, including updating the icon with Retina support and updating some of
the more trivial deprecation warnings. There are still many other warnings that
probably warrant some attention in the future.

All credit for the app and its design should go to the original author, Michael
Bianco. While I did redraw the icon to vectorise it, I tried to keep it as close
as possible to the author's original work.

To build the app, you'll need Xcode v10 (I've only tested it in v10.2.1). Build
the app for deployment and copy the .app bundle to your desired location.


  [1]: https://github.com/iloveitaly/Color-Blender
