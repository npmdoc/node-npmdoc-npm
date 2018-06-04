# npmdoc-npm

#### basic api documentation for  [npm (6.1.0)](https://docs.npmjs.com/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm)

#### a package manager for JavaScript

[![NPM](https://nodei.co/npm/npm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm)

- [https://npmdoc.github.io/node-npmdoc-npm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "url": "http://blog.izs.me"
    },
    "bin": {
        "npm": "./bin/npm-cli.js",
        "npx": "./bin/npx-cli.js"
    },
    "bugs": {
        "url": "https://github.com/npm/npm/issues"
    },
    "bundleDependencies": [
        "abbrev",
        "ansi-regex",
        "ansicolors",
        "ansistyles",
        "aproba",
        "archy",
        "byte-size",
        "cacache",
        "call-limit",
        "bluebird",
        "bin-links",
        "chownr",
        "cli-table2",
        "cmd-shim",
        "columnify",
        "config-chain",
        "debuglog",
        "detect-indent",
        "detect-newline",
        "dezalgo",
        "editor",
        "figgy-pudding",
        "find-npm-prefix",
        "fs-vacuum",
        "fs-write-stream-atomic",
        "gentle-fs",
        "glob",
        "graceful-fs",
        "has-unicode",
        "hosted-git-info",
        "iferr",
        "imurmurhash",
        "inflight",
        "inherits",
        "ini",
        "init-package-json",
        "is-cidr",
        "json-parse-better-errors",
        "JSONStream",
        "lazy-property",
        "libcipm",
        "libnpmhook",
        "libnpx",
        "lockfile",
        "lodash._baseindexof",
        "lodash._baseuniq",
        "lodash._bindcallback",
        "lodash._cacheindexof",
        "lodash._createcache",
        "lodash._getnative",
        "lodash.clonedeep",
        "lodash.restparam",
        "lodash.union",
        "lodash.uniq",
        "lodash.without",
        "lru-cache",
        "meant",
        "mkdirp",
        "mississippi",
        "move-concurrently",
        "nopt",
        "normalize-package-data",
        "npm-audit-report",
        "npm-cache-filename",
        "npm-lifecycle",
        "npm-install-checks",
        "npm-package-arg",
        "npm-packlist",
        "npm-pick-manifest",
        "npm-profile",
        "npm-registry-client",
        "npm-registry-fetch",
        "npm-user-validate",
        "npmlog",
        "once",
        "opener",
        "osenv",
        "pacote",
        "path-is-inside",
        "promise-inflight",
        "query-string",
        "qrcode-terminal",
        "qw",
        "read",
        "read-cmd-shim",
        "read-installed",
        "read-package-json",
        "read-package-tree",
        "readable-stream",
        "readdir-scoped-modules",
        "request",
        "retry",
        "rimraf",
        "semver",
        "sha",
        "slide",
        "sorted-object",
        "sorted-union-stream",
        "ssri",
        "strip-ansi",
        "tar",
        "text-table",
        "uid-number",
        "umask",
        "unique-filename",
        "unpipe",
        "update-notifier",
        "uuid",
        "validate-npm-package-license",
        "validate-npm-package-name",
        "which",
        "wrappy",
        "write-file-atomic",
        "safe-buffer",
        "worker-farm",
        "tiny-relative-date",
        "cli-columns",
        "node-gyp",
        "lock-verify"
    ],
    "config": {
        "publishtest": false
    },
    "contributors": [
        {
            "name": "Isaac Z. Schlueter"
        },
        {
            "name": "Steve Steiner"
        },
        {
            "name": "Mikeal Rogers"
        },
        {
            "name": "Aaron Blohowiak"
        },
        {
            "name": "Martyn Smith"
        },
        {
            "name": "Charlie Robbins"
        },
        {
            "name": "Francisco Treacy"
        },
        {
            "name": "Cliffano Subagio"
        },
        {
            "name": "Christian Eager"
        },
        {
            "name": "Dav Glass"
        },
        {
            "name": "Alex K. Wolfe"
        },
        {
            "name": "James Sanders"
        },
        {
            "name": "Reid Burke"
        },
        {
            "name": "Arlo Breault"
        },
        {
            "name": "Timo Derstappen"
        },
        {
            "name": "Bart Teeuwisse"
        },
        {
            "name": "Ben Noordhuis"
        },
        {
            "name": "Tor Valamo"
        },
        {
            "name": "Whyme.Lyu"
        },
        {
            "name": "Olivier Melcher"
        },
        {
            "name": "Tomaž Muraus"
        },
        {
            "name": "Evan Meagher"
        },
        {
            "name": "Orlando Vazquez"
        },
        {
            "name": "Kai Chen"
        },
        {
            "name": "George Miroshnykov"
        },
        {
            "name": "Geoff Flarity"
        },
        {
            "name": "Max Goodman"
        },
        {
            "name": "Pete Kruckenberg"
        },
        {
            "name": "Laurie Harper"
        },
        {
            "name": "Chris Wong"
        },
        {
            "name": "Scott Bronson"
        },
        {
            "name": "Federico Romero"
        },
        {
            "name": "Visnu Pitiyanuvath"
        },
        {
            "name": "Irakli Gozalishvili"
        },
        {
            "name": "Mark Cahill"
        },
        {
            "name": "Tony"
        },
        {
            "name": "Iain Sproat"
        },
        {
            "name": "Trent Mick"
        },
        {
            "name": "Felix Geisendörfer"
        },
        {
            "name": "Jameson Little"
        },
        {
            "name": "Conny Brunnkvist"
        },
        {
            "name": "Will Elwood"
        },
        {
            "name": "Dean Landolt"
        },
        {
            "name": "Oleg Efimov"
        },
        {
            "name": "Martin Cooper"
        },
        {
            "name": "Jann Horn"
        },
        {
            "name": "Andrew Bradley"
        },
        {
            "name": "Maciej Małecki"
        },
        {
            "name": "Stephen Sugden"
        },
        {
            "name": "Michael Budde"
        },
        {
            "name": "Jason Smith"
        },
        {
            "name": "Gautham Pai"
        },
        {
            "name": "David Trejo"
        },
        {
            "name": "Paul Vorbach"
        },
        {
            "name": "George Ornbo"
        },
        {
            "name": "Tim Oxley"
        },
        {
            "name": "Tyler Green"
        },
        {
            "name": "Dave Pacheco"
        },
        {
            "name": "Danila Gerasimov"
        },
        {
            "name": "Rod Vagg"
        },
        {
            "name": "Christian Howe"
        },
        {
            "name": "Andrew Lunny"
        },
        {
            "name": "Henrik Hodne"
        },
        {
            "name": "Adam Blackburn"
        },
        {
            "name": "Kris Windham"
        },
        {
            "name": "Jens Grunert"
        },
        {
            "name": "Joost-Wim Boekesteijn"
        },
        {
            "name": "Dalmais Maxence"
        },
        {
            "name": "Marcus Ekwall"
        },
        {
            "name": "Aaron Stacy"
        },
        {
            "name": "Phillip Howell"
        },
        {
            "name": "Domenic Denicola"
        },
        {
            "name": "James Halliday"
        },
        {
            "name": "Jeremy Cantrell"
        },
        {
            "name": "Ribettes"
        },
        {
            "name": "Don Park"
        },
        {
            "name": "Einar Otto Stangvik"
        },
        {
            "name": "Kei Son"
        },
        {
            "name": "Nicolas Morel"
        },
        {
            "name": "Mark Dube"
        },
        {
            "name": "Nathan Rajlich"
        },
        {
            "name": "Maxim Bogushevich"
        },
        {
            "name": "Meaglin"
        },
        {
            "name": "Ben Evans"
        },
        {
            "name": "Nathan Zadoks"
        },
        {
            "name": "Brian White"
        },
        {
            "name": "Jed Schmidt"
        },
        {
            "name": "Ian Livingstone"
        },
        {
            "name": "Patrick Pfeiffer"
        },
        {
            "name": "Paul Miller"
        },
        {
            "name": "Ryan Emery"
        },
        {
            "name": "Carl Lange"
        },
        {
            "name": "Jan Lehnardt"
        },
        {
            "name": "Stuart P. Bentley"
        },
        {
            "name": "Johan Sköld"
        },
        {
            "name": "Stuart Knightley"
        },
        {
            "name": "Niggler"
        },
        {
            "name": "Paolo Fragomeni"
        },
        {
            "name": "Jaakko Manninen"
        },
        {
            "name": "Luke Arduini"
        },
        {
            "name": "Larz Conwell",
            "url": "none"
        },
        {
            "name": "Marcel Klehr"
        },
        {
            "name": "Robert Kowalski"
        },
        {
            "name": "Forbes Lindesay"
        },
        {
            "name": "Vaz Allen"
        },
        {
            "name": "Jake Verbaten"
        },
        {
            "name": "Schabse Laks"
        },
        {
            "name": "Florian Margaine"
        },
        {
            "name": "Johan Nordberg"
        },
        {
            "name": "Ian Babrou"
        },
        {
            "name": "Di Wu"
        },
        {
            "name": "Mathias Bynens"
        },
        {
            "name": "Matt McClure"
        },
        {
            "name": "Matt Lunn"
        },
        {
            "name": "Alexey Kreschuk"
        },
        {
            "name": "elisee"
        },
        {
            "name": "Robert Gieseke"
        },
        {
            "name": "François Frisch"
        },
        {
            "name": "Trevor Burnham"
        },
        {
            "name": "Alan Shaw"
        },
        {
            "name": "TJ Holowaychuk"
        },
        {
            "name": "Nicholas Kinsey"
        },
        {
            "name": "Paulo Cesar"
        },
        {
            "name": "Elan Shanker"
        },
        {
            "name": "Jon Spencer"
        },
        {
            "name": "Jason Diamond"
        },
        {
            "name": "Maximilian Antoni"
        },
        {
            "name": "Thom Blake"
        },
        {
            "name": "Jess Martin"
        },
        {
            "name": "Spain Train"
        },
        {
            "name": "Alex Rodionov"
        },
        {
            "name": "Matt Colyer"
        },
        {
            "name": "Evan You"
        },
        {
            "name": "bitspill"
        },
        {
            "name": "Gabriel Falkenberg"
        },
        {
            "name": "Alexej Yaroshevich"
        },
        {
            "name": "Quim Calpe"
        },
        {
            "name": "Steve Mason"
        },
        {
            "name": "Wil Moore III"
        },
        {
            "name": "Sergey Belov"
        },
        {
            "name": "Tom Huang"
        },
        {
            "name": "CamilleM"
        },
        {
            "name": "Sébastien Santoro"
        },
        {
            "name": "Evan Lucas"
        },
        {
            "name": "Quinn Slack"
        },
        {
            "name": "Alex Kocharin"
        },
        {
            "name": "Daniel Santiago"
        },
        {
            "name": "Denis Gladkikh"
        },
        {
            "name": "Andrew Horton"
        },
        {
            "name": "Zeke Sikelianos"
        },
        {
            "name": "Dylan Greene"
        },
        {
            "name": "Franck Cuny"
        },
        {
            "name": "Yeonghoon Park"
        },
        {
            "name": "Rafael de Oleza"
        },
        {
            "name": "Mikola Lysenko"
        },
        {
            "name": "Yazhong Liu"
        },
        {
            "name": "Neil Gentleman"
        },
        {
            "name": "Kris Kowal"
        },
        {
            "name": "Alex Gorbatchev"
        },
        {
            "name": "Shawn Wildermuth"
        },
        {
            "name": "Wesley de Souza"
        },
        {
            "name": "yoyoyogi"
        },
        {
            "name": "J. Tangelder"
        },
        {
            "name": "Jean Lauliac"
        },
        {
            "name": "Andrey Kislyuk"
        },
        {
            "name": "Thorsten Lorenz"
        },
        {
            "name": "Julian Gruber"
        },
        {
            "name": "Benjamin Coe"
        },
        {
            "name": "Alex Ford"
        },
        {
            "name": "Matt Hickford"
        },
        {
            "name": "Sean McGivern"
        },
        {
            "name": "C J Silverio"
        },
        {
            "name": "Robin Tweedie"
        },
        {
            "name": "Miroslav Bajtoš"
        },
        {
            "name": "David Glasser"
        },
        {
            "name": "Gianluca Casati"
        },
        {
            "name": "Forrest L Norvell"
        },
        {
            "name": "Karsten Tinnefeld"
        },
        {
            "name": "Bryan Burgers"
        },
        {
            "name": "David Beitey"
        },
        {
            "name": "Evan You"
        },
        {
            "name": "Zach Pomerantz"
        },
        {
            "name": "Chris Williams"
        },
        {
            "name": "sudodoki"
        },
        {
            "name": "Mick Thompson"
        },
        {
            "name": "Felix Rabe"
        },
        {
            "name": "Michael Hayes"
        },
        {
            "name": "Chris Dickinson"
        },
        {
            "name": "Bradley Meck"
        },
        {
            "name": "GeJ"
        },
        {
            "name": "Andrew Terris"
        },
        {
            "name": "Michael Nisi"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "Adam Meadows"
        },
        {
            "name": "Chulki Lee"
        },
        {
            "name": "不四"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "Kenan Yildirim"
        },
        {
            "name": "Laurie Voss"
        },
        {
            "name": "Rebecca Turner"
        },
        {
            "name": "Hunter Loftis"
        },
        {
            "name": "Peter Richardson"
        },
        {
            "name": "Jussi Kalliokoski"
        },
        {
            "name": "Filip Weiss"
        },
        {
            "name": "Timo Weiß"
        },
        {
            "name": "Christopher Hiller"
        },
        {
            "name": "Jérémy Lal"
        },
        {
            "name": "Anders Janmyr"
        },
        {
            "name": "Chris Meyers"
        },
        {
            "name": "Ludwig Magnusson"
        },
        {
            "name": "Wout Mertens"
        },
        {
            "name": "Nick Santos"
        },
        {
            "name": "Terin Stock"
        },
        {
            "name": "Faiq Raza"
        },
        {
            "name": "Thomas Torp"
        },
        {
            "name": "Sam Mikes"
        },
        {
            "name": "Mat Tyndall"
        },
        {
            "name": "Tauren Mills"
        },
        {
            "name": "Ron Martinez"
        },
        {
            "name": "Kazuhito Hokamura"
        },
        {
            "name": "Tristan Davies"
        },
        {
            "name": "David Volm"
        },
        {
            "name": "Lin Clark"
        },
        {
            "name": "Ben Page"
        },
        {
            "name": "Jeff Jo"
        },
        {
            "name": "martinvd"
        },
        {
            "name": "Mark J. Titorenko"
        },
        {
            "name": "Oddur Sigurdsson"
        },
        {
            "name": "Eric Mill"
        },
        {
            "name": "Gabriel Barros"
        },
        {
            "name": "KevinSheedy"
        },
        {
            "name": "Aleksey Smolenchuk"
        },
        {
            "name": "Ed Morley"
        },
        {
            "name": "Blaine Bublitz"
        },
        {
            "name": "Andrey Fedorov"
        },
        {
            "name": "Daijiro Wachi"
        },
        {
            "name": "Luc Thevenard"
        },
        {
            "name": "Aria Stewart"
        },
        {
            "name": "Charlie Rudolph"
        },
        {
            "name": "Vladimir Rutsky"
        },
        {
            "name": "Isaac Murchie"
        },
        {
            "name": "Marcin Wosinek"
        },
        {
            "name": "David Marr"
        },
        {
            "name": "Bryan English"
        },
        {
            "name": "Anthony Zotti"
        },
        {
            "name": "Karl Horky"
        },
        {
            "name": "Jordan Harband"
        },
        {
            "name": "Guðlaugur Stefán Egilsson"
        },
        {
            "name": "Helge Skogly Holm"
        },
        {
            "name": "Peter A. Shevtsov"
        },
        {
            "name": "Alain Kalker"
        },
        {
            "name": "Bryant Williams"
        },
        {
            "name": "Jonas Weber"
        },
        {
            "name": "Tim Whidden"
        },
        {
            "name": "Andreas"
        },
        {
            "name": "Karolis Narkevicius"
        },
        {
            "name": "Adrian Lynch"
        },
        {
            "name": "Richard Littauer"
        },
        {
            "name": "Oli Evans"
        },
        {
            "name": "Matt Brennan"
        },
        {
            "name": "Jeff Barczewski"
        },
        {
            "name": "Danny Fritz"
        },
        {
            "name": "Takaya Kobayashi"
        },
        {
            "name": "Ra'Shaun Stovall"
        },
        {
            "name": "Julien Meddah"
        },
        {
            "name": "Michiel Sikma"
        },
        {
            "name": "Jakob Krigovsky"
        },
        {
            "name": "Charmander"
        },
        {
            "name": "Erik Wienhold"
        },
        {
            "name": "James Butler"
        },
        {
            "name": "Kevin Kragenbrink"
        },
        {
            "name": "Arnaud Rinquin"
        },
        {
            "name": "Mike MacCana"
        },
        {
            "name": "Antti Mattila"
        },
        {
            "name": "laiso"
        },
        {
            "name": "Matt Zorn"
        },
        {
            "name": "Kyle Mitchell"
        },
        {
            "name": "Jeremiah Senkpiel"
        },
        {
            "name": "Michael Klein"
        },
        {
            "name": "Simen Bekkhus"
        },
        {
            "name": "Victor"
        },
        {
            "name": "thefourtheye"
        },
        {
            "name": "Clay Carpenter"
        },
        {
            "name": "bangbang93"
        },
        {
            "name": "Nick Malaguti"
        },
        {
            "name": "Cedric Nelson"
        },
        {
            "name": "Kat Marchán"
        },
        {
            "name": "Andrew"
        },
        {
            "name": "Eduardo Pinho"
        },
        {
            "name": "Rachel Hutchison"
        },
        {
            "name": "Ryan Temple"
        },
        {
            "name": "Eugene Sharygin"
        },
        {
            "name": "James Talmage"
        },
        {
            "name": "jane arc"
        },
        {
            "name": "Joseph Dykstra"
        },
        {
            "name": "Andrew Crites"
        },
        {
            "name": "Joshua Egan"
        },
        {
            "name": "Carlos Alberto"
        },
        {
            "name": "Thomas Cort"
        },
        {
            "name": "Thaddee Tyl"
        },
        {
            "name": "Steve Klabnik"
        },
        {
            "name": "Andrew Murray"
        },
        {
            "name": "Stephan Bönnemann"
        },
        {
            "name": "Kyle M. Tarplee"
        },
        {
            "name": "Derek Peterson"
        },
        {
            "name": "Greg Whiteley"
        },
        {
            "name": "murgatroid99"
        },
        {
            "name": "Marcin Cieslak"
        },
        {
            "name": "João Reis"
        },
        {
            "name": "Matthew Hasbach"
        },
        {
            "name": "Jon Hall"
        },
        {
            "name": "Anna Henningsen"
        },
        {
            "name": "James Treworgy"
        },
        {
            "name": "James Hartig"
        },
        {
            "name": "Stephanie Snopek"
        },
        {
            "name": "Kent C. Dodds"
        },
        {
            "name": "Aaron Krause"
        },
        {
            "name": "Daniel K O'Leary"
        },
        {
            "name": "fscherwi"
        },
        {
            "name": "Thomas Reggi"
        },
        {
            "name": "Thomas Michael McTiernan"
        },
        {
            "name": "Jason Kurian"
        },
        {
            "name": "Sebastiaan Deckers"
        },
        {
            "name": "lady3bean"
        },
        {
            "name": "Tomi Carr"
        },
        {
            "name": "Juan Caicedo"
        },
        {
            "name": "Ashley Williams"
        },
        {
            "name": "Andrew Marcinkevičius"
        },
        {
            "name": "Jorrit Schippers"
        },
        {
            "name": "Alex Lukin"
        },
        {
            "name": "Aria Stewart"
        },
        {
            "name": "Tiago Rodrigues"
        },
        {
            "name": "Tim"
        },
        {
            "name": "Nick Williams"
        },
        {
            "name": "Louis Larry"
        },
        {
            "name": "Ben Gotow"
        },
        {
            "name": "Jakub Gieryluk"
        },
        {
            "name": "Kevin Lorenz"
        },
        {
            "name": "Martin von Gagern"
        },
        {
            "name": "Eymen Gunay"
        },
        {
            "name": "Martin Ek"
        },
        {
            "name": "Rafał Pocztarski"
        },
        {
            "name": "Mark Reeder"
        },
        {
            "name": "Chris Rebert"
        },
        {
            "name": "Scott Addie"
        },
        {
            "name": "Jeff McMahan"
        },
        {
            "name": "Tim Krins"
        },
        {
            "name": "Hal Henke"
        },
        {
            "name": "Julian Simioni"
        },
        {
            "name": "Jimb Esser"
        },
        {
            "name": "Alexis Campailla"
        },
        {
            "name": "Chris Chua"
        },
        {
            "name": "Beau Gunderson"
        },
        {
            "name": "Dave Galbraith"
        },
        {
            "name": "s100"
        },
        {
            "name": "Sergey Simonchik"
        },
        {
            "name": "Vanja Radovanović"
        },
        {
            "name": "Jonathan Persson"
        },
        {
            "name": "Vedat Mahir YILMAZ"
        },
        {
            "name": "Samuel Reed"
        },
        {
            "name": "Rafał Legiędź"
        },
        {
            "name": "Jan Schär"
        },
        {
            "name": "Xcat Liu"
        },
        {
            "name": "harryh"
        },
        {
            "name": "Prayag Verma"
        },
        {
            "name": "Neil Kistner"
        },
        {
            "name": "Zoujie Wzj"
        },
        {
            "name": "Ryan Hendrickson"
        },
        {
            "name": "Arturo Coronel"
        },
        {
            "name": "Hutson Betts"
        },
        {
            "name": "Lewis Cowper"
        },
        {
            "name": "Adam Byrne"
        },
        {
            "name": "Ifeanyi Oraelosi"
        },
        {
            "name": "Robert Ludwig"
        },
        {
            "name": "Chris Warren"
        },
        {
            "name": "Scott Plumlee"
        },
        {
            "name": "Daniel Pedersen"
        },
        {
            "name": "rhgb"
        },
        {
            "name": "doug.wade"
        },
        {
            "name": "Zac"
        },
        {
            "name": "GriffinSchneider"
        },
        {
            "name": "Andres Kalle"
        },
        {
            "name": "thefourtheye"
        },
        {
            "name": "Yael"
        },
        {
            "name": "Yann Odeyer"
        },
        {
            "name": "James Monger"
        },
        {
            "name": "Thomas Hallock"
        },
        {
            "name": "Paul Irish"
        },
        {
            "name": "Paul O'Leary McCann"
        },
        {
            "name": "Francis Gulotta"
        },
        {
            "name": "Felix Rieseberg"
        },
        {
            "name": "Glen Mailer"
        },
        {
            "name": "Federico Brigante"
        },
        {
            "name": "Steve Mao"
        },
        {
            "name": "Anna Henningsen"
        },
        {
            "name": "Rachel Evans"
        },
        {
            "name": "Sam Minnee"
        },
        {
            "name": "Zirak"
        },
        {
            "name": "Daniel Lupu"
        },
        {
            "name": "Gianluca Casati"
        },
        {
            "name": "André Herculano"
        },
        {
            "name": "Wyatt Preul"
        },
        {
            "name": "Myles Borins"
        },
        {
            "name": "Elliot Lee"
        },
        {
            "name": "Dmitry Kirilyuk"
        },
        {
            "name": "Aaron Tribou"
        },
        {
            "name": "Tapani Moilanen"
        },
        {
            "name": "Han Seoul-Oh"
        },
        {
            "name": "Aleksey Shvayka"
        },
        {
            "name": "Emma Ramirez"
        },
        {
            "name": "Julian Duque"
        },
        {
            "name": "Simon MacDonald"
        },
        {
            "name": "Adam Stankiewicz"
        },
        {
            "name": "Gregers Gram Rygg"
        },
        {
            "name": "Peter Dave Hello"
        },
        {
            "name": "Jordan Klassen"
        },
        {
            "name": "Jason Palmer"
        },
        {
            "name": "Michael Hart"
        },
        {
            "name": "Sasha Koss"
        },
        {
            "name": "David Emmerson"
        },
        {
            "name": "Christophe Hurpeau"
        },
        {
            "name": "Daniel Paz-Soldan"
        },
        {
            "name": "Sakthipriyan Vairamani"
        },
        {
            "name": "Zach Renner"
        },
        {
            "name": "Christopher Hiller"
        },
        {
            "name": "Joshua Bennett"
        },
        {
            "name": "Andrew Meyer"
        },
        {
            "name": "Michael Jasper"
        },
        {
            "name": "Max"
        },
        {
            "name": "Szymon Nowak"
        },
        {
            "name": "Jason Karns"
        },
        {
            "name": "Lucas Holmquist"
        },
        {
            "name": "Ionică Bizău"
        },
        {
            "name": "Alex Chesters"
        },
        {
            "name": "Robert Gay"
        },
        {
            "name": "Steven"
        },
        {
            "name": "Tim Caswell"
        },
        {
            "name": "Anna Henningsen"
        },
        {
            "name": "Kim Røen"
        },
        {
            "name": "Douglas Wilson"
        },
        {
            "name": "Mike Engel"
        },
        {
            "name": "baderbuddy"
        },
        {
            "name": "Alex Jordan"
        },
        {
            "name": "Ville Lahdenvuo"
        },
        {
            "name": "Natalie Wolfe"
        },
        {
            "name": "Andrew Schmadel"
        },
        {
            "name": "Jonah Moses"
        },
        {
            "name": "Daijirō Wachi"
        },
        {
            "name": "Dmitry Litvinchenko"
        },
        {
            "name": "chocolateboy"
        },
        {
            "name": "Henry Zhu"
        },
        {
            "name": "Nate Goldman"
        },
        {
            "name": "Ted Yavuzkurt"
        },
        {
            "name": "Arseniy Maximov"
        },
        {
            "name": "Evgeny Kulikov"
        },
        {
            "name": "Сковорода Никита Андреевич"
        },
        {
            "name": "Carol",
            "url": "Nichols || Goulding"
        },
        {
            "name": "Jarid Margolin"
        },
        {
            "name": "David Cook"
        },
        {
            "name": "Brian Dukes"
        },
        {
            "name": "Jed Fox"
        },
        {
            "name": "Pavlo Liulia"
        },
        {
            "name": "Ján Dzurek"
        },
        {
            "name": "Lucas Theisen"
        },
        {
            "name": "Mike Sherov"
        },
        {
            "name": "薛定谔的猫"
        },
        {
            "name": "Paweł Lula"
        },
        {
            "name": "Jakob Krigovsky"
        },
        {
            "name": "George Rawlinson"
        },
        {
            "name": "Jack Nagel"
        },
        {
            "name": "Andreas Kohn"
        },
        {
            "name": "Jason Wohlgemuth"
        },
        {
            "name": "Ryan Graham"
        },
        {
            "name": "Hirse"
        },
        {
            "name": "Colin Rotherham"
        },
        {
            "name": "Aki"
        },
        {
            "name": "Emily Marigold Klassen"
        },
        {
            "name": "Ramana Venkata"
        },
        {
            "name": "kierendixon"
        },
        {
            "name": "Rácz Tibor Zoltán"
        },
        {
            "name": "Guangcong Luo"
        },
        {
            "name": "Steven"
        },
        {
            "name": "Jan Pilzer"
        },
        {
            "name": "Leonard Martin"
        },
        {
            "name": "Teddy Katz"
        },
        {
            "name": "Simon Legg"
        },
        {
            "name": "Kin Lum"
        },
        {
            "name": "David Rousselie"
        },
        {
            "name": "Jože Mlakar"
        },
        {
            "name": "happylynx"
        },
        {
            "name": "Dominic Watson"
        },
        {
            "name": "Enrico Weigelt, metux IT consult"
        },
        {
            "name": "Brian Beck"
        },
        {
            "name": "Ramana Venkata"
        },
        {
            "name": "Misha Kaletsky"
        },
        {
            "name": "Andrew Schmadel"
        },
        {
            "name": "AJ Jordan"
        },
        {
            "name": "Mark Banner"
        },
        {
            "name": "Richard Simko"
        },
        {
            "name": "Sanketh Katta"
        },
        {
            "name": "Tim Needham"
        },
        {
            "name": "Leonardo Rojas"
        },
        {
            "name": "Mark Peter Fejes"
        },
        {
            "name": "Ryan Florence"
        },
        {
            "name": "MichaelQQ"
        },
        {
            "name": "Anders D. Johnson"
        },
        {
            "name": "Benjamin Fernandes"
        },
        {
            "name": "Simon Kurtz"
        },
        {
            "name": "David Goss"
        },
        {
            "name": "Luis Gustavo Pereira"
        },
        {
            "name": "Amos Wenger"
        },
        {
            "name": "Samuel Marks"
        },
        {
            "name": "Victor Travieso"
        },
        {
            "name": "Joshua Chaitin-Pollak"
        },
        {
            "name": "Brendan Warkentin"
        },
        {
            "name": "Scott Santucci"
        },
        {
            "name": "Xavier Cambar"
        },
        {
            "name": "Vikram"
        },
        {
            "name": "Igor Nadj"
        },
        {
            "name": "Tong Li"
        },
        {
            "name": "tripu"
        },
        {
            "name": "Carsten Brandt"
        },
        {
            "name": "Marcin Szczepanski"
        },
        {
            "name": "Josh Clow"
        },
        {
            "name": "Jakub Holy"
        },
        {
            "name": "Alexandra Ulsh"
        },
        {
            "name": "Tom MacWright"
        },
        {
            "name": "Felicio Mununga"
        },
        {
            "name": "Gabor Szabo"
        },
        {
            "name": "Andreas Müller"
        },
        {
            "name": "Andrew Pitman"
        },
        {
            "name": "Jacob Wejendorp"
        },
        {
            "name": "Alejandro López"
        },
        {
            "name": "Victor Belozyorov"
        },
        {
            "name": "Bradley Farias"
        },
        {
            "name": "Kyle E. Mitchell"
        },
        {
            "name": "Tuan Anh Tran"
        },
        {
            "name": "Nathan Woltman"
        },
        {
            "name": "Kyra"
        },
        {
            "name": "Leаh Neukirchen"
        },
        {
            "name": "Kyle Spier-Swenson"
        },
        {
            "name": "Joe Bowbeer"
        },
        {
            "name": "Nalin Bhardwaj"
        },
        {
            "name": "Nicolas Garnier"
        },
        {
            "name": "Vladislav Rassokhin"
        },
        {
            "name": "Josh Goldberg"
        },
        {
            "name": "laggingreflex"
        },
        {
            "name": "Kristofer Selbekk"
        },
        {
            "name": "Sreenivas Alapati"
        },
        {
            "name": "Ben Creasy"
        },
        {
            "name": "Allan Kimmer Jensen"
        },
        {
            "name": "rinfan"
        },
        {
            "name": "Matt Hoyle"
        },
        {
            "name": "Mason Pawsey"
        },
        {
            "name": "Johannes Bader"
        },
        {
            "name": "Michael Zabka"
        },
        {
            "name": "Bruce MacNaughton"
        },
        {
            "name": "Christopher Patty"
        },
        {
            "name": "Max Stoiber"
        },
        {
            "name": "Enrico Weigelt"
        },
        {
            "name": "David Hu"
        },
        {
            "name": "Steven R. Loomis"
        },
        {
            "name": "Julien Deniau"
        },
        {
            "name": "Prasanna Venkatesh T S"
        },
        {
            "name": "Alec Larson"
        },
        {
            "name": "John-David Dalton"
        },
        {
            "name": "Raymond Feng"
        },
        {
            "name": "Tieme van Veen"
        },
        {
            "name": "Finn Pauls"
        },
        {
            "name": "Jeremy Kahn"
        },
        {
            "name": "Mertcan Mermerkaya"
        }
    ],
    "dependencies": {
        "JSONStream": "^1.3.2",
        "abbrev": "~1.1.1",
        "ansi-regex": "~3.0.0",
        "ansicolors": "~0.3.2",
        "ansistyles": "~0.1.3",
        "aproba": "~1.2.0",
        "archy": "~1.0.0",
        "bin-links": "^1.1.2",
        "bluebird": "~3.5.1",
        "byte-size": "^4.0.3",
        "cacache": "^11.0.2",
        "call-limit": "~1.1.0",
        "chownr": "~1.0.1",
        "cli-columns": "^3.1.2",
        "cli-table2": "~0.2.0",
        "cmd-shim": "~2.0.2",
        "columnify": "~1.5.4",
        "config-chain": "~1.1.11",
        "debuglog": "*",
        "detect-indent": "~5.0.0",
        "detect-newline": "^2.1.0",
        "dezalgo": "~1.0.3",
        "editor": "~1.0.0",
        "figgy-pudding": "^3.1.0",
        "find-npm-prefix": "^1.0.2",
        "fs-vacuum": "~1.2.10",
        "fs-write-stream-atomic": "~1.0.10",
        "gentle-fs": "^2.0.1",
        "glob": "~7.1.2",
        "graceful-fs": "~4.1.11",
        "has-unicode": "~2.0.1",
        "hosted-git-info": "^2.6.0",
        "iferr": "^1.0.0",
        "imurmurhash": "*",
        "inflight": "~1.0.6",
        "inherits": "~2.0.3",
        "ini": "^1.3.5",
        "init-package-json": "^1.10.3",
        "is-cidr": "^2.0.5",
        "json-parse-better-errors": "^1.0.2",
        "lazy-property": "~1.0.0",
        "libcipm": "^1.6.2",
        "libnpmhook": "^4.0.1",
        "libnpx": "^10.2.0",
        "lock-verify": "^2.0.2",
        "lockfile": "^1.0.4",
        "lodash._baseindexof": "*",
        "lodash._baseuniq": "~4.6.0",
        "lodash._bindcallback": "*",
        "lodash._cacheindexof": "*",
        "lodash._createcache": "*",
        "lodash._getnative": "*",
        "lodash.clonedeep": "~4.5.0",
        "lodash.restparam": "*",
        "lodash.union": "~4.6.0",
        "lodash.uniq": "~4.5.0",
        "lodash.without": "~4.4.0",
        "lru-cache": "^4.1.3",
        "meant": "~1.0.1",
        "mississippi": "^3.0.0",
        "mkdirp": "~0.5.1",
        "move-concurrently": "^1.0.1",
        "node-gyp": "^3.6.2",
        "nopt": "~4.0.1",
        "normalize-package-data": "~2.4.0",
        "npm-audit-report": "^1.2.1",
        "npm-cache-filename": "~1.0.2",
        "npm-install-checks": "~3.0.0",
        "npm-lifecycle": "^2.0.3",
        "npm-package-arg": "^6.1.0",
        "npm-packlist": "~1.1.10",
        "npm-pick-manifest": "^2.1.0",
        "npm-profile": "^3.0.1",
        "npm-registry-client": "^8.5.1",
        "npm-registry-fetch": "^1.1.0",
        "npm-user-validate": "~1.0.0",
        "npmlog": "~4.1.2",
        "once": "~1.4.0",
        "opener": "~1.4.3",
        "osenv": "^0.1.5",
        "pacote": "^8.1.5",
        "path-is-inside": "~1.0.2",
        "promise-inflight": "~1.0.1",
        "qrcode-terminal": "^0.12.0",
        "query-string": "^6.1.0",
        "qw": "~1.0.1",
        "read": "~1.0.7",
        "read-cmd-shim": "~1.0.1",
        "read-installed": "~4.0.3",
        "read-package-json": "^2.0.13",
        "read-package-tree": "^5.2.1",
        "readable-stream": "^2.3.6",
        "readdir-scoped-modules": "*",
        "request": "^2.86.0",
        "retry": "^0.12.0",
        "rimraf": "~2.6.2",
        "safe-buffer": "^5.1.2",
        "semver": "^5.5.0",
        "sha": "~2.0.1",
        "slide": "~1.1.6",
        "sorted-object": "~2.0.1",
        "sorted-union-stream": "~2.1.3",
        "ssri": "^6.0.0",
        "strip-ansi": "~4.0.0",
        "tar": "^4.4.1",
        "text-table": "~0.2.0",
        "tiny-relative-date": "^1.3.0",
        "uid-number": "0.0.6",
        "umask": "~1.1.0",
        "unique-filename": "~1.1.0",
        "unpipe": "~1.0.0",
        "update-notifier": "^2.5.0",
        "uuid": "^3.2.1",
        "validate-npm-package-license": "^3.0.3",
        "validate-npm-package-name": "~3.0.0",
        "which": "~1.3.0",
        "worker-farm": "^1.6.0",
        "wrappy": "~1.0.2",
        "write-file-atomic": "^2.3.0"
    },
    "deprecated": false,
    "description": "a package manager for JavaScript",
    "devDependencies": {
        "deep-equal": "~1.0.1",
        "marked": "^0.3.19",
        "marked-man": "~0.2.1",
        "npm-registry-couchapp": "^2.7.1",
        "npm-registry-mock": "~1.1.0",
        "require-inject": "^1.4.3",
        "sprintf-js": "~1.1.1",
        "standard": "^11.0.1",
        "tacks": "~1.2.6",
        "tap": "^11.1.5"
    },
    "directories": {
        "bin": "./bin",
        "doc": "./doc",
        "lib": "./lib",
        "man": "./man"
    },
    "homepage": "https://docs.npmjs.com/",
    "keywords": [
        "install",
        "modules",
        "package manager",
        "package.json"
    ],
    "license": "Artistic-2.0",
    "main": "./lib/npm.js",
    "man": [
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-access.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-adduser.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-audit.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-bin.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-bugs.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-build.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-bundle.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-cache.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-ci.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-completion.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-config.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-dedupe.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-deprecate.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-dist-tag.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-docs.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-doctor.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-edit.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-explore.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-help-search.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-help.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-hook.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-init.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-install-ci-test.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-install-test.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-install.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-link.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-logout.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-ls.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-outdated.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-owner.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-pack.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-ping.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-prefix.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-profile.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-prune.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-publish.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-README.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-rebuild.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-repo.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-restart.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-root.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-run-script.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-search.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-shrinkwrap.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-star.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-stars.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-start.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-stop.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-team.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-test.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-token.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-uninstall.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-unpublish.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-update.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-version.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-view.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm-whoami.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npm.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man1/npx.1",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man5/npm-folders.5",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man5/npm-global.5",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man5/npm-json.5",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man5/npm-package-locks.5",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man5/npm-shrinkwrap.json.5",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man5/npmrc.5",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man5/package-lock.json.5",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man5/package.json.5",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-coding-style.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-config.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-developers.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-disputes.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-index.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-orgs.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-registry.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-scope.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/npm-scripts.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/removing-npm.7",
        "/home/travis/build/npmdoc/node-npmdoc-npm/node_modules/npm/man/man7/semver.7"
    ],
    "name": "npm",
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/npm/npm.git"
    },
    "scripts": {
        "dumpconf": "env | grep npm | sort | uniq",
        "prepare": "node bin/npm-cli.js --no-audit --no-timing prune --prefix=. --no-global && rimraf test/*/*/node_modules && make -j4 doc",
        "preversion": "bash scripts/update-authors.sh && git add AUTHORS && git commit -m \"update AUTHORS\" || true",
        "tap": "tap --reporter=classic --timeout 300",
        "tap-cover": "tap --reporter=classic --nyc-arg='--cache' --coverage --timeout 600",
        "test": "standard && npm run test-tap",
        "test-coverage": "npm run tap-cover -- \"test/tap/*.js\" \"test/network/*.js\" \"test/broken-under-*/*.js\"",
        "test-node": "tap --timeout 240 \"test/tap/*.js\" \"test/network/*.js\" \"test/broken-under-nyc*/*.js\"",
        "test-tap": "npm run tap -- \"test/tap/*.js\" \"test/network/*.js\" \"test/broken-under-*/*.js\""
    },
    "version": "6.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
