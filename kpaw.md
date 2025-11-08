---
layout: default
title: KPAW, an API wrapper of PenguinMod for python.
permalink: /KPAW
---

# Koffee's PwnguinMod API Wrapper
KPAW was made to use the PeguinMod API easer!

## All API functions
KPAW contains these API functions,

```python
# All "TOGGLE" In the fuctions must be a boolean option (eg, true or false)
kpaw.setUserAndToken("USERNAME", "TOKEN") # Sets the username and token for all API calls
kpaw.loveToggle("PROJECT-ID", "TOGGLE") # Toggles the heart buttton on and off.
kpaw.voteToggle("PROJECT-ID", "TOGGLE") # Same as loveToggle but for the vote/favorite button.
kpaw.follow("TARGET", "TOGGLE") # Follows the target user.
kpaw.featured() # Sets var, featuredp, to the currently featured projects.
kpaw.getPfp("TARGET") # Downloads the target user's pfp
kpaw.getThumb("PROJECT-ID") # Also downloads the target project thumbnail.
kpaw.getAmountMessage() # Tells you the amount of messages with var, kpaw.message_amount, unread that YOU HAVE! Idk if this fully works.
kpaw.getProjectMeta("PROJECT-ID") # Gets all of the metadata of the project id with var, kpaw.project_meta .
kpaw.getUserMeta("TARGET") # Just like getProjectMeta but fetches information about the target user user var, kpaw.user_meta .
```

## Warnings
I am not responsible for you getting banned for something stupid you did with this (eg, make a like/favorite bot)
Be careful with your token! Don't let ANYBODY else see or use it!

[![Home](/assets/images/home.png)](..)
