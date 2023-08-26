# simple-twitch-chat-listener

Seeing the pure lack of twitch chat bots that are only meant for listening in and not requiring oauth tokens I decided to make my own.

This package is only meant for **Twitch** chat and is only capable of **receiving** messages, **not sending**

Pros:

- Does not require a oauth token
- Extremely simple setup
- Chat listener runs on a separate thread

Cons:

- Not much experience with edge case error handling

## Installation

```sh
pip install -U simple-twitch-chat-listener
```

## Example usage
```python
import simple-twitch-chat-listener

def my_chat_handler

tc = simple-twitch-chat-listener.TwitchChatListener("channelname")
tc. 
```

## Stuff that still needs to be done

actual RECONNECT handling

network connectivity testing
