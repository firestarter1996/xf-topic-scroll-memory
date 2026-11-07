# 🗂️📜📍 Topic Scroll Memory

A Nagram XF plugin that keeps your place in every forum topic. Stock XF remembers where you were when you leave a chat from the chat list, but switching topics with the topic tabs throws that away: going back to a topic always lands at the bottom or the first unread message. With this plugin, a topic you switch back to opens exactly where you left it, down to the pixel.

## Install

1. Download `topic_scroll_memory.plugin` from the latest release.
2. Send it to yourself in Nagram XF and tap it, or open it from Settings, Plugins.
3. Turn it on. Settings: one switch, "Keep my place when switching topics".

## How it behaves

* Leave a topic part way up, open another tab, come back: you are where you were.
* Leave a topic at the very bottom: it opens at the bottom as usual, with new messages showing.
* New messages that arrived while you were away do not move you; the scroll to bottom button shows them.
* Opening a topic from the chat list works the same as stock, since it uses the same saved place.

## Speed

Nothing runs while you scroll or while anything draws. The plugin does its work once when you leave a topic (it saves the bottom message and its offset with the app's own keys) and once when the next topic opens (the app loads around that message, the same way it opens a chat from the chat list). A one time check after that load lines the message up to the exact pixel and then removes itself.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=firestarter1996/xf-topic-scroll-memory&type=Date)](https://star-history.com/#firestarter1996/xf-topic-scroll-memory&Date)
