# f-list multi-compare

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This is a small single page application LinuxPony made, so he could quickly compare more than two f-list profiles at
once.

It contains a single page `index.html` that contains all the required code. To run it, you simply have to open this
page. Do note that local storage function may not work if opened from a filesystem context. 

it's written entirely in vanilla JS and jQuery using f-list's API. It's not the cleanest code, but it's functional.
Coded this a while ago but just getting around to uploading now.

Features include:   

 - **All Client side**: all the requests to f-list's API are handled in the browser.
 - **Sortable and Filterable**: You can easily search, sort, and filter the output to find what you're looking for.
 - **Saves in your browser**: All the characters you look up are cached to your browser's local storage so you can come
 back later and re-view the results without having to re-do it.
 
The one pitfall of this approach is you do need to enter your username and password as f-list does not allow anonymous
access to their APIs

Live version: https://linuxpony.dev/f-list-multi-compare/

Contact me on Discord [@LinuxPony#3888](https://discord.com/users/174641580878069760) or Telegram [@LinuxPony](https://t.me/linuxpony) if you have any questions or concerns.