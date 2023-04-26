# Awesome Zig

> 📜Zig Learning Guide & Project Lists

[<img src="https://ziglang.org/zig-logo-light.svg" align="right" width="100">](https://ziglang.org)

[Zig](https://ziglang.org/) is a general-purpose programming language and toolchain for maintaining robust, optimal, and reusable software.

**Thanks to all the project authors and others who made this project possible.**

**Note🗒️An project may also be a development tool, application, library or other category, but it will only appear once in this guide.**

## Table Of Contents

- [Related Web Sites](#related-web-sites)
- [Development Tools](#development-tools)
  - [Editor Plugins](#editor-plugins)
  - [Package Managers](#package-managers)
  - [Other Tools](#other-tools)
- [Applications](#applications)
  - [Blockchain](#blockchain)
  - [Command Line](#command-line)
  - [Compiler & Parser & Interpreter](#compiler--parser--interpreter)
  - [Database](#database)
  - [Embedded](#embedded)
  - [Game and Desktop(GUI) Applications](#game--desktopgui-applications)
  - [Operating Systems & Kernels](#operating-systems--kernels)
  - [Simulator & Virtual Machine & Emulator](#simulator--virtual-machine--emulator)
  - [Web](#web)
  - [Other Applications](#other-applications)
- [Libraries](#libraries)
  - [Database Operation](#database-operation)
  - [Encryption & Encoding & Decoding](#encryption--encoding--decoding)
  - [Game Dev & GUI Dev & Media Framework](#game-dev--gui-dev--media-framework)
  - [Images](#images)
  - [Language Bindings](#language-bindings)
  - [Terminal & Low-Level Libraries & System API](#terminal--low-level-libraries--system-api)
  - [Universal](#universal)
    - [Algorithms & Data Structures](#algorithms--data-structures)
    - [Memory Management](#memory-management)
    - [Other Universal Libraries](#other-universal-libraries)
  - [Web](#web)
  - [Other Libraries](#other-libraries)
- [Resources](#resources)
  - [Community](https://github.com/ziglang/zig/wiki/Community)
  - [Introduction Or News](#introduction-or-News)
  - [Learning](#learning)
- [Contributing](https://github.com/C-BJ/awesome-zig/blob/main/CONTRIBUTING.md)

## Related Web Sites

- [Zig Official Website](https://ziglang.org/)
- [Zig Github Page](https://github.com/ziglang)
- [Zig News](https://zig.news/)
- [Zig Community List](https://github.com/ziglang/zig/wiki/Community)
- [Learning Zig](https://ziglearn.org/)
- [Zig Monthly](https://zigmonthly.org/)
- [Zig Showtime](https://zig.show/)
- [Zig Playground](https://zig-play.dev/)
- [Andrew Kelley's  (founder of zig) Personal Blog](https://andrewkelley.me/)
- [Loris Cro's Personal Blog](https://kristoff.it/)
- [Zig Weekly](https://discu.eu/weekly/zig/)

## Development Tools

- ### Editor Plugins

  - ![Star](https://img.shields.io/github/stars/ice1000/intellij-zig?color=orange)</span>
  [intellij-zig🗒️The IntelliJ IDEA plugin for the Zig programming language](https://github.com/ice1000/intellij-zig)
  - ![Star](https://img.shields.io/github/stars/ziglang/kde-syntax-highlighting?color=orange)
  [kde-syntax-highlighting🗒️kde xml file for zig syntax highlighting](https://github.com/ziglang/kde-syntax-highlighting) 
  - ![Star](https://img.shields.io/github/stars/ziglang/sublime-zig-language?color=orange)
  [sublime-zig-language🗒️Zig language support for Sublime Text](https://github.com/ziglang/sublime-zig-language)
  - ![Star](https://img.shields.io/github/stars/ziglang/vscode-zig?color=orange)
  [vscode-zig🗒️Zig language support for VSCode](https://github.com/ziglang/vscode-zig)
  - ![Star](https://img.shields.io/github/stars/ziglang/zig-mode?color=orange)
  [zig-mode🗒️Zig mode for Emacs](https://github.com/ziglang/zig-mode) 
  - ![Star](https://img.shields.io/github/stars/ziglang/zig.vim?color=orange)
  [zig.vim🗒️Vim configuration for Zig](https://github.com/ziglang/zig.vim) 

- ### Package Managers

  - ![Star](https://img.shields.io/github/stars/cheetah/asdf-zig?color=orange)
  [asdf-zig🗒️zig plugin for asdf version manager](https://github.com/cheetah/asdf-zig) 
  - ![Star](https://img.shields.io/github/stars/mattnite/gyro?color=orange)
  [gyro🗒️A Zig package manager with an index, build runner, and build dependencies](https://github.com/mattnite/gyro)
  - ![Star](https://img.shields.io/github/stars/zigtools/zpm?color=orange)
  [zpm🗒️Package dependency generator; WIP](https://github.com/zigtools/zpm) 
  - ![Star](https://img.shields.io/github/stars/SpexGuy/Zig-AoC-Template?color=orange)
  [Zig-AoC-Template🗒️A template for Advent of Code participants using Zig](https://github.com/SpexGuy/Zig-AoC-Template)
  - ![Star](https://img.shields.io/github/stars/nektro/zigmod?color=orange)
  [zigmod🗒️A package manager for the Zig programming language](https://github.com/nektro/zigmod) 

- ### Other Tools

  - ![Star](https://img.shields.io/github/stars/nektro/aquila?color=orange)
  [aquila🗒️📫 A federated package index and CI system for Zig projects](https://github.com/nektro/aquila) 
  - ![Star](https://img.shields.io/github/stars/mkeeter/futureproof?color=orange)
  [futureproof🗒️A live editor for fragment shaders, powered by Neovim, WebGPU, and Zig!](https://github.com/mkeeter/futureproof) 
  - ![Star](https://img.shields.io/github/stars/zig-java/jaz?color=orange)
  [jaz🗒️A JVM implementation in Zig!](https://github.com/zig-java/jaz) 
  - ![Star](https://img.shields.io/github/stars/cryptocode/marble?color=orange)
  [marble🗒️A metamorphic testing library for Zig](https://github.com/cryptocode/marble) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/repository?color=orange)
  [repository🗒️A community-maintained repository of zig packages](https://github.com/ziglibs/repository) 
  - ![Star](https://img.shields.io/github/stars/goto-bus-stop/setup-zig?color=orange)
  [setup-zig🗒️use a @ziglang compiler in your github actions workflows](https://github.com/goto-bus-stop/setup-zig) 
  - ![Star](https://img.shields.io/github/stars/justinbalexander/svd2zig?color=orange)
  [svd2zig🗒️Convert System View Description (svd) files to Zig headers for baremetal development](https://github.com/justinbalexander/svd2zig) 
  - ![Star](https://img.shields.io/github/stars/maxxnino/tree-sitter-zig?color=orange)
  [tree-sitter-zig🗒️Tree Sitter for Zig](https://github.com/maxxnino/tree-sitter-zig) 
  - ![Star](https://img.shields.io/github/stars/xmake-io/xmake?color=orange)
  [xmake🗒️A cross-platform build utility based on Lua](https://github.com/xmake-io/xmake) 
  - ![Star](https://img.shields.io/github/stars/haze/zigbo?color=orange)
  [zigbo🗒️Zig build system graph output step](https://github.com/haze/zigbo) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zig-deploy?color=orange)
  [zig-deploy🗒️Deploy your iOS apps written with Zig!](https://github.com/kubkon/zig-deploy) 
  - ![Star](https://img.shields.io/github/stars/tomhoule/zig-diff?color=orange)
  [zig-diff🗒️Text diffing in zig](https://github.com/tomhoule/zig-diff) 
  - ![Star](https://img.shields.io/github/stars/kristoff-it/zig-doctest?color=orange)
  [zig-doctest🗒️A tool for testing snippets of code, useful for websites and books that talk about Zig](https://github.com/kristoff-it/zig-doctest) 
  - ![Star](https://img.shields.io/github/stars/shritesh/zigfmt-web?color=orange)
  [zigfmt-web🗒️zig fmt on the web](https://github.com/shritesh/zigfmt-web) 
  - ![Star](https://img.shields.io/github/stars/suirad/zig-header-gen?color=orange)
  [zig-header-gen🗒️Automatically generate headers/bindings for other languages from Zig code](https://github.com/suirad/zig-header-gen) 
  - ![Star](https://img.shields.io/github/stars/ziglang/zig-pypi?color=orange)
  [zig-pypi🗒️The Zig programming language, packaged for PyPI](https://github.com/ziglang/zig-pypi) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zig-snapshots?color=orange)
  [zig-snapshots🗒️Preview Zig's incremental linker state in interactive HTML](https://github.com/kubkon/zig-snapshots) 
  - ![Star](https://img.shields.io/github/stars/marler8997/zigup?color=orange)
  [zigup🗒️Download and manage zig compilers](https://github.com/marler8997/zigup) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zld?color=orange)
  [zld🗒️Zig's lld drop-in replacement](https://github.com/kubkon/zld) 
  - ![Star](https://img.shields.io/github/stars/zigtools/zls?color=orange)
  [zls🗒️Zig LSP implementation + Zig Language Server](https://github.com/zigtools/zls) 
  

## Applications

- ### Blockchain

  - ![Star](https://img.shields.io/github/stars/lithdew/rheia?color=orange)
  [rheia🗒️A blockchain written in Zig](https://github.com/lithdew/rheia) 

- ### Command Line

  - ![Star](https://img.shields.io/github/stars/kubkon/calctax?color=orange)
  [calctax🗒️Simple tax calculator for employees in Poland after Nowy Lad changes in 2022](https://github.com/kubkon/calctax) 
  - ![Star](https://img.shields.io/github/stars/rvcas/crisp?color=orange)
  [crisp🗒️A Minimal Lispy Calculator](https://github.com/rvcas/crisp) 
  - ![Star](https://img.shields.io/github/stars/dmbfm/gi?color=orange)
  [gi🗒️Simple program that generates .gitignore files based on the templates from https://github.com/toptal/gitignore](https://github.com/dmbfm/gi) 
  - [outfieldr🗒️A TLDR client in Zig](https://gitlab.com/ve-nt/outfieldr) 
  - ![Star](https://img.shields.io/github/stars/michaelo/sapt?color=orange)
  [sapt🗒️Simple file-oriented API-testing tool](https://github.com/michaelo/sapt) 
  - ![Star](https://img.shields.io/github/stars/pbui-project/pbui-main?color=orange)
  [pbui-main🗒️The main repository for the PBUI project](https://github.com/pbui-project/pbui-main) 
  - ![Star](https://img.shields.io/github/stars/ekzhang/redis-rope?color=orange)
  [redis-rope🗒️A fast native data type for manipulating large strings in Redis](https://github.com/ekzhang/redis-rope) 
  - ![Star](https://img.shields.io/github/stars/user00e00/sudokuinzig?color=orange)
  [sudokuinzig🗒️Sudoku solver in zig](https://github.com/user00e00/sudokuinzig) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zcoff?color=orange)
  [zcoff🗒️Like dumpbin.exe but cross-platform](https://github.com/kubkon/zcoff) 
  - ![Star](https://img.shields.io/github/stars/nektro/zig-inquirer?color=orange)
  [zig-inquirer🗒️A collection of utilities for prompting information from the user on the CLI](https://github.com/nektro/zig-inquirer) 
  - ![Star](https://img.shields.io/github/stars/ratfactor/zigish?color=orange)
  [zigish🗒️A toy Unix shell written in Zig](https://github.com/ratfactor/zigish) 

- ### Compiler & Parser & Interpreter

  - ![Star](https://img.shields.io/github/stars/Vexu/arocc?color=orange)
  [arocc🗒️A C compiler written in Zig](https://github.com/Vexu/arocc) 
  - ![Star](https://img.shields.io/github/stars/gernest/base32?color=orange)
  [base32🗒️base32 encoding/decoding for ziglang](https://github.com/gernest/base32) 
  - ![Star](https://img.shields.io/github/stars/Vexu/bog?color=orange)
  [bog🗒️Small, strongly typed, embeddable language](https://github.com/Vexu/bog) 
  - ![Star](https://img.shields.io/github/stars/dantecatalfamo/brainfuck-zig?color=orange)
  [brainfuck-zig🗒️Brainfuck interpreter written in zig](https://github.com/dantecatalfamo/brainfuck-zig) 
  - ![Star](https://img.shields.io/github/stars/buzz-language/buzz?color=orange)
  [buzz🗒️buzz, A small/lightweight statically typed scripting language (in development)](https://github.com/buzz-language/buzz) 
  - ![Star](https://img.shields.io/github/stars/travisstaloch/cmdlinezig?color=orange)
  [cmdlinezig🗒️A simple command line parser](https://github.com/travisstaloch/cmdlinezig) 
  - ![Star](https://img.shields.io/github/stars/fubark/cyber?color=orange)
  [cyber🗒️Fast and concurrent scripting](https://github.com/fubark/cyber) 
  - ![Star](https://img.shields.io/github/stars/truemedian/hzzp?color=orange)
  [hzzp🗒️A I/O agnostic HTTP/1.1 parser and encoder for Zig](https://github.com/truemedian/hzzp) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/ini?color=orange)
  [ini🗒️A teeny tiny ini parser](https://github.com/ziglibs/ini) 
  - ![Star](https://img.shields.io/github/stars/Hejsil/jng2-decrypt?color=orange)
  [jng2-decrypt🗒️Small program for decrypting the Jets'n'Guns 2 game files](https://github.com/Hejsil/jng2-decrypt) 
  - ![Star](https://img.shields.io/github/stars/kivikakk/koino?color=orange)
  [koino🗒️CommonMark + GFM compatible Markdown parser and renderer](https://github.com/kivikakk/koino) 
  - ![Star](https://img.shields.io/github/stars/kivikakk/libpcre.zig?color=orange)
  [libpcre.zig🗒️Zig bindings to libpcre](https://github.com/kivikakk/libpcre.zig) 
  - ![Star](https://img.shields.io/github/stars/dundalek/liz?color=orange)
  [liz🗒️Lisp-flavored general-purpose programming language (based on Zig)](https://github.com/dundalek/liz) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/LoLa?color=orange)
  [LoLa🗒️LoLa is a small programming language meant to be embedded into games](https://github.com/MasterQ32/LoLa) 
  - ![Star](https://img.shields.io/github/stars/Luukdegram/luf?color=orange)
  [luf🗒️Statically typed, embeddable, scripting language written in Zig](https://github.com/Luukdegram/luf) 
  - ![Star](https://img.shields.io/github/stars/kubkon/protozig?color=orange)
  [protozig🗒️The protozig(uana), or protocol buffers implementation in Zig](https://github.com/kubkon/protozig) 
  - ![Star](https://img.shields.io/github/stars/chwayne/rem?color=orange)
  [rem🗒️An HTML parsing library, written in Zig](https://github.com/chwayne/rem) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/tres?color=orange)
  [tres🗒️ValueTree-based JSON parser](https://github.com/ziglibs/tres) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zacho?color=orange)
  [zacho🗒️Zig's Mach-O parser](https://github.com/kubkon/zacho)
  - [zcheme🗒️WIP implementation of R7RS Scheme](https://hg.sr.ht/~hutzdog/Zcheme)
  - ![Star](https://img.shields.io/github/stars/kubkon/zelf?color=orange)
  [zelf🗒️Zig's ELF parser utility](https://github.com/kubkon/zelf) 
  - [zexpr🗒️Zig S-expression library](https://hg.sr.ht/~hutzdog/Zcheme/browse/zexpr?rev=tip)
  - ![Star](https://img.shields.io/github/stars/sam701/zig-cli?color=orange)
  [zig-cli🗒️A simple package for building command line apps in Zig](https://github.com/sam701/zig-cli) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zig-dwarfdump?color=orange)
  [zig-dwarfdump🗒️dwarfdump utility but in Zig](https://github.com/kubkon/zig-dwarfdump) 
  - ![Star](https://img.shields.io/github/stars/vi/zigmkv?color=orange)
  [zigmkv🗒️wip Matroska/webm (mkv) parser in Zig](https://github.com/vi/zigmkv) 
  - ![Star](https://img.shields.io/github/stars/winksaville/zig-parse-args?color=orange)
  [zig-parse-args🗒️Parse command line arguments](https://github.com/winksaville/zig-parse-args)
  - ![Star](https://img.shields.io/github/stars/winksaville/zig-parse-number?color=orange)
  [zig-parse-number🗒️Implement ParseNumber which can parse any TypeId.Int or TypeId.Float](https://github.com/winksaville/zig-parse-number) 
  - ![Star](https://img.shields.io/github/stars/tiehuis/zig-regex?color=orange)
  [zig-regex🗒️A regex implementation for the zig programming language](https://github.com/tiehuis/zig-regex) 
  - ![Star](https://img.shields.io/github/stars/tiehuis/zig-ryu?color=orange)
  [zig-ryu🗒️Zig port of https://github.com/ulfjack/ryu](https://github.com/tiehuis/zig-ryu) 
  - ![Star](https://img.shields.io/github/stars/aeronavery/zig-toml?color=orange)
  [zig-toml🗒️A TOML parser written in Zig](https://github.com/aeronavery/zig-toml) 
  - ![Star](https://img.shields.io/github/stars/sam701/zig-toml?color=orange)
  [zig-toml🗒️An LL TOML parser that parses into Zig structs](https://github.com/sam701/zig-toml) 
  - ![Star](https://img.shields.io/github/stars/Himujjal/zig-json5?color=orange)
  [zig-json5🗒️A JSON5 Parser/Stringifier written in Zig](https://github.com/Himujjal/zig-json5) 
  - ![Star](https://img.shields.io/github/stars/goto-bus-stop/ziguid?color=orange)
  [ziguid🗒️GUID parsing/stringifying with zig](https://github.com/goto-bus-stop/ziguid) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zig-yaml?color=orange)
  [zig-yaml🗒️YAML parser for Zig](https://github.com/kubkon/zig-yaml) 
  - [ztoml🗒️TOMLv1.0.0 parser](https://codeberg.org/naneros/ztoml.git)
  - ![Star](https://img.shields.io/github/stars/squeek502/zua?color=orange)
  [zua🗒️An implementation of Lua 5.1 in Zig, for learning purposes](https://github.com/squeek502/zua) 
  - ![Star](https://img.shields.io/github/stars/Vexu/zuri?color=orange)
  [zuri🗒️URI parser for Zig](https://github.com/Vexu/zuri) 

- ### Database
  
  - ![Star](https://img.shields.io/github/stars/lun-4/awtfdb?color=orange)
  [awtfdb🗒️the Anime Woman's Tagged File Data Base](https://github.com/lun-4/awtfdb) 
  - ![Star](https://img.shields.io/github/stars/kristoff-it/redis-cuckoofilter?color=orange)
  [redis-cuckoofilter🗒️Hashing-function agnostic Cuckoo filters for Redis](https://github.com/kristoff-it/redis-cuckoofilter) 
  - ![Star](https://img.shields.io/github/stars/leroycep/sqlite-zig?color=orange)
  [sqlite-zig SQLite bindings](https://github.com/leroycep/sqlite-zig) 
  - ![Star](https://img.shields.io/github/stars/coilhq/tigerbeetle?color=orange)
  [tigerbeetle🗒️A distributed financial accounting database designed for mission critical safety and performance to power the future of financial services](https://github.com/coilhq/tigerbeetle) 
  - ![Star](https://img.shields.io/github/stars/drcode/zek?color=orange)
  [zek](https://github.com/drcode/zek) 
  - ![Star](https://img.shields.io/github/stars/vrischmann/zig-cassandra?color=orange)
  [zig-cassandra🗒️Cassandra CQL client](https://github.com/vrischmann/zig-cassandra) 
  - ![Star](https://img.shields.io/github/stars/kristoff-it/zig-okredis?color=orange)
  [zig-okredis🗒️Zero-allocation Client for Redis 6+](https://github.com/kristoff-it/zig-okredis) 
  - ![Star](https://img.shields.io/github/stars/vrischmann/zig-sqlite?color=orange)
  [zig-sqlite🗒️zig-sqlite is a small wrapper around sqlite's C API, making it easier to use with Zig](https://github.com/vrischmann/zig-sqlite) 

- ### Embedded
  
  - ![Star](https://img.shields.io/github/stars/tralamazza/embedded_zig?color=orange)
  [embedded_zig🗒️minimal Zig embedded ARM example (STM32F103 blue pill)](https://github.com/tralamazza/embedded_zig) 
  - ![Star](https://img.shields.io/github/stars/nrdmn/uefi-paint?color=orange)
  [uefi-paint🗒️UEFI-bootable touch paint app](https://github.com/nrdmn/uefi-paint) 
  - ![Star](https://img.shields.io/github/stars/yvt/zig-armv8m-test?color=orange)
  [zig-armv8m-test🗒️Minimal Zig-based app for Armv8-M + TrustZone](https://github.com/yvt/zig-armv8m-test) 
  - ![Star](https://img.shields.io/github/stars/markfirmware/zig-bare-metal-microbit?color=orange)
  [zig-bare-metal-microbit🗒️Bare metal microbit program written in zig](https://github.com/markfirmware/zig-bare-metal-microbit) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/Ziguana-Game-System?color=orange)
  [Ziguana-Game-System🗒️A retro-style gaming console running on bare x86 metal written in Zig](https://github.com/MasterQ32/Ziguana-Game-System) 
  
- ### Game & Desktop(GUI) Applications

  - ![Star](https://img.shields.io/github/stars/Stenodyon/blink?color=orange)
  [blink🗒️A game about building logic with lasers](https://github.com/Stenodyon/blink) 
  - ![Star](https://img.shields.io/github/stars/kristoff-it/bork?color=orange)
  [bork🗒️A TUI chat client tailored for livecoding on Twitch](https://github.com/kristoff-it/bork) 
  - ![Star](https://img.shields.io/github/stars/andrewrk/clashos?color=orange)
  [clashos🗒️multiplayer arcade game for bare metal Raspberry Pi 3 B+](https://github.com/andrewrk/clashos) 
  - ![Star](https://img.shields.io/github/stars/Akuli/curses-minesweeper?color=orange)
  [curses-minesweeper🗒️Minesweeper game written in curses with zig](https://github.com/Akuli/curses-minesweeper) 
  - ![Star](https://img.shields.io/github/stars/Avokadoen/gamejam-zig-vulkan?color=orange)
  [gamejam-zig-vulkan🗒️A game written in ~1 day using zig and vulkan](https://github.com/Avokadoen/gamejam-zig-vulkan) 
  - ![Star](https://img.shields.io/github/stars/zig-community/hello-triangle?color=orange)
  [hello-triangle🗒️Opens a window and draws a nice little triangle](https://github.com/zig-community/hello-triangle) 
  - ![Star](https://img.shields.io/github/stars/thejoshwolfe/legend-of-swarkland?color=orange)
  [legend-of-swarkland🗒️Hack-n-slash roguelike inspired by NetHack](https://github.com/thejoshwolfe/legend-of-swarkland) 
  - ![Star](https://img.shields.io/github/stars/greenfork/kisa?color=orange)
  [kisa🗒️Text editor of the new world](https://github.com/greenfork/kisa) 
  - ![Star](https://img.shields.io/github/stars/Ryp/minesweeper-zig?color=orange)
  [minesweeper-zig🗒️Simple Minesweeper clone written in Zig, using SDL for graphics](https://github.com/Ryp/minesweeper-zig) 
  - ![Star](https://img.shields.io/github/stars/fabioarnold/MiniPixel?color=orange)
  [MiniPixel🗒️Tiny pixel art editor](https://github.com/fabioarnold/MiniPixel) 
  - ![Star](https://img.shields.io/github/stars/kooparse/mogwai?color=orange)
  [mogwai🗒️Graphic utility used to manipulate objects in 3D for scene editing (commonly called Gizmo)](https://github.com/kooparse/mogwai) 
  - ![Star](https://img.shields.io/github/stars/dantecatalfamo/OpenCSE?color=orange)
  [OpenCSE🗒️Free implementation of the Can't Stop Express dice game](https://github.com/dantecatalfamo/OpenCSE) 
  - ![Star](https://img.shields.io/github/stars/floooh/pacman.zig?color=orange)
  [pacman.zig🗒️Simple Pacman clone written in Zig](https://github.com/floooh/pacman.zig) 
  - ![Star](https://img.shields.io/github/stars/pfgithub/pixelcode?color=orange)
  [pixelcode](https://github.com/pfgithub/pixelcode) 
  - ![Star](https://img.shields.io/github/stars/mkeeter/rayray?color=orange)
  [rayray🗒️A tiny GPU raytracer, using Zig and WebGPU](https://github.com/mkeeter/rayray) 
  - ![Star](https://img.shields.io/github/stars/fabioarnold/snake-zig?color=orange)
  [snake-zig🗒️A simple snake game written in the Zig programming language using OpenGL 2](https://github.com/fabioarnold/snake-zig) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/SoftRenderLib?color=orange)
  [SoftRenderLib🗒️A collection of software rendering routines](https://github.com/MasterQ32/SoftRenderLib) 
  - ![Star](https://img.shields.io/github/stars/andrewrk/tetris?color=orange)
  [tetris🗒️A simple tetris clone written in zig programming language](https://github.com/andrewrk/tetris) 
  - ![Star](https://img.shields.io/github/stars/JonSnowbd/underburrow?color=orange)
  [underburrow🗒️A small platformer example for Slingworks & Zig](https://github.com/JonSnowbd/underburrow) 
  - ![Star](https://img.shields.io/github/stars/Nelarius/weekend-raytracer-zig?color=orange)
  [weekend-raytracer-zig🗒️A Zig implementation of the "Ray Tracing in One Weekend" book](https://github.com/Nelarius/weekend-raytracer-zig) 
  - ![Star](https://img.shields.io/github/stars/desttinghim/wired?color=orange)
  [wired](https://github.com/desttinghim/wired) 
  - ![Star](https://img.shields.io/github/stars/fabioarnold/zig-gorillas?color=orange)
  [zig-gorillas🗒️A clone of the classic QBasic Gorillas written in the Zig programming language](https://github.com/fabioarnold/zig-gorillas) 
  - ![Star](https://img.shields.io/github/stars/SpexGuy/Zig-Oculus-Quest?color=orange)
  [Zig-Oculus-Quest🗒️An example application for the Oculus Quest, written in Zig](https://github.com/SpexGuy/Zig-Oculus-Quest) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/ZigPaint?color=orange)
  [ZigPaint🗒️A simple paint application written in Zig. Used to create an OpenGL loader/wrapper and a minimal UI system](https://github.com/MasterQ32/ZigPaint) 
  - ![Star](https://img.shields.io/github/stars/BitPuffin/zig-raylib-experiments?color=orange)
  [zig-raylib-experiments🗒️Some classic game implementations in Zig using raylib](https://github.com/BitPuffin/zig-raylib-experiments) 
  - ![Star](https://img.shields.io/github/stars/tiehuis/zig-raytrace?color=orange)
  [zig-raytrace🗒️simple raytracer in zig](https://github.com/tiehuis/zig-raytrace) 
  - ![Star](https://img.shields.io/github/stars/zig-community/Zig-Showdown?color=orange)
  [Zig-Showdown🗒️A community effort to create a small multiplayer 3D shooter game in pure zig](https://github.com/zig-community/Zig-Showdown) 
  - ![Star](https://img.shields.io/github/stars/andrewrk/zig-vulkan-triangle?color=orange)
  [zig-vulkan-triangle🗒️simple triangle displayed using vulkan, glfw, and zig](https://github.com/andrewrk/zig-vulkan-triangle) 
  - ![Star](https://img.shields.io/github/stars/holobeat/zig-wasm-snake?color=orange)
  [zig-wasm-snake🗒️Classic snake game written in Zig, compiled to WASM](https://github.com/holobeat/zig-wasm-snake) 
  - ![Star](https://img.shields.io/github/stars/donpdonp/zootdeck?color=orange)
  [zootdeck🗒️Fediverse GTK Desktop Reader](https://github.com/donpdonp/zootdeck) 
  - ![Star](https://img.shields.io/github/stars/tiehuis/zstack?color=orange)
  [zstack🗒️Line-race tetris mode in Zig](https://github.com/tiehuis/zstack) 
  - ![Star](https://img.shields.io/github/stars/flouthoc/ztick?color=orange)
  [ztick🗒️tiny desktop utility to keep notes ( with no features ). Written in zig and gtk4](https://github.com/flouthoc/ztick) 
  - ![Star](https://img.shields.io/github/stars/Opioid/zyg?color=orange)
  [zyg🗒️Pathtracer written in zig](https://github.com/Opioid/zyg) 

- ### Operating Systems & Kernels

  - ![Star](https://img.shields.io/github/stars/kivikakk/daintree?color=orange)
  [daintree🗒️ARMv8-A/RISC-V kernel (with UEFI bootloader)](https://github.com/kivikakk/daintree) 
  - ![Star](https://img.shields.io/github/stars/iguessthislldo/georgios?color=orange)
  [georgios🗒️Hobby Operating System](https://github.com/iguessthislldo/georgios) 
  - ![Star](https://img.shields.io/github/stars/andrewrk/HellOS?color=orange)
  [HellOS🗒️"hello world" x86 kernel example](https://github.com/andrewrk/HellOS) 
  - ![Star](https://img.shields.io/github/stars/HidamariProject/Hidamari?color=orange)
  [Hidamari🗒️Modern operating system aimed at running WebAssembly code](https://github.com/HidamariProject/Hidamari) 
  - ![Star](https://img.shields.io/github/stars/jzck/kernel-zig?color=orange)
  [kernel-zig🗒️hobby x86 kernel zig](https://github.com/jzck/kernel-zig) 
  - ![Star](https://img.shields.io/github/stars/DorianXGH/Lukarnel?color=orange)
  [Lukarnel🗒️A microkernel in zig with rust microservices](https://github.com/DorianXGH/Lukarnel) 
  - ![Star](https://img.shields.io/github/stars/ZigEmbeddedGroup/microzig?color=orange)
  [microzig🗒️Unified abstraction layer and HAL for several microcontrollers](https://github.com/ZigEmbeddedGroup/microzig) 
  - ![Star](https://img.shields.io/github/stars/ZystemOS/pluto?color=orange)
  [pluto🗒️An x86 kernel written in Zig](https://github.com/ZystemOS/pluto) 
  - ![Star](https://img.shields.io/github/stars/jacobly0/tizr80?color=orange)
  [tizr80🗒️TiZr80, a TI-84+ CE/TI-83 Premium CE calculator emulator core](https://github.com/jacobly0/tizr80) 
  - ![Star](https://img.shields.io/github/stars/sjdh02/trOS?color=orange)
  [trOS🗒️tiny aarch64 baremetal OS thingy](https://github.com/sjdh02/trOS) 
  - ![Star](https://img.shields.io/github/stars/stakach/uefi-bootstrap?color=orange)
  [uefi-bootstrap🗒️experiments with bootstrapping a kernel with UEFI](https://github.com/stakach/uefi-bootstrap) 
  - ![Star](https://img.shields.io/github/stars/nrdmn/uefi-examples?color=orange)
  [uefi-examples🗒️UEFI examples in Zig](https://github.com/nrdmn/uefi-examples) 
  - ![Star](https://img.shields.io/github/stars/davidgm94/rise?color=orange)
  [rise🗒️A better operating system](https://github.com/davidgm94/rise) 
  - ![Star](https://img.shields.io/github/stars/ZeeBoppityZagZiggity/ZBZZ.OS?color=orange)
  [ZBZZ.OS🗒️An operating system built with RISCV and Zig](https://github.com/ZeeBoppityZagZiggity/ZBZZ.OS) 
  - ![Star](https://img.shields.io/github/stars/AndreaOrru/zen?color=orange)
  [zen🗒️Experimental operating system written in Zig](https://github.com/AndreaOrru/zen) 
  - ![Star](https://img.shields.io/github/stars/markfirmware/zig-bare-metal-raspberry-pi?color=orange)
  [zig-bare-metal-raspberry-pi🗒️Bare metal raspberry pi program written in zig](https://github.com/markfirmware/zig-bare-metal-raspberry-pi) 
  - ![Star](https://img.shields.io/github/stars/leecannon/zig-x86_64?color=orange)
  [zig-x86_64🗒️Support for x86_64 specific instructions (e.g. TLB flush), registers (e.g. control registers), and structures (e.g. page tables)](https://github.com/leecannon/zig-x86_64) 

- ### Simulator & Virtual Machine & Emulator

  - ![Star](https://img.shields.io/github/stars/GrooveStomp/chip8-zig?color=orange)
  [chip8-zig🗒️A CHIP-8 emulator written in Zig](https://github.com/GrooveStomp/chip8-zig) 
  - ![Star](https://img.shields.io/github/stars/Arwalk/ChipZ?color=orange)
  [ChipZ🗒️A simple Chip8 emulator (executable and library) written in Zig](https://github.com/Arwalk/ChipZ) 
  - ![Star](https://img.shields.io/github/stars/fengb/fundude?color=orange)
  [fundude🗒️Gameboy emulator:Zig -> wasm](https://github.com/fengb/fundude) 
  - ![Star](https://img.shields.io/github/stars/floooh/kc85.zig?color=orange)
  [kc85.zig🗒️A KC85 emulator written in Zig](https://github.com/floooh/kc85.zig) 
  - ![Star](https://img.shields.io/github/stars/Ronsor/riscv-zig?color=orange)
  [riscv-zig🗒️A RISC-V emulator written in Zig](https://github.com/Ronsor/riscv-zig) 
  - ![Star](https://img.shields.io/github/stars/I-mikan-I/zlox?color=orange)
  [zlox🗒️lox virtual machine implementation in zig!](https://github.com/I-mikan-I/zlox) 
  
- ### Web

  - ![Star](https://img.shields.io/github/stars/mattnite/astrolabe?color=orange)
  [astrolabe🗒️backend for https://astrolabe.pm](https://github.com/mattnite/astrolabe) 
  - ![Star](https://img.shields.io/github/stars/lithdew/hello?color=orange)
  [hello🗒️Multi-threaded cross-platform HTTP/1.1 web server example in Zig](https://github.com/lithdew/hello) 
  - ![Star](https://img.shields.io/github/stars/andrewrk/lua-in-the-browser?color=orange)
  [lua-in-the-browser🗒️using zig to build lua for webassembly](https://github.com/andrewrk/lua-in-the-browser) 
  - ![Star](https://img.shields.io/github/stars/haze/zelda?color=orange)
  [zelda🗒️A simple HTTP client library for Zig](https://github.com/haze/zelda) 
  - ![Star](https://img.shields.io/github/stars/haze/zig-libressl?color=orange)
  [zig-libressl🗒️LibreSSL stream wrappers for Zig](https://github.com/haze/zig-libressl)
  - ![Star](https://img.shields.io/github/stars/kubkon/zig-objdump?color=orange)
  [zig-objdump🗒️objdump but in Zig and for Zig](https://github.com/kubkon/zig-objdump) 
  - ![Star](https://img.shields.io/github/stars/shritesh/zig-wasm-dom?color=orange)
  [zig-wasm-dom🗒️Zig + WebAssembly + JS + DOM](https://github.com/shritesh/zig-wasm-dom) 
  - ![Star](https://img.shields.io/github/stars/meheleventyone/zig-wasm-test?color=orange)
  [zig-wasm-test🗒️A minimal Web Assembly example using Zig's build system](https://github.com/meheleventyone/zig-wasm-test) 
  - ![Star](https://img.shields.io/github/stars/chwayne/zss?color=orange)
  [zss🗒️zss is a CSS layout engine and renderer](https://github.com/chwayne/zss) 
  - ![Star](https://img.shields.io/github/stars/Luukdegram/zwld?color=orange)
  [zwld🗒️Experimental wasm linker](https://github.com/Luukdegram/zwld) 

- ### Other Applications
  - ![Star](https://img.shields.io/github/stars/oven-sh/bun?color=orange)
  [bun🗒️Incredibly fast JavaScript runtime, bundler, transpiler and package manager – all in one](https://github.com/oven-sh/bun) 
  - ![Star](https://img.shields.io/github/stars/Luukdegram/cld?color=orange)
  [cld🗒️Linker for the Coff/PE file format](https://github.com/Luukdegram/cld) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/computils?color=orange)
  [computils🗒️Zig utilities for all your comptime needs](https://github.com/ziglibs/computils) 
  - ![Star](https://img.shields.io/github/stars/fubark/cosmic?color=orange)
  [cosmic🗒️A general purpose runtime for Javascript/WASM](https://github.com/fubark/cosmic) 
  - ![Star](https://img.shields.io/github/stars/hspak/geteltorito-zig?color=orange)
  [geteltorito-zig🗒️geteltorito re-write in Zig](https://github.com/hspak/geteltorito-zig) 
  - ![Star](https://img.shields.io/github/stars/thejoshwolfe/hexdump-zip?color=orange)
  [hexdump-zip🗒️produce an annotated hexdump of a zipfile](https://github.com/thejoshwolfe/hexdump-zip) 
  - ![Star](https://img.shields.io/github/stars/alexnask/iguanaTLS?color=orange)
  [iguanaTLS🗒️Minimal, experimental TLS 1.2 implementation in Zig](https://github.com/alexnask/iguanaTLS) 
  - ![Star](https://img.shields.io/github/stars/mqttiotstuff/iotmonitor?color=orange)
  [iotmonitor🗒️Monitor and State server for iot mqtt devices, and software agents. This daemon permit to maintain the execution of constellations of mqtt devices and associated agents](https://github.com/mqttiotstuff/iotmonitor) 
  - ![Star](https://img.shields.io/github/stars/mjoerussell/onenightonearth?color=orange)
  [onenightonearth🗒️An interactive star map, written in Typescript and WebAssembly using Zig](https://github.com/mjoerussell/onenightonearth) 
  - ![Star](https://img.shields.io/github/stars/floooh/pacman.zig?color=orange)
  [pacman.zig🗒️Simple Pacman clone written in Zig](https://github.com/floooh/pacman.zig) 
  - ![Star](https://img.shields.io/github/stars/kauche/proxy-wasm-cloud-logging-trace-context?color=orange)
  [proxy-wasm-cloud-logging-trace-context🗒️A proxy-wasm compilant WebAssembly module for making proxies integrate with Google Cloud Logging](https://github.com/kauche/proxy-wasm-cloud-logging-trace-context) 
  - ![Star](https://img.shields.io/github/stars/riverwm/river?color=orange)
  [river🗒️A dynamic tiling Wayland compositor](https://github.com/riverwm/river) 
  - ![Star](https://img.shields.io/github/stars/dominikh/wayfarer?color=orange)
  [wayfarer🗒️Experiments involving a Zig Wayland compositor](https://github.com/dominikh/wayfarer) 
  - ![Star](https://img.shields.io/github/stars/ifreund/waylock?color=orange)
  [waylock🗒️A small screenlocker for Wayland compositors](https://github.com/ifreund/waylock) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/ZigAndroidTemplate?color=orange)
  [ZigAndroidTemplate🗒️This repository contains a example on how to create a minimal Android app in Zig](https://github.com/MasterQ32/ZigAndroidTemplate) 
  - ![Star](https://img.shields.io/github/stars/dvmason/Zag-Smalltalk?color=orange)
  [Zag-Smalltalk🗒️Smalltalk VM Written in Zig with methods stored as type-annotated ASTs](https://github.com/dvmason/Zag-Smalltalk) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zig-ios-example?color=orange)
  [zig-ios-example🗒️Minimal build.zig for targeting iOS](https://github.com/kubkon/zig-ios-example) 
  - ![Star](https://img.shields.io/github/stars/jedisct1/zig-minisign?color=orange)
  [zig-minisign🗒️Minisign reimplemented in Zig](https://github.com/jedisct1/zig-minisign) 
  - ![Star](https://img.shields.io/github/stars/staltz/zig-nodejs-example?color=orange)
  [zig-nodejs-example🗒️Node.js Native Module written in Zig](https://github.com/staltz/zig-nodejs-example) 
  - ![Star](https://img.shields.io/github/stars/Arwalk/zig-protobuf?color=orange)
  [zig-protobuf🗒️a protobuf 3 implementation for zig](https://github.com/Arwalk/zig-protobuf) 
  - ![Star](https://img.shields.io/github/stars/gsquire/zig-snappy?color=orange)
  [zig-snappy🗒️Snappy compression for Zig](https://github.com/gsquire/zig-snappy) 
  
## Libraries

- ### Database Operation

  - ![Star](https://img.shields.io/github/stars/lithdew/lmdb-zig?color=orange)
  [lithdew/lmdb-zig🗒️Lightweight, fully-featured, idiomatic cross-platform Zig bindings to Lightning Memory-Mapped Database (LMDB)](https://github.com/lithdew/lmdb-zig) 
  - ![Star](https://img.shields.io/github/stars/vrischmann/zig-sqlite?color=orange)
  [zig-sqlite🗒️zig-sqlite is a small wrapper around sqlite's C API, making it easier to use with Zig](https://github.com/vrischmann/zig-sqlite) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/zdb?color=orange)
  [zdb🗒️Allocator-free document oriented database management](https://github.com/ziglibs/zdb) 
  - ![Star](https://img.shields.io/github/stars/nektro/zig-sqlite3?color=orange)
  [zig-sqlite3🗒️sqlite3 wrapper for Zig](https://github.com/nektro/zig-sqlite3) 

- ### Encryption & Encoding & Decoding

  - ![Star](https://img.shields.io/github/stars/brentp/hts-zig?color=orange)
  [hts-zig🗒️ziglang + htslib](https://github.com/brentp/hts-zig) 
  - ![Star](https://img.shields.io/github/stars/iddev5/inon?color=orange)
  [inon🗒️Data serialization format in Zig](https://github.com/iddev5/inon) 
  - ![Star](https://img.shields.io/github/stars/Hejsil/mecha?color=orange)
  [mecha🗒️A parser combinator library for Zig](https://github.com/Hejsil/mecha) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/s2s?color=orange)
  [s2s🗒️A zig binary serialization format](https://github.com/ziglibs/s2s) 
  - ![Star](https://img.shields.io/github/stars/shiguredo/tls13-zig?color=orange)
  [tls13-zig🗒️The first TLS1.3 implementation in Zig(master/HEAD) only with std](https://github.com/shiguredo/tls13-zig) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/uuencode?color=orange)
  [uuencode🗒️Unix-To-Unix-Encoding for Zig](https://github.com/ziglibs/uuencode) 
  - ![Star](https://img.shields.io/github/stars/andrewrk/xml?color=orange)
  [xm🗒️Tokenize XML](https://github.com/andrewrk/xml) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/wavefront-obj?color=orange)
  [wavefront-obj🗒️A parser for wavefront object files](https://github.com/ziglibs/wavefront-obj) 
  - ![Star](https://img.shields.io/github/stars/fengb/zasp?color=orange)
  [zasp🗒️zasp ⚡ a streaming parser](https://github.com/fengb/zasp) 
  - ![Star](https://img.shields.io/github/stars/alexnask/zdwg?color=orange)
  [zaml🗒️Fast YAML 1.2 parsing library for Python 3](https://github.com/adamserafini/zaml) 
  - ![Star](https://img.shields.io/github/stars/adamserafini/zaml?color=orange)
  [zdwg🗒️Read, manipulate, write AutoCad DWG files in zig](https://github.com/alexnask/zdwg) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/zig-args?color=orange)
  [zig-args🗒️Simple-to-use argument parser with struct-based config](https://github.com/MasterQ32/zig-args) 
  - ![Star](https://img.shields.io/github/stars/jedisct1/zig-charm?color=orange)
  [zig-charm🗒️A Zig version of the Charm crypto library](https://github.com/jedisct1/zig-charm) 
  - ![Star](https://img.shields.io/github/stars/mitchellh/zig-libxml2?color=orange)
  [zig-libxml2🗒️libxml2 built using Zig build system](https://github.com/mitchellh/zig-libxml2) 
  - ![Star](https://img.shields.io/github/stars/leroycep/zig-tzif?color=orange)
  [zig-tzif🗒️TZif parsing for Zig](https://github.com/leroycep/zig-tzif) 
  - ![Star](https://img.shields.io/github/stars/LewisGaul/zig-nestedtext?color=orange)
  [zig-nestedtext🗒️Zig NestedText parser library - a simple human readable data format based on YAML](https://github.com/LewisGaul/zig-nestedtext) 
  - ![Star](https://img.shields.io/github/stars/ifreund/zig-wayland?color=orange)
  [zig-wayland🗒️Zig wayland scanner and libwayland bindings](https://github.com/ifreund/zig-wayland) 
  - ![Star](https://img.shields.io/github/stars/xyaman/zjson?color=orange)
  [zjson🗒️Minimal json library with zero allocations](https://github.com/xyaman/zjson) 

- ### Game Dev & GUI Dev & Media Framework

  - ![Star](https://img.shields.io/github/stars/EvWilson/2jz?color=orange)
  [2jz🗒️An archetype-based entity-component-system library written in Zig](https://github.com/EvWilson/2jz) 
  - ![Star](https://img.shields.io/github/stars/Kiakra/Alka?color=orange)
  [Alka🗒️Simple, fast, easy to get started mid-level game engine written in Zig](https://github.com/Kiakra/Alka) 
  - ![Star](https://img.shields.io/github/stars/squeek502/audiometa?color=orange)
  [audiometa🗒️An audio metadata/tag reading library written in Zig](https://github.com/squeek502/audiometa) 
  - ![Star](https://img.shields.io/github/stars/capy-ui/capy?color=orange)
  [capy🗒️Cross-platform library for making true native GUIs in Zig](https://github.com/capy-ui/capy) 
  - ![Star](https://img.shields.io/github/stars/bootradev/cupcake?color=orange)
  [cupcake🗒️an app framework for making small and delicious games! (very wip)](https://github.com/bootradev/cupcake) 
  - ![Star](https://img.shields.io/github/stars/zenith391/didot?color=orange)
  [didot🗒️Zig 3D game engine](https://github.com/zenith391/didot) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/fontaine?color=orange)
  [fontaine🗒️A library to support text rendering in arbitrary contexts](https://github.com/ziglibs/fontaine) 
  - ![Star](https://img.shields.io/github/stars/david-vanderson/gui?color=orange)
  [gui](https://github.com/david-vanderson/gui) 
  - ![Star](https://img.shields.io/github/stars/batiati/IUPforZig?color=orange)
  [IUPforZig🗒️Zig idiomatic and type-checked bindings for IUP Portable User Interface Toolkit](https://github.com/batiati/IUPforZig) 
  - ![Star](https://img.shields.io/github/stars/kassane/libvlc-zig?color=orange)
  [libvlc-zig🗒️Zig bindings for libVLC media framework](https://github.com/kassane/libvlc-zig) 
  - ![Star](https://img.shields.io/github/stars/hexops/mach?color=orange)
  [mach🗒️Mach is a game engine & graphics toolkit for the future](https://github.com/hexops/mach) 
  - ![Star](https://img.shields.io/github/stars/TM35-Metronome/metronome?color=orange)
  [metronome🗒️A set of tools for modifying and randomizing Pokémon games](https://github.com/TM35-Metronome/metronome) 
  - ![Star](https://img.shields.io/github/stars/ashpil/moonshine?color=orange)
  [moonshine🗒️A general purpose ray traced renderer built with Zig + Vulkan](https://github.com/ashpil/moonshine) 
  - ![Star](https://img.shields.io/github/stars/dundalek/notcurses-zig-example?color=orange)
  [notcurses-zig-example🗒️Demo showing how to use Notcurses library for building terminal UIs with Zig](https://github.com/dundalek/notcurses-zig-example) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/painterz?color=orange)
  [painterz🗒️Low-level implementation of different painting primitives (lines, rectangles, ...) without specialization on a certain draw target](https://github.com/ziglibs/painterz) 
  - ![Star](https://img.shields.io/github/stars/kassane/qml_zig?color=orange)
  [qml_zig🗒️QML bindings for the Zig programming language](https://github.com/kassane/qml_zig) 
  - ![Star](https://img.shields.io/github/stars/raysan5/raylib?color=orange)
  [raylib-zig🗒️Manually tweaked, auto generated raylib bindings for zig. https://github.com/raysan5/raylib](https://github.com/Not-Nik/raylib-zig) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/SDL.zig?color=orange)
  [SDL.zig🗒️A shallow wrapper around SDL that provides object API and error handling](https://github.com/MasterQ32/SDL.zig) 
  - ![Star](https://img.shields.io/github/stars/leroycep/seizer?color=orange)
  [seizer🗒️Cross platform Zig library for obtaining a rendering context and loading assets](https://github.com/leroycep/seizer) 
  - ![Star](https://img.shields.io/github/stars/JonSnowbd/slingworks?color=orange)
  [slingworks🗒️Small to Medium scale 2d Game Engine for Zig](https://github.com/JonSnowbd/slingworks) 
  - ![Star](https://img.shields.io/github/stars/dantecatalfamo/sndio-zig?color=orange)
  [sndio-zig🗒️sndio bindings for zig](https://github.com/dantecatalfamo/sndio-zig) 
  - ![Star](https://img.shields.io/github/stars/TM35-Metronome/tm35-nds?color=orange)
  [tm35-nds🗒️A library for working with Nintendo DS roms](https://github.com/TM35-Metronome/tm35-nds) 
  - ![Star](https://img.shields.io/github/stars/omaraaa/VecFns?color=orange)
  [VecFns🗒️Automatic Vector Math Functions In Zig](https://github.com/omaraaa/VecFns) 
  - ![Star](https://img.shields.io/github/stars/Snektron/vulkan-zig?color=orange)
  [vulkan-zig🗒️Vulkan binding generator for Zig](https://github.com/Snektron/vulkan-zig) 
  - ![Star](https://img.shields.io/github/stars/aduros/wasm4?color=orange)
  [wasm4🗒️Build retro games using WebAssembly for a fantasy console](https://github.com/aduros/wasm4) 
  - ![Star](https://img.shields.io/github/stars/kooparse/zalgebra?color=orange)
  [zalgebra🗒️Linear algebra library for games and real-time graphics](https://github.com/kooparse/zalgebra) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/zero-graphics?color=orange)
  [zero-graphics🗒️Application framework based on OpenGL ES 2.0. Runs on desktop machines, Android phones and the web](https://github.com/MasterQ32/zero-graphics) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/zgl?color=orange)
  [zgl🗒️Zig OpenGL Wrapper](https://github.com/ziglibs/zgl) 
  - ![Star](https://img.shields.io/github/stars/Iridescence-Technologies/zglfw?color=orange)
  [zglfw🗒️A thin, idiomatic wrapper for GLFW. Written in Zig, for Zig!](https://github.com/Iridescence-Technologies/zglfw) 
  - ![Star](https://img.shields.io/github/stars/Iridescence-Technologies/zglfw?color=orange)
  [zig-gamedev-lib🗒️xq's Zig Game Development Library](https://github.com/Iridescence-Technologies/zglfw) 
  - ![Star](https://img.shields.io/github/stars/michal-z/zig-gamedev?color=orange)
  [zig-gamedev🗒️Building game development ecosystem for @ziglang!](https://github.com/michal-z/zig-gamedev) 
  - ![Star](https://img.shields.io/github/stars/danielabbott/Zig-Game-Engine?color=orange)
  [Zig-Game-Engine](https://github.com/danielabbott/Zig-Game-Engine) 
  - ![Star](https://img.shields.io/github/stars/prime31/zig-gamekit?color=orange)
  [zig-gamekit🗒️Companion repo for zig-renderkit for making 2D games](https://github.com/prime31/zig-gamekit) 
  - ![Star](https://img.shields.io/github/stars/wendigojaeger/ZigGBA?color=orange)
  [ZigGBA🗒️Work in progress SDK for creating Game Boy Advance games using Zig programming language](https://github.com/wendigojaeger/ZigGBA) 
  - ![Star](https://img.shields.io/github/stars/SpexGuy/Zig-Gltf-Display?color=orange)
  [Zig-Gltf-Display🗒️A program that displays glTF files using Vulkan, written in Zig](https://github.com/SpexGuy/Zig-Gltf-Display) 
  - ![Star](https://img.shields.io/github/stars/zigimg/zigimg?color=orange)
  [zigimg🗒️Zig library for reading and writing different image formats](https://github.com/zigimg/zigimg) 
  - ![Star](https://img.shields.io/github/stars/zPSP-Dev/Zig-PSP?color=orange)
  [Zig-PSP🗒️A project to bring the Zig Programming Language to the Sony PlayStation Portable!](https://github.com/zPSP-Dev/Zig-PSP) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/zig-qoi?color=orange)
  [zig-qoi🗒️Quite OK Image format encoder/decoder written in Zig](https://github.com/MasterQ32/zig-qoi) 
  - ![Star](https://img.shields.io/github/stars/prime31/zig-renderkit?color=orange)
  [zig-renderkit🗒️Cross platform Zig graphics backends with a 2D focus](https://github.com/prime31/zig-renderkit) 
  - ![Star](https://img.shields.io/github/stars/andrewrk/zig-sdl?color=orange)
  [zig-sdl🗒️self-contained SDL2 package for Zig](https://github.com/andrewrk/zig-sdl) 
  - ![Star](https://img.shields.io/github/stars/Guigui220D/zig-sfml-wrapper?color=orange)
  [zig-sfml-wrapper🗒️A zig wrapper for csfml](https://github.com/Guigui220D/zig-sfml-wrapper) 
  - ![Star](https://img.shields.io/github/stars/nektro/zig-tracy?color=orange)
  [zig-tracy🗒️Zig bindings for the Tracy profiler](https://github.com/nektro/zig-tracy) 
  - ![Star](https://img.shields.io/github/stars/prime31/zig-upaya?color=orange)
  [zig-upaya🗒️Zig-based framework for creating game tools and helper apps](https://github.com/prime31/zig-upaya) 
  - ![Star](https://img.shields.io/github/stars/andrewrk/zig-window?color=orange)
  [zig-window🗒️window client library](https://github.com/andrewrk/zig-window) 
  - ![Star](https://img.shields.io/github/stars/swaywm/zig-wlroots?color=orange)
  [zig-wlroots🗒️Zig bindings for wlroots](https://github.com/swaywm/zig-wlroots) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/zlm?color=orange)
  [zlm🗒️Zig linear mathemathics](https://github.com/ziglibs/zlm) 
  - ![Star](https://img.shields.io/github/stars/jack-ji/zplay?color=orange)
  [zplay🗒️A simple framework intended for game/tool creation](https://github.com/jack-ji/zplay) 
  - ![Star](https://img.shields.io/github/stars/JonSnowbd/ZT?color=orange)
  [ZT🗒️A zig based Imgui Application framework](https://github.com/JonSnowbd/ZT) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/zwin?color=orange)
  [zwin🗒️Making windows with Zig! (Only works on Windows at the moment)](https://github.com/ziglibs/zwin) 
  - ![Star](https://img.shields.io/github/stars/Aransentin/ZWL?color=orange)
  [ZWL🗒️Zig Windowing Library](https://github.com/Aransentin/ZWL) 

- ### Language Bindings

  - ![Star](https://img.shields.io/github/stars/dantecatalfamo/mruby-zig?color=orange)
  [mruby-zig🗒️mruby bindings for zig](https://github.com/dantecatalfamo/mruby-zig) 
  - ![Star](https://img.shields.io/github/stars/dantecatalfamo/wren-zig?color=orange)
  [wren-zig🗒️wren bindings for zig](https://github.com/dantecatalfamo/wren-zig) 
  - ![Star](https://img.shields.io/github/stars/daurnimator/zig-autolua?color=orange)
  [zig-autolua🗒️Lua binding creator for zig](https://github.com/daurnimator/zig-autolua) 
  - ![Star](https://img.shields.io/github/stars/mitchellh/zig-objc?color=orange)
  [zig-objc🗒️Objective-C runtime bindings for Zig (Zig calling ObjC)](https://github.com/mitchellh/zig-objc) 

- ### Terminal & Low-Level Libraries & System API

  - ![Star](https://img.shields.io/github/stars/ziglibs/ansi-term?color=orange)
  [ansi-term🗒️Zig library for dealing with ANSI terminals](https://github.com/ziglibs/ansi-term) 
  - ![Star](https://img.shields.io/github/stars/jayschwa/dos.zig?color=orange)
  [dos.zig🗒️Create DOS programs with Zig](https://github.com/jayschwa/dos.zig) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/known-folders?color=orange)
  [known-folders🗒️Provides access to well-known folders across several operating systems](https://github.com/ziglibs/known-folders) 
  - ![Star](https://img.shields.io/github/stars/joachimschmidt557/linenoize?color=orange)
  [linenoize🗒️A port of linenoise to zig](https://github.com/joachimschmidt557/linenoize) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/lscolors?color=orange)
  [lscolors🗒️A zig library for colorizing paths according to LS_COLORS](https://github.com/ziglibs/lscolors) 
  - ![Star](https://img.shields.io/github/stars/xyaman/mibu?color=orange)
  [mibu🗒️Pure Zig library for low-level terminal manipulation](https://github.com/xyaman/mibu) 
  - ![Star](https://img.shields.io/github/stars/fabioarnold/nfd-zig?color=orange)
  [nfd-zig🗒️OS-native file dialogs on Linux, macOS and Windows](https://github.com/fabioarnold/nfd-zig) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/TextEditor?color=orange)
  [TextEditor🗒️A backbone for text editors. No rendering, no input, but everything else](https://github.com/MasterQ32/TextEditor) 
  - ![Star](https://img.shields.io/github/stars/momumi/x86-zig?color=orange)
  [x86-zig🗒️library for assembling x86 in zig (WIP)](https://github.com/momumi/x86-zig) 
  - ![Star](https://img.shields.io/github/stars/PrajwalCH/yazap?color=orange)
  [yazap🗒️A simple and easy-to-use zig library for parsing command line arguments, flags and subcommands](https://github.com/PrajwalCH/yazap) 
  - ![Star](https://img.shields.io/github/stars/Hejsil/zig-clap?color=orange)
  [zig-clap🗒️Simple command line argument parsing library](https://github.com/Hejsil/zig-clap) 
  - ![Star](https://img.shields.io/github/stars/kubkon/ZigKit?color=orange)
  [ZigKit🗒️Zig bindings for low-level macOS frameworks](https://github.com/kubkon/ZigKit) 
  - ![Star](https://img.shields.io/github/stars/Gonzih/zigra?color=orange)
  [zigra🗒️Command line toolkit for Zig](https://github.com/Gonzih/zigra) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/zig-serial?color=orange)
  [zig-serial🗒️Serial port configuration library for Zig](https://github.com/MasterQ32/zig-serial) 
  - ![Star](https://img.shields.io/github/stars/marlersoft/zigwin32?color=orange)
  [zigwin32🗒️Autogenerated Zig bindings for Win32](https://github.com/marlersoft/zigwin32) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/zig-windows-console?color=orange)
  [zig-windows-console🗒️Zig Windows Console stuff](https://github.com/ziglibs/zig-windows-console) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/zinput?color=orange)
  [zinput🗒️A Zig command-line input library!](https://github.com/ziglibs/zinput) 

- ### Universal

  - #### Algorithms & Data Structures

    - ![Star](https://img.shields.io/github/stars/DutchGhost/ArrayVec?color=orange)
  [ArrayVec🗒️An array with a vector feeling in Zig](https://github.com/DutchGhost/ArrayVec) 
    - ![Star](https://img.shields.io/github/stars/travisstaloch/art.zig?color=orange)
  [art.zig🗒️An Adaptive Radix Tree ported from c](https://github.com/travisstaloch/art.zig) 
    - ![Star](https://img.shields.io/github/stars/alexnask/ctregex.zig?color=orange)
  [ctregex.zig🗒️Compile time regular expressions in zig](https://github.com/alexnask/ctregex.zig) 
    - ![Star](https://img.shields.io/github/stars/Vexu/comptime_hash_map?color=orange)
  [comptime_hash_map🗒️A statically initiated HashMap](https://github.com/Vexu/comptime_hash_map) 
    - ![Star](https://img.shields.io/github/stars/emekoi/deque.zig?color=orange)
  [deque.zig🗒️a lock free chase-lev deque for zig](https://github.com/emekoi/deque.zig) 
    - ![Star](https://img.shields.io/github/stars/hexops/fastfilter?color=orange)
  [fastfilter🗒️fastfilter:Binary fuse & xor filters for Zig (faster and smaller than bloom filters)](https://github.com/hexops/fastfilter) 
    - ![Star](https://img.shields.io/github/stars/ziglibs/funzig?color=orange)
  [funzig🗒️Fun functional functionality for Zig!](https://github.com/ziglibs/funzig) 
    - ![Star](https://img.shields.io/github/stars/judofyr/ish?color=orange)
  [ish🗒️Sketches for Zig](https://github.com/judofyr/ish) 
    - ![Star](https://img.shields.io/github/stars/kristoff-it/redis-cuckoofilter?color=orange)
  [it/redis-cuckoofilter🗒️Hashing-function agnostic Cuckoo filters for Redis](https://github.com/kristoff-it/redis-cuckoofilter) 
    - ![Star](https://img.shields.io/github/stars/BraedonWooding/Lazy-Zig?color=orange)
  [Lazy-Zig🗒️Linq in Zig](https://github.com/BraedonWooding/Lazy-Zig) 
    - ![Star](https://img.shields.io/github/stars/BarabasGitHub/LZig4?color=orange)
  [LZig4🗒️Implementing lz4 in zig](https://github.com/BarabasGitHub/LZig4) 
    - ![Star](https://img.shields.io/github/stars/judofyr/minz?color=orange)
  [minz🗒️Minimal string compression](https://github.com/judofyr/minz) 
    - ![Star](https://img.shields.io/github/stars/ziglibs/string-searching?color=orange)
  [string-searching🗒️String(not limited to [] const u8)-searching algorithms in zig](https://github.com/ziglibs/string-searching) 
    - ![Star](https://img.shields.io/github/stars/Sahnvour/zig-containers?color=orange)
  [zig-containers🗒️A container library for Zig](https://github.com/Sahnvour/zig-containers) 
    - ![Star](https://img.shields.io/github/stars/kristoff-it/zig-cuckoofilter?color=orange)
  [zig-cuckoofilter🗒️Production-ready Cuckoo Filters for any C ABI compatible target](https://github.com/kristoff-it/zig-cuckoofilter) 
    - ![Star](https://img.shields.io/github/stars/mitchellh/zig-graph?color=orange)
  [zig-graph🗒️Directed graph data structure for Zig](https://github.com/mitchellh/zig-graph) 
    - ![Star](https://img.shields.io/github/stars/vrischmann/zig-prometheus?color=orange)
  [zig-prometheus🗒️Prometheus/VictoriaMetrics client library for Zig](https://github.com/vrischmann/zig-prometheus) 
    - ![Star](https://img.shields.io/github/stars/Srekel/zig-sparse-set?color=orange)
  [zig-sparse-set🗒️Sparse sets for zig, supporting both SOA and AOS style](https://github.com/Srekel/zig-sparse-set) 
    - ![Star](https://img.shields.io/github/stars/jecolon/zigstr?color=orange)
  [zigstr🗒️Zigstr is a UTF-8 string type for Zig programs](https://github.com/jecolon/zigstr) 
    - ![Star](https://img.shields.io/github/stars/JakubSzark/zig-string?color=orange)
  [zig-string🗒️A String Library made in Zig](https://github.com/JakubSzark/zig-string) 
    - ![Star](https://img.shields.io/github/stars/ziglibs/zigfp?color=orange)
  [zigfp🗒️Basic fixed point implementation in Zig](https://github.com/ziglibs/zigfp) 
    - ![Star](https://img.shields.io/github/stars/shunkeen/zignite?color=orange)
  [zignite🗒️A lazy stream (iterator) library for Zig](https://github.com/shunkeen/zignite) 
    - ![Star](https://img.shields.io/github/stars/marijnfs/zigtimsort?color=orange)
  [zigtimsort🗒️TimSort implementation for Zig](https://github.com/marijnfs/zigtimsort) 
    - ![Star](https://img.shields.io/github/stars/judofyr/zini?color=orange)
  [zini🗒️Minimal perfect hash function for Zig](https://github.com/judofyr/zini) 
    - ![Star](https://img.shields.io/github/stars/Hejsil/ziter?color=orange)
  [ziter🗒️Best iterator library for Zig (fight me!)](https://github.com/Hejsil/ziter) 
    - [znum🗒️Simple numeric tower implemented on Zig standard types](https://hg.sr.ht/~hutzdog/Zcheme/browse/znum?rev=tip)
    - ![Star](https://img.shields.io/github/stars/ziglibs/zorm?color=orange)
  [zorm🗒️Lightweight and efficient object-relational mapping](https://github.com/ziglibs/zorm) 
    - ![Star](https://img.shields.io/github/stars/AliChraghi/zort?color=orange)
  [zort🗒️Implementation of 9 sorting algorithms in Zig](https://github.com/AliChraghi/zort) 
    - ![Star](https://img.shields.io/github/stars/gruebite/zzz?color=orange)
  [zzz🗒️Simple and boring human readable data format for Zig](https://github.com/gruebite/zzz) 

  - #### Memory Management

    - ![Star](https://img.shields.io/github/stars/suirad/adma?color=orange)
  [adma🗒️A general purpose, multithreaded capable slab allocator for Zig](https://github.com/suirad/adma) 
    - ![Star](https://img.shields.io/github/stars/suirad/Seal?color=orange)
  [Seal🗒️An allocator that wraps another allocator and detects if memory is leaked after usage](https://github.com/suirad/Seal) 
    - ![Star](https://img.shields.io/github/stars/hmusgrave/zcirc?color=orange)
  [zcirc🗒️A dynamic circular buffer allocator for zig](https://github.com/hmusgrave/zcirc) 
    - ![Star](https://img.shields.io/github/stars/fengb/zee_alloc?color=orange)
  [zee_alloc🗒️tiny Zig allocator primarily targeting WebAssembly](https://github.com/fengb/zee_alloc) 
    - ![Star](https://img.shields.io/github/stars/mdsteele/ziegfried?color=orange)
  [ziegfried🗒️A general-purpose memory allocator for Zig](https://github.com/mdsteele/ziegfried) 
    - ![Star](https://img.shields.io/github/stars/mitchellh/zig-libgc?color=orange)
  [zig-libgc🗒️Zig-friendly library for interfacing with libgc (bdwgc) -- the Boehm-Demers-Weiser conservative garbage collector](https://github.com/mitchellh/zig-libgc) 
    - ![Star](https://img.shields.io/github/stars/yrashk/zig-rcsp?color=orange)
  [zig-rcsp🗒️Reference-counted Shared Pointer for Zig](https://github.com/yrashk/zig-rcsp) 

  - #### Other Universal Libraries

    - ![Star](https://img.shields.io/github/stars/saltzm/async_io_uring?color=orange)
  [async_io_uring🗒️An event loop in Zig using io_uring and coroutines](https://github.com/saltzm/async_io_uring) 
    - ![Star](https://img.shields.io/github/stars/ziglibs/comptemplate?color=orange)
  [comptemplate](https://github.com/ziglibs/comptemplate) 
    - ![Star](https://img.shields.io/github/stars/ziglibs/diffz?color=orange)
  [diffz🗒️Implementation of go-diff's diffmatchpatch in Zig](https://github.com/ziglibs/diffz) 
    - ![Star](https://img.shields.io/github/stars/getty-zig/getty?color=orange)
  [getty🗒️Serialization framework for Zig](https://github.com/getty-zig/getty) 
    - ![Star](https://img.shields.io/github/stars/alexnask/interface.zig?color=orange)
  [interface.zig🗒️Dynamic dispatch for zig made easy](https://github.com/alexnask/interface.zig) 
    - ![Star](https://img.shields.io/github/stars/mitchellh/libxev?color=orange)
  [libxev🗒️libxev is a cross-platform, high-performance event loop that provides abstractions for non-blocking IO, timers, events, and more and works on Linux (io_uring or epoll), macOS (kqueue), and Wasm + WASI. Available as both a Zig and C API](https://github.com/mitchellh/libxev) 
    - ![Star](https://img.shields.io/github/stars/emekoi/log.zig?color=orange)
  [log.zig🗒️a thread-safe logging library for zig](https://github.com/emekoi/log.zig) 
    - ![Star](https://img.shields.io/github/stars/alexnask/PeerType?color=orange)
  [PeerType🗒️Zig peer type resolution at comptime, ported from the compiler source code](https://github.com/alexnask/PeerType) 
    - ![Star](https://img.shields.io/github/stars/floooh/sokol-zig?color=orange)
  [sokol-zig🗒️Zig bindings for the sokol headers (https://github.com/floooh/sokol)](https://github.com/floooh/sokol-zig) 
    - [trace.zig🗒️A small and simple tracing client library for Zig](https://gitlab.com/zig_tracing/trace.zig)
    - ![Star](https://img.shields.io/github/stars/kprotty/zap?color=orange)
  [zap🗒️An asynchronous runtime with a focus on performance and resource efficiency](https://github.com/kprotty/zap) 
    - ![Star](https://img.shields.io/github/stars/frmdstryr/zig-datetime?color=orange)
  [zig-datetime🗒️A date and time module for Zig](https://github.com/frmdstryr/zig-datetime) 
    - ![Star](https://img.shields.io/github/stars/nektro/zig-extras?color=orange)
  [zig-extras🗒️An assortment of random utility functions that aren't in std and don't deserve their own pacakge](https://github.com/nektro/zig-extras) 
    - ![Star](https://img.shields.io/github/stars/yrashk/zig-generator?color=orange)
  [zig-generator🗒️Async generator type for Zig](https://github.com/yrashk/zig-generator) 
    - ![Star](https://img.shields.io/github/stars/nektro/zig-leven?color=orange)
  [zig-leven🗒️Measure the difference between two slices using the Levenshtein distance algorithm](https://github.com/nektro/zig-leven) 
    - ![Star](https://img.shields.io/github/stars/jecolon/ziglyph?color=orange)
  [ziglyph🗒️Unicode text processing for the Zig programming language](https://github.com/jecolon/ziglyph) 
    - ![Star](https://img.shields.io/github/stars/nektro/zig-range?color=orange)
  [zig-range🗒️A range function to loop over an index without an extra variable](https://github.com/nektro/zig-range) 
    - ![Star](https://img.shields.io/github/stars/tiehuis/zig-regex?color=orange)
  [zig-regex🗒️A regex implementation for the zig programming language](https://github.com/tiehuis/zig-regex) 
    - ![Star](https://img.shields.io/github/stars/nektro/zig-time?color=orange)
  [zig-time🗒️A date and time parsing and formatting library for Zig](https://github.com/nektro/zig-time) 
    - ![Star](https://img.shields.io/github/stars/nektro/zig-ulid?color=orange)
  [zig-ulid🗒️A binary implementation of ULID in Zig](https://github.com/nektro/zig-ulid) 
    - ![Star](https://img.shields.io/github/stars/ranciere/zoltan?color=orange)
  [zoltan🗒️A Sol-inspired minimalist Lua binding for Zig](https://github.com/ranciere/zoltan) 

- ### Web

  - ![Star](https://img.shields.io/github/stars/Luukdegram/apple_pie?color=orange)
  [apple_pie🗒️Basic HTTP server implementation in Zig](https://github.com/Luukdegram/apple_pie) 
  - ![Star](https://img.shields.io/github/stars/kubkon/espresso-zig?color=orange)
  [espresso-zig🗒️Zig bindings for espresso C library](https://github.com/kubkon/espresso-zig) 
  - ![Star](https://img.shields.io/github/stars/malcolmstill/foxwren?color=orange)
  [foxwren🗒️A WebAssembly runtime in zig](https://github.com/malcolmstill/foxwren) 
  - ![Star](https://img.shields.io/github/stars/ducdetronquito/h11?color=orange)
  [h11🗒️I/O agnostic HTTP/1.1 implementation for Zig ](https://github.com/ducdetronquito/h11) 
  - ![Star](https://img.shields.io/github/stars/kivikakk/htmlentities.zig?color=orange)
  [htmlentities.zig🗒️HTML entity data for Zig](https://github.com/kivikakk/htmlentities.zig) 
  - ![Star](https://img.shields.io/github/stars/ducdetronquito/http?color=orange)
  [http🗒️HTTP core types for Zig 🦴](https://github.com/ducdetronquito/http) 
  - ![Star](https://img.shields.io/github/stars/euantorano/ip.zig?color=orange)
  [ip.zig🗒️A Zig library for working with IP Addresses](https://github.com/euantorano/ip.zig) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/positron?color=orange)
  [positron🗒️A web renderer frontend for zig applications](https://github.com/ziglibs/positron) 
  - ![Star](https://img.shields.io/github/stars/chwayne/rem?color=orange)
  [rem🗒️An HTML parsing library, written in Zig](https://github.com/chwayne/rem) 
  - ![Star](https://img.shields.io/github/stars/Vexu/routez?color=orange)
  - [routez🗒️Http server for Zig](https://github.com/Vexu/routez) 
  - ![Star](https://img.shields.io/github/stars/lithdew/snow?color=orange)
  [snow🗒️A small, fast, cross-platform, async Zig networking framework built on top of lithdew/pike](https://github.com/lithdew/snow) 
  - ![Star](https://img.shields.io/github/stars/zigwasm/wasmer-zig?color=orange)
  [wasmer-zig🗒️Zig bindings for the Wasmer WebAssembly runtime](https://github.com/zigwasm/wasmer-zig) 
  - ![Star](https://img.shields.io/github/stars/zigwasm/wasmtime-zig?color=orange)
  [wasmtime-zig🗒️Zig embedding of Wasmtime](https://github.com/zigwasm/wasmtime-zig) 
  - ![Star](https://img.shields.io/github/stars/zigwasm/wasm-zig?color=orange)
  [wasm-zig🗒️Common Wasm runtime binding to C API](https://github.com/zigwasm/wasm-zig) 
  - ![Star](https://img.shields.io/github/stars/fengb/wazm?color=orange)
  [wazm🗒️Web Assembly Zig Machine](https://github.com/fengb/wazm) 
  - ![Star](https://img.shields.io/github/stars/truemedian/wz?color=orange)
  [wz🗒️An I/O agnostic WebSocket 1.3 library for Zig](https://github.com/truemedian/wz) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/zCOM?color=orange)
  [zCOM🗒️A composable network protocol stack for embedded and desktop](https://github.com/ziglibs/zCOM) 
  - ![Star](https://img.shields.io/github/stars/frmdstryr/zhp?color=orange)
  [zhp🗒️A Http server written in Zig](https://github.com/frmdstryr/zhp) 
  - ![Star](https://img.shields.io/github/stars/lun-4/zigdig?color=orange)
  [zigdig🗒️naive dns client library in zig](https://github.com/lun-4/zigdig) 
  - ![Star](https://img.shields.io/github/stars/dantecatalfamo/zig-dns?color=orange)
  [zig-dns🗒️Experimental DNS library implemented in zig](https://github.com/dantecatalfamo/zig-dns) 
  - ![Star](https://img.shields.io/github/stars/jedisct1/zigly?color=orange)
  [zigly🗒️The easiest way to write services for Fastly's Compute@Edge in Zig](https://github.com/jedisct1/zigly) 
  - ![Star](https://img.shields.io/github/stars/MasterQ32/zig-network?color=orange)
  [zig-network🗒️A smallest-common-subset of socket functions for crossplatform networking, TCP & UDP](https://github.com/MasterQ32/zig-network) 
  - ![Star](https://img.shields.io/github/stars/nektro/zig-oauth2?color=orange)
  [zig-oauth2🗒️HTTP handler functions to allow you to easily add OAuth2 login support to your Zig application](https://github.com/nektro/zig-oauth2) 
  - ![Star](https://img.shields.io/github/stars/fubark/zig-v8?color=orange)
  - [zig-v8🗒️Simple V8 builds with C and Zig bindings](https://github.com/fubark/zig-v8) 

- ### Other Libraries

  - ![Star](https://img.shields.io/github/stars/ziglibs/antiphony?color=orange)
  [antiphony🗒️A zig remote procedure call solution](https://github.com/ziglibs/antiphony) 
  - ![Star](https://img.shields.io/github/stars/mitchellh/libflightplan?color=orange)
  [libflightplan🗒️A library for reading and writing flight plans in various formats. Available as both a C and Zig library](https://github.com/mitchellh/libflightplan) 
  - ![Star](https://img.shields.io/github/stars/christopher-hesse/tenet?color=orange)
  [tenet🗒️Automatic differentiation prototype in Zig](https://github.com/christopher-hesse/tenet) 
  - ![Star](https://img.shields.io/github/stars/Hejsil/zig-bench?color=orange)
  [zig-bench🗒️Simple benchmarking library](https://github.com/Hejsil/zig-bench) 
  - ![Star](https://img.shields.io/github/stars/ryoppippi/zigcv?color=orange)
  [zigcv🗒️zig bindings for OpenCV4](https://github.com/ryoppippi/zigcv) 
  - ![Star](https://img.shields.io/github/stars/kubkon/zig-dis-x86_64?color=orange)
  [zig-dis-x86_64🗒️x86_64 disassembler library written in Zig](https://github.com/kubkon/zig-dis-x86_64) 
  - ![Star](https://img.shields.io/github/stars/nektro/zig-docker?color=orange)
  [zig-docker🗒️Zig bindings for the Docker Engine API](https://github.com/nektro/zig-docker) 
  - ![Star](https://img.shields.io/github/stars/mattnite/zig-libcurl?color=orange)
  [zig-libcurl🗒️compile libcurl in your build.zig](https://github.com/mattnite/zig-libcurl) 
  - ![Star](https://img.shields.io/github/stars/ziglibs/zig-lv2?color=orange)
  [zig-lv2🗒️Zig-intuitive bindings for LV2](https://github.com/ziglibs/zig-lv2) 
  - ![Star](https://img.shields.io/github/stars/SasLuca/zig-nanoid?color=orange)
  [zig-nanoid🗒️A tiny, secure, URL-friendly, unique string ID generator. Now available in pure Zig](https://github.com/SasLuca/zig-nanoid) 
  - ![Star](https://img.shields.io/github/stars/nektro/zig-pek?color=orange)
  [zig-pek🗒️A comptime HTML preprocessor with a builtin template engine for Zig](https://github.com/nektro/zig-pek) 
  - ![Star](https://img.shields.io/github/stars/mattnite/zig-zlib?color=orange)
  [zig-zlib🗒️compile zlib in your build.zig](https://github.com/mattnite/zig-zlib) 


## Resources

**Content that has appeared in [Related Web Sites](#related-web-sites) will not appear here again** 

- ### [Community](https://github.com/ziglang/zig/wiki/Community)

- ### Introduction Or News
  
  - ![Views](https://img.shields.io/youtube/views/ZvskDoP09Ao)
  [Interview with Zig language creator Andrew Kelley - YouTube](https://www.youtube.com/watch?v=ZvskDoP09Ao) 
  - ![Views](https://img.shields.io/youtube/views/AqDdWEiSwMM)
  [Zig Roadmap 2023 - Andrew Kelley](https://www.youtube.com/watch?v=AqDdWEiSwMM) 
  - ![Views](https://img.shields.io/youtube/views/Gv2I7qTux7g)
  [The Road to Zig 1.0 - Andrew Kelley - YouTube](https://www.youtube.com/watch?v=Gv2I7qTux7g) 
  - ![Views](https://img.shields.io/youtube/views/ygfGO5n1Oe4)
  [Zig Programming Language - YouTube](https://www.youtube.com/watch?v=ygfGO5n1Oe4) 
  - ![Views](https://img.shields.io/youtube/channel/views/UC2EQzAewrC10KCDFSS4j-zA)
  [Zig SHOWTIME - YouTube](https://www.youtube.com/channel/UC2EQzAewrC10KCDFSS4j-zA) 
  - [Zig Star History](https://star-history.com/#ziglang/zig&Date)

- ### Learning


  - [Exercism exercises in Zig](https://github.com/exercism/zig)
  - ![Views](https://img.shields.io/youtube/views/O4UYT-brgrc)
  [Learning the Zig programming language with help from its creator and core team - YouTube](https://www.youtube.com/watch?v=O4UYT-brgrc) 
  - [learnopengl🗒️https://learnopengl.com tutorials ported to zig](https://github.com/cshenton/learnopengl)
  - [libc-to-zig🗒️Comparison between libc functions and their best fitting zig alternatives](https://github.com/zig-community/libc-to-zig)
  - ![Views](https://img.shields.io/youtube/views/vHWiDx_l4V0)
  [What's a Memory Allocator Anyway? - Benjamin Feng](https://www.youtube.com/watch?v=vHWiDx_l4V0) 
  - [zig-by-example.github.io🗒️learn Zig, by example](https://github.com/zig-by-example/zig-by-example.github.io)
  - ![Views](https://img.shields.io/youtube/views/8MbREuiLQrM)
  [Zig Compiler Internals - Andrew Kelley](https://www.youtube.com/watch?v=8MbREuiLQrM) 
  - [zig.internals🗒️An Unofficial Writeup on Zig Compiler Internals](https://github.com/mikdusan/zig.internals)
  - ![Views](https://img.shields.io/youtube/views/J6ZxxnSp_fY)
  [Zig language:a WAY better C! - YouTube](https://www.youtube.com/watch?v=J6ZxxnSp_fY) 
  - [Zig Language Reference](https://ziglang.org/documentation/master/)
  - [ziglearn🗒️Repo for https://ziglearn.org content. Get up to speed with Zig quickly](https://github.com/Sobeston/ziglearn)
  - [ziglings🗒️Learn the Zig programming language by fixing tiny broken programs](https://github.com/ratfactor/ziglings)
  - ![Views](https://img.shields.io/youtube/views/fQ08HMZLbCw)
  [Zig Programming Language Tutorials](https://www.youtube.com/watch?v=fQ08HMZLbCw&list=PLRMNjZSQLv5iGpjubyzlWYcGqiTPVyK3s) 
  - [Zig Standard Library Documentation](https://ziglang.org/documentation/master/std/)
  
## Algorithms and data structures
- [BarabasGitHub/LZig4](https://github.com/BarabasGitHub/LZig4) Implementing lz4 in zig.
- [DutchGhost/ArrayVec](https://github.com/DutchGhost/ArrayVec) An array with a vector feeling in Zig
- [emekoi/deque.zig](https://github.com/emekoi/deque.zig) a lock free chase-lev deque for zig
- [kristoff-it/zig-cuckoofilter](https://github.com/kristoff-it/zig-cuckoofilter) Production-ready Cuckoo Filters for any C ABI compatible target.
- [marijnfs/zigtimsort](https://github.com/marijnfs/zigtimsort) TimSort implementation for Zig
- [Sahnvour/zig-containers](https://github.com/Sahnvour/zig-containers) A container library for Zig.
- [Srekel/zig-sparse-set](https://github.com/Srekel/zig-sparse-set) Sparse sets for zig, supporting both SOA and AOS style
- [v1zix/zig-string](https://github.com/v1zix/zig-string) Strings for Zig

## Allocators
- [dbandstra/zig-hunk](https://github.com/dbandstra/zig-hunk) Basic stack allocator for Zig
- [fengb/zee_alloc](https://github.com/fengb/zee_alloc) tiny Zig allocator primarily targeting WebAssembly
- [mdsteele/ziegfried](https://github.com/mdsteele/ziegfried) A general-purpose memory allocator for Zig
- [suirad/Seal](https://github.com/suirad/Seal) An allocator that wraps another allocator and detects if memory is leaked after usage

## Audio
- [dbandstra/zang](https://github.com/dbandstra/zang) Audio synthesis for Zig
- [dbandstra/zig-wav](https://github.com/dbandstra/zig-wav)
- [Hejsil/zig-midi](https://github.com/Hejsil/zig-midi)

## Bootables
- [AndreaOrru/zen](https://github.com/AndreaOrru/zen) Experimental operating system written in Zig
- [andrewrk/clashos](https://github.com/andrewrk/clashos) multiplayer arcade game for bare metal Raspberry Pi 3 B+
- [andrewrk/HellOS](https://github.com/andrewrk/HellOS) "hello world" x86 kernel example
- [DorianXGH/Lukarnel](https://github.com/DorianXGH/Lukarnel) A microkernel in zig with rust microservices
- [iguessthislldo/georgios](https://github.com/iguessthislldo/georgios) Hobby Operating System
- [jzck/kernel-zig](https://github.com/jzck/kernel-zig) 💾 hobby x86 kernel zig
- [liampwll/zig-efi-os](https://github.com/liampwll/zig-efi-os)
- [markfirmware/zig-bare-metal-microbit](https://github.com/markfirmware/zig-bare-metal-microbit) Bare metal microbit program written in zig
- [markfirmware/zig-bare-metal-raspberry-pi](https://github.com/markfirmware/zig-bare-metal-raspberry-pi) Bare metal raspberry pi program written in zig
- [MasterQ32/RetrOS](https://github.com/MasterQ32/RetrOS) A retro-style gaming console running on bare x86 metal written in Zig
- [nrdmn/uefi-examples](https://github.com/nrdmn/uefi-examples) UEFI examples in Zig
- [nrdmn/uefi-paint](https://github.com/nrdmn/uefi-paint) UEFI-bootable touch paint app
- [SamTebbs33/pluto](https://github.com/SamTebbs33/pluto) An x86 kernel written in Zig
- [sjdh02/trOS](https://github.com/sjdh02/trOS) tiny aarch64 baremetal OS thingy
- [tralamazza/embedded_zig](https://github.com/tralamazza/embedded_zig) minimal Zig embedded ARM example (STM32F103 blue pill)
- [yvt/zig-armv8m-test](https://github.com/yvt/zig-armv8m-test) Example Zig-based app for Armv8-M + TrustZone
- [ZeeBoppityZagZiggity/ZBZZ.OS](https://github.com/ZeeBoppityZagZiggity/ZBZZ.OS) An operating system built with RISCV and Zig

## Compilers and interpreters
- [CurtisFenner/zsmol](https://github.com/CurtisFenner/zsmol) The new Smol compiler and reference.
- [squeek502/zua](https://github.com/squeek502/zua) An implementation of Lua 5.1 in Zig, for learning purposes
- [Vexu/bog](https://github.com/Vexu/bog) Small, strongly typed, embeddable language.

## Database
- [kristoff-it/redis-cuckoofilter](https://github.com/kristoff-it/redis-cuckoofilter) Hashing-function agnostic Cuckoo filters for Redis
- [kristoff-it/zig-okredis](https://github.com/kristoff-it/zig-okredis) Zero-allocation Client for Redis 6+
- [leroycep/sqlite-zig](https://github.com/leroycep/sqlite-zig)
- [vrischmann/zig-cassandra](https://github.com/vrischmann/zig-cassandra) Client for Cassandra 2.1+

## Editor plugins
- [ice1000/intellij-zig](https://github.com/ice1000/intellij-zig) The IntelliJ IDEA plugin for the Zig programming language ┗😃┛ ┏😃┓ ┗😃┛ ┏😃┓
- [isaachier/ztags](https://github.com/isaachier/ztags) ctags implementation for Zig written in Zig
- [Tetralux/sublime-zig](https://github.com/Tetralux/sublime-zig) My own, more lightweight, syntax highlighting for the Zig Programming Language.
- [ziglang/sublime-zig-language](https://github.com/ziglang/sublime-zig-language) Zig language support for Sublime Text
- [ziglang/vscode-zig](https://github.com/ziglang/vscode-zig) Zig language support for VSCode
- [ziglang/zig-mode](https://github.com/ziglang/zig-mode) Zig mode for Emacs
- [ziglang/zig.vim](https://github.com/ziglang/zig.vim) Vim configuration for Zig
- [zigtools/zls](https://github.com/zigtools/zls) Zig LSP implementation + Zig Language Server

## Emulators
- [emekoi/c8](https://github.com/emekoi/c8) chip 8 emulator in zig
- [fengb/fundude](https://github.com/fengb/fundude) Gameboy emulator: Zig -> wasm
- [GrooveStomp/chip8-zig](https://github.com/GrooveStomp/chip8-zig) CHIP-8 emulator in Zig
- [isaachier/gbemu](https://github.com/isaachier/gbemu) Zig Game Boy emulator
- [sourgrasses/fishnchips](https://github.com/sourgrasses/fishnchips) [WIP] 🐟 CHIP-8 emulator implemented in Zig for leeeearning
- [sourgrasses/ichigo](https://github.com/sourgrasses/ichigo) [WIP] 🍓 Virtual Boy emulator
- [Srekel/zag](https://github.com/Srekel/zag) Game dev project written in Zig and C
- [tiehuis/zig-gameboy](https://github.com/tiehuis/zig-gameboy) A gameboy emulator in zig

## Game tools and libraries
- [danielabbott/Game-Engine](https://github.com/danielabbott/Game-Engine)
- [emekoi/ziglet](https://github.com/emekoi/ziglet) a small zig game library
- [kristianhasselknippe/zig-game-engine](https://github.com/kristianhasselknippe/zig-game-engine) Learning zig through game engine
- [TM35-Metronome/metronome](https://github.com/TM35-Metronome/metronome) A set of tools for modifying and randomizing Pokémon games
- [TM35-Metronome/tm35-nds](https://github.com/TM35-Metronome/tm35-nds) A library for working with Nintendo DS roms
- [user00e00/sudokuinzig](https://github.com/user00e00/sudokuinzig)
- [wendigojaeger/ZigGBA](https://github.com/wendigojaeger/ZigGBA) Work in progress SDK for creating Game Boy Advance games using Zig programming language.

## Games
- [Akuli/curses-minesweeper](https://github.com/Akuli/curses-minesweeper) Minesweeper game written in curses with zig
- [andrewrk/clashos](https://github.com/andrewrk/clashos) multiplayer arcade game for bare metal Raspberry Pi 3 B+
- [andrewrk/tetris](https://github.com/andrewrk/tetris) A simple tetris clone written in zig programming language.
- [dbandstra/oxid](https://github.com/dbandstra/oxid) Arcade style game written in Zig
- [fabioarnold/snake-zig](https://github.com/fabioarnold/snake-zig)
- [Stenodyon/blink](https://github.com/Stenodyon/blink) A game about building logic with lasers
- [thejoshwolfe/legend-of-swarkland](https://github.com/thejoshwolfe/legend-of-swarkland) Hack-n-slash roguelike inspired by NetHack
- [tiehuis/zstack](https://github.com/tiehuis/zstack) Line-race tetris mode in Zig
- [kooparse/zalgebra](https://github.com/kooparse/zalgebra) Linear algebra library for games and real-time computer graphics.

## GUI
- [andrewrk/zig-mandelbrot-gl](https://github.com/andrewrk/zig-mandelbrot-gl) mandelbrot set in zig
- [andrewrk/zig-sdl](https://github.com/andrewrk/zig-sdl) self-contained SDL2 package for Zig
- [andrewrk/zig-vulkan-triangle](https://github.com/andrewrk/zig-vulkan-triangle) simple triangle displayed using vulkan, glfw, and zig
- [cshenton/learnopengl](https://github.com/cshenton/learnopengl) https://learnopengl.com tutorials ported to zig
- [dbandstra/zig-pcx](https://github.com/dbandstra/zig-pcx) Load and save PCX images in Zig
- [ifreund/river](https://github.com/ifreund/river) dynamic wayland compositor that takes inspiration from dwm and bspwm
- [Nelarius/weekend-raytracer-zig](https://github.com/Nelarius/weekend-raytracer-zig) A Zig implementation of the "Ray Tracing in One Weekend" book
- [SpexGuy/Zig-Gltf-Display](https://github.com/SpexGuy/Zig-Gltf-Display) A program that displays glTF files using Vulkan, written in Zig.
- [tiehuis/zig-raytrace](https://github.com/tiehuis/zig-raytrace) simple raytracer in zig
- [tiehuis/zig-sdl2](https://github.com/tiehuis/zig-sdl2) SDL2 bindings for Zig
- [winksaville/zig-3d-soft-engine](https://github.com/winksaville/zig-3d-soft-engine) An attempt to create a 3D engine in software using zig.

## Misc libraries
- [BraedonWooding/Lazy-Zig](https://github.com/BraedonWooding/Lazy-Zig) Linq in Zig
- [DutchGhost/maybeuninit](https://github.com/DutchGhost/maybeuninit) MaybeUninit in Zig.
- [emekoi/log.zig](https://github.com/emekoi/log.zig) a thread-safe logging library for zig.
- [gernest/time](https://github.com/gernest/time)
- [kprotty/zap](https://github.com/kprotty/zap) A collection of zig libraries which provide interfaces over the system for writing high performance applications
- [mlarouche/zigimg](https://github.com/mlarouche/zigimg) Zig library for reading and writing different image formats
- [ziglibs/known-folders](https://github.com/ziglibs/known-folders) Provides access to well-known folders across several operating systems

## Network
- [connectFree/ZigZag](https://github.com/connectFree/ZigZag) Noise Framework implementation in Zig Language for use in EVER/IP and WireGuard
- [ducdetronquito/h11](https://github.com/ducdetronquito/h11) I/O-free HTTP/1.1 implementation inspired by hyper/h11
- [euantorano/ip.zig](https://github.com/euantorano/ip.zig) A Zig library for working with IP Addresses
- [lun-4/zigdig](https://github.com/lun-4/zigdig) naive dns client library in zig
- [lun-4/ziget](https://github.com/lun-4/ziget) simple wget in zig without libc
- [marler8997/netpunch](https://github.com/marler8997/netpunch) Outbound proxy protocol
- [mstroecker/zig-robotstxt](https://github.com/mstroecker/zig-robotstxt) Lightweight docker image for serving a disallow robots.txt file using the zig programming language.
- [Vexu/routez](https://github.com/Vexu/routez) Http server for Zig
- [Vexu/zuri](https://github.com/Vexu/zuri) URI parser for Zig
- [remeh/statsd-zig](https://github.com/remeh/statsd-zig) Basic DogStatsD UDP server

## System tools
- [pbui-project/pbui-main](https://github.com/pbui-project/pbui-main) BSD/Linux core utilities written in Zig
- [hspak/brightnessztl](https://github.com/hspak/brightnessztl) A CLI to control device backlight
- [thejoshwolfe/hexdump-zip](https://github.com/thejoshwolfe/hexdump-zip) produce an annotated hexdump of a zipfile


## Other
- [andersfr/zig-lsp](https://github.com/andersfr/zig-lsp) Language Server Protocol for Zig
- [belse-de/zig-tut](https://github.com/belse-de/zig-tut) A collection of small projects and tutorials to learn ZIG; may it be inspiration for others as well.
- [donpdonp/zootdeck](https://github.com/donpdonp/zootdeck) Zootdeck Fediverse GTK Desktop Reader
- [fengb/zig-protobuf](https://github.com/fengb/zig-protobuf)
- [gernest/base32](https://github.com/gernest/base32) base32 encoding/decoding for ziglang
- [gernest/hoodie](https://github.com/gernest/hoodie) pure zig language server with swagger and bling bling
- [Hejsil/zig-gc](https://github.com/Hejsil/zig-gc) A super simple mark-and-sweep garbage collector written in Zig.
- [hspak/geteltorito-zig](https://github.com/hspak/geteltorito-zig) geteltorito re-write in Zig
- [lun-4/zig-docsearch](https://github.com/lun-4/zig-docsearch) search over zig stdlib doc comments (with rudimentary html gen)
- [MasterQ32/ZigPaint](https://github.com/MasterQ32/ZigPaint) A simple paint application written in Zig. Used to create an OpenGL loader/wrapper and a minimal UI system.
- [meta-leap/langserv](https://github.com/meta-leap/langserv) LSP implementation lib plus demo / dummy language server showcasing usage (WIP)
- [momumi/x86-zig](https://github.com/momumi/x86-zig) library for assembling x86 in zig (WIP)
- [nrdmn/ilo_license_key](https://github.com/nrdmn/ilo_license_key) iLO license key library
- [vegecode/svd2zig](https://github.com/vegecode/svd2zig) Convert System View Description (svd) files to Zig headers for baremetal development
- [zigtools/zpm](https://github.com/zigtools/zpm) Unofficial Zig package manager
- [Sobeston/ziglearn](https://github.com/Sobeston/ziglearn) Zig learning resources
- [mqttiotstuff/iotmonitor](https://github.com/mqttiotstuff/iotmonitor) Zig MQTT IotMonitor tools, save time to monitor mqtt agents or devices


## Parser
- [darithorn/zig-toml](https://github.com/darithorn/zig-toml) A TOML parser written in Zig
- [ducdetronquito/hppy](https://github.com/ducdetronquito/hppy) The happy HTML parser ᕕ( ᐛ )ᕗ
- [gernest/url](https://github.com/gernest/url)
- [goto-bus-stop/ziguid](https://github.com/goto-bus-stop/ziguid) GUID parsing/stringifying with zig
- [Hejsil/zig-clap](https://github.com/Hejsil/zig-clap) Simple command line argument parsing library
- [kivikakk/libpcre.zig](https://github.com/kivikakk/libpcre.zig) Bindings to libpcre for Perl-compatible regular expressions
- [kivikakk/koino](https://github.com/kivikakk/koino) CommonMark/GitHub Flavored Markdown parser and HTML renderer
- [m-r-hunt/tjp](https://github.com/m-r-hunt/tjp)
- [prostomarkeloff/zigini](https://github.com/prostomarkeloff/zigini) Simple, small (~220 loc) library for parsing .INI files in Zig.
- [tiehuis/zig-regex](https://github.com/tiehuis/zig-regex) A regex implementation for the zig programming language
- [tiehuis/zig-ryu](https://github.com/tiehuis/zig-ryu) Zig port of https://github.com/ulfjack/ryu
- [Vexu/zuri](https://github.com/Vexu/zuri) URI parser for Zig
- [vi/zigmkv](https://github.com/vi/zigmkv) [wip] Matroska/webm (mkv) parser in Zig
- [winksaville/zig-parse-args](https://github.com/winksaville/zig-parse-args) Parse command line arguments.
- [winksaville/zig-parse-number](https://github.com/winksaville/zig-parse-number) Implement ParseNumber which can parse any TypeId.Int or TypeId.Float.
- [demizer/markzig](https://github.com/demizer/markzig) Pure Zig Markdown Parser

## Web
- [andrewrk/lua-in-the-browser](https://github.com/andrewrk/lua-in-the-browser) using zig to build lua for webassembly
- [fengb/fundude](https://github.com/fengb/fundude) Gameboy emulator: Zig -> wasm
- [fengb/zee_alloc](https://github.com/fengb/zee_alloc) tiny Zig allocator primarily targeting WebAssembly
- [gernest/url](https://github.com/gernest/url)
- [kivikakk/htmlentities.zig](https://github.com/kivikakk/htmlentities.zig) HTML5 entity data.
- [meheleventyone/zig-wasm-test](https://github.com/meheleventyone/zig-wasm-test) A minimal Web Assembly example using Zig's build system.
- [shritesh/zig-wasm-dom](https://github.com/shritesh/zig-wasm-dom) Zig + WebAssembly + JS + DOM
- [shritesh/zigfmt-web](https://github.com/shritesh/zigfmt-web) zig fmt on the web
- [Vexu/routez](https://github.com/Vexu/routez) Http server for Zig
- 
# The End
