# Awesome Go

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome)

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
        - [HTTP Clients](#http-clients)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - EasyMidi is a simple and reliable library for working with standard midi file (SMF).( ★ 15 , Latest commit: Mar 22, 2018 )
* [flac](https://github.com/eaburns/flac) - Native Go FLAC decoder.( ★ 79 , Latest commit: Oct 4, 2017 )
* [flac](https://github.com/mewkiz/flac) - Native Go FLAC decoder.( ★ 82 , Latest commit: Aug 19, 2018 )
* [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.( ★ 50 , Latest commit: Feb 21, 2018 )
* [go-sox](https://github.com/krig/go-sox) - libsox bindings for go.( ★ 83 , Latest commit: Jun 17, 2018 )
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go.( ★ 19 , Latest commit: Dec 24, 2015 )
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.( ★ 8 , Latest commit: Jun 4, 2018 )
* [id3v2](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go.( ★ 81 , Latest commit: Oct 16, 2018 )
* [malgo](https://github.com/gen2brain/malgo) - Mini audio library.( ★ 48 , Latest commit: Nov 17, 2018 )
* [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.( ★ 17 , Latest commit: Sep 17, 2018 )
* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps.( ★ 88 , Latest commit: Jun 24, 2017 )
* [mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder.( ★ 81 , Latest commit: Apr 26, 2017 )
* [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go.( ★ 223 , Latest commit: Jun 12, 2018 )
* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.( ★ 235 , Latest commit: Aug 17, 2018 )
* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.( ★ 180 , Latest commit: Jul 16, 2017 )
* [taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib.( ★ 63 , Latest commit: Jul 18, 2018 )
* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).( ★ 22 , Latest commit: Oct 14, 2017 )
* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams.( ★ 224 , Latest commit: Jul 7, 2016 )

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.( ★★★ 1644 , Latest commit: Dec 17, 2018 )
* [branca](https://github.com/hako/branca) - Golang implementation of Branca Tokens.( ★ 38 , Latest commit: Aug 8, 2018 )
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.( ★★★★ 3416 , Latest commit: Dec 14, 2018 )
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format.( ★ 1 , Latest commit:  )
* [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.( ★★★ 1001 , Latest commit: Jul 25, 2018 )
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang.( ★★★ 1034 , Latest commit: Nov 16, 2018 )
* [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.( ★★ 940 , Latest commit: Nov 20, 2018 )
* [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.( ★★ 799 , Latest commit: Oct 30, 2017 )
* [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.( ★★★ 1971 , Latest commit: Dec 10, 2018 )
* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware.( ★ 162 , Latest commit: Jun 1, 2016 )
* [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT).( ★ 50 , Latest commit: Nov 9, 2018 )
* [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.( ★ 17 , Latest commit: Dec 10, 2018 )
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.( ★ 135 , Latest commit: Jul 23, 2018 )
* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT).( ★★★★ 4678 , Latest commit: Sep 21, 2018 )
* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.( ★★ 677 , Latest commit: Oct 4, 2018 )
* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.( ★★★ 1976 , Latest commit: Dec 2, 2018 )
* [osin](https://github.com/openshift/osin) - Golang OAuth2 server library.( ★★★ 1488 , Latest commit: Jul 18, 2018 )
* [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO).( ★ 167 , Latest commit: Nov 8, 2018 )
* [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.( ★ 291 , Latest commit: Nov 30, 2018 )
* [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications.( ★ 17 , Latest commit: Aug 29, 2018 )
* [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.( ★ 23 , Latest commit: Aug 31, 2018 )
* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).( ★ 77 , Latest commit: Sep 10, 2018 )
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module.( ★ 5 , Latest commit: Nov 9, 2018 )
* [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.( ★ 38 , Latest commit: Nov 29, 2017 )
* [signedvalue](https://github.com/sashka/signedvalue) - Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`.( ★ 5 , Latest commit:  )

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.( ★ 60 , Latest commit: Dec 12, 2018 )
* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.( ★ 11 , Latest commit: Nov 30, 2018 )
* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.( ★ 411 , Latest commit: Sep 19, 2018 )
* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.( ★ 39 , Latest commit: Jul 5, 2018 )
* [cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications.( ★★ 846 , Latest commit: Jan 28, 2017 )
* [climax](https://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.( ★ 149 , Latest commit: Jul 16, 2018 )
* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.( ★★★★★ 9989 , Latest commit: Nov 27, 2018 )
* [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.( ★ 67 , Latest commit: Nov 27, 2018 )
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.( ★★ 530 , Latest commit: Oct 26, 2018 )
* [docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile.( ★★★ 1021 , Latest commit: Jan 11, 2018 )
* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.( ★ 34 , Latest commit: Oct 16, 2018 )
* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.( ★ 86 , Latest commit: Nov 30, 2018 )
* [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.( ★ 393 , Latest commit: Oct 7, 2018 )
* [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.( ★ 24 , Latest commit: Nov 2, 2018 )
* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.( ★★ 556 , Latest commit: Nov 21, 2018 )
* [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow.( ★ 8 , Latest commit: Jun 8, 2018 )
* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser.( ★★★ 1240 , Latest commit: Dec 21, 2018 )
* [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications.( ★ 25 , Latest commit: Sep 5, 2018 )
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.( ★ 51 , Latest commit: Nov 28, 2018 )
* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.( ★★★ 2185 , Latest commit: Oct 28, 2018 )
* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.( ★★ 506 , Latest commit: Aug 26, 2018 )
* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.( ★★ 902 , Latest commit: Aug 24, 2018 )
* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.( ★★ 573 , Latest commit: Aug 31, 2018 )
* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.( ★★ 570 , Latest commit: Dec 23, 2018 )
* [readline](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license.( ★★★ 1276 , Latest commit: Jun 3, 2018 )
* [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.( ★ 1 , Latest commit: Nov 21, 2018 )
* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.( ★ 66 , Latest commit: Feb 4, 2018 )
* [strumt](https://github.com/antham/strumt) - Library to create prompt chain.( ★ 20 , Latest commit: Feb 17, 2018 )
* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework.( ★ 90 , Latest commit: Jan 9, 2016 )
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).( ★★★★★ 9517 , Latest commit: Oct 29, 2018 )
* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.( ★ 27 , Latest commit: Jul 20, 2017 )
* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.( ★ 60 , Latest commit: Jul 29, 2018 )

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.( ★ 393 , Latest commit: Oct 3, 2018 )
* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.( ★ 48 , Latest commit: Dec 7, 2018 )
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.( ★ 280 , Latest commit: Jun 26, 2016 )
* [color](https://github.com/fatih/color) - Versatile package for colored terminal output.( ★★★★ 2791 , Latest commit: Oct 10, 2018 )
* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.( ★ 13 , Latest commit: May 10, 2016 )
* [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.( ★ 4 , Latest commit: Oct 22, 2018 )
* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.( ★ 8 , Latest commit: Sep 25, 2017 )
* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows.( ★ 322 , Latest commit: Mar 10, 2018 )
* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.( ★ 182 , Latest commit: Apr 9, 2018 )
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.( ★ 286 , Latest commit: Aug 30, 2018 )
* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).( ★★★ 1948 , Latest commit: Dec 18, 2018 )
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.( ★★★★ 3751 , Latest commit: Apr 12, 2018 )
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.( ★ 262 , Latest commit: Sep 25, 2016 )
* [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.( ★ 42 , Latest commit: Nov 1, 2018 )
* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.( ★ 374 , Latest commit: Dec 25, 2018 )
* [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.( ★ 457 , Latest commit: Nov 21, 2018 )
* [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go.( ★ 107 , Latest commit: Jul 30, 2018 )
* [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.( ★ 14 , Latest commit: May 14, 2018 )
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.( ★★★★ 3159 , Latest commit: Oct 27, 2018 )
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output.( ★ 197 , Latest commit: Apr 5, 2017 )
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib).( ★★★★★ 8126 , Latest commit: Dec 3, 2018 )
* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.( ★★ 704 , Latest commit: Mar 23, 2017 )
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.( ★★★ 1213 , Latest commit: Feb 24, 2017 )
* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.( ★ 454 , Latest commit: Apr 4, 2016 )

## Configuration

*Libraries for configuration parsing.*

* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.( ★ 186 , Latest commit: Sep 10, 2018 )
* [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.( ★ 42 , Latest commit: Jun 26, 2017 )
* [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.( ★ 192 , Latest commit: Nov 26, 2018 )
* [conflate](https://github.com/miracl/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.( ★ 15 , Latest commit: Jul 26, 2018 )
* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).( ★★ 638 , Latest commit: Oct 23, 2018 )
* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.( ★ 89 , Latest commit: Jun 19, 2017 )
* [envconf](https://github.com/ian-kent/envconf) - Configuration from environment.( ★ 7 , Latest commit: Oct 26, 2014 )
* [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.( ★ 131 , Latest commit: Nov 28, 2018 )
* [envh](https://github.com/antham/envh) - Helpers to manage environment variables.( ★ 89 , Latest commit:  )
* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.( ★ 101 , Latest commit: May 18, 2018 )
* [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.( ★ 16 , Latest commit:  )
* [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.( ★ 85 , Latest commit: Dec 10, 2018 )
* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).( ★★★ 1618 , Latest commit: Nov 20, 2018 )
* [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy.( ★ 55 , Latest commit: May 3, 2017 )
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.( ★ 23 , Latest commit: Jun 20, 2017 )
* [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.( ★ 25 , Latest commit: Dec 20, 2018 )
* [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.( ★ 154 , Latest commit: Dec 10, 2018 )
* [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.( ★ 21 , Latest commit: Apr 2, 2017 )
* [ini](https://github.com/go-ini/ini) - Go package to read and write INI files.( ★★★ 1233 , Latest commit: Dec 22, 2018 )
* [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.( ★ 191 , Latest commit: May 7, 2017 )
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.( ★★★ 1986 , Latest commit: May 18, 2018 )
* [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.( ★ 19 , Latest commit: Dec 2, 2018 )
* [sprbox](https://github.com/oblq/sprbox) - Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars).( ★ 3 , Latest commit: Oct 31, 2018 )
* [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go.( ★ 237 , Latest commit: Sep 5, 2017 )
* [viper](https://github.com/spf13/viper) - Go configuration with fangs.( ★★★★★ 7096 , Latest commit: Dec 7, 2018 )
* [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).( ★ 16 , Latest commit: Aug 3, 2017 )

## Continuous Integration

*Tools for help with continuous integration.*

* [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.( ★★★★★ 16654 , Latest commit: Dec 6, 2018 )
* [duci](https://github.com/duck8823/duci) - A simple ci server no needs domain specific languages.( ★ 15 , Latest commit: Dec 19, 2018 )
* [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace.( ★ 13 , Latest commit: Dec 20, 2018 )
* [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.( ★★ 528 , Latest commit: Sep 27, 2018 )
* [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.( ★ 94 , Latest commit: Feb 1, 2018 )
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.( ★ 10 , Latest commit: Nov 20, 2017 )

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.( ★ 407 , Latest commit: Oct 12, 2014 )
* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.( ★ 111 , Latest commit: Nov 30, 2018 )

## Data Structures

*Generic datastructures and algorithms in Go.*
* [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.( ★ 112 , Latest commit: Aug 3, 2018 )
* [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.( ★ 103 , Latest commit: Oct 16, 2017 )
* [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.( ★ 28 , Latest commit: Mar 13, 2018 )
* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets.( ★ 410 , Latest commit: Oct 14, 2018 )
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.( ★ 120 , Latest commit: Oct 27, 2015 )
* [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.( ★ 11 , Latest commit: Jun 2, 2017 )
* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.( ★★★ 1043 , Latest commit: Oct 28, 2018 )
* [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.( ★ 12 , Latest commit: Nov 18, 2017 )
* [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library.( ★ 51 , Latest commit: Oct 31, 2018 )
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).( ★ 39 , Latest commit: Feb 12, 2017 )
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.( ★ 396 , Latest commit: Aug 1, 2018 )
* [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).( ★ 20 , Latest commit: Sep 21, 2018 )
* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go.( ★ 88 , Latest commit: Dec 23, 2017 )
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.( ★ 59 , Latest commit: Mar 24, 2017 )
* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.( ★★★★ 4595 , Latest commit: Aug 29, 2018 )
* [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.( ★ 8 , Latest commit: Sep 25, 2017 )
* [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index.( ★ 291 , Latest commit: Jan 27, 2016 )
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.( ★ 18 , Latest commit: Nov 17, 2018 )
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.( ★ 90 , Latest commit: Jun 18, 2018 )
* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.( ★★★★★ 4934 , Latest commit: Oct 20, 2018 )
* [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.( ★★ 917 , Latest commit: Sep 27, 2018 )
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.( ★ 11 , Latest commit: Aug 25, 2017 )
* [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.( ★ 173 , Latest commit: Mar 12, 2015 )
* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.( ★★ 679 , Latest commit: Oct 24, 2017 )
* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.( ★ 164 , Latest commit: Nov 22, 2018 )
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.( ★★ 626 , Latest commit: Dec 23, 2018 )
* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.( ★ 21 , Latest commit: Feb 17, 2017 )
* [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.( ★ 36 , Latest commit: Dec 21, 2018 )
* [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing.( ★ 270 , Latest commit: Mar 22, 2016 )
* [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.( ★ 108 , Latest commit: Dec 25, 2018 )
* [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.( ★ 4 , Latest commit: May 19, 2018 )
* [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out.( ★ 7 , Latest commit: Aug 31, 2018 )
* [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.( ★★ 508 , Latest commit: Dec 11, 2018 )
* [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap.( ★ 5 , Latest commit: Oct 9, 2018 )
* [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation.( ★ 67 , Latest commit: Dec 8, 2018 )
* [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.( ★ 57 , Latest commit: Nov 21, 2014 )
* [trie](https://github.com/derekparker/trie) - Trie implementation in Go.( ★ 337 , Latest commit: Feb 12, 2018 )
* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang.( ★ 75 , Latest commit: Sep 9, 2018 )
* [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters.( ★★ 561 , Latest commit: May 6, 2017 )

## Database

*Databases implemented in Go.*

* [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go.( ★★★★ 4799 , Latest commit: Dec 25, 2018 )
* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.( ★★★ 1771 , Latest commit: Nov 25, 2018 )
* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go.( ★★★★★ 9282 , Latest commit: Mar 2, 2018 )
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.( ★★★ 2179 , Latest commit: May 3, 2018 )
* [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.( ★★ 741 , Latest commit: Oct 26, 2018 )
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.( ★ 23 , Latest commit: Jan 22, 2018 )
* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.( ★★★★★ 15021 , Latest commit: Dec 25, 2018 )
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.( ★ 39 , Latest commit: Oct 25, 2017 )
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.( ★ 383 , Latest commit: Dec 25, 2018 )
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.( ★★★★★ 7185 , Latest commit: Dec 25, 2018 )
* [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.( ★★ 663 , Latest commit: Mar 12, 2018 )
* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.( ★ 496 , Latest commit: Sep 9, 2017 )
* [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.( ★ 308 , Latest commit: Dec 6, 2018 )
* [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.( ★ 29 , Latest commit: Dec 15, 2016 )
* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.( ★★ 606 , Latest commit: Oct 10, 2017 )
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.( ★★★ 2201 , Latest commit: Aug 15, 2018 )
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go.( ★★★★ 2663 , Latest commit: Nov 28, 2018 )
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go.( ★ 6 , Latest commit: Jan 10, 2018 )
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.( ★★★★★ 6945 , Latest commit: Oct 24, 2018 )
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.( ★★★★★ 15132 , Latest commit: Dec 21, 2018 )
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.( ★★★★ 2796 , Latest commit: Oct 29, 2018 )
* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.( ★ 342 , Latest commit: Nov 15, 2016 )
* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.( ★★ 660 , Latest commit: Nov 20, 2018 )
* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.( ★ 165 , Latest commit: Mar 29, 2018 )
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.( ★★★★★ 21033 , Latest commit: Dec 25, 2018 )
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.( ★★★★ 4137 , Latest commit: Nov 27, 2018 )
* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.( ★ 23 , Latest commit: Jun 7, 2018 )
* [slowpoke](https://github.com/recoilme/slowpoke) - Key-value store with persistence.( ★ 66 , Latest commit: Dec 24, 2018 )
* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.( ★ 13 , Latest commit: Feb 14, 2018 )
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.( ★★★★★ 16561 , Latest commit: Dec 26, 2018 )
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.( ★★★ 2260 , Latest commit: Jan 5, 2018 )
* [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.( ★ 106 , Latest commit: Oct 23, 2018 )

*Database schema migration.*

* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.( ★ 73 , Latest commit: Feb 10, 2017 )
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.( ★ 17 , Latest commit: Nov 1, 2018 )
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg.( ★ 13 , Latest commit: Dec 22, 2018 )
* [gondolier](https://github.com/emvicom/gondolier) - Gondolier is a library to auto migrate database schemas using structs.( ★ 20 , Latest commit: Jul 5, 2018 )
* [goose](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.( ★ 94 , Latest commit: Jul 25, 2016 )
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.( ★ 229 , Latest commit: Dec 15, 2018 )
* [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.( ★★★ 1306 , Latest commit: Dec 21, 2018 )
* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.( ★ 22 , Latest commit: Dec 19, 2018 )
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.( ★★ 546 , Latest commit: Dec 22, 2018 )
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.( ★★★ 1187 , Latest commit: Dec 13, 2018 )

*Database tools.*

* [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.( ★ 205 , Latest commit: Sep 24, 2018 )
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers.( ★ 89 , Latest commit: Sep 10, 2018 )
* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.( ★★★ 1427 , Latest commit: Dec 21, 2018 )
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.( ★★★ 1898 , Latest commit: Sep 8, 2018 )
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.( ★★★★ 3997 , Latest commit: Dec 1, 2018 )
* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication.( ★ 126 , Latest commit: Oct 5, 2018 )
* [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).( ★ 37 , Latest commit: Dec 12, 2018 )
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.( ★★★ 2399 , Latest commit: Dec 24, 2018 )
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.( ★★★★★ 5473 , Latest commit: Dec 24, 2018 )
* [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.( ★ 21 , Latest commit: Dec 20, 2017 )
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database.( ★★★ 1904 , Latest commit: Sep 4, 2018 )
* [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.( ★ 9 , Latest commit:  )
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.( ★★★★★ 7220 , Latest commit: Dec 24, 2018 )

*SQL query builder, libraries for building and using SQL.*

* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.( ★ 392 , Latest commit: Oct 22, 2018 )
* [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.( ★ 491 , Latest commit: Nov 30, 2018 )
* [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.( ★ 48 , Latest commit: Dec 4, 2018 )
* [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.( ★ 476 , Latest commit: Sep 9, 2018 )
* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.( ★ 70 , Latest commit: Jul 1, 2018 )
* [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.( ★ 0 , Latest commit: Dec 3, 2018 )
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.( ★ 282 , Latest commit: Jun 15, 2018 )
* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs.( ★ 138 , Latest commit: Jul 16, 2015 )
* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.( ★ 135 , Latest commit: Nov 24, 2018 )
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.( ★★★ 1837 , Latest commit: Dec 19, 2018 )
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.( ★★★ 1846 , Latest commit: Dec 15, 2018 )

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.( ★ 21 , Latest commit: Dec 4, 2018 )
    * [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.( ★ 9 , Latest commit: Nov 20, 2018 )
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.( ★ 90 , Latest commit: Dec 22, 2018 )
    * [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.( ★ 85 , Latest commit: Oct 6, 2018 )
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.( ★★ 864 , Latest commit: Oct 14, 2018 )
    * [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.( ★ 345 , Latest commit: Dec 19, 2018 )
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.( ★★★★★ 6679 , Latest commit: Dec 18, 2018 )
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.( ★★★★ 2938 , Latest commit: Dec 18, 2018 )
    * [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).( ★ 80 , Latest commit: Sep 3, 2018 )
    * [goracle](https://github.com/go-goracle/goracle) - Oracle driver for Go, using the ODPI-C driver.( ★ 150 , Latest commit: Dec 19, 2018 )
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.( ★★★ 1584 , Latest commit: Dec 15, 2018 )
    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.( ★★★★ 4476 , Latest commit: Oct 16, 2018 )

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.( ★ 287 , Latest commit: Dec 3, 2018 )
    * [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.( ★ 64 , Latest commit: Sep 10, 2017 )
    * [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.( ★ 4 , Latest commit: Oct 4, 2018 )
    * [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component for multiple drivers.( ★ 99 , Latest commit: May 20, 2018 )
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.( ★★★★★ 12065 , Latest commit: Nov 30, 2018 )
    * [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.( ★ 6 , Latest commit:  )
    * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB.( ★ 61 , Latest commit: Mar 28, 2017 )
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.( ★ 284 , Latest commit: Dec 10, 2018 )
    * [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go.( ★ 50 , Latest commit: Jul 4, 2014 )
    * [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.( ★ 274 , Latest commit: Dec 6, 2018 )
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.( ★ 4 , Latest commit: Jun 6, 2018 )
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.( ★★ 989 , Latest commit: Jul 10, 2018 )
    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.( ★★★ 1398 , Latest commit: Dec 1, 2018 )
    * [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV.( ★ 24 , Latest commit: Dec 18, 2018 )
    * [mgo](https://github.com/globalsign/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.( ★★★ 1343 , Latest commit: Oct 15, 2018 )
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.( ★★★ 1545 , Latest commit: Dec 19, 2018 )
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.( ★ 24 , Latest commit: Apr 3, 2015 )
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.( ★ 70 , Latest commit: Jun 20, 2018 )
    * [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.( ★ 347 , Latest commit: Mar 6, 2017 )
    * [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.( ★★★★★ 5318 , Latest commit: Dec 13, 2018 )
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang.( ★★★★ 4719 , Latest commit: Dec 21, 2018 )
    * [redis](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.( ★ 234 , Latest commit: Nov 29, 2018 )
    * [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.( ★ 9 , Latest commit: Jun 7, 2018 )

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go.( ★★★★★ 4818 , Latest commit: Dec 18, 2018 )
    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.( ★★★★ 3295 , Latest commit: Dec 12, 2018 )
    * [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.( ★ 252 , Latest commit: Dec 26, 2017 )
    * [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library.( ★★ 931 , Latest commit: Jan 24, 2017 )
    * [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.( ★ 25 , Latest commit: Mar 2, 2017 )
    * [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine.( ★★★★ 4155 , Latest commit: Dec 22, 2018 )
    * [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.( ★ 56 , Latest commit: May 3, 2016 )

## Date and Time

*Libraries for working with dates and times.*

* [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.( ★ 278 , Latest commit: Dec 5, 2018 )
* [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.( ★ 21 , Latest commit: Nov 27, 2018 )
* [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.( ★★ 759 , Latest commit: Nov 23, 2018 )
* [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go.( ★ 202 , Latest commit: May 20, 2018 )
* [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...( ★ 15 , Latest commit: Nov 2, 2018 )
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).( ★ 42 , Latest commit: Nov 23, 2018 )
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location.( ★ 8 , Latest commit:  )
* [goweek](https://github.com/grsmv/goweek) - Library for working with week entity in golang.( ★ 17 , Latest commit: Jan 4, 2017 )
* [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex.( ★ 55 , Latest commit: Dec 21, 2018 )
* [Kair](https://github.com/GuilhermeCaruso/Kair) - Date and Time - Golang Formatting Library.( ★ 5 , Latest commit: Oct 5, 2018 )
* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang.( ★★★ 1898 , Latest commit: Nov 16, 2018 )
* [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.( ★ 8 , Latest commit: Mar 22, 2017 )
* [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter.( ★ 5 , Latest commit:  )
* [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration.( ★ 58 , Latest commit: Apr 3, 2016 )
* [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.( ★ 152 , Latest commit: Aug 2, 2015 )
* [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.( ★ 6 , Latest commit:  )

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.( ★ 43 , Latest commit: Dec 8, 2018 )
* [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.( ★ 143 , Latest commit: Sep 28, 2018 )
* [digota](https://github.com/digota/digota) - grpc ecommerce microservice.( ★ 257 , Latest commit: Oct 15, 2018 )
* [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.( ★ 24 , Latest commit:  )
* [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.( ★ 22 , Latest commit: May 14, 2018 )
* [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.( ★★★ 1494 , Latest commit: Dec 16, 2018 )
* [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package.( ★ 3 , Latest commit: Dec 14, 2018 )
* [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.( ★★★ 1730 , Latest commit: Dec 11, 2018 )
* [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.( ★★★ 2280 , Latest commit: Nov 1, 2018 )
* [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.( ★ 409 , Latest commit: Dec 5, 2018 )
* [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.( ★ 218 , Latest commit: Apr 9, 2017 )
* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.( ★★★★★ 12232 , Latest commit: Dec 19, 2018 )
* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.( ★★ 503 , Latest commit: May 19, 2016 )
* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.( ★★★★★ 7134 , Latest commit: Dec 21, 2018 )
* [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.( ★★ 881 , Latest commit: May 17, 2018 )
* [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system.( ★★★★★ 6781 , Latest commit: Dec 25, 2018 )
* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.( ★ 87 , Latest commit: Nov 30, 2018 )
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.( ★ 70 , Latest commit: Dec 1, 2018 )
* [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.( ★★★ 1110 , Latest commit: Dec 18, 2018 )
* [micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform.( ★★★★★ 5165 , Latest commit: Dec 21, 2018 )
* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.( ★★★★★ 5033 , Latest commit: Dec 21, 2018 )
* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.( ★★★ 2323 , Latest commit: Aug 23, 2018 )
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.( ★★★★★ 22026 , Latest commit: Dec 7, 2018 )
* [redis-lock](https://github.com/bsm/redis-lock) - Simplified distributed locking implementation using Redis.( ★ 90 , Latest commit: Nov 29, 2018 )
* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.( ★★ 518 , Latest commit: Jul 26, 2018 )
* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.( ★★★★ 3049 , Latest commit: Dec 22, 2018 )
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)).( ★ 283 , Latest commit: Mar 21, 2018 )
* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.( ★★★★ 2587 , Latest commit: Dec 21, 2018 )
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package.( ★★★★ 2542 , Latest commit: Nov 29, 2018 )
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
    * [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.( ★ 344 , Latest commit: Jul 18, 2016 )

## Email

*Libraries and tools that implement email creation and sending.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
* [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.( ★ 136 , Latest commit: Mar 22, 2018 )
* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.( ★★ 974 , Latest commit: Dec 5, 2018 )
* [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.( ★ 46 , Latest commit: Dec 3, 2017 )
* [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers.( ★★ 571 , Latest commit: Dec 14, 2018 )
* [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.( ★ 74 , Latest commit: Sep 28, 2018 )
* [Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails.( ★★★ 2035 , Latest commit: Apr 11, 2016 )
* [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.( ★ 158 , Latest commit: Apr 15, 2018 )
* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.( ★★★ 1400 , Latest commit: Oct 29, 2018 )
* [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.( ★★★★ 4189 , Latest commit: Oct 17, 2018 )
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.( ★ 441 , Latest commit: Nov 18, 2018 )
* [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine.( ★ 49 , Latest commit: Nov 20, 2016 )

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go.( ★ 315 , Latest commit: Jan 25, 2015 )
* [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go.( ★★ 805 , Latest commit: Dec 25, 2018 )
* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua).( ★ 22 , Latest commit: Jul 29, 2018 )
* [expr](https://github.com/antonmedv/expr) - an engine that can evaluate expressions.( ★ 235 , Latest commit: Dec 2, 2018 )
* [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go.( ★ 409 , Latest commit: Jun 29, 2014 )
* [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.( ★★ 615 , Latest commit: Nov 25, 2018 )
* [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.( ★★★ 1458 , Latest commit: Nov 7, 2018 )
* [go-php](https://github.com/deuill/go-php) - PHP bindings for Go.( ★★ 579 , Latest commit: Oct 1, 2018 )
* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.( ★★ 780 , Latest commit: Aug 7, 2018 )
* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API.( ★ 416 , Latest commit: Mar 2, 2018 )
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.( ★★★★ 2501 , Latest commit: Dec 14, 2018 )
* [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.( ★ 15 , Latest commit: Jun 3, 2018 )
* [otto](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go.( ★★★★ 4265 , Latest commit: Jun 17, 2018 )
* [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.( ★ 25 , Latest commit: Dec 7, 2014 )

## Files

*Libraries for  handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.( ★★★ 1828 , Latest commit: Dec 16, 2018 )
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag.( ★ 35 , Latest commit: Oct 15, 2018 )
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.( ★ 7 , Latest commit: Oct 18, 2018 )
* [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go.( ★ 10 , Latest commit: Oct 15, 2018 )
* [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.( ★ 421 , Latest commit: Nov 26, 2018 )
* [pdfcpu](https://github.com/hhrutter/pdfcpu) - PDF processor.( ★★ 744 , Latest commit: Dec 22, 2018 )
* [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.( ★ 38 , Latest commit: Aug 4, 2017 )
* [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.( ★ 30 , Latest commit: Apr 2, 2017 )

## Financial

*Packages for accounting and finance.*

* [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang.( ★ 425 , Latest commit: Jul 3, 2018 )
* [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.( ★★★ 1227 , Latest commit: Jul 9, 2018 )
* [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go.( ★★ 537 , Latest commit: Mar 9, 2018 )
* [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.( ★ 26 , Latest commit: May 6, 2018 )
* [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.( ★★ 510 , Latest commit: Jul 25, 2018 )
* [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).( ★ 49 , Latest commit: Oct 12, 2018 )
* [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies.( ★ 92 , Latest commit: Apr 16, 2018 )
* [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode.( ★ 33 , Latest commit: Sep 5, 2018 )
* [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.( ★ 52 , Latest commit: Sep 10, 2018 )

## Forms

*Libraries for working with forms.*

* [bind](https://github.com/robfig/bind) - Bind form data to any Go values.( ★ 22 , Latest commit: Aug 16, 2014 )
* [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct.( ★★ 726 , Latest commit: Sep 17, 2017 )
* [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.( ★ 153 , Latest commit: Jun 16, 2018 )
* [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.( ★ 308 , Latest commit: Nov 21, 2018 )
* [formam](https://github.com/monoculum/formam) - decode form's values into a struct.( ★ 109 , Latest commit: Sep 1, 2018 )
* [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.( ★ 94 , Latest commit: Feb 16, 2017 )
* [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.( ★ 338 , Latest commit: Dec 10, 2018 )
* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.( ★★ 891 , Latest commit: Nov 22, 2018 )

## Functional

*Packages to support functional programming in Go.*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.( ★ 63 , Latest commit: Jul 18, 2018 )
* [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go.( ★ 0 , Latest commit: Nov 27, 2018 )
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.( ★★ 987 , Latest commit: Jun 29, 2015 )

## Game Development

*Awesome game development libraries.*

* [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go.( ★ 396 , Latest commit: Jun 24, 2018 )
* [Ebiten](https://github.com/hajimehoshi/ebiten) - dead simple 2D game library in Go.( ★★★ 1214 , Latest commit: Dec 26, 2018 )
* [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.( ★★ 909 , Latest commit: Dec 12, 2018 )
* [g3n](https://github.com/g3n/engine) - Go 3D Game Engine.( ★★ 523 , Latest commit: Sep 20, 2018 )
* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL.( ★ 305 , Latest commit: Sep 3, 2013 )
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library.( ★ 76 , Latest commit: Sep 24, 2015 )
* [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.( ★ 299 , Latest commit: Oct 25, 2017 )
* [go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format.( ★ 12 , Latest commit: Sep 27, 2013 )
* [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).( ★★★ 1004 , Latest commit: Dec 10, 2018 )
* [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.( ★ 144 , Latest commit: May 9, 2018 )
* [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.( ★★ 976 , Latest commit: May 12, 2017 )
* [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping.( ★★ 875 , Latest commit: Dec 8, 2018 )
* [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework.( ★★★★ 2587 , Latest commit: Nov 3, 2018 )
* [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework.( ★★ 774 , Latest commit: Dec 11, 2018 )
* [Oak](https://github.com/oakmound/oak) - Pure Go game engine.( ★★ 548 , Latest commit: Feb 7, 2018 )
* [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.( ★ 97 , Latest commit: Dec 20, 2018 )
* [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go.( ★★★ 1898 , Latest commit: Dec 11, 2018 )
* [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.( ★ 307 , Latest commit: Nov 17, 2018 )
* [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.( ★★ 940 , Latest commit: Nov 12, 2018 )

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations.( ★ 37 , Latest commit: Oct 12, 2017 )
* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.( ★★ 954 , Latest commit: Jun 11, 2018 )
* [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments.( ★ 61 , Latest commit: Oct 9, 2018 )
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.( ★★★ 1602 , Latest commit: Oct 24, 2018 )
* [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types.( ★★ 640 , Latest commit: Sep 11, 2018 )
* [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.( ★ 165 , Latest commit: Dec 23, 2018 )
* [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.( ★ 148 , Latest commit: Dec 21, 2018 )
* [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.( ★★★ 1022 , Latest commit: Dec 6, 2018 )
* [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection.( ★ 74 , Latest commit: Sep 5, 2017 )

## Geographic

*Geographic tools and servers*

* [geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications.( ★ 94 , Latest commit: Jun 21, 2016 )
* [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.( ★ 19 , Latest commit: Nov 20, 2018 )
* [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.( ★ 7 , Latest commit: Oct 30, 2018 )
* [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs.( ★ 35 , Latest commit: Dec 15, 2018 )
* [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder.( ★ 10 , Latest commit:  )
* [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go.( ★★ 770 , Latest commit: Oct 8, 2018 )
* [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.( ★★★★★ 5115 , Latest commit: Dec 13, 2018 )

## Go Compilers

*Tools for compiling Go to other languages.*

* [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.( ★ 49 , Latest commit: Dec 17, 2018 )
* [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code.( ★ 8 , Latest commit: Dec 21, 2018 )
* [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.( ★★★★★ 7724 , Latest commit: Nov 3, 2018 )
* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go.( ★★ 935 , Latest commit: Jan 5, 2015 )
* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.( ★ 382 , Latest commit: Nov 19, 2016 )

## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) - A high-performance goroutine pool for golang.( ★★★ 1102 , Latest commit: Dec 7, 2018 )
* [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.( ★ 4 , Latest commit: Nov 3, 2018 )
* [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.( ★ 11 , Latest commit: Sep 29, 2017 )
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.( ★ 21 , Latest commit: Oct 27, 2018 )
* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.( ★ 161 , Latest commit: Jan 15, 2018 )
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.( ★ 93 , Latest commit: Sep 19, 2017 )
* [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.( ★ 4 , Latest commit: May 29, 2018 )
* [GoSlaves](https://github.com/themester/GoSlaves) - Simple and Asynchronous Goroutine pool library.( ★ 52 , Latest commit: Aug 2, 2018 )
* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.( ★★★ 2092 , Latest commit: Sep 18, 2018 )
* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.( ★ 441 , Latest commit: Aug 4, 2017 )
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.( ★ 22 , Latest commit: Jan 1, 2018 )
* [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.( ★ 413 , Latest commit: Aug 23, 2016 )
* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.( ★ 38 , Latest commit: Oct 7, 2018 )
* [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).( ★ 46 , Latest commit: Oct 27, 2018 )
* [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.( ★ 5 , Latest commit: Sep 28, 2018 )
* [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation.( ★ 9 , Latest commit: Dec 11, 2017 )
* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang.( ★★★ 1062 , Latest commit: Nov 8, 2018 )
* [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.( ★ 26 , Latest commit: Nov 13, 2018 )
* [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.( ★ 63 , Latest commit: Sep 20, 2018 )

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.( ★★★★ 2651 , Latest commit: Dec 9, 2018 )
* [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go, rendered using EFL. Supports: Linux, macOS, Windows.( ★ 285 , Latest commit: Dec 24, 2018 )
* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).( ★★★ 2171 , Latest commit: Oct 21, 2018 )
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.( ★★★ 1239 , Latest commit: Oct 25, 2018 )
* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.( ★★ 579 , Latest commit: Dec 18, 2018 )
* [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.( ★ 160 , Latest commit: Oct 25, 2018 )
* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).( ★★★★★ 4977 , Latest commit: Dec 23, 2018 )
* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.( ★★★★★ 6292 , Latest commit: Sep 2, 2018 )
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go.( ★★★★ 3124 , Latest commit: Dec 6, 2018 )
* [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).( ★★★★ 3351 , Latest commit: Oct 18, 2018 )

*Interaction*

* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.( ★ 466 , Latest commit: Feb 1, 2018 )
* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.( ★★★★ 3636 , Latest commit: Dec 21, 2018 )
* [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.( ★★ 585 , Latest commit: Dec 5, 2018 )
* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.( ★ 138 , Latest commit: Oct 20, 2018 )


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.( ★★★ 1877 , Latest commit: May 8, 2018 )
* [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.( ★★ 636 , Latest commit: Dec 10, 2018 )
* [cameron](https://github.com/aofei/cameron) - An avatar generator for Go.( ★ 9 , Latest commit: Dec 12, 2018 )
* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.( ★★ 973 , Latest commit: May 9, 2017 )
* [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go.( ★★★ 1601 , Latest commit: Aug 23, 2018 )
* [gift](https://github.com/disintegration/gift) - Package of image processing filters.( ★★★ 1144 , Latest commit: Oct 5, 2018 )
* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.( ★ 81 , Latest commit: Sep 10, 2018 )
* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library.( ★ 47 , Latest commit: May 8, 2018 )
* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go.( ★ 270 , Latest commit: Apr 10, 2015 )
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.( ★★★ 1004 , Latest commit: Aug 17, 2017 )
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.( ★ 24 , Latest commit:  )
* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.( ★★★ 1816 , Latest commit: Nov 28, 2018 )
* [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.( ★ 149 , Latest commit: Oct 1, 2018 )
* [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.( ★ 274 , Latest commit: Apr 12, 2018 )
* [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII.( ★ 221 , Latest commit: Nov 7, 2018 )
* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.( ★★ 839 , Latest commit: Sep 25, 2018 )
* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.( ★★★ 2120 , Latest commit: Dec 23, 2018 )
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.( ★★★ 2045 , Latest commit: Oct 20, 2018 )
* [img](https://github.com/hawx/img) - Selection of image manipulation tools.( ★ 126 , Latest commit:  )
* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.( ★★★ 2323 , Latest commit: Feb 23, 2017 )
* [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).( ★ 35 , Latest commit: Oct 26, 2018 )
* [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go.( ★ 336 , Latest commit: Oct 4, 2018 )
* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.( ★ 4 , Latest commit: Nov 11, 2018 )
* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go.( ★★ 925 , Latest commit: Dec 12, 2018 )
* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go.( ★★★ 1687 , Latest commit: Jun 19, 2017 )
* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.( ★★★ 1958 , Latest commit: Feb 21, 2018 )
* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.( ★ 155 , Latest commit: Jul 31, 2017 )
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.( ★★★ 1187 , Latest commit: Oct 29, 2018 )
* [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography.( ★ 10 , Latest commit:  )
* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.( ★★★ 1186 , Latest commit: Oct 5, 2018 )
* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.( ★ 19 , Latest commit: May 24, 2015 )

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.( ★ 141 , Latest commit: Apr 10, 2018 )
* [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.( ★ 211 , Latest commit: Jul 9, 2016 )
* [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.( ★ 24 , Latest commit: Apr 12, 2017 )
* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.( ★★ 866 , Latest commit: Dec 14, 2018 )
* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.( ★★ 740 , Latest commit: Oct 11, 2015 )
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.( ★★★★★ 4980 , Latest commit: Dec 19, 2018 )
* [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go.( ★ 71 , Latest commit: Nov 28, 2018 )
* [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device.( ★ 25 , Latest commit: Apr 6, 2018 )
* [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.( ★ 269 , Latest commit: Dec 21, 2018 )
* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
* [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.( ★ 159 , Latest commit: Dec 31, 2017 )

## Logging

*Libraries for generating and working with log files.*

* [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).( ★ 15 , Latest commit: Jul 27, 2018 )
* [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.( ★ 23 , Latest commit: Nov 13, 2018 )
* [glog](https://github.com/golang/glog) - Leveled execution logs for Go.( ★★★ 2079 , Latest commit: Jan 26, 2016 )
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.( ★ 17 , Latest commit: Sep 1, 2018 )
* [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.( ★ 8 , Latest commit: May 19, 2018 )
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.( ★ 19 , Latest commit: Aug 7, 2018 )
* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go.( ★ 32 , Latest commit: Jan 14, 2016 )
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.( ★ 205 , Latest commit: Sep 30, 2018 )
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.( ★ 38 , Latest commit: Jan 31, 2018 )
* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.( ★ 12 , Latest commit:  )
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.( ★ 23 , Latest commit: Sep 6, 2017 )
* [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.( ★ 16 , Latest commit: Dec 25, 2018 )
* [log](https://github.com/apex/log) - Structured logging package for Go.( ★★ 641 , Latest commit: Oct 11, 2018 )
* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.( ★ 256 , Latest commit: Jun 29, 2018 )
* [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.( ★ 20 , Latest commit: Dec 4, 2017 )
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.( ★ 82 , Latest commit:  )
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.( ★★ 825 , Latest commit: Aug 19, 2018 )
* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.( ★ 7 , Latest commit:  )
* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.( ★ 33 , Latest commit:  )
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go.( ★ 128 , Latest commit: Sep 23, 2018 )
* [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration.( ★ 1 , Latest commit: Nov 7, 2018 )
* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers.( ★ 4 , Latest commit: Oct 19, 2017 )
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.( ★★★★★ 9340 , Latest commit: Dec 15, 2018 )
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).( ★ 24 , Latest commit: Mar 15, 2018 )
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.( ★ 232 , Latest commit: Aug 28, 2018 )
* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.( ★ 326 , Latest commit: Oct 27, 2016 )
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.( ★★★ 1094 , Latest commit: Aug 17, 2018 )
* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.( ★ 16 , Latest commit: Aug 6, 2018 )
* [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation.( ★ 296 , Latest commit: Dec 20, 2018 )
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).( ★ 97 , Latest commit: Jul 4, 2016 )
* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.( ★★★ 1241 , Latest commit: Jan 30, 2017 )
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.( ★★★★ 2771 , Latest commit: Aug 31, 2018 )
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.( ★ 44 , Latest commit: Sep 16, 2015 )
* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.( ★★★ 1293 , Latest commit: May 15, 2018 )
* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.( ★ 3 , Latest commit:  )
* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.( ★ 128 , Latest commit: Dec 27, 2017 )
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.( ★★★★★ 5719 , Latest commit: Aug 15, 2018 )
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.( ★★★ 1579 , Latest commit: Dec 7, 2018 )

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.( ★★ 588 , Latest commit: Dec 11, 2016 )
* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.( ★★ 623 , Latest commit: Dec 1, 2016 )
* [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library.( ★★ 566 , Latest commit: Nov 11, 2018 )
* [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.( ★ 22 , Latest commit: Apr 10, 2018 )
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.( ★ 14 , Latest commit: Aug 6, 2018 )
* [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go.( ★ 183 , Latest commit: Sep 14, 2018 )
* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.( ★ 97 , Latest commit: Feb 3, 2015 )
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.( ★ 162 , Latest commit: Dec 28, 2015 )
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.( ★ 55 , Latest commit: Jun 8, 2013 )
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go.( ★ 318 , Latest commit: Dec 9, 2018 )
* [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.( ★ 20 , Latest commit: May 11, 2015 )
* [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.( ★ 69 , Latest commit: Apr 17, 2016 )
* [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.( ★★★★★ 6166 , Latest commit: Aug 31, 2018 )
* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go.( ★ 37 , Latest commit: Apr 18, 2017 )
* [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go.( ★ 5 , Latest commit: Jul 31, 2018 )
* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.( ★★ 932 , Latest commit: Oct 31, 2016 )
* [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.( ★ 133 , Latest commit: Jul 29, 2014 )
* [gorgonia](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.( ★★★ 2315 , Latest commit: Nov 9, 2018 )
* [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML.( ★ 25 , Latest commit: Apr 4, 2018 )
* [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.( ★★ 688 , Latest commit: Dec 7, 2018 )
* [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.( ★ 58 , Latest commit: May 9, 2016 )
* [mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go.( ★ 4 , Latest commit: Dec 7, 2015 )
* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).( ★ 49 , Latest commit: May 18, 2018 )
* [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.( ★ 59 , Latest commit: Oct 18, 2013 )
* [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.( ★ 9 , Latest commit: Aug 2, 2013 )
* [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.( ★ 228 , Latest commit: Oct 29, 2018 )
* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.( ★ 118 , Latest commit: Apr 15, 2013 )
* [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.( ★★★ 1012 , Latest commit: Oct 25, 2018 )
* [Varis](https://github.com/Xamber/Varis) - Golang Neural Network.( ★ 18 , Latest commit: Aug 2, 2018 )

## Messaging

*Libraries that implement messaging systems.*

* [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.( ★★★ 1898 , Latest commit: Oct 14, 2018 )
* [Benthos](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols.( ★★★ 1653 , Latest commit: Dec 25, 2018 )
* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.( ★★★★ 3223 , Latest commit: Dec 24, 2018 )
* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.( ★ 291 , Latest commit: Dec 13, 2018 )
* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.( ★ 54 , Latest commit: Nov 11, 2018 )
* [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.( ★ 259 , Latest commit: Dec 21, 2017 )
* [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer.( ★ 17 , Latest commit: Feb 19, 2018 )
* [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.( ★ 451 , Latest commit: Mar 15, 2018 )
* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.( ★ 7 , Latest commit:  )
* [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).( ★ 293 , Latest commit: Oct 18, 2017 )
* [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.( ★ 41 , Latest commit:  )
* [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.( ★★★ 1265 , Latest commit: Oct 29, 2018 )
* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.( ★★★★ 2518 , Latest commit: Dec 14, 2018 )
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.( ★ 10 , Latest commit: Nov 2, 2018 )
* [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.( ★★ 639 , Latest commit: Aug 30, 2018 )
* [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.( ★ 389 , Latest commit: Jul 11, 2018 )
* [goose](https://github.com/ian-kent/goose) - Server Sent Events in Go.( ★ 34 , Latest commit: Dec 21, 2014 )
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.( ★★★ 1759 , Latest commit: May 25, 2017 )
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm).( ★★★★ 3135 , Latest commit: Dec 19, 2018 )
* [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.( ★ 133 , Latest commit: Oct 31, 2017 )
* [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.( ★ 12 , Latest commit: May 2, 2018 )
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.( ★★★★ 2791 , Latest commit: Dec 24, 2018 )
* [mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability.( ★★★ 1492 , Latest commit: Nov 1, 2018 )
* [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.( ★★★ 1229 , Latest commit: Feb 27, 2018 )
* [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).( ★★ 778 , Latest commit: Dec 17, 2018 )
* [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.( ★ 28 , Latest commit: Aug 28, 2018 )
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.( ★★★ 2010 , Latest commit: Dec 20, 2018 )
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.( ★ 40 , Latest commit: Feb 16, 2018 )
* [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.( ★ 92 , Latest commit: Nov 7, 2015 )
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.( ★ 229 , Latest commit: Oct 4, 2018 )
* [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues.( ★ 47 , Latest commit: Sep 18, 2018 )
* [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.( ★ 43 , Latest commit: Dec 22, 2018 )
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.( ★ 49 , Latest commit: Dec 7, 2017 )
* [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka.( ★★★★ 3732 , Latest commit: Dec 14, 2018 )
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.( ★★★ 1039 , Latest commit: Oct 10, 2018 )
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2).( ★★ 712 , Latest commit: Dec 5, 2018 )

## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang.( ★ 30 , Latest commit: Apr 26, 2017 )
* [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.( ★ 8 , Latest commit: Aug 10, 2018 )
* [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.( ★ 115 , Latest commit: Jul 28, 2018 )
* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.( ★★★ 1872 , Latest commit: Dec 12, 2018 )
* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.( ★ 21 , Latest commit:  )
* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.( ★ 8 , Latest commit: Aug 5, 2017 )
* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.( ★ 194 , Latest commit: Nov 8, 2016 )
* [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.( ★ 458 , Latest commit: Nov 27, 2018 )
* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.( ★ 110 , Latest commit: May 21, 2017 )
* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.( ★ 69 , Latest commit: Feb 21, 2018 )
* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).( ★ 27 , Latest commit: Sep 12, 2016 )
* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.( ★ 26 , Latest commit: Nov 7, 2018 )
* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.( ★ 333 , Latest commit: May 23, 2017 )
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.( ★ 26 , Latest commit: Nov 4, 2017 )
* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives.( ★★★★ 3776 , Latest commit: Oct 24, 2018 )
* [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.( ★ 443 , Latest commit: Dec 7, 2018 )
* [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans.( ★ 93 , Latest commit: Dec 3, 2018 )
* [ghorg](https://github.com/gabrie30/ghorg) - Clone all repos from a GitHub org into a single directory.( ★ 16 , Latest commit:  )
* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.( ★ 386 , Latest commit: Nov 28, 2018 )
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.( ★★ 573 , Latest commit: Aug 30, 2018 )
* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.( ★★ 537 , Latest commit: Aug 24, 2018 )
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.( ★★ 726 , Latest commit: Dec 14, 2018 )
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.( ★ 109 , Latest commit: Jul 31, 2018 )
* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.( ★ 48 , Latest commit:  )
* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go.( ★ 215 , Latest commit: Nov 6, 2018 )
* [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.( ★ 15 , Latest commit: Oct 12, 2018 )
* [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns.( ★ 56 , Latest commit: Jul 25, 2018 )
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).( ★★★★ 3174 , Latest commit: Dec 25, 2018 )
* [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.( ★ 11 , Latest commit: May 28, 2018 )
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.( ★★★ 1183 , Latest commit: Jul 7, 2017 )
* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.( ★ 190 , Latest commit: Oct 19, 2017 )
* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.( ★ 80 , Latest commit: Sep 4, 2018 )
* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library.( ★ 338 , Latest commit: Jul 24, 2018 )
* [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.( ★ 57 , Latest commit: Mar 9, 2018 )
* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.( ★ 6 , Latest commit: Oct 25, 2018 )
* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.( ★ 43 , Latest commit: Oct 18, 2018 )
* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.( ★ 437 , Latest commit: Dec 14, 2017 )
* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.( ★ 81 , Latest commit: Feb 19, 2018 )
* [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.( ★ 320 , Latest commit: Dec 20, 2018 )
* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots.( ★ 50 , Latest commit: Sep 18, 2016 )
* [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code.( ★ 38 , Latest commit: Nov 30, 2018 )
* [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.( ★ 18 , Latest commit: Feb 19, 2018 )
* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go.( ★ 25 , Latest commit: Jul 20, 2018 )
* [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.( ★ 3 , Latest commit: Nov 9, 2018 )
* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.( ★ 3 , Latest commit: Oct 2, 2017 )
* [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.( ★ 368 , Latest commit: Oct 29, 2017 )
* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.( ★ 224 , Latest commit: Dec 6, 2018 )
* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...( ★ 110 , Latest commit: Sep 7, 2016 )
* [strutil](https://github.com/ozgio/strutil) - String utilities.( ★ 34 , Latest commit: Sep 6, 2018 )
* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go.( ★ 60 , Latest commit: Oct 5, 2017 )
* [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.( ★ 10 , Latest commit: Jun 9, 2018 )
* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.( ★ 6 , Latest commit: Jun 22, 2017 )
* [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.( ★ 360 , Latest commit: Nov 28, 2018 )
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.( ★ 3 , Latest commit: Apr 11, 2016 )
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.( ★ 9 , Latest commit:  )
* [wuid](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID.( ★ 223 , Latest commit: Jun 29, 2018 )
* [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go.( ★ 12 , Latest commit: Nov 26, 2018 )
* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber.( ★ 36 , Latest commit: Jan 8, 2015 )
* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.( ★★ 531 , Latest commit: Sep 6, 2018 )

## Natural Language Processing

*Libraries for working with human languages.*

* [getlang](https://github.com/rylans/getlang) - Fast natural language detection package.( ★ 34 , Latest commit: Jul 13, 2018 )
* [go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.( ★ 4 , Latest commit: May 27, 2014 )
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.( ★★ 794 , Latest commit: Dec 8, 2018 )
* [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.( ★ 20 , Latest commit: Oct 5, 2016 )
* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.( ★ 77 , Latest commit:  )
* [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.( ★ 417 , Latest commit: Aug 5, 2018 )
* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.( ★ 50 , Latest commit: Jun 30, 2015 )
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.( ★ 36 , Latest commit: Nov 7, 2016 )
* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.( ★ 30 , Latest commit: May 17, 2017 )
* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.( ★★ 684 , Latest commit: Oct 5, 2018 )
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.( ★ 15 , Latest commit:  )
* [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)( ★ 2 , Latest commit: Oct 23, 2018 )
* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.( ★ 60 , Latest commit: Jun 29, 2015 )
* [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.( ★★ 639 , Latest commit: Dec 20, 2018 )
* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.( ★ 17 , Latest commit:  )
* [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.( ★ 342 , Latest commit: Sep 14, 2018 )
* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.( ★ 10 , Latest commit:  )
* [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.( ★ 57 , Latest commit:  )
* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.( ★ 348 , Latest commit:  )
* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).( ★ 176 , Latest commit: Nov 29, 2018 )
* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.( ★ 24 , Latest commit: Jun 19, 2013 )
* [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.( ★ 16 , Latest commit:  )
* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.( ★ 8 , Latest commit:  )
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.( ★ 32 , Latest commit: Aug 29, 2015 )
* [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more.( ★★★ 1850 , Latest commit: Oct 22, 2018 )
* [RAKE.go](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).( ★ 35 , Latest commit: Aug 4, 2017 )
* [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)( ★ 42 , Latest commit: Sep 15, 2016 )
* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences.( ★ 242 , Latest commit: Sep 2, 2017 )
* [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.( ★ 9 , Latest commit: Oct 18, 2018 )
* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).( ★ 21 , Latest commit:  )
* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.( ★ 42 , Latest commit: Dec 7, 2016 )
* [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.( ★ 58 , Latest commit: Nov 9, 2016 )
* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).( ★ 314 , Latest commit: Oct 4, 2018 )
* [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.( ★★ 892 , Latest commit: Oct 23, 2017 )

## Networking

*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.( ★ 162 , Latest commit: Oct 25, 2018 )
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.( ★ 215 , Latest commit: Apr 16, 2016 )
* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).( ★ 124 , Latest commit: Feb 7, 2018 )
* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.( ★ 314 , Latest commit: Feb 14, 2018 )
* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.( ★ 54 , Latest commit: Nov 20, 2018 )
* [dns](https://github.com/miekg/dns) - Go library for working with DNS.( ★★★★ 3320 , Latest commit: Dec 19, 2018 )
* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.( ★ 58 , Latest commit: Apr 5, 2016 )
* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.( ★ 163 , Latest commit: Oct 25, 2018 )
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.( ★★★★★ 7681 , Latest commit: Dec 13, 2018 )
* [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.( ★★ 571 , Latest commit: Dec 1, 2018 )
* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).( ★ 408 , Latest commit: Nov 1, 2018 )
* [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.( ★ 26 , Latest commit: Dec 19, 2018 )
* [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols.( ★ 77 , Latest commit: Dec 20, 2018 )
* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.( ★★ 600 , Latest commit: Dec 12, 2018 )
* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).( ★ 277 , Latest commit: Jul 26, 2018 )
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.( ★★★ 1504 , Latest commit: Dec 25, 2018 )
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.( ★ 12 , Latest commit:  )
* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.( ★★★ 2371 , Latest commit: Dec 23, 2018 )
* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.( ★ 332 , Latest commit: Jul 29, 2015 )
* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.( ★ 7 , Latest commit: Oct 24, 2017 )
* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.( ★ 388 , Latest commit: Oct 9, 2018 )
* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.( ★ 380 , Latest commit: Apr 18, 2017 )
* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.( ★ 431 , Latest commit: Nov 8, 2018 )
* [graval](https://github.com/koofr/graval) - Experimental FTP server framework.( ★ 23 , Latest commit:  )
* [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.( ★★★★ 3260 , Latest commit: Oct 21, 2018 )
* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.( ★ 104 , Latest commit: Aug 28, 2018 )
* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.( ★★★ 1805 , Latest commit: Dec 25, 2018 )
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.( ★★★★★ 9252 , Latest commit: Oct 27, 2018 )
* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.( ★ 460 , Latest commit: Apr 8, 2018 )
* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.( ★ 36 , Latest commit: Aug 7, 2017 )
* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.( ★ 7 , Latest commit: Apr 4, 2016 )
* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.( ★ 463 , Latest commit: Feb 21, 2017 )
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).( ★★ 557 , Latest commit: Dec 12, 2018 )
* [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed.( ★ 9 , Latest commit: Dec 11, 2018 )
* [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast.( ★ 311 , Latest commit: Sep 24, 2018 )
* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.( ★ 39 , Latest commit: Dec 13, 2014 )
* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).( ★ 16 , Latest commit:  )
* [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.( ★★★ 2207 , Latest commit: Dec 21, 2018 )
* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.( ★ 245 , Latest commit: Oct 16, 2018 )
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.( ★★ 617 , Latest commit: Sep 17, 2018 )
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).( ★★ 890 , Latest commit: Nov 14, 2018 )
* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.( ★ 108 , Latest commit: Mar 10, 2018 )
* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.( ★ 169 , Latest commit: Dec 5, 2018 )
* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.( ★ 236 , Latest commit: Sep 5, 2018 )
* [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server. ( ★ 2 , Latest commit: Oct 29, 2018 )
* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.( ★ 147 , Latest commit: Feb 19, 2018 )
* [water](https://github.com/songgao/water) - Simple TUN/TAP library.( ★★ 711 , Latest commit: Apr 20, 2018 )
* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.( ★ 186 , Latest commit: Nov 12, 2018 )
* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol.( ★ 52 , Latest commit: May 14, 2018 )

### HTTP Clients

*Libraries for making HTTP requests.*

* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.( ★★ 577 , Latest commit: Sep 14, 2018 )
* [goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest.( ★ 86 , Latest commit: Jul 27, 2018 )
* [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.( ★★★ 1218 , Latest commit: Nov 22, 2018 )
* [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities.( ★★ 621 , Latest commit: Dec 22, 2018 )
* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.( ★ 285 , Latest commit: Apr 30, 2018 )
* [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.( ★ 23 , Latest commit: Oct 20, 2018 )
* [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests.( ★★ 765 , Latest commit: Nov 25, 2018 )

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).( ★★ 545 , Latest commit: Oct 26, 2018 )
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.( ★★ 547 , Latest commit: Dec 13, 2018 )
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).( ★ 127 , Latest commit: Nov 28, 2017 )
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.( ★ 55 , Latest commit: Oct 18, 2017 )
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.( ★ 257 , Latest commit: Aug 4, 2018 )

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.( ★★★★★ 18349 , Latest commit: Nov 20, 2018 )
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.( ★★★ 2243 , Latest commit: Dec 23, 2018 )
* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.( ★ 372 , Latest commit: Aug 25, 2018 )
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.( ★ 89 , Latest commit: Nov 23, 2018 )
* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.( ★ 90 , Latest commit: Feb 23, 2017 )
* [gomodel](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database.( ★ 60 , Latest commit: Jul 2, 2017 )
* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.( ★★★★★ 11629 , Latest commit: Dec 13, 2018 )
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.( ★★★★ 2923 , Latest commit: Nov 4, 2018 )
* [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).( ★ 33 , Latest commit: Dec 17, 2018 )
* [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.( ★ 4 , Latest commit: Oct 22, 2017 )
* [Marlow](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances.( ★ 44 , Latest commit: Sep 28, 2018 )
* [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.( ★★ 546 , Latest commit: Dec 22, 2018 )
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM.( ★★ 518 , Latest commit: Apr 17, 2017 )
* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.( ★★ 716 , Latest commit: Dec 11, 2018 )
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.( ★★★ 1770 , Latest commit: Oct 30, 2018 )
* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.( ★★★ 1586 , Latest commit: Dec 25, 2018 )
* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go.( ★★★★ 4183 , Latest commit: Dec 20, 2018 )
* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.( ★ 227 , Latest commit: Mar 14, 2018 )

## Package Management

*Official tooling for package management*

* [dep](https://github.com/golang/dep) - Go dependency tool.( ★★★★★ 11229 , Latest commit: Oct 3, 2018 )
* [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

*Unofficial libraries for package and dependency management.*

* [gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes.( ★ 196 , Latest commit: Aug 6, 2015 )
* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.( ★★★★★ 7361 , Latest commit: Sep 26, 2018 )
* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.( ★★★★★ 5578 , Latest commit: Jan 26, 2018 )
* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go.( ★★★ 1342 , Latest commit: May 20, 2018 )
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.( ★★ 775 , Latest commit: Oct 2, 2014 )
* [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH.( ★ 49 , Latest commit: Sep 27, 2018 )
* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager.( ★★★ 2066 , Latest commit: Jul 28, 2017 )
* [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.( ★★★★ 4157 , Latest commit: Nov 14, 2018 )
* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.( ★★★ 1199 , Latest commit: Sep 7, 2017 )
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.( ★ 213 , Latest commit: Sep 16, 2014 )
* [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.( ★ 70 , Latest commit: Dec 19, 2018 )
* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies.( ★ 248 , Latest commit: Jun 25, 2015 )
* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.( ★ 112 , Latest commit: Apr 27, 2016 )

## Query Language

* [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data.( ★ 484 , Latest commit: Dec 17, 2018 )
* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities.( ★ 47 , Latest commit: Jun 2, 2017 )
* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.( ★★★ 2230 , Latest commit: Nov 28, 2018 )
* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.( ★★★★ 4067 , Latest commit: Dec 10, 2018 )
* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang.( ★ 180 , Latest commit: Nov 6, 2018 )
* [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters.( ★ 11 , Latest commit: Dec 25, 2018 )
* [rql](https://github.com/a8m/rql) - Resource Query Language for REST API.( ★ 78 , Latest commit: Oct 6, 2018 )

## Resource Embedding

* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.( ★ 377 , Latest commit: Nov 20, 2018 )
* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.( ★ 360 , Latest commit: Nov 14, 2018 )
* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable.( ★ 12 , Latest commit: Apr 12, 2016 )
* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.( ★ 147 , Latest commit: Oct 24, 2017 )
* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.( ★★★ 1449 , Latest commit: Apr 20, 2017 )
* [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.( ★★★ 1476 , Latest commit: Dec 12, 2018 )
* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.( ★ 49 , Latest commit: Oct 5, 2016 )
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable.( ★★★ 1628 , Latest commit: Nov 28, 2018 )
* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.( ★ 15 , Latest commit: Nov 2, 2018 )
* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.( ★ 446 , Latest commit: Dec 2, 2018 )

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.( ★★ 527 , Latest commit: Nov 1, 2018 )
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for Go for machine-learning and statistics (similar to pandas).( ★ 21 , Latest commit: Oct 24, 2018 )
* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.( ★ 34 , Latest commit:  )
* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.( ★ 246 , Latest commit: Aug 4, 2017 )
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang.( ★ 36 , Latest commit: Jan 3, 2018 )
* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.( ★★ 586 , Latest commit: May 8, 2018 )
* [go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg.( ★ 10 , Latest commit: Apr 3, 2013 )
* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.( ★ 4 , Latest commit: Apr 3, 2013 )
* [gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language.( ★ 4 , Latest commit: Nov 19, 2009 )
* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.( ★ 11 , Latest commit:  )
* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.( ★ 113 , Latest commit: Aug 22, 2016 )
* [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.( ★★★ 2270 , Latest commit: Dec 22, 2018 )
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.( ★★★ 1003 , Latest commit: Dec 19, 2018 )
* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).( ★★ 559 , Latest commit: Oct 1, 2017 )
* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.( ★★★ 1186 , Latest commit: Dec 18, 2018 )
* [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.( ★ 6 , Latest commit:  )
* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms.( ★ 180 , Latest commit: Sep 21, 2017 )
* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.( ★ 7 , Latest commit:  )
* [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.( ★ 74 , Latest commit: Nov 22, 2018 )
* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.( ★ 41 , Latest commit:  )
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.( ★ 5 , Latest commit: Nov 14, 2018 )
* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.( ★ 4 , Latest commit: Oct 2, 2017 )
* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.( ★ 52 , Latest commit: Dec 23, 2018 )
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.( ★★ 949 , Latest commit: Dec 13, 2018 )
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.( ★★★ 1312 , Latest commit: Apr 2, 2015 )
* [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.( ★ 57 , Latest commit: Sep 5, 2018 )
* [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.( ★ 7 , Latest commit: Aug 20, 2018 )

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.( ★★★ 1629 , Latest commit: Feb 13, 2018 )
* [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.( ★ 353 , Latest commit: Dec 18, 2018 )
* [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison.( ★ 66 , Latest commit: Sep 5, 2018 )
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
* [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.( ★ 228 , Latest commit: Jun 5, 2017 )
* [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.( ★★★ 1529 , Latest commit: Dec 25, 2018 )
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".( ★ 109 , Latest commit: Dec 5, 2018 )
* [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.( ★ 7 , Latest commit:  )
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.( ★ 24 , Latest commit: Dec 15, 2018 )
* [lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).( ★★★★ 3059 , Latest commit: Dec 22, 2018 )
* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.( ★★ 839 , Latest commit: Jun 11, 2018 )
* [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's.( ★ 378 , Latest commit: Dec 18, 2018 )
* [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library.( ★ 206 , Latest commit: Jun 1, 2018 )
* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.( ★★★ 1063 , Latest commit: Dec 21, 2018 )
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.( ★ 145 , Latest commit: Jun 6, 2018 )
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.( ★ 178 , Latest commit: Sep 12, 2018 )

## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.( ★ 34 , Latest commit: Mar 7, 2016 )
* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.( ★ 60 , Latest commit: Oct 8, 2016 )
* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.( ★ 420 , Latest commit: Sep 6, 2018 )
* [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.( ★ 251 , Latest commit: Sep 11, 2018 )
* [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.( ★ 6 , Latest commit: Jan 14, 2018 )
* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.( ★ 268 , Latest commit: Jan 31, 2017 )
* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.( ★★★ 1068 , Latest commit: Dec 9, 2018 )
* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.( ★★★ 2227 , Latest commit: Dec 11, 2018 )
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.( ★★★★ 3866 , Latest commit: Nov 28, 2018 )
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".( ★★★★ 4078 , Latest commit: Nov 12, 2018 )
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.( ★★★ 1897 , Latest commit: Oct 4, 2018 )
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.( ★ 108 , Latest commit: Aug 3, 2018 )
* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.( ★ 81 , Latest commit: Jun 4, 2015 )

## Server Applications

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.( ★ 497 , Latest commit: Dec 20, 2018 )
* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.( ★★★★★ 19753 , Latest commit: Dec 19, 2018 )
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers.( ★★★★ 2667 , Latest commit: Dec 24, 2018 )
* [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover.( ★ 320 , Latest commit: Dec 19, 2018 )
* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.( ★★★★★ 22026 , Latest commit: Dec 23, 2018 )
* [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.( ★★ 625 , Latest commit: Dec 25, 2018 )
* [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.( ★★ 506 , Latest commit: Dec 20, 2018 )
* [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go.( ★★ 525 , Latest commit: Dec 17, 2018 )
* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server.( ★★★★★ 14039 , Latest commit: Dec 23, 2018 )
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager.( ★★★ 2164 , Latest commit: Dec 20, 2018 )
* [yakvs](https://git.sci4me.com/sci4me/yakvs) - Small, networked, in-memory key-value store.

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.( ★★ 741 , Latest commit: Jun 17, 2018 )
* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.( ★★ 799 , Latest commit: Oct 10, 2017 )
* [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.( ★ 20 , Latest commit: Apr 7, 2016 )
* [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.( ★ 393 , Latest commit: Jun 24, 2018 )
* [extemplate](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.( ★ 8 , Latest commit: Aug 18, 2018 )
* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).( ★ 236 , Latest commit: Feb 24, 2017 )
* [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.( ★★★★ 2661 , Latest commit: Dec 22, 2018 )
* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.( ★★★ 1097 , Latest commit: Oct 20, 2018 )
* [jet](https://github.com/CloudyKit/jet) - Jet template engine.( ★★ 527 , Latest commit: Jul 3, 2018 )
* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.( ★ 70 , Latest commit: Jul 22, 2015 )
* [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.( ★ 71 , Latest commit: Jun 5, 2018 )
* [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.( ★★ 946 , Latest commit: Aug 5, 2016 )
* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.( ★★★ 1355 , Latest commit: Dec 25, 2018 )
* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.( ★★★ 1171 , Latest commit: Nov 24, 2018 )
* [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.( ★ 295 , Latest commit: Mar 22, 2018 )
* [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang.( ★★ 641 , Latest commit: Sep 11, 2018 )
* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).( ★ 135 , Latest commit: Nov 16, 2018 )
* [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.( ★ 62 , Latest commit: Mar 20, 2017 )

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.( ★ 11 , Latest commit: Feb 5, 2016 )
    * [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.( ★ 8 , Latest commit:  )
    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.( ★★ 569 , Latest commit: Sep 18, 2018 )
    * [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible.( ★ 5 , Latest commit: May 23, 2018 )
    * [bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them.( ★ 22 , Latest commit:  )
    * [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests.( ★ 182 , Latest commit:  )
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.( ★ 62 , Latest commit: Dec 17, 2018 )
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.( ★ 56 , Latest commit: Jul 16, 2018 )
    * [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.( ★ 20 , Latest commit: Dec 25, 2018 )
    * [endly](https://github.com/viant/endly) - Declarative end to end functional testing.( ★ 59 , Latest commit: Dec 25, 2018 )
    * [frisby](https://github.com/verdverm/frisby) - REST API testing framework.( ★ 236 , Latest commit: Jun 5, 2017 )
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.( ★ 182 , Latest commit:  )
    * [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests.( ★★ 744 , Latest commit: Nov 14, 2018 )
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.( ★ 191 , Latest commit: Nov 1, 2018 )
    * [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package.( ★ 26 , Latest commit: Dec 24, 2018 )
    * [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.( ★ 263 , Latest commit: Dec 20, 2018 )
    * [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go.( ★★ 569 , Latest commit: Oct 3, 2018 )
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.( ★★★★ 4120 , Latest commit: Nov 7, 2018 )
    * [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.( ★ 7 , Latest commit: Jan 31, 2018 )
    * [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go.( ★★ 506 , Latest commit: Dec 19, 2018 )
    * [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.( ★ 214 , Latest commit: Dec 26, 2018 )
    * [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go.( ★ 7 , Latest commit: Mar 1, 2018 )
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.( ★ 110 , Latest commit: Jul 31, 2014 )
    * [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.( ★ 50 , Latest commit:  )
    * [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.( ★ 7 , Latest commit:  )
    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns.( ★ 68 , Latest commit: Dec 23, 2018 )
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.( ★ 24 , Latest commit:  )
    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.( ★★ 999 , Latest commit: Aug 3, 2018 )
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.( ★ 49 , Latest commit:  )
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.( ★ 239 , Latest commit: Dec 15, 2018 )
    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.( ★★★★★ 6422 , Latest commit: Dec 4, 2018 )
    * [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished.( ★ 5 , Latest commit: Oct 12, 2018 )
    * [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools.( ★ 2 , Latest commit:  )
    * [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.( ★ 50 , Latest commit: Feb 17, 2018 )

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.( ★ 293 , Latest commit: Dec 7, 2018 )
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.( ★★★ 1206 , Latest commit: Dec 21, 2018 )
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.( ★ 106 , Latest commit: Nov 24, 2018 )
    * [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.( ★★ 647 , Latest commit: Nov 13, 2018 )
    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.( ★★★ 1942 , Latest commit: Dec 21, 2018 )
    * [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.( ★ 52 , Latest commit: Dec 14, 2018 )
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. ( ★★★ 1255 , Latest commit: Dec 4, 2018 )
    * [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.( ★ 150 , Latest commit: Dec 20, 2018 )
    * [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.( ★ 22 , Latest commit: Oct 30, 2014 )

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.( ★★★★ 2479 , Latest commit: Nov 23, 2018 )
    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.( ★ 466 , Latest commit: Jun 12, 2017 )
    * [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.( ★ 195 , Latest commit: Nov 1, 2018 )

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.( ★ 219 , Latest commit: Dec 15, 2018 )
    * [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.( ★★★★ 2551 , Latest commit: Nov 22, 2018 )
    * [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs.( ★ 177 , Latest commit: Dec 24, 2018 )
    * [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers.( ★★ 862 , Latest commit: Dec 24, 2018 )

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.( ★ 45 , Latest commit: Sep 10, 2017 )
    * [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.( ★ 32 , Latest commit: Oct 24, 2016 )
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.( ★ 5 , Latest commit: Sep 14, 2016 )
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.( ★★★★ 3447 , Latest commit: Nov 15, 2018 )
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.( ★★★ 1057 , Latest commit: Dec 22, 2018 )
    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.( ★★★★★ 6555 , Latest commit: Oct 27, 2018 )
    * [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go.( ★★ 519 , Latest commit: Dec 8, 2018 )
    * [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.( ★ 174 , Latest commit: Dec 25, 2018 )
    * [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.( ★ 8 , Latest commit: Nov 18, 2018 )
    * [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.( ★ 3 , Latest commit: Aug 21, 2017 )
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.( ★ 27 , Latest commit: Nov 20, 2018 )
    * [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).( ★ 5 , Latest commit:  )
    * [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa.( ★ 3 , Latest commit: Sep 26, 2018 )
    * [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.( ★ 48 , Latest commit:  )
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).( ★ 14 , Latest commit: Aug 10, 2018 )
    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.( ★★★ 1661 , Latest commit: Jun 22, 2018 )
    * [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.( ★ 69 , Latest commit: Dec 18, 2018 )
    * [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.( ★ 170 , Latest commit: Dec 18, 2018 )
    * [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.( ★ 23 , Latest commit: Aug 13, 2016 )
    * [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.( ★ 14 , Latest commit: Oct 1, 2018 )
    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.( ★ 37 , Latest commit: Dec 16, 2018 )
    * [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.( ★★ 947 , Latest commit: Oct 10, 2018 )
    * [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.( ★ 232 , Latest commit: Oct 13, 2018 )
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.( ★ 262 , Latest commit: Dec 19, 2018 )
    * [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.( ★ 28 , Latest commit:  )
    * [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).( ★ 121 , Latest commit: May 24, 2018 )
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.( ★★★★★ 6620 , Latest commit: Nov 15, 2018 )
    * [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.( ★ 33 , Latest commit: Mar 3, 2016 )
    * [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.( ★ 192 , Latest commit: Dec 21, 2018 )
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.( ★ 39 , Latest commit: Dec 16, 2014 )
    * [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.( ★ 55 , Latest commit: Dec 7, 2018 )
    * [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.( ★★★ 1041 , Latest commit: Jul 5, 2018 )
    * [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.( ★ 299 , Latest commit: Dec 17, 2018 )
    * [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)].( ★ 48 , Latest commit: Aug 28, 2018 )
    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter.( ★★★ 1534 , Latest commit: Dec 16, 2018 )
    * [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.( ★ 306 , Latest commit: Dec 13, 2018 )
    * [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.( ★ 24 , Latest commit: May 1, 2018 )
    * [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0.( ★ 4 , Latest commit: Mar 12, 2018 )
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).( ★★★ 2376 , Latest commit: Aug 15, 2018 )
* Utility
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.( ★ 9 , Latest commit: Nov 18, 2018 )
    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.( ★ 188 , Latest commit: Mar 16, 2017 )
    * [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.( ★ 8 , Latest commit:  )
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.( ★ 4 , Latest commit: Jan 25, 2017 )
    * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.( ★ 23 , Latest commit:  )
    * [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm.( ★ 58 , Latest commit: Mar 8, 2018 )
    * [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.( ★ 15 , Latest commit: Dec 22, 2018 )
    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text.( ★ 391 , Latest commit: Oct 21, 2018 )

## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).( ★ 34 , Latest commit: Dec 3, 2016 )
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.( ★★ 932 , Latest commit: Oct 15, 2018 )
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.( ★★★★ 4401 , Latest commit: Dec 21, 2018 )
* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.( ★ 14 , Latest commit: Jun 18, 2015 )
* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).( ★ 57 , Latest commit: Apr 5, 2018 )
* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.( ★ 34 , Latest commit: Dec 15, 2018 )
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.( ★ 58 , Latest commit: Aug 28, 2017 )
* [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.( ★ 15 , Latest commit: Nov 16, 2018 )
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.( ★ 3 , Latest commit: Dec 17, 2018 )
* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.( ★★ 753 , Latest commit: Nov 2, 2018 )
* [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.( ★ 145 , Latest commit: Oct 10, 2018 )
* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.( ★★ 705 , Latest commit: Dec 25, 2018 )
* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.( ★ 29 , Latest commit: Nov 28, 2018 )
* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.( ★ 38 , Latest commit: Sep 8, 2015 )
* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.( ★ 26 , Latest commit:  )
* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.( ★ 30 , Latest commit: Dec 4, 2015 )
* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.( ★ 272 , Latest commit: Nov 14, 2018 )
* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.( ★★★★ 4173 , Latest commit: Dec 22, 2018 )
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.( ★ 358 , Latest commit: Dec 15, 2018 )
* [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler( ★ 3 , Latest commit:  )
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.( ★ 7 , Latest commit:  )
* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)( ★ 9 , Latest commit: Sep 22, 2018 )
* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)( ★ 373 , Latest commit: Nov 21, 2018 )
* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.( ★ 178 , Latest commit: Jul 6, 2018 )
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).( ★ 15 , Latest commit: Mar 11, 2017 )
* [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.( ★ 2 , Latest commit:  )
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.( ★ 5 , Latest commit:  )
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.( ★ 80 , Latest commit: Jun 25, 2018 )
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.( ★ 95 , Latest commit: Aug 26, 2018 )
* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.( ★ 14 , Latest commit: Aug 20, 2017 )
* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.( ★★ 568 , Latest commit: Dec 17, 2018 )
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.( ★ 15 , Latest commit: Jul 15, 2018 )
* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.( ★ 36 , Latest commit:  )
* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.( ★ 28 , Latest commit: Jun 30, 2018 )
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.( ★ 31 , Latest commit: Oct 8, 2018 )
* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.( ★★★ 1640 , Latest commit: Dec 20, 2018 )
* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.( ★ 11 , Latest commit: May 30, 2015 )
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.( ★★★ 1476 , Latest commit: Dec 19, 2018 )
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).( ★ 5 , Latest commit:  )
* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.( ★ 116 , Latest commit: Oct 9, 2017 )
* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.( ★ 19 , Latest commit: Dec 5, 2018 )
* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.( ★ 108 , Latest commit: Mar 24, 2016 )
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.( ★ 113 , Latest commit:  )
* [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).( ★ 20 , Latest commit: Jan 10, 2018 )
* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.( ★ 106 , Latest commit: Dec 31, 2017 )
* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.( ★ 56 , Latest commit: Apr 24, 2018 )
* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.( ★ 9 , Latest commit: Feb 15, 2018 )
* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.( ★★ 578 , Latest commit: Nov 30, 2018 )
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.( ★ 26 , Latest commit: Sep 25, 2018 )
* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.( ★ 14 , Latest commit: Aug 7, 2018 )
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API.( ★ 264 , Latest commit: Dec 16, 2018 )
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.( ★ 1 , Latest commit: Mar 6, 2016 )
* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.( ★ 50 , Latest commit: Feb 9, 2018 )
* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.( ★ 8 , Latest commit:  )
* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.( ★ 19 , Latest commit: Jan 21, 2015 )
* [slack](https://github.com/nlopes/slack) - Slack API in Go.( ★★★ 1965 , Latest commit: Nov 18, 2018 )
* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.( ★ 9 , Latest commit:  )
* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.( ★ 16 , Latest commit: Oct 31, 2017 )
* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.( ★ 13 , Latest commit: Mar 13, 2018 )
* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.( ★★ 819 , Latest commit: Dec 13, 2018 )
* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.( ★ 172 , Latest commit: Dec 16, 2018 )
* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.( ★★ 780 , Latest commit: Dec 13, 2018 )
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.( ★★★ 1304 , Latest commit: Dec 25, 2018 )
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.( ★ 12 , Latest commit:  )
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org).( ★ 11 , Latest commit:  )
* [translate](https://github.com/poorny/translate) - Go online translation package.( ★ 25 , Latest commit:  )
* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.( ★ 73 , Latest commit: Oct 9, 2018 )
* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.( ★ 6 , Latest commit:  )
* [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API.( ★ 28 , Latest commit: Dec 8, 2018 )
* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.( ★ 255 , Latest commit: Dec 8, 2018 )
* [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.( ★ 19 , Latest commit: Nov 1, 2018 )
* [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.( ★ 7 , Latest commit: Dec 20, 2018 )
* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.( ★ 4 , Latest commit: Jun 5, 2018 )

## Utilities

*General utilities and tools to make your life easier.*

* [abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers.( ★ 50 , Latest commit: Sep 2, 2015 )
* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.( ★ 118 , Latest commit: Nov 24, 2016 )
* [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.( ★ 6 , Latest commit: Feb 26, 2018 )
* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.( ★★ 811 , Latest commit: Jul 19, 2017 )
* [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.( ★ 97 , Latest commit: Dec 3, 2018 )
* [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.( ★ 219 , Latest commit: Oct 30, 2018 )
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.( ★★ 714 , Latest commit: Mar 31, 2017 )
* [clockwerk](https://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.( ★ 49 , Latest commit: Apr 15, 2017 )
* [clockwork](https://github.com/whiteShtef/clockwork) - Simple and intuitive job scheduling library in Go.( ★ 35 , Latest commit: May 28, 2018 )
* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.( ★ 9 , Latest commit: Apr 21, 2016 )
* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.( ★ 31 , Latest commit:  )
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.( ★★★★★ 7747 , Latest commit: Dec 1, 2018 )
* [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.( ★ 0 , Latest commit: Oct 26, 2018 )
* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.( ★ 107 , Latest commit: Oct 23, 2018 )
* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.( ★ 179 , Latest commit: Nov 7, 2017 )
* [delve](https://github.com/derekparker/delve) - Go debugger.( ★★★★★ 10098 , Latest commit: Dec 3, 2018 )
* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.( ★ 15 , Latest commit: Jul 28, 2017 )
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.( ★ 248 , Latest commit: Nov 29, 2018 )
* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.( ★ 12 , Latest commit: Jan 29, 2018 )
* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.( ★★★★ 2837 , Latest commit: Dec 26, 2018 )
* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang.( ★ 10 , Latest commit: Feb 9, 2015 )
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.( ★ 401 , Latest commit: Dec 20, 2018 )
* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.( ★ 14 , Latest commit: Apr 10, 2017 )
* [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.( ★ 5 , Latest commit: Dec 19, 2018 )
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.( ★★★★★ 18586 , Latest commit: Dec 22, 2018 )
* [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.( ★ 29 , Latest commit: Nov 18, 2018 )
* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.( ★ 15 , Latest commit: Jan 10, 2017 )
* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.( ★★ 628 , Latest commit: Jul 4, 2018 )
* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.( ★★★★ 3738 , Latest commit: Oct 28, 2018 )
* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.( ★ 42 , Latest commit: Aug 11, 2018 )
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).( ★ 157 , Latest commit: Aug 27, 2017 )
* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.( ★ 169 , Latest commit: Apr 19, 2013 )
* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.( ★ 414 , Latest commit: Apr 11, 2018 )
* [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table.( ★ 32 , Latest commit: Dec 22, 2018 )
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).( ★★ 642 , Latest commit: Oct 20, 2018 )
* [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.( ★ 57 , Latest commit: Jun 13, 2018 )
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.( ★ 14 , Latest commit: Nov 3, 2018 )
* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.( ★ 276 , Latest commit: Apr 8, 2018 )
* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.( ★ 14 , Latest commit: Oct 20, 2018 )
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.( ★ 89 , Latest commit: Oct 28, 2018 )
* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs.( ★★★★ 3417 , Latest commit: Nov 6, 2018 )
* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.( ★ 163 , Latest commit: Mar 28, 2017 )
* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.( ★ 38 , Latest commit: Mar 15, 2015 )
* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.( ★ 377 , Latest commit: Sep 11, 2015 )
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.( ★★★★ 3623 , Latest commit: May 13, 2018 )
* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.( ★ 250 , Latest commit: Aug 12, 2017 )
* [gojq](https://github.com/elgs/gojq) - JSON query in Golang.( ★ 128 , Latest commit: Apr 21, 2016 )
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.( ★★★ 1876 , Latest commit: Aug 18, 2018 )
* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events.( ★ 32 , Latest commit:  )
* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.( ★ 41 , Latest commit:  )
* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.( ★ 414 , Latest commit: Nov 13, 2016 )
* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.( ★ 21 , Latest commit: Jan 17, 2016 )
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.( ★★★★ 3565 , Latest commit: Dec 23, 2018 )
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.( ★★★ 2278 , Latest commit: Sep 2, 2018 )
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.( ★ 15 , Latest commit: Aug 4, 2017 )
* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.( ★ 117 , Latest commit: Jun 5, 2018 )
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.( ★ 11 , Latest commit: Apr 20, 2018 )
* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.( ★ 25 , Latest commit: Jun 4, 2017 )
* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.( ★★ 534 , Latest commit: Jun 21, 2016 )
* [gubrak](https://gubrak.github.io/) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.( ★ 466 , Latest commit: Jun 8, 2015 )
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.( ★★★★★ 14295 , Latest commit: Dec 21, 2018 )
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.( ★★★ 1523 , Latest commit: May 2, 2018 )
* [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor.( ★★ 558 , Latest commit: Dec 17, 2018 )
* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.( ★ 36 , Latest commit: Jun 22, 2017 )
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.( ★★ 500 , Latest commit: Oct 19, 2016 )
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.( ★ 5 , Latest commit:  )
* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.( ★ 53 , Latest commit: Jul 8, 2016 )
* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.( ★ 84 , Latest commit: Dec 15, 2016 )
* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.( ★ 8 , Latest commit:  )
* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.( ★ 100 , Latest commit: Aug 29, 2018 )
* [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.( ★ 95 , Latest commit: Dec 16, 2018 )
* [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.( ★ 8 , Latest commit: Nov 30, 2018 )
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.( ★ 97 , Latest commit: Nov 30, 2017 )
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.( ★★ 889 , Latest commit: Dec 22, 2018 )
* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.( ★★ 637 , Latest commit: Nov 7, 2018 )
* [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.( ★ 34 , Latest commit: Oct 29, 2018 )
* [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.( ★ 1 , Latest commit: Dec 21, 2018 )
* [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers.( ★ 47 , Latest commit: Dec 2, 2018 )
* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.( ★★★ 1631 , Latest commit: Dec 10, 2018 )
* [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).( ★ 42 , Latest commit: Jun 24, 2018 )
* [mmake](https://github.com/tj/mmake) - Modern Make.( ★★★ 1434 , Latest commit: Jan 10, 2018 )
* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.( ★ 146 , Latest commit: Sep 4, 2017 )
* [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.( ★★★ 1210 , Latest commit: Dec 6, 2018 )
* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.( ★ 29 , Latest commit:  )
* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.( ★ 48 , Latest commit:  )
* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.( ★ 57 , Latest commit:  )
* [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.( ★ 26 , Latest commit: May 6, 2018 )
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.( ★ 65 , Latest commit: Oct 30, 2015 )
* [okrun](https://github.com/xta/okrun) - go run error steamroller.( ★ 13 , Latest commit:  )
* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).( ★ 80 , Latest commit: Aug 28, 2018 )
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.( ★★★ 1811 , Latest commit: Aug 6, 2018 )
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.( ★★★★★ 5036 , Latest commit: Oct 25, 2018 )
* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.( ★ 63 , Latest commit: Dec 11, 2018 )
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.( ★★ 851 , Latest commit: Oct 29, 2018 )
* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.( ★ 21 , Latest commit: Aug 29, 2018 )
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.( ★★★★ 2683 , Latest commit: Sep 18, 2018 )
* [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.( ★ 52 , Latest commit: May 7, 2018 )
* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.( ★ 334 , Latest commit: Oct 24, 2017 )
* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.( ★ 11 , Latest commit: Mar 28, 2017 )
* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.( ★ 150 , Latest commit: Mar 31, 2017 )
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.( ★★★ 1466 , Latest commit: Dec 21, 2018 )
* [retry](https://github.com/kamilsk/retry) - Functional mechanism based on context to perform actions repetitively until successful.( ★ 71 , Latest commit: Oct 6, 2018 )
* [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go.( ★ 2 , Latest commit:  )
* [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.( ★ 28 , Latest commit: Mar 22, 2018 )
* [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done.( ★ 7 , Latest commit: Aug 27, 2018 )
* [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.( ★ 24 , Latest commit:  )
* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.( ★ 129 , Latest commit: Mar 24, 2018 )
* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.( ★ 256 , Latest commit: Jan 9, 2017 )
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.( ★★ 628 , Latest commit: Oct 29, 2018 )
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.( ★★★★★ 5456 , Latest commit: Oct 24, 2018 )
* [sslice](https://github.com/yaa110/sslice) - Create a slice which is always sorted.( ★ 1 , Latest commit: Nov 17, 2018 )
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.( ★★★ 1186 , Latest commit: Dec 22, 2018 )
* [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.( ★ 9 , Latest commit:  )
* [Task](https://github.com/go-task/task) - simple "Make" alternative.( ★★★ 1071 , Latest commit: Dec 24, 2018 )
* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.( ★ 46 , Latest commit: Dec 25, 2018 )
* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.( ★ 19 , Latest commit: Jun 30, 2016 )
* [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.( ★ 67 , Latest commit: May 9, 2017 )
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.( ★★★★ 4444 , Latest commit: Dec 20, 2018 )
* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).( ★ 97 , Latest commit: Jun 7, 2018 )
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.( ★★★★★ 7815 , Latest commit: Oct 5, 2018 )
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.( ★ 65 , Latest commit: Aug 20, 2016 )
* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.( ★★★★ 2895 , Latest commit: Oct 24, 2018 )
* [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.( ★ 28 , Latest commit: Aug 21, 2018 )

## Validation

*Libraries for validation.*

* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.( ★★★★ 3040 , Latest commit: Jul 20, 2018 )
* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.( ★★ 527 , Latest commit: Nov 22, 2018 )
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.( ★★ 837 , Latest commit: Nov 16, 2018 )
* [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.( ★ 30 , Latest commit: Dec 23, 2018 )
* [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications.( ★ 10 , Latest commit: Nov 10, 2018 )
* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.( ★★★★ 2508 , Latest commit: Dec 8, 2018 )

## Version Control

*Libraries for version control.*

* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.( ★ 64 , Latest commit: Jul 25, 2017 )
* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.( ★★★ 1242 , Latest commit: Dec 17, 2018 )
* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.( ★ 64 , Latest commit: Sep 26, 2018 )
* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.( ★ 12 , Latest commit: Aug 25, 2015 )

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.( ★ 430 , Latest commit: Dec 4, 2018 )
* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).( ★ 139 , Latest commit: Jul 28, 2018 )
* [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.( ★ 222 , Latest commit: Feb 25, 2018 )
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) - Parser and generator library for Apple m3u8 playlists.( ★ 20 , Latest commit: Nov 8, 2018 )
* [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg.( ★★ 571 , Latest commit: Nov 22, 2018 )
* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer.( ★ 147 , Latest commit: Jul 25, 2018 )
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.( ★ 9 , Latest commit: Dec 4, 2018 )
* [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).( ★ 32 , Latest commit:  )
* [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.( ★ 20 , Latest commit: May 20, 2018 )

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Aero](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse.( ★ 78 , Latest commit: Dec 12, 2018 )
* [Air](https://github.com/aofei/air) - An ideally refined web framework for Go.( ★ 103 , Latest commit: Dec 25, 2018 )
* [Banjo](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go.( ★ 3 , Latest commit: Jan 31, 2018 )
* [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.( ★★★★★ 18349 , Latest commit: Dec 19, 2018 )
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.( ★★★★★ 12492 , Latest commit: Dec 5, 2018 )
* [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.( ★ 42 , Latest commit: Oct 3, 2018 )
* [Gem](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API.( ★ 151 , Latest commit: Mar 19, 2017 )
* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.( ★★★★★ 23152 , Latest commit: Dec 25, 2018 )
* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.( ★★★★ 2494 , Latest commit: Dec 11, 2018 )
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.( ★★★★ 3221 , Latest commit: Sep 12, 2017 )
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.( ★ 111 , Latest commit: Jan 20, 2017 )
* [goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis.( ★★★★ 3187 , Latest commit: Dec 22, 2018 )
* [Golax](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more.( ★ 64 , Latest commit: Jun 3, 2018 )
* [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.( ★ 227 , Latest commit: Feb 24, 2017 )
* [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.( ★ 312 , Latest commit: Feb 21, 2017 )
* [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.( ★ 406 , Latest commit: Nov 16, 2017 )
* [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support.( ★ 51 , Latest commit: Dec 10, 2018 )
* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.( ★★★★ 2625 , Latest commit: Dec 16, 2018 )
* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.( ★ 332 , Latest commit: Oct 17, 2017 )
* [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.( ★ 48 , Latest commit: Dec 27, 2017 )
* [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.( ★ 381 , Latest commit: Aug 14, 2017 )
* [nio](https://github.com/go-nio/nio) - Modern, minimal and productive Go HTTP framework.( ★ 4 , Latest commit: Dec 20, 2018 )
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.( ★ 29 , Latest commit:  )
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.( ★★★★★ 10614 , Latest commit: Oct 30, 2018 )
* [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.( ★ 24 , Latest commit: Dec 22, 2017 )
* [sawsij](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications.( ★ 2 , Latest commit: Apr 28, 2014 )
* [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.( ★★ 752 , Latest commit: Sep 15, 2018 )
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.( ★★ 990 , Latest commit: Apr 20, 2017 )
* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go.( ★★ 513 , Latest commit: Nov 26, 2015 )
* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).( ★★★ 2104 , Latest commit: Oct 28, 2018 )
* [vox](https://github.com/aisk/vox) - A golang web framework for humans, inspired by Koa heavily.( ★ 12 , Latest commit: Dec 7, 2018 )
* [WebGo](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc).( ★ 58 , Latest commit: Oct 11, 2018 )
* [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.( ★ 45 , Latest commit: Sep 14, 2017 )
* [Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework.( ★ 143 , Latest commit: May 8, 2016 )

### Middlewares

#### Actual middlewares

* [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header.( ★ 10 , Latest commit: Feb 27, 2018 )
* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.( ★★ 966 , Latest commit: Oct 11, 2018 )
* [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.( ★ 30 , Latest commit:  )
* [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.( ★★ 721 , Latest commit: Aug 23, 2018 )
* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.( ★ 438 , Latest commit: Nov 7, 2018 )
* [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin)( ★ 74 , Latest commit: Oct 7, 2018 )
* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.( ★★★ 1037 , Latest commit: Apr 16, 2018 )
* [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.( ★ 68 , Latest commit: Sep 10, 2016 )

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.( ★★★ 1689 , Latest commit: Oct 23, 2017 )
* [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").( ★ 7 , Latest commit:  )
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").( ★ 64 , Latest commit:  )
* [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http.( ★ 54 , Latest commit:  )
* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.( ★ 77 , Latest commit:  )
* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.( ★ 287 , Latest commit: Dec 7, 2016 )
* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.( ★ 202 , Latest commit: Oct 27, 2014 )
* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.( ★★★★★ 5971 , Latest commit: Dec 1, 2018 )
* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.( ★★★ 1174 , Latest commit: Dec 10, 2018 )
* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.( ★ 133 , Latest commit: Dec 19, 2018 )
* [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.( ★ 88 , Latest commit: Oct 4, 2018 )
* [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.( ★★ 511 , Latest commit: Dec 18, 2018 )

### Routers

* [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.( ★ 93 , Latest commit: Jan 29, 2018 )
* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.( ★★★ 1183 , Latest commit: Sep 10, 2018 )
* [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.( ★ 90 , Latest commit: Aug 30, 2018 )
* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.( ★★★★ 4720 , Latest commit: Dec 21, 2018 )
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.( ★★ 620 , Latest commit: Feb 11, 2018 )
* [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.( ★ 18 , Latest commit: Nov 1, 2017 )
* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.( ★★★ 1352 , Latest commit: Sep 25, 2017 )
* [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.( ★★ 691 , Latest commit: Dec 15, 2018 )
* [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.( ★ 36 , Latest commit: Jun 25, 2018 )
* [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.( ★ 153 , Latest commit:  )
* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.( ★★★★★ 8330 , Latest commit: Oct 22, 2018 )
* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.( ★ 363 , Latest commit: Dec 18, 2018 )
* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.( ★ 364 , Latest commit: Oct 31, 2017 )
* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.( ★★★★★ 7796 , Latest commit: Dec 25, 2018 )
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.( ★ 312 , Latest commit: Feb 10, 2018 )
* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.( ★ 69 , Latest commit: Sep 11, 2017 )
* [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.( ★ 347 , Latest commit: Aug 24, 2018 )
* [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.( ★ 238 , Latest commit: May 14, 2018 )
* [violetear](https://github.com/nbari/violetear) - Go HTTP router.( ★ 91 , Latest commit: Sep 12, 2018 )
* [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.( ★ 87 , Latest commit: Jun 9, 2017 )
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go.( ★ 364 , Latest commit: Dec 20, 2018 )

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.( ★ 77 , Latest commit: Apr 12, 2018 )
* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.( ★ 473 , Latest commit: Dec 14, 2018 )

## XML

*Libraries and tools for manipulating XML.*

* [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.( ★ 15 , Latest commit: Jul 19, 2018 )
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.( ★ 6 , Latest commit:  )
* [xpath](https://github.com/antchfx/xpath) - XPath package for Go.( ★ 102 , Latest commit: Dec 8, 2018 )
* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.( ★ 140 , Latest commit: May 15, 2018 )
* [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang.( ★ 9 , Latest commit: Nov 10, 2018 )
# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.( ★ 155 , Latest commit: Feb 5, 2017 )
* [dupl](https://github.com/mibk/dupl) - Tool for code clone detection.( ★ 130 , Latest commit: Oct 11, 2018 )
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.( ★★★ 1176 , Latest commit: Aug 7, 2018 )
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.( ★★ 862 , Latest commit: Dec 22, 2017 )
* [Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form.( ★★★★ 3371 , Latest commit: Dec 16, 2018 )
* [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments.( ★ 88 , Latest commit: Nov 22, 2018 )
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.( ★ 235 , Latest commit: May 14, 2018 )
* [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters.( ★ 423 , Latest commit: Dec 21, 2018 )
* [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.( ★ 46 , Latest commit: Mar 25, 2016 )
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.( ★ 314 , Latest commit: Dec 6, 2017 )
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GolangCI](https://golangci.com/) - GolangCI is an automated Golang code review service for GitHub pull requests. Service is open source and it's free for open source projects.
* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code.( ★★★★ 2800 , Latest commit: Dec 14, 2018 )
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.( ★★★ 1965 , Latest commit: Apr 3, 2018 )
* [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.( ★ 231 , Latest commit: Sep 19, 2017 )
* [lint](https://github.com/surullabs/lint) - Run linters as part of go test.( ★ 61 , Latest commit: Oct 3, 2017 )
* [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go.( ★★ 541 , Latest commit: Nov 5, 2018 )
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.( ★★★ 1965 , Latest commit: Aug 5, 2017 )
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.( ★ 11 , Latest commit:  )
* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.( ★ 230 , Latest commit: Jul 3, 2018 )
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.( ★★★ 1965 , Latest commit: Nov 8, 2017 )
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.( ★ 62 , Latest commit: Mar 29, 2016 )

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.( ★ 18 , Latest commit: Mar 1, 2018 )
* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.( ★★ 859 , Latest commit: Sep 10, 2018 )
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.( ★★★ 1427 , Latest commit: Nov 26, 2018 )
* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.( ★★★★ 4543 , Latest commit: Nov 20, 2018 )
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.( ★★★★ 3093 , Latest commit: Dec 10, 2018 )
* [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.( ★ 15 , Latest commit: Oct 29, 2018 )
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE.( ★ 8 , Latest commit: Dec 4, 2018 )
* [velour](https://github.com/velour/velour) - IRC client for the acme editor.( ★ 16 , Latest commit: Mar 3, 2016 )
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.( ★ 78 , Latest commit: Jun 28, 2016 )
* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.( ★★★★★ 9627 , Latest commit: Dec 24, 2018 )
* [vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.( ★★★★ 4298 , Latest commit: Dec 17, 2018 )
* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.( ★ 156 , Latest commit: Mar 25, 2018 )

## Go Generate Tools

* [generic](https://github.com/usk81/generic) - flexible data type for Go.( ★ 24 , Latest commit: Aug 20, 2018 )
* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go.( ★★ 771 , Latest commit: Aug 30, 2018 )
* [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation.( ★ 31 , Latest commit: Nov 13, 2018 )
* [gonerics](https://github.com/bouk/gonerics) - Idiomatic Generics in Go.( ★ 108 , Latest commit: Sep 29, 2014 )
* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.( ★★★ 1585 , Latest commit: Oct 29, 2018 )
* [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates.( ★ 17 , Latest commit:  )
* [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.( ★ 161 , Latest commit: Sep 11, 2018 )

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.( ★ 95 , Latest commit: Oct 27, 2016 )
* [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.( ★ 287 , Latest commit: Feb 14, 2018 )
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](http://yeoman.io) generator to get new Go projects started.( ★ 8 , Latest commit: Jan 19, 2018 )
* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.( ★★★ 1408 , Latest commit: Sep 22, 2018 )
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.( ★ 37 , Latest commit: Nov 17, 2017 )
* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.( ★★★★ 3037 , Latest commit: Dec 25, 2018 )
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.( ★★★★ 3109 , Latest commit: Dec 18, 2018 )
* [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.( ★ 315 , Latest commit: May 13, 2018 )
* [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.( ★ 179 , Latest commit: Dec 6, 2016 )

## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.( ★★★ 1647 , Latest commit: Oct 10, 2018 )
* [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.( ★ 343 , Latest commit: Dec 21, 2018 )
* [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.( ★ 17 , Latest commit: Jul 17, 2018 )
* [Banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics.( ★★★ 1016 , Latest commit: Jan 17, 2018 )
* [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.( ★ 155 , Latest commit: Mar 1, 2018 )
* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.( ★★★ 1266 , Latest commit: Dec 24, 2018 )
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.( ★★★★ 2747 , Latest commit: Nov 16, 2018 )
* [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects.( ★ 6 , Latest commit:  )
* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).( ★ 200 , Latest commit: Nov 2, 2016 )
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.( ★ 16 , Latest commit: Nov 11, 2018 )
* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.( ★ 42 , Latest commit: Nov 5, 2018 )
* [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.( ★ 43 , Latest commit: Jul 25, 2018 )
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.( ★ 70 , Latest commit: Nov 6, 2018 )
* [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts.( ★★★ 1521 , Latest commit: Sep 8, 2018 )
* [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.( ★★★★ 2525 , Latest commit: Dec 14, 2018 )
* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.( ★★★★★ 11385 , Latest commit: Dec 24, 2018 )
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
* [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.( ★ 51 , Latest commit: Dec 17, 2018 )
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.( ★★ 627 , Latest commit: Dec 16, 2016 )
* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.( ★ 173 , Latest commit: Nov 4, 2015 )
* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.( ★ 216 , Latest commit: Jul 9, 2018 )
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.( ★ 299 , Latest commit: Jul 22, 2016 )
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.( ★ 304 , Latest commit: Nov 2, 2017 )
* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.( ★★★★ 3026 , Latest commit: Oct 25, 2018 )
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.( ★★★ 1586 , Latest commit: Mar 2, 2018 )
* [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.( ★ 115 , Latest commit: Nov 28, 2017 )
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.( ★★★★ 4013 , Latest commit: Jul 18, 2018 )
* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.( ★★★★ 4608 , Latest commit: Oct 18, 2018 )
* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.( ★★★ 1282 , Latest commit: Jul 13, 2018 )
* [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages.( ★ 48 , Latest commit: Aug 23, 2018 )
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.( ★★★★★ 45832 , Latest commit: Dec 26, 2018 )
* [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries.( ★ 197 , Latest commit: Dec 7, 2018 )
* [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.( ★ 7 , Latest commit:  )
* [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.( ★ 188 , Latest commit: Jun 21, 2018 )
* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.( ★★★★★ 51636 , Latest commit: Dec 25, 2018 )
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.( ★ 253 , Latest commit: Jan 9, 2017 )
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.( ★ 158 , Latest commit: Apr 4, 2018 )
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.( ★★★★★ 8354 , Latest commit: Dec 20, 2018 )
* [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.( ★ 175 , Latest commit: Oct 26, 2018 )
* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.( ★ 31 , Latest commit:  )
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.( ★★ 956 , Latest commit: Feb 10, 2017 )
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).( ★ 478 , Latest commit: Sep 28, 2018 )
* [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.( ★ 3 , Latest commit:  )
* [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!( ★ 478 , Latest commit: Nov 10, 2018 )
* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.( ★★★ 1021 , Latest commit: Nov 1, 2018 )
* [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.( ★★★★★ 19424 , Latest commit: Dec 14, 2018 )
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!( ★★★★★ 10211 , Latest commit: Dec 19, 2018 )
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.( ★★★★ 3409 , Latest commit: Nov 16, 2018 )
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.( ★ 49 , Latest commit: Apr 26, 2018 )

### Other Software
* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.( ★★★ 1388 , Latest commit: Feb 7, 2018 )
* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine.( ★ 71 , Latest commit: Aug 9, 2018 )
* [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.( ★ 180 , Latest commit: Dec 14, 2016 )
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.( ★★★ 1717 , Latest commit: Nov 21, 2016 )
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.( ★★★★★ 5875 , Latest commit: Oct 20, 2018 )
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.( ★★★★★ 5710 , Latest commit: Jul 16, 2018 )
* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.( ★ 63 , Latest commit: Nov 18, 2018 )
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.( ★★ 547 , Latest commit: Nov 21, 2018 )
* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline.( ★★★★ 4564 , Latest commit: Nov 12, 2018 )
* [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.( ★★★★ 2423 , Latest commit: Nov 9, 2018 )
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.( ★★ 866 , Latest commit: Dec 15, 2018 )
* [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go.( ★★★ 1845 , Latest commit: Nov 27, 2018 )
* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.( ★ 303 , Latest commit: Nov 17, 2018 )
* [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.( ★ 313 , Latest commit: Dec 26, 2018 )
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.( ★ 12 , Latest commit:  )
* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.( ★★★★★ 10068 , Latest commit: Aug 24, 2018 )
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.( ★ 239 , Latest commit: Dec 22, 2018 )
* [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.( ★ 243 , Latest commit: Dec 19, 2018 )
* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.( ★ 30 , Latest commit: Dec 6, 2018 )
* [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together.( ★ 110 , Latest commit: Dec 6, 2018 )
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.( ★★ 622 , Latest commit: Dec 23, 2018 )
* [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.( ★★★ 1512 , Latest commit: Jul 23, 2018 )
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.( ★★★★★ 4987 , Latest commit: Dec 24, 2018 )
* [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.( ★ 379 , Latest commit: Nov 9, 2018 )
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.( ★★★ 2109 , Latest commit: Aug 16, 2017 )
* [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.( ★ 20 , Latest commit:  )
* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.( ★★★★ 3878 , Latest commit: Feb 22, 2018 )
* [orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go.( ★ 172 , Latest commit: Sep 12, 2015 )
* [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.( ★ 118 , Latest commit: Jun 17, 2018 )
* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.( ★★ 538 , Latest commit: Nov 6, 2018 )
* [Pipe](https://github.com/b3log/pipe) - A small and beautiful blogging platform.( ★★★ 1764 , Latest commit: Dec 26, 2018 )
* [restic](https://github.com/restic/restic) - De-duplicating backup program.( ★★★★★ 5725 , Latest commit: Dec 15, 2018 )
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.( ★★★★★ 8361 , Latest commit: Aug 2, 2018 )
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.( ★★★★★ 7050 , Latest commit: Dec 26, 2018 )
* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).( ★ 299 , Latest commit: Nov 14, 2018 )
* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.( ★★★ 1783 , Latest commit: Dec 20, 2018 )
* [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.( ★ 15 , Latest commit: Jul 23, 2018 )
* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.( ★★★ 1841 , Latest commit: Dec 12, 2018 )
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.( ★ 166 , Latest commit:  )
* [term-quiz](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal.( ★ 15 , Latest commit: Oct 25, 2018 )
* [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.( ★★★★ 3304 , Latest commit: Dec 18, 2018 )
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.( ★ 494 , Latest commit: Dec 19, 2018 )
* [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).( ★ 284 , Latest commit: Oct 26, 2018 )

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.( ★ 89 , Latest commit: Jun 19, 2014 )
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.( ★ 19 , Latest commit: Mar 17, 2017 )
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.( ★ 109 , Latest commit: Feb 25, 2016 )
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.( ★★★ 1177 , Latest commit: May 31, 2017 )
* [go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go.( ★ 5 , Latest commit: Oct 28, 2014 )
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.( ★★ 851 , Latest commit: Oct 15, 2018 )
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.( ★★ 737 , Latest commit: Aug 21, 2018 )
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.( ★ 51 , Latest commit: Jan 4, 2015 )
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others.( ★ 15 , Latest commit:  )
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.( ★ 48 , Latest commit: Mar 13, 2015 )
* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.( ★ 85 , Latest commit:  )
* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.( ★ 14 , Latest commit: Apr 20, 2014 )
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.( ★★ 878 , Latest commit: Oct 18, 2018 )
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.( ★ 156 , Latest commit: Mar 13, 2017 )

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA.
* [dotGo](http://www.dotgo.eu) - Paris, France.
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan.
* [GoDays](https://www.godays.io/) - Berlin, Germany.
* [GoLab](http://golab.io/) - Florence, Italy.
* [GolangUK](http://golanguk.com/) - London, UK.
* [GopherChina](http://gopherchina.org) - Shanghai, China.
* [GopherCon](http://www.gophercon.com/) - Denver, USA.
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR.
* [GopherCon Europe](https://gophercon.is/) - Reykjavik, Iceland.
* [GopherCon India](https://www.gophercon.in/) - Pune, India.
* [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
* [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
* [GothamGo](http://gothamgo.com/) - New York City, USA.
* [GoWayFest](https://goway.io/) - Minsk, Belarus.

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go Bootcamp](http://golangbootcamp.com)
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.( ★★★★★ 5763 , Latest commit: Dec 1, 2018 )
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)( ★★★ 2163 , Latest commit: Jul 9, 2018 )
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg].( ★ 26 , Latest commit: Mar 4, 2018 )
* [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos.( ★ 52 , Latest commit: Jun 27, 2018 )
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)( ★ 394 , Latest commit: Aug 23, 2016 )
* [gopher-vector](https://github.com/golang-samples/gopher-vector)( ★ 321 , Latest commit: Jul 27, 2016 )
* [gophericons](https://github.com/shalakhin/gophericons)( ★★ 553 , Latest commit: Mar 24, 2018 )
* [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself.( ★ 258 , Latest commit: Oct 1, 2018 )
* [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara.( ★★★ 1552 , Latest commit: Oct 1, 2018 )
* [gophers](https://github.com/egonelbre/gophers) - Free gophers.( ★★★ 1333 , Latest commit: Jul 24, 2018 )
* [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics.( ★ 48 , Latest commit: Mar 19, 2017 )
* [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern.( ★ 31 , Latest commit:  )

## Meetups

* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.( ★★★★★ 13153 , Latest commit: Dec 11, 2018 )
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.( ★★★★★ 22985 , Latest commit: Dec 11, 2018 )
* [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.( ★★★★★ 51118 , Latest commit:  )
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.( ★ 31 , Latest commit: Sep 23, 2017 )
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.( ★ 137 , Latest commit: Aug 24, 2015 )
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy [@francesc](https://twitter.com/francesc).
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.( ★★★★★ 26996 , Latest commit: Dec 16, 2018 )
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* [Games With Go](http://gameswithgo.org/) - A video series teaching programming and game development.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.( ★★★★ 3613 , Latest commit: Nov 12, 2018 )
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - Interactively edit & play Go snippets on your mobile device.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.( ★★★ 2383 , Latest commit: Dec 2, 2018 )
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.( ★★★ 1071 , Latest commit: Apr 7, 2018 )
* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's.
