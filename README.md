# Awesome Gemini [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
A collection of awesome things regarding the [gemini protocol][1] ecosystem.

Please contribute to this list to link to all the awesome gemini projects out there.

Repo mirrors:
* https://git.sr.ht/~kr1sp1n/awesome-gemini
* https://github.com/kr1sp1n/awesome-gemini/

## What is Gemini

[Excerpt from gemini.circumlunar.space](https://gemini.circumlunar.space/docs/specification.html):

> Gemini is a client-server protocol featuring request-response transactions, broadly similar to gopher or HTTP.
  Connections are closed at the end of a single transaction and cannot be reused. When Gemini is served over TCP/IP, servers
  should listen on port 1965 (the first manned Gemini mission, Gemini 3, flew in March'65).
  This is an unprivileged port, so it's very easy to run a server as a "nobody" user, even if e.g. the server is written
  in Go and so can't drop privileges in the traditional fashion.

## Gemini Specification 

- [protocol](https://gitlab.com/gemini-specification/protocol)
- [gemini-text](https://gitlab.com/gemini-specification/gemini-text)

## Contents

- [Clients](#clients)
  - [Terminal](#terminal)
  - [Graphical](#graphical)
    - [Cross-platform](#cross-platform)
    - [Mobile](#mobile)
    - [Windows](#windows)
- [Programming](#programming)
- [Resources](#resources)
- [Servers](#servers)
- [Services](#services)
- [Tools](#tools)
- [Web proxies](#web-proxies)
- [Bots](#bots)

## Clients

### Terminal
- [Amfora](https://github.com/makeworld-the-better-one/amfora) (Go) - "fancy" terminal client.
- [Asuka](https://git.sr.ht/~julienxx/asuka) (Rust) - an NCurses-based Gemini client.
- [AV-98](https://tildegit.org/solderpunk/AV-98) (Python) - Gemini client derived from the popular VF-1 Gopher client.
- [bollux](https://sr.ht/~acdw/bollux/) (Bash) - bash Gemini client.
- [bombadillo](https://rawtext.club/~sloum/bombadillo.html) (Go) - combined Gopher, Gemini, Finger, and File client with vim-inspired key mappings.
- [cgmnlm](https://src.clttr.info/rwa/cgmnlm) (C) - colorful gemini line-mode client, fork of gmni.
- [diohsc](https://mbays.sdf.org/diohsc/) (Haskell) - simple line-based command-response terminal user interface with ANSI colour.
- [Elpher](https://thelambdalab.xyz/elpher/) (Emacs) - combined Gopher and Gemini client for the popular text editor / operating system.
- [gem.awk](git://git.vgx.fr/gem.awk) (Awk) - minimal but usable interactive Gemini client in < 250 LOC of Awk.
- [gembro](https://git.sr.ht/~rafael/gembro) (Go) - gemini client using [Bubble Tea](https://github.com/charmbracelet/bubbletea).
- [gemini-demo-1](https://tildegit.org/solderpunk/gemini-demo-1) (Python) - minimal but usable interactive Gemini client in < 100 LOC of Python 3.
- [gemini-demo-2](https://tildegit.org/solderpunk/gemini-demo-2) (Lua) - minimal but usable interactive Gemini client in < 100 LOC of Lua.
- [gemini-demo-3](https://tildegit.org/solderpunk/gemini-demo-3) (Go) - minimal but usable interactive Gemini client in not quite < 100 LOC of Go.
- [gemini-fetch](https://github.com/RangerMauve/gemini-fetch) (Node.js) - cURL-like CLI for loading content from Gemini URLs.
- [gmni](https://sr.ht/~sircmpwn/gmni/) (C) - CLI utility (like curl) and line-mode browser.
- [Gremlin](https://github.com/actuday6418/gremlin) (Rust) - TUI for browsing Gemini space
- [min](https://github.com/a-h/min) (Go) - supports advanced features like input and client certificate generation.
- [ncgopher](https://github.com/jansc/ncgopher) (Rust) - gopher and gemini client for the modern internet.
- [tinmop](https://www.autistici.org/interzona/tinmop.html) (Common Lisp) - opinionated Mastodon and Gemini client

### Graphical
#### Cross-platform
- [Agregore](https://github.com/RangerMauve/agregore-browser#fetch-api-for-gemini) - (Electron.js) - peer to peer web browser with support for loading Gemini pages.
- [Alrisha](https://git.sr.ht/~fabrixxm/alrisha) (QML) - QML-based Gemini client.
- [Castor](https://git.sr.ht/~julienxx/castor) (Rust) - graphical Gemini client using GTK.
- [Fafi](https://git.sr.ht/~soapdog/fafi-browser) (Racket) - graphical Gemini browser written in Racket.
- [Fossil](https://github.com/koyuspace/fossil) (Vala) - GTK3 Gemini browser written in Vala for desktop and mobile.
- [Lagrange](https://git.skyjake.fi/skyjake/lagrange) (C) - desktop GUI client with inline image viewing, multiple tabs, bookmarks and more.
- [Moonlander](https://sr.ht/~admicos/moonlander/) (Rust) - the fanciest Gemini client in the entire solar system.
- [Kristall](https://github.com/MasterQ32/kristall) (C++) - graphical Gopher and Gemini client using QT.
- [spacewar](https://github.com/ResonAtom/spacewar) (Electron.js) - Gemini browser running on Electron.

#### Mobile
- [Ariane](https://oppen.digital/software/ariane/) (Kotlin/Java) - Gemini protocol client for Android based OS.
- [Deedum](https://github.com/snoe/deedum) (Dart) - an Android and iOS client made with Flutter.
- [Elaho](https://github.com/pitr/gemini-ios) (Swift) - full featured Gemini protocol browser for iOS.
- [Gem](https://open-store.io/app/gem.aaron) (Python) - Gemini client for Ubuntu Touch.
- [Xenia](https://gitlab.com/tslocum/xenia) (Java) - Gemini proxy for Android.
- [Phaedra](https://oppen.digital/software/phaedra/) (Java) - Gemini client for Android supporting even very old ones; author recommends using Ariana if a current Android is at hand.

#### Windows
- [GemiNaut](https://www.marmaladefoo.com/pages/geminaut) (C#) - user friendly graphical Gemini client for MS Windows.

## Programming
- [gemclient](https://github.com/Koshroy/gemclient) (Nim) - rich client library for the Gemini Protocol.
- [derhuerst/gemini](https://github.com/derhuerst/gemini) (Node.js) - server & client lib.
- [a-h/gemini](https://github.com/a-h/gemini) (Go) - Applications and libraries for building applications on Gemini.
- [cuipod](https://github.com/aegis-dev/cuipod) (C#) - Simple yet flexible framework for Gemini protocol server.
- [go-gemini](https://git.sr.ht/~yotam/go-gemini) (Go) - library that provides an easy interface to create client and servers.
- [go-gemini](https://github.com/makeworld-the-better-one/go-gemini) (Go) - more recent fork of the library above.
- [gig](https://github.com/pitr/gig) (Go) - Gemini framework.
- [ignition](https://github.com/cbrews/ignition) (Python) - Gemini client transport/request library for python3.
- [Agunua](https://framagit.org/bortzmeyer/agunua) (Python) - Gemini library to write clients. Includes IRI support, gemtext parsing and CLI tool.
- [kaksik](https://github.com/sergetymo/kaksik) (Deno/TypeScript) - middleware library for building server applications.
- [ruby-net-text](https://git.umaneti.net/ruby-net-text/) (Ruby) - Gemini support in Net::* and URI::* stack.
- [warmuuh/jemini](https://github.com/warmuuh/jemini/tree/main/gemini-client)(Java) - reactive gemini-client, part of jemini-project
- 
## Resources
- [Gemini Specification](https://gemini.circumlunar.space/docs/specification.html) - the Gemini protocol specification.
- [gemini.circumlunar.space/software](https://portal.mozz.us/gemini/gemini.circumlunar.space/software/) - list of Gemini software.
- [transjovian.org/gemini](https://transjovian.org/gemini/) - wiki space dedicated to Gemini communities and software.

## Servers
- [Agate](https://github.com/mbrubeck/agate) (Rust) - simple Gemini server for static files.
- [Apogee](https://github.com/bunburya/apogee) (Kotlin) - Gemini server written in Kotlin for the JVM.
- [a-h/gemini](https://github.com/a-h/gemini) (Go) - Server for Linux, Mac, Raspberry Pi. Supports SNI for multiple domains on the same server, has Docker image.
- [blizanci](https://github.com/mk270/blizanci) (Erlang) - server designed primarily for robustness and security.
- [Denoscuri](https://github.com/caranatar/denoscuri) (Typescript) - simple Gemini server written using Deno and Typescript.
- [Dʒɛmɪni](https://sr.ht/~rwv/dezhemini/) (Racket) - server with features like SNI and CGI.
- [Diamant](https://git.umaneti.net/diamant/) (Ruby) - simple Gemini server for static files.
- [Doppio](https://github.com/bhavanki/doppio) (Java) - single-JAR Gemini server with CGI, authentication, and Atom feed support.
- [Duckling proxy 🦆](https://portal.mozz.us/gemini/gemini.marmaladefoo.com/blog/31-Aug-2020_The_Duckling_Proxy.gmi) (Go) - scheme-specific filtering proxy for Gemini clients to access the web.
- [Earl Server](https://github.com/mrletourneau/EarlServer) (Kotlin) - Gemini fileserver for the JVM.
- [Ergol](http://adele.work/code/ergol/ergol.gmi) (PHP) - light Gemini server able to host several capsules with different cerificates.
- [GeGoBi](https://tildegit.org/solderpunk/gegobi) (Python) - server to facilitate easy Gemini-Gopher bi-hosting.
- [Gemeaux](https://github.com/brunobord/gemeaux) (Python) - server using only the Python standard library.
- [gemini-ipfs-gateway](https://git.sr.ht/~hsanjuan/gemini-ipfs-gateway) (Go) - an IPFS Gateway that makes IPFS content available over the Gemini protocol.
- [gemini-server](https://hackage.haskell.org/package/gemini-server) (Haskell) - lightweight server for the Gemini protocol.
- [geminid](https://github.com/jovoro/geminid/) (C) - Gemini Server in C.
- [geminid](https://www.upyum.com/cgit.cgi/geminid) (Scheme) - Gemini Server in CHICKEN Scheme.
- [gemini-php](https://opensource.glasgow.social/gemini-php) (PHP) - simple Gemini server in PHP.
- [JAGS-php](https://github.com/codeandcreate/JAGS-PHP) (PHP) - fork of gemini-php with support of dynamic pages.
- [geminim](https://github.com/ardek66/geminim) (Nim) - an async lightweight Gemini server made in Nim.
- [gmid](https://github.com/omar-polo/gmid) (C) - simple and secure Gemini server.
- [gmnisrv](https://sr.ht/~sircmpwn/gmnisrv/) (C) - high-performance Gemini server for POSIX systems.
- [Gemserv](https://portal.mozz.us/gemini/80h.dev/projects/gemserv/) (Rust) - server with features like vhosts, CGI, SCGI, reverse-proxying and more.
- [Germinal](https://github.com/jfmcbrayer/germinal) (Common Lisp) - serves any type of document with an appropriate mime type.
- [GLV-1.12556](https://github.com/spc476/GLV-1.12556) (Lua) - the first Gemini protocol server with a lot of features.
- [Hydepark](https://github.com/spektom/hydepark) (Rust) - discussion forum application for Gemini.
- [Jetforce](https://github.com/michael-lazar/jetforce) (Python) - built-in static file server with support for gemini directories and CGI scripts.
- [warmuuh/jemini](https://github.com/warmuuh/jemini)(Java) - dual gemini/http server on top of jetty with spring-boot integration
- [Lupa Pona](https://github.com/kensanata/lupa-pona) (Perl) - simple single directory Gemini server.
- [Marami](https://github.com/MagnificentPako/Marami/) (Prolog) - server written in Prolog.
- [Molly Brown](https://tildegit.org/solderpunk/molly-brown) (Go) - full-featured Gemini server implemented in Go.
- [MoonGem](https://sr.ht/~panda-roux/MoonGem) (C) - gemini server with inline Lua scripting for dynamic content generation.
- [net-gemini](https://github.com/jackdoe/net-gemini) (Go) - gemini server inspired by Molly Brown.
- [northstar](https://github.com/panicbit/northstar) (Rust) - gemini server implementation.
- [Orbit](https://tildegit.org/sumpygump/orbit) (PHP) - Gemini server implemented in PHP.
- [Phoebe](https://alexschroeder.ch/cgit/phoebe/about/) (Perl) - Gemini/web wiki.
- [pollux](https://git.sr.ht/~julienxx/pollux) (Rust) - simple server that will only serve one `index.gemini` file.
- [rc-gemd](https://sr.ht/~moody/rc-gemd) (Shell) - simple Gemini server written in rc (for plan9 operating systems).
- [Satellite](https://sr.ht/~gsthnz/satellite/) (Go) - small Gemini server for serving static files.
- [Shavit](https://git.sr.ht/~yotam/shavit) (Go) - configurable Gemini server for UNIX operating systems.
- [Space-Age](https://gitlab.com/lambdatronic/space-age) (Clojure) - Gemini server written in Clojure.
- [Taurus](https://git.sr.ht/~garritfra/taurus)(Rust) - A Concurrent Gemini Server.
- [Titan](https://github.com/jahzielv/titan) (Rust) - simple TOML-configured Gemini server and an Express-like Gemini server framework.
- [twins](https://gitlab.com/tslocum/twins) (Go) - YAML-configured Gemini server supporting vhosts, FastCGI and reverse-proxying.
- [vger](https://tildegit.org/solene/vger) (C) - Gemini server written in C used with inetd.

## Services
- __gemini://drewdevault.com/cgi-bin/man.sh__ - look up a POSIX man page.
- __gemini://flounder.online__ ([https version](https://flounder.online/)) - host small Gemini web pages over https and Gemini ([repo](https://github.com/alexwennerberg/flounder)).
- __gemini://geminispace.info__ - public search provider for Gemini ([repo](https://src.clttr.info/rwa/geminispace.info)).
- __gemini://geddit.glv.one__ - interactive link service (with comments).
- __gemini://glv.one__ - free platform as a service (PaaS) that runs any Gemini server (packaged as a Docker image) in the cloud.
- __gemini://gus.guru/__ - Gemini Universal Search ([repo](https://natpen.net/code/gus)).
- __gemini://gemini.omarpolo.com/cgi/gempkg/__ - interface for the OpenBSD ports collection.
- __gemini://tictactoe.lanterne.chilliet.eu__ - Tic Tac Toe game ([repo](https://framagit.org/MCMic/gemini-tictactoe)).
- __gemini://ur.gs/__ - translate from en->es and es->en ([repo](https://code.ur.gs/lupine/capsule/src/branch/main/src/cgi-bin/translate)).
- __gemini://rawtext.club/~sloum/geminews/__ - Daily news feeds proxied to gemini.
- __gemini://rawtext.club/~sloum/cgi/othello/__ - Play othello/reversi against a computer opponent over gemini.
- __gemini://rawtext.club/~sloum/cgi/weather__ - US weather reports by zip code.
- [gemlog.blue](https://gemlog.blue) - Gemini hosting from a web frontend.


## Tools
- [CAPCOM](https://tildegit.org/solderpunk/CAPCOM) (Python) - Atom feed aggregator for gemini.
- [certified](https://code.lag.net/robey/certified) (Python) - Generate TOFU TLS certificates for gemini servers.
- [cl-yag](git://bitreich.org/cl-yag) (Common-Lisp) - Static site generator producing gemini, gopher and html.
- [comitium](https://git.nytpu.com/comitium) (C) - A feed aggregator for gemini supporting many formats and protocols.
- [gemini-pandoc-lua-filter](https://github.com/kr1sp1n/gemini-pandoc-lua-filter) (Lua) - lua filter for pandoc to output Gemini text.
- [gemini-to-html](https://github.com/RangerMauve/gemini-to-html) (Node.js) - JavaScript library for parsing Gemini pages, and for rendering them to HTML.
- [geminize](https://addons.mozilla.org/en-US/firefox/addon/geminize/) - Firefox addon that redirects gemini:// URLs and links to a customizable HTTP-to-Gemini proxy.
- [gemlog.sh](https://git.nytpu.com/gemlog.sh/about/) (Bash) - Utility for writing and managing gemini logs (gemlogs) and atom feeds (simple gemini static site generator/framework).
- [gem.git](https://git.sr.ht/~fkfd/git.gmi/) (Python) - git frontend CGI script.
- [gemini_http](https://github.com/cyevgeniy/gemini_http) (Go) - simple tool for viewing gemini files that are placed on a http server.
- [gemmit](https://github.com/t-900-a/gemmit) (Go) - social news aggregation and web content rating website for the gemini protocol.
- [gemtexter](https://github.com/snonux/gemtexter) (Bash) - Site generator and blog engine for Gemini. Generates Atom and Gemfeeds , and also does Gemtext to HTML and Markdown conversion.
- [gloggery](https://github.com/kconner/gloggery) (Go) - basic static site generator for blogs in Gemini.
- [gmitohtml](https://gitlab.com/tslocum/gmitohtml) (Go) - proxy that renders Gemini pages using HTML.
- [gmi2html](https://github.com/shtanton/gmi2html) (Zig) - tiny gemtext to HTML converter with a focus on performance.
- [gmi2html](gemini://gemini.thegonz.net/gmi2html.sed) (Sed) - sed script to convert text/gemini to html.
- [gmi-web](https://codeberg.org/talon/gmi-web) (JS) - generate _semantic_ HTML styled for readability and mobile-friendliness.
- [gmnhg](https://git.tdem.in/tdemin/gmnhg) (Go) - renders a Hugo site to a Gemini site.
- [gssg](https://git.sr.ht/~gsthnz/gssg) (Go) - simple gemini static site generator. Generates pages, index and atom feeds.
- [Html2GeminiPy](https://github.com/Aarontheissueguy/Html2GeminiPy) (Python) - Converts Html sites to Gemini sites using markdownify and md2gemini.
- [kiln](https://git.sr.ht/~adnano/kiln) (Go) - simple static site generator for Gemini sites.
- [Lupa](https://framagit.org/bortzmeyer/lupa) - crawler to explore the geminispace and make statistics (you can see them at __gemini://gemini.bortzmeyer.org/software/lupa/stats.gmi ).
- [Manisha](https://framagit.org/bortzmeyer/manisha) - Nagios (and compatible, such as Icinga) plugin to monitor Gemini servers.
- [md2gmn](https://git.tdem.in/tdemin/gmnhg) (Go) - renders Markdown text to Gemini pages.
- [md2gemini](https://github.com/makeworld-the-better-one/md2gemini) (Python) - converter from Markdown to the Gemini text format.
- [spacewalk](https://tildegit.org/sloum/spacewalk) (Go) - Page-hash based feed aggregator for gemini.
- [MastoGem](https://git.rdelaage.ovh/rdelaage/mastoGem) (Go) - Mastodon proxy for Gemini.
- [Hugo-2-Gopher-and-Gemini](https://github.com/mkamarin/Hugo-2-Gopher-and-Gemini) (Python) - A Hugo theme to convert a Hugo site to Gemini or Gopher.
- [Gopher-and-Gemini-Walker](https://github.com/mkamarin/Gopher-and-Gemini-Walker) (Python) - Terminal client (without network connectivity) to navigate a folder structure containing a Gemini capsule or Gopher hole.

### Syntax Highlighting
- [gemini-vim-syntax](https://tildegit.org/sloum/gemini-vim-syntax) - text/gemini syntax highlighting for vim.
- [gemini.el](https://git.carcosa.net/jmcbray/gemini.el) - text/gemini syntax highlighting for emacs.
- [gemini.kak](https://github.com/kakoune-editor/kakoune-extra-filetypes/blob/master/rc/gemini.kak) - text/gemini syntax highlighting for kakoune.
- [gemini.nanorc](https://github.com/yzzyx-network/nanorc/blob/master/gemini.nanorc) - text/gemini syntax highlighting for nano.
- [gemini.sublime-syntax](https://github.com/adiabatic/gemini.sublime-syntax) - text/gemini syntax highlighting for bat (and maybe Sublime Text).
- [gemini.yml](https://github.com/zyedidia/micro/blob/master/runtime/syntax/gemini.yaml) - text/gemini syntax highlighting for micro.

## Web proxies
- [Mozz.us portal](https://portal.mozz.us/gemini/gemini.circumlunar.space/)
- [Soweli Lukin](https://alexschroeder.ch/soweli-lukin)
- [Vulpes proxy](https://proxy.vulpes.one/gemini/gemini.circumlunar.space/)

## Bots
- [Fortune Teller Bot](https://github.com/t-900-a/gemini-fortune-bot) - Generates a fortune gmi file, gemlog/index.gmi, and atom.xml every time the bot is executed

---
[1]: https://gemini.circumlunar.space/
