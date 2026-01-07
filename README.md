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
  - [Email Clients](#email-clients)
  - [File Managers](#file-managers)
  - [File Operations](#file-operations)
  - [Languages (oh boy)](#languages-oh-boy)
  - [Note-taking](#note-taking)
  - [Package \& Version Managers](#package--version-managers)
  - [Process Management](#process-management)
  - [Productivity](#productivity)
  - [Search Engines](#search-engines)
  - [Search/Find](#searchfind)
  - [Social Media](#social-media)
  - [Static Site Generators](#static-site-generators)
  - [Terminal Emulators](#terminal-emulators)
  - [Universal Package Formats](#universal-package-formats)
  - [Web Frameworks](#web-frameworks)
  - [Widget Systems](#widget-systems)
  - [Window Managers \& Compositors](#window-managers--compositors)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Api Testing
- [Postman](https://www.postman.com/) -> [Bruno](https://github.com/usebruno/bruno)

## Bootable USB Creation
- [balenaEtcher](https://etcher.balena.io/) -> [Rufus](https://github.com/pbatard/rufus) -> [Ventoy](https://github.com/ventoy/Ventoy)*
- [dd](https://www.man7.org/linux/man-pages/man1/dd.1.html) -> [caligula](https://github.com/ifd3f/caligula)

## Bootloaders
- [GRUB](https://www.gnu.org/software/grub/grub.html) -> [systemd-boot](https://systemd.io/BOOT/)* -> 
[rEFInd](https://www.rodsbooks.com/refind/) -> [Limine](https://codeberg.org/Limine/Limine)*

## Email Clients
- [mutt](https://github.com/muttmua/mutt) -> [neomutt](https://github.com/neomutt/neomutt), [aerc](https://github.com/rjarry/aerc)
- [Thunderbird](https://www.thunderbird.net/en-US/) -> [Betterbird](https://www.betterbird.eu/)
## File Managers
- [ranger](https://github.com/ranger/ranger) -> [lf](https://github.com/gokcehan/lf) -> [superfile](https://github.com/yorukot/superfile) -> [yazi](https://github.com/sxyazi/yazi)*

## File Operations
- [cat](https://man7.org/linux/man-pages/man1/cat.1.html) -> [bat](https://github.com/sharkdp/bat)*
- [du](https://man7.org/linux/man-pages/man1/du.1.html) -> [dust](https://github.com/bootandy/dust)
- [ls](https://man7.org/linux/man-pages/man1/ls.1.html) -> [eza](https://github.com/eza-community/eza), [lsd](https://github.com/lsd-rs/lsd)

## Languages (oh boy)
- [Erlang](https://www.erlang.org/) -> [Elixir](https://elixir-lang.org/)
- [Java](https://openjdk.org/) -> [Kotlin](https://kotlinlang.org/)
- [Node.js](https://nodejs.org/en) -> [Deno](https://deno.com/) -> [Bun](https://bun.com/)
- [Perl](https://www.perl.org/) -> [Raku](https://raku.org/)

## Note-taking
- [Evernote](https://evernote.com/) -> [Notion](https://www.notion.com/product) -> [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)
- [Joplin](https://github.com/laurent22/joplin) -> [Obsidian](https://obsidian.md/) -> [Logseq](https://github.com/logseq/logseq)

## Package & Version Managers
- [npm](https://github.com/npm/cli) -> [yarn](https://github.com/yarnpkg/yarn) -> [pnpm](https://github.com/pnpm/pnpm) -> [bun](https://github.com/oven-sh/bun)
- [pip](https://pip.pypa.io/en/stable/) -> [conda](https://docs.conda.io/projects/conda/en/stable/) -> [uv](https://github.com/astral-sh/uv)
- [pyenv](https://github.com/pyenv/pyenv), [rbenv](https://github.com/rbenv/rbenv), [nvm](https://github.com/nvm-sh/nvm), etc. -> [asdf](https://github.com/asdf-vm/asdf) -> [mise](https://github.com/jdx/mise)*

## Process Management
- [top](https://man7.org/linux/man-pages/man1/top.1.html) -> [btop](https://github.com/aristocratos/btop)

## Productivity
- [cd](https://man7.org/linux/man-pages/man1/cd.1p.html) spam -> [zoxide](https://github.com/ajeetdsouza/zoxide)*
- [fzf](https://github.com/junegunn/fzf) -> [skim](https://github.com/skim-rs/skim)
- [man](https://man7.org/linux/man-pages/man1/man.1.html) -> [tldr](https://github.com/tldr-pages/tldr) -> [cheat.sh](https://github.com/chubin/cheat.sh)*

## Search Engines
- [Google](https://search.google/) -> [DuckDuckGo](https://duckduckgo.com/app/unsupported) -> [SearXNG](https://github.com/searxng/searxng) -> [Kagi](https://kagi.com/)

## Search/Find
- [find](https://man7.org/linux/man-pages/man1/find.1.html) -> [fd](https://github.com/sharkdp/fd)
- [grep](https://man7.org/linux/man-pages/man1/grep.1.html) -> [ripgrep](https://github.com/BurntSushi/ripgrep)*
- [locate](https://man7.org/linux/man-pages/man1/locate.1.html) -> [plocate](https://plocate.sesse.net/)

## Social Media
- The App Formerly Known as Twitter -> [Bluesky](https://bsky.social/about) -> [Mastodon](https://joinmastodon.org/)
- [Reddit](https://redditinc.com/) -> [Lemmy](https://join-lemmy.org/)
- [YouTube](https://about.youtube/) -> [PeerTube](https://joinpeertube.org/)

## Static Site Generators
- [Jekyll](https://github.com/jekyll/jekyll) -> [Hugo](https://github.com/gohugoio/hugo)*, [Zola](https://github.com/getzola/zola)
  
## Terminal Emulators
- [Konsole](https://github.com/KDE/konsole), etc. -> [Alacritty](https://github.com/alacritty/alacritty) -> [Kitty](https://github.com/kovidgoyal/kitty), [Wezterm](https://github.com/wezterm/wezterm), [Ghostty](https://github.com/ghostty-org/ghostty)*, [Rio](https://github.com/raphamorim/rio)

## Universal Package Formats
- [Snaps](https://snapcraft.io/about) -> [AppImages](https://appimage.org/) -> [Flatpak](https://flatpak.org/) -> [Nixpkgs](https://nixos.wiki/wiki/Nixpkgs)*

## Web Frameworks
- [Django](https://github.com/django/django), [Flask](https://github.com/pallets/flask) -> [FastAPI](https://github.com/fastapi/fastapi)
- [Rails](https://github.com/rails/rails) -> [Phoenix](https://github.com/phoenixframework/phoenix)

## Widget Systems
- [eww](https://github.com/elkowar/eww) -> [Astal](https://github.com/Aylur/astal)/[AGS](https://github.com/Aylur/ags) -> [Quickshell](https://github.com/quickshell-mirror/quickshell)

## Window Managers & Compositors
- [hyprland](https://github.com/hyprwm/Hyprland) -> [niri](https://github.com/YaLTeR/niri)
- [i3](https://github.com/i3/i3) -> [sway](https://github.com/swaywm/sway)
