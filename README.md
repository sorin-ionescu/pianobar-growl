# Pianobar Growl Script

This is a [Growl](http://growl.info) notification script for [Pianobar](http://6xq.net/projects/pianobar), a console-based Pandora client.

## Installation

Make sure that the Growl Network Transport Protocol ([GNTP](https://github.com/kfdm/gntp)) Python bindings are installed.

    pip install gntp

Move *growl.py* and *pandora.png* to *~/.config/pianobar/*.

Append to *~/.config/pianobar/config*:

    event_command = /Users/user/.config/pianobar/growl.py

## Settings

`NOTIFY_SONG_START`

Notify when a song starts. (**True**/False)

`NOTIFY_SONG_END`

Notify when a song ends. (True/**False**)

`NOTIFY_SONG_LOVE`

Notify when a song is loved. (**True**/False)

`NOTIFY_SONG_BAN`

Notify when a song is banned. (**True**/False)

`NOTIFY_SONG_SHELVE`

Notify when a song is shelved. (**True**/False)

`NOTIFY_SONG_BOOKMARK`

Notify when a song is bookmarked. (**True**/False)

`NOTIFY_ARTIST_BOOKMARK`

Notify when an artist is bookmarked. (**True**/False)

`NOTIFY_PROGRAM_ERROR`

Notify on program error. (**True**/False)

`NOTIFY_NETWORK_ERROR`

Notify on network error. (**True**/False)

## License

The MIT License

Copyright (c) 2011 by Sorin Ionescu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

### Icon

The Pandora icon was created by [Ross A. Reyman](http://www.flickr.com/photos/rossr/2768279921/).

