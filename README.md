Discord Bot
=====================

[![Python3](https://img.shields.io/badge/python-3.5-blue.svg)](https://github.com/Der-Eddy/discord_bot)
[![GitHub license](https://img.shields.io/badge/license-Unlicense-blue.svg)](https://raw.githubusercontent.com/Der-Eddy/discord_bot/master/LICENSE)

This is mostly a german discord bot made with [discord.py](https://github.com/Rapptz/discord.py). This Bot also support Heroku.

Ihr benötigt mindestens Python 3.5 + [discord.py](https://github.com/Rapptz/discord.py) für diesen Bot und einen Discord Bot Account (siehe weiter unten).
Vor dem Start muss im selben Ordner wie `main.py` eine Datei namens `config.py` angelegt werden, ein Beispiel einer solchen gibt es in `config.example.py` zu finden:

    __token__ = 'INSERT BOT TOKEN HERE'
    __prefix__ = ':'
    __game__ = 'with Senpai'
    __adminid__ = 'YOUR USERID i.e. 102815825781596160'
    __adminrole__ = 'Administrator'

Eine Auflistung aller Befehle gibt es unter `:help` (Standardpräfix)

![help command](https://i.imgur.com/CMms1if.png)

Bot Accounts
-------------
Allgemeine Infos zu Discord Bot Accounts gibt es bei [discordapp.com/developers/](https://discordapp.com/developers/applications/me).  
Einen Bot Account fügt man dann über diesen Link hinzu (CLIENT ID einfügen nicht vergessen):  
`https://discordapp.com/oauth2/authorize?client_id=CLIENTID&scope=bot&permissions=0`

Full list of requirements
-------------

    discord.py==0.10.0
    aiohttp
    websockets
    chardet

License
-------------
    This is free and unencumbered software released into the public domain.

    Anyone is free to copy, modify, publish, use, compile, sell, or
    distribute this software, either in source code form or as a compiled
    binary, for any purpose, commercial or non-commercial, and by any
    means.

    In jurisdictions that recognize copyright laws, the author or authors
    of this software dedicate any and all copyright interest in the
    software to the public domain. We make this dedication for the benefit
    of the public at large and to the detriment of our heirs and
    successors. We intend this dedication to be an overt act of
    relinquishment in perpetuity of all present and future rights to this
    software under copyright law.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
    OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
    ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
    OTHER DEALINGS IN THE SOFTWARE.

    For more information, please refer to <http://unlicense.org>