# telegram-desktop(1) -- official telegram messaging application

## SYNOPSIS
`telegram-desktop` \[`-startintray`\] \[`-many`\] \[`-debug`\] \[`--` <URI>\]

## DESCRIPTION
This manual page documents how to run **Telegram Desktop**, official Telegram
client.

## OPTIONS
The program understands various parameters, some of them are described in the
present document.

  * `-startintray`:
     Do not show the main window, just start in the system tray. Useful for
     automatic launching.

  * `-many`:
    Allow multiple instances of the client to run at the same time.

  * `-debug`:
    Run in debug mode immediately. See logs in
    `~/.local/share/TelegramDesktop/DebugLogs`.

  * <URI>:
    Specify Telegram URI. It is used for automatically opening chats by **t.me**
    site.

## ENVIRONMENT
  * `HOME`:
    User home directory where it stores downloaded files and configuration.

## SEE ALSO
[Wiki on GitHub](https://github.com/telegramdesktop/tdesktop/wiki)
