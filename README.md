# api documentation for  [npm (v4.4.4)](https://docs.npmjs.com/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm)
#### a package manager for JavaScript

[![NPM](https://nodei.co/npm/npm.png?downloads=true)](https://www.npmjs.com/package/npm)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-npm_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-npm/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "email": "i@izs.me",
        "url": "http://blog.izs.me"
    },
    "bin": {
        "npm": "./bin/npm-cli.js"
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
        "asap",
        "call-limit",
        "bluebird",
        "chownr",
        "cmd-shim",
        "columnify",
        "config-chain",
        "debuglog",
        "dezalgo",
        "editor",
        "fs-vacuum",
        "fs-write-stream-atomic",
        "fstream",
        "fstream-npm",
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
        "JSONStream",
        "lazy-property",
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
        "mkdirp",
        "mississippi",
        "move-concurrently",
        "node-gyp",
        "nopt",
        "normalize-git-url",
        "normalize-package-data",
        "npm-cache-filename",
        "npm-install-checks",
        "npm-package-arg",
        "npm-registry-client",
        "npm-user-validate",
        "npmlog",
        "once",
        "opener",
        "osenv",
        "path-is-inside",
        "read",
        "read-cmd-shim",
        "read-installed",
        "read-package-json",
        "read-package-tree",
        "readable-stream",
        "readdir-scoped-modules",
        "realize-package-specifier",
        "request",
        "retry",
        "rimraf",
        "semver",
        "sha",
        "slide",
        "sorted-object",
        "sorted-union-stream",
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
        "write-file-atomic"
    ],
    "config": {
        "publishtest": false
    },
    "contributors": [
        {
            "name": "Isaac Z. Schlueter",
            "email": "i@izs.me"
        },
        {
            "name": "Steve Steiner",
            "email": "ssteinerX@gmail.com"
        },
        {
            "name": "Mikeal Rogers",
            "email": "mikeal.rogers@gmail.com"
        },
        {
            "name": "Aaron Blohowiak",
            "email": "aaron.blohowiak@gmail.com"
        },
        {
            "name": "Martyn Smith",
            "email": "martyn@dollyfish.net.nz"
        },
        {
            "name": "Charlie Robbins",
            "email": "charlie.robbins@gmail.com"
        },
        {
            "name": "Francisco Treacy",
            "email": "francisco.treacy@gmail.com"
        },
        {
            "name": "Cliffano Subagio",
            "email": "cliffano@gmail.com"
        },
        {
            "name": "Christian Eager",
            "email": "christian.eager@nokia.com"
        },
        {
            "name": "Dav Glass",
            "email": "davglass@gmail.com"
        },
        {
            "name": "Alex K. Wolfe",
            "email": "alexkwolfe@gmail.com"
        },
        {
            "name": "James Sanders",
            "email": "jimmyjazz14@gmail.com"
        },
        {
            "name": "Reid Burke",
            "email": "me@reidburke.com"
        },
        {
            "name": "Arlo Breault",
            "email": "arlolra@gmail.com"
        },
        {
            "name": "Timo Derstappen",
            "email": "teemow@gmail.com"
        },
        {
            "name": "Bart Teeuwisse",
            "email": "bart.teeuwisse@thecodemill.biz"
        },
        {
            "name": "Ben Noordhuis",
            "email": "info@bnoordhuis.nl"
        },
        {
            "name": "Tor Valamo",
            "email": "tor.valamo@gmail.com"
        },
        {
            "name": "Whyme.Lyu",
            "email": "5longluna@gmail.com"
        },
        {
            "name": "Olivier Melcher",
            "email": "olivier.melcher@gmail.com"
        },
        {
            "name": "Tomaž Muraus",
            "email": "kami@k5-storitve.net"
        },
        {
            "name": "Evan Meagher",
            "email": "evan.meagher@gmail.com"
        },
        {
            "name": "Orlando Vazquez",
            "email": "ovazquez@gmail.com"
        },
        {
            "name": "Kai Chen",
            "email": "kaichenxyz@gmail.com"
        },
        {
            "name": "George Miroshnykov",
            "email": "gmiroshnykov@lohika.com"
        },
        {
            "name": "Geoff Flarity",
            "email": "geoff.flarity@gmail.com"
        },
        {
            "name": "Max Goodman",
            "email": "c@chromakode.com"
        },
        {
            "name": "Pete Kruckenberg",
            "email": "pete@kruckenberg.com"
        },
        {
            "name": "Laurie Harper",
            "email": "laurie@holoweb.net"
        },
        {
            "name": "Chris Wong",
            "email": "chris@chriswongstudio.com"
        },
        {
            "name": "Scott Bronson",
            "email": "brons_github@rinspin.com"
        },
        {
            "name": "Federico Romero",
            "email": "federomero@gmail.com"
        },
        {
            "name": "Visnu Pitiyanuvath",
            "email": "visnupx@gmail.com"
        },
        {
            "name": "Irakli Gozalishvili",
            "email": "rfobic@gmail.com"
        },
        {
            "name": "Mark Cahill",
            "email": "mark@tiemonster.info"
        },
        {
            "name": "Tony",
            "email": "zearin@gonk.net"
        },
        {
            "name": "Iain Sproat",
            "email": "iainsproat@gmail.com"
        },
        {
            "name": "Trent Mick",
            "email": "trentm@gmail.com"
        },
        {
            "name": "Felix Geisendörfer",
            "email": "felix@debuggable.com"
        },
        {
            "name": "Jameson Little",
            "email": "t.jameson.little@gmail.com"
        },
        {
            "name": "Conny Brunnkvist",
            "email": "conny@fuchsia.se"
        },
        {
            "name": "Will Elwood",
            "email": "w.elwood08@gmail.com"
        },
        {
            "name": "Dean Landolt",
            "email": "dean@deanlandolt.com"
        },
        {
            "name": "Oleg Efimov",
            "email": "efimovov@gmail.com"
        },
        {
            "name": "Martin Cooper",
            "email": "mfncooper@gmail.com"
        },
        {
            "name": "Jann Horn",
            "email": "jannhorn@googlemail.com"
        },
        {
            "name": "Andrew Bradley",
            "email": "cspotcode@gmail.com"
        },
        {
            "name": "Maciej Małecki",
            "email": "me@mmalecki.com"
        },
        {
            "name": "Stephen Sugden",
            "email": "glurgle@gmail.com"
        },
        {
            "name": "Michael Budde",
            "email": "mbudde@gmail.com"
        },
        {
            "name": "Jason Smith",
            "email": "jhs@iriscouch.com"
        },
        {
            "name": "Gautham Pai",
            "email": "buzypi@gmail.com"
        },
        {
            "name": "David Trejo",
            "email": "david.daniel.trejo@gmail.com"
        },
        {
            "name": "Paul Vorbach",
            "email": "paul@vorb.de"
        },
        {
            "name": "George Ornbo",
            "email": "george@shapeshed.com"
        },
        {
            "name": "Tim Oxley",
            "email": "secoif@gmail.com"
        },
        {
            "name": "Tyler Green",
            "email": "tyler.green2@gmail.com"
        },
        {
            "name": "Dave Pacheco",
            "email": "dap@joyent.com"
        },
        {
            "name": "Danila Gerasimov",
            "email": "danila.gerasimov@gmail.com"
        },
        {
            "name": "Rod Vagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "Christian Howe",
            "email": "coderarity@gmail.com"
        },
        {
            "name": "Andrew Lunny",
            "email": "alunny@gmail.com"
        },
        {
            "name": "Henrik Hodne",
            "email": "dvyjones@binaryhex.com"
        },
        {
            "name": "Adam Blackburn",
            "email": "regality@gmail.com"
        },
        {
            "name": "Kris Windham",
            "email": "kriswindham@gmail.com"
        },
        {
            "name": "Jens Grunert",
            "email": "jens.grunert@gmail.com"
        },
        {
            "name": "Joost-Wim Boekesteijn",
            "email": "joost-wim@boekesteijn.nl"
        },
        {
            "name": "Dalmais Maxence",
            "email": "root@ip-10-195-202-5.ec2.internal"
        },
        {
            "name": "Marcus Ekwall",
            "email": "marcus.ekwall@gmail.com"
        },
        {
            "name": "Aaron Stacy",
            "email": "aaron.r.stacy@gmail.com"
        },
        {
            "name": "Phillip Howell",
            "email": "phowell@cothm.org"
        },
        {
            "name": "Domenic Denicola",
            "email": "domenic@domenicdenicola.com"
        },
        {
            "name": "James Halliday",
            "email": "mail@substack.net"
        },
        {
            "name": "Jeremy Cantrell",
            "email": "jmcantrell@gmail.com"
        },
        {
            "name": "Ribettes",
            "email": "patlogan29@gmail.com"
        },
        {
            "name": "Don Park",
            "email": "donpark@docuverse.com"
        },
        {
            "name": "Einar Otto Stangvik",
            "email": "einaros@gmail.com"
        },
        {
            "name": "Kei Son",
            "email": "heyacct@gmail.com"
        },
        {
            "name": "Nicolas Morel",
            "email": "marsup@gmail.com"
        },
        {
            "name": "Mark Dube",
            "email": "markisdee@gmail.com"
        },
        {
            "name": "Nathan Rajlich",
            "email": "nathan@tootallnate.net"
        },
        {
            "name": "Maxim Bogushevich",
            "email": "boga1@mail.ru"
        },
        {
            "name": "Meaglin",
            "email": "Meaglin.wasabi@gmail.com"
        },
        {
            "name": "Ben Evans",
            "email": "ben@bensbit.co.uk"
        },
        {
            "name": "Nathan Zadoks",
            "email": "nathan@nathan7.eu"
        },
        {
            "name": "Brian White",
            "email": "mscdex@mscdex.net"
        },
        {
            "name": "Jed Schmidt",
            "email": "tr@nslator.jp"
        },
        {
            "name": "Ian Livingstone",
            "email": "ianl@cs.dal.ca"
        },
        {
            "name": "Patrick Pfeiffer",
            "email": "patrick@buzzle.at"
        },
        {
            "name": "Paul Miller",
            "email": "paul@paulmillr.com"
        },
        {
            "name": "Ryan Emery",
            "email": "seebees@gmail.com"
        },
        {
            "name": "Carl Lange",
            "email": "carl@flax.ie"
        },
        {
            "name": "Jan Lehnardt",
            "email": "jan@apache.org"
        },
        {
            "name": "Stuart P. Bentley",
            "email": "stuart@testtrack4.com"
        },
        {
            "name": "Johan Sköld",
            "email": "johan@skold.cc"
        },
        {
            "name": "Stuart Knightley",
            "email": "stuart@stuartk.com"
        },
        {
            "name": "Niggler",
            "email": "nirk.niggler@gmail.com"
        },
        {
            "name": "Paolo Fragomeni",
            "email": "paolo@async.ly"
        },
        {
            "name": "Jaakko Manninen",
            "email": "jaakko@rocketpack.fi"
        },
        {
            "name": "Luke Arduini",
            "email": "luke.arduini@gmail.com"
        },
        {
            "name": "Larz Conwell",
            "email": "larz@larz-laptop.(none)",
            "url": "none"
        },
        {
            "name": "Marcel Klehr",
            "email": "mklehr@gmx.net"
        },
        {
            "name": "Robert Kowalski",
            "email": "rok@kowalski.gd"
        },
        {
            "name": "Forbes Lindesay",
            "email": "forbes@lindesay.co.uk"
        },
        {
            "name": "Vaz Allen",
            "email": "vaz@tryptid.com"
        },
        {
            "name": "Jake Verbaten",
            "email": "raynos2@gmail.com"
        },
        {
            "name": "Schabse Laks",
            "email": "Dev@SLaks.net"
        },
        {
            "name": "Florian Margaine",
            "email": "florian@margaine.com"
        },
        {
            "name": "Johan Nordberg",
            "email": "its@johan-nordberg.com"
        },
        {
            "name": "Ian Babrou",
            "email": "ibobrik@gmail.com"
        },
        {
            "name": "Di Wu",
            "email": "dwu@palantir.com"
        },
        {
            "name": "Mathias Bynens",
            "email": "mathias@qiwi.be"
        },
        {
            "name": "Matt McClure",
            "email": "matt.mcclure@mapmyfitness.com"
        },
        {
            "name": "Matt Lunn",
            "email": "matt@mattlunn.me.uk"
        },
        {
            "name": "Alexey Kreschuk",
            "email": "akrsch@gmail.com"
        },
        {
            "name": "elisee",
            "email": "elisee@sparklin.org"
        },
        {
            "name": "Robert Gieseke",
            "email": "robert.gieseke@gmail.com"
        },
        {
            "name": "François Frisch",
            "email": "francoisfrisch@gmail.com"
        },
        {
            "name": "Trevor Burnham",
            "email": "tburnham@hubspot.com"
        },
        {
            "name": "Alan Shaw",
            "email": "alan@freestyle-developments.co.uk"
        },
        {
            "name": "TJ Holowaychuk",
            "email": "tj@vision-media.ca"
        },
        {
            "name": "Nicholas Kinsey",
            "email": "pyro@feisty.io"
        },
        {
            "name": "Paulo Cesar",
            "email": "pauloc062@gmail.com"
        },
        {
            "name": "Elan Shanker",
            "email": "elan.shanker@gmail.com"
        },
        {
            "name": "Jon Spencer",
            "email": "jon@jonspencer.ca"
        },
        {
            "name": "Jason Diamond",
            "email": "jason@diamond.name"
        },
        {
            "name": "Maximilian Antoni",
            "email": "mail@maxantoni.de"
        },
        {
            "name": "Thom Blake",
            "email": "tblake@brightroll.com"
        },
        {
            "name": "Jess Martin",
            "email": "jessmartin@gmail.com"
        },
        {
            "name": "Spain Train",
            "email": "michael.spainhower@opower.com"
        },
        {
            "name": "Alex Rodionov",
            "email": "p0deje@gmail.com"
        },
        {
            "name": "Matt Colyer",
            "email": "matt@colyer.name"
        },
        {
            "name": "Evan You",
            "email": "yyx990803@gmail.com"
        },
        {
            "name": "bitspill",
            "email": "bitspill+github@bitspill.net"
        },
        {
            "name": "Gabriel Falkenberg",
            "email": "gabriel.falkenberg@gmail.com"
        },
        {
            "name": "Alexej Yaroshevich",
            "email": "alex@qfox.ru"
        },
        {
            "name": "Quim Calpe",
            "email": "quim@kalpe.com"
        },
        {
            "name": "Steve Mason",
            "email": "stevem@brandwatch.com"
        },
        {
            "name": "Wil Moore III",
            "email": "wil.moore@wilmoore.com"
        },
        {
            "name": "Sergey Belov",
            "email": "peimei@ya.ru"
        },
        {
            "name": "Tom Huang",
            "email": "hzlhu.dargon@gmail.com"
        },
        {
            "name": "CamilleM",
            "email": "camille.moulin@alterway.fr"
        },
        {
            "name": "Sébastien Santoro",
            "email": "dereckson@espace-win.org"
        },
        {
            "name": "Evan Lucas",
            "email": "evan@btc.com"
        },
        {
            "name": "Quinn Slack",
            "email": "qslack@qslack.com"
        },
        {
            "name": "Alex Kocharin",
            "email": "alex@kocharin.ru"
        },
        {
            "name": "Daniel Santiago",
            "email": "daniel.santiago@highlevelwebs.com"
        },
        {
            "name": "Denis Gladkikh",
            "email": "outcoldman@gmail.com"
        },
        {
            "name": "Andrew Horton",
            "email": "andrew.j.horton@gmail.com"
        },
        {
            "name": "Zeke Sikelianos",
            "email": "zeke@sikelianos.com"
        },
        {
            "name": "Dylan Greene",
            "email": "dylang@gmail.com"
        },
        {
            "name": "Franck Cuny",
            "email": "franck.cuny@gmail.com"
        },
        {
            "name": "Yeonghoon Park",
            "email": "sola92@gmail.com"
        },
        {
            "name": "Rafael de Oleza",
            "email": "rafa@spotify.com"
        },
        {
            "name": "Mikola Lysenko",
            "email": "mikolalysenko@gmail.com"
        },
        {
            "name": "Yazhong Liu",
            "email": "yorkiefixer@gmail.com"
        },
        {
            "name": "Neil Gentleman",
            "email": "ngentleman@gmail.com"
        },
        {
            "name": "Kris Kowal",
            "email": "kris.kowal@cixar.com"
        },
        {
            "name": "Alex Gorbatchev",
            "email": "alex.gorbatchev@gmail.com"
        },
        {
            "name": "Shawn Wildermuth",
            "email": "shawn@wildermuth.com"
        },
        {
            "name": "Wesley de Souza",
            "email": "wesleywex@gmail.com"
        },
        {
            "name": "yoyoyogi",
            "email": "yogesh.k@gmail.com"
        },
        {
            "name": "J. Tangelder",
            "email": "j.tangelder@gmail.com"
        },
        {
            "name": "Jean Lauliac",
            "email": "jean@lauliac.com"
        },
        {
            "name": "Andrey Kislyuk",
            "email": "kislyuk@gmail.com"
        },
        {
            "name": "Thorsten Lorenz",
            "email": "thlorenz@gmx.de"
        },
        {
            "name": "Julian Gruber",
            "email": "julian@juliangruber.com"
        },
        {
            "name": "Benjamin Coe",
            "email": "bencoe@gmail.com"
        },
        {
            "name": "Alex Ford",
            "email": "Alex.Ford@CodeTunnel.com"
        },
        {
            "name": "Matt Hickford",
            "email": "matt.hickford@gmail.com"
        },
        {
            "name": "Sean McGivern",
            "email": "sean.mcgivern@rightscale.com"
        },
        {
            "name": "C J Silverio",
            "email": "ceejceej@gmail.com"
        },
        {
            "name": "Robin Tweedie",
            "email": "robin@songkick.com"
        },
        {
            "name": "Miroslav Bajtoš",
            "email": "miroslav@strongloop.com"
        },
        {
            "name": "David Glasser",
            "email": "glasser@davidglasser.net"
        },
        {
            "name": "Gianluca Casati",
            "email": "casati_gianluca@yahoo.it"
        },
        {
            "name": "Forrest L Norvell",
            "email": "ogd@aoaioxxysz.net"
        },
        {
            "name": "Karsten Tinnefeld",
            "email": "k.tinnefeld@googlemail.com"
        },
        {
            "name": "Bryan Burgers",
            "email": "bryan@burgers.io"
        },
        {
            "name": "David Beitey",
            "email": "david@davidjb.com"
        },
        {
            "name": "Evan You",
            "email": "yyou@google.com"
        },
        {
            "name": "Zach Pomerantz",
            "email": "zmp@umich.edu"
        },
        {
            "name": "Chris Williams",
            "email": "cwilliams88@gmail.com"
        },
        {
            "name": "sudodoki",
            "email": "smd.deluzion@gmail.com"
        },
        {
            "name": "Mick Thompson",
            "email": "dthompson@gmail.com"
        },
        {
            "name": "Felix Rabe",
            "email": "felix@rabe.io"
        },
        {
            "name": "Michael Hayes",
            "email": "michael@hayes.io"
        },
        {
            "name": "Chris Dickinson",
            "email": "christopher.s.dickinson@gmail.com"
        },
        {
            "name": "Bradley Meck",
            "email": "bradley.meck@gmail.com"
        },
        {
            "name": "GeJ",
            "email": "geraud@gcu.info"
        },
        {
            "name": "Andrew Terris",
            "email": "atterris@gmail.com"
        },
        {
            "name": "Michael Nisi",
            "email": "michael.nisi@gmail.com"
        },
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com"
        },
        {
            "name": "Adam Meadows",
            "email": "adam.meadows@gmail.com"
        },
        {
            "name": "Chulki Lee",
            "email": "chulki.lee@gmail.com"
        },
        {
            "name": "不四",
            "email": "busi.hyy@taobao.com"
        },
        {
            "name": "dead_horse",
            "email": "dead_horse@qq.com"
        },
        {
            "name": "Kenan Yildirim",
            "email": "kenan@kenany.me"
        },
        {
            "name": "Laurie Voss",
            "email": "git@seldo.com"
        },
        {
            "name": "Rebecca Turner",
            "email": "me@re-becca.org"
        },
        {
            "name": "Hunter Loftis",
            "email": "hunter@hunterloftis.com"
        },
        {
            "name": "Peter Richardson",
            "email": "github@zoomy.net"
        },
        {
            "name": "Jussi Kalliokoski",
            "email": "jussi.kalliokoski@gmail.com"
        },
        {
            "name": "Filip Weiss",
            "email": "me@fiws.net"
        },
        {
            "name": "Timo Weiß",
            "email": "timoweiss@Timo-MBP.local"
        },
        {
            "name": "Christopher Hiller",
            "email": "chiller@badwing.com"
        },
        {
            "name": "Jérémy Lal",
            "email": "kapouer@melix.org"
        },
        {
            "name": "Anders Janmyr",
            "email": "anders@janmyr.com"
        },
        {
            "name": "Chris Meyers",
            "email": "chris.meyers.fsu@gmail.com"
        },
        {
            "name": "Ludwig Magnusson",
            "email": "ludwig@mediatool.com"
        },
        {
            "name": "Wout Mertens",
            "email": "Wout.Mertens@gmail.com"
        },
        {
            "name": "Nick Santos",
            "email": "nick@medium.com"
        },
        {
            "name": "Terin Stock",
            "email": "terinjokes@gmail.com"
        },
        {
            "name": "Faiq Raza",
            "email": "faiqrazarizvi@gmail.com"
        },
        {
            "name": "Thomas Torp",
            "email": "thomas@erupt.no"
        },
        {
            "name": "Sam Mikes",
            "email": "smikes@cubane.com"
        },
        {
            "name": "Mat Tyndall",
            "email": "mat.tyndall@gmail.com"
        },
        {
            "name": "Tauren Mills",
            "email": "tauren@sportzing.com"
        },
        {
            "name": "Ron Martinez",
            "email": "ramartin.net@gmail.com"
        },
        {
            "name": "Kazuhito Hokamura",
            "email": "k.hokamura@gmail.com"
        },
        {
            "name": "Tristan Davies",
            "email": "github@tristan.io"
        },
        {
            "name": "David Volm",
            "email": "david@volminator.com"
        },
        {
            "name": "Lin Clark",
            "email": "lin.w.clark@gmail.com"
        },
        {
            "name": "Ben Page",
            "email": "bpage@dewalch.com"
        },
        {
            "name": "Jeff Jo",
            "email": "jeffjo@squareup.com"
        },
        {
            "name": "martinvd",
            "email": "martinvdpub@gmail.com"
        },
        {
            "name": "Mark J. Titorenko",
            "email": "nospam-github.com@titorenko.net"
        },
        {
            "name": "Oddur Sigurdsson",
            "email": "oddurs@gmail.com"
        },
        {
            "name": "Eric Mill",
            "email": "eric@konklone.com"
        },
        {
            "name": "Gabriel Barros",
            "email": "descartavel1@gmail.com"
        },
        {
            "name": "KevinSheedy",
            "email": "kevinsheedy@gmail.com"
        },
        {
            "name": "Aleksey Smolenchuk",
            "email": "aleksey@uber.com"
        },
        {
            "name": "Ed Morley",
            "email": "emorley@mozilla.com"
        },
        {
            "name": "Blaine Bublitz",
            "email": "blaine@iceddev.com"
        },
        {
            "name": "Andrey Fedorov",
            "email": "anfedorov@gmail.com"
        },
        {
            "name": "Daijiro Wachi",
            "email": "daijiro.wachi@gmail.com"
        },
        {
            "name": "Luc Thevenard",
            "email": "lucthevenard@gmail.com"
        },
        {
            "name": "Aria Stewart",
            "email": "aredridel@nbtsc.org"
        },
        {
            "name": "Charlie Rudolph",
            "email": "charles.w.rudolph@gmail.com"
        },
        {
            "name": "Vladimir Rutsky",
            "email": "rutsky@users.noreply.github.com"
        },
        {
            "name": "Isaac Murchie",
            "email": "isaac@saucelabs.com"
        },
        {
            "name": "Marcin Wosinek",
            "email": "marcin.wosinek@gmail.com"
        },
        {
            "name": "David Marr",
            "email": "davemarr@gmail.com"
        },
        {
            "name": "Bryan English",
            "email": "bryan@bryanenglish.com"
        },
        {
            "name": "Anthony Zotti",
            "email": "amZotti@users.noreply.github.com"
        },
        {
            "name": "Karl Horky",
            "email": "karl.horky@gmail.com"
        },
        {
            "name": "Jordan Harband",
            "email": "ljharb@gmail.com"
        },
        {
            "name": "Guðlaugur Stefán Egilsson",
            "email": "gulli@kolibri.is"
        },
        {
            "name": "Helge Skogly Holm",
            "email": "helge.holm@gmail.com"
        },
        {
            "name": "Peter A. Shevtsov",
            "email": "petr.shevtsov@gmail.com"
        },
        {
            "name": "Alain Kalker",
            "email": "a.c.kalker@gmail.com"
        },
        {
            "name": "Bryant Williams",
            "email": "b.n.williams@gmail.com"
        },
        {
            "name": "Jonas Weber",
            "email": "github@jonasw.de"
        },
        {
            "name": "Tim Whidden",
            "email": "twhid@twhid.com"
        },
        {
            "name": "Andreas",
            "email": "functino@users.noreply.github.com"
        },
        {
            "name": "Karolis Narkevicius",
            "email": "karolis.n@gmail.com"
        },
        {
            "name": "Adrian Lynch",
            "email": "adi_ady_ade@hotmail.com"
        },
        {
            "name": "Richard Littauer",
            "email": "richard.littauer@gmail.com"
        },
        {
            "name": "Oli Evans",
            "email": "oli@zilla.org.uk"
        },
        {
            "name": "Matt Brennan",
            "email": "mattyb1000@gmail.com"
        },
        {
            "name": "Jeff Barczewski",
            "email": "jeff.barczewski@gmail.com"
        },
        {
            "name": "Danny Fritz",
            "email": "dannyfritz@gmail.com"
        },
        {
            "name": "Takaya Kobayashi",
            "email": "jigsaw@live.jp"
        },
        {
            "name": "Ra'Shaun Stovall",
            "email": "rashaunstovall@gmail.com"
        },
        {
            "name": "Julien Meddah",
            "email": "julien.meddah@deveryware.com"
        },
        {
            "name": "Michiel Sikma",
            "email": "michiel@wedemandhtml.com"
        },
        {
            "name": "Jakob Krigovsky",
            "email": "jakob.krigovsky@gmail.com"
        },
        {
            "name": "Charmander",
            "email": "~@charmander.me"
        },
        {
            "name": "Erik Wienhold",
            "email": "git@ewie.name"
        },
        {
            "name": "James Butler",
            "email": "james.butler@sandfox.co.uk"
        },
        {
            "name": "Kevin Kragenbrink",
            "email": "kevin@gaikai.com"
        },
        {
            "name": "Arnaud Rinquin",
            "email": "rinquin.arnaud@gmail.com"
        },
        {
            "name": "Mike MacCana",
            "email": "mike.maccana@gmail.com"
        },
        {
            "name": "Antti Mattila",
            "email": "anttti@fastmail.fm"
        },
        {
            "name": "laiso",
            "email": "laiso@lai.so"
        },
        {
            "name": "Matt Zorn",
            "email": "zornme@gmail.com"
        },
        {
            "name": "Kyle Mitchell",
            "email": "kyle@kemitchell.com"
        },
        {
            "name": "Jeremiah Senkpiel",
            "email": "fishrock123@rocketmail.com"
        },
        {
            "name": "Michael Klein",
            "email": "mischkl@users.noreply.github.com"
        },
        {
            "name": "Simen Bekkhus",
            "email": "sbekkhus91@gmail.com"
        },
        {
            "name": "Victor",
            "email": "victor.shih@gmail.com"
        },
        {
            "name": "thefourtheye",
            "email": "thechargingvolcano@gmail.com"
        },
        {
            "name": "Clay Carpenter",
            "email": "claycarpenter@gmail.com"
        },
        {
            "name": "bangbang93",
            "email": "bangbang93@163.com"
        },
        {
            "name": "Nick Malaguti",
            "email": "nmalaguti@palantir.com"
        },
        {
            "name": "Cedric Nelson",
            "email": "cedric.nelson@gmail.com"
        },
        {
            "name": "Kat Marchán",
            "email": "kzm@sykosomatic.org"
        },
        {
            "name": "Andrew",
            "email": "talktome@aboutandrew.co.uk"
        },
        {
            "name": "Eduardo Pinho",
            "email": "enet4mikeenet@gmail.com"
        },
        {
            "name": "Rachel Hutchison",
            "email": "rhutchix@intel.com"
        },
        {
            "name": "Ryan Temple",
            "email": "ryantemple145@gmail.com"
        },
        {
            "name": "Eugene Sharygin",
            "email": "eush77@gmail.com"
        },
        {
            "name": "James Talmage",
            "email": "james@talmage.io"
        },
        {
            "name": "jane arc",
            "email": "jane@uber.com"
        },
        {
            "name": "Joseph Dykstra",
            "email": "josephdykstra@gmail.com"
        },
        {
            "name": "Andrew Crites",
            "email": "ajcrites@gmail.com"
        },
        {
            "name": "Joshua Egan",
            "email": "josh-egan@users.noreply.github.com"
        },
        {
            "name": "Carlos Alberto",
            "email": "euprogramador@gmail.com"
        },
        {
            "name": "Thomas Cort",
            "email": "thomasc@ssimicro.com"
        },
        {
            "name": "Thaddee Tyl",
            "email": "thaddee.tyl@gmail.com"
        },
        {
            "name": "Steve Klabnik",
            "email": "steve@steveklabnik.com"
        },
        {
            "name": "Andrew Murray",
            "email": "radarhere@gmail.com"
        },
        {
            "name": "Stephan Bönnemann",
            "email": "stephan@excellenteasy.com"
        },
        {
            "name": "Kyle M. Tarplee",
            "email": "kyle.tarplee@numerica.us"
        },
        {
            "name": "Derek Peterson",
            "email": "derekpetey@gmail.com"
        },
        {
            "name": "Greg Whiteley",
            "email": "greg.whiteley@atomos.com"
        },
        {
            "name": "murgatroid99",
            "email": "mlumish@google.com"
        },
        {
            "name": "Marcin Cieslak",
            "email": "saper@saper.info"
        },
        {
            "name": "João Reis",
            "email": "reis@janeasystems.com"
        },
        {
            "name": "Matthew Hasbach",
            "email": "hasbach.git@gmail.com"
        },
        {
            "name": "Jon Hall",
            "email": "jon_hall@outlook.com"
        },
        {
            "name": "Anna Henningsen",
            "email": "sqrt@entless.org"
        },
        {
            "name": "James Treworgy",
            "email": "jamietre@gmail.com"
        },
        {
            "name": "James Hartig",
            "email": "james@levenlabs.com"
        },
        {
            "name": "Stephanie Snopek",
            "email": "stephaniesnopek@gmail.com"
        },
        {
            "name": "Kent C. Dodds",
            "email": "kent@doddsfamily.us"
        },
        {
            "name": "Aaron Krause",
            "email": "aaronjkrause@gmail.com"
        },
        {
            "name": "Daniel K O'Leary",
            "email": "daniel@dko.io"
        },
        {
            "name": "fscherwi",
            "email": "fscherwi@users.noreply.github.com"
        },
        {
            "name": "Thomas Reggi",
            "email": "thomas@reggi.com"
        },
        {
            "name": "Thomas Michael McTiernan",
            "email": "thomasmctiernan@gmail.com"
        },
        {
            "name": "Jason Kurian",
            "email": "JaKXz@users.noreply.github.com"
        },
        {
            "name": "Sebastiaan Deckers",
            "email": "seb@ninja.sg"
        },
        {
            "name": "lady3bean",
            "email": "lady3bean@users.noreply.github.com"
        },
        {
            "name": "Tomi Carr",
            "email": "TaMe3971@users.noreply.github.com"
        },
        {
            "name": "Juan Caicedo",
            "email": "retiredcanadianpoet@gmail.com"
        },
        {
            "name": "Ashley Williams",
            "email": "ashley@npmjs.com"
        },
        {
            "name": "Andrew Marcinkevičius",
            "email": "andrew.web@ifdattic.com"
        },
        {
            "name": "Jorrit Schippers",
            "email": "jorrit@ncode.nl"
        },
        {
            "name": "Alex Lukin",
            "email": "alex.lukin@softgrad.com"
        },
        {
            "name": "Aria Stewart",
            "email": "aredridel@dinhe.net"
        },
        {
            "name": "Tiago Rodrigues",
            "email": "tmcrodrigues@gmail.com"
        },
        {
            "name": "Tim",
            "email": "tim-github@baverstock.org.uk"
        },
        {
            "name": "Nick Williams",
            "email": "WickyNilliams@users.noreply.github.com"
        },
        {
            "name": "Louis Larry",
            "email": "louis.larry@gmail.com"
        },
        {
            "name": "Ben Gotow",
            "email": "bengotow@gmail.com"
        },
        {
            "name": "Jakub Gieryluk",
            "email": "jakub.g.opensource@gmail.com"
        },
        {
            "name": "Kevin Lorenz",
            "email": "mail@kevinlorenz.com"
        },
        {
            "name": "Martin von Gagern",
            "email": "Martin.vGagern@gmx.net"
        },
        {
            "name": "Eymen Gunay",
            "email": "eymen@egunay.com"
        },
        {
            "name": "Martin Ek",
            "email": "mail@ekmartin.com"
        },
        {
            "name": "Rafał Pocztarski",
            "email": "r.pocztarski@gmail.com"
        },
        {
            "name": "Mark Reeder",
            "email": "mreeder@uber.com"
        },
        {
            "name": "Chris Rebert",
            "email": "github@chrisrebert.com"
        },
        {
            "name": "Scott Addie",
            "email": "tobias.addie@gmail.com"
        },
        {
            "name": "Jeff McMahan",
            "email": "jeffrey.lee.mcmahan@gmail.com"
        },
        {
            "name": "Tim Krins",
            "email": "timkrins@gmail.com"
        },
        {
            "name": "Hal Henke",
            "email": "halhenke@gmail.com"
        },
        {
            "name": "Julian Simioni",
            "email": "julian@simioni.org"
        },
        {
            "name": "Jimb Esser",
            "email": "jimb@yahoo-inc.com"
        },
        {
            "name": "Alexis Campailla",
            "email": "alexis@janeasystems.com"
        },
        {
            "name": "Chris Chua",
            "email": "chris.sirhc@gmail.com"
        },
        {
            "name": "Beau Gunderson",
            "email": "beau@beaugunderson.com"
        },
        {
            "name": "Dave Galbraith",
            "email": "dave@jut.io"
        },
        {
            "name": "s100",
            "email": "shughes1@uk.ibm.com"
        },
        {
            "name": "Sergey Simonchik",
            "email": "sergey.simonchik@jetbrains.com"
        },
        {
            "name": "Vanja Radovanović",
            "email": "elvanja@gmail.com"
        },
        {
            "name": "Jonathan Persson",
            "email": "persson.jonathan@gmail.com"
        },
        {
            "name": "Vedat Mahir YILMAZ",
            "email": "mahir@vedatmahir.com"
        },
        {
            "name": "Samuel Reed",
            "email": "samuel.trace.reed@gmail.com"
        },
        {
            "name": "Rafał Legiędź",
            "email": "rafal.legiedz@gmail.com"
        },
        {
            "name": "Jan Schär",
            "email": "jscissr@gmail.com"
        },
        {
            "name": "Xcat Liu",
            "email": "xcatliu@gmail.com"
        },
        {
            "name": "harryh",
            "email": "Aourin@users.noreply.github.com"
        },
        {
            "name": "Prayag Verma",
            "email": "prayag.verma@gmail.com"
        },
        {
            "name": "Neil Kistner",
            "email": "neil.kistner@gmail.com"
        },
        {
            "name": "Zoujie Wzj",
            "email": "zoujie.wzj@alibaba-inc.com"
        },
        {
            "name": "Ryan Hendrickson",
            "email": "ryan.hendrickson@alum.mit.edu"
        },
        {
            "name": "Arturo Coronel",
            "email": "aoitsu3@gmail.com"
        },
        {
            "name": "Hutson Betts",
            "email": "hbetts@factset.com"
        },
        {
            "name": "Lewis Cowper",
            "email": "lewis.cowper@googlemail.com"
        },
        {
            "name": "Adam Byrne",
            "email": "misterbyrne@gmail.com"
        },
        {
            "name": "Ifeanyi Oraelosi",
            "email": "ifeanyioraelosi@gmail.com"
        },
        {
            "name": "Robert Ludwig",
            "email": "rob.ludwig@rideamigos.com"
        },
        {
            "name": "Chris Warren",
            "email": "chris@ixalon.net"
        },
        {
            "name": "Scott Plumlee",
            "email": "scott@plumlee.org"
        },
        {
            "name": "Daniel Pedersen",
            "email": "daniel@scandinav.se"
        },
        {
            "name": "rhgb",
            "email": "kaiserdaemon@gmail.com"
        },
        {
            "name": "doug.wade",
            "email": "doug.wade@redfin.com"
        },
        {
            "name": "Zac",
            "email": "zdoege@gm.slc.edu"
        },
        {
            "name": "GriffinSchneider",
            "email": "griffinschneider@gmail.com"
        },
        {
            "name": "Andres Kalle",
            "email": "mjomble@gmail.com"
        },
        {
            "name": "thefourtheye",
            "email": "thefourtheye@users.noreply.github.com"
        },
        {
            "name": "Yael",
            "email": "yaelz@users.noreply.github.com"
        },
        {
            "name": "Yann Odeyer",
            "email": "yann@odeyer.com"
        },
        {
            "name": "James Monger",
            "email": "jameskmonger@hotmail.co.uk"
        },
        {
            "name": "Thomas Hallock",
            "email": "thomas@1stdibs.com"
        },
        {
            "name": "Paul Irish",
            "email": "paul.irish@gmail.com"
        },
        {
            "name": "Paul O'Leary McCann",
            "email": "polm@dampfkraft.com"
        },
        {
            "name": "Francis Gulotta",
            "email": "wizard@roborooter.com"
        },
        {
            "name": "Felix Rieseberg",
            "email": "felix@felixrieseberg.com"
        },
        {
            "name": "Glen Mailer",
            "email": "glenjamin@gmail.com"
        },
        {
            "name": "Federico Brigante",
            "email": "bfred-it@users.noreply.github.com"
        },
        {
            "name": "Steve Mao",
            "email": "maochenyan@gmail.com"
        },
        {
            "name": "Anna Henningsen",
            "email": "anna@addaleax.net"
        },
        {
            "name": "Rachel Evans",
            "email": "git@rve.org.uk"
        },
        {
            "name": "Sam Minnee",
            "email": "sam@silverstripe.com"
        },
        {
            "name": "Zirak",
            "email": "zirakertan@gmail.com"
        },
        {
            "name": "Daniel Lupu",
            "email": "lupu.daniel.f@gmail.com"
        },
        {
            "name": "Gianluca Casati",
            "email": "fibo@users.noreply.github.com"
        },
        {
            "name": "André Herculano",
            "email": "andresilveirah@gmail.com"
        },
        {
            "name": "Wyatt Preul",
            "email": "wpreul@gmail.com"
        },
        {
            "name": "Myles Borins",
            "email": "mborins@us.ibm.com"
        },
        {
            "name": "Elliot Lee",
            "email": "github.public@intelliot.com"
        },
        {
            "name": "Dmitry Kirilyuk",
            "email": "gk.joker@gmail.com"
        },
        {
            "name": "Aaron Tribou",
            "email": "aaron.tribou@gmail.com"
        },
        {
            "name": "Tapani Moilanen",
            "email": "moilanen.tapani@gmail.com"
        },
        {
            "name": "Han Seoul-Oh",
            "email": "laughinghan@gmail.com"
        },
        {
            "name": "Aleksey Shvayka",
            "email": "shvaikalesh@gmail.com"
        },
        {
            "name": "Emma Ramirez",
            "email": "ramirez.emma.g@gmail.com"
        },
        {
            "name": "Julian Duque",
            "email": "julianduquej@gmail.com"
        },
        {
            "name": "Simon MacDonald",
            "email": "simon.macdonald@gmail.com"
        },
        {
            "name": "Adam Stankiewicz",
            "email": "sheerun@sher.pl"
        },
        {
            "name": "Gregers Gram Rygg",
            "email": "gregers.gram.rygg@finn.no"
        },
        {
            "name": "Peter Dave Hello",
            "email": "hsu@peterdavehello.org"
        },
        {
            "name": "Jordan Klassen",
            "email": "forivall@gmail.com"
        },
        {
            "name": "Jason Palmer",
            "email": "jason@jason-palmer.com"
        },
        {
            "name": "Michael Hart",
            "email": "michael.hart.au@gmail.com"
        },
        {
            "name": "Sasha Koss",
            "email": "koss@nocorp.me"
        },
        {
            "name": "David Emmerson",
            "email": "david.emmerson@gmail.com"
        },
        {
            "name": "Christophe Hurpeau",
            "email": "christophe@hurpeau.com"
        },
        {
            "name": "Daniel Paz-Soldan",
            "email": "daniel.pazsoldan@gmail.com"
        },
        {
            "name": "Sakthipriyan Vairamani",
            "email": "thechargingvolcano@gmail.com"
        },
        {
            "name": "Zach Renner",
            "email": "zarenner@microsoft.com"
        },
        {
            "name": "Christopher Hiller",
            "email": "boneskull@boneskull.com"
        },
        {
            "name": "legodude17",
            "email": "legodudejb@gmail.com"
        },
        {
            "name": "Andrew Meyer",
            "email": "andrewm.bpi@gmail.com"
        },
        {
            "name": "Michael Jasper",
            "email": "mdjasper@gmail.com"
        },
        {
            "name": "Max",
            "email": "contact@mstoiber.com"
        },
        {
            "name": "Szymon Nowak",
            "email": "szimek@gmail.com"
        },
        {
            "name": "Jason Karns",
            "email": "jason.karns@gmail.com"
        },
        {
            "name": "Lucas Holmquist",
            "email": "lholmqui@redhat.com"
        },
        {
            "name": "Ionică Bizău",
            "email": "bizauionica@gmail.com"
        },
        {
            "name": "Alex Chesters",
            "email": "AlexChesters@users.noreply.github.com"
        },
        {
            "name": "Robert Gay",
            "email": "robert.gay@redfin.com"
        },
        {
            "name": "Steven",
            "email": "stevokk@hotmail.com"
        },
        {
            "name": "Tim Caswell",
            "email": "tim@creationix.com"
        },
        {
            "name": "Anna Henningsen",
            "email": "github@addaleax.net"
        },
        {
            "name": "Kim Røen",
            "email": "kim@kimroen.com"
        },
        {
            "name": "Douglas Wilson",
            "email": "dougwilson@live.com"
        },
        {
            "name": "Mike Engel",
            "email": "mike@mike-engel.com"
        },
        {
            "name": "baderbuddy",
            "email": "baderbuddy@gmail.com"
        },
        {
            "name": "Alex Jordan",
            "email": "alex@strugee.net"
        },
        {
            "name": "Ville Lahdenvuo",
            "email": "tuhoojabotti@gmail.com"
        },
        {
            "name": "Natalie Wolfe",
            "email": "nwolfe@newrelic.com"
        },
        {
            "name": "Andrew Schmadel",
            "email": "aschmadel@learningobjects.com"
        },
        {
            "name": "Jonah Moses",
            "email": "jonahkmoses@gmail.com"
        },
        {
            "name": "Daijirō Wachi",
            "email": "daijiro.wachi@gmail.com"
        },
        {
            "name": "Dmitry Litvinchenko",
            "email": "karaliti@gmail.com"
        },
        {
            "name": "chocolateboy",
            "email": "chocolate@cpan.org"
        },
        {
            "name": "Henry Zhu",
            "email": "hi@henryzoo.com"
        },
        {
            "name": "Nate Goldman",
            "email": "ungoldman@gmail.com"
        },
        {
            "name": "Ted Yavuzkurt",
            "email": "hello@TedY.io"
        },
        {
            "name": "Arseniy Maximov",
            "email": "localhost@kern0.ru"
        },
        {
            "name": "Joshua Bennett",
            "email": "legodude17@users.noreply.github.com"
        },
        {
            "name": "Evgeny Kulikov",
            "email": "beyondcompute@users.noreply.github.com"
        },
        {
            "name": "Сковорода Никита Андреевич",
            "email": "chalkerx@gmail.com"
        },
        {
            "name": "Carol",
            "email": "carol.nichols@gmail.com",
            "url": "Nichols || Goulding"
        }
    ],
    "dependencies": {
        "JSONStream": "~1.3.1",
        "abbrev": "~1.1.0",
        "ansi-regex": "~2.1.1",
        "ansicolors": "~0.3.2",
        "ansistyles": "~0.1.3",
        "aproba": "~1.1.1",
        "archy": "~1.0.0",
        "asap": "~2.0.5",
        "bluebird": "~3.5.0",
        "call-limit": "~1.1.0",
        "chownr": "~1.0.1",
        "cmd-shim": "~2.0.2",
        "columnify": "~1.5.4",
        "config-chain": "~1.1.11",
        "debuglog": "*",
        "dezalgo": "~1.0.3",
        "editor": "~1.0.0",
        "fs-vacuum": "~1.2.10",
        "fs-write-stream-atomic": "~1.0.10",
        "fstream": "~1.0.11",
        "fstream-npm": "~1.2.0",
        "glob": "~7.1.1",
        "graceful-fs": "~4.1.11",
        "has-unicode": "~2.0.1",
        "hosted-git-info": "~2.2.0",
        "iferr": "~0.1.5",
        "imurmurhash": "*",
        "inflight": "~1.0.6",
        "inherits": "~2.0.3",
        "ini": "~1.3.4",
        "init-package-json": "~1.9.5",
        "lazy-property": "~1.0.0",
        "lockfile": "~1.0.3",
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
        "mississippi": "~1.3.0",
        "mkdirp": "~0.5.1",
        "move-concurrently": "~1.0.1",
        "node-gyp": "~3.5.0",
        "nopt": "~4.0.1",
        "normalize-git-url": "~3.0.2",
        "normalize-package-data": "~2.3.6",
        "npm-cache-filename": "~1.0.2",
        "npm-install-checks": "~3.0.0",
        "npm-package-arg": "~4.2.1",
        "npm-registry-client": "~7.4.6",
        "npm-user-validate": "~0.1.5",
        "npmlog": "~4.0.2",
        "once": "~1.4.0",
        "opener": "~1.4.3",
        "osenv": "~0.1.4",
        "path-is-inside": "~1.0.2",
        "read": "~1.0.7",
        "read-cmd-shim": "~1.0.1",
        "read-installed": "~4.0.3",
        "read-package-json": "~2.0.5",
        "read-package-tree": "~5.1.5",
        "readable-stream": "~2.2.3",
        "readdir-scoped-modules": "*",
        "realize-package-specifier": "~3.0.3",
        "request": "~2.81.0",
        "retry": "~0.10.1",
        "rimraf": "~2.6.1",
        "semver": "~5.3.0",
        "sha": "~2.0.1",
        "slide": "~1.1.6",
        "sorted-object": "~2.0.1",
        "sorted-union-stream": "~2.1.3",
        "strip-ansi": "~3.0.1",
        "tar": "~2.2.1",
        "text-table": "~0.2.0",
        "uid-number": "0.0.6",
        "umask": "~1.1.0",
        "unique-filename": "~1.1.0",
        "unpipe": "~1.0.0",
        "update-notifier": "~2.1.0",
        "uuid": "~3.0.1",
        "validate-npm-package-license": "*",
        "validate-npm-package-name": "~3.0.0",
        "which": "~1.2.12",
        "wrappy": "~1.0.2",
        "write-file-atomic": "~1.3.1"
    },
    "description": "a package manager for JavaScript",
    "devDependencies": {
        "deep-equal": "~1.0.1",
        "marked": "~0.3.6",
        "marked-man": "~0.2.0",
        "npm-registry-couchapp": "~2.6.12",
        "npm-registry-mock": "~1.1.0",
        "require-inject": "~1.4.0",
        "sprintf-js": "~1.0.3",
        "standard": "~6.0.8",
        "tacks": "~1.2.6",
        "tap": "~10.3.0"
    },
    "directories": {
        "bin": "./bin",
        "doc": "./doc",
        "lib": "./lib",
        "man": "./man"
    },
    "dist": {
        "shasum": "d5ec661923a06bcd6a6eec3d0433a9da3fd67e37",
        "tarball": "https://registry.npmjs.org/npm/-/npm-4.4.4.tgz"
    },
    "gitHead": "63468a65738547d730232196c094f19a8a383c99",
    "homepage": "https://docs.npmjs.com/",
    "keywords": [
        "install",
        "modules",
        "package manager",
        "package.json"
    ],
    "license": "Artistic-2.0",
    "main": "./lib/npm.js",
    "maintainers": [
        {
            "name": "ceejbot",
            "email": "ceejceej@gmail.com"
        },
        {
            "name": "iarna",
            "email": "me@re-becca.org"
        },
        {
            "name": "isaacs",
            "email": "i@izs.me"
        },
        {
            "name": "zkat",
            "email": "kat@sykosomatic.org"
        }
    ],
    "man": [
        "/Users/rebecca/code/release/npm-4/man/man1/npm-access.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-adduser.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-bin.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-bugs.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-build.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-bundle.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-cache.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-completion.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-config.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-dedupe.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-deprecate.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-dist-tag.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-docs.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-doctor.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-edit.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-explore.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-help-search.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-help.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-init.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-install-test.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-install.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-link.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-logout.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-ls.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-outdated.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-owner.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-pack.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-ping.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-prefix.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-prune.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-publish.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-README.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-rebuild.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-repo.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-restart.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-root.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-run-script.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-search.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-shrinkwrap.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-star.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-stars.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-start.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-stop.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-team.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-test.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-uninstall.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-unpublish.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-update.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-version.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-view.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm-whoami.1",
        "/Users/rebecca/code/release/npm-4/man/man1/npm.1",
        "/Users/rebecca/code/release/npm-4/man/man5/npm-folders.5",
        "/Users/rebecca/code/release/npm-4/man/man5/npm-global.5",
        "/Users/rebecca/code/release/npm-4/man/man5/npm-json.5",
        "/Users/rebecca/code/release/npm-4/man/man5/npmrc.5",
        "/Users/rebecca/code/release/npm-4/man/man5/package.json.5",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-coding-style.7",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-config.7",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-developers.7",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-disputes.7",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-index.7",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-orgs.7",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-registry.7",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-scope.7",
        "/Users/rebecca/code/release/npm-4/man/man7/npm-scripts.7",
        "/Users/rebecca/code/release/npm-4/man/man7/removing-npm.7",
        "/Users/rebecca/code/release/npm-4/man/man7/semver.7"
    ],
    "name": "npm",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/npm/npm.git"
    },
    "scripts": {
        "dumpconf": "env | grep npm | sort | uniq",
        "prepare": "node bin/npm-cli.js prune --prefix=. --no-global && rimraf test/*/*/node_modules && make -j4 doc",
        "preversion": "bash scripts/update-authors.sh && git add AUTHORS && git commit -m \"update AUTHORS\" || true",
        "tap": "tap --timeout 300",
        "tap-cover": "tap --nyc-arg='--cache' --coverage --timeout 600",
        "test": "standard && npm run test-tap",
        "test-coverage": "npm run tap-cover -- \"test/tap/*.js\" \"test/network/*.js\" \"test/broken-under-*/*.js\"",
        "test-node": "tap --timeout 240 \"test/tap/*.js\" \"test/network/*.js\" \"test/broken-under-nyc*/*.js\"",
        "test-tap": "npm run tap -- \"test/tap/*.js\" \"test/network/*.js\" \"test/broken-under-*/*.js\""
    },
    "version": "4.4.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module npm](#apidoc.module.npm)
