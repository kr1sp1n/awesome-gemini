# Awesome Gemini [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
A collection of awesome things regarding the [gemini protocol][1] ecosystem.

Please contribute to this list to link to all the awesome gemini projects out there.

## What is Gemini

[Excerpt from gemini.circumlunar.space](https://gemini.circumlunar.space/docs/specification.html):

> Gemini is a client-server protocol featuring request-response transactions, broadly similar to gopher or HTTP.
  Connections are closed at the end of a single transaction and cannot be reused. When Gemini is served over TCP/IP, servers 
  should listen on port 1965 (the first manned Gemini mission, Gemini 3, flew in March'65).
  This is an unprivileged port, so it's very easy to run a server as a "nobody" user, even if e.g. the server is written
  in Go and so can't drop privileges in the traditional fashion.

## Contents

- [Clients](#clients)
  - [Terminal](#terminal)
  - [Graphical](#graphical)
- [Programming](#programming)
- [Resources](#resources)
- [Servers](#servers)
- [Tools](#tools)
- [Web proxies](#web-proxies)

## Clients

### Terminal
- [Asuka](https://tildegit.org/julienxx/asuka) (Rust) - an NCurses-based Gemini client
- [Amfora](https://github.com/makeworld-the-better-one/amfora) (Go) - a "fancy" terminal client
- [AV-98](https://tildegit.org/solderpunk/AV-98) (Python) - a Gemini client derived from the popular VF-1 Gopher client
- [Bombadillo](https://rawtext.club/~sloum/bombadillo.html) (Go) - a combined Gopher and Gemini client with vim-inspired key mappings
- [diohasc](https://repo.or.cz/diohsc.git) (Haskell) -a simple line-based command-response terminal user interface with ANSI colour
- [Elpher](https://thelambdalab.xyz/elpher/) (Emacs) - a combined Gopher and Gemini client for the popular text editor / operating system
- [gemini-fetch](https://github.com/RangerMauve/gemini-fetch) (Node.js) - a cURL-like CLI for loading content from Gemini URLs

### Graphical
- [Agregore](https://github.com/RangerMauve/agregore-browser#fetch-api-for-gemini) - (Electron.js) - a peer to peer web browser with support for loading Gemini pages
- [Castor](https://git.sr.ht/~julienxx/castor) (Rust) - a graphical Gemini client using GTK
- [Deedum](https://github.com/snoe/deedum/releases) (Dart/Ruby) - an Android client
- [GemiNaut](https://www.marmaladefoo.com/pages/geminaut) (C#) - a user friendly graphical Gemini client for MS Windows
- [Kristall](https://github.com/MasterQ32/kristall) (C++) - a graphical Gopher and Gemini client using QT
- [Två](https://www.oppenlab.net/pr/tva/) (Kotlin/Java) - a Gemini protocol client for Android based OS

## Programming
- [gemini](https://github.com/derhuerst/gemini) (Node.js) - a server & client lib
- [gig](https://github.com/pitr/gig) (Go) - a Gemini framework

## Resources
- [Gemini Specification](https://gemini.circumlunar.space/docs/specification.html) - the Gemini protocol specification
- [gemini.circumlunar.space/software](https://portal.mozz.us/gemini/gemini.circumlunar.space/software/) - a list of Gemini software
- [transjovian.org/gemini](https://transjovian.org:1965/gemini/) - a wiki space dedicated to Gemini communities and software

## Servers
- [Agate](https://github.com/mbrubeck/agate) (Rust) - a simple Gemini server for static files
- [blizanci](https://github.com/mk270/blizanci) (Erlang) - a server designed primarily for robustness and security
- [Denoscuri](https://github.com/caranatar/denoscuri) (Typescript) - a simple Gemini server written using Deno and Typescript
- [GeGoBi](https://tildegit.org/solderpunk/gegobi) (Python) - a server to facilitate easy Gemini-Gopher bi-hosting
- [gemini-server](https://hackage.haskell.org/package/gemini-server) (Haskell) - a lightweight server for the Gemini protocol
- [geminid](https://github.com/jovoro/geminid/) (C) - a Gemini Server in C
- [Gemserv](https://portal.mozz.us/gemini/80h.dev/projects/gemserv/) (Rust) - a server with features like vhosts, CGI, SCGI, reverse-proxying and more
- [Germinal](https://github.com/jfmcbrayer/germinal) (Common Lisp) - serves any type of document with an appropriate mime type
- [Molly Brown](https://tildegit.org/solderpunk/molly-brown) (Go) - a full-featured Gemini server implemented in Go
- [Shavit](https://git.sr.ht/~yotam/shavit) (Go) - a configurable Gemini server for UNIX operating systems

## Tools
- [gemini-pandoc-lua-filter](https://github.com/kr1sp1n/gemini-pandoc-lua-filter) - a lua filter for pandoc to output Gemini text
- [gemini-to-html](https://github.com/RangerMauve/gemini-to-html) (Node.js) - a JavaScript library for parsing Gemini pages, and for rendering them to HTML.

## Web proxies
- [Mozz.us portal](https://portal.mozz.us/gemini/gemini.circumlunar.space/)
- [Vulpes proxy](https://proxy.vulpes.one/gemini/gemini.circumlunar.space/)

---
[1]: https://gemini.circumlunar.space/
