See also:

* [Awesome Rust](https://github.com/kud1ing/awesome-rust)
* [Travis CI Status](http://hiho.io/rust-ci/)
* [Rust Kit Library Browser](http://rustkit.io/)

## Audio

* [pistondevelopers/music](https://github.com/pistondevelopers/music): high level library for playing music

See Computer Graphics and Game Development.

## Collections

* [chris-morgan/mucell](https://github.com/chris-morgan/mucell): A cell with the ability to mutate the value through an immutable reference when safe

## Compression

We want compression/decompression support for TAR and ZIP file formats.

* [alexcrichton/rust-compress](https://github.com/alexcrichton/rust-compress): compression algorithms, all written in rust [<img src="https://travis-ci.org/alexcrichton/rust-compress.png?branch=master">](https://travis-ci.org/alexcrichton/rust-compress)
* [erickt/rustzlib](https://github.com/erickt/rustzlib): libzlib bindings
* [thestinger/rust-snappy](https://github.com/thestinger/rust-snappy): libsnappy bindings

## Computation
See also [Mathematics](Community-libraries#mathematics)

* GMP
  * [thestinger/rust-gmp](https://github.com/thestinger/rust-gmp)
* OpenCL
  * [eholk/rust-opencl](https://github.com/eholk/rust-opencl): OpenCL bindings [<img src="https://travis-ci.org/eholk/rust-opencl.png?branch=master">](https://travis-ci.org/eholk/rust-opencl)

## Computer Graphics and Game Development
* Piston
   * [PistonDevelopers/piston](https://github.com/PistonDevelopers/piston): A user friendly game engine, with OpenGL, SDL, and other backends.
   * [PistonDevelopers/asset_store](https://github.com/PistonDevelopers/asset_store): Reading and caching video, audio, images, and other game files.

## Concurrency
 * task management, actor, OTP, [[Bikeshed mapreduce]], pools
 
## Crypto

* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto): [<img src="https://travis-ci.org/DaGenix/rust-crypto.png?branch=master">](https://travis-ci.org/DaGenix/rust-crypto)
* LibNSS
  * [mletterle/rust-nss](https://github.com/mletterle/rust-nss)
* libsodium
  * [dnaq/sodiumoxide](https://github.com/dnaq/sodiumoxide)
* OpenSSL
  * [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl): [<img src="https://travis-ci.org/sfackler/rust-openssl.png?branch=master">](https://travis-ci.org/sfackler/rust-openssl)

## Database Access

* NoSql
  * LevelDB
      * [thestinger/rust-leveldb](https://github.com/thestinger/rust-leveldb)
  * LMDB
      * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs)
  * MongoDB
      * [10gen-interns/mongo-rust-driver-prototype](https://github.com/10gen-interns/mongo-rust-driver-prototype)
  * Redis
      * [mitsuhiko/redis-rs](https://github.com/mitsuhiko/redis-rs) [<img src="https://travis-ci.org/mitsuhiko/redis-rs.png?branch=master">](https://travis-ci.org/mitsuhiko/redis-rs)
      * [mneumann/rust-redis](https://github.com/mneumann/rust-redis) [<img src="https://travis-ci.org/mneumann/rust-redis.png?branch=master">](https://travis-ci.org/mneumann/rust-redis)
* SQL
  * [wycats/rust-arel](https://github.com/wycats/rust-arel): An in-progress port of the Ruby SQL building library arel
  * MySql
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple): [<img src="https://travis-ci.org/blackbeam/rust-mysql-simple.png?branch=master">](https://travis-ci.org/blackbeam/rust-mysql-simple)
  * PostgreSql
      * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres): [<img src="https://travis-ci.org/sfackler/rust-postgres.png?branch=master">](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite
      * [linuxfood/rustsqlite](https://github.com/linuxfood/rustsqlite): Sqlite3 bindings [<img src="https://travis-ci.org/kud1ing/rustsqlite.png?branch=master">](https://travis-ci.org/kud1ing/rustsqlite)
 
## Date and Time

Wanted library: [[Lib datetime]]

  * [lifthrasiir/rust-chrono](https://github.com/lifthrasiir/rust-chrono)
  * [luisbg/rust-datetime](https://github.com/luisbg/rust-datetime)
  * [tedhorst/rust_datetime](https://github.com/tedhorst/rust_datetime)
  
## Embedded Languages
* Lua
  * [kballard/rust-lua](https://github.com/kballard/rust-lua) (Lua 5.1): [<img src="https://travis-ci.org/kballard/rust-lua.png?branch=master">](https://travis-ci.org/kballard/rust-lua)
  * [tomaka/rust-hl-lua](https://github.com/tomaka/rust-hl-lua) (Lua 5.2)
* Python
  * [lukemetz/rustpy](https://github.com/lukemetz/rustpy)

## Encoding
* [Base64](https://github.com/mozilla/rust/blob/master/src/libserialize/base64.rs)
* Cap'n Proto
    * [dwrensha/capnproto-rust](https://github.com/dwrensha/capnproto-rust):  [<img src="https://travis-ci.org/dwrensha/capnproto-rust.png?branch=master">](https://travis-ci.org/dwrensha/capnproto-rust)
* Character Encoding
    * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding): [<img src="https://travis-ci.org/lifthrasiir/rust-encoding.png?branch=rust-0.9-pre">](https://travis-ci.org/lifthrasiir/rust-encoding)
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv): [<img src="https://api.travis-ci.org/BurntSushi/rust-csv.png">](https://travis-ci.org/BurntSushi/rust-csv)
  * [Geal/rust-csv](https://github.com/Geal/rust-csv): [<img src="https://travis-ci.org/Geal/rust-csv.png?branch=master">](https://travis-ci.org/Geal/rust-csv)
* Erlang External Term Format [(about)](http://erlang.org/doc/apps/erts/erl_ext_dist.html)
  * [seriyps/rust-erl-ext](https://github.com/seriyps/rust-erl-ext)
  * [LeebDeveloper/retf](https://github.com/LeebDeveloper/retf)
* HTML
    * [veddan/rust-htmlescape](https://github.com/veddan/rust-htmlescape):  [<img src="https://travis-ci.org/veddan/rust-htmlescape.png?branch=master">](https://travis-ci.org/veddan/rust-htmlescape)
* [JSON](https://github.com/mozilla/rust/blob/master/src/libserialize/json.rs)
* MsgPck
  * [mneumann/rust-msgpack](https://github.com/mneumann/rust-msgpack):  [<img src="https://travis-ci.org/mneumann/rust-msgpack.png?branch=master">](https://travis-ci.org/mneumann/rust-msgpack)
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf):  [<img src="https://travis-ci.org/stepancheg/rust-protobuf.png?branch=master">](https://travis-ci.org/stepancheg/rust-protobuf)
  * [tildeio/buffoon](https://github.com/tildeio/buffoon)
* S-Expressions
  * [darkf/rust_sexpr](https://github.com/darkf/rust_sexpr)
* TOML
  * [mneumann/rust-toml](https://github.com/mneumann/rust-toml):  [<img src="https://travis-ci.org/mneumann/rust-toml.png?branch=master">](https://travis-ci.org/mneumann/rust-toml)
* Tnetstring
  * [erickt/rust-tnetstring](https://github.com/erickt/rust-tnetstring):  [<img src="https://travis-ci.org/erickt/rust-tnetstring.png?branch=master">](https://travis-ci.org/erickt/rust-tnetstring)
* XML
   * [bjz/sax-rs](https://github.com/bjz/sax-rs): bindings to libxml2's SAX parser [<img src="https://travis-ci.org/bjz/sax-rs.png?branch=master">](https://travis-ci.org/bjz/sax-rs)
   * [DanielFath/xml-parser](https://github.com/DanielFath/xml-parser): A hybrid pull, DOM parser written in pure Rust [![Build Status](https://travis-ci.org/DanielFath/xml-parser.png?branch=master)](https://travis-ci.org/DanielFath/xml-parser)
   * [Florob/RustyXML](https://github.com/Florob/RustyXML): an XML parser written in Rust
   * [netvl/xml-rs](https://github.com/netvl/rust-xml): an XML library in Rust [![Build Status](https://travis-ci.org/netvl/xml-rs.svg?branch=master)](https://travis-ci.org/netvl/xml-rs)


## GIS

   * [JamesFysh/rust-proj4](https://github.com/JamesFysh/rust-proj4): Rust bindings for PROJ.4 [![Build Status](https://travis-ci.org/JamesFysh/rust-proj4.svg?branch=master)](https://travis-ci.org/JamesFysh/rust-proj4)


## Graphics and Image Manipulation

* Gnuplot
   * [SiegeLord/RustGnuplot] (https://github.com/SiegeLord/RustGnuplot) [![Build Status](https://travis-ci.org/SiegeLord/RustGnuplot.png)](https://travis-ci.org/SiegeLord/RustGnuplot)
* Images
   * [PistonDevelopers/image](https://github.com/PistonDevelopers/image): Encoding and decoding images in pure Rust [![Build Status](https://travis-ci.org/PistonDevelopers/image.svg?branch=master)](https://travis-ci.org/PistonDevelopers/image)
* LibRaw
   * [damienfir/rust-libraw](https://github.com/damienfir/rust-libraw): load RAW image files
* Screen capture
   * [alexchandel/screenshot-rs](https://github.com/alexchandel/screenshot-rs): Get a bitmap image of the display.

See also Computer Graphics and Game Development.

## GUI Toolkits

* Cocoa
  * [mozilla-servo/rust-cocoa](https://github.com/mozilla-servo/rust-cocoa)
* Conrod
  * [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod)
* Gtk
  * [JeremyLetang/rgtk](https://github.com/JeremyLetang/rgtk)
* ncurses
  * [drhodes/rust-ncurses](https://github.com/drhodes/rust-ncurses)
  * [eevee/amulet](https://github.com/eevee/amulet)
  * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs): [![Build Status](https://travis-ci.org/jeaye/ncurses-rs.png?branch=master)](https://travis-ci.org/jeaye/ncurses-rs.png)
  * [pnkfelix/rust-curses](https://github.com/pnkfelix/rust-curses)
* Termbox
  * [gchp/rustbox](https://github.com/gchp/rustbox)
  * [apribadi/rust-termbox](https://github.com/apribadi/rust-termbox)
* wxWidgets
  * [kenz-gelsoft/wxRust](https://github.com/kenz-gelsoft/wxRust): [![Build Status](https://travis-ci.org/kenz-gelsoft/wxRust.png?branch=master)](https://travis-ci.org/kenz-gelsoft/wxRust)
* Wayland
  * [eyolfson/rust-wayland](https://github.com/eyolfson/rust-wayland)

## IO
 * AIO, SIO, stdio
 * [filesystem](https://github.com/mozilla/rust/blob/master/src/libstd/os.rs)
 * [path manipulation](https://github.com/mozilla/rust/blob/master/src/libstd/path.rs)
 * <> or fileinput.
 * timers
 
## Localizability
 * one aspect of L10n is to map a key to a text, based on the current locale (eg Java's [ResourceBundle](http://docs.oracle.com/javase/7/docs/api/java/util/ResourceBundle.html) or [GNU gettext](http://www.gnu.org/software/gettext/))
 * another aspect is to format a string based on the current locale (eg Java's [MessageFormat](http://docs.oracle.com/javase/7/docs/api/java/text/MessageFormat.html))
 * See [issue #4630](https://github.com/mozilla/rust/issues/4630)
 
## Mathematics
* [bluss/rust-ndarray](https://github.com/bluss/rust-ndarray) (N-dimensional array with linear algebra)
* [bjz/cgmath-rs](https://github.com/bjz/cgmath-rs) (Linear algebra and math library for graphics)
* [cmr/linalg](https://github.com/cmr/linalg) (Toy/tinkering linear algebra library)
* [ptal/Rust.Interval](https://github.com/ptal/Rust.Interval) (Interval arithmetic library)

### Unit Conversions
* [uwap/unitr](https://github.com/uwap/unitr) (A unit conversion library)

## Misc
* low-level OS services
  * [zargony/rust-fuse](https://github.com/zargony/rust-fuse): Library for filesystems in userspace (FUSE)  [<img src="https://travis-ci.org/zargony/rust-fuse.png?branch=master">](https://travis-ci.org/zargony/rust-fuse)
* Simple search on a filesystem (eg Ruby's [glob](http://ruby-doc.org/core-2.0/Dir.html#method-c-glob))
* unit testing
* FFI, ctypes
* dlopen, os processes
* standard predicates
 * text, numeric, sorted
* error-trapping wrappers, in-place task?
 * Consistent error handling
* quotas, accounting
* reflection
* command-line handling
  *  [tailhook/rust-argparse](https://github.com/tailhook/rust-argparse) [<img src="https://travis-ci.org/tailhook/rust-argparse.png?branch=master">](https://travis-ci.org/tailhook/rust-argparse)
  *  [docopt/docopt.rs](https://github.com/docopt/docopt.rs) [![Build status](https://api.travis-ci.org/docopt/docopt.rs.svg)](https://travis-ci.org/docopt/docopt.rs)

## Networking

* GUID
* [UUID](https://github.com/rust-lang/uuid)
* NanoMsg
  * [glycerine/rust-nanomsg](https://github.com/glycerine/rust-nanomsg)
* Beanstalkd
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd):  [<img src="https://travis-ci.org/schickling/rust-beanstalkd.png?branch=master">](https://travis-ci.org/schickling/rust-beanstalkd)
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq):  [<img src="https://travis-ci.org/erickt/rust-zmq.png?branch=master">](https://travis-ci.org/erickt/rust-zmq)
* STOMP
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs):  [<img src="https://travis-ci.org/zslayton/stomp-rs.png?branch=master">](https://travis-ci.org/zslayton/stomp-rs)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs):  [<img src="https://travis-ci.org/alexcrichton/ssh2-rs.png?branch=master">](https://travis-ci.org/alexcrichton/ssh2-rs)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3):  [<img src="https://api.travis-ci.org/mattnenterprise/rust-pop3.png?branch=master">](https://travis-ci.org/mattnenterprise/rust-pop3)
* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp):  [<img src="https://api.travis-ci.org/mattnenterprise/rust-ftp.png?branch=master">](https://travis-ci.org/mattnenterprise/rust-ftp)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp):  [<img src="https://api.travis-ci.org/mattnenterprise/rust-nntp.png?branch=master">](https://travis-ci.org/mattnenterprise/rust-nntp)

## Operating system specific

* Windows
   * [retep998/winapi-rs](https://github.com/retep998/winapi-rs): Low-level types and consts for Windows.
   * [retep998/kernel32-sys](https://github.com/retep998/kernel32-sys): Low-level bindings to kernel32.
   * [retep998/user32-sys](https://github.com/retep998/user32-sys): Low-level bindings to user32.
   * [retep998/gdi32-sys](https://github.com/retep998/gdi32-sys): Low-level bindings to gdi32. (Graphics)
   * [retep998/shell32-sys](https://github.com/retep998/shell32-sys): Low-level bindings to shell32. (Explorer)
   * [klutzy/rust-windows](https://github.com/klutzy/rust-windows): Win32/Win64 wrapper. High level, but not Cargo.
* Mac
   * [servo/rust-core-foundation](https://github.com/servo/rust-core-foundation): Low-level Core Foundation bindings.
   * [servo/rust-core-graphics](https://github.com/servo/rust-core-graphics): Low-level Core Graphics bindings.
   * [servo/rust-cocoa](https://github.com/servo/rust-cocoa): Bindings to Objective-C and Cocoa.
* Linux
   * [Stebalien/udev-rs](https://github.com/Stebalien/udev-rs): Bindings to udev.

## OS

* [uutils/coreutils](https://github.com/uutils/coreutils): GNU coreutils replacement

## Parser Generator

* [erickt/ragel](https://github.com/erickt/ragel)
* [jesse99/rparse](https://github.com/jesse99/rparse)
* [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg)
* [Valloric/nailed](https://github.com/Valloric/nailed): A Rust PEG parser generator
* [ptal/Rust.peg](https://github.com/ptal/Rust.peg): Parser and AST generator, on-going work.

## Random Numbers
* [random](https://github.com/mozilla/rust/blob/master/src/libcstd/rand.rs)

## Regular Expressions
See the [regex crate](http://doc.rust-lang.org/regex/).

* [glennsl/rust-re](https://github.com/glennsl/rust-re)
* [sanxiyn/rree](https://github.com/sanxiyn/rree)
* PCRE
  * [cadencemarseille/rust-pcre](https://github.com/cadencemarseille/rust-pcre): [![cadencemarseille/rust-pcre Build Status](https://travis-ci.org/cadencemarseille/rust-pcre.png?branch=master)](https://travis-ci.org/cadencemarseille/rust-pcre)
  * [erickt/rustpcre](https://github.com/erickt/rustpcre)
  * [uasi/rust-pcre](https://github.com/uasi/rust-pcre):  [<img src="https://travis-ci.org/uasi/rust-pcre.png?branch=master">](https://travis-ci.org/uasi/rust-pcre)
* re2
  * [nickdesaulniers/rust-re2](https://github.com/nickdesaulniers/rust-re2)

## String manipulation
* Slicing w/o copy, stringref
* Ropes
* Tokenizer
* Unicode
  * [Unicode](https://github.com/mozilla/rust/blob/master/src/libextra/unicode.rs)
  * Convertions between text encodings. Ideally, with a customizable way of handling conversion errors.
  * Unicode normalization (NFD, NFC, NFKD, NFKC)
  * Collator (locale sensitive string comparison), with a configurable degree of strictness

## Template engine

* Mustache
  * [erickt/rust-mustache](https://github.com/erickt/rust-mustache): [<img src="https://travis-ci.org/erickt/rust-mustache.png?branch=master">](https://travis-ci.org/erickt/rust-mustache)


## Testing

* QuickCheck
  * [mcandre/rustcheck](https://github.com/mcandre/rustcheck)
  * [BurntSushi/quickcheck](https://github.com/BurntSushi/quickcheck): [<img src="https://api.travis-ci.org/BurntSushi/quickcheck.png">](https://travis-ci.org/BurntSushi/quickcheck)

## Web Programming

See also http://www.arewewebyet.org/

  * common client + server functionality
    * [chris-morgan/rust-http](https://github.com/chris-morgan/rust-http): Superceeded by Teepee  [<img src="https://travis-ci.org/chris-morgan/rust-http.png?branch=master">](https://travis-ci.org/chris-morgan/rust-http)
    * [teepee/teepee](https://github.com/teepee/teepee) [<img src="https://travis-ci.org/teepee/teepee.png?branch=master">](https://travis-ci.org/teepee/teepee)
    * [SimonSapin/rust-url](https://github.com/SimonSapin/rust-url)
    * [url.rs](https://github.com/mozilla/rust/blob/master/src/liburl/lib.rs)
  * client
    * [andelf/rust-httpc](https://github.com/andelf/rust-httpc)
    * [carllerche/curl-rust](https://github.com/carllerche/curl-rust)
  * server framework
    * [conduit-rust/conduit](https://github.com/conduit-rust/conduit)
    * [Earlz/rustymvc](https://github.com/Earlz/rustymvc)
    * [erickt/rust-mongrel2](https://github.com/erickt/rust-mongrel2): bindings for the [Mongrel2](http://mongrel2.org) webserver
    * [iron/iron](https://github.com/iron/iron): Middleware based, concurrency oriented pure Rust framework.
    * [jroweboy/oxidize](https://github.com/jroweboy/oxidize)
    * [nickel-org/nickel.rs](https://github.com/nickel-org/nickel.rs): inspired by Express.js, which is inspired by Sinatra.
    * [Ogeon/rustful](https://github.com/Ogeon/rustful):  [<img src="https://travis-ci.org/Ogeon/rustful.png?branch=master">](https://travis-ci.org/Ogeon/rustful)
    * [skade/widmann](https://github.com/skade/widmann): inspired by Sinatra. [<img src="https://travis-ci.org/skade/widmann.png?branch=master">](https://travis-ci.org/skade/widmann)
    * [WebeWizard/libhttpd](https://github.com/WebeWizard/libhttpd)
    * [nathansizemore/rustic-io](https://github.com/nathansizemore/rustic-io): Websocket abstraction inspired by socket.io [<img src="https://travis-ci.org/nathansizemore/rustic-io.png?branch=master">](https://travis-ci.org/nathansizemore/rustic-io)
