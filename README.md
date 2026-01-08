# awesome-new-and-improved [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
An awesome list of modern tools that improve upon older ones so you can stop being a cringe boomer and become an epic zoomer/s (I am going to try to keep
this from being a Rust circlejerk. Language choice alone is not considered an improvement.)

I should also mention that:
1. This list will often be opinionated
2. Only add stuff that I or anyone who wishes to collaborate with me have experience with
3. For the most part I will only give the "highly recommended" (indicated by the * next to it) label to stuff I consider absolutely essential
4. This does not mean older tools are bad or irrelevant. There are many times when older tools still have their usage and the existence 
of stuff that is easier to use does not mean we should ditch old things entirely.


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [awesome-new-and-improved ](#awesome-new-and-improved-)
  - [Api Testing](#api-testing)
  - [Bootable USB Creation](#bootable-usb-creation)
  - [Bootloaders](#bootloaders)
  - [Browsers](#browsers)
  - [Databases](#databases)
  - [Diagramming](#diagramming)
  - [Email Clients](#email-clients)
  - [File Managers](#file-managers)
  - [File Operations](#file-operations)
  - [Keyboards](#keyboards)
  - [Languages (oh boy)](#languages-oh-boy)
  - [Note-taking](#note-taking)
  - [Operating Systems](#operating-systems)
  - [Package \& Version Managers](#package--version-managers)
  - [Process Management](#process-management)
  - [Productivity](#productivity)
  - [Reverse Proxies](#reverse-proxies)
  - [Screen Recording](#screen-recording)
  - [Search Engines](#search-engines)
  - [Search/Find](#searchfind)
  - [Shells](#shells)
  - [Social Media](#social-media)
  - [Static Site Generators](#static-site-generators)
  - [Streaming Services](#streaming-services)
  - [Terminal Emulators](#terminal-emulators)
  - [Terminal Multiplexers](#terminal-multiplexers)
  - [Testing](#testing)
  - [Text Editors \& IDEs](#text-editors--ides)
  - [Universal Package Formats](#universal-package-formats)
  - [Virtualization](#virtualization)
  - [Web Frameworks](#web-frameworks)
  - [Widget Systems](#widget-systems)
  - [Window Managers \& Compositors](#window-managers--compositors)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Api Testing
- [Postman](https://www.postman.com/) -> [Bruno](https://github.com/usebruno/bruno)

## Bootable USB Creation
- [balenaEtcher](https://etcher.balena.io/) -> [Rufus](https://github.com/pbatard/rufus) -> [Ventoy](https://github.com/ventoy/Ventoy)*
- [dd](https://www.man7.org/linux/man-pages/man1/dd.1.html) -> [caligula](https://github.com/ifd3f/caligula)

*Rufus is much faster and more feature-rich than balenaEtcher is, though it is sadly a Windows only tool. Ventoy is even better as it allows you to store multiple isos on a single drive and just drag-and-drop them onto it rather than reformatting every time. Great way to save time and money.*

*caligula is essentially a simplified dd that removes all the hassle involved with it while also offering a super helpful feature that checks for the SIG automatically if you have it. It's also fast. Not as handy as Ventoy due to still taking up the whole flash drive, but handy if you like TUI-based tools*

## Bootloaders
- [GRUB](https://www.gnu.org/software/grub/grub.html) -> [systemd-boot](https://systemd.io/BOOT/)* -> [rEFInd](https://www.rodsbooks.com/refind/) -> [Limine](https://codeberg.org/Limine/Limine)*

*Nothing wrong here of course, but GRUB has been around for so long that it almost feels like some sort of pagan wizardry rather than a modern software tool. It's everything and the kitchen sink, which ain't always a good thing. systemd-boot is something I'm really glad exists because while it's nothing fancy, it's broadly compatible and super fast and simple. An excellent option for Linux newcomers. rEFInd is one I'm admittedly less familiar with, but it does have very nice customization options for those ricers, and it's great for people who need to dual boot. Limine is my current fave - offering nice customization options, the ability to chainload other bootloaders, and out-of-the-box snapshotting. It even supports both UEFI and BIOS!*

## Browsers
- [Firefox](https://www.firefox.com/en-US/)* -> [LibreWolf](https://librewolf.net/), [Waterfox](https://www.waterfox.com/), [Zen](https://zen-browser.app/)*
- [Google Chrome](https://www.google.com/chrome/) -> [Brave](https://brave.com/), [Chromium](https://www.chromium.org/Home/)
- [Opera](https://www.opera.com/) -> [Vivaldi](https://vivaldi.com/)

## Databases
- [MySQL](https://www.mysql.com/) -> [MariaDB](https://mariadb.org/)
- [PostgreSQL](https://www.postgresql.org/)* -> [CockroachDB](https://github.com/cockroachdb/cockroach), [YugabyteDB](https://github.com/yugabyte/yugabyte-db)
- [CouchDB](https://couchdb.apache.org/) -> [MongoDB](https://www.mongodb.com/)
- [Redis](https://redis.io/) -> [Valkey](https://valkey.io/), [Dragonfly](https://www.dragonflydb.io/)
- [SQLite](https://sqlite.org/) -> [DuckDB](https://www.duckdb.org/)
  

## Diagramming
- [draw.io](https://www.drawio.com/) -> [Excalidraw](https://github.com/excalidraw/excalidraw) -> [Mermaid](https://github.com/mermaid-js/mermaid)


## Email Clients
- [mutt](https://github.com/muttmua/mutt) -> [neomutt](https://github.com/neomutt/neomutt), [aerc](https://github.com/rjarry/aerc)
- [Thunderbird](https://www.thunderbird.net/en-US/) -> [Betterbird](https://www.betterbird.eu/)


## File Managers
- [Midnight Commander](https://midnight-commander.org/) -> [ranger](https://github.com/ranger/ranger) -> [lf](https://github.com/gokcehan/lf), [nnn](https://github.com/jarun/nnn) -> [superfile](https://github.com/yorukot/superfile) -> [yazi](https://github.com/sxyazi/yazi)*


## File Operations
- [cat](https://man7.org/linux/man-pages/man1/cat.1.html) -> [bat](https://github.com/sharkdp/bat)*
- [du](https://man7.org/linux/man-pages/man1/du.1.html) -> [dust](https://github.com/bootandy/dust)
- [ls](https://man7.org/linux/man-pages/man1/ls.1.html) -> [eza](https://github.com/eza-community/eza), [lsd](https://github.com/lsd-rs/lsd)

## Keyboards
- [QWERTY](https://en.wikipedia.org/wiki/QWERTY) -> [Dvorak](https://en.wikipedia.org/wiki/Dvorak_keyboard_layout) -> [Colemak](https://colemak.com/) -> [Colemak-DH](https://colemakmods.github.io/mod-dh/)*

## Languages (oh boy)
- [Erlang](https://www.erlang.org/) -> [Elixir](https://elixir-lang.org/)
- [Java](https://openjdk.org/) -> [Kotlin](https://kotlinlang.org/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) -> [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en) -> [Deno](https://deno.com/) -> [Bun](https://bun.com/)
- [Perl](https://www.perl.org/) -> [Raku](https://raku.org/)

## Note-taking
- [Evernote](https://evernote.com/) -> [Notion](https://www.notion.com/product) -> [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)
- [Joplin](https://github.com/laurent22/joplin) -> [Obsidian](https://obsidian.md/) -> [Logseq](https://github.com/logseq/logseq)

## Operating Systems
- [Debian](https://www.debian.org/)* -> [Arch Linux](https://archlinux.org/)* -> [NixOS](https://nixos.org/)*

*Now I mean no insult here, as these are the best distros overall imo. Debian is old, and it is undeniably a boomer OS. It takes a long time between releases and the packages are frequently out of date, but it just. Damn. Works. It's like the Toyota Corolla or the Honda Accord of Linux distros: it will last you a lifetime and never fail. Arch is the cool kid of the current day and is completely different: it's like the wild west, everything is constantly changing and you never know what will happen. But that's why it's great: you get the freshest of fresh software right out of the oven, and there's so many packages in the repo + AUR that it's insane. It's also the best distro to use to really learn about Linux as a whole, and you never have to worry about updates thanks to the rolling release model. Finally, there's the cool kid of the future: NixOS. If Debian is a Corolla, NixOS is like some futuristic vehicle that requires a PhD to operate. It's both stable as hell and has tons of fresh packages, but it's arcane knowledge for only the bravest of souls.*

## Package & Version Managers
- [npm](https://github.com/npm/cli) -> [yarn](https://github.com/yarnpkg/yarn) -> [pnpm](https://github.com/pnpm/pnpm) -> [bun](https://github.com/oven-sh/bun)
- [pip](https://pip.pypa.io/en/stable/) -> [conda](https://docs.conda.io/projects/conda/en/stable/) -> [uv](https://github.com/astral-sh/uv)
- [pyenv](https://github.com/pyenv/pyenv), [rbenv](https://github.com/rbenv/rbenv), [nvm](https://github.com/nvm-sh/nvm), etc. -> [asdf](https://github.com/asdf-vm/asdf) -> [mise](https://github.com/jdx/mise)*

## Process Management
- [top](https://man7.org/linux/man-pages/man1/top.1.html) -> [btop](https://github.com/aristocratos/btop)

## Productivity
- [cd](https://man7.org/linux/man-pages/man1/cd.1p.html) spam -> [zoxide](https://github.com/ajeetdsouza/zoxide)*
- [du](https://www.man7.org/linux/man-pages/man1/du.1.html) -> [dust](https://github.com/bootandy/dust)
- [fzf](https://github.com/junegunn/fzf) -> [skim](https://github.com/skim-rs/skim)
- [man](https://man7.org/linux/man-pages/man1/man.1.html) -> [tldr](https://github.com/tldr-pages/tldr) -> [cheat.sh](https://github.com/chubin/cheat.sh)*

## Reverse Proxies
- [Port forwarding](https://en.wikipedia.org/wiki/Port_forwarding) -> [Apache](https://httpd.apache.org/) -> [Nginx](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/) -> [Caddy](https://caddyserver.com/)


## Screen Recording
- [Fraps](https://fraps.com/) -> [Bandicam](https://www.bandicam.com/) -> [OBS Studio](https://obsproject.com/)

## Search Engines
- [Google](https://search.google/) -> [DuckDuckGo](https://duckduckgo.com/app/unsupported) -> [SearXNG](https://github.com/searxng/searxng) -> [Kagi](https://kagi.com/)

## Search/Find
- [find](https://man7.org/linux/man-pages/man1/find.1.html) -> [fd](https://github.com/sharkdp/fd)
- [grep](https://man7.org/linux/man-pages/man1/grep.1.html) -> [ripgrep](https://github.com/BurntSushi/ripgrep)*
- [locate](https://man7.org/linux/man-pages/man1/locate.1.html) -> [plocate](https://plocate.sesse.net/)

## Shells
- [sh](https://en.wikipedia.org/wiki/Bourne_shell) -> [Bash](https://www.gnu.org/software/bash/) -> [Zsh](https://en.wikipedia.org/wiki/Z_shell)
- [fish](https://fishshell.com/) -> [Nushell](https://www.nushell.sh/)

## Social Media
- The App Formerly Known as Twitter -> [Bluesky](https://bsky.social/about) -> [Mastodon](https://joinmastodon.org/)
- [Reddit](https://redditinc.com/) -> [Lemmy](https://join-lemmy.org/)
- [YouTube](https://about.youtube/) -> [PeerTube](https://joinpeertube.org/)

## Static Site Generators
- [Jekyll](https://github.com/jekyll/jekyll) -> [Hugo](https://github.com/gohugoio/hugo)*, [Zola](https://github.com/getzola/zola)

## Streaming Services
- [Netflix](https://www.netflix.com) and co. -> [Plex](https://www.plex.tv/) -> [Jellyfin](https://jellyfin.org/)*
- [Spotify](https://open.spotify.com/) -> [TIDAL](https://tidal.com/) -> [Bandcamp](https://bandcamp.com/)*
  
## Terminal Emulators
- [xterm](https://invisible-island.net/xterm/) -> [Konsole](https://github.com/KDE/konsole), etc. -> [Alacritty](https://github.com/alacritty/alacritty) -> [Kitty](https://github.com/kovidgoyal/kitty), [Wezterm](https://github.com/wezterm/wezterm), [Ghostty](https://github.com/ghostty-org/ghostty)*, [Rio](https://github.com/raphamorim/rio)

## Terminal Multiplexers
- [GNU Screen](https://www.gnu.org/software/screen/) -> [tmux](https://github.com/tmux/tmux/wiki) -> [Zellij](https://zellij.dev/)

## Testing
- [Jest](https://jestjs.io/) -> [Vitest](https://vitest.dev/) -> [Bun test](https://bun.sh/docs/test)

## Text Editors & IDEs
- [Atom](https://atom-editor.cc/) -> [VSCode](https://code.visualstudio.com/) -> [Zed](https://zed.dev/) -> [Lapce](https://github.com/lapce/lapce)
- [GNU Emacs](https://www.gnu.org/software/emacs/) -> [Spacemacs](https://www.spacemacs.org/) -> [Doom Emacs](https://github.com/doomemacs/doomemacs)
- [nano](https://www.nano-editor.org/) -> [micro](https://github.com/zyedidia/micro)
- [vi](https://ex-vi.sourceforge.net/) -> [vim](https://www.vim.org/) -> [neovim](https://neovim.io/)

## Universal Package Formats
- [Snaps](https://snapcraft.io/about) -> [AppImages](https://appimage.org/) -> [Flatpak](https://flatpak.org/) -> [Nixpkgs](https://nixos.wiki/wiki/Nixpkgs)*

## Virtualization
- [VirtualBox](https://www.virtualbox.org/) -> [QEMU](https://www.qemu.org/)

## Web Frameworks
- [AngularJS](https://angularjs.org/) -> [React](https://react.dev/) -> [Svelte](https://svelte.dev/), [SolidJS](https://www.solidjs.com/)
- [Django](https://github.com/django/django), [Flask](https://github.com/pallets/flask) -> [FastAPI](https://github.com/fastapi/fastapi)
- [Rails](https://github.com/rails/rails) -> [Phoenix](https://github.com/phoenixframework/phoenix)

## Widget Systems
- [eww](https://github.com/elkowar/eww) -> [Astal](https://github.com/Aylur/astal)/[AGS](https://github.com/Aylur/ags) -> [Quickshell](https://github.com/quickshell-mirror/quickshell)

## Window Managers & Compositors
- [hyprland](https://github.com/hyprwm/Hyprland) -> [niri](https://github.com/YaLTeR/niri)
- [i3](https://github.com/i3/i3) -> [sway](https://github.com/swaywm/sway)
