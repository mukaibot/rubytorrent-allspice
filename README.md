== RubyTorrent-AllSpice ==

Yup, I forked it.

Many thanks to William Morgan and Remo Mueller for the original and enhanced versions.

I've added the ability to remove torrents from the queue.

Try it out
----------

RubyTorrent is primarily a library. See doc/api.txt for an example of how to
use it in your Ruby applications. There are also a few executable scripts for
you to play around with.

rtpeer.rb: downloads a BitTorrent package.

rtpeer-ncurses.rb: a nicer, ncurses version of the same. (The standard Ruby
curses library appears not to play nicely with Threads, so we can't use it.)

dump-metainfo.rb: takes a .torrent metainfo file and spits out everything about
it.

make-metainfo.rb: creates a .torrent file.

dump-peers.rb: takes a .torrent metainfo file, connects to the tracker, and
displays all the peers. (hack.)