1.  [function <span class="apidocSignatureSpan">npm.</span>access (args, cb)](#apidoc.element.npm.access)
1.  [function <span class="apidocSignatureSpan">npm.</span>build (args, global, didPre, didRB, cb)](#apidoc.element.npm.build)
1.  [function <span class="apidocSignatureSpan">npm.</span>completion (args, cb)](#apidoc.element.npm.completion)
1.  [function <span class="apidocSignatureSpan">npm.</span>deprecate (args, cb)](#apidoc.element.npm.deprecate)
1.  [function <span class="apidocSignatureSpan">npm.</span>deref (c)](#apidoc.element.npm.deref)
1.  [function <span class="apidocSignatureSpan">npm.</span>dist_tag (args, cb)](#apidoc.element.npm.dist_tag)
1.  [function <span class="apidocSignatureSpan">npm.</span>edit (args, cb)](#apidoc.element.npm.edit)
1.  [function <span class="apidocSignatureSpan">npm.</span>explore (args, cb)](#apidoc.element.npm.explore)
1.  [function <span class="apidocSignatureSpan">npm.</span>help (args, cb)](#apidoc.element.npm.help)
1.  [function <span class="apidocSignatureSpan">npm.</span>link (args, cb)](#apidoc.element.npm.link)
1.  [function <span class="apidocSignatureSpan">npm.</span>load (cli, cb_)](#apidoc.element.npm.load)
1.  [function <span class="apidocSignatureSpan">npm.</span>owner (args, cb)](#apidoc.element.npm.owner)
1.  [function <span class="apidocSignatureSpan">npm.</span>publish (args, isRetry, cb)](#apidoc.element.npm.publish)
1.  [function <span class="apidocSignatureSpan">npm.</span>rebuild (args, cb)](#apidoc.element.npm.rebuild)
1.  [function <span class="apidocSignatureSpan">npm.</span>restart (args, cb)](#apidoc.element.npm.restart)
1.  [function <span class="apidocSignatureSpan">npm.</span>run_script (args, cb)](#apidoc.element.npm.run_script)
1.  [function <span class="apidocSignatureSpan">npm.</span>search (args, cb)](#apidoc.element.npm.search)
1.  [function <span class="apidocSignatureSpan">npm.</span>star (args, cb)](#apidoc.element.npm.star)
1.  [function <span class="apidocSignatureSpan">npm.</span>start (args, cb)](#apidoc.element.npm.start)
1.  [function <span class="apidocSignatureSpan">npm.</span>stop (args, cb)](#apidoc.element.npm.stop)
1.  [function <span class="apidocSignatureSpan">npm.</span>team (args, cb)](#apidoc.element.npm.team)
1.  [function <span class="apidocSignatureSpan">npm.</span>unbuild (args, silent, cb)](#apidoc.element.npm.unbuild)
1.  [function <span class="apidocSignatureSpan">npm.</span>unpublish (args, cb)](#apidoc.element.npm.unpublish)
1.  [function <span class="apidocSignatureSpan">npm.</span>view (args, silent, cb)](#apidoc.element.npm.view)
1.  number <span class="apidocSignatureSpan">npm.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">npm.</span>_events
1.  object <span class="apidocSignatureSpan">npm.</span>commands
1.  object <span class="apidocSignatureSpan">npm.</span>config
1.  object <span class="apidocSignatureSpan">npm.</span>domain
1.  object <span class="apidocSignatureSpan">npm.</span>fullList
1.  object <span class="apidocSignatureSpan">npm.</span>limit
1.  object <span class="apidocSignatureSpan">npm.</span>rollbacks
1.  string <span class="apidocSignatureSpan">npm.</span>version

#### [module npm.access](#apidoc.module.npm.access)
1.  [function <span class="apidocSignatureSpan">npm.</span>access (args, cb)](#apidoc.element.npm.access.access)
1.  [function <span class="apidocSignatureSpan">npm.access.</span>completion (opts, cb)](#apidoc.element.npm.access.completion)
1.  object <span class="apidocSignatureSpan">npm.access.</span>subcommands
1.  string <span class="apidocSignatureSpan">npm.access.</span>usage

#### [module npm.build](#apidoc.module.npm.build)
1.  [function <span class="apidocSignatureSpan">npm.</span>build (args, global, didPre, didRB, cb)](#apidoc.element.npm.build.build)
1.  [function <span class="apidocSignatureSpan">npm.build.</span>linkStuff (pkg, folder, global, didRB, cb)](#apidoc.element.npm.build.linkStuff)
1.  [function <span class="apidocSignatureSpan">npm.build.</span>writeBuiltinConf (pkg, folder, cb)](#apidoc.element.npm.build.writeBuiltinConf)
1.  object <span class="apidocSignatureSpan">npm.build.</span>_didBuild
1.  object <span class="apidocSignatureSpan">npm.build.</span>_noLC
1.  string <span class="apidocSignatureSpan">npm.build.</span>usage

#### [module npm.completion](#apidoc.module.npm.completion)
1.  [function <span class="apidocSignatureSpan">npm.</span>completion (opts, cb)](#apidoc.element.npm.completion.completion)
1.  string <span class="apidocSignatureSpan">npm.completion.</span>usage

#### [module npm.config](#apidoc.module.npm.config)
1.  boolean <span class="apidocSignatureSpan">npm.config.</span>loaded
1.  [function <span class="apidocSignatureSpan">npm.config.</span>get ()](#apidoc.element.npm.config.get)
1.  [function <span class="apidocSignatureSpan">npm.config.</span>set ()](#apidoc.element.npm.config.set)

#### [module npm.deprecate](#apidoc.module.npm.deprecate)
1.  [function <span class="apidocSignatureSpan">npm.</span>deprecate (args, cb)](#apidoc.element.npm.deprecate.deprecate)
1.  [function <span class="apidocSignatureSpan">npm.deprecate.</span>completion (opts, cb)](#apidoc.element.npm.deprecate.completion)
1.  string <span class="apidocSignatureSpan">npm.deprecate.</span>usage

#### [module npm.dist_tag](#apidoc.module.npm.dist_tag)
1.  [function <span class="apidocSignatureSpan">npm.</span>dist_tag (args, cb)](#apidoc.element.npm.dist_tag.dist_tag)
1.  [function <span class="apidocSignatureSpan">npm.dist_tag.</span>completion (opts, cb)](#apidoc.element.npm.dist_tag.completion)
1.  string <span class="apidocSignatureSpan">npm.dist_tag.</span>usage

#### [module npm.edit](#apidoc.module.npm.edit)
1.  [function <span class="apidocSignatureSpan">npm.</span>edit (args, cb)](#apidoc.element.npm.edit.edit)
1.  [function <span class="apidocSignatureSpan">npm.edit.</span>completion (opts, filter, cb)](#apidoc.element.npm.edit.completion)
1.  string <span class="apidocSignatureSpan">npm.edit.</span>usage

#### [module npm.explore](#apidoc.module.npm.explore)
1.  [function <span class="apidocSignatureSpan">npm.</span>explore (args, cb)](#apidoc.element.npm.explore.explore)
1.  [function <span class="apidocSignatureSpan">npm.explore.</span>completion (opts, filter, cb)](#apidoc.element.npm.explore.completion)
1.  string <span class="apidocSignatureSpan">npm.explore.</span>usage

#### [module npm.help](#apidoc.module.npm.help)
1.  [function <span class="apidocSignatureSpan">npm.</span>help (args, cb)](#apidoc.element.npm.help.help)
1.  [function <span class="apidocSignatureSpan">npm.help.</span>completion (opts, cb)](#apidoc.element.npm.help.completion)

#### [module npm.link](#apidoc.module.npm.link)
1.  [function <span class="apidocSignatureSpan">npm.</span>link (args, cb)](#apidoc.element.npm.link.link)
1.  [function <span class="apidocSignatureSpan">npm.link.</span>completion (opts, cb)](#apidoc.element.npm.link.completion)
1.  string <span class="apidocSignatureSpan">npm.link.</span>usage

#### [module npm.owner](#apidoc.module.npm.owner)
1.  [function <span class="apidocSignatureSpan">npm.</span>owner (args, cb)](#apidoc.element.npm.owner.owner)
1.  [function <span class="apidocSignatureSpan">npm.owner.</span>completion (opts, cb)](#apidoc.element.npm.owner.completion)
1.  string <span class="apidocSignatureSpan">npm.owner.</span>usage

#### [module npm.publish](#apidoc.module.npm.publish)
1.  [function <span class="apidocSignatureSpan">npm.</span>publish (args, isRetry, cb)](#apidoc.element.npm.publish.publish)
1.  [function <span class="apidocSignatureSpan">npm.publish.</span>completion (opts, cb)](#apidoc.element.npm.publish.completion)
1.  string <span class="apidocSignatureSpan">npm.publish.</span>usage

#### [module npm.rebuild](#apidoc.module.npm.rebuild)
1.  [function <span class="apidocSignatureSpan">npm.</span>rebuild (args, cb)](#apidoc.element.npm.rebuild.rebuild)
1.  [function <span class="apidocSignatureSpan">npm.rebuild.</span>completion (opts, cb)](#apidoc.element.npm.rebuild.completion)
1.  string <span class="apidocSignatureSpan">npm.rebuild.</span>usage

#### [module npm.restart](#apidoc.module.npm.restart)
1.  [function <span class="apidocSignatureSpan">npm.</span>restart (args, cb)](#apidoc.element.npm.restart.restart)
1.  [function <span class="apidocSignatureSpan">npm.restart.</span>completion (opts, cb)](#apidoc.element.npm.restart.completion)
1.  string <span class="apidocSignatureSpan">npm.restart.</span>usage

#### [module npm.run_script](#apidoc.module.npm.run_script)
1.  [function <span class="apidocSignatureSpan">npm.</span>run_script (args, cb)](#apidoc.element.npm.run_script.run_script)
1.  [function <span class="apidocSignatureSpan">npm.run_script.</span>completion (opts, cb)](#apidoc.element.npm.run_script.completion)
1.  string <span class="apidocSignatureSpan">npm.run_script.</span>usage

#### [module npm.search](#apidoc.module.npm.search)
1.  [function <span class="apidocSignatureSpan">npm.</span>search (args, cb)](#apidoc.element.npm.search.search)
1.  [function <span class="apidocSignatureSpan">npm.search.</span>completion (opts, cb)](#apidoc.element.npm.search.completion)
1.  string <span class="apidocSignatureSpan">npm.search.</span>usage

#### [module npm.star](#apidoc.module.npm.star)
1.  [function <span class="apidocSignatureSpan">npm.</span>star (args, cb)](#apidoc.element.npm.star.star)
1.  [function <span class="apidocSignatureSpan">npm.star.</span>completion (opts, cb)](#apidoc.element.npm.star.completion)
1.  string <span class="apidocSignatureSpan">npm.star.</span>usage

#### [module npm.start](#apidoc.module.npm.start)
1.  [function <span class="apidocSignatureSpan">npm.</span>start (args, cb)](#apidoc.element.npm.start.start)
1.  [function <span class="apidocSignatureSpan">npm.start.</span>completion (opts, cb)](#apidoc.element.npm.start.completion)
1.  string <span class="apidocSignatureSpan">npm.start.</span>usage

#### [module npm.stop](#apidoc.module.npm.stop)
1.  [function <span class="apidocSignatureSpan">npm.</span>stop (args, cb)](#apidoc.element.npm.stop.stop)
1.  [function <span class="apidocSignatureSpan">npm.stop.</span>completion (opts, cb)](#apidoc.element.npm.stop.completion)
1.  string <span class="apidocSignatureSpan">npm.stop.</span>usage

#### [module npm.team](#apidoc.module.npm.team)
1.  [function <span class="apidocSignatureSpan">npm.</span>team (args, cb)](#apidoc.element.npm.team.team)
1.  [function <span class="apidocSignatureSpan">npm.team.</span>completion (opts, cb)](#apidoc.element.npm.team.completion)
1.  object <span class="apidocSignatureSpan">npm.team.</span>subcommands
1.  string <span class="apidocSignatureSpan">npm.team.</span>usage

#### [module npm.unbuild](#apidoc.module.npm.unbuild)
1.  [function <span class="apidocSignatureSpan">npm.</span>unbuild (args, silent, cb)](#apidoc.element.npm.unbuild.unbuild)
1.  [function <span class="apidocSignatureSpan">npm.unbuild.</span>rmStuff (pkg, folder, cb)](#apidoc.element.npm.unbuild.rmStuff)
1.  string <span class="apidocSignatureSpan">npm.unbuild.</span>usage

#### [module npm.unpublish](#apidoc.module.npm.unpublish)
1.  [function <span class="apidocSignatureSpan">npm.</span>unpublish (args, cb)](#apidoc.element.npm.unpublish.unpublish)
1.  [function <span class="apidocSignatureSpan">npm.unpublish.</span>completion (opts, cb)](#apidoc.element.npm.unpublish.completion)
1.  string <span class="apidocSignatureSpan">npm.unpublish.</span>usage

#### [module npm.view](#apidoc.module.npm.view)
1.  [function <span class="apidocSignatureSpan">npm.</span>view (args, silent, cb)](#apidoc.element.npm.view.view)
1.  [function <span class="apidocSignatureSpan">npm.view.</span>completion (opts, cb)](#apidoc.element.npm.view.completion)
1.  string <span class="apidocSignatureSpan">npm.view.</span>usage



# <a name="apidoc.module.npm"></a>[module npm](#apidoc.module.npm)

#### <a name="apidoc.element.npm.access"></a>[function <span class="apidocSignatureSpan">npm.</span>access (args, cb)](#apidoc.element.npm.access)
- description and source-code
```javascript
function access(args, cb) {
  var cmd = args.shift()
  var params
  return parseParams(cmd, args, function (err, p) {
    if (err) { return cb(err) }
    params = p
    return mapToRegistry(params.package, npm.config, invokeCmd)
  })

  function invokeCmd (err, uri, auth, base) {
    if (err) { return cb(err) }
    params.auth = auth
    try {
      return npm.registry.access(cmd, uri, params, function (err, data) {
        if (!err && data) {
          output(JSON.stringify(data, undefined, 2))
        }
        cb(err, data)
      })
    } catch (e) {
      cb(e.message + '\n\nUsage:\n' + access.usage)
    }
  }
}
```
- example usage
```shell
...
  return mapToRegistry(params.package, npm.config, invokeCmd)
})

function invokeCmd (err, uri, auth, base) {
  if (err) { return cb(err) }
  params.auth = auth
  try {
    return npm.registry.access(cmd, uri, params, function (err, data) {
      if (!err && data) {
        output(JSON.stringify(data, undefined, 2))
      }
      cb(err, data)
    })
  } catch (e) {
    cb(e.message + '\n\nUsage:\n' + access.usage)
...
```

#### <a name="apidoc.element.npm.build"></a>[function <span class="apidocSignatureSpan">npm.</span>build (args, global, didPre, didRB, cb)](#apidoc.element.npm.build)
- description and source-code
```javascript
function build(args, global, didPre, didRB, cb) {
  if (typeof cb !== 'function') {
    cb = didRB
    didRB = false
  }
  if (typeof cb !== 'function') {
    cb = didPre
    didPre = false
  }
  if (typeof cb !== 'function') {
    cb = global
    global = npm.config.get('global')
  }

  // it'd be nice to asyncMap these, but actually, doing them
  // in parallel generally munges up the output from node-waf
  var builder = build_(global, didPre, didRB)
  chain(args.map(function (arg) {
    return function (cb) {
      builder(arg, cb)
    }
  }), cb)
}
```
- example usage
```shell
...
    if (!folders.length) return cb()
    log.silly('rebuild set', folders)
    cleanBuild(folders, set, cb)
  })
}

function cleanBuild (folders, set, cb) {
  npm.commands.build(folders, function (er) {
    if (er) return cb(er)
    output(folders.map(function (f) {
      return set[f] + ' ' + f
    }).join('\n'))
    cb()
  })
}
...
```

#### <a name="apidoc.element.npm.completion"></a>[function <span class="apidocSignatureSpan">npm.</span>completion (args, cb)](#apidoc.element.npm.completion)
- description and source-code
```javascript
function completion(args, cb) {
  if (isWindowsShell) {
    var e = new Error('npm completion supported only in MINGW / Git bash on Windows')
    e.code = 'ENOTSUP'
    e.errno = require('constants').ENOTSUP
    return cb(e)
  }

  // if the COMP_* isn't in the env, then just dump the script.
  if (process.env.COMP_CWORD === undefined ||
      process.env.COMP_LINE === undefined ||
      process.env.COMP_POINT === undefined) {
    return dumpScript(cb)
  }

  console.error(process.env.COMP_CWORD)
  console.error(process.env.COMP_LINE)
  console.error(process.env.COMP_POINT)

  // get the partial line and partial word,
  // if the point isn't at the end.
  // ie, tabbing at: npm foo b|ar
  var w = +process.env.COMP_CWORD
  var words = args.map(unescape)
  var word = words[w]
  var line = process.env.COMP_LINE
  var point = +process.env.COMP_POINT
  var partialLine = line.substr(0, point)
  var partialWords = words.slice(0, w)

  // figure out where in that last word the point is.
  var partialWord = args[w]
  var i = partialWord.length
  while (partialWord.substr(0, i) !== partialLine.substr(-1 * i) && i > 0) {
    i--
  }
  partialWord = unescape(partialWord.substr(0, i))
  partialWords.push(partialWord)

  var opts = {
    words: words,
    w: w,
    word: word,
    line: line,
    lineLength: line.length,
    point: point,
    partialLine: partialLine,
    partialWords: partialWords,
    partialWord: partialWord,
    raw: args
  }

  cb = wrapCb(cb, opts)

  console.error(opts)

  if (partialWords.slice(0, -1).indexOf('--') === -1) {
    if (word.charAt(0) === '-') return configCompl(opts, cb)
    if (words[w - 1] &&
        words[w - 1].charAt(0) === '-' &&
        !isFlag(words[w - 1])) {
      // awaiting a value for a non-bool config.
      // don't even try to do this for now
      console.error('configValueCompl')
      return configValueCompl(opts, cb)
    }
  }

  // try to find the npm command.
  // it's the first thing after all the configs.
  // take a little shortcut and use npm's arg parsing logic.
  // don't have to worry about the last arg being implicitly
  // boolean'ed, since the last block will catch that.
  var parsed = opts.conf =
    nopt(configTypes, shorthands, partialWords.slice(0, -1), 0)
  // check if there's a command already.
  console.error(parsed)
  var cmd = parsed.argv.remain[1]
  if (!cmd) return cmdCompl(opts, cb)

  Object.keys(parsed).forEach(function (k) {
    npm.config.set(k, parsed[k])
  })

  // at this point, if words[1] is some kind of npm command,
  // then complete on it.
  // otherwise, do nothing
  cmd = npm.commands[cmd]
  if (cmd && cmd.completion) return cmd.completion(opts, cb)

  // nothing to do.
  cb()
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```

#### <a name="apidoc.element.npm.deprecate"></a>[function <span class="apidocSignatureSpan">npm.</span>deprecate (args, cb)](#apidoc.element.npm.deprecate)
- description and source-code
```javascript
function deprecate(args, cb) {
  var pkg = args[0]
  var msg = args[1]
  if (msg === undefined) return cb('Usage: ' + deprecate.usage)

  // fetch the data and make sure it exists.
  var p = npa(pkg)

  // npa makes the default spec "latest", but for deprecation
  // "*" is the appropriate default.
  if (p.rawSpec === '') p.spec = '*'

  mapToRegistry(p.name, npm.config, function (er, uri, auth) {
    if (er) return cb(er)

    var params = {
      version: p.spec,
      message: msg,
      auth: auth
    }
    npm.registry.deprecate(uri, params, cb)
  })
}
```
- example usage
```shell
...
    if (er) return cb(er)

    var params = {
      version: p.spec,
      message: msg,
      auth: auth
    }
    npm.registry.deprecate(uri, params, cb)
  })
}
...
```

#### <a name="apidoc.element.npm.deref"></a>[function <span class="apidocSignatureSpan">npm.</span>deref (c)](#apidoc.element.npm.deref)
- description and source-code
```javascript
deref = function (c) {
  if (!c) return ''
  if (c.match(/[A-Z]/)) {
    c = c.replace(/([A-Z])/g, function (m) {
      return '-' + m.toLowerCase()
    })
  }
  if (plumbing.indexOf(c) !== -1) return c
  var a = abbrevs[c]
  if (aliases[a]) a = aliases[a]
  return a
}
```
- example usage
```shell
...
}

// npm help foo bar baz: search topics
if (args.length > 1 && args[0]) {
  return npm.commands['help-search'](args, argnum, cb)
}

var section = npm.deref(args[0]) || args[0]

// npm help <noargs>:  show basic usage
if (!section) {
  var valid = argv[0] === 'help' ? 0 : 1
  return npmUsage(valid, cb)
}
...
```

#### <a name="apidoc.element.npm.dist_tag"></a>[function <span class="apidocSignatureSpan">npm.</span>dist_tag (args, cb)](#apidoc.element.npm.dist_tag)
- description and source-code
```javascript
function distTag(args, cb) {
  var cmd = args.shift()
  switch (cmd) {
    case 'add': case 'a': case 'set': case 's':
      return add(args[0], args[1], cb)
    case 'rm': case 'r': case 'del': case 'd': case 'remove':
      return remove(args[1], args[0], cb)
    case 'ls': case 'l': case 'sl': case 'list':
      return list(args[0], cb)
    default:
      return cb('Usage:\n' + distTag.usage)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.edit"></a>[function <span class="apidocSignatureSpan">npm.</span>edit (args, cb)](#apidoc.element.npm.edit)
- description and source-code
```javascript
function edit(args, cb) {
  var p = args[0]
  if (args.length !== 1 || !p) return cb(edit.usage)
  var e = npm.config.get('editor')
  if (!e) {
    return cb(new Error(
      "No editor set.  Set the 'editor' config, or $EDITOR environ."
    ))
  }
  p = p.split('/')
       .join('/node_modules/')
       .replace(/(\/node_modules)+/, '/node_modules')
  var f = path.resolve(npm.dir, p)
  fs.lstat(f, function (er) {
    if (er) return cb(er)
    editor(f, { editor: e }, noProgressTillDone(function (er) {
      if (er) return cb(er)
      npm.commands.rebuild(args, cb)
    }))
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.explore"></a>[function <span class="apidocSignatureSpan">npm.</span>explore (args, cb)](#apidoc.element.npm.explore)
- description and source-code
```javascript
function explore(args, cb) {
  if (args.length < 1 || !args[0]) return cb(explore.usage)
  var p = args.shift()

  var cwd = path.resolve(npm.dir, p)
  var opts = {cwd: cwd, stdio: 'inherit'}

  var shellArgs = []
  if (args) {
    if (isWindowsShell) {
      var execCmd = escapeExecPath(args.shift())
      var execArgs = [execCmd].concat(args.map(escapeArg))
      opts.windowsVerbatimArguments = true
      shellArgs = ['/d', '/s', '/c'].concat(execArgs)
    } else {
      shellArgs.unshift('-c')
      shellArgs = ['-c', args.map(escapeArg).join(' ').trim()]
    }
  }

  var sh = npm.config.get('shell')
  fs.stat(cwd, function (er, s) {
    if (er || !s.isDirectory()) {
      return cb(new Error(
        "It doesn't look like " + p + ' is installed.'
      ))
    }

    if (!shellArgs.length) {
      output(
        '\nExploring ' + cwd + '\n' +
          "Type 'exit' or ^D when finished\n"
      )
    }

    var shell = spawn(sh, shellArgs, opts)
    shell.on('close', function (er) {
      // only fail if non-interactive.
      if (!shellArgs.length) return cb()
      cb(er)
    })
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.help"></a>[function <span class="apidocSignatureSpan">npm.</span>help (args, cb)](#apidoc.element.npm.help)
- description and source-code
```javascript
function help(args, cb) {
  var argv = npm.config.get('argv').cooked

  var argnum = 0
  if (args.length === 2 && ~~args[0]) {
    argnum = ~~args.shift()
  }

  // npm help foo bar baz: search topics
  if (args.length > 1 && args[0]) {
    return npm.commands['help-search'](args, argnum, cb)
  }

  var section = npm.deref(args[0]) || args[0]

  // npm help <noargs>:  show basic usage
  if (!section) {
    var valid = argv[0] === 'help' ? 0 : 1
    return npmUsage(valid, cb)
  }

  // npm <cmd> -h: show command usage
  if (npm.config.get('usage') &&
      npm.commands[section] &&
      npm.commands[section].usage) {
    npm.config.set('loglevel', 'silent')
    log.level = 'silent'
    output(npm.commands[section].usage)
    return cb()
  }

  // npm apihelp <section>: Prefer section 3 over section 1
  var apihelp = argv.length && argv[0].indexOf('api') !== -1
  var pref = apihelp ? [3, 1, 5, 7] : [1, 3, 5, 7]
  if (argnum) {
    pref = [ argnum ].concat(pref.filter(function (n) {
      return n !== argnum
    }))
  }

  // npm help <section>: Try to find the path
  var manroot = path.resolve(__dirname, '..', 'man')

  // legacy
  if (section === 'global') section = 'folders'
  else if (section === 'json') section = 'package.json'

  // find either /section.n or /npm-section.n
  // The glob is used in the glob.  The regexp is used much
  // further down.  Globs and regexps are different
  var compextglob = '.+(gz|bz2|lzma|[FYzZ]|xz)'
  var compextre = '\\.(gz|bz2|lzma|[FYzZ]|xz)$'
  var f = '+(npm-' + section + '|' + section + ').[0-9]?(' + compextglob + ')'
  return glob(manroot + '/*/' + f, function (er, mans) {
    if (er) return cb(er)

    if (!mans.length) return npm.commands['help-search'](args, cb)

    mans = mans.map(function (man) {
      var ext = path.extname(man)
      if (man.match(new RegExp(compextre))) man = path.basename(man, ext)

      return man
    })

    viewMan(pickMan(mans, pref), cb)
  })
}
```
- example usage
```shell
...
    hits: found,
    totalHits: totalHits
  })
})

// if only one result, then just show that help section.
if (results.length === 1) {
  return npm.commands.help([results[0].file.replace(/\.md$/, '')], cb)
}

if (results.length === 0) {
  output('No results for ' + args.map(JSON.stringify).join(' '))
  return cb()
}
...
```

#### <a name="apidoc.element.npm.link"></a>[function <span class="apidocSignatureSpan">npm.</span>link (args, cb)](#apidoc.element.npm.link)
- description and source-code
```javascript
function link(args, cb) {
  if (process.platform === 'win32') {
    var semver = require('semver')
    if (!semver.gte(process.version, '0.7.9')) {
      var msg = 'npm link not supported on windows prior to node 0.7.9'
      var e = new Error(msg)
      e.code = 'ENOTSUP'
      e.errno = require('constants').ENOTSUP
      return cb(e)
    }
  }

  if (npm.config.get('global')) {
    return cb(new Error(
      'link should never be --global.\n' +
      'Please re-run this command with --local'
    ))
  }

  if (args.length === 1 && args[0] === '.') args = []
  if (args.length) return linkInstall(args, cb)
  linkPkg(npm.prefix, cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.load"></a>[function <span class="apidocSignatureSpan">npm.</span>load (cli, cb_)](#apidoc.element.npm.load)
- description and source-code
```javascript
load = function (cli, cb_) {
  if (!cb_ && typeof cli === 'function') {
    cb_ = cli
    cli = {}
  }
  if (!cb_) cb_ = function () {}
  if (!cli) cli = {}
  loadListeners.push(cb_)
  if (loaded || loadErr) return cb(loadErr)
  if (loading) return
  loading = true
  var onload = true

  function cb (er) {
    if (loadErr) return
    loadErr = er
    if (er) return cb_(er)
    if (npm.config.get('force')) {
      log.warn('using --force', 'I sure hope you know what you are doing.')
    }
    npm.config.loaded = true
    loaded = true
    loadCb(loadErr = er)
    onload = onload && npm.config.get('onload-script')
    if (onload) {
      try {
        require(onload)
      } catch (err) {
        log.warn('onload-script', 'failed to require onload script', onload)
        log.warn('onload-script', err)
      }
      onload = false
    }
  }

  log.pause()

  load(npm, cli, cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.owner"></a>[function <span class="apidocSignatureSpan">npm.</span>owner (args, cb)](#apidoc.element.npm.owner)
- description and source-code
```javascript
function owner(args, cb) {
  var action = args.shift()
  switch (action) {
    case 'ls': case 'list': return ls(args[0], cb)
    case 'add': return add(args[0], args[1], cb)
    case 'rm': case 'remove': return rm(args[0], args[1], cb)
    default: return unknown(action, cb)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.publish"></a>[function <span class="apidocSignatureSpan">npm.</span>publish (args, isRetry, cb)](#apidoc.element.npm.publish)
- description and source-code
```javascript
function publish(args, isRetry, cb) {
  if (typeof cb !== 'function') {
    cb = isRetry
    isRetry = false
  }
  if (args.length === 0) args = ['.']
  if (args.length !== 1) return cb(publish.usage)

  log.verbose('publish', args)

  var t = npm.config.get('tag').trim()
  if (semver.validRange(t)) {
    var er = new Error('Tag name must not be a valid SemVer range: ' + t)
    return cb(er)
  }

  var arg = args[0]
  // if it's a local folder, then run the prepublish there, first.
  readJson(path.resolve(arg, 'package.json'), function (er, data) {
    if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)

    if (data) {
      if (!data.name) return cb(new Error('No name provided'))
      if (!data.version) return cb(new Error('No version provided'))
    }

    // if readJson errors, the argument might be a tarball or package URL
    if (er) {
      npm.commands.cache.add(arg, null, null, false, function (er, data) {
        if (er) return cb(er)
        log.silly('publish', data)
        var cached = path.resolve(cachedPackageRoot(data), 'package') + '.tgz'
        // *publish* lifecycle scripts aren't run when publishing a built artifact
        // go to the next step directly
        publish_(arg, data, isRetry, cached, cb)
      })
    } else {
      var dir = arg
      npm.commands.cache.add(dir, null, null, false, function (er, data) {
        if (er) return cb(er)
        log.silly('publish', data)
        var cached = path.resolve(cachedPackageRoot(data), 'package') + '.tgz'
        // 'prepublish' and 'prepare' are run by cache.add
        chain(
          [
            [lifecycle, data, 'prepublishOnly', dir],
            [publish_, dir, data, isRetry, cached],
            [lifecycle, data, 'publish', dir],
            [lifecycle, data, 'postpublish', dir]
          ],
          cb
        )
      })
    }
  })
}
```
- example usage
```shell
...
    return cb(new Error("Can't restrict access to unscoped packages."))
  }

  params.access = config.get('access')
}

log.showProgress('publish:' + data._id)
registry.publish(registryBase, params, function (er) {
  if (er && er.code === 'EPUBLISHCONFLICT' &&
      npm.config.get('force') && !isRetry) {
    log.warn('publish', 'Forced publish over ' + data._id)
    return npm.commands.unpublish([data._id], function (er) {
      // ignore errors.  Use the force.  Reach out with your feelings.
      // but if it fails again, then report the first error.
      publish([arg], er || true, cb)
...
```

#### <a name="apidoc.element.npm.rebuild"></a>[function <span class="apidocSignatureSpan">npm.</span>rebuild (args, cb)](#apidoc.element.npm.rebuild)
- description and source-code
```javascript
function rebuild(args, cb) {
  var opt = { depth: npm.config.get('depth'), dev: true }
  readInstalled(npm.prefix, opt, function (er, data) {
    log.info('readInstalled', typeof data)
    if (er) return cb(er)
    var set = filter(data, args)
    var folders = Object.keys(set).filter(function (f) {
      return f !== npm.prefix
    })
    if (!folders.length) return cb()
    log.silly('rebuild set', folders)
    cleanBuild(folders, set, cb)
  })
}
```
- example usage
```shell
...
       .join('/node_modules/')
       .replace(/(\/node_modules)+/, '/node_modules')
  var f = path.resolve(npm.dir, p)
  fs.lstat(f, function (er) {
    if (er) return cb(er)
    editor(f, { editor: e }, noProgressTillDone(function (er) {
      if (er) return cb(er)
      npm.commands.rebuild(args, cb)
    }))
  })
}
...
```

#### <a name="apidoc.element.npm.restart"></a>[function <span class="apidocSignatureSpan">npm.</span>restart (args, cb)](#apidoc.element.npm.restart)
- description and source-code
```javascript
function CMD(args, cb) {
  npm.commands['run-script']([stage].concat(args), cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.run_script"></a>[function <span class="apidocSignatureSpan">npm.</span>run_script (args, cb)](#apidoc.element.npm.run_script)
- description and source-code
```javascript
function runScript(args, cb) {
  if (!args.length) return list(cb)

  var pkgdir = npm.localPrefix
  var cmd = args.shift()

  readJson(path.resolve(pkgdir, 'package.json'), function (er, d) {
    if (er) return cb(er)
    run(d, pkgdir, cmd, args, cb)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.search"></a>[function <span class="apidocSignatureSpan">npm.</span>search (args, cb)](#apidoc.element.npm.search)
- description and source-code
```javascript
function search(args, cb) {
  var searchOpts = {
    description: npm.config.get('description'),
    exclude: prepareExcludes(npm.config.get('searchexclude')),
    include: prepareIncludes(args, npm.config.get('searchopts')),
    limit: npm.config.get('searchlimit'),
    log: log,
    staleness: npm.config.get('searchstaleness'),
    unicode: npm.config.get('unicode')
  }

  if (searchOpts.include.length === 0) {
    return cb(new Error('search must be called with arguments'))
  }

  // Used later to figure out whether we had any packages go out
  var anyOutput = false

  var entriesStream = ms.through.obj()

  var esearchWritten = false
  esearch(searchOpts).on('data', function (pkg) {
    entriesStream.write(pkg)
    !esearchWritten && (esearchWritten = true)
  }).on('error', function (e) {
    if (esearchWritten) {
      // If esearch errored after already starting output, we can't fall back.
      return entriesStream.emit('error', e)
    }
    log.warn('search', 'fast search endpoint errored. Using old search.')
    allPackageSearch(searchOpts).on('data', function (pkg) {
      entriesStream.write(pkg)
    }).on('error', function (e) {
      entriesStream.emit('error', e)
    }).on('end', function () {
      entriesStream.end()
    })
  }).on('end', function () {
    entriesStream.end()
  })

  // Grab a configured output stream that will spit out packages in the
  // desired format.
  var outputStream = formatPackageStream({
    args: args, // --searchinclude options are not highlighted
    long: npm.config.get('long'),
    description: npm.config.get('description'),
    json: npm.config.get('json'),
    parseable: npm.config.get('parseable'),
    color: npm.color
  })
  outputStream.on('data', function (chunk) {
    if (!anyOutput) { anyOutput = true }
    output(chunk.toString('utf8'))
  })

  log.silly('search', 'searching packages')
  ms.pipe(entriesStream, outputStream, function (er) {
    if (er) return cb(er)
    if (!anyOutput && !npm.config.get('json') && !npm.config.get('parseable')) {
      output('No matches found for ' + (args.map(JSON.stringify).join(' ')))
    }
    log.silly('search', 'search completed')
    log.clearProgress()
    cb(null, {})
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.star"></a>[function <span class="apidocSignatureSpan">npm.</span>star (args, cb)](#apidoc.element.npm.star)
- description and source-code
```javascript
function star(args, cb) {
  if (!args.length) return cb(star.usage)
  var s = npm.config.get('unicode') ? '\u2605 ' : '(*)'
  var u = npm.config.get('unicode') ? '\u2606 ' : '( )'
  var using = !(npm.command.match(/^un/))
  if (!using) s = u
  asyncMap(args, function (pkg, cb) {
    mapToRegistry(pkg, npm.config, function (er, uri, auth) {
      if (er) return cb(er)

      var params = {
        starred: using,
        auth: auth
      }
      npm.registry.star(uri, params, function (er, data, raw, req) {
        if (!er) {
          output(s + ' ' + pkg)
          log.verbose('star', data)
        }
        cb(er, data, raw, req)
      })
    })
  }, cb)
}
```
- example usage
```shell
...
mapToRegistry(pkg, npm.config, function (er, uri, auth) {
  if (er) return cb(er)

  var params = {
    starred: using,
    auth: auth
  }
  npm.registry.star(uri, params, function (er, data, raw, req) {
    if (!er) {
      output(s + ' ' + pkg)
      log.verbose('star', data)
    }
    cb(er, data, raw, req)
  })
})
...
```

#### <a name="apidoc.element.npm.start"></a>[function <span class="apidocSignatureSpan">npm.</span>start (args, cb)](#apidoc.element.npm.start)
- description and source-code
```javascript
function CMD(args, cb) {
  npm.commands['run-script']([stage].concat(args), cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.stop"></a>[function <span class="apidocSignatureSpan">npm.</span>stop (args, cb)](#apidoc.element.npm.stop)
- description and source-code
```javascript
function CMD(args, cb) {
  npm.commands['run-script']([stage].concat(args), cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.team"></a>[function <span class="apidocSignatureSpan">npm.</span>team (args, cb)](#apidoc.element.npm.team)
- description and source-code
```javascript
function team(args, cb) {
  // Entities are in the format <scope>:<team>
  var cmd = args.shift()
  var entity = (args.shift() || '').split(':')
  return mapToRegistry('/', npm.config, function (err, uri, auth) {
    if (err) { return cb(err) }
    try {
      return npm.registry.team(cmd, uri, {
        auth: auth,
        scope: entity[0],
        team: entity[1],
        user: args.shift()
      }, function (err, data) {
        !err && data && output(JSON.stringify(data, undefined, 2))
        cb(err, data)
      })
    } catch (e) {
      cb(e.message + '\n\nUsage:\n' + team.usage)
    }
  })
}
```
- example usage
```shell
...
function team (args, cb) {
// Entities are in the format <scope>:<team>
var cmd = args.shift()
var entity = (args.shift() || '').split(':')
return mapToRegistry('/', npm.config, function (err, uri, auth) {
  if (err) { return cb(err) }
  try {
    return npm.registry.team(cmd, uri, {
      auth: auth,
      scope: entity[0],
      team: entity[1],
      user: args.shift()
    }, function (err, data) {
      !err && data && output(JSON.stringify(data, undefined, 2))
      cb(err, data)
...
```

#### <a name="apidoc.element.npm.unbuild"></a>[function <span class="apidocSignatureSpan">npm.</span>unbuild (args, silent, cb)](#apidoc.element.npm.unbuild)
- description and source-code
```javascript
function unbuild(args, silent, cb) {
  if (typeof silent === 'function') {
    cb = silent
    silent = false
  }
  asyncMap(args, unbuild_(silent), cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.unpublish"></a>[function <span class="apidocSignatureSpan">npm.</span>unpublish (args, cb)](#apidoc.element.npm.unpublish)
- description and source-code
```javascript
function unpublish(args, cb) {
  if (args.length > 1) return cb(unpublish.usage)

  var thing = args.length ? npa(args[0]) : {}
  var project = thing.name
  var version = thing.rawSpec

  log.silly('unpublish', 'args[0]', args[0])
  log.silly('unpublish', 'thing', thing)
  if (!version && !npm.config.get('force')) {
    return cb(
      'Refusing to delete entire project.\n' +
      'Run with --force to do this.\n' +
      unpublish.usage
    )
  }

  if (!project || path.resolve(project) === npm.localPrefix) {
    // if there's a package.json in the current folder, then
    // read the package name and version out of that.
    var cwdJson = path.join(npm.localPrefix, 'package.json')
    return readJson(cwdJson, function (er, data) {
      if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)
      if (er) return cb('Usage:\n' + unpublish.usage)
      log.verbose('unpublish', data)
      gotProject(data.name, data.version, data.publishConfig, cb)
    })
  }
  return gotProject(project, version, cb)
}
```
- example usage
```shell
...
}

log.showProgress('publish:' + data._id)
registry.publish(registryBase, params, function (er) {
  if (er && er.code === 'EPUBLISHCONFLICT' &&
      npm.config.get('force') && !isRetry) {
    log.warn('publish', 'Forced publish over ' + data._id)
    return npm.commands.unpublish([data._id], function (er) {
      // ignore errors.  Use the force.  Reach out with your feelings.
      // but if it fails again, then report the first error.
      publish([arg], er || true, cb)
    })
  }
  // report the unpublish error if this was a retry and unpublish failed
  if (er && isRetry && isRetry !== true) return cb(isRetry)
...
```

#### <a name="apidoc.element.npm.view"></a>[function <span class="apidocSignatureSpan">npm.</span>view (args, silent, cb)](#apidoc.element.npm.view)
- description and source-code
```javascript
function view(args, silent, cb) {
  if (typeof cb !== 'function') {
    cb = silent
    silent = false
  }

  if (!args.length) args = ['.']

  var pkg = args.shift()
  var nv = npa(pkg)
  var name = nv.name
  var local = (name === '.' || !name)

  if (npm.config.get('global') && local) {
    return cb(new Error('Cannot use view command in global mode.'))
  }

  if (local) {
    var dir = npm.prefix
    readJson(path.resolve(dir, 'package.json'), function (er, d) {
      d = d || {}
      if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)
      if (!d.name) return cb(new Error('Invalid package.json'))

      var p = d.name
      nv = npa(p)
      if (pkg && ~pkg.indexOf('@')) {
        nv.rawSpec = pkg.split('@')[pkg.indexOf('@')]
      }

      fetchAndRead(nv, args, silent, cb)
    })
  } else {
    fetchAndRead(nv, args, silent, cb)
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.npm.access"></a>[module npm.access](#apidoc.module.npm.access)

#### <a name="apidoc.element.npm.access.access"></a>[function <span class="apidocSignatureSpan">npm.</span>access (args, cb)](#apidoc.element.npm.access.access)
- description and source-code
```javascript
function access(args, cb) {
  var cmd = args.shift()
  var params
  return parseParams(cmd, args, function (err, p) {
    if (err) { return cb(err) }
    params = p
    return mapToRegistry(params.package, npm.config, invokeCmd)
  })

  function invokeCmd (err, uri, auth, base) {
    if (err) { return cb(err) }
    params.auth = auth
    try {
      return npm.registry.access(cmd, uri, params, function (err, data) {
        if (!err && data) {
          output(JSON.stringify(data, undefined, 2))
        }
        cb(err, data)
      })
    } catch (e) {
      cb(e.message + '\n\nUsage:\n' + access.usage)
    }
  }
}
```
- example usage
```shell
...
  return mapToRegistry(params.package, npm.config, invokeCmd)
})

function invokeCmd (err, uri, auth, base) {
  if (err) { return cb(err) }
  params.auth = auth
  try {
    return npm.registry.access(cmd, uri, params, function (err, data) {
      if (!err && data) {
        output(JSON.stringify(data, undefined, 2))
      }
      cb(err, data)
    })
  } catch (e) {
    cb(e.message + '\n\nUsage:\n' + access.usage)
...
```

#### <a name="apidoc.element.npm.access.completion"></a>[function <span class="apidocSignatureSpan">npm.access.</span>completion (opts, cb)](#apidoc.element.npm.access.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  var argv = opts.conf.argv.remain
  if (argv.length === 2) {
    return cb(null, access.subcommands)
  }

  switch (argv[2]) {
    case 'grant':
      if (argv.length === 3) {
        return cb(null, ['read-only', 'read-write'])
      } else {
        return cb(null, [])
      }
    case 'public':
    case 'restricted':
    case 'ls-packages':
    case 'ls-collaborators':
    case 'edit':
      return cb(null, [])
    case 'revoke':
      return cb(null, [])
    default:
      return cb(new Error(argv[2] + ' not recognized'))
  }
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.build"></a>[module npm.build](#apidoc.module.npm.build)

#### <a name="apidoc.element.npm.build.build"></a>[function <span class="apidocSignatureSpan">npm.</span>build (args, global, didPre, didRB, cb)](#apidoc.element.npm.build.build)
- description and source-code
```javascript
function build(args, global, didPre, didRB, cb) {
  if (typeof cb !== 'function') {
    cb = didRB
    didRB = false
  }
  if (typeof cb !== 'function') {
    cb = didPre
    didPre = false
  }
  if (typeof cb !== 'function') {
    cb = global
    global = npm.config.get('global')
  }

  // it'd be nice to asyncMap these, but actually, doing them
  // in parallel generally munges up the output from node-waf
  var builder = build_(global, didPre, didRB)
  chain(args.map(function (arg) {
    return function (cb) {
      builder(arg, cb)
    }
  }), cb)
}
```
- example usage
```shell
...
    if (!folders.length) return cb()
    log.silly('rebuild set', folders)
    cleanBuild(folders, set, cb)
  })
}

function cleanBuild (folders, set, cb) {
  npm.commands.build(folders, function (er) {
    if (er) return cb(er)
    output(folders.map(function (f) {
      return set[f] + ' ' + f
    }).join('\n'))
    cb()
  })
}
...
```

#### <a name="apidoc.element.npm.build.linkStuff"></a>[function <span class="apidocSignatureSpan">npm.build.</span>linkStuff (pkg, folder, global, didRB, cb)](#apidoc.element.npm.build.linkStuff)
- description and source-code
```javascript
linkStuff = function (pkg, folder, global, didRB, cb) {
  // allow to opt out of linking binaries.
  if (npm.config.get('bin-links') === false) return cb()

  // if it's global, and folder is in {prefix}/node_modules,
  // then bins are in {prefix}/bin
  // otherwise, then bins are in folder/../.bin
  var parent = pkg.name && pkg.name[0] === '@' ? path.dirname(path.dirname(folder)) : path.dirname(folder)
  var gnm = global && npm.globalDir
  var gtop = parent === gnm

  log.info('linkStuff', packageId(pkg))
  log.silly('linkStuff', packageId(pkg), 'has', parent, 'as its parent node_modules')
  if (global) log.silly('linkStuff', packageId(pkg), 'is part of a global install')
  if (gnm) log.silly('linkStuff', packageId(pkg), 'is installed into a global node_modules')
  if (gtop) log.silly('linkStuff', packageId(pkg), 'is installed into the top-level global node_modules')

  shouldWarn(pkg, folder, global, function () {
    asyncMap(
      [linkBins, linkMans, !didRB && rebuildBundles],
      function (fn, cb) {
        if (!fn) return cb()
        log.verbose(fn.name, packageId(pkg))
        fn(pkg, folder, parent, gtop, cb)
      },
      cb
    )
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.build.writeBuiltinConf"></a>[function <span class="apidocSignatureSpan">npm.build.</span>writeBuiltinConf (pkg, folder, cb)](#apidoc.element.npm.build.writeBuiltinConf)
- description and source-code
```javascript
writeBuiltinConf = function (pkg, folder, cb) {
  // the builtin config is "sticky". Any time npm installs
  // itself globally, it puts its builtin config file there
  var parent = path.dirname(folder)
  var dir = npm.globalDir

  if (pkg.name !== 'npm' ||
      !npm.config.get('global') ||
      !npm.config.usingBuiltin ||
      dir !== parent) {
    return cb()
  }

  var data = ini.stringify(npm.config.sources.builtin.data)
  writeFile(path.resolve(folder, 'npmrc'), data, cb)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.npm.completion"></a>[module npm.completion](#apidoc.module.npm.completion)

#### <a name="apidoc.element.npm.completion.completion"></a>[function <span class="apidocSignatureSpan">npm.</span>completion (opts, cb)](#apidoc.element.npm.completion.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  if (opts.w > 3) return cb()

  var fs = require('graceful-fs')
  var path = require('path')
  var bashExists = null
  var zshExists = null
  fs.stat(path.resolve(process.env.HOME, '.bashrc'), function (er) {
    bashExists = !er
    next()
  })
  fs.stat(path.resolve(process.env.HOME, '.zshrc'), function (er) {
    zshExists = !er
    next()
  })
  function next () {
    if (zshExists === null || bashExists === null) return
    var out = []
    if (zshExists) out.push('~/.zshrc')
    if (bashExists) out.push('~/.bashrc')
    if (opts.w === 2) {
      out = out.map(function (m) {
        return ['>>', m]
      })
    }
    cb(null, out)
  }
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.config"></a>[module npm.config](#apidoc.module.npm.config)

#### <a name="apidoc.element.npm.config.get"></a>[function <span class="apidocSignatureSpan">npm.config.</span>get ()](#apidoc.element.npm.config.get)
- description and source-code
```javascript
get = function () {
  throw new Error('npm.load() required')
}
```
- example usage
```shell
...
function adduser (args, cb) {
if (!crypto) {
  return cb(new Error(
  'You must compile node with ssl support to use the adduser feature'
  ))
}

var registry = npm.config.get('registry')
var scope = npm.config.get('scope')
var creds = npm.config.getCredentialsByURI(npm.config.get('registry'))

if (scope) {
  var scopedRegistry = npm.config.get(scope + ':registry')
  var cliRegistry = npm.config.get('registry', 'cli')
  if (scopedRegistry && !cliRegistry) registry = scopedRegistry
...
```

#### <a name="apidoc.element.npm.config.set"></a>[function <span class="apidocSignatureSpan">npm.config.</span>set ()](#apidoc.element.npm.config.set)
- description and source-code
```javascript
set = function () {
  throw new Error('npm.load() required')
}
```
- example usage
```shell
...
  } catch (e) {
    return cb(new Error('no such auth module'))
  }
  auth.login(creds, registry, scope, function (err, newCreds) {
    if (err) return cb(err)

    npm.config.del('_token', 'user') // prevent legacy pollution
    if (scope) npm.config.set(scope + ':registry', registry, 'user')
    npm.config.setCredentialsByURI(registry, newCreds)
    npm.config.save('user', cb)
  })
}
...
```



# <a name="apidoc.module.npm.deprecate"></a>[module npm.deprecate](#apidoc.module.npm.deprecate)

#### <a name="apidoc.element.npm.deprecate.deprecate"></a>[function <span class="apidocSignatureSpan">npm.</span>deprecate (args, cb)](#apidoc.element.npm.deprecate.deprecate)
- description and source-code
```javascript
function deprecate(args, cb) {
  var pkg = args[0]
  var msg = args[1]
  if (msg === undefined) return cb('Usage: ' + deprecate.usage)

  // fetch the data and make sure it exists.
  var p = npa(pkg)

  // npa makes the default spec "latest", but for deprecation
  // "*" is the appropriate default.
  if (p.rawSpec === '') p.spec = '*'

  mapToRegistry(p.name, npm.config, function (er, uri, auth) {
    if (er) return cb(er)

    var params = {
      version: p.spec,
      message: msg,
      auth: auth
    }
    npm.registry.deprecate(uri, params, cb)
  })
}
```
- example usage
```shell
...
    if (er) return cb(er)

    var params = {
      version: p.spec,
      message: msg,
      auth: auth
    }
    npm.registry.deprecate(uri, params, cb)
  })
}
...
```

#### <a name="apidoc.element.npm.deprecate.completion"></a>[function <span class="apidocSignatureSpan">npm.deprecate.</span>completion (opts, cb)](#apidoc.element.npm.deprecate.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  // first, get a list of remote packages this user owns.
  // once we have a user account, then don't complete anything.
  if (opts.conf.argv.remain.length > 2) return cb()
  // get the list of packages by user
  var path = '/-/by-user/'
  mapToRegistry(path, npm.config, function (er, uri, c) {
    if (er) return cb(er)

    if (!(c && c.username)) return cb()

    var params = {
      timeout: 60000,
      auth: c
    }
    npm.registry.get(uri + c.username, params, function (er, list) {
      if (er) return cb()
      console.error(list)
      return cb(null, list[c.username])
    })
  })
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.dist_tag"></a>[module npm.dist_tag](#apidoc.module.npm.dist_tag)

#### <a name="apidoc.element.npm.dist_tag.dist_tag"></a>[function <span class="apidocSignatureSpan">npm.</span>dist_tag (args, cb)](#apidoc.element.npm.dist_tag.dist_tag)
- description and source-code
```javascript
function distTag(args, cb) {
  var cmd = args.shift()
  switch (cmd) {
    case 'add': case 'a': case 'set': case 's':
      return add(args[0], args[1], cb)
    case 'rm': case 'r': case 'del': case 'd': case 'remove':
      return remove(args[1], args[0], cb)
    case 'ls': case 'l': case 'sl': case 'list':
      return list(args[0], cb)
    default:
      return cb('Usage:\n' + distTag.usage)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.dist_tag.completion"></a>[function <span class="apidocSignatureSpan">npm.dist_tag.</span>completion (opts, cb)](#apidoc.element.npm.dist_tag.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  var argv = opts.conf.argv.remain
  if (argv.length === 2) {
    return cb(null, ['add', 'rm', 'ls'])
  }

  switch (argv[2]) {
    default:
      return cb()
  }
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.edit"></a>[module npm.edit](#apidoc.module.npm.edit)

#### <a name="apidoc.element.npm.edit.edit"></a>[function <span class="apidocSignatureSpan">npm.</span>edit (args, cb)](#apidoc.element.npm.edit.edit)
- description and source-code
```javascript
function edit(args, cb) {
  var p = args[0]
  if (args.length !== 1 || !p) return cb(edit.usage)
  var e = npm.config.get('editor')
  if (!e) {
    return cb(new Error(
      "No editor set.  Set the 'editor' config, or $EDITOR environ."
    ))
  }
  p = p.split('/')
       .join('/node_modules/')
       .replace(/(\/node_modules)+/, '/node_modules')
  var f = path.resolve(npm.dir, p)
  fs.lstat(f, function (er) {
    if (er) return cb(er)
    editor(f, { editor: e }, noProgressTillDone(function (er) {
      if (er) return cb(er)
      npm.commands.rebuild(args, cb)
    }))
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.edit.completion"></a>[function <span class="apidocSignatureSpan">npm.edit.</span>completion (opts, filter, cb)](#apidoc.element.npm.edit.completion)
- description and source-code
```javascript
function installedShallow(opts, filter, cb) {
  if (typeof cb !== 'function') {
    cb = filter
    filter = null
  }
  var conf = opts.conf
  var args = conf.argv.remain
  if (args.length > 3) return cb()
  var local
  var global
  var localDir = npm.dir
  var globalDir = npm.globalDir
  if (npm.config.get('global')) {
    local = []
    next()
  } else {
    fs.readdir(localDir, function (er, pkgs) {
      local = (pkgs || []).filter(function (p) {
        return p.charAt(0) !== '.'
      })
      next()
    })
  }

  fs.readdir(globalDir, function (er, pkgs) {
    global = (pkgs || []).filter(function (p) {
      return p.charAt(0) !== '.'
    })
    next()
  })
  function next () {
    if (!local || !global) return
    filterInstalled(local, global, filter, cb)
  }
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.explore"></a>[module npm.explore](#apidoc.module.npm.explore)

#### <a name="apidoc.element.npm.explore.explore"></a>[function <span class="apidocSignatureSpan">npm.</span>explore (args, cb)](#apidoc.element.npm.explore.explore)
- description and source-code
```javascript
function explore(args, cb) {
  if (args.length < 1 || !args[0]) return cb(explore.usage)
  var p = args.shift()

  var cwd = path.resolve(npm.dir, p)
  var opts = {cwd: cwd, stdio: 'inherit'}

  var shellArgs = []
  if (args) {
    if (isWindowsShell) {
      var execCmd = escapeExecPath(args.shift())
      var execArgs = [execCmd].concat(args.map(escapeArg))
      opts.windowsVerbatimArguments = true
      shellArgs = ['/d', '/s', '/c'].concat(execArgs)
    } else {
      shellArgs.unshift('-c')
      shellArgs = ['-c', args.map(escapeArg).join(' ').trim()]
    }
  }

  var sh = npm.config.get('shell')
  fs.stat(cwd, function (er, s) {
    if (er || !s.isDirectory()) {
      return cb(new Error(
        "It doesn't look like " + p + ' is installed.'
      ))
    }

    if (!shellArgs.length) {
      output(
        '\nExploring ' + cwd + '\n' +
          "Type 'exit' or ^D when finished\n"
      )
    }

    var shell = spawn(sh, shellArgs, opts)
    shell.on('close', function (er) {
      // only fail if non-interactive.
      if (!shellArgs.length) return cb()
      cb(er)
    })
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.explore.completion"></a>[function <span class="apidocSignatureSpan">npm.explore.</span>completion (opts, filter, cb)](#apidoc.element.npm.explore.completion)
- description and source-code
```javascript
function installedShallow(opts, filter, cb) {
  if (typeof cb !== 'function') {
    cb = filter
    filter = null
  }
  var conf = opts.conf
  var args = conf.argv.remain
  if (args.length > 3) return cb()
  var local
  var global
  var localDir = npm.dir
  var globalDir = npm.globalDir
  if (npm.config.get('global')) {
    local = []
    next()
  } else {
    fs.readdir(localDir, function (er, pkgs) {
      local = (pkgs || []).filter(function (p) {
        return p.charAt(0) !== '.'
      })
      next()
    })
  }

  fs.readdir(globalDir, function (er, pkgs) {
    global = (pkgs || []).filter(function (p) {
      return p.charAt(0) !== '.'
    })
    next()
  })
  function next () {
    if (!local || !global) return
    filterInstalled(local, global, filter, cb)
  }
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.help"></a>[module npm.help](#apidoc.module.npm.help)

#### <a name="apidoc.element.npm.help.help"></a>[function <span class="apidocSignatureSpan">npm.</span>help (args, cb)](#apidoc.element.npm.help.help)
- description and source-code
```javascript
function help(args, cb) {
  var argv = npm.config.get('argv').cooked

  var argnum = 0
  if (args.length === 2 && ~~args[0]) {
    argnum = ~~args.shift()
  }

  // npm help foo bar baz: search topics
  if (args.length > 1 && args[0]) {
    return npm.commands['help-search'](args, argnum, cb)
  }

  var section = npm.deref(args[0]) || args[0]

  // npm help <noargs>:  show basic usage
  if (!section) {
    var valid = argv[0] === 'help' ? 0 : 1
    return npmUsage(valid, cb)
  }

  // npm <cmd> -h: show command usage
  if (npm.config.get('usage') &&
      npm.commands[section] &&
      npm.commands[section].usage) {
    npm.config.set('loglevel', 'silent')
    log.level = 'silent'
    output(npm.commands[section].usage)
    return cb()
  }

  // npm apihelp <section>: Prefer section 3 over section 1
  var apihelp = argv.length && argv[0].indexOf('api') !== -1
  var pref = apihelp ? [3, 1, 5, 7] : [1, 3, 5, 7]
  if (argnum) {
    pref = [ argnum ].concat(pref.filter(function (n) {
      return n !== argnum
    }))
  }

  // npm help <section>: Try to find the path
  var manroot = path.resolve(__dirname, '..', 'man')

  // legacy
  if (section === 'global') section = 'folders'
  else if (section === 'json') section = 'package.json'

  // find either /section.n or /npm-section.n
  // The glob is used in the glob.  The regexp is used much
  // further down.  Globs and regexps are different
  var compextglob = '.+(gz|bz2|lzma|[FYzZ]|xz)'
  var compextre = '\\.(gz|bz2|lzma|[FYzZ]|xz)$'
  var f = '+(npm-' + section + '|' + section + ').[0-9]?(' + compextglob + ')'
  return glob(manroot + '/*/' + f, function (er, mans) {
    if (er) return cb(er)

    if (!mans.length) return npm.commands['help-search'](args, cb)

    mans = mans.map(function (man) {
      var ext = path.extname(man)
      if (man.match(new RegExp(compextre))) man = path.basename(man, ext)

      return man
    })

    viewMan(pickMan(mans, pref), cb)
  })
}
```
- example usage
```shell
...
    hits: found,
    totalHits: totalHits
  })
})

// if only one result, then just show that help section.
if (results.length === 1) {
  return npm.commands.help([results[0].file.replace(/\.md$/, '')], cb)
}

if (results.length === 0) {
  output('No results for ' + args.map(JSON.stringify).join(' '))
  return cb()
}
...
```

#### <a name="apidoc.element.npm.help.completion"></a>[function <span class="apidocSignatureSpan">npm.help.</span>completion (opts, cb)](#apidoc.element.npm.help.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  if (opts.conf.argv.remain.length > 2) return cb(null, [])
  getSections(cb)
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.link"></a>[module npm.link](#apidoc.module.npm.link)

#### <a name="apidoc.element.npm.link.link"></a>[function <span class="apidocSignatureSpan">npm.</span>link (args, cb)](#apidoc.element.npm.link.link)
- description and source-code
```javascript
function link(args, cb) {
  if (process.platform === 'win32') {
    var semver = require('semver')
    if (!semver.gte(process.version, '0.7.9')) {
      var msg = 'npm link not supported on windows prior to node 0.7.9'
      var e = new Error(msg)
      e.code = 'ENOTSUP'
      e.errno = require('constants').ENOTSUP
      return cb(e)
    }
  }

  if (npm.config.get('global')) {
    return cb(new Error(
      'link should never be --global.\n' +
      'Please re-run this command with --local'
    ))
  }

  if (args.length === 1 && args[0] === '.') args = []
  if (args.length) return linkInstall(args, cb)
  linkPkg(npm.prefix, cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.link.completion"></a>[function <span class="apidocSignatureSpan">npm.link.</span>completion (opts, cb)](#apidoc.element.npm.link.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  var dir = npm.globalDir
  fs.readdir(dir, function (er, files) {
    cb(er, files.filter(function (f) {
      return !f.match(/^[\._-]/)
    }))
  })
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.owner"></a>[module npm.owner](#apidoc.module.npm.owner)

#### <a name="apidoc.element.npm.owner.owner"></a>[function <span class="apidocSignatureSpan">npm.</span>owner (args, cb)](#apidoc.element.npm.owner.owner)
- description and source-code
```javascript
function owner(args, cb) {
  var action = args.shift()
  switch (action) {
    case 'ls': case 'list': return ls(args[0], cb)
    case 'add': return add(args[0], args[1], cb)
    case 'rm': case 'remove': return rm(args[0], args[1], cb)
    default: return unknown(action, cb)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.owner.completion"></a>[function <span class="apidocSignatureSpan">npm.owner.</span>completion (opts, cb)](#apidoc.element.npm.owner.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  var argv = opts.conf.argv.remain
  if (argv.length > 4) return cb()
  if (argv.length <= 2) {
    var subs = ['add', 'rm']
    if (opts.partialWord === 'l') subs.push('ls')
    else subs.push('ls', 'list')
    return cb(null, subs)
  }

  npm.commands.whoami([], true, function (er, username) {
    if (er) return cb()

    var un = encodeURIComponent(username)
    var byUser, theUser
    switch (argv[2]) {
      case 'ls':
        // FIXME: there used to be registry completion here, but it stopped
        // making sense somewhere around 50,000 packages on the registry
        return cb()

      case 'rm':
        if (argv.length > 3) {
          theUser = encodeURIComponent(argv[3])
          byUser = '-/by-user/' + theUser + '|' + un
          return mapToRegistry(byUser, npm.config, function (er, uri, auth) {
            if (er) return cb(er)

            console.error(uri)
            npm.registry.get(uri, { auth: auth }, function (er, d) {
              if (er) return cb(er)
              // return the intersection
              return cb(null, d[theUser].filter(function (p) {
                // kludge for server adminery.
                return un === 'isaacs' || d[un].indexOf(p) === -1
              }))
            })
          })
        }
        // else fallthrough
<span class="apidocCodeCommentSpan">        /*eslint no-fallthrough:0*/
</span>      case 'add':
        if (argv.length > 3) {
          theUser = encodeURIComponent(argv[3])
          byUser = '-/by-user/' + theUser + '|' + un
          return mapToRegistry(byUser, npm.config, function (er, uri, auth) {
            if (er) return cb(er)

            console.error(uri)
            npm.registry.get(uri, { auth: auth }, function (er, d) {
              console.error(uri, er || d)
              // return mine that they're not already on.
              if (er) return cb(er)
              var mine = d[un] || []
              var theirs = d[theUser] || []
              return cb(null, mine.filter(function (p) {
                return theirs.indexOf(p) === -1
              }))
            })
          })
        }
        // just list all users who aren't me.
        return mapToRegistry('-/users', npm.config, function (er, uri, auth) {
          if (er) return cb(er)

          npm.registry.get(uri, { auth: auth }, function (er, list) {
            if (er) return cb()
            return cb(null, Object.keys(list).filter(function (n) {
              return n !== un
            }))
          })
        })

      default:
        return cb()
    }
  })
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.publish"></a>[module npm.publish](#apidoc.module.npm.publish)

#### <a name="apidoc.element.npm.publish.publish"></a>[function <span class="apidocSignatureSpan">npm.</span>publish (args, isRetry, cb)](#apidoc.element.npm.publish.publish)
- description and source-code
```javascript
function publish(args, isRetry, cb) {
  if (typeof cb !== 'function') {
    cb = isRetry
    isRetry = false
  }
  if (args.length === 0) args = ['.']
  if (args.length !== 1) return cb(publish.usage)

  log.verbose('publish', args)

  var t = npm.config.get('tag').trim()
  if (semver.validRange(t)) {
    var er = new Error('Tag name must not be a valid SemVer range: ' + t)
    return cb(er)
  }

  var arg = args[0]
  // if it's a local folder, then run the prepublish there, first.
  readJson(path.resolve(arg, 'package.json'), function (er, data) {
    if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)

    if (data) {
      if (!data.name) return cb(new Error('No name provided'))
      if (!data.version) return cb(new Error('No version provided'))
    }

    // if readJson errors, the argument might be a tarball or package URL
    if (er) {
      npm.commands.cache.add(arg, null, null, false, function (er, data) {
        if (er) return cb(er)
        log.silly('publish', data)
        var cached = path.resolve(cachedPackageRoot(data), 'package') + '.tgz'
        // *publish* lifecycle scripts aren't run when publishing a built artifact
        // go to the next step directly
        publish_(arg, data, isRetry, cached, cb)
      })
    } else {
      var dir = arg
      npm.commands.cache.add(dir, null, null, false, function (er, data) {
        if (er) return cb(er)
        log.silly('publish', data)
        var cached = path.resolve(cachedPackageRoot(data), 'package') + '.tgz'
        // 'prepublish' and 'prepare' are run by cache.add
        chain(
          [
            [lifecycle, data, 'prepublishOnly', dir],
            [publish_, dir, data, isRetry, cached],
            [lifecycle, data, 'publish', dir],
            [lifecycle, data, 'postpublish', dir]
          ],
          cb
        )
      })
    }
  })
}
```
- example usage
```shell
...
    return cb(new Error("Can't restrict access to unscoped packages."))
  }

  params.access = config.get('access')
}

log.showProgress('publish:' + data._id)
registry.publish(registryBase, params, function (er) {
  if (er && er.code === 'EPUBLISHCONFLICT' &&
      npm.config.get('force') && !isRetry) {
    log.warn('publish', 'Forced publish over ' + data._id)
    return npm.commands.unpublish([data._id], function (er) {
      // ignore errors.  Use the force.  Reach out with your feelings.
      // but if it fails again, then report the first error.
      publish([arg], er || true, cb)
...
```

#### <a name="apidoc.element.npm.publish.completion"></a>[function <span class="apidocSignatureSpan">npm.publish.</span>completion (opts, cb)](#apidoc.element.npm.publish.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  // publish can complete to a folder with a package.json
  // or a tarball, or a tarball url.
  // for now, not yet implemented.
  return cb()
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.rebuild"></a>[module npm.rebuild](#apidoc.module.npm.rebuild)

#### <a name="apidoc.element.npm.rebuild.rebuild"></a>[function <span class="apidocSignatureSpan">npm.</span>rebuild (args, cb)](#apidoc.element.npm.rebuild.rebuild)
- description and source-code
```javascript
function rebuild(args, cb) {
  var opt = { depth: npm.config.get('depth'), dev: true }
  readInstalled(npm.prefix, opt, function (er, data) {
    log.info('readInstalled', typeof data)
    if (er) return cb(er)
    var set = filter(data, args)
    var folders = Object.keys(set).filter(function (f) {
      return f !== npm.prefix
    })
    if (!folders.length) return cb()
    log.silly('rebuild set', folders)
    cleanBuild(folders, set, cb)
  })
}
```
- example usage
```shell
...
       .join('/node_modules/')
       .replace(/(\/node_modules)+/, '/node_modules')
  var f = path.resolve(npm.dir, p)
  fs.lstat(f, function (er) {
    if (er) return cb(er)
    editor(f, { editor: e }, noProgressTillDone(function (er) {
      if (er) return cb(er)
      npm.commands.rebuild(args, cb)
    }))
  })
}
...
```

#### <a name="apidoc.element.npm.rebuild.completion"></a>[function <span class="apidocSignatureSpan">npm.rebuild.</span>completion (opts, cb)](#apidoc.element.npm.rebuild.completion)
- description and source-code
```javascript
function installedDeep(opts, cb) {
  var local
  var global
  var depth = npm.config.get('depth')
  var opt = { depth: depth, dev: true }

  if (npm.config.get('global')) {
    local = []
    next()
  } else {
    readInstalled(npm.prefix, opt, function (er, data) {
      local = getNames(data || {})
      next()
    })
  }

  readInstalled(npm.config.get('prefix'), opt, function (er, data) {
    global = getNames(data || {})
    next()
  })

  function getNames_ (d, n) {
    if (d.realName && n) {
      if (n[d.realName]) return n
      n[d.realName] = true
    }
    if (!n) n = {}
    Object.keys(d.dependencies || {}).forEach(function (dep) {
      getNames_(d.dependencies[dep], n)
    })
    return n
  }
  function getNames (d) {
    return Object.keys(getNames_(d))
  }

  function next () {
    if (!local || !global) return
    if (!npm.config.get('global')) {
      global = global.map(function (g) {
        return [g, '-g']
      })
    }
    var names = local.concat(global)
    return cb(null, names)
  }
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.restart"></a>[module npm.restart](#apidoc.module.npm.restart)

#### <a name="apidoc.element.npm.restart.restart"></a>[function <span class="apidocSignatureSpan">npm.</span>restart (args, cb)](#apidoc.element.npm.restart.restart)
- description and source-code
```javascript
function CMD(args, cb) {
  npm.commands['run-script']([stage].concat(args), cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.restart.completion"></a>[function <span class="apidocSignatureSpan">npm.restart.</span>completion (opts, cb)](#apidoc.element.npm.restart.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  installedShallow(opts, function (d) {
    return d.scripts && d.scripts[stage]
  }, cb)
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.run_script"></a>[module npm.run_script](#apidoc.module.npm.run_script)

#### <a name="apidoc.element.npm.run_script.run_script"></a>[function <span class="apidocSignatureSpan">npm.</span>run_script (args, cb)](#apidoc.element.npm.run_script.run_script)
- description and source-code
```javascript
function runScript(args, cb) {
  if (!args.length) return list(cb)

  var pkgdir = npm.localPrefix
  var cmd = args.shift()

  readJson(path.resolve(pkgdir, 'package.json'), function (er, d) {
    if (er) return cb(er)
    run(d, pkgdir, cmd, args, cb)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.run_script.completion"></a>[function <span class="apidocSignatureSpan">npm.run_script.</span>completion (opts, cb)](#apidoc.element.npm.run_script.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  // see if there's already a package specified.
  var argv = opts.conf.argv.remain

  if (argv.length >= 4) return cb()

  if (argv.length === 3) {
    // either specified a script locally, in which case, done,
    // or a package, in which case, complete against its scripts
    var json = path.join(npm.localPrefix, 'package.json')
    return readJson(json, function (er, d) {
      if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)
      if (er) d = {}
      var scripts = Object.keys(d.scripts || {})
      console.error('local scripts', scripts)
      if (scripts.indexOf(argv[2]) !== -1) return cb()
      // ok, try to find out which package it was, then
      var pref = npm.config.get('global') ? npm.config.get('prefix')
               : npm.localPrefix
      var pkgDir = path.resolve(pref, 'node_modules', argv[2], 'package.json')
      readJson(pkgDir, function (er, d) {
        if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)
        if (er) d = {}
        var scripts = Object.keys(d.scripts || {})
        return cb(null, scripts)
      })
    })
  }

  readJson(path.join(npm.localPrefix, 'package.json'), function (er, d) {
    if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)
    d = d || {}
    cb(null, Object.keys(d.scripts || {}))
  })
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.search"></a>[module npm.search](#apidoc.module.npm.search)

#### <a name="apidoc.element.npm.search.search"></a>[function <span class="apidocSignatureSpan">npm.</span>search (args, cb)](#apidoc.element.npm.search.search)
- description and source-code
```javascript
function search(args, cb) {
  var searchOpts = {
    description: npm.config.get('description'),
    exclude: prepareExcludes(npm.config.get('searchexclude')),
    include: prepareIncludes(args, npm.config.get('searchopts')),
    limit: npm.config.get('searchlimit'),
    log: log,
    staleness: npm.config.get('searchstaleness'),
    unicode: npm.config.get('unicode')
  }

  if (searchOpts.include.length === 0) {
    return cb(new Error('search must be called with arguments'))
  }

  // Used later to figure out whether we had any packages go out
  var anyOutput = false

  var entriesStream = ms.through.obj()

  var esearchWritten = false
  esearch(searchOpts).on('data', function (pkg) {
    entriesStream.write(pkg)
    !esearchWritten && (esearchWritten = true)
  }).on('error', function (e) {
    if (esearchWritten) {
      // If esearch errored after already starting output, we can't fall back.
      return entriesStream.emit('error', e)
    }
    log.warn('search', 'fast search endpoint errored. Using old search.')
    allPackageSearch(searchOpts).on('data', function (pkg) {
      entriesStream.write(pkg)
    }).on('error', function (e) {
      entriesStream.emit('error', e)
    }).on('end', function () {
      entriesStream.end()
    })
  }).on('end', function () {
    entriesStream.end()
  })

  // Grab a configured output stream that will spit out packages in the
  // desired format.
  var outputStream = formatPackageStream({
    args: args, // --searchinclude options are not highlighted
    long: npm.config.get('long'),
    description: npm.config.get('description'),
    json: npm.config.get('json'),
    parseable: npm.config.get('parseable'),
    color: npm.color
  })
  outputStream.on('data', function (chunk) {
    if (!anyOutput) { anyOutput = true }
    output(chunk.toString('utf8'))
  })

  log.silly('search', 'searching packages')
  ms.pipe(entriesStream, outputStream, function (er) {
    if (er) return cb(er)
    if (!anyOutput && !npm.config.get('json') && !npm.config.get('parseable')) {
      output('No matches found for ' + (args.map(JSON.stringify).join(' ')))
    }
    log.silly('search', 'search completed')
    log.clearProgress()
    cb(null, {})
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.search.completion"></a>[function <span class="apidocSignatureSpan">npm.search.</span>completion (opts, cb)](#apidoc.element.npm.search.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  cb(null, [])
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.star"></a>[module npm.star](#apidoc.module.npm.star)

#### <a name="apidoc.element.npm.star.star"></a>[function <span class="apidocSignatureSpan">npm.</span>star (args, cb)](#apidoc.element.npm.star.star)
- description and source-code
```javascript
function star(args, cb) {
  if (!args.length) return cb(star.usage)
  var s = npm.config.get('unicode') ? '\u2605 ' : '(*)'
  var u = npm.config.get('unicode') ? '\u2606 ' : '( )'
  var using = !(npm.command.match(/^un/))
  if (!using) s = u
  asyncMap(args, function (pkg, cb) {
    mapToRegistry(pkg, npm.config, function (er, uri, auth) {
      if (er) return cb(er)

      var params = {
        starred: using,
        auth: auth
      }
      npm.registry.star(uri, params, function (er, data, raw, req) {
        if (!er) {
          output(s + ' ' + pkg)
          log.verbose('star', data)
        }
        cb(er, data, raw, req)
      })
    })
  }, cb)
}
```
- example usage
```shell
...
mapToRegistry(pkg, npm.config, function (er, uri, auth) {
  if (er) return cb(er)

  var params = {
    starred: using,
    auth: auth
  }
  npm.registry.star(uri, params, function (er, data, raw, req) {
    if (!er) {
      output(s + ' ' + pkg)
      log.verbose('star', data)
    }
    cb(er, data, raw, req)
  })
})
...
```

#### <a name="apidoc.element.npm.star.completion"></a>[function <span class="apidocSignatureSpan">npm.star.</span>completion (opts, cb)](#apidoc.element.npm.star.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  // FIXME: there used to be registry completion here, but it stopped making
  // sense somewhere around 50,000 packages on the registry
  cb()
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.start"></a>[module npm.start](#apidoc.module.npm.start)

#### <a name="apidoc.element.npm.start.start"></a>[function <span class="apidocSignatureSpan">npm.</span>start (args, cb)](#apidoc.element.npm.start.start)
- description and source-code
```javascript
function CMD(args, cb) {
  npm.commands['run-script']([stage].concat(args), cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.start.completion"></a>[function <span class="apidocSignatureSpan">npm.start.</span>completion (opts, cb)](#apidoc.element.npm.start.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  installedShallow(opts, function (d) {
    return d.scripts && d.scripts[stage]
  }, cb)
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.stop"></a>[module npm.stop](#apidoc.module.npm.stop)

#### <a name="apidoc.element.npm.stop.stop"></a>[function <span class="apidocSignatureSpan">npm.</span>stop (args, cb)](#apidoc.element.npm.stop.stop)
- description and source-code
```javascript
function CMD(args, cb) {
  npm.commands['run-script']([stage].concat(args), cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.stop.completion"></a>[function <span class="apidocSignatureSpan">npm.stop.</span>completion (opts, cb)](#apidoc.element.npm.stop.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  installedShallow(opts, function (d) {
    return d.scripts && d.scripts[stage]
  }, cb)
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.team"></a>[module npm.team](#apidoc.module.npm.team)

#### <a name="apidoc.element.npm.team.team"></a>[function <span class="apidocSignatureSpan">npm.</span>team (args, cb)](#apidoc.element.npm.team.team)
- description and source-code
```javascript
function team(args, cb) {
  // Entities are in the format <scope>:<team>
  var cmd = args.shift()
  var entity = (args.shift() || '').split(':')
  return mapToRegistry('/', npm.config, function (err, uri, auth) {
    if (err) { return cb(err) }
    try {
      return npm.registry.team(cmd, uri, {
        auth: auth,
        scope: entity[0],
        team: entity[1],
        user: args.shift()
      }, function (err, data) {
        !err && data && output(JSON.stringify(data, undefined, 2))
        cb(err, data)
      })
    } catch (e) {
      cb(e.message + '\n\nUsage:\n' + team.usage)
    }
  })
}
```
- example usage
```shell
...
function team (args, cb) {
// Entities are in the format <scope>:<team>
var cmd = args.shift()
var entity = (args.shift() || '').split(':')
return mapToRegistry('/', npm.config, function (err, uri, auth) {
  if (err) { return cb(err) }
  try {
    return npm.registry.team(cmd, uri, {
      auth: auth,
      scope: entity[0],
      team: entity[1],
      user: args.shift()
    }, function (err, data) {
      !err && data && output(JSON.stringify(data, undefined, 2))
      cb(err, data)
...
```

#### <a name="apidoc.element.npm.team.completion"></a>[function <span class="apidocSignatureSpan">npm.team.</span>completion (opts, cb)](#apidoc.element.npm.team.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  var argv = opts.conf.argv.remain
  if (argv.length === 2) {
    return cb(null, team.subcommands)
  }
  switch (argv[2]) {
    case 'ls':
    case 'create':
    case 'destroy':
    case 'add':
    case 'rm':
    case 'edit':
      return cb(null, [])
    default:
      return cb(new Error(argv[2] + ' not recognized'))
  }
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.unbuild"></a>[module npm.unbuild](#apidoc.module.npm.unbuild)

#### <a name="apidoc.element.npm.unbuild.unbuild"></a>[function <span class="apidocSignatureSpan">npm.</span>unbuild (args, silent, cb)](#apidoc.element.npm.unbuild.unbuild)
- description and source-code
```javascript
function unbuild(args, silent, cb) {
  if (typeof silent === 'function') {
    cb = silent
    silent = false
  }
  asyncMap(args, unbuild_(silent), cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.unbuild.rmStuff"></a>[function <span class="apidocSignatureSpan">npm.unbuild.</span>rmStuff (pkg, folder, cb)](#apidoc.element.npm.unbuild.rmStuff)
- description and source-code
```javascript
function rmStuff(pkg, folder, cb) {
  // if it's global, and folder is in {prefix}/node_modules,
  // then bins are in {prefix}/bin
  // otherwise, then bins are in folder/../.bin
  var parent = pkg.name[0] === '@' ? path.dirname(path.dirname(folder)) : path.dirname(folder)
  var gnm = npm.dir
  var top = gnm === parent

  log.verbose('unbuild rmStuff', pkg._id, 'from', gnm)
  if (!top) log.verbose('unbuild rmStuff', 'in', parent)
  asyncMap([rmBins, rmMans], function (fn, cb) {
    fn(pkg, folder, parent, top, cb)
  }, cb)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.npm.unpublish"></a>[module npm.unpublish](#apidoc.module.npm.unpublish)

#### <a name="apidoc.element.npm.unpublish.unpublish"></a>[function <span class="apidocSignatureSpan">npm.</span>unpublish (args, cb)](#apidoc.element.npm.unpublish.unpublish)
- description and source-code
```javascript
function unpublish(args, cb) {
  if (args.length > 1) return cb(unpublish.usage)

  var thing = args.length ? npa(args[0]) : {}
  var project = thing.name
  var version = thing.rawSpec

  log.silly('unpublish', 'args[0]', args[0])
  log.silly('unpublish', 'thing', thing)
  if (!version && !npm.config.get('force')) {
    return cb(
      'Refusing to delete entire project.\n' +
      'Run with --force to do this.\n' +
      unpublish.usage
    )
  }

  if (!project || path.resolve(project) === npm.localPrefix) {
    // if there's a package.json in the current folder, then
    // read the package name and version out of that.
    var cwdJson = path.join(npm.localPrefix, 'package.json')
    return readJson(cwdJson, function (er, data) {
      if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)
      if (er) return cb('Usage:\n' + unpublish.usage)
      log.verbose('unpublish', data)
      gotProject(data.name, data.version, data.publishConfig, cb)
    })
  }
  return gotProject(project, version, cb)
}
```
- example usage
```shell
...
}

log.showProgress('publish:' + data._id)
registry.publish(registryBase, params, function (er) {
  if (er && er.code === 'EPUBLISHCONFLICT' &&
      npm.config.get('force') && !isRetry) {
    log.warn('publish', 'Forced publish over ' + data._id)
    return npm.commands.unpublish([data._id], function (er) {
      // ignore errors.  Use the force.  Reach out with your feelings.
      // but if it fails again, then report the first error.
      publish([arg], er || true, cb)
    })
  }
  // report the unpublish error if this was a retry and unpublish failed
  if (er && isRetry && isRetry !== true) return cb(isRetry)
...
```

#### <a name="apidoc.element.npm.unpublish.completion"></a>[function <span class="apidocSignatureSpan">npm.unpublish.</span>completion (opts, cb)](#apidoc.element.npm.unpublish.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  if (opts.conf.argv.remain.length >= 3) return cb()
  npm.commands.whoami([], true, function (er, username) {
    if (er) return cb()

    var un = encodeURIComponent(username)
    if (!un) return cb()
    var byUser = '-/by-user/' + un
    mapToRegistry(byUser, npm.config, function (er, uri, auth) {
      if (er) return cb(er)

      npm.registry.get(uri, { auth: auth }, function (er, pkgs) {
        // do a bit of filtering at this point, so that we don't need
        // to fetch versions for more than one thing, but also don't
        // accidentally a whole project.
        pkgs = pkgs[un]
        if (!pkgs || !pkgs.length) return cb()
        var pp = npa(opts.partialWord).name
        pkgs = pkgs.filter(function (p) {
          return p.indexOf(pp) === 0
        })
        if (pkgs.length > 1) return cb(null, pkgs)
        mapToRegistry(pkgs[0], npm.config, function (er, uri, auth) {
          if (er) return cb(er)

          npm.registry.get(uri, { auth: auth }, function (er, d) {
            if (er) return cb(er)
            var vers = Object.keys(d.versions)
            if (!vers.length) return cb(null, pkgs)
            return cb(null, vers.map(function (v) {
              return pkgs[0] + '@' + v
            }))
          })
        })
      })
    })
  })
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# <a name="apidoc.module.npm.view"></a>[module npm.view](#apidoc.module.npm.view)

#### <a name="apidoc.element.npm.view.view"></a>[function <span class="apidocSignatureSpan">npm.</span>view (args, silent, cb)](#apidoc.element.npm.view.view)
- description and source-code
```javascript
function view(args, silent, cb) {
  if (typeof cb !== 'function') {
    cb = silent
    silent = false
  }

  if (!args.length) args = ['.']

  var pkg = args.shift()
  var nv = npa(pkg)
  var name = nv.name
  var local = (name === '.' || !name)

  if (npm.config.get('global') && local) {
    return cb(new Error('Cannot use view command in global mode.'))
  }

  if (local) {
    var dir = npm.prefix
    readJson(path.resolve(dir, 'package.json'), function (er, d) {
      d = d || {}
      if (er && er.code !== 'ENOENT' && er.code !== 'ENOTDIR') return cb(er)
      if (!d.name) return cb(new Error('Invalid package.json'))

      var p = d.name
      nv = npa(p)
      if (pkg && ~pkg.indexOf('@')) {
        nv.rawSpec = pkg.split('@')[pkg.indexOf('@')]
      }

      fetchAndRead(nv, args, silent, cb)
    })
  } else {
    fetchAndRead(nv, args, silent, cb)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.npm.view.completion"></a>[function <span class="apidocSignatureSpan">npm.view.</span>completion (opts, cb)](#apidoc.element.npm.view.completion)
- description and source-code
```javascript
completion = function (opts, cb) {
  if (opts.conf.argv.remain.length <= 2) {
    // FIXME: there used to be registry completion here, but it stopped making
    // sense somewhere around 50,000 packages on the registry
    return cb()
  }
  // have the package, get the fields.
  var tag = npm.config.get('tag')
  mapToRegistry(opts.conf.argv.remain[2], npm.config, function (er, uri, auth) {
    if (er) return cb(er)

    npm.registry.get(uri, { auth: auth }, function (er, d) {
      if (er) return cb(er)
      var dv = d.versions[d['dist-tags'][tag]]
      var fields = []
      d.versions = Object.keys(d.versions).sort(semver.compareLoose)
      fields = getFields(d).concat(getFields(dv))
      cb(null, fields)
    })
  })

  function getFields (d, f, pref) {
    f = f || []
    if (!d) return f
    pref = pref || []
    Object.keys(d).forEach(function (k) {
      if (k.charAt(0) === '_' || k.indexOf('.') !== -1) return
      var p = pref.concat(k).join('.')
      f.push(p)
      if (Array.isArray(d[k])) {
        d[k].forEach(function (val, i) {
          var pi = p + '[' + i + ']'
          if (val && typeof val === 'object') getFields(val, f, [p])
          else f.push(pi)
        })
        return
      }
      if (typeof d[k] === 'object') getFields(d[k], f, [p])
    })
    return f
  }
}
```
- example usage
```shell
...
  npm.config.set(k, parsed[k])
})

// at this point, if words[1] is some kind of npm command,
// then complete on it.
// otherwise, do nothing
cmd = npm.commands[cmd]
if (cmd && cmd.completion) return cmd.completion(opts, cb)

// nothing to do.
cb()
}

function dumpScript (cb) {
var fs = require('graceful-fs')
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
