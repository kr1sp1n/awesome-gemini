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

## Clients

### Terminal
- [Amfora](https://github.com/makeworld-the-better-one/amfora) (Go) - a "fancy" terminal client.
- [Asuka](https://git.sr.ht/~julienxx/asuka) (Rust) - an NCurses-based Gemini client.
- [AV-98](https://tildegit.org/solderpunk/AV-98) (Python) - a Gemini client derived from the popular VF-1 Gopher client.
- [bollux](https://sr.ht/~acdw/bollux/) (Bash) - a bash Gemini client.
- [bombadillo](https://rawtext.club/~sloum/bombadillo.html) (Go) - a combined Gopher, Gemini, Finger, and File client with vim-inspired key mappings.
- [cgmnlm](https://src.clttr.info/rwa/cgmnlm) (C) - colorful gemini line-mode client, fork of gmni
- [diohsc](https://mbays.sdf.org/diohsc/) (Haskell) - a simple line-based command-response terminal user interface with ANSI colour.
- [Elpher](https://thelambdalab.xyz/elpher/) (Emacs) - a combined Gopher and Gemini client for the popular text editor / operating system.
- [gemini-demo-1](https://tildegit.org/solderpunk/gemini-demo-1) (Python) - a minimal but usable interactive Gemini client in < 100 LOC of Python 3.
- [gemini-demo-2](https://tildegit.org/solderpunk/gemini-demo-2) (Lua) - a minimal but usable interactive Gemini client in < 100 LOC of Lua.
- [gemini-demo-3](https://tildegit.org/solderpunk/gemini-demo-3) (Go) - a minimal but usable interactive Gemini client in not quite < 100 LOC of Go.
- [gemini-fetch](https://github.com/RangerMauve/gemini-fetch) (Node.js) - a cURL-like CLI for loading content from Gemini URLs.
- [gmni](https://sr.ht/~sircmpwn/gmni/) (C) - a CLI utility (like curl) and a line-mode browser.
- [min](https://github.com/a-h/min) (Go) - supports advanced features like input and client certificate generation.
- [ncgopher](https://github.com/jansc/ncgopher) (Rust) - a gopher and gemini client for the modern internet.

### Graphical
#### Cross-platform
- [Agregore](https://github.com/RangerMauve/agregore-browser#fetch-api-for-gemini) - (Electron.js) - a peer to peer web browser with support for loading Gemini pages.
- [Alrisha](https://git.sr.ht/~fabrixxm/alrisha) (QML) - QML-based Gemini client.
- [Castor](https://git.sr.ht/~julienxx/castor) (Rust) - a graphical Gemini client using GTK.
- [Fafi](https://git.sr.ht/~soapdog/fafi-browser) (Racket) - a graphical Gemini browser written in Racket.
- [Lagrange](https://git.skyjake.fi/skyjake/lagrange) (C) - a desktop GUI client with inline image viewing, multiple tabs, bookmarks and more.
- [Moonlander](https://sr.ht/~admicos/moonlander/) (Rust) - the fanciest Gemini client in the entire solar system.
- [Kristall](https://github.com/MasterQ32/kristall) (C++) - a graphical Gopher and Gemini client using QT.
- [spacewar](https://github.com/ResonAtom/spacewar) (Electron.js) - a Gemini browser running on Electron.

#### Mobile
- [Ariane](https://oppen.digital/software/ariane/) (Kotlin/Java) - a Gemini protocol client for Android based OS.
- [Deedum](https://github.com/snoe/deedum) (Dart) - an Android and iOS client made with Flutter.
- [Elaho](https://github.com/pitr/gemini-ios) (Swift) - a full featured Gemini protocol browser for iOS.
- [Xenia](https://gitlab.com/tslocum/xenia) (Java) - a Gemini proxy for Android.
- [Phaedra](https://oppen.digital/software/phaedra/) (Java) - Gemini client for Android supporting even very old ones; author recommends using Ariana if a current Android is at hand.

#### Windows
- [GemiNaut](https://www.marmaladefoo.com/pages/geminaut) (C#) - a user friendly graphical Gemini client for MS Windows.

## Programming
- [gemclient](https://github.com/Koshroy/gemclient) (Nim) - a rich client library for the Gemini Protocol.
- [derhuerst/gemini](https://github.com/derhuerst/gemini) (Node.js) - a server & client lib.
- [a-h/gemini](https://github.com/a-h/gemini) (Go) - Applications and libraries for building applications on Gemini.
- [cuipod](https://github.com/aegis-dev/cuipod) (C#) - Simple yet flexible framework for Gemini protocol server.
- [go-gemini](https://git.sr.ht/~yotam/go-gemini) (Go) - a library that provides an easy interface to create client and servers.
- [go-gemini](https://github.com/makeworld-the-better-one/go-gemini) (Go) - a more recent fork of the library above.
- [gig](https://github.com/pitr/gig) (Go) - a Gemini framework.
- [ignition](https://github.com/cbrews/ignition) (Python) - a Gemini client transport/request library for python3.
- [Agunua](https://framagit.org/bortzmeyer/agunua) (Python) - a Gemini library to write clients. Includes IRI support, gemtext parsing and a CLI tool.
- [kaksik](https://github.com/sergetymo/kaksik) (Deno/TypeScript) - middleware library for building server applications.
- [ruby-net-text](https://git.umaneti.net/ruby-net-text/) (Ruby) - Gemini support in Net::* and URI::* stack.

## Resources
- [Gemini Specification](https://gemini.circumlunar.space/docs/specification.html) - the Gemini protocol specification.
- [gemini.circumlunar.space/software](https://portal.mozz.us/gemini/gemini.circumlunar.space/software/) - a list of Gemini software.
- [transjovian.org/gemini](https://transjovian.org/gemini/) - a wiki space dedicated to Gemini communities and software.

## Servers
- [Agate](https://github.com/mbrubeck/agate) (Rust) - a simple Gemini server for static files.
- [a-h/gemini](https://github.com/a-h/gemini) (Go) - Server for Linux, Mac, Raspberry Pi. Supports SNI for multiple domains on the same server, has Docker image.
- [blizanci](https://github.com/mk270/blizanci) (Erlang) - a server designed primarily for robustness and security.
- [Denoscuri](https://github.com/caranatar/denoscuri) (Typescript) - a simple Gemini server written using Deno and Typescript.
- [Dʒɛmɪni](https://sr.ht/~rwv/dezhemini/) (Racket) - a server with features like SNI and CGI.
- [Diamant](https://git.umaneti.net/diamant/) (Ruby) - a simple Gemini server for static files.
- [Duckling proxy 🦆](https://portal.mozz.us/gemini/gemini.marmaladefoo.com/blog/31-Aug-2020_The_Duckling_Proxy.gmi) (Go) - a scheme-specific filtering proxy for Gemini clients to access the web.
- [Earl Server](https://github.com/mrletourneau/EarlServer) (Kotlin) - a Gemini fileserver for the JVM.
- [Ergol](http://adele.work/code/ergol/ergol.gmi) (PHP) - a light Gemini server able to host several capsules with different cerificates.
- [GeGoBi](https://tildegit.org/solderpunk/gegobi) (Python) - a server to facilitate easy Gemini-Gopher bi-hosting.
- [Gemeaux](https://github.com/brunobord/gemeaux) (Python) - a Server using only the Python standard library.
- [gemini-ipfs-gateway](https://git.sr.ht/~hsanjuan/gemini-ipfs-gateway) (Go) - an IPFS Gateway that makes IPFS content available over the Gemini protocol.
- [gemini-server](https://hackage.haskell.org/package/gemini-server) (Haskell) - a lightweight server for the Gemini protocol.
- [geminid](https://github.com/jovoro/geminid/) (C) - a Gemini Server in C.
- [geminid](https://www.upyum.com/cgit.cgi/geminid) (Scheme) - a Gemini Server in CHICKEN Scheme.
- [gemini-php](https://opensource.glasgow.social/gemini-php) (PHP) - a simple Gemini server in PHP.
- [JAGS-php](https://github.com/codeandcreate/JAGS-PHP) (PHP) - fork of gemini-php with support of dynamic pages.
- [geminim](https://github.com/ardek66/geminim) (Nim) - an async lightweight Gemini server made in Nim.
- [gmnisrv](https://sr.ht/~sircmpwn/gmnisrv/) (C) - a high-performance Gemini server for POSIX systems.
- [Gemserv](https://portal.mozz.us/gemini/80h.dev/projects/gemserv/) (Rust) - a server with features like vhosts, CGI, SCGI, reverse-proxying and more.
- [Germinal](https://github.com/jfmcbrayer/germinal) (Common Lisp) - serves any type of document with an appropriate mime type.
- [GLV-1.12556](https://github.com/spc476/GLV-1.12556) (Lua) - the first Gemini protocol server with a lot of features.
- [Jetforce](https://github.com/michael-lazar/jetforce) (Python) - a built-in static file server with support for gemini directories and CGI scripts.
- [Lupa Pona](https://github.com/kensanata/lupa-pona) (Perl) - a simple single directory Gemini server.
- [Marami](https://github.com/MagnificentPako/Marami/) (Prolog) - a server written in Prolog.
- [Molly Brown](https://tildegit.org/solderpunk/molly-brown) (Go) - a full-featured Gemini server implemented in Go.
- [net-gemini](https://github.com/jackdoe/net-gemini) (Go) - a gemini server inspired by Molly Brown.
- [northstar](https://github.com/panicbit/northstar) (Rust) - a gemini server implementation.
- [Orbit](https://tildegit.org/sumpygump/orbit) (PHP) - a Gemini server implemented in PHP.
- [Phoebe](https://alexschroeder.ch/cgit/phoebe/about/) (Perl) - a Gemini/web wiki.
- [pollux](https://git.sr.ht/~julienxx/pollux) (Rust) - a simple server that will only serve one `index.gemini` file.
- [Satellite](https://sr.ht/~gsthnz/satellite/) (Go) - a small Gemini server for serving static files.
- [Shavit](https://git.sr.ht/~yotam/shavit) (Go) - a configurable Gemini server for UNIX operating systems.
- [Space-Age](https://gitlab.com/lambdatronic/space-age) (Clojure) - a Gemini server written in Clojure.
- [Titan](https://github.com/jahzielv/titan) (Rust) - a simple TOML-configured Gemini server and an Express-like Gemini server framework.
- [twins](https://gitlab.com/tslocum/twins) (Go) - a YAML-configured Gemini server supporting vhosts, FastCGI and reverse-proxying.
- [vger](https://tildegit.org/solene/vger) (C) - Gemini server written in C used with inetd

## Services
- __gemini://drewdevault.com/cgi-bin/man.sh__ - look up a POSIX man page.
- __gemini://flounder.online__ ([https version](https://flounder.online/)) - host small Gemini web pages over https and Gemini ([repo](https://github.com/alexwennerberg/flounder)).
- __gemini://geminispace.info__ - public search provider for Gemini ([repo](https://src.clttr.info/rwa/geminispace.info)).
- __gemini://geddit.glv.one__ - interactive link service (with comments).
- __gemini://glv.one__ - a free platform as a service (PaaS) that runs any Gemini server (packaged as a Docker image) in the cloud.
- __gemini://gus.guru/__ - Gemini Universal Search ([repo](https://natpen.net/code/gus)).
- __gemini://tictactoe.lanterne.chilliet.eu__ - a Tic Tac Toe game ([repo](https://framagit.org/MCMic/gemini-tictactoe)).
- __gemini://ur.gs/__ - translate from en->es and es->en ([repo](https://code.ur.gs/lupine/capsule/src/branch/main/src/cgi-bin/translate)).
- __gemini://rawtext.club/~sloum/geminews/__ - Daily news feeds proxied to gemini.
- __gemini://rawtext.club/~sloum/cgi/othello/__ - Play othello/reversi against a computer opponent over gemini.
- __gemini://rawtext.club/~sloum/cgi/weather__ - US weather reports by zip code.
- [gemlog.blue](https://gemlog.blue) - Gemini hosting from a web frontend.


## Tools
- [CAPCOM](https://tildegit.org/solderpunk/CAPCOM) (Python) - Atom feed aggregator for gemini.
- [gemini-pandoc-lua-filter](https://github.com/kr1sp1n/gemini-pandoc-lua-filter) (Lua) - a lua filter for pandoc to output Gemini text.
- [gemini-to-html](https://github.com/RangerMauve/gemini-to-html) (Node.js) - a JavaScript library for parsing Gemini pages, and for rendering them to HTML.
- [geminize](https://addons.mozilla.org/en-US/firefox/addon/geminize/) - a Firefox addon that redirects gemini:// URLs and links to a customizable HTTP-to-Gemini proxy.
- [gem.git](https://git.sr.ht/~fkfd/git.gmi/) (Python) - git frontend CGI script.
- [gloggery](https://github.com/kconner/gloggery) (Go) - basic static site generator for blogs in Gemini.
- [gmitohtml](https://gitlab.com/tslocum/gmitohtml) (Go) - a proxy that renders Gemini pages using HTML.
- [gmi2html](https://github.com/shtanton/gmi2html) (Zig) - A tiny gemtext to HTML converter with a focus on performance.
- [gmi-web](https://codeberg.org/talon/gmi-web) (JS) - generate _semantic_ HTML styled for readability and mobile-friendliness.
- [gmnhg](https://git.tdem.in/tdemin/gmnhg) (Go) - renders a Hugo site to a Gemini site.
- [Html2GeminiPy](https://github.com/Aarontheissueguy/Html2GeminiPy) (Python) - Converts Html sites to Gemini sites using markdownify and md2gemini.
- [kiln](https://git.sr.ht/~adnano/kiln) (Go) - a simple static site generator for Gemini sites.
- [Lupa](https://framagit.org/bortzmeyer/lupa) - A crawler to explore the geminispace and make statistics (you can see them at __gemini://gemini.bortzmeyer.org/software/lupa/stats.gmi )
- [Manisha](https://framagit.org/bortzmeyer/manisha) - A Nagios (and compatible, such as Icinga) plugin to monitor Gemini servers
- [md2gmn](https://git.tdem.in/tdemin/gmnhg) (Go) - renders Markdown text to Gemini pages.
- [md2gemini](https://github.com/makeworld-the-better-one/md2gemini) (Python) - converter from Markdown to the Gemini text format.
- [spacewalk](https://tildegit.org/sloum/spacewalk) (Go) - Page-hash based feed aggregator for gemini.
- [MastoGem](https://git.rdelaage.ovh) (Go) - A Mastodon proxy for Gemini


### Syntax Highlighting
- [gemini-vim-syntax](https://tildegit.org/sloum/gemini-vim-syntax) - text/gemini syntax highlighting for vim.
- [gemini.el](https://git.carcosa.net/jmcbray/gemini.el) - text/gemini syntax highlighting for emacs.
- [gemini.kak](https://github.com/kakoune-editor/kakoune-extra-filetypes/blob/master/rc/gemini.kak) - text/gemini syntax highlighting for kakoune.
- [gemini.nanorc](https://github.com/yzzyx-network/nanorc/blob/master/gemini.nanorc) - text/gemini syntax highlighting for nano.
- [gemini.sublime-syntax](https://github.com/adiabatic/gemini.sublime-syntax) - text/gemini syntax highlighting for bat (and maybe Sublime Text).

## Web proxies
- [Mozz.us portal](https://portal.mozz.us/gemini/gemini.circumlunar.space/)
- [Soweli Lukin](https://alexschroeder.ch/soweli-lukin)
- [Vulpes proxy](https://proxy.vulpes.one/gemini/gemini.circumlunar.space/)

---
[1]: https://gemini.circumlunar.space/
