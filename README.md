# api documentation for  [sinon (v2.1.0)](http://sinonjs.org/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sinon.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sinon)
#### JavaScript test spies, stubs and mocks.

[![NPM](https://nodei.co/npm/sinon.png?downloads=true)](https://www.npmjs.com/package/sinon)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sinon/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sinon_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sinon/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-sinon/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Christian Johansen"
    },
    "bugs": {
        "url": "http://github.com/sinonjs/sinon/issues"
    },
    "contributors": [
        {
            "name": "Christian Johansen",
            "email": "christian@cjohansen.no"
        },
        {
            "name": "Morgan Roderick",
            "email": "morgan@roderick.dk"
        },
        {
            "name": "Carl-Erik Kopseng",
            "email": "carlerik@gmail.com"
        },
        {
            "name": "Maximilian Antoni",
            "email": "mail@maxantoni.de"
        },
        {
            "name": "Jonny Reeves",
            "email": "github@jonnyreeves.co.uk"
        },
        {
            "name": "Phred",
            "email": "fearphage@gmail.com"
        },
        {
            "name": "lucasfcosta",
            "email": "fernandesdacostalucas@gmail.com"
        },
        {
            "name": "ben hockey",
            "email": "neonstalwart@gmail.com"
        },
        {
            "name": "Tim Fischbach",
            "email": "mail@timfischbach.de"
        },
        {
            "name": "Håvard Wormdal Høiby",
            "email": "havardwhoiby@gmail.com"
        },
        {
            "name": "Tim Ruffles",
            "email": "timruffles@googlemail.com"
        },
        {
            "name": "Jonathan Sokolowski",
            "email": "jonathan.sokolowski@gmail.com"
        },
        {
            "name": "Andreas Lind",
            "email": "andreas@one.com"
        },
        {
            "name": "Domenic Denicola",
            "email": "domenic@domenicdenicola.com"
        },
        {
            "name": "Tim Perry",
            "email": "pimterry@gmail.com"
        },
        {
            "name": "William Sears",
            "email": "MrBigDog2U@gmail.com"
        },
        {
            "name": "Mikhail Gusarov",
            "email": "mikhail@hola.org"
        },
        {
            "name": "kpdecker",
            "email": "kpdecker@gmail.com"
        },
        {
            "name": "Bryan Donovan",
            "email": "bdondo@gmail.com"
        },
        {
            "name": "Felix Geisendörfer",
            "email": "felix@debuggable.com"
        },
        {
            "name": "Tobias Ebnöther",
            "email": "ebi@gorn.ch"
        },
        {
            "name": "Keith Cirkel",
            "email": "github@keithcirkel.co.uk"
        },
        {
            "name": "Doug Orleans",
            "email": "dougorleans@gmail.com"
        },
        {
            "name": "Andrew Gurinovich",
            "email": "altmind@gmail.com"
        },
        {
            "name": "Cory",
            "email": "seeflanigan@gmail.com"
        },
        {
            "name": "Martin Sander",
            "email": "forke@uni-bonn.de"
        },
        {
            "name": "Luis Cardoso",
            "email": "luis.cardoso@feedzai.com"
        },
        {
            "name": "Tristan Koch",
            "email": "tristan.koch@1und1.de"
        },
        {
            "name": "Adam Hull",
            "email": "adam@hmlad.com"
        },
        {
            "name": "Konrad Holowinski",
            "email": "konrad.holowinski@gmail.com"
        },
        {
            "name": "Garrick Cheung",
            "email": "garrick@garrickcheung.com"
        },
        {
            "name": "Benjamin Coe",
            "email": "ben@yesware.com"
        },
        {
            "name": "Viktor Zozulyak",
            "email": "zozulyakviktor@gmail.com"
        },
        {
            "name": "Marten Lienen",
            "email": "marten.lienen@gmail.com"
        },
        {
            "name": "Travis Kaufman",
            "email": "travis.kaufman@gmail.com"
        },
        {
            "name": "ben fleis",
            "email": "ben.fleis@gmail.com"
        },
        {
            "name": "zcicala",
            "email": "zcicala@fitbit.com"
        },
        {
            "name": "Gavin Huang",
            "email": "gravof@gmail.com"
        },
        {
            "name": "Duncan Beevers",
            "email": "duncan@dweebd.com"
        },
        {
            "name": "Islam Sharabash",
            "email": "islam.sharabash@gmail.com"
        },
        {
            "name": "Ming Liu",
            "email": "vmliu1@gmail.com"
        },
        {
            "name": "Dmitriy Kubyshkin",
            "email": "grassator@gmail.com"
        },
        {
            "name": "Dominykas Blyžė",
            "email": "hello@dominykas.com"
        },
        {
            "name": "Rae Liu",
            "email": "happyaray@gmail.com"
        },
        {
            "name": "Jmeas",
            "email": "jellyes2@gmail.com"
        },
        {
            "name": "Robin Pedersen",
            "email": "robinp@snap.tv"
        },
        {
            "name": "Roman Potashow",
            "email": "justgook@gmail.com"
        },
        {
            "name": "Scott Andrews",
            "email": "scothis@gmail.com"
        },
        {
            "name": "Soutaro Matsumoto",
            "email": "matsumoto@soutaro.com"
        },
        {
            "name": "August Lilleaas",
            "email": "august.lilleaas@gmail.com"
        },
        {
            "name": "Florent Jaby",
            "email": "florent.jaby@gmail.com"
        },
        {
            "name": "Tamas Szebeni",
            "email": "tamas_szebeni@epam.com"
        },
        {
            "name": "Garrick",
            "email": "gcheung@fitbit.com"
        },
        {
            "name": "Thomas Meyer",
            "email": "meyertee@gmail.com"
        },
        {
            "name": "Glen Mailer",
            "email": "glen.mailer@bskyb.com"
        },
        {
            "name": "geries",
            "email": "geries.handal@videoplaza.com"
        },
        {
            "name": "Cormac Flynn",
            "email": "cormac.flynn@viadeoteam.com"
        },
        {
            "name": "Szymon Przybylski",
            "email": "szymon.przybylski@gmail.com"
        },
        {
            "name": "Josh Greenberger",
            "email": "jdgreenb@usc.edu"
        },
        {
            "name": "Spencer Elliott",
            "email": "me@elliottsj.com"
        },
        {
            "name": "Josh Graham",
            "email": "josh@canva.com"
        },
        {
            "name": "Simen Bekkhus",
            "email": "sbekkhus91@gmail.com"
        },
        {
            "name": "Victor Costan",
            "email": "costan@gmail.com"
        },
        {
            "name": "Farid Neshat",
            "email": "FaridN_SOAD@yahoo.com"
        },
        {
            "name": "yoshimura-toshihide",
            "email": "toshihide0105yoshimura@gmail.com"
        },
        {
            "name": "Brandon Heyer",
            "email": "brandonheyer@gmail.com"
        },
        {
            "name": "Alex Urbano",
            "email": "asgaroth.belem@gmail.com"
        },
        {
            "name": "Alexander Schmidt",
            "email": "alexanderschmidt1@gmail.com"
        },
        {
            "name": "Satoshi Nakamura",
            "email": "snakamura@infoteria.com"
        },
        {
            "name": "Jonathan Freeman",
            "email": "freethejazz@gmail.com"
        },
        {
            "name": "Andrzej Porebski",
            "email": "fkuciapa@yahoo.com"
        },
        {
            "name": "Jimmy Shimizu",
            "email": "jimmy.shimizu@springworks.se"
        },
        {
            "name": "Marcus Hüsgen",
            "email": "marcus.huesgen@lusini.com"
        },
        {
            "name": "Max Calabrese",
            "email": "max.calabrese@ymail.com"
        },
        {
            "name": "gtothesquare",
            "email": "me@gerieshandal.com"
        },
        {
            "name": "なつき",
            "email": "i@ntk.me"
        },
        {
            "name": "Henry Tung",
            "email": "henryptung@gmail.com"
        },
        {
            "name": "Mark Stacey",
            "email": "mark.stacey@amecfw.com"
        },
        {
            "name": "Jeffrey Falgout",
            "email": "jfalgout@bloomberg.net"
        },
        {
            "name": "Jason Karns",
            "email": "jason.karns@gmail.com"
        },
        {
            "name": "mohayonao",
            "email": "mohayonao@gmail.com"
        },
        {
            "name": "Márton Salomváry",
            "email": "salomvary@gmail.com"
        },
        {
            "name": "James Barwell",
            "email": "jb@jamesbarwell.co.uk"
        },
        {
            "name": "Devin Weaver",
            "email": "suki@tritarget.org"
        },
        {
            "name": "Martin Hansen",
            "email": "martin@martinhansen.no"
        },
        {
            "name": "Daniel Rey Lopez",
            "email": "daniel.rey.lopez@automattic.com"
        },
        {
            "name": "Irina Dumitrascu",
            "email": "me@dira.ro"
        },
        {
            "name": "vitalets",
            "email": "vitalets@yandex-team.ru"
        },
        {
            "name": "Matt Kern",
            "email": "matt@bloomcrush.com"
        },
        {
            "name": "Tim Costa",
            "email": "tcosta@2u.com"
        },
        {
            "name": "G.Serebryanskyi",
            "email": "x5x3x5x@gmail.com"
        },
        {
            "name": "Simone Fonda",
            "email": "fonda@netseven.it"
        },
        {
            "name": "Stefan Weil",
            "email": "sw@weilnetz.de"
        },
        {
            "name": "Stephen Burrows",
            "email": "stephen.r.burrows@gmail.com"
        },
        {
            "name": "Sven Fuchs",
            "email": "svenfuchs@artweb-design.de"
        },
        {
            "name": "Søren Enemærke",
            "email": "soren.enemaerke@gmail.com"
        },
        {
            "name": "T1st3",
            "email": "contact@tiste.org"
        },
        {
            "name": "TEHEK Firefox",
            "email": "tehek@tehek.net"
        },
        {
            "name": "Tarjei Huse",
            "email": "tarjei.huse@gmail.com"
        },
        {
            "name": "Tek Nynja",
            "email": "github@teknynja.com"
        },
        {
            "name": "The Gitter Badger",
            "email": "badger@gitter.im"
        },
        {
            "name": "Tieme van Veen",
            "email": "tiemevanveen@hotmail.com"
        },
        {
            "name": "Tim Branyen",
            "email": "tim@tabdeveloper.com"
        },
        {
            "name": "Tim Wienk",
            "email": "tim@wienk.name"
        },
        {
            "name": "Timo Tijhof",
            "email": "krinklemail@gmail.com"
        },
        {
            "name": "Volkan Ozcelik",
            "email": "volkan.ozcelik@jivesoftware.com"
        },
        {
            "name": "AJ Ortega",
            "email": "ajo@google.com"
        },
        {
            "name": "William Meleyal",
            "email": "w.meleyal@wollzelle.com"
        },
        {
            "name": "Xiao Ma",
            "email": "x@medium.com"
        },
        {
            "name": "charlierudolph",
            "email": "charles.w.rudolph@gmail.com"
        },
        {
            "name": "clint",
            "email": "clint@wealthfront.com"
        },
        {
            "name": "goligo",
            "email": "ich@malte.de"
        },
        {
            "name": "hashchange",
            "email": "heim@zeilenwechsel.de"
        },
        {
            "name": "ichthala",
            "email": "alice.mottola@gmail.com"
        },
        {
            "name": "jamestalmage",
            "email": "james.talmage@jrtechnical.com"
        },
        {
            "name": "kbackowski",
            "email": "kbackowski@gmail.com"
        },
        {
            "name": "ngryman",
            "email": "ngryman@gmail.com"
        },
        {
            "name": "simonzack",
            "email": "simonzack@gmail.com"
        },
        {
            "name": "stevesouth",
            "email": "stephen.south@caplin.com"
        },
        {
            "name": "thefourtheye",
            "email": "thefourtheye@users.noreply.github.com"
        },
        {
            "name": "till",
            "email": "till@php.net"
        },
        {
            "name": "wwalser",
            "email": "waw325@gmail.com"
        },
        {
            "name": "Will Butler",
            "email": "will@butlerhq.com"
        },
        {
            "name": "AdilKhn",
            "email": "AdilKhn@users.noreply.github.com"
        },
        {
            "name": "Adrian Phinney",
            "email": "adrian.phinney@bellaliant.net"
        },
        {
            "name": "Afnizar Nur Ghifari",
            "email": "afnizarnur@users.noreply.github.com"
        },
        {
            "name": "Akira Matsuda",
            "email": "ronnie@dio.jp"
        },
        {
            "name": "Alex Ghiculescu",
            "email": "alex@tanda.co"
        },
        {
            "name": "Alex Kessaris",
            "email": "alex@artsy.ca"
        },
        {
            "name": "Alex Tran",
            "email": "alex@Alexs-MacBook-Pro-2.local"
        },
        {
            "name": "Alexander Aivars",
            "email": "alex@aivars.se"
        },
        {
            "name": "Alfonso Boza",
            "email": "alfonso@cloud.com"
        },
        {
            "name": "Ali Shakiba",
            "email": "ali@shakiba.me"
        },
        {
            "name": "Antonio D'Ettole",
            "email": "antonio@brandwatch.com"
        },
        {
            "name": "Auclair Emmanuel",
            "email": "auclair.emmanuel.prestataire@sfr.com"
        },
        {
            "name": "Aziz Punjani",
            "email": "aziz.punjani@gmail.com"
        },
        {
            "name": "Ben Brostoff",
            "email": "ben.brostoff@gmail.com"
        },
        {
            "name": "Blaine Bublitz",
            "email": "blaine@iceddev.com"
        },
        {
            "name": "Blake Embrey",
            "email": "hello@blakeembrey.com"
        },
        {
            "name": "Blake Israel",
            "email": "blake.israel@gatech.edu"
        },
        {
            "name": "Boshen Chen",
            "email": "boshenc@gmail.com"
        },
        {
            "name": "Brian M Hunt",
            "email": "brianmhunt@gmail.com"
        },
        {
            "name": "Burak Yiğit Kaya",
            "email": "ben@byk.im"
        },
        {
            "name": "C. T. Lin",
            "email": "chentsulin@gmail.com"
        },
        {
            "name": "Daryl Lau",
            "email": "daryl@goodeggs.com"
        },
        {
            "name": "Duc Tri Le",
            "email": "duc1@email.tiger-inc.com"
        },
        {
            "name": "Eli White",
            "email": "github@eli-white.com"
        },
        {
            "name": "Eric Stobbart",
            "email": "Eric_Stobbart@comcast.com"
        },
        {
            "name": "Eric Wendelin",
            "email": "ewendelin@twitter.com"
        },
        {
            "name": "Ericat",
            "email": "erica.salvaneschi@gmail.com"
        },
        {
            "name": "Gavin Boulton",
            "email": "gavin.boulton@digital.cabinet-office.gov.uk"
        },
        {
            "name": "Gilad Peleg",
            "email": "giladp007@gmail.com"
        },
        {
            "name": "Giorgos Giannoutsos",
            "email": "contact@nuc.gr"
        },
        {
            "name": "Gord Tanner",
            "email": "gord@tinyhippos.com"
        },
        {
            "name": "Gordon L. Hempton",
            "email": "ghempton@gmail.com"
        },
        {
            "name": "Gvozd",
            "email": "gvozdev.viktor@gmail.com"
        },
        {
            "name": "Gyandeep Singh",
            "email": "gyandeeps@gmail.com"
        },
        {
            "name": "Harry Wolff",
            "email": "hswolff@gmail.com"
        },
        {
            "name": "Ian Lewis",
            "email": "IanMLewis@gmail.com"
        },
        {
            "name": "Ian Thomas",
            "email": "ian@ian-thomas.net"
        },
        {
            "name": "Irving",
            "email": "Irvingb232@gmail.com"
        },
        {
            "name": "Jack Brown",
            "email": "jack.brown@mi9.com.au"
        },
        {
            "name": "James Beavers",
            "email": "jamesjbeavers@gmail.com"
        },
        {
            "name": "James M. Greene",
            "email": "james.m.greene@gmail.com"
        },
        {
            "name": "Jan Kopriva",
            "email": "jan.kopriva@gooddata.com"
        },
        {
            "name": "Jan Suchý",
            "email": "jan.sandokan@gmail.com"
        },
        {
            "name": "Jason Anderson",
            "email": "diurnalist@gmail.com"
        },
        {
            "name": "Johann Hubert Sonntagbauer",
            "email": "johann.sonntagbauer@gmx.at"
        },
        {
            "name": "John Bernardo",
            "email": "jbernardo@linkedin.com"
        },
        {
            "name": "Jordan Harband",
            "email": "ljharb@gmail.com"
        },
        {
            "name": "Jordan Hawker",
            "email": "hawker.jordan@gmail.com"
        },
        {
            "name": "Joseph Spens",
            "email": "joseph@workmarket.com"
        },
        {
            "name": "Josh Goldberg",
            "email": "josh@fullscreenmario.com"
        },
        {
            "name": "JoshuaCWebDeveloper",
            "email": "coosriverjoshua1@outlook.com"
        },
        {
            "name": "Kalisa Falzone",
            "email": "KalisaFalzone@users.noreply.github.com"
        },
        {
            "name": "Kelly Selden",
            "email": "kellyselden@gmail.com"
        },
        {
            "name": "Kenneth Williams",
            "email": "scriptdaemon@gmail.com"
        },
        {
            "name": "Kevin Turner",
            "email": "kevin@decipherinc.com"
        },
        {
            "name": "Kim Joar Bekkelund",
            "email": "kjbekkelund@gmail.com"
        },
        {
            "name": "Kris Kowal",
            "email": "kris.kowal@cixar.com"
        },
        {
            "name": "Kurt Ruppel",
            "email": "me@kurtruppel.com"
        },
        {
            "name": "Lars Thorup",
            "email": "lars@zealake.com"
        },
        {
            "name": "LostArchives",
            "email": "valentin.mullet@gmail.com"
        },
        {
            "name": "Lucas Vieira",
            "email": "vieiralucas@users.noreply.github.com"
        },
        {
            "name": "Luchs",
            "email": "Luchs@euirc.eu"
        },
        {
            "name": "Maarten Tromp",
            "email": "maarten@nouncy.com"
        },
        {
            "name": "Marco Ramirez",
            "email": "marco-ramirez@bankofamerica.com"
        },
        {
            "name": "Mario Pareja",
            "email": "mpareja@360incentives.com"
        },
        {
            "name": "Mark Banner",
            "email": "standard8@mozilla.com"
        },
        {
            "name": "Mark Gibson",
            "email": "mgibson@adaptavist.com"
        },
        {
            "name": "Martin Brochhaus",
            "email": "mbrochh@gmail.com"
        },
        {
            "name": "Martin Körner",
            "email": "martin.koerner@objectfab.de"
        },
        {
            "name": "Max Klymyshyn",
            "email": "klymyshyn@gmail.com"
        },
        {
            "name": "Michael Jackson",
            "email": "mjijackson@gmail.com"
        },
        {
            "name": "Michał Perłakowski",
            "email": "michal@perlakowski.pl"
        },
        {
            "name": "Mikolaj Banasik",
            "email": "d1sover@gmail.com"
        },
        {
            "name": "Mustafa Sak",
            "email": "mustafa.sak@1und1.de"
        },
        {
            "name": "Nelson Silva",
            "email": "nelson.silva@inevo.pt"
        },
        {
            "name": "Nicholas Stephan",
            "email": "nicholas.stephan@gmail.com"
        },
        {
            "name": "Nikita Litvin",
            "email": "deltaidea@derpy.ru"
        },
        {
            "name": "Niklas Andreasson",
            "email": "eaglus_@hotmail.com"
        },
        {
            "name": "Olmo Maldonado",
            "email": "olmo.maldonado@gmail.com"
        },
        {
            "name": "Petar Dochev",
            "email": "dotchev@gmail.com"
        },
        {
            "name": "Pia Mancini",
            "email": "piamancini@gmail.com"
        },
        {
            "name": "Prayag Verma",
            "email": "prayag.verma@gmail.com"
        },
        {
            "name": "Rajeesh C V",
            "email": "cvrajeesh@gmail.com"
        },
        {
            "name": "Raynos",
            "email": "raynos2@gmail.com"
        },
        {
            "name": "ReadmeCritic",
            "email": "frankensteinbot@gmail.com"
        },
        {
            "name": "Rodion Vynnychenko",
            "email": "roddiku@gmail.com"
        },
        {
            "name": "Ryan Wholey",
            "email": "rjwholey@gmail.com"
        },
        {
            "name": "STuFF",
            "email": "nchalleil@gmail.com"
        },
        {
            "name": "Sebastian Van Sande",
            "email": "sebastian@vansande.org"
        },
        {
            "name": "Sergio Cinos",
            "email": "scinos@atlassian.com"
        },
        {
            "name": "Shaine Hatch",
            "email": "shainehatch@overstock.com"
        },
        {
            "name": "Shawn Krisman",
            "email": "skrisman@nodelings"
        },
        {
            "name": "Shinnosuke Watanabe",
            "email": "snnskwtnb@gmail.com"
        }
    ],
    "dependencies": {
        "diff": "^3.1.0",
        "formatio": "1.2.0",
        "lolex": "^1.6.0",
        "native-promise-only": "^0.8.1",
        "path-to-regexp": "^1.7.0",
        "samsam": "^1.1.3",
        "text-encoding": "0.6.4",
        "type-detect": "^4.0.0"
    },
    "description": "JavaScript test spies, stubs and mocks.",
    "devDependencies": {
        "browserify": "^14.0.0",
        "eslint": "^3.1.1",
        "eslint-config-sinon": "^1.0.0",
        "eslint-plugin-mocha": "^4.2.0",
        "mocaccino": "^2.0.0",
        "mocha": "^3.1.2",
        "mochify": "^3.0.0",
        "mochify-istanbul": "^2.4.1",
        "phantomic": "^1.4.0",
        "phantomjs-prebuilt": "^2.1.14",
        "pre-commit": "^1.1.2",
        "referee": "^1.2.0",
        "rimraf": "^2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "e057a9d2bf1b32f5d6dd62628ca9ee3961b0cafb",
        "tarball": "https://registry.npmjs.org/sinon/-/sinon-2.1.0.tgz"
    },
    "engines": {
        "node": ">=0.1.103"
    },
    "eslintConfig": {
        "extends": "eslint-config-sinon"
    },
    "files": [
        "lib",
        "pkg",
        "AUTHORS",
        "CONTRIBUTING.md",
        "Changelog.txt",
        "LICENSE",
        "README.md"
    ],
    "gitHead": "9157d41cd95cb29ea1154083787df2406f2b37cc",
    "homepage": "http://sinonjs.org/",
    "license": "BSD-3-Clause",
    "main": "./lib/sinon.js",
    "maintainers": [
        {
            "name": "cjohansen",
            "email": "christian@cjohansen.no"
        },
        {
            "name": "fatso83",
            "email": "carlerik@gmail.com"
        },
        {
            "name": "mantoni",
            "email": "mail@maxantoni.de"
        },
        {
            "name": "mrgnrdrck",
            "email": "morgan@roderick.dk"
        }
    ],
    "name": "sinon",
    "optionalDependencies": {},
    "pre-commit": [
        "eslint-pre-commit"
    ],
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/sinonjs/sinon.git"
    },
    "scripts": {
        "eslint-pre-commit": "./scripts/eslint-pre-commit",
        "lint": "eslint .",
        "postversion": "./scripts/postversion.sh",
        "prepublish": "rimraf pkg && ./build.js",
        "preversion": "./scripts/preversion.sh",
        "test": "npm run test-node && npm run test-headless && npm run test-webworker",
        "test-cloud": "npm run test-headless -- --wd",
        "test-coverage": "mochify --recursive -R dot --grep WebWorker --invert --plugin [ mochify-istanbul --report text --report lcovonly --dir ./coverage ] test/",
        "test-dev": "npm run test-node -- --watch -R min",
        "test-headless": "mochify --recursive -R dot --grep WebWorker --invert test/",
        "test-node": "mocha --recursive -R dot test/",
        "test-webworker": "browserify --no-commondir --full-paths -p [ mocaccino -R spec --color ] test/webworker/webworker-support-assessment.js | phantomic --web-security false"
    },
    "version": "2.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sinon](#apidoc.module.sinon)
1.  [function <span class="apidocSignatureSpan">sinon.</span>CustomEvent ()](#apidoc.element.sinon.CustomEvent)
1.  [function <span class="apidocSignatureSpan">sinon.</span>CustomEvent.prototype.constructor (type, customData, target)](#apidoc.element.sinon.CustomEvent.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">sinon.</span>Event ()](#apidoc.element.sinon.Event)
1.  [function <span class="apidocSignatureSpan">sinon.</span>FakeXMLHttpRequest (config)](#apidoc.element.sinon.FakeXMLHttpRequest)
1.  [function <span class="apidocSignatureSpan">sinon.</span>ProgressEvent ()](#apidoc.element.sinon.ProgressEvent)
1.  [function <span class="apidocSignatureSpan">sinon.</span>ProgressEvent.prototype.constructor (type, progressEventRaw, target)](#apidoc.element.sinon.ProgressEvent.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">sinon.</span>addBehavior (name, fn)](#apidoc.element.sinon.addBehavior)
1.  [function <span class="apidocSignatureSpan">sinon.</span>calledInOrder ()](#apidoc.element.sinon.calledInOrder)
1.  [function <span class="apidocSignatureSpan">sinon.</span>configureLogError ()](#apidoc.element.sinon.configureLogError)
1.  [function <span class="apidocSignatureSpan">sinon.</span>createStubInstance (constructor)](#apidoc.element.sinon.createStubInstance)
1.  [function <span class="apidocSignatureSpan">sinon.</span>deepEqual ()](#apidoc.element.sinon.deepEqual)
1.  [function <span class="apidocSignatureSpan">sinon.</span>every ()](#apidoc.element.sinon.every)
1.  [function <span class="apidocSignatureSpan">sinon.</span>extend ()](#apidoc.element.sinon.extend)
1.  [function <span class="apidocSignatureSpan">sinon.</span>format ()](#apidoc.element.sinon.format)
1.  [function <span class="apidocSignatureSpan">sinon.</span>functionName ()](#apidoc.element.sinon.functionName)
1.  [function <span class="apidocSignatureSpan">sinon.</span>functionToString ()](#apidoc.element.sinon.functionToString)
1.  [function <span class="apidocSignatureSpan">sinon.</span>getConfig ()](#apidoc.element.sinon.getConfig)
1.  [function <span class="apidocSignatureSpan">sinon.</span>getPropertyDescriptor ()](#apidoc.element.sinon.getPropertyDescriptor)
1.  [function <span class="apidocSignatureSpan">sinon.</span>iterableToString ()](#apidoc.element.sinon.iterableToString)
1.  [function <span class="apidocSignatureSpan">sinon.</span>match (expectation, message)](#apidoc.element.sinon.match)
1.  [function <span class="apidocSignatureSpan">sinon.</span>mock (object)](#apidoc.element.sinon.mock)
1.  [function <span class="apidocSignatureSpan">sinon.</span>orderByFirstCall ()](#apidoc.element.sinon.orderByFirstCall)
1.  [function <span class="apidocSignatureSpan">sinon.</span>restore ()](#apidoc.element.sinon.restore)
1.  [function <span class="apidocSignatureSpan">sinon.</span>spy (object, property, types)](#apidoc.element.sinon.spy)
1.  [function <span class="apidocSignatureSpan">sinon.</span>spyCall {{signature}}](#apidoc.element.sinon.spyCall)
1.  [function <span class="apidocSignatureSpan">sinon.</span>stub (object, property, descriptor)](#apidoc.element.sinon.stub)
1.  [function <span class="apidocSignatureSpan">sinon.</span>timesInWords ()](#apidoc.element.sinon.timesInWords)
1.  [function <span class="apidocSignatureSpan">sinon.</span>typeOf ()](#apidoc.element.sinon.typeOf)
1.  [function <span class="apidocSignatureSpan">sinon.</span>useFakeTimers ()](#apidoc.element.sinon.useFakeTimers)
1.  [function <span class="apidocSignatureSpan">sinon.</span>useFakeXMLHttpRequest ()](#apidoc.element.sinon.useFakeXMLHttpRequest)
1.  [function <span class="apidocSignatureSpan">sinon.</span>walk ()](#apidoc.element.sinon.walk)
1.  [function <span class="apidocSignatureSpan">sinon.</span>wrapMethod ()](#apidoc.element.sinon.wrapMethod)
1.  object <span class="apidocSignatureSpan">sinon.</span>CustomEvent.prototype
1.  object <span class="apidocSignatureSpan">sinon.</span>Event.prototype
1.  object <span class="apidocSignatureSpan">sinon.</span>EventTarget
1.  object <span class="apidocSignatureSpan">sinon.</span>FakeXMLHttpRequest.prototype
1.  object <span class="apidocSignatureSpan">sinon.</span>ProgressEvent.prototype
1.  object <span class="apidocSignatureSpan">sinon.</span>assert
1.  object <span class="apidocSignatureSpan">sinon.</span>clock
1.  object <span class="apidocSignatureSpan">sinon.</span>collection
1.  object <span class="apidocSignatureSpan">sinon.</span>defaultConfig
1.  object <span class="apidocSignatureSpan">sinon.</span>expectation
1.  object <span class="apidocSignatureSpan">sinon.</span>fakeServer
1.  object <span class="apidocSignatureSpan">sinon.</span>fakeServerWithClock
1.  object <span class="apidocSignatureSpan">sinon.</span>match.any
1.  object <span class="apidocSignatureSpan">sinon.</span>match.array
1.  object <span class="apidocSignatureSpan">sinon.</span>match.bool
1.  object <span class="apidocSignatureSpan">sinon.</span>match.date
1.  object <span class="apidocSignatureSpan">sinon.</span>match.defined
1.  object <span class="apidocSignatureSpan">sinon.</span>match.falsy
1.  object <span class="apidocSignatureSpan">sinon.</span>match.func
1.  object <span class="apidocSignatureSpan">sinon.</span>match.map
1.  object <span class="apidocSignatureSpan">sinon.</span>match.number
1.  object <span class="apidocSignatureSpan">sinon.</span>match.object
1.  object <span class="apidocSignatureSpan">sinon.</span>match.regexp
1.  object <span class="apidocSignatureSpan">sinon.</span>match.set
1.  object <span class="apidocSignatureSpan">sinon.</span>match.string
1.  object <span class="apidocSignatureSpan">sinon.</span>match.symbol
1.  object <span class="apidocSignatureSpan">sinon.</span>match.truthy
1.  object <span class="apidocSignatureSpan">sinon.</span>sandbox
1.  object <span class="apidocSignatureSpan">sinon.</span>spy.formatters
1.  object <span class="apidocSignatureSpan">sinon.</span>timers
1.  object <span class="apidocSignatureSpan">sinon.</span>xhr

#### [module sinon.CustomEvent](#apidoc.module.sinon.CustomEvent)
1.  [function <span class="apidocSignatureSpan">sinon.</span>CustomEvent ()](#apidoc.element.sinon.CustomEvent.CustomEvent)

#### [module sinon.CustomEvent.prototype](#apidoc.module.sinon.CustomEvent.prototype)
1.  [function <span class="apidocSignatureSpan">sinon.CustomEvent.prototype.</span>constructor (type, customData, target)](#apidoc.element.sinon.CustomEvent.prototype.constructor)

#### [module sinon.CustomEvent.prototype.constructor](#apidoc.module.sinon.CustomEvent.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">sinon.CustomEvent.prototype.</span>constructor ()](#apidoc.element.sinon.CustomEvent.prototype.constructor.constructor)

#### [module sinon.Event](#apidoc.module.sinon.Event)
1.  [function <span class="apidocSignatureSpan">sinon.</span>Event ()](#apidoc.element.sinon.Event.Event)

#### [module sinon.Event.prototype](#apidoc.module.sinon.Event.prototype)
1.  [function <span class="apidocSignatureSpan">sinon.Event.prototype.</span>initEvent (type, bubbles, cancelable, target)](#apidoc.element.sinon.Event.prototype.initEvent)
1.  [function <span class="apidocSignatureSpan">sinon.Event.prototype.</span>preventDefault ()](#apidoc.element.sinon.Event.prototype.preventDefault)
1.  [function <span class="apidocSignatureSpan">sinon.Event.prototype.</span>stopPropagation ()](#apidoc.element.sinon.Event.prototype.stopPropagation)

#### [module sinon.EventTarget](#apidoc.module.sinon.EventTarget)
1.  [function <span class="apidocSignatureSpan">sinon.EventTarget.</span>addEventListener ()](#apidoc.element.sinon.EventTarget.addEventListener)
1.  [function <span class="apidocSignatureSpan">sinon.EventTarget.</span>dispatchEvent ()](#apidoc.element.sinon.EventTarget.dispatchEvent)
1.  [function <span class="apidocSignatureSpan">sinon.EventTarget.</span>removeEventListener ()](#apidoc.element.sinon.EventTarget.removeEventListener)

#### [module sinon.FakeXMLHttpRequest](#apidoc.module.sinon.FakeXMLHttpRequest)
1.  boolean <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>useFilters
1.  [function <span class="apidocSignatureSpan">sinon.</span>FakeXMLHttpRequest (config)](#apidoc.element.sinon.FakeXMLHttpRequest.FakeXMLHttpRequest)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>addFilter (fn)](#apidoc.element.sinon.FakeXMLHttpRequest.addFilter)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>defake (fakeXhr, xhrArgs)](#apidoc.element.sinon.FakeXMLHttpRequest.defake)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>parseXML (text)](#apidoc.element.sinon.FakeXMLHttpRequest.parseXML)
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>DONE
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>HEADERS_RECEIVED
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>LOADING
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>OPENED
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>UNSENT
1.  object <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>filters
1.  object <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>statusCodes

#### [module sinon.FakeXMLHttpRequest.prototype](#apidoc.module.sinon.FakeXMLHttpRequest.prototype)
1.  boolean <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>async
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>abort ()](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.abort)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>addEventListener (event, listener)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.addEventListener)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>dispatchEvent (event)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.dispatchEvent)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>downloadProgress (progressEventRaw)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.downloadProgress)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>error ()](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.error)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>getAllResponseHeaders ()](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.getAllResponseHeaders)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>getResponseHeader (header)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.getResponseHeader)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>open (method, url, async, username, password)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.open)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>overrideMimeType (type)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.overrideMimeType)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>readyStateChange (state)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.readyStateChange)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>removeEventListener (event, listener)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.removeEventListener)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>respond (status, headers, body)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.respond)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>send (data)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.send)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>setRequestHeader (header, value)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.setRequestHeader)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>setResponseBody (body)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.setResponseBody)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>setResponseHeaders (headers)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.setResponseHeaders)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>setStatus (status)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.setStatus)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>uploadError (error)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.uploadError)
1.  [function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>uploadProgress (progressEventRaw)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.uploadProgress)
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>DONE
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>HEADERS_RECEIVED
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>LOADING
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>OPENED
1.  number <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>UNSENT

#### [module sinon.ProgressEvent](#apidoc.module.sinon.ProgressEvent)
1.  [function <span class="apidocSignatureSpan">sinon.</span>ProgressEvent ()](#apidoc.element.sinon.ProgressEvent.ProgressEvent)

#### [module sinon.ProgressEvent.prototype](#apidoc.module.sinon.ProgressEvent.prototype)
1.  [function <span class="apidocSignatureSpan">sinon.ProgressEvent.prototype.</span>constructor (type, progressEventRaw, target)](#apidoc.element.sinon.ProgressEvent.prototype.constructor)

#### [module sinon.ProgressEvent.prototype.constructor](#apidoc.module.sinon.ProgressEvent.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">sinon.ProgressEvent.prototype.</span>constructor ()](#apidoc.element.sinon.ProgressEvent.prototype.constructor.constructor)

#### [module sinon.assert](#apidoc.module.sinon.assert)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledOn (fake)](#apidoc.element.sinon.assert.alwaysCalledOn)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledWith (fake)](#apidoc.element.sinon.assert.alwaysCalledWith)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledWithExactly (fake)](#apidoc.element.sinon.assert.alwaysCalledWithExactly)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledWithMatch (fake)](#apidoc.element.sinon.assert.alwaysCalledWithMatch)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledWithNew (fake)](#apidoc.element.sinon.assert.alwaysCalledWithNew)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysThrew (fake)](#apidoc.element.sinon.assert.alwaysThrew)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>callCount (method, count)](#apidoc.element.sinon.assert.callCount)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>callOrder ()](#apidoc.element.sinon.assert.callOrder)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>called (fake)](#apidoc.element.sinon.assert.called)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>calledOn (fake)](#apidoc.element.sinon.assert.calledOn)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>calledOnce (fake)](#apidoc.element.sinon.assert.calledOnce)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>calledThrice (fake)](#apidoc.element.sinon.assert.calledThrice)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>calledTwice (fake)](#apidoc.element.sinon.assert.calledTwice)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>calledWith (fake)](#apidoc.element.sinon.assert.calledWith)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>calledWithExactly (fake)](#apidoc.element.sinon.assert.calledWithExactly)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>calledWithMatch (fake)](#apidoc.element.sinon.assert.calledWithMatch)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>calledWithNew (fake)](#apidoc.element.sinon.assert.calledWithNew)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>expose (target, options)](#apidoc.element.sinon.assert.expose)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>fail (message)](#apidoc.element.sinon.assert.fail)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>match (actual, expectation)](#apidoc.element.sinon.assert.match)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>neverCalledWith (fake)](#apidoc.element.sinon.assert.neverCalledWith)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>neverCalledWithMatch (fake)](#apidoc.element.sinon.assert.neverCalledWithMatch)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>notCalled (fake)](#apidoc.element.sinon.assert.notCalled)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>pass ()](#apidoc.element.sinon.assert.pass)
1.  [function <span class="apidocSignatureSpan">sinon.assert.</span>threw (fake)](#apidoc.element.sinon.assert.threw)
1.  string <span class="apidocSignatureSpan">sinon.assert.</span>failException

#### [module sinon.clock](#apidoc.module.sinon.clock)
1.  [function <span class="apidocSignatureSpan">sinon.clock.</span>create (now)](#apidoc.element.sinon.clock.create)

#### [module sinon.collection](#apidoc.module.sinon.collection)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>add (fake)](#apidoc.element.sinon.collection.add)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>inject (obj)](#apidoc.element.sinon.collection.inject)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>mock ()](#apidoc.element.sinon.collection.mock)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>reset ()](#apidoc.element.sinon.collection.reset)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>resetBehavior ()](#apidoc.element.sinon.collection.resetBehavior)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>resetHistory ()](#apidoc.element.sinon.collection.resetHistory)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>restore ()](#apidoc.element.sinon.collection.restore)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>spy ()](#apidoc.element.sinon.collection.spy)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>stub (object, property)](#apidoc.element.sinon.collection.stub)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>verify ()](#apidoc.element.sinon.collection.verify)
1.  [function <span class="apidocSignatureSpan">sinon.collection.</span>verifyAndRestore ()](#apidoc.element.sinon.collection.verifyAndRestore)

#### [module sinon.expectation](#apidoc.module.sinon.expectation)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>allowsCall (thisValue, args)](#apidoc.element.sinon.expectation.allowsCall)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>atLeast (num)](#apidoc.element.sinon.expectation.atLeast)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>atMost (num)](#apidoc.element.sinon.expectation.atMost)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>create (methodName)](#apidoc.element.sinon.expectation.create)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>exactly (num)](#apidoc.element.sinon.expectation.exactly)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>fail (message)](#apidoc.element.sinon.expectation.fail)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>invoke (func, thisValue, args)](#apidoc.element.sinon.expectation.invoke)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>met ()](#apidoc.element.sinon.expectation.met)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>never ()](#apidoc.element.sinon.expectation.never)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>on (thisValue)](#apidoc.element.sinon.expectation.on)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>once ()](#apidoc.element.sinon.expectation.once)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>pass (message)](#apidoc.element.sinon.expectation.pass)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>thrice ()](#apidoc.element.sinon.expectation.thrice)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>toString ()](#apidoc.element.sinon.expectation.toString)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>twice ()](#apidoc.element.sinon.expectation.twice)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>verify ()](#apidoc.element.sinon.expectation.verify)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>verifyCallAllowed (thisValue, args)](#apidoc.element.sinon.expectation.verifyCallAllowed)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>withArgs ()](#apidoc.element.sinon.expectation.withArgs)
1.  [function <span class="apidocSignatureSpan">sinon.expectation.</span>withExactArgs ()](#apidoc.element.sinon.expectation.withExactArgs)
1.  number <span class="apidocSignatureSpan">sinon.expectation.</span>maxCalls
1.  number <span class="apidocSignatureSpan">sinon.expectation.</span>minCalls

#### [module sinon.fakeServer](#apidoc.module.sinon.fakeServer)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>addRequest (xhrObj)](#apidoc.element.sinon.fakeServer.addRequest)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>configure (config)](#apidoc.element.sinon.fakeServer.configure)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>create (config)](#apidoc.element.sinon.fakeServer.create)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>getHTTPMethod (request)](#apidoc.element.sinon.fakeServer.getHTTPMethod)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>getRequest (index)](#apidoc.element.sinon.fakeServer.getRequest)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>handleRequest (xhr)](#apidoc.element.sinon.fakeServer.handleRequest)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>log (response, request)](#apidoc.element.sinon.fakeServer.log)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>logError (label, e)](#apidoc.element.sinon.fakeServer.logError)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>logger ()](#apidoc.element.sinon.fakeServer.logger)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>processRequest (request)](#apidoc.element.sinon.fakeServer.processRequest)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>reset ()](#apidoc.element.sinon.fakeServer.reset)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>resetBehavior ()](#apidoc.element.sinon.fakeServer.resetBehavior)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>resetHistory ()](#apidoc.element.sinon.fakeServer.resetHistory)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>respond ()](#apidoc.element.sinon.fakeServer.respond)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>respondWith (method, url, body)](#apidoc.element.sinon.fakeServer.respondWith)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServer.</span>restore ()](#apidoc.element.sinon.fakeServer.restore)

#### [module sinon.fakeServerWithClock](#apidoc.module.sinon.fakeServerWithClock)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServerWithClock.</span>addRequest (xhr)](#apidoc.element.sinon.fakeServerWithClock.addRequest)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServerWithClock.</span>respond ()](#apidoc.element.sinon.fakeServerWithClock.respond)
1.  [function <span class="apidocSignatureSpan">sinon.fakeServerWithClock.</span>restore ()](#apidoc.element.sinon.fakeServerWithClock.restore)

#### [module sinon.match](#apidoc.module.sinon.match)
1.  [function <span class="apidocSignatureSpan">sinon.</span>match (expectation, message)](#apidoc.element.sinon.match.match)
1.  [function <span class="apidocSignatureSpan">sinon.match.</span>has (property, value)](#apidoc.element.sinon.match.has)
1.  [function <span class="apidocSignatureSpan">sinon.match.</span>hasOwn (property, value)](#apidoc.element.sinon.match.hasOwn)
1.  [function <span class="apidocSignatureSpan">sinon.match.</span>instanceOf (type)](#apidoc.element.sinon.match.instanceOf)
1.  [function <span class="apidocSignatureSpan">sinon.match.</span>isMatcher (object)](#apidoc.element.sinon.match.isMatcher)
1.  [function <span class="apidocSignatureSpan">sinon.match.</span>same (expectation)](#apidoc.element.sinon.match.same)
1.  [function <span class="apidocSignatureSpan">sinon.match.</span>typeOf (type)](#apidoc.element.sinon.match.typeOf)
1.  object <span class="apidocSignatureSpan">sinon.match.</span>any
1.  object <span class="apidocSignatureSpan">sinon.match.</span>array
1.  object <span class="apidocSignatureSpan">sinon.match.</span>bool
1.  object <span class="apidocSignatureSpan">sinon.match.</span>date
1.  object <span class="apidocSignatureSpan">sinon.match.</span>defined
1.  object <span class="apidocSignatureSpan">sinon.match.</span>falsy
1.  object <span class="apidocSignatureSpan">sinon.match.</span>func
1.  object <span class="apidocSignatureSpan">sinon.match.</span>map
1.  object <span class="apidocSignatureSpan">sinon.match.</span>number
1.  object <span class="apidocSignatureSpan">sinon.match.</span>object
1.  object <span class="apidocSignatureSpan">sinon.match.</span>regexp
1.  object <span class="apidocSignatureSpan">sinon.match.</span>set
1.  object <span class="apidocSignatureSpan">sinon.match.</span>string
1.  object <span class="apidocSignatureSpan">sinon.match.</span>symbol
1.  object <span class="apidocSignatureSpan">sinon.match.</span>truthy

#### [module sinon.match.any](#apidoc.module.sinon.match.any)
1.  [function <span class="apidocSignatureSpan">sinon.match.any.</span>test ()](#apidoc.element.sinon.match.any.test)
1.  string <span class="apidocSignatureSpan">sinon.match.any.</span>message

#### [module sinon.match.array](#apidoc.module.sinon.match.array)
1.  [function <span class="apidocSignatureSpan">sinon.match.array.</span>contains (expectation)](#apidoc.element.sinon.match.array.contains)
1.  [function <span class="apidocSignatureSpan">sinon.match.array.</span>deepEquals (expectation)](#apidoc.element.sinon.match.array.deepEquals)
1.  [function <span class="apidocSignatureSpan">sinon.match.array.</span>endsWith (expectation)](#apidoc.element.sinon.match.array.endsWith)
1.  [function <span class="apidocSignatureSpan">sinon.match.array.</span>startsWith (expectation)](#apidoc.element.sinon.match.array.startsWith)
1.  [function <span class="apidocSignatureSpan">sinon.match.array.</span>test (actual)](#apidoc.element.sinon.match.array.test)
1.  string <span class="apidocSignatureSpan">sinon.match.array.</span>message

#### [module sinon.match.bool](#apidoc.module.sinon.match.bool)
1.  [function <span class="apidocSignatureSpan">sinon.match.bool.</span>test (actual)](#apidoc.element.sinon.match.bool.test)
1.  string <span class="apidocSignatureSpan">sinon.match.bool.</span>message

#### [module sinon.match.date](#apidoc.module.sinon.match.date)
1.  [function <span class="apidocSignatureSpan">sinon.match.date.</span>test (actual)](#apidoc.element.sinon.match.date.test)
1.  string <span class="apidocSignatureSpan">sinon.match.date.</span>message

#### [module sinon.match.defined](#apidoc.module.sinon.match.defined)
1.  [function <span class="apidocSignatureSpan">sinon.match.defined.</span>test (actual)](#apidoc.element.sinon.match.defined.test)
1.  string <span class="apidocSignatureSpan">sinon.match.defined.</span>message

#### [module sinon.match.falsy](#apidoc.module.sinon.match.falsy)
1.  [function <span class="apidocSignatureSpan">sinon.match.falsy.</span>test (actual)](#apidoc.element.sinon.match.falsy.test)
1.  string <span class="apidocSignatureSpan">sinon.match.falsy.</span>message

#### [module sinon.match.func](#apidoc.module.sinon.match.func)
1.  [function <span class="apidocSignatureSpan">sinon.match.func.</span>test (actual)](#apidoc.element.sinon.match.func.test)
1.  string <span class="apidocSignatureSpan">sinon.match.func.</span>message

#### [module sinon.match.map](#apidoc.module.sinon.match.map)
1.  [function <span class="apidocSignatureSpan">sinon.match.map.</span>contains (expectation)](#apidoc.element.sinon.match.map.contains)
1.  [function <span class="apidocSignatureSpan">sinon.match.map.</span>deepEquals (expectation)](#apidoc.element.sinon.match.map.deepEquals)
1.  [function <span class="apidocSignatureSpan">sinon.match.map.</span>test (actual)](#apidoc.element.sinon.match.map.test)
1.  string <span class="apidocSignatureSpan">sinon.match.map.</span>message

#### [module sinon.match.number](#apidoc.module.sinon.match.number)
1.  [function <span class="apidocSignatureSpan">sinon.match.number.</span>test (actual)](#apidoc.element.sinon.match.number.test)
1.  string <span class="apidocSignatureSpan">sinon.match.number.</span>message

#### [module sinon.match.object](#apidoc.module.sinon.match.object)
1.  [function <span class="apidocSignatureSpan">sinon.match.object.</span>test (actual)](#apidoc.element.sinon.match.object.test)
1.  string <span class="apidocSignatureSpan">sinon.match.object.</span>message

#### [module sinon.match.regexp](#apidoc.module.sinon.match.regexp)
1.  [function <span class="apidocSignatureSpan">sinon.match.regexp.</span>test (actual)](#apidoc.element.sinon.match.regexp.test)
1.  string <span class="apidocSignatureSpan">sinon.match.regexp.</span>message

#### [module sinon.match.set](#apidoc.module.sinon.match.set)
1.  [function <span class="apidocSignatureSpan">sinon.match.set.</span>contains (expectation)](#apidoc.element.sinon.match.set.contains)
1.  [function <span class="apidocSignatureSpan">sinon.match.set.</span>deepEquals (expectation)](#apidoc.element.sinon.match.set.deepEquals)
1.  [function <span class="apidocSignatureSpan">sinon.match.set.</span>test (actual)](#apidoc.element.sinon.match.set.test)
1.  string <span class="apidocSignatureSpan">sinon.match.set.</span>message

#### [module sinon.match.string](#apidoc.module.sinon.match.string)
1.  [function <span class="apidocSignatureSpan">sinon.match.string.</span>test (actual)](#apidoc.element.sinon.match.string.test)
1.  string <span class="apidocSignatureSpan">sinon.match.string.</span>message

#### [module sinon.match.symbol](#apidoc.module.sinon.match.symbol)
1.  [function <span class="apidocSignatureSpan">sinon.match.symbol.</span>test (actual)](#apidoc.element.sinon.match.symbol.test)
1.  string <span class="apidocSignatureSpan">sinon.match.symbol.</span>message

#### [module sinon.match.truthy](#apidoc.module.sinon.match.truthy)
1.  [function <span class="apidocSignatureSpan">sinon.match.truthy.</span>test (actual)](#apidoc.element.sinon.match.truthy.test)
1.  string <span class="apidocSignatureSpan">sinon.match.truthy.</span>message

#### [module sinon.mock](#apidoc.module.sinon.mock)
1.  [function <span class="apidocSignatureSpan">sinon.</span>mock (object)](#apidoc.element.sinon.mock.mock)
1.  [function <span class="apidocSignatureSpan">sinon.mock.</span>create (object)](#apidoc.element.sinon.mock.create)
1.  [function <span class="apidocSignatureSpan">sinon.mock.</span>expects (method)](#apidoc.element.sinon.mock.expects)
1.  [function <span class="apidocSignatureSpan">sinon.mock.</span>invokeMethod (method, thisValue, args)](#apidoc.element.sinon.mock.invokeMethod)
1.  [function <span class="apidocSignatureSpan">sinon.mock.</span>restore ()](#apidoc.element.sinon.mock.restore)
1.  [function <span class="apidocSignatureSpan">sinon.mock.</span>verify ()](#apidoc.element.sinon.mock.verify)

#### [module sinon.sandbox](#apidoc.module.sinon.sandbox)
1.  [function <span class="apidocSignatureSpan">sinon.sandbox.</span>create (config)](#apidoc.element.sinon.sandbox.create)
1.  [function <span class="apidocSignatureSpan">sinon.sandbox.</span>inject (obj)](#apidoc.element.sinon.sandbox.inject)
1.  [function <span class="apidocSignatureSpan">sinon.sandbox.</span>match (expectation, message)](#apidoc.element.sinon.sandbox.match)
1.  [function <span class="apidocSignatureSpan">sinon.sandbox.</span>restore ()](#apidoc.element.sinon.sandbox.restore)
1.  [function <span class="apidocSignatureSpan">sinon.sandbox.</span>restoreContext ()](#apidoc.element.sinon.sandbox.restoreContext)
1.  [function <span class="apidocSignatureSpan">sinon.sandbox.</span>useFakeServer ()](#apidoc.element.sinon.sandbox.useFakeServer)
1.  [function <span class="apidocSignatureSpan">sinon.sandbox.</span>useFakeTimers ()](#apidoc.element.sinon.sandbox.useFakeTimers)
1.  [function <span class="apidocSignatureSpan">sinon.sandbox.</span>useFakeXMLHttpRequest ()](#apidoc.element.sinon.sandbox.useFakeXMLHttpRequest)
1.  object <span class="apidocSignatureSpan">sinon.sandbox.</span>assert
1.  object <span class="apidocSignatureSpan">sinon.sandbox.</span>serverPrototype

#### [module sinon.spy](#apidoc.module.sinon.spy)
1.  [function <span class="apidocSignatureSpan">sinon.</span>spy (object, property, types)](#apidoc.element.sinon.spy.spy)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledOn ()](#apidoc.element.sinon.spy.alwaysCalledOn)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledWith ()](#apidoc.element.sinon.spy.alwaysCalledWith)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledWithExactly ()](#apidoc.element.sinon.spy.alwaysCalledWithExactly)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledWithMatch ()](#apidoc.element.sinon.spy.alwaysCalledWithMatch)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledWithNew ()](#apidoc.element.sinon.spy.alwaysCalledWithNew)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysReturned ()](#apidoc.element.sinon.spy.alwaysReturned)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysThrew ()](#apidoc.element.sinon.spy.alwaysThrew)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>callArg ()](#apidoc.element.sinon.spy.callArg)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>callArgOn ()](#apidoc.element.sinon.spy.callArgOn)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>callArgOnWith ()](#apidoc.element.sinon.spy.callArgOnWith)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>callArgWith ()](#apidoc.element.sinon.spy.callArgWith)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledAfter (spyFn)](#apidoc.element.sinon.spy.calledAfter)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledBefore (spyFn)](#apidoc.element.sinon.spy.calledBefore)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledImmediatelyAfter (spyFn)](#apidoc.element.sinon.spy.calledImmediatelyAfter)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledImmediatelyBefore (spyFn)](#apidoc.element.sinon.spy.calledImmediatelyBefore)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledOn ()](#apidoc.element.sinon.spy.calledOn)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledWith ()](#apidoc.element.sinon.spy.calledWith)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledWithExactly ()](#apidoc.element.sinon.spy.calledWithExactly)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledWithMatch ()](#apidoc.element.sinon.spy.calledWithMatch)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>calledWithNew ()](#apidoc.element.sinon.spy.calledWithNew)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>create (func, spyLength)](#apidoc.element.sinon.spy.create)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>getCall (i)](#apidoc.element.sinon.spy.getCall)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>getCalls ()](#apidoc.element.sinon.spy.getCalls)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>invoke (func, thisValue, args)](#apidoc.element.sinon.spy.invoke)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>invokeCallback ()](#apidoc.element.sinon.spy.invokeCallback)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>matches (args, strict)](#apidoc.element.sinon.spy.matches)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>named (name)](#apidoc.element.sinon.spy.named)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>neverCalledWith ()](#apidoc.element.sinon.spy.neverCalledWith)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>neverCalledWithMatch ()](#apidoc.element.sinon.spy.neverCalledWithMatch)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>printf (format)](#apidoc.element.sinon.spy.printf)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>reset ()](#apidoc.element.sinon.spy.reset)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>returned ()](#apidoc.element.sinon.spy.returned)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>spyCall {{signature}}](#apidoc.element.sinon.spy.spyCall)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>threw ()](#apidoc.element.sinon.spy.threw)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>withArgs ()](#apidoc.element.sinon.spy.withArgs)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>yield ()](#apidoc.element.sinon.spy.yield)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>yieldOn ()](#apidoc.element.sinon.spy.yieldOn)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>yieldTo ()](#apidoc.element.sinon.spy.yieldTo)
1.  [function <span class="apidocSignatureSpan">sinon.spy.</span>yieldToOn ()](#apidoc.element.sinon.spy.yieldToOn)
1.  object <span class="apidocSignatureSpan">sinon.spy.</span>formatters

#### [module sinon.spy.formatters](#apidoc.module.sinon.spy.formatters)
1.  [function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>C (spyInstance)](#apidoc.element.sinon.spy.formatters.C)
1.  [function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>D (spyInstance, args)](#apidoc.element.sinon.spy.formatters.D)
1.  [function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>c (spyInstance)](#apidoc.element.sinon.spy.formatters.c)
1.  [function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>n (spyInstance)](#apidoc.element.sinon.spy.formatters.n)
1.  [function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>t (spyInstance)](#apidoc.element.sinon.spy.formatters.t)

#### [module sinon.spyCall](#apidoc.module.sinon.spyCall)
1.  [function <span class="apidocSignatureSpan">sinon.</span>spyCall {{signature}}](#apidoc.element.sinon.spyCall.spyCall)
1.  [function <span class="apidocSignatureSpan">sinon.spyCall.</span>toString ()](#apidoc.element.sinon.spyCall.toString)

#### [module sinon.stub](#apidoc.module.sinon.stub)
1.  [function <span class="apidocSignatureSpan">sinon.</span>stub (object, property, descriptor)](#apidoc.element.sinon.stub.stub)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>addBehavior ()](#apidoc.element.sinon.stub.addBehavior)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callThrough ()](#apidoc.element.sinon.stub.callThrough)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsArg ()](#apidoc.element.sinon.stub.callsArg)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgAsync ()](#apidoc.element.sinon.stub.callsArgAsync)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgOn ()](#apidoc.element.sinon.stub.callsArgOn)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgOnAsync ()](#apidoc.element.sinon.stub.callsArgOnAsync)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgOnWith ()](#apidoc.element.sinon.stub.callsArgOnWith)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgOnWithAsync ()](#apidoc.element.sinon.stub.callsArgOnWithAsync)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgWith ()](#apidoc.element.sinon.stub.callsArgWith)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgWithAsync ()](#apidoc.element.sinon.stub.callsArgWithAsync)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>callsFake ()](#apidoc.element.sinon.stub.callsFake)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>create (stubLength)](#apidoc.element.sinon.stub.create)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>createBehavior ()](#apidoc.element.sinon.stub.createBehavior)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>createStubInstance (constructor)](#apidoc.element.sinon.stub.createStubInstance)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>get ()](#apidoc.element.sinon.stub.get)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>isPresent ()](#apidoc.element.sinon.stub.isPresent)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>onCall (index)](#apidoc.element.sinon.stub.onCall)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>onFirstCall ()](#apidoc.element.sinon.stub.onFirstCall)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>onSecondCall ()](#apidoc.element.sinon.stub.onSecondCall)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>onThirdCall ()](#apidoc.element.sinon.stub.onThirdCall)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>rejects ()](#apidoc.element.sinon.stub.rejects)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>reset ()](#apidoc.element.sinon.stub.reset)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>resetBehavior ()](#apidoc.element.sinon.stub.resetBehavior)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>resetHistory ()](#apidoc.element.sinon.stub.resetHistory)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>resolves ()](#apidoc.element.sinon.stub.resolves)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>returns ()](#apidoc.element.sinon.stub.returns)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>returnsArg ()](#apidoc.element.sinon.stub.returnsArg)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>returnsThis ()](#apidoc.element.sinon.stub.returnsThis)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>set ()](#apidoc.element.sinon.stub.set)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>throws ()](#apidoc.element.sinon.stub.throws)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>throwsException ()](#apidoc.element.sinon.stub.throwsException)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yields ()](#apidoc.element.sinon.stub.yields)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsAsync ()](#apidoc.element.sinon.stub.yieldsAsync)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsOn ()](#apidoc.element.sinon.stub.yieldsOn)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsOnAsync ()](#apidoc.element.sinon.stub.yieldsOnAsync)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsRight ()](#apidoc.element.sinon.stub.yieldsRight)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsRightAsync ()](#apidoc.element.sinon.stub.yieldsRightAsync)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsTo ()](#apidoc.element.sinon.stub.yieldsTo)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsToAsync ()](#apidoc.element.sinon.stub.yieldsToAsync)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsToOn ()](#apidoc.element.sinon.stub.yieldsToOn)
1.  [function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsToOnAsync ()](#apidoc.element.sinon.stub.yieldsToOnAsync)

#### [module sinon.timers](#apidoc.module.sinon.timers)
1.  [function <span class="apidocSignatureSpan">sinon.timers.</span>Date ()](#apidoc.element.sinon.timers.Date)
1.  [function <span class="apidocSignatureSpan">sinon.timers.</span>clearImmediate (immediate)](#apidoc.element.sinon.timers.clearImmediate)
1.  [function <span class="apidocSignatureSpan">sinon.timers.</span>clearInterval (timer)](#apidoc.element.sinon.timers.clearInterval)
1.  [function <span class="apidocSignatureSpan">sinon.timers.</span>clearTimeout (timer)](#apidoc.element.sinon.timers.clearTimeout)
1.  [function <span class="apidocSignatureSpan">sinon.timers.</span>setImmediate (callback, arg1, arg2, arg3)](#apidoc.element.sinon.timers.setImmediate)
1.  [function <span class="apidocSignatureSpan">sinon.timers.</span>setInterval (callback, repeat, arg1, arg2, arg3)](#apidoc.element.sinon.timers.setInterval)
1.  [function <span class="apidocSignatureSpan">sinon.timers.</span>setTimeout (callback, after, arg1, arg2, arg3)](#apidoc.element.sinon.timers.setTimeout)



# <a name="apidoc.module.sinon"></a>[module sinon](#apidoc.module.sinon)

#### <a name="apidoc.element.sinon.CustomEvent"></a>[function <span class="apidocSignatureSpan">sinon.</span>CustomEvent ()](#apidoc.element.sinon.CustomEvent)
- description and source-code
```javascript
CustomEvent = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.CustomEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">sinon.</span>CustomEvent.prototype.constructor (type, customData, target)](#apidoc.element.sinon.CustomEvent.prototype.constructor)
- description and source-code
```javascript
function CustomEvent(type, customData, target) {
    this.initEvent(type, false, false, target);
    this.detail = customData.detail || null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.Event"></a>[function <span class="apidocSignatureSpan">sinon.</span>Event ()](#apidoc.element.sinon.Event)
- description and source-code
```javascript
Event = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest"></a>[function <span class="apidocSignatureSpan">sinon.</span>FakeXMLHttpRequest (config)](#apidoc.element.sinon.FakeXMLHttpRequest)
- description and source-code
```javascript
function FakeXMLHttpRequest(config) {
    EventTargetHandler.call(this);
    this.readyState = FakeXMLHttpRequest.UNSENT;
    this.requestHeaders = {};
    this.requestBody = null;
    this.status = 0;
    this.statusText = "";
    this.upload = new EventTargetHandler();
    this.responseType = "";
    this.response = "";
    this.logError = configureLogError(config);
    if (sinonXhr.supportsCORS) {
        this.withCredentials = false;
    }

    if (typeof FakeXMLHttpRequest.onCreate === "function") {
        FakeXMLHttpRequest.onCreate(this);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.ProgressEvent"></a>[function <span class="apidocSignatureSpan">sinon.</span>ProgressEvent ()](#apidoc.element.sinon.ProgressEvent)
- description and source-code
```javascript
ProgressEvent = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.ProgressEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">sinon.</span>ProgressEvent.prototype.constructor (type, progressEventRaw, target)](#apidoc.element.sinon.ProgressEvent.prototype.constructor)
- description and source-code
```javascript
function ProgressEvent(type, progressEventRaw, target) {
    this.initEvent(type, false, false, target);
    this.loaded = typeof progressEventRaw.loaded === "number" ? progressEventRaw.loaded : null;
    this.total = typeof progressEventRaw.total === "number" ? progressEventRaw.total : null;
    this.lengthComputable = !!progressEventRaw.total;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.addBehavior"></a>[function <span class="apidocSignatureSpan">sinon.</span>addBehavior (name, fn)](#apidoc.element.sinon.addBehavior)
- description and source-code
```javascript
addBehavior = function (name, fn) {
    behavior.addBehavior(exports.stub, name, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.calledInOrder"></a>[function <span class="apidocSignatureSpan">sinon.</span>calledInOrder ()](#apidoc.element.sinon.calledInOrder)
- description and source-code
```javascript
calledInOrder = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.configureLogError"></a>[function <span class="apidocSignatureSpan">sinon.</span>configureLogError ()](#apidoc.element.sinon.configureLogError)
- description and source-code
```javascript
configureLogError = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.createStubInstance"></a>[function <span class="apidocSignatureSpan">sinon.</span>createStubInstance (constructor)](#apidoc.element.sinon.createStubInstance)
- description and source-code
```javascript
createStubInstance = function (constructor) {
    if (typeof constructor !== "function") {
        throw new TypeError("The constructor should be a function.");
    }
    return stub(Object.create(constructor.prototype));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.deepEqual"></a>[function <span class="apidocSignatureSpan">sinon.</span>deepEqual ()](#apidoc.element.sinon.deepEqual)
- description and source-code
```javascript
deepEqual = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.every"></a>[function <span class="apidocSignatureSpan">sinon.</span>every ()](#apidoc.element.sinon.every)
- description and source-code
```javascript
every = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.extend"></a>[function <span class="apidocSignatureSpan">sinon.</span>extend ()](#apidoc.element.sinon.extend)
- description and source-code
```javascript
extend = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.format"></a>[function <span class="apidocSignatureSpan">sinon.</span>format ()](#apidoc.element.sinon.format)
- description and source-code
```javascript
format = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.functionName"></a>[function <span class="apidocSignatureSpan">sinon.</span>functionName ()](#apidoc.element.sinon.functionName)
- description and source-code
```javascript
functionName = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.functionToString"></a>[function <span class="apidocSignatureSpan">sinon.</span>functionToString ()](#apidoc.element.sinon.functionToString)
- description and source-code
```javascript
functionToString = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.getConfig"></a>[function <span class="apidocSignatureSpan">sinon.</span>getConfig ()](#apidoc.element.sinon.getConfig)
- description and source-code
```javascript
getConfig = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.getPropertyDescriptor"></a>[function <span class="apidocSignatureSpan">sinon.</span>getPropertyDescriptor ()](#apidoc.element.sinon.getPropertyDescriptor)
- description and source-code
```javascript
getPropertyDescriptor = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.iterableToString"></a>[function <span class="apidocSignatureSpan">sinon.</span>iterableToString ()](#apidoc.element.sinon.iterableToString)
- description and source-code
```javascript
iterableToString = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match"></a>[function <span class="apidocSignatureSpan">sinon.</span>match (expectation, message)](#apidoc.element.sinon.match)
- description and source-code
```javascript
function match(expectation, message) {
    var m = Object.create(matcher);
    var type = typeOf(expectation);

    if (type in TYPE_MAP) {
        TYPE_MAP[type](m, expectation, message);
    } else {
        m.test = function (actual) {
            return deepEqual(expectation, actual);
        };
    }

    if (!m.message) {
        m.message = "match(" + valueToString(expectation) + ")";
    }

    return m;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.mock"></a>[function <span class="apidocSignatureSpan">sinon.</span>mock (object)](#apidoc.element.sinon.mock)
- description and source-code
```javascript
function mock(object) {
    if (!object) {
        return mockExpectation.create("Anonymous mock");
    }

    return mock.create(object);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.orderByFirstCall"></a>[function <span class="apidocSignatureSpan">sinon.</span>orderByFirstCall ()](#apidoc.element.sinon.orderByFirstCall)
- description and source-code
```javascript
orderByFirstCall = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.restore"></a>[function <span class="apidocSignatureSpan">sinon.</span>restore ()](#apidoc.element.sinon.restore)
- description and source-code
```javascript
restore = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy"></a>[function <span class="apidocSignatureSpan">sinon.</span>spy (object, property, types)](#apidoc.element.sinon.spy)
- description and source-code
```javascript
function spy(object, property, types) {
    var descriptor, methodDesc;

    if (!property && typeof object === "function") {
        return spy.create(object);
    }

    if (!object && !property) {
        return spy.create(function () { });
    }

    if (!types) {
        return wrapMethod(object, property, spy.create(object[property]));
    }

    descriptor = {};
    methodDesc = getPropertyDescriptor(object, property);

    types.forEach(function (type) {
        descriptor[type] = spy.create(methodDesc[type]);
    });

    return wrapMethod(object, property, descriptor);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spyCall"></a>[function <span class="apidocSignatureSpan">sinon.</span>spyCall {{signature}}](#apidoc.element.sinon.spyCall)
- description and source-code
```javascript
:(
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub"></a>[function <span class="apidocSignatureSpan">sinon.</span>stub (object, property, descriptor)](#apidoc.element.sinon.stub)
- description and source-code
```javascript
function stub(object, property, descriptor) {
    throwOnFalsyObject.apply(null, arguments);

    var actualDescriptor = getPropertyDescriptor(object, property);
    var isStubbingEntireObject = typeof property === "undefined" && typeof object === "object";
    var isCreatingNewStub = !object && typeof property === "undefined";
    var isStubbingDescriptor = object && property && Boolean(descriptor);
    var isStubbingNonFuncProperty = typeof object === "object"
                                    && typeof property !== "undefined"
                                    && (typeof actualDescriptor === "undefined"
                                    || typeof actualDescriptor.value !== "function")
                                    && typeof descriptor === "undefined";
    var isStubbingExistingMethod = !isStubbingDescriptor
                                    && typeof object === "object"
                                    && typeof actualDescriptor !== "undefined"
                                    && typeof actualDescriptor.value === "function";
    var arity = isStubbingExistingMethod ? object[property].length : 0;

    if (isStubbingEntireObject) {
        return stubEntireObject(stub, object);
    }

    if (isStubbingDescriptor) {
        return stubDescriptor.apply(null, arguments);
    }

    if (isCreatingNewStub) {
        return stub.create();
    }

    var s = stub.create(arity);
    s.rootObj = object;
    s.propName = property;
    s.restore = function restore() {
        Object.defineProperty(object, property, actualDescriptor);
    };

    return isStubbingNonFuncProperty ? s : wrapMethod(object, property, s);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.timesInWords"></a>[function <span class="apidocSignatureSpan">sinon.</span>timesInWords ()](#apidoc.element.sinon.timesInWords)
- description and source-code
```javascript
timesInWords = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.typeOf"></a>[function <span class="apidocSignatureSpan">sinon.</span>typeOf ()](#apidoc.element.sinon.typeOf)
- description and source-code
```javascript
typeOf = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.useFakeTimers"></a>[function <span class="apidocSignatureSpan">sinon.</span>useFakeTimers ()](#apidoc.element.sinon.useFakeTimers)
- description and source-code
```javascript
useFakeTimers = function () {
    var now;
    var methods = Array.prototype.slice.call(arguments);

    if (typeof methods[0] === "string") {
        now = 0;
    } else {
        now = methods.shift();
    }

    var clock = llx.install(now || 0, methods);
    clock.restore = clock.uninstall;
    return clock;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.useFakeXMLHttpRequest"></a>[function <span class="apidocSignatureSpan">sinon.</span>useFakeXMLHttpRequest ()](#apidoc.element.sinon.useFakeXMLHttpRequest)
- description and source-code
```javascript
function useFakeXMLHttpRequest() {
    FakeXMLHttpRequest.restore = function restore(keepOnCreate) {
        if (sinonXhr.supportsXHR) {
            global.XMLHttpRequest = sinonXhr.GlobalXMLHttpRequest;
        }

        if (sinonXhr.supportsActiveX) {
            global.ActiveXObject = sinonXhr.GlobalActiveXObject;
        }

        delete FakeXMLHttpRequest.restore;

        if (keepOnCreate !== true) {
            delete FakeXMLHttpRequest.onCreate;
        }
    };
    if (sinonXhr.supportsXHR) {
        global.XMLHttpRequest = FakeXMLHttpRequest;
    }

    if (sinonXhr.supportsActiveX) {
        global.ActiveXObject = function ActiveXObject(objId) {
            if (objId === "Microsoft.XMLHTTP" || /^Msxml2\.XMLHTTP/i.test(objId)) {

                return new FakeXMLHttpRequest();
            }

            return new sinonXhr.GlobalActiveXObject(objId);
        };
    }

    return FakeXMLHttpRequest;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.walk"></a>[function <span class="apidocSignatureSpan">sinon.</span>walk ()](#apidoc.element.sinon.walk)
- description and source-code
```javascript
walk = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.wrapMethod"></a>[function <span class="apidocSignatureSpan">sinon.</span>wrapMethod ()](#apidoc.element.sinon.wrapMethod)
- description and source-code
```javascript
wrapMethod = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.CustomEvent"></a>[module sinon.CustomEvent](#apidoc.module.sinon.CustomEvent)

#### <a name="apidoc.element.sinon.CustomEvent.CustomEvent"></a>[function <span class="apidocSignatureSpan">sinon.</span>CustomEvent ()](#apidoc.element.sinon.CustomEvent.CustomEvent)
- description and source-code
```javascript
CustomEvent = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.CustomEvent.prototype"></a>[module sinon.CustomEvent.prototype](#apidoc.module.sinon.CustomEvent.prototype)

#### <a name="apidoc.element.sinon.CustomEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">sinon.CustomEvent.prototype.</span>constructor (type, customData, target)](#apidoc.element.sinon.CustomEvent.prototype.constructor)
- description and source-code
```javascript
function CustomEvent(type, customData, target) {
    this.initEvent(type, false, false, target);
    this.detail = customData.detail || null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.CustomEvent.prototype.constructor"></a>[module sinon.CustomEvent.prototype.constructor](#apidoc.module.sinon.CustomEvent.prototype.constructor)

#### <a name="apidoc.element.sinon.CustomEvent.prototype.constructor.constructor"></a>[function <span class="apidocSignatureSpan">sinon.CustomEvent.prototype.</span>constructor ()](#apidoc.element.sinon.CustomEvent.prototype.constructor.constructor)
- description and source-code
```javascript
function Function() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.Event"></a>[module sinon.Event](#apidoc.module.sinon.Event)

#### <a name="apidoc.element.sinon.Event.Event"></a>[function <span class="apidocSignatureSpan">sinon.</span>Event ()](#apidoc.element.sinon.Event.Event)
- description and source-code
```javascript
Event = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.Event.prototype"></a>[module sinon.Event.prototype](#apidoc.module.sinon.Event.prototype)

#### <a name="apidoc.element.sinon.Event.prototype.initEvent"></a>[function <span class="apidocSignatureSpan">sinon.Event.prototype.</span>initEvent (type, bubbles, cancelable, target)](#apidoc.element.sinon.Event.prototype.initEvent)
- description and source-code
```javascript
initEvent = function (type, bubbles, cancelable, target) {
    this.type = type;
    this.bubbles = bubbles;
    this.cancelable = cancelable;
    this.target = target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.Event.prototype.preventDefault"></a>[function <span class="apidocSignatureSpan">sinon.Event.prototype.</span>preventDefault ()](#apidoc.element.sinon.Event.prototype.preventDefault)
- description and source-code
```javascript
preventDefault = function () {
    this.defaultPrevented = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.Event.prototype.stopPropagation"></a>[function <span class="apidocSignatureSpan">sinon.Event.prototype.</span>stopPropagation ()](#apidoc.element.sinon.Event.prototype.stopPropagation)
- description and source-code
```javascript
stopPropagation = function () {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.EventTarget"></a>[module sinon.EventTarget](#apidoc.module.sinon.EventTarget)

#### <a name="apidoc.element.sinon.EventTarget.addEventListener"></a>[function <span class="apidocSignatureSpan">sinon.EventTarget.</span>addEventListener ()](#apidoc.element.sinon.EventTarget.addEventListener)
- description and source-code
```javascript
addEventListener = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.EventTarget.dispatchEvent"></a>[function <span class="apidocSignatureSpan">sinon.EventTarget.</span>dispatchEvent ()](#apidoc.element.sinon.EventTarget.dispatchEvent)
- description and source-code
```javascript
dispatchEvent = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.EventTarget.removeEventListener"></a>[function <span class="apidocSignatureSpan">sinon.EventTarget.</span>removeEventListener ()](#apidoc.element.sinon.EventTarget.removeEventListener)
- description and source-code
```javascript
removeEventListener = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.FakeXMLHttpRequest"></a>[module sinon.FakeXMLHttpRequest](#apidoc.module.sinon.FakeXMLHttpRequest)

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.FakeXMLHttpRequest"></a>[function <span class="apidocSignatureSpan">sinon.</span>FakeXMLHttpRequest (config)](#apidoc.element.sinon.FakeXMLHttpRequest.FakeXMLHttpRequest)
- description and source-code
```javascript
function FakeXMLHttpRequest(config) {
    EventTargetHandler.call(this);
    this.readyState = FakeXMLHttpRequest.UNSENT;
    this.requestHeaders = {};
    this.requestBody = null;
    this.status = 0;
    this.statusText = "";
    this.upload = new EventTargetHandler();
    this.responseType = "";
    this.response = "";
    this.logError = configureLogError(config);
    if (sinonXhr.supportsCORS) {
        this.withCredentials = false;
    }

    if (typeof FakeXMLHttpRequest.onCreate === "function") {
        FakeXMLHttpRequest.onCreate(this);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.addFilter"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>addFilter (fn)](#apidoc.element.sinon.FakeXMLHttpRequest.addFilter)
- description and source-code
```javascript
function addFilter(fn) {
    this.filters.push(fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.defake"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>defake (fakeXhr, xhrArgs)](#apidoc.element.sinon.FakeXMLHttpRequest.defake)
- description and source-code
```javascript
function defake(fakeXhr, xhrArgs) {
    var xhr = new sinonXhr.workingXHR(); // eslint-disable-line new-cap

    [
        "open",
        "setRequestHeader",
        "send",
        "abort",
        "getResponseHeader",
        "getAllResponseHeaders",
        "addEventListener",
        "overrideMimeType",
        "removeEventListener"
    ].forEach(function (method) {
        fakeXhr[method] = function () {
            return apply(xhr, method, arguments);
        };
    });

    var copyAttrs = function (args) {
        args.forEach(function (attr) {
            fakeXhr[attr] = xhr[attr];
        });
    };

    var stateChange = function stateChange() {
        fakeXhr.readyState = xhr.readyState;
        if (xhr.readyState >= FakeXMLHttpRequest.HEADERS_RECEIVED) {
            copyAttrs(["status", "statusText"]);
        }
        if (xhr.readyState >= FakeXMLHttpRequest.LOADING) {
            copyAttrs(["responseText", "response"]);
        }
        if (xhr.readyState === FakeXMLHttpRequest.DONE) {
            copyAttrs(["responseXML"]);
        }
        if (fakeXhr.onreadystatechange) {
            fakeXhr.onreadystatechange.call(fakeXhr, { target: fakeXhr });
        }
    };

    if (xhr.addEventListener) {
        Object.keys(fakeXhr.eventListeners).forEach(function (event) {
<span class="apidocCodeCommentSpan">            /*eslint-disable no-loop-func*/
</span>            fakeXhr.eventListeners[event].forEach(function (handler) {
                xhr.addEventListener(event, handler);
            });
            /*eslint-enable no-loop-func*/
        });

        xhr.addEventListener("readystatechange", stateChange);
    } else {
        xhr.onreadystatechange = stateChange;
    }
    apply(xhr, "open", xhrArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.parseXML"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.</span>parseXML (text)](#apidoc.element.sinon.FakeXMLHttpRequest.parseXML)
- description and source-code
```javascript
function parseXML(text) {
    // Treat empty string as parsing failure
    if (text !== "") {
        try {
            if (typeof DOMParser !== "undefined") {
                var parser = new DOMParser();
                return parser.parseFromString(text, "text/xml");
            }
            var xmlDoc = new window.ActiveXObject("Microsoft.XMLDOM");
            xmlDoc.async = "false";
            xmlDoc.loadXML(text);
            return xmlDoc;
        } catch (e) {
            // Unable to parse XML - no biggie
        }
    }

    return null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.FakeXMLHttpRequest.prototype"></a>[module sinon.FakeXMLHttpRequest.prototype](#apidoc.module.sinon.FakeXMLHttpRequest.prototype)

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.abort"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>abort ()](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.abort)
- description and source-code
```javascript
function abort() {
    this.aborted = true;
    clearResponse(this);
    this.errorFlag = true;
    this.requestHeaders = {};
    this.responseHeaders = {};

    if (this.readyState !== FakeXMLHttpRequest.UNSENT && this.sendFlag
        && this.readyState !== FakeXMLHttpRequest.DONE) {
        this.readyStateChange(FakeXMLHttpRequest.DONE);
        this.sendFlag = false;
    }

    this.readyState = FakeXMLHttpRequest.UNSENT;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.addEventListener"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>addEventListener (event, listener)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.addEventListener)
- description and source-code
```javascript
function addEventListener(event, listener) {
    this.eventListeners = this.eventListeners || {};
    this.eventListeners[event] = this.eventListeners[event] || [];
    push.call(this.eventListeners[event], listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.dispatchEvent"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>dispatchEvent (event)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.dispatchEvent)
- description and source-code
```javascript
function dispatchEvent(event) {
    var self = this;
    var type = event.type;
    var listeners = self.eventListeners && self.eventListeners[type] || [];

    listeners.forEach(function (listener) {
        if (typeof listener === "function") {
            listener.call(self, event);
        } else {
            listener.handleEvent(event);
        }
    });

    return !!event.defaultPrevented;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.downloadProgress"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>downloadProgress (progressEventRaw)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.downloadProgress)
- description and source-code
```javascript
function downloadProgress(progressEventRaw) {
    if (supportsProgress) {
        this.dispatchEvent(new sinonEvent.ProgressEvent("progress", progressEventRaw));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.error"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>error ()](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.error)
- description and source-code
```javascript
error = function () {
    clearResponse(this);
    this.errorFlag = true;
    this.requestHeaders = {};
    this.responseHeaders = {};

    this.readyStateChange(FakeXMLHttpRequest.DONE);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.getAllResponseHeaders"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>getAllResponseHeaders ()](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.getAllResponseHeaders)
- description and source-code
```javascript
function getAllResponseHeaders() {
    if (this.readyState < FakeXMLHttpRequest.HEADERS_RECEIVED) {
        return "";
    }

    var responseHeaders = this.responseHeaders;
    var headers = Object.keys(responseHeaders)
        .filter(excludeSetCookie2Header)
        .reduce(function (prev, header) {
            var value = responseHeaders[header];

            return prev + (header + ": " + value + "\r\n");
        }, "");

    return headers;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.getResponseHeader"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>getResponseHeader (header)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.getResponseHeader)
- description and source-code
```javascript
function getResponseHeader(header) {
    if (this.readyState < FakeXMLHttpRequest.HEADERS_RECEIVED) {
        return null;
    }

    if (/^Set-Cookie2?$/i.test(header)) {
        return null;
    }

    header = getHeader(this.responseHeaders, header);

    return this.responseHeaders[header] || null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.open"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>open (method, url, async, username, password)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.open)
- description and source-code
```javascript
function open(method, url, async, username, password) {
    this.method = method;
    this.url = url;
    this.async = typeof async === "boolean" ? async : true;
    this.username = username;
    this.password = password;
    clearResponse(this);
    this.requestHeaders = {};
    this.sendFlag = false;

    if (FakeXMLHttpRequest.useFilters === true) {
        var xhrArgs = arguments;
        var defake = FakeXMLHttpRequest.filters.some(function (filter) {
            return filter.apply(this, xhrArgs);
        });
        if (defake) {
            FakeXMLHttpRequest.defake(this, arguments);
            return;
        }
    }
    this.readyStateChange(FakeXMLHttpRequest.OPENED);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.overrideMimeType"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>overrideMimeType (type)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.overrideMimeType)
- description and source-code
```javascript
function overrideMimeType(type) {
    if (this.readyState >= FakeXMLHttpRequest.LOADING) {
        throw new Error("INVALID_STATE_ERR");
    }
    this.overriddenMimeType = type;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.readyStateChange"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>readyStateChange (state)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.readyStateChange)
- description and source-code
```javascript
function readyStateChange(state) {
    this.readyState = state;

    var readyStateChangeEvent = new sinonEvent.Event("readystatechange", false, false, this);
    var event, progress;

    if (typeof this.onreadystatechange === "function") {
        try {
            this.onreadystatechange(readyStateChangeEvent);
        } catch (e) {
            this.logError("Fake XHR onreadystatechange handler", e);
        }
    }

    if (this.readyState === FakeXMLHttpRequest.DONE) {
        if (this.aborted || this.status === 0) {
            progress = {loaded: 0, total: 0};
            event = this.aborted ? "abort" : "error";
        } else {
            progress = {loaded: 100, total: 100};
            event = "load";
        }

        if (supportsProgress) {
            this.upload.dispatchEvent(new sinonEvent.ProgressEvent("progress", progress, this));
            this.upload.dispatchEvent(new sinonEvent.ProgressEvent(event, progress, this));
            this.upload.dispatchEvent(new sinonEvent.ProgressEvent("loadend", progress, this));
        }

        this.dispatchEvent(new sinonEvent.ProgressEvent("progress", progress, this));
        this.dispatchEvent(new sinonEvent.ProgressEvent(event, progress, this));
        this.dispatchEvent(new sinonEvent.ProgressEvent("loadend", progress, this));
    }

    this.dispatchEvent(readyStateChangeEvent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.removeEventListener"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>removeEventListener (event, listener)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.removeEventListener)
- description and source-code
```javascript
function removeEventListener(event, listener) {
    var listeners = this.eventListeners && this.eventListeners[event] || [];
    var index = listeners.indexOf(listener);

    if (index === -1) {
        return;
    }

    listeners.splice(index, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.respond"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>respond (status, headers, body)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.respond)
- description and source-code
```javascript
function respond(status, headers, body) {
    this.setStatus(status);
    this.setResponseHeaders(headers || {});
    this.setResponseBody(body || "");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.send"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>send (data)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.send)
- description and source-code
```javascript
function send(data) {
    verifyState(this);

    if (!/^(head)$/i.test(this.method)) {
        var contentType = getHeader(this.requestHeaders, "Content-Type");
        if (this.requestHeaders[contentType]) {
            var value = this.requestHeaders[contentType].split(";");
            this.requestHeaders[contentType] = value[0] + ";charset=utf-8";
        } else if (supportsFormData && !(data instanceof FormData)) {
            this.requestHeaders["Content-Type"] = "text/plain;charset=utf-8";
        }

        this.requestBody = data;
    }

    this.errorFlag = false;
    this.sendFlag = this.async;
    clearResponse(this);
    this.readyStateChange(FakeXMLHttpRequest.OPENED);

    if (typeof this.onSend === "function") {
        this.onSend(this);
    }

    this.dispatchEvent(new sinonEvent.Event("loadstart", false, false, this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.setRequestHeader"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>setRequestHeader (header, value)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.setRequestHeader)
- description and source-code
```javascript
function setRequestHeader(header, value) {
    verifyState(this);

    var checkUnsafeHeaders = true;
    if (typeof this.unsafeHeadersEnabled === "function") {
        checkUnsafeHeaders = this.unsafeHeadersEnabled();
    }

    if (checkUnsafeHeaders && (unsafeHeaders[header] || /^(Sec-|Proxy-)/.test(header))) {
        throw new Error("Refused to set unsafe header \"" + header + "\"");
    }

    if (this.requestHeaders[header]) {
        this.requestHeaders[header] += "," + value;
    } else {
        this.requestHeaders[header] = value;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.setResponseBody"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>setResponseBody (body)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.setResponseBody)
- description and source-code
```javascript
function setResponseBody(body) {
    verifyRequestSent(this);
    verifyHeadersReceived(this);
    verifyResponseBodyType(body);
    var contentType = this.overriddenMimeType || this.getResponseHeader("Content-Type");

    var isTextResponse = this.responseType === "" || this.responseType === "text";
    clearResponse(this);
    if (this.async) {
        var chunkSize = this.chunkSize || 10;
        var index = 0;

        do {
            this.readyStateChange(FakeXMLHttpRequest.LOADING);

            if (isTextResponse) {
                this.responseText = this.response += body.substring(index, index + chunkSize);
            }
            index += chunkSize;
        } while (index < body.length);
    }

    this.response = convertResponseBody(this.responseType, contentType, body);
    if (isTextResponse) {
        this.responseText = this.response;
    }

    if (this.responseType === "document") {
        this.responseXML = this.response;
    } else if (this.responseType === "" && isXmlContentType(contentType)) {
        this.responseXML = FakeXMLHttpRequest.parseXML(this.responseText);
    }
    this.readyStateChange(FakeXMLHttpRequest.DONE);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.setResponseHeaders"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>setResponseHeaders (headers)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.setResponseHeaders)
- description and source-code
```javascript
function setResponseHeaders(headers) {
    verifyRequestOpened(this);

    var responseHeaders = this.responseHeaders = {};

    Object.keys(headers).forEach(function (header) {
        responseHeaders[header] = headers[header];
    });

    if (this.async) {
        this.readyStateChange(FakeXMLHttpRequest.HEADERS_RECEIVED);
    } else {
        this.readyState = FakeXMLHttpRequest.HEADERS_RECEIVED;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.setStatus"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>setStatus (status)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.setStatus)
- description and source-code
```javascript
function setStatus(status) {
    var sanitizedStatus = typeof status === "number" ? status : 200;

    verifyRequestOpened(this);
    this.status = sanitizedStatus;
    this.statusText = FakeXMLHttpRequest.statusCodes[sanitizedStatus];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.uploadError"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>uploadError (error)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.uploadError)
- description and source-code
```javascript
function uploadError(error) {
    if (supportsCustomEvent) {
        this.upload.dispatchEvent(new sinonEvent.CustomEvent("error", {detail: error}));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.FakeXMLHttpRequest.prototype.uploadProgress"></a>[function <span class="apidocSignatureSpan">sinon.FakeXMLHttpRequest.prototype.</span>uploadProgress (progressEventRaw)](#apidoc.element.sinon.FakeXMLHttpRequest.prototype.uploadProgress)
- description and source-code
```javascript
function uploadProgress(progressEventRaw) {
    if (supportsProgress) {
        this.upload.dispatchEvent(new sinonEvent.ProgressEvent("progress", progressEventRaw));
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.ProgressEvent"></a>[module sinon.ProgressEvent](#apidoc.module.sinon.ProgressEvent)

#### <a name="apidoc.element.sinon.ProgressEvent.ProgressEvent"></a>[function <span class="apidocSignatureSpan">sinon.</span>ProgressEvent ()](#apidoc.element.sinon.ProgressEvent.ProgressEvent)
- description and source-code
```javascript
ProgressEvent = function () {
    exports.printWarning(msg);
    return func.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.ProgressEvent.prototype"></a>[module sinon.ProgressEvent.prototype](#apidoc.module.sinon.ProgressEvent.prototype)

#### <a name="apidoc.element.sinon.ProgressEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">sinon.ProgressEvent.prototype.</span>constructor (type, progressEventRaw, target)](#apidoc.element.sinon.ProgressEvent.prototype.constructor)
- description and source-code
```javascript
function ProgressEvent(type, progressEventRaw, target) {
    this.initEvent(type, false, false, target);
    this.loaded = typeof progressEventRaw.loaded === "number" ? progressEventRaw.loaded : null;
    this.total = typeof progressEventRaw.total === "number" ? progressEventRaw.total : null;
    this.lengthComputable = !!progressEventRaw.total;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.ProgressEvent.prototype.constructor"></a>[module sinon.ProgressEvent.prototype.constructor](#apidoc.module.sinon.ProgressEvent.prototype.constructor)

#### <a name="apidoc.element.sinon.ProgressEvent.prototype.constructor.constructor"></a>[function <span class="apidocSignatureSpan">sinon.ProgressEvent.prototype.</span>constructor ()](#apidoc.element.sinon.ProgressEvent.prototype.constructor.constructor)
- description and source-code
```javascript
function Function() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.assert"></a>[module sinon.assert](#apidoc.module.sinon.assert)

#### <a name="apidoc.element.sinon.assert.alwaysCalledOn"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledOn (fake)](#apidoc.element.sinon.assert.alwaysCalledOn)
- description and source-code
```javascript
alwaysCalledOn = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.alwaysCalledWith"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledWith (fake)](#apidoc.element.sinon.assert.alwaysCalledWith)
- description and source-code
```javascript
alwaysCalledWith = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.alwaysCalledWithExactly"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledWithExactly (fake)](#apidoc.element.sinon.assert.alwaysCalledWithExactly)
- description and source-code
```javascript
alwaysCalledWithExactly = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.alwaysCalledWithMatch"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledWithMatch (fake)](#apidoc.element.sinon.assert.alwaysCalledWithMatch)
- description and source-code
```javascript
alwaysCalledWithMatch = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.alwaysCalledWithNew"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysCalledWithNew (fake)](#apidoc.element.sinon.assert.alwaysCalledWithNew)
- description and source-code
```javascript
alwaysCalledWithNew = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.alwaysThrew"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>alwaysThrew (fake)](#apidoc.element.sinon.assert.alwaysThrew)
- description and source-code
```javascript
alwaysThrew = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.callCount"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>callCount (method, count)](#apidoc.element.sinon.assert.callCount)
- description and source-code
```javascript
function assertCallCount(method, count) {
    verifyIsStub(method);

    if (method.callCount !== count) {
        var msg = "expected %n to be called " + timesInWords(count) +
            " but was called %c%C";
        failAssertion(this, method.printf(msg));
    } else {
        assert.pass("callCount");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.callOrder"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>callOrder ()](#apidoc.element.sinon.assert.callOrder)
- description and source-code
```javascript
function assertCallOrder() {
    verifyIsStub.apply(null, arguments);
    var expected = "";
    var actual = "";

    if (!calledInOrder(arguments)) {
        try {
            expected = [].join.call(arguments, ", ");
            var calls = slice.call(arguments);
            var i = calls.length;
            while (i) {
                if (!calls[--i].called) {
                    calls.splice(i, 1);
                }
            }
            actual = orderByFirstCall(calls).join(", ");
        } catch (e) {
            // If this fails, we'll just fall back to the blank string
        }

        failAssertion(this, "expected " + expected + " to be " +
                    "called in order but were called as " + actual);
    } else {
        assert.pass("callOrder");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.called"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>called (fake)](#apidoc.element.sinon.assert.called)
- description and source-code
```javascript
called = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.calledOn"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>calledOn (fake)](#apidoc.element.sinon.assert.calledOn)
- description and source-code
```javascript
calledOn = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.calledOnce"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>calledOnce (fake)](#apidoc.element.sinon.assert.calledOnce)
- description and source-code
```javascript
calledOnce = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.calledThrice"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>calledThrice (fake)](#apidoc.element.sinon.assert.calledThrice)
- description and source-code
```javascript
calledThrice = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.calledTwice"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>calledTwice (fake)](#apidoc.element.sinon.assert.calledTwice)
- description and source-code
```javascript
calledTwice = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.calledWith"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>calledWith (fake)](#apidoc.element.sinon.assert.calledWith)
- description and source-code
```javascript
calledWith = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.calledWithExactly"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>calledWithExactly (fake)](#apidoc.element.sinon.assert.calledWithExactly)
- description and source-code
```javascript
calledWithExactly = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.calledWithMatch"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>calledWithMatch (fake)](#apidoc.element.sinon.assert.calledWithMatch)
- description and source-code
```javascript
calledWithMatch = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.calledWithNew"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>calledWithNew (fake)](#apidoc.element.sinon.assert.calledWithNew)
- description and source-code
```javascript
calledWithNew = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.expose"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>expose (target, options)](#apidoc.element.sinon.assert.expose)
- description and source-code
```javascript
function expose(target, options) {
    if (!target) {
        throw new TypeError("target is null or undefined");
    }

    var o = options || {};
    var prefix = typeof o.prefix === "undefined" && "assert" || o.prefix;
    var includeFail = typeof o.includeFail === "undefined" || !!o.includeFail;
    var instance = this;

    Object.keys(instance).forEach(function (method) {
        if (method !== "expose" && (includeFail || !/^(fail)/.test(method))) {
            target[exposedName(prefix, method)] = instance[method];
        }
    });

    return target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.fail"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>fail (message)](#apidoc.element.sinon.assert.fail)
- description and source-code
```javascript
function fail(message) {
    var error = new Error(message);
    error.name = this.failException || assert.failException;

    throw error;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.match"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>match (actual, expectation)](#apidoc.element.sinon.assert.match)
- description and source-code
```javascript
function match(actual, expectation) {
    var matcher = sinonMatch(expectation);
    if (matcher.test(actual)) {
        assert.pass("match");
    } else {
        var formatted = [
            "expected value to match",
            "    expected = " + format(expectation),
            "    actual = " + format(actual)
        ];

        failAssertion(this, formatted.join("\n"));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.neverCalledWith"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>neverCalledWith (fake)](#apidoc.element.sinon.assert.neverCalledWith)
- description and source-code
```javascript
neverCalledWith = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.neverCalledWithMatch"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>neverCalledWithMatch (fake)](#apidoc.element.sinon.assert.neverCalledWithMatch)
- description and source-code
```javascript
neverCalledWithMatch = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.notCalled"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>notCalled (fake)](#apidoc.element.sinon.assert.notCalled)
- description and source-code
```javascript
notCalled = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.pass"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>pass ()](#apidoc.element.sinon.assert.pass)
- description and source-code
```javascript
function pass() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.assert.threw"></a>[function <span class="apidocSignatureSpan">sinon.assert.</span>threw (fake)](#apidoc.element.sinon.assert.threw)
- description and source-code
```javascript
threw = function (fake) {
    verifyIsStub(fake);

    var args = slice.call(arguments, 1);
    var failed = false;

    verifyIsValidAssertion(name, args);

    if (typeof method === "function") {
        failed = !method(fake);
    } else {
        failed = typeof fake[method] === "function" ?
            !fake[method].apply(fake, args) : !fake[method];
    }

    if (failed) {
        failAssertion(this, (fake.printf || fake.proxy.printf).apply(fake, [message].concat(args)));
    } else {
        assert.pass(name);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.clock"></a>[module sinon.clock](#apidoc.module.sinon.clock)

#### <a name="apidoc.element.sinon.clock.create"></a>[function <span class="apidocSignatureSpan">sinon.clock.</span>create (now)](#apidoc.element.sinon.clock.create)
- description and source-code
```javascript
create = function (now) {
    return llx.createClock(now);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.collection"></a>[module sinon.collection](#apidoc.module.sinon.collection)

#### <a name="apidoc.element.sinon.collection.add"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>add (fake)](#apidoc.element.sinon.collection.add)
- description and source-code
```javascript
function add(fake) {
    push.call(getFakes(this), fake);
    return fake;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.inject"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>inject (obj)](#apidoc.element.sinon.collection.inject)
- description and source-code
```javascript
function inject(obj) {
    var col = this;

    obj.spy = function () {
        return col.spy.apply(col, arguments);
    };

    obj.stub = function () {
        return col.stub.apply(col, arguments);
    };

    obj.mock = function () {
        return col.mock.apply(col, arguments);
    };

    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.mock"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>mock ()](#apidoc.element.sinon.collection.mock)
- description and source-code
```javascript
function mock() {
    return this.add(sinonMock.apply(null, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.reset"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>reset ()](#apidoc.element.sinon.collection.reset)
- description and source-code
```javascript
function reset() {
    each(this, "reset");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.resetBehavior"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>resetBehavior ()](#apidoc.element.sinon.collection.resetBehavior)
- description and source-code
```javascript
function resetBehavior() {
    each(this, "resetBehavior");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.resetHistory"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>resetHistory ()](#apidoc.element.sinon.collection.resetHistory)
- description and source-code
```javascript
function resetHistory() {
    each(this, "resetHistory");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.restore"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>restore ()](#apidoc.element.sinon.collection.restore)
- description and source-code
```javascript
function restore() {
    each(this, "restore");
    this.fakes = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.spy"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>spy ()](#apidoc.element.sinon.collection.spy)
- description and source-code
```javascript
function spy() {
    return this.add(sinonSpy.apply(sinonSpy, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.stub"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>stub (object, property)](#apidoc.element.sinon.collection.stub)
- description and source-code
```javascript
function stub(object, property) {
    throwOnFalsyObject.apply(null, arguments);

    var isStubbingEntireObject = typeof property === "undefined" && typeof object === "object";
    var isStubbingNonFunctionProperty = property && typeof object[property] !== "function";
    var stubbed = isStubbingNonFunctionProperty ?
                    stubNonFunctionProperty.apply(null, arguments) :
                    sinonStub.apply(null, arguments);

    if (isStubbingEntireObject) {
        collectOwnMethods(stubbed).forEach(this.add.bind(this));
    } else {
        this.add(stubbed);
    }

    return stubbed;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.verify"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>verify ()](#apidoc.element.sinon.collection.verify)
- description and source-code
```javascript
function verify() {
    each(this, "verify");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.collection.verifyAndRestore"></a>[function <span class="apidocSignatureSpan">sinon.collection.</span>verifyAndRestore ()](#apidoc.element.sinon.collection.verifyAndRestore)
- description and source-code
```javascript
function verifyAndRestore() {
    var exception;

    try {
        this.verify();
    } catch (e) {
        exception = e;
    }

    this.restore();

    if (exception) {
        throw exception;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.expectation"></a>[module sinon.expectation](#apidoc.module.sinon.expectation)

#### <a name="apidoc.element.sinon.expectation.allowsCall"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>allowsCall (thisValue, args)](#apidoc.element.sinon.expectation.allowsCall)
- description and source-code
```javascript
function allowsCall(thisValue, args) {
    var expectedArguments = this.expectedArguments;

    if (this.met() && receivedMaxCalls(this)) {
        return false;
    }

    if ("expectedThis" in this && this.expectedThis !== thisValue) {
        return false;
    }

    if (!("expectedArguments" in this)) {
        return true;
    }

    args = args || [];

    if (args.length < expectedArguments.length) {
        return false;
    }

    if (this.expectsExactArgCount &&
        args.length !== expectedArguments.length) {
        return false;
    }

    return expectedArguments.every(function (expectedArgument, i) {
        if (!verifyMatcher(expectedArgument, args[i])) {
            return false;
        }

        if (!deepEqual(expectedArgument, args[i])) {
            return false;
        }

        return true;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.atLeast"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>atLeast (num)](#apidoc.element.sinon.expectation.atLeast)
- description and source-code
```javascript
function atLeast(num) {
    if (typeof num !== "number") {
        throw new TypeError("'" + valueToString(num) + "' is not number");
    }

    if (!this.limitsSet) {
        this.maxCalls = null;
        this.limitsSet = true;
    }

    this.minCalls = num;

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.atMost"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>atMost (num)](#apidoc.element.sinon.expectation.atMost)
- description and source-code
```javascript
function atMost(num) {
    if (typeof num !== "number") {
        throw new TypeError("'" + valueToString(num) + "' is not number");
    }

    if (!this.limitsSet) {
        this.minCalls = null;
        this.limitsSet = true;
    }

    this.maxCalls = num;

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.create"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>create (methodName)](#apidoc.element.sinon.expectation.create)
- description and source-code
```javascript
function create(methodName) {
    var expectation = extend(stub.create(), mockExpectation);
    delete expectation.create;
    expectation.method = methodName;

    return expectation;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.exactly"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>exactly (num)](#apidoc.element.sinon.expectation.exactly)
- description and source-code
```javascript
function exactly(num) {
    if (typeof num !== "number") {
        throw new TypeError("'" + valueToString(num) + "' is not a number");
    }

    this.atLeast(num);
    return this.atMost(num);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.fail"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>fail (message)](#apidoc.element.sinon.expectation.fail)
- description and source-code
```javascript
function fail(message) {
    var exception = new Error(message);
    exception.name = "ExpectationError";

    throw exception;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.invoke"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>invoke (func, thisValue, args)](#apidoc.element.sinon.expectation.invoke)
- description and source-code
```javascript
function invoke(func, thisValue, args) {
    this.verifyCallAllowed(thisValue, args);

    return spyInvoke.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.met"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>met ()](#apidoc.element.sinon.expectation.met)
- description and source-code
```javascript
function met() {
    return !this.failed && receivedMinCalls(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.never"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>never ()](#apidoc.element.sinon.expectation.never)
- description and source-code
```javascript
function never() {
    return this.exactly(0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.on"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>on (thisValue)](#apidoc.element.sinon.expectation.on)
- description and source-code
```javascript
function on(thisValue) {
    this.expectedThis = thisValue;
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.once"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>once ()](#apidoc.element.sinon.expectation.once)
- description and source-code
```javascript
function once() {
    return this.exactly(1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.pass"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>pass (message)](#apidoc.element.sinon.expectation.pass)
- description and source-code
```javascript
function pass(message) {
    assert.pass(message);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.thrice"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>thrice ()](#apidoc.element.sinon.expectation.thrice)
- description and source-code
```javascript
function thrice() {
    return this.exactly(3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.toString"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>toString ()](#apidoc.element.sinon.expectation.toString)
- description and source-code
```javascript
toString = function () {
    var args = (this.expectedArguments || []).slice();

    if (!this.expectsExactArgCount) {
        push.call(args, "[...]");
    }

    var callStr = spyCallToString.call({
        proxy: this.method || "anonymous mock expectation",
        args: args
    });

    var message = callStr.replace(", [...", "[, ...") + " " +
        expectedCallCountInWords(this);

    if (this.met()) {
        return "Expectation met: " + message;
    }

    return "Expected " + message + " (" +
        callCountInWords(this.callCount) + ")";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.twice"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>twice ()](#apidoc.element.sinon.expectation.twice)
- description and source-code
```javascript
function twice() {
    return this.exactly(2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.verify"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>verify ()](#apidoc.element.sinon.expectation.verify)
- description and source-code
```javascript
function verify() {
    if (!this.met()) {
        mockExpectation.fail(this.toString());
    } else {
        mockExpectation.pass(this.toString());
    }

    return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.verifyCallAllowed"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>verifyCallAllowed (thisValue, args)](#apidoc.element.sinon.expectation.verifyCallAllowed)
- description and source-code
```javascript
function verifyCallAllowed(thisValue, args) {
    var expectedArguments = this.expectedArguments;

    if (receivedMaxCalls(this)) {
        this.failed = true;
        mockExpectation.fail(this.method + " already called " + timesInWords(this.maxCalls));
    }

    if ("expectedThis" in this && this.expectedThis !== thisValue) {
        mockExpectation.fail(this.method + " called with " + valueToString(thisValue) +
            " as thisValue, expected " + valueToString(this.expectedThis));
    }

    if (!("expectedArguments" in this)) {
        return;
    }

    if (!args) {
        mockExpectation.fail(this.method + " received no arguments, expected " +
            format(expectedArguments));
    }

    if (args.length < expectedArguments.length) {
        mockExpectation.fail(this.method + " received too few arguments (" + format(args) +
            "), expected " + format(expectedArguments));
    }

    if (this.expectsExactArgCount &&
        args.length !== expectedArguments.length) {
        mockExpectation.fail(this.method + " received too many arguments (" + format(args) +
            "), expected " + format(expectedArguments));
    }

    expectedArguments.forEach(function (expectedArgument, i) {
        if (!verifyMatcher(expectedArgument, args[i])) {
            mockExpectation.fail(this.method + " received wrong arguments " + format(args) +
                ", didn't match " + expectedArguments.toString());
        }

        if (!deepEqual(expectedArgument, args[i])) {
            mockExpectation.fail(this.method + " received wrong arguments " + format(args) +
                ", expected " + format(expectedArguments));
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.withArgs"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>withArgs ()](#apidoc.element.sinon.expectation.withArgs)
- description and source-code
```javascript
function withArgs() {
    this.expectedArguments = slice.call(arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.expectation.withExactArgs"></a>[function <span class="apidocSignatureSpan">sinon.expectation.</span>withExactArgs ()](#apidoc.element.sinon.expectation.withExactArgs)
- description and source-code
```javascript
function withExactArgs() {
    this.withArgs.apply(this, arguments);
    this.expectsExactArgCount = true;
    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.fakeServer"></a>[module sinon.fakeServer](#apidoc.module.sinon.fakeServer)

#### <a name="apidoc.element.sinon.fakeServer.addRequest"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>addRequest (xhrObj)](#apidoc.element.sinon.fakeServer.addRequest)
- description and source-code
```javascript
function addRequest(xhrObj) {
    var server = this;
    push.call(this.requests, xhrObj);

    incrementRequestCount.call(this);

    xhrObj.onSend = function () {
        server.handleRequest(this);

        if (server.respondImmediately) {
            server.respond();
        } else if (server.autoRespond && !server.responding) {
            setTimeout(function () {
                server.responding = false;
                server.respond();
            }, server.autoRespondAfter || 10);

            server.responding = true;
        }
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.configure"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>configure (config)](#apidoc.element.sinon.fakeServer.configure)
- description and source-code
```javascript
configure = function (config) {
    var self = this;
    var whitelist = {
        "autoRespond": true,
        "autoRespondAfter": true,
        "respondImmediately": true,
        "fakeHTTPMethods": true,
        "logger": true,
        "unsafeHeadersEnabled": true
    };

    config = config || {};

    Object.keys(config).forEach(function (setting) {
        if (setting in whitelist) {
            self[setting] = config[setting];
        }
    });

    self.logError = configureLogError(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.create"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>create (config)](#apidoc.element.sinon.fakeServer.create)
- description and source-code
```javascript
create = function (config) {
    var server = Object.create(this);
    server.configure(config);
    this.xhr = fakeXhr.useFakeXMLHttpRequest();
    server.requests = [];
    server.requestCount = 0;

    this.xhr.onCreate = function (xhrObj) {
        xhrObj.unsafeHeadersEnabled = function () {
            return !(server.unsafeHeadersEnabled === false);
        };
        server.addRequest(xhrObj);
    };

    return server;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.getHTTPMethod"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>getHTTPMethod (request)](#apidoc.element.sinon.fakeServer.getHTTPMethod)
- description and source-code
```javascript
function getHTTPMethod(request) {
    if (this.fakeHTTPMethods && /post/i.test(request.method)) {
        var matches = (request.requestBody || "").match(/_method=([^\b;]+)/);
        return matches ? matches[1] : request.method;
    }

    return request.method;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.getRequest"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>getRequest (index)](#apidoc.element.sinon.fakeServer.getRequest)
- description and source-code
```javascript
function getRequest(index) {
    return this.requests[index] || null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.handleRequest"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>handleRequest (xhr)](#apidoc.element.sinon.fakeServer.handleRequest)
- description and source-code
```javascript
function handleRequest(xhr) {
    if (xhr.async) {
        if (!this.queue) {
            this.queue = [];
        }

        push.call(this.queue, xhr);
    } else {
        this.processRequest(xhr);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.log"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>log (response, request)](#apidoc.element.sinon.fakeServer.log)
- description and source-code
```javascript
function log(response, request) {
    var str;

    str = "Request:\n" + format(request) + "\n\n";
    str += "Response:\n" + format(response) + "\n\n";

    if (typeof this.logger === "function") {
        this.logger(str);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.logError"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>logError (label, e)](#apidoc.element.sinon.fakeServer.logError)
- description and source-code
```javascript
function logError(label, e) {
    var msg = label + " threw exception: ";
    var err = { name: e.name || label, message: e.message || e.toString(), stack: e.stack };

    function throwLoggedError() {
        err.message = msg + err.message;
        throw err;
    }

    config.logger(msg + "[" + err.name + "] " + err.message);

    if (err.stack) {
        config.logger(err.stack);
    }

    if (config.useImmediateExceptions) {
        throwLoggedError();
    } else {
        config.setTimeout(throwLoggedError, 0);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.logger"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>logger ()](#apidoc.element.sinon.fakeServer.logger)
- description and source-code
```javascript
logger = function () {
    // no-op; override via configure()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.processRequest"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>processRequest (request)](#apidoc.element.sinon.fakeServer.processRequest)
- description and source-code
```javascript
function processRequest(request) {
    try {
        if (request.aborted) {
            return;
        }

        var response = this.response || [404, {}, ""];

        if (this.responses) {
            for (var l = this.responses.length, i = l - 1; i >= 0; i--) {
                if (match.call(this, this.responses[i], request)) {
                    response = this.responses[i].response;
                    break;
                }
            }
        }

        if (request.readyState !== 4) {
            this.log(response, request);

            request.respond(response[0], response[1], response[2]);
        }
    } catch (e) {
        this.logError("Fake server request processing", e);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.reset"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>reset ()](#apidoc.element.sinon.fakeServer.reset)
- description and source-code
```javascript
function reset() {
    this.resetBehavior();
    this.resetHistory();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.resetBehavior"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>resetBehavior ()](#apidoc.element.sinon.fakeServer.resetBehavior)
- description and source-code
```javascript
function resetBehavior() {
    this.responses.length = this.queue.length = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.resetHistory"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>resetHistory ()](#apidoc.element.sinon.fakeServer.resetHistory)
- description and source-code
```javascript
function resetHistory() {
    this.requests.length = this.requestCount = 0;

    this.requestedOnce = this.requestedTwice = this.requestedThrice = this.requested = false;

    this.firstRequest = this.secondRequest = this.thirdRequest = this.lastRequest = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.respond"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>respond ()](#apidoc.element.sinon.fakeServer.respond)
- description and source-code
```javascript
function respond() {
    if (arguments.length > 0) {
        this.respondWith.apply(this, arguments);
    }

    var queue = this.queue || [];
    var requests = queue.splice(0, queue.length);
    var self = this;

    requests.forEach(function (request) {
        self.processRequest(request);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.respondWith"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>respondWith (method, url, body)](#apidoc.element.sinon.fakeServer.respondWith)
- description and source-code
```javascript
function respondWith(method, url, body) {
    if (arguments.length === 1 && typeof method !== "function") {
        this.response = responseArray(method);
        return;
    }

    if (!this.responses) {
        this.responses = [];
    }

    if (arguments.length === 1) {
        body = method;
        url = method = null;
    }

    if (arguments.length === 2) {
        body = url;
        url = method;
        method = null;
    }

    push.call(this.responses, {
        method: method,
        url: typeof url === "string" && url !== "" ? pathToRegexp(url) : url,
        response: typeof body === "function" ? body : responseArray(body)
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServer.restore"></a>[function <span class="apidocSignatureSpan">sinon.fakeServer.</span>restore ()](#apidoc.element.sinon.fakeServer.restore)
- description and source-code
```javascript
function restore() {
    return this.xhr.restore && this.xhr.restore.apply(this.xhr, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.fakeServerWithClock"></a>[module sinon.fakeServerWithClock](#apidoc.module.sinon.fakeServerWithClock)

#### <a name="apidoc.element.sinon.fakeServerWithClock.addRequest"></a>[function <span class="apidocSignatureSpan">sinon.fakeServerWithClock.</span>addRequest (xhr)](#apidoc.element.sinon.fakeServerWithClock.addRequest)
- description and source-code
```javascript
function addRequest(xhr) {
    if (xhr.async) {
        if (typeof setTimeout.clock === "object") {
            this.clock = setTimeout.clock;
        } else {
            this.clock = fakeTimers.useFakeTimers();
            this.resetClock = true;
        }

        if (!this.longestTimeout) {
            var clockSetTimeout = this.clock.setTimeout;
            var clockSetInterval = this.clock.setInterval;
            var server = this;

            this.clock.setTimeout = function (fn, timeout) {
                server.longestTimeout = Math.max(timeout, server.longestTimeout || 0);

                return clockSetTimeout.apply(this, arguments);
            };

            this.clock.setInterval = function (fn, timeout) {
                server.longestTimeout = Math.max(timeout, server.longestTimeout || 0);

                return clockSetInterval.apply(this, arguments);
            };
        }
    }

    return fakeServer.addRequest.call(this, xhr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServerWithClock.respond"></a>[function <span class="apidocSignatureSpan">sinon.fakeServerWithClock.</span>respond ()](#apidoc.element.sinon.fakeServerWithClock.respond)
- description and source-code
```javascript
function respond() {
    var returnVal = fakeServer.respond.apply(this, arguments);

    if (this.clock) {
        this.clock.tick(this.longestTimeout || 0);
        this.longestTimeout = 0;

        if (this.resetClock) {
            this.clock.restore();
            this.resetClock = false;
        }
    }

    return returnVal;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.fakeServerWithClock.restore"></a>[function <span class="apidocSignatureSpan">sinon.fakeServerWithClock.</span>restore ()](#apidoc.element.sinon.fakeServerWithClock.restore)
- description and source-code
```javascript
function restore() {
    if (this.clock) {
        this.clock.restore();
    }

    return fakeServer.restore.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match"></a>[module sinon.match](#apidoc.module.sinon.match)

#### <a name="apidoc.element.sinon.match.match"></a>[function <span class="apidocSignatureSpan">sinon.</span>match (expectation, message)](#apidoc.element.sinon.match.match)
- description and source-code
```javascript
function match(expectation, message) {
    var m = Object.create(matcher);
    var type = typeOf(expectation);

    if (type in TYPE_MAP) {
        TYPE_MAP[type](m, expectation, message);
    } else {
        m.test = function (actual) {
            return deepEqual(expectation, actual);
        };
    }

    if (!m.message) {
        m.message = "match(" + valueToString(expectation) + ")";
    }

    return m;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.has"></a>[function <span class="apidocSignatureSpan">sinon.match.</span>has (property, value)](#apidoc.element.sinon.match.has)
- description and source-code
```javascript
has = function (property, value) {
    assertType(property, "string", "property");
    var onlyProperty = arguments.length === 1;
    var message = messagePrefix + "(\"" + property + "\"";
    if (!onlyProperty) {
        message += ", " + valueToString(value);
    }
    message += ")";
    return match(function (actual) {
        if (actual === undefined || actual === null ||
                !propertyTest(actual, property)) {
            return false;
        }
        return onlyProperty || deepEqual(value, actual[property]);
    }, message);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.hasOwn"></a>[function <span class="apidocSignatureSpan">sinon.match.</span>hasOwn (property, value)](#apidoc.element.sinon.match.hasOwn)
- description and source-code
```javascript
hasOwn = function (property, value) {
    assertType(property, "string", "property");
    var onlyProperty = arguments.length === 1;
    var message = messagePrefix + "(\"" + property + "\"";
    if (!onlyProperty) {
        message += ", " + valueToString(value);
    }
    message += ")";
    return match(function (actual) {
        if (actual === undefined || actual === null ||
                !propertyTest(actual, property)) {
            return false;
        }
        return onlyProperty || deepEqual(value, actual[property]);
    }, message);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.instanceOf"></a>[function <span class="apidocSignatureSpan">sinon.match.</span>instanceOf (type)](#apidoc.element.sinon.match.instanceOf)
- description and source-code
```javascript
instanceOf = function (type) {
    assertType(type, "function", "type");
    return match(function (actual) {
        return actual instanceof type;
    }, "instanceOf(" + functionName(type) + ")");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.isMatcher"></a>[function <span class="apidocSignatureSpan">sinon.match.</span>isMatcher (object)](#apidoc.element.sinon.match.isMatcher)
- description and source-code
```javascript
function isMatcher(object) {
    return matcher.isPrototypeOf(object);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.same"></a>[function <span class="apidocSignatureSpan">sinon.match.</span>same (expectation)](#apidoc.element.sinon.match.same)
- description and source-code
```javascript
same = function (expectation) {
    return match(function (actual) {
        return expectation === actual;
    }, "same(" + valueToString(expectation) + ")");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.typeOf"></a>[function <span class="apidocSignatureSpan">sinon.match.</span>typeOf (type)](#apidoc.element.sinon.match.typeOf)
- description and source-code
```javascript
typeOf = function (type) {
    assertType(type, "string", "type");
    return match(function (actual) {
        return typeOf(actual) === type;
    }, "typeOf(\"" + type + "\")");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.any"></a>[module sinon.match.any](#apidoc.module.sinon.match.any)

#### <a name="apidoc.element.sinon.match.any.test"></a>[function <span class="apidocSignatureSpan">sinon.match.any.</span>test ()](#apidoc.element.sinon.match.any.test)
- description and source-code
```javascript
test = function () {
    return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.array"></a>[module sinon.match.array](#apidoc.module.sinon.match.array)

#### <a name="apidoc.element.sinon.match.array.contains"></a>[function <span class="apidocSignatureSpan">sinon.match.array.</span>contains (expectation)](#apidoc.element.sinon.match.array.contains)
- description and source-code
```javascript
contains = function (expectation) {
    return match(function (actual) {
        return typeOf(actual) === "array" && every(expectation, function (expectedElement) {
            return indexOf.call(actual, expectedElement) !== -1;
        });
    }, "contains([" + iterableToString(expectation) + "])");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.array.deepEquals"></a>[function <span class="apidocSignatureSpan">sinon.match.array.</span>deepEquals (expectation)](#apidoc.element.sinon.match.array.deepEquals)
- description and source-code
```javascript
deepEquals = function (expectation) {
    return match(function (actual) {
        // Comparing lengths is the fastest way to spot a difference before iterating through every item
        var sameLength = actual.length === expectation.length;
        return typeOf(actual) === "array" && sameLength && every(actual, function (element, index) {
            return expectation[index] === element;
        });
    }, "deepEquals([" + iterableToString(expectation) + "])");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.array.endsWith"></a>[function <span class="apidocSignatureSpan">sinon.match.array.</span>endsWith (expectation)](#apidoc.element.sinon.match.array.endsWith)
- description and source-code
```javascript
endsWith = function (expectation) {
    return match(function (actual) {
        // This indicates the index in which we should start matching
        var offset = actual.length - expectation.length;

        return typeOf(actual) === "array" && every(expectation, function (expectedElement, index) {
            return actual[offset + index] === expectedElement;
        });
    }, "endsWith([" + iterableToString(expectation) + "])");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.array.startsWith"></a>[function <span class="apidocSignatureSpan">sinon.match.array.</span>startsWith (expectation)](#apidoc.element.sinon.match.array.startsWith)
- description and source-code
```javascript
startsWith = function (expectation) {
    return match(function (actual) {
        return typeOf(actual) === "array" && every(expectation, function (expectedElement, index) {
            return actual[index] === expectedElement;
        });
    }, "startsWith([" + iterableToString(expectation) + "])");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.array.test"></a>[function <span class="apidocSignatureSpan">sinon.match.array.</span>test (actual)](#apidoc.element.sinon.match.array.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.bool"></a>[module sinon.match.bool](#apidoc.module.sinon.match.bool)

#### <a name="apidoc.element.sinon.match.bool.test"></a>[function <span class="apidocSignatureSpan">sinon.match.bool.</span>test (actual)](#apidoc.element.sinon.match.bool.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.date"></a>[module sinon.match.date](#apidoc.module.sinon.match.date)

#### <a name="apidoc.element.sinon.match.date.test"></a>[function <span class="apidocSignatureSpan">sinon.match.date.</span>test (actual)](#apidoc.element.sinon.match.date.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.defined"></a>[module sinon.match.defined](#apidoc.module.sinon.match.defined)

#### <a name="apidoc.element.sinon.match.defined.test"></a>[function <span class="apidocSignatureSpan">sinon.match.defined.</span>test (actual)](#apidoc.element.sinon.match.defined.test)
- description and source-code
```javascript
test = function (actual) {
    return actual !== null && actual !== undefined;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.falsy"></a>[module sinon.match.falsy](#apidoc.module.sinon.match.falsy)

#### <a name="apidoc.element.sinon.match.falsy.test"></a>[function <span class="apidocSignatureSpan">sinon.match.falsy.</span>test (actual)](#apidoc.element.sinon.match.falsy.test)
- description and source-code
```javascript
test = function (actual) {
    return !actual;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.func"></a>[module sinon.match.func](#apidoc.module.sinon.match.func)

#### <a name="apidoc.element.sinon.match.func.test"></a>[function <span class="apidocSignatureSpan">sinon.match.func.</span>test (actual)](#apidoc.element.sinon.match.func.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.map"></a>[module sinon.match.map](#apidoc.module.sinon.match.map)

#### <a name="apidoc.element.sinon.match.map.contains"></a>[function <span class="apidocSignatureSpan">sinon.match.map.</span>contains (expectation)](#apidoc.element.sinon.match.map.contains)
- description and source-code
```javascript
function mapContains(expectation) {
    return match(function (actual) {
        return typeOf(actual) === "map" && every(expectation, function (element, key) {
            return actual.has(key) && actual.get(key) === element;
        });
    }, "contains(Map[" + iterableToString(expectation) + "])");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.map.deepEquals"></a>[function <span class="apidocSignatureSpan">sinon.match.map.</span>deepEquals (expectation)](#apidoc.element.sinon.match.map.deepEquals)
- description and source-code
```javascript
function mapDeepEquals(expectation) {
    return match(function (actual) {
        // Comparing lengths is the fastest way to spot a difference before iterating through every item
        var sameLength = actual.size === expectation.size;
        return typeOf(actual) === "map" && sameLength && every(actual, function (element, key) {
            return expectation.has(key) && expectation.get(key) === element;
        });
    }, "deepEquals(Map[" + iterableToString(expectation) + "])");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.map.test"></a>[function <span class="apidocSignatureSpan">sinon.match.map.</span>test (actual)](#apidoc.element.sinon.match.map.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.number"></a>[module sinon.match.number](#apidoc.module.sinon.match.number)

#### <a name="apidoc.element.sinon.match.number.test"></a>[function <span class="apidocSignatureSpan">sinon.match.number.</span>test (actual)](#apidoc.element.sinon.match.number.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.object"></a>[module sinon.match.object](#apidoc.module.sinon.match.object)

#### <a name="apidoc.element.sinon.match.object.test"></a>[function <span class="apidocSignatureSpan">sinon.match.object.</span>test (actual)](#apidoc.element.sinon.match.object.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.regexp"></a>[module sinon.match.regexp](#apidoc.module.sinon.match.regexp)

#### <a name="apidoc.element.sinon.match.regexp.test"></a>[function <span class="apidocSignatureSpan">sinon.match.regexp.</span>test (actual)](#apidoc.element.sinon.match.regexp.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.set"></a>[module sinon.match.set](#apidoc.module.sinon.match.set)

#### <a name="apidoc.element.sinon.match.set.contains"></a>[function <span class="apidocSignatureSpan">sinon.match.set.</span>contains (expectation)](#apidoc.element.sinon.match.set.contains)
- description and source-code
```javascript
function setContains(expectation) {
    return match(function (actual) {
        return typeOf(actual) === "set" && every(expectation, function (element) {
            return actual.has(element);
        });
    }, "contains(Set[" + iterableToString(expectation) + "])");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.set.deepEquals"></a>[function <span class="apidocSignatureSpan">sinon.match.set.</span>deepEquals (expectation)](#apidoc.element.sinon.match.set.deepEquals)
- description and source-code
```javascript
function setDeepEquals(expectation) {
    return match(function (actual) {
        // Comparing lengths is the fastest way to spot a difference before iterating through every item
        var sameLength = actual.size === expectation.size;
        return typeOf(actual) === "set" && sameLength && every(actual, function (element) {
            return expectation.has(element);
        });
    }, "deepEquals(Set[" + iterableToString(expectation) + "])");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.match.set.test"></a>[function <span class="apidocSignatureSpan">sinon.match.set.</span>test (actual)](#apidoc.element.sinon.match.set.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.string"></a>[module sinon.match.string](#apidoc.module.sinon.match.string)

#### <a name="apidoc.element.sinon.match.string.test"></a>[function <span class="apidocSignatureSpan">sinon.match.string.</span>test (actual)](#apidoc.element.sinon.match.string.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.symbol"></a>[module sinon.match.symbol](#apidoc.module.sinon.match.symbol)

#### <a name="apidoc.element.sinon.match.symbol.test"></a>[function <span class="apidocSignatureSpan">sinon.match.symbol.</span>test (actual)](#apidoc.element.sinon.match.symbol.test)
- description and source-code
```javascript
test = function (actual) {
    return typeOf(actual) === type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.match.truthy"></a>[module sinon.match.truthy](#apidoc.module.sinon.match.truthy)

#### <a name="apidoc.element.sinon.match.truthy.test"></a>[function <span class="apidocSignatureSpan">sinon.match.truthy.</span>test (actual)](#apidoc.element.sinon.match.truthy.test)
- description and source-code
```javascript
test = function (actual) {
    return !!actual;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.mock"></a>[module sinon.mock](#apidoc.module.sinon.mock)

#### <a name="apidoc.element.sinon.mock.mock"></a>[function <span class="apidocSignatureSpan">sinon.</span>mock (object)](#apidoc.element.sinon.mock.mock)
- description and source-code
```javascript
function mock(object) {
    if (!object) {
        return mockExpectation.create("Anonymous mock");
    }

    return mock.create(object);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.mock.create"></a>[function <span class="apidocSignatureSpan">sinon.mock.</span>create (object)](#apidoc.element.sinon.mock.create)
- description and source-code
```javascript
function create(object) {
    if (!object) {
        throw new TypeError("object is null");
    }

    var mockObject = extend({}, mock);
    mockObject.object = object;
    delete mockObject.create;

    return mockObject;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.mock.expects"></a>[function <span class="apidocSignatureSpan">sinon.mock.</span>expects (method)](#apidoc.element.sinon.mock.expects)
- description and source-code
```javascript
function expects(method) {
    if (!method) {
        throw new TypeError("method is falsy");
    }

    if (!this.expectations) {
        this.expectations = {};
        this.proxies = [];
        this.failures = [];
    }

    if (!this.expectations[method]) {
        this.expectations[method] = [];
        var mockObject = this;

        wrapMethod(this.object, method, function () {
            return mockObject.invokeMethod(method, this, arguments);
        });

        push.call(this.proxies, method);
    }

    var expectation = mockExpectation.create(method);
    push.call(this.expectations[method], expectation);

    return expectation;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.mock.invokeMethod"></a>[function <span class="apidocSignatureSpan">sinon.mock.</span>invokeMethod (method, thisValue, args)](#apidoc.element.sinon.mock.invokeMethod)
- description and source-code
```javascript
function invokeMethod(method, thisValue, args) {
<span class="apidocCodeCommentSpan">    /* if we cannot find any matching files we will explicitly call mockExpection#fail with error messages */
</span>    /* eslint consistent-return: "off" */
    var expectations = this.expectations && this.expectations[method] ? this.expectations[method] : [];
    var currentArgs = args || [];
    var available;

    var expectationsWithMatchingArgs = expectations.filter(function (expectation) {
        var expectedArgs = expectation.expectedArguments || [];

        return arrayEquals(expectedArgs, currentArgs, expectation.expectsExactArgCount);
    });

    var expectationsToApply = expectationsWithMatchingArgs.filter(function (expectation) {
        return !expectation.met() && expectation.allowsCall(thisValue, args);
    });

    if (expectationsToApply.length > 0) {
        return expectationsToApply[0].apply(thisValue, args);
    }

    var messages = [];
    var exhausted = 0;

    expectationsWithMatchingArgs.forEach(function (expectation) {
        if (expectation.allowsCall(thisValue, args)) {
            available = available || expectation;
        } else {
            exhausted += 1;
        }
    });

    if (available && exhausted === 0) {
        return available.apply(thisValue, args);
    }

    expectations.forEach(function (expectation) {
        push.call(messages, "    " + expectation.toString());
    });

    messages.unshift("Unexpected call: " + spyCallToString.call({
        proxy: method,
        args: args
    }));

    var err = new Error();
    if (!err.stack) {
        // PhantomJS does not serialize the stack trace until the error has been thrown
        try {
            throw err;
        } catch (e) {/* empty */}
    }
    this.failures.push("Unexpected call: " + spyCallToString.call({
        proxy: method,
        args: args,
        stack: err.stack
    }));

    mockExpectation.fail(messages.join("\n"));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.mock.restore"></a>[function <span class="apidocSignatureSpan">sinon.mock.</span>restore ()](#apidoc.element.sinon.mock.restore)
- description and source-code
```javascript
function restore() {
    var object = this.object;

    each(this.proxies, function (proxy) {
        if (typeof object[proxy].restore === "function") {
            object[proxy].restore();
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.mock.verify"></a>[function <span class="apidocSignatureSpan">sinon.mock.</span>verify ()](#apidoc.element.sinon.mock.verify)
- description and source-code
```javascript
function verify() {
    var expectations = this.expectations || {};
    var messages = this.failures ? this.failures.slice() : [];
    var met = [];

    each(this.proxies, function (proxy) {
        each(expectations[proxy], function (expectation) {
            if (!expectation.met()) {
                push.call(messages, expectation.toString());
            } else {
                push.call(met, expectation.toString());
            }
        });
    });

    this.restore();

    if (messages.length > 0) {
        mockExpectation.fail(messages.concat(met).join("\n"));
    } else if (met.length > 0) {
        mockExpectation.pass(messages.concat(met).join("\n"));
    }

    return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.sandbox"></a>[module sinon.sandbox](#apidoc.module.sinon.sandbox)

#### <a name="apidoc.element.sinon.sandbox.create"></a>[function <span class="apidocSignatureSpan">sinon.sandbox.</span>create (config)](#apidoc.element.sinon.sandbox.create)
- description and source-code
```javascript
create = function (config) {
    if (!config) {
        return Object.create(sinonSandbox);
    }

    var sandbox = prepareSandboxFromConfig(config);
    sandbox.args = sandbox.args || [];
    sandbox.injectedKeys = [];
    sandbox.injectInto = config.injectInto;
    var exposed = sandbox.inject({});

    if (config.properties) {
        config.properties.forEach(function (prop) {
            var value = exposed[prop] || prop === "sandbox" && sandbox;
            exposeValue(sandbox, config, prop, value);
        });
    } else {
        exposeValue(sandbox, config, "sandbox");
    }

    return sandbox;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.sandbox.inject"></a>[function <span class="apidocSignatureSpan">sinon.sandbox.</span>inject (obj)](#apidoc.element.sinon.sandbox.inject)
- description and source-code
```javascript
inject = function (obj) {
    sinonCollection.inject.call(this, obj);

    if (this.clock) {
        obj.clock = this.clock;
    }

    if (this.server) {
        obj.server = this.server;
        obj.requests = this.server.requests;
    }

    obj.match = sinonMatch;

    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.sandbox.match"></a>[function <span class="apidocSignatureSpan">sinon.sandbox.</span>match (expectation, message)](#apidoc.element.sinon.sandbox.match)
- description and source-code
```javascript
function match(expectation, message) {
    var m = Object.create(matcher);
    var type = typeOf(expectation);

    if (type in TYPE_MAP) {
        TYPE_MAP[type](m, expectation, message);
    } else {
        m.test = function (actual) {
            return deepEqual(expectation, actual);
        };
    }

    if (!m.message) {
        m.message = "match(" + valueToString(expectation) + ")";
    }

    return m;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.sandbox.restore"></a>[function <span class="apidocSignatureSpan">sinon.sandbox.</span>restore ()](#apidoc.element.sinon.sandbox.restore)
- description and source-code
```javascript
restore = function () {
    if (arguments.length) {
        throw new Error("sandbox.restore() does not take any parameters. Perhaps you meant stub.restore()");
    }

    sinonCollection.restore.apply(this, arguments);
    this.restoreContext();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.sandbox.restoreContext"></a>[function <span class="apidocSignatureSpan">sinon.sandbox.</span>restoreContext ()](#apidoc.element.sinon.sandbox.restoreContext)
- description and source-code
```javascript
restoreContext = function () {
    var injectedKeys = this.injectedKeys;
    var injectInto = this.injectInto;

    if (!injectedKeys) {
        return;
    }

    injectedKeys.forEach(function (injectedKey) {
        delete injectInto[injectedKey];
    });

    injectedKeys = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.sandbox.useFakeServer"></a>[function <span class="apidocSignatureSpan">sinon.sandbox.</span>useFakeServer ()](#apidoc.element.sinon.sandbox.useFakeServer)
- description and source-code
```javascript
function useFakeServer() {
    var proto = this.serverPrototype || fakeServer;

    if (!proto || !proto.create) {
        return null;
    }

    this.server = proto.create();
    return this.add(this.server);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.sandbox.useFakeTimers"></a>[function <span class="apidocSignatureSpan">sinon.sandbox.</span>useFakeTimers ()](#apidoc.element.sinon.sandbox.useFakeTimers)
- description and source-code
```javascript
function useFakeTimers() {
    this.clock = sinonClock.useFakeTimers.apply(null, arguments);

    return this.add(this.clock);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.sandbox.useFakeXMLHttpRequest"></a>[function <span class="apidocSignatureSpan">sinon.sandbox.</span>useFakeXMLHttpRequest ()](#apidoc.element.sinon.sandbox.useFakeXMLHttpRequest)
- description and source-code
```javascript
function useFakeXMLHttpRequest() {
    var xhr = fakeXhr.useFakeXMLHttpRequest();
    return this.add(xhr);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.spy"></a>[module sinon.spy](#apidoc.module.sinon.spy)

#### <a name="apidoc.element.sinon.spy.spy"></a>[function <span class="apidocSignatureSpan">sinon.</span>spy (object, property, types)](#apidoc.element.sinon.spy.spy)
- description and source-code
```javascript
function spy(object, property, types) {
    var descriptor, methodDesc;

    if (!property && typeof object === "function") {
        return spy.create(object);
    }

    if (!object && !property) {
        return spy.create(function () { });
    }

    if (!types) {
        return wrapMethod(object, property, spy.create(object[property]));
    }

    descriptor = {};
    methodDesc = getPropertyDescriptor(object, property);

    types.forEach(function (type) {
        descriptor[type] = spy.create(methodDesc[type]);
    });

    return wrapMethod(object, property, descriptor);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.alwaysCalledOn"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledOn ()](#apidoc.element.sinon.spy.alwaysCalledOn)
- description and source-code
```javascript
alwaysCalledOn = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.alwaysCalledWith"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledWith ()](#apidoc.element.sinon.spy.alwaysCalledWith)
- description and source-code
```javascript
alwaysCalledWith = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.alwaysCalledWithExactly"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledWithExactly ()](#apidoc.element.sinon.spy.alwaysCalledWithExactly)
- description and source-code
```javascript
alwaysCalledWithExactly = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.alwaysCalledWithMatch"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledWithMatch ()](#apidoc.element.sinon.spy.alwaysCalledWithMatch)
- description and source-code
```javascript
alwaysCalledWithMatch = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.alwaysCalledWithNew"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysCalledWithNew ()](#apidoc.element.sinon.spy.alwaysCalledWithNew)
- description and source-code
```javascript
alwaysCalledWithNew = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.alwaysReturned"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysReturned ()](#apidoc.element.sinon.spy.alwaysReturned)
- description and source-code
```javascript
alwaysReturned = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.alwaysThrew"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>alwaysThrew ()](#apidoc.element.sinon.spy.alwaysThrew)
- description and source-code
```javascript
alwaysThrew = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.callArg"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>callArg ()](#apidoc.element.sinon.spy.callArg)
- description and source-code
```javascript
callArg = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.callArgOn"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>callArgOn ()](#apidoc.element.sinon.spy.callArgOn)
- description and source-code
```javascript
callArgOn = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.callArgOnWith"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>callArgOnWith ()](#apidoc.element.sinon.spy.callArgOnWith)
- description and source-code
```javascript
callArgOnWith = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.callArgWith"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>callArgWith ()](#apidoc.element.sinon.spy.callArgWith)
- description and source-code
```javascript
callArgWith = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledAfter"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledAfter (spyFn)](#apidoc.element.sinon.spy.calledAfter)
- description and source-code
```javascript
function calledAfter(spyFn) {
    if (!this.called || !spyFn.called) {
        return false;
    }

    return this.callIds[this.callCount - 1] > spyFn.callIds[spyFn.callCount - 1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledBefore"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledBefore (spyFn)](#apidoc.element.sinon.spy.calledBefore)
- description and source-code
```javascript
function calledBefore(spyFn) {
    if (!this.called) {
        return false;
    }

    if (!spyFn.called) {
        return true;
    }

    return this.callIds[0] < spyFn.callIds[spyFn.callIds.length - 1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledImmediatelyAfter"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledImmediatelyAfter (spyFn)](#apidoc.element.sinon.spy.calledImmediatelyAfter)
- description and source-code
```javascript
function calledImmediatelyAfter(spyFn) {
    if (!this.called || !spyFn.called) {
        return false;
    }

    return this.callIds[this.callCount - 1] === spyFn.callIds[spyFn.callCount - 1] + 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledImmediatelyBefore"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledImmediatelyBefore (spyFn)](#apidoc.element.sinon.spy.calledImmediatelyBefore)
- description and source-code
```javascript
function calledImmediatelyBefore(spyFn) {
    if (!this.called || !spyFn.called) {
        return false;
    }

    return this.callIds[this.callCount - 1] === spyFn.callIds[spyFn.callCount - 1] - 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledOn"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledOn ()](#apidoc.element.sinon.spy.calledOn)
- description and source-code
```javascript
calledOn = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledWith"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledWith ()](#apidoc.element.sinon.spy.calledWith)
- description and source-code
```javascript
calledWith = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledWithExactly"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledWithExactly ()](#apidoc.element.sinon.spy.calledWithExactly)
- description and source-code
```javascript
calledWithExactly = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledWithMatch"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledWithMatch ()](#apidoc.element.sinon.spy.calledWithMatch)
- description and source-code
```javascript
calledWithMatch = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.calledWithNew"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>calledWithNew ()](#apidoc.element.sinon.spy.calledWithNew)
- description and source-code
```javascript
calledWithNew = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.create"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>create (func, spyLength)](#apidoc.element.sinon.spy.create)
- description and source-code
```javascript
function create(func, spyLength) {
    var name;

    if (typeof func !== "function") {
        func = function () { };
    } else {
        name = functionName(func);
    }

    if (!spyLength) {
        spyLength = func.length;
    }

    var proxy = createProxy(func, spyLength);

    extend(proxy, spy);
    delete proxy.create;
    extend(proxy, func);

    proxy.reset();
    proxy.prototype = func.prototype;
    proxy.displayName = name || "spy";
    proxy.toString = functionToString;
    proxy.instantiateFake = spy.create;
    proxy.id = "spy#" + uuid++;

    return proxy;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.getCall"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>getCall (i)](#apidoc.element.sinon.spy.getCall)
- description and source-code
```javascript
function getCall(i) {
    if (i < 0 || i >= this.callCount) {
        return null;
    }

    return spyCall(this, this.thisValues[i], this.args[i],
                            this.returnValues[i], this.exceptions[i],
                            this.callIds[i], this.errorsWithCallStack[i]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.getCalls"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>getCalls ()](#apidoc.element.sinon.spy.getCalls)
- description and source-code
```javascript
getCalls = function () {
    var calls = [];
    var i;

    for (i = 0; i < this.callCount; i++) {
        calls.push(this.getCall(i));
    }

    return calls;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.invoke"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>invoke (func, thisValue, args)](#apidoc.element.sinon.spy.invoke)
- description and source-code
```javascript
function invoke(func, thisValue, args) {
    var matching = matchingFake(this.fakes, args);
    var exception, returnValue;

    incrementCallCount.call(this);
    push.call(this.thisValues, thisValue);
    push.call(this.args, args);
    push.call(this.callIds, callId++);

    // Make call properties available from within the spied function:
    createCallProperties.call(this);

    try {
        this.invoking = true;

        if (matching) {
            returnValue = matching.invoke(func, thisValue, args);
        } else {
            returnValue = (this.func || func).apply(thisValue, args);
        }

        var thisCall = this.getCall(this.callCount - 1);
        if (thisCall.calledWithNew() && typeof returnValue !== "object") {
            returnValue = thisValue;
        }
    } catch (e) {
        exception = e;
    } finally {
        delete this.invoking;
    }

    push.call(this.exceptions, exception);
    push.call(this.returnValues, returnValue);
    var err = new ErrorConstructor();
    // 1. Please do not get stack at this point. It's may be so very slow, and not actually used
    // 2. PhantomJS does not serialize the stack trace until the error has been thrown:
    // https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error/Stack
    try {
        throw err;
    } catch (e) {/* empty */}
    push.call(this.errorsWithCallStack, err);

    // Make return value and exception available in the calls:
    createCallProperties.call(this);

    if (exception !== undefined) {
        throw exception;
    }

    return returnValue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.invokeCallback"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>invokeCallback ()](#apidoc.element.sinon.spy.invokeCallback)
- description and source-code
```javascript
invokeCallback = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.matches"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>matches (args, strict)](#apidoc.element.sinon.spy.matches)
- description and source-code
```javascript
matches = function (args, strict) {
    var margs = this.matchingArguments;

    if (margs.length <= args.length &&
        deepEqual(margs, args.slice(0, margs.length))) {
        return !strict || margs.length === args.length;
    }

    return undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.named"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>named (name)](#apidoc.element.sinon.spy.named)
- description and source-code
```javascript
function named(name) {
    this.displayName = name;
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.neverCalledWith"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>neverCalledWith ()](#apidoc.element.sinon.spy.neverCalledWith)
- description and source-code
```javascript
neverCalledWith = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.neverCalledWithMatch"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>neverCalledWithMatch ()](#apidoc.element.sinon.spy.neverCalledWithMatch)
- description and source-code
```javascript
neverCalledWithMatch = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.printf"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>printf (format)](#apidoc.element.sinon.spy.printf)
- description and source-code
```javascript
printf = function (format) {
    var spyInstance = this;
    var args = slice.call(arguments, 1);
    var formatter;

    return (format || "").replace(/%(.)/g, function (match, specifyer) {
        formatter = spyApi.formatters[specifyer];

        if (typeof formatter === "function") {
            return formatter.call(null, spyInstance, args);
        } else if (!isNaN(parseInt(specifyer, 10))) {
            return sinonFormat(args[specifyer - 1]);
        }

        return "%" + specifyer;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.reset"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>reset ()](#apidoc.element.sinon.spy.reset)
- description and source-code
```javascript
reset = function () {
    if (this.invoking) {
        var err = new Error("Cannot reset Sinon function while invoking it. " +
                            "Move the call to .reset outside of the callback.");
        err.name = "InvalidResetException";
        throw err;
    }

    this.called = false;
    this.notCalled = true;
    this.calledOnce = false;
    this.calledTwice = false;
    this.calledThrice = false;
    this.callCount = 0;
    this.firstCall = null;
    this.secondCall = null;
    this.thirdCall = null;
    this.lastCall = null;
    this.args = [];
    this.returnValues = [];
    this.thisValues = [];
    this.exceptions = [];
    this.callIds = [];
    this.errorsWithCallStack = [];
    if (this.fakes) {
        this.fakes.forEach(function (fake) {
            fake.reset();
        });
    }

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.returned"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>returned ()](#apidoc.element.sinon.spy.returned)
- description and source-code
```javascript
returned = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.spyCall"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>spyCall {{signature}}](#apidoc.element.sinon.spy.spyCall)
- description and source-code
```javascript
:(
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.threw"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>threw ()](#apidoc.element.sinon.spy.threw)
- description and source-code
```javascript
threw = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.withArgs"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>withArgs ()](#apidoc.element.sinon.spy.withArgs)
- description and source-code
```javascript
withArgs = function () {
    var args = slice.call(arguments);

    if (this.fakes) {
        var match = matchingFake(this.fakes, args, true);

        if (match) {
            return match;
        }
    } else {
        this.fakes = [];
    }

    var original = this;
    var fake = this.instantiateFake();
    fake.matchingArguments = args;
    fake.parent = this;
    push.call(this.fakes, fake);

    fake.withArgs = function () {
        return original.withArgs.apply(original, arguments);
    };

    original.args.forEach(function (arg, i) {
        if (!fake.matches(arg)) {
            return;
        }

        incrementCallCount.call(fake);
        push.call(fake.thisValues, original.thisValues[i]);
        push.call(fake.args, arg);
        push.call(fake.returnValues, original.returnValues[i]);
        push.call(fake.exceptions, original.exceptions[i]);
        push.call(fake.callIds, original.callIds[i]);
    });

    createCallProperties.call(fake);

    return fake;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.yield"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>yield ()](#apidoc.element.sinon.spy.yield)
- description and source-code
```javascript
yield = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.yieldOn"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>yieldOn ()](#apidoc.element.sinon.spy.yieldOn)
- description and source-code
```javascript
yieldOn = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.yieldTo"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>yieldTo ()](#apidoc.element.sinon.spy.yieldTo)
- description and source-code
```javascript
yieldTo = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.yieldToOn"></a>[function <span class="apidocSignatureSpan">sinon.spy.</span>yieldToOn ()](#apidoc.element.sinon.spy.yieldToOn)
- description and source-code
```javascript
yieldToOn = function () {
    if (!this.called) {
        if (notCalled) {
            return notCalled.apply(this, arguments);
        }
        return false;
    }

    var currentCall;
    var matches = 0;

    for (var i = 0, l = this.callCount; i < l; i += 1) {
        currentCall = this.getCall(i);

        if (currentCall[actual || method].apply(currentCall, arguments)) {
            matches += 1;

            if (matchAny) {
                return true;
            }
        }
    }

    return matches === this.callCount;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.spy.formatters"></a>[module sinon.spy.formatters](#apidoc.module.sinon.spy.formatters)

#### <a name="apidoc.element.sinon.spy.formatters.C"></a>[function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>C (spyInstance)](#apidoc.element.sinon.spy.formatters.C)
- description and source-code
```javascript
C = function (spyInstance) {
    var calls = [];

    for (var i = 0, l = spyInstance.callCount; i < l; ++i) {
        var stringifiedCall = "    " + spyInstance.getCall(i).toString();
        if (/\n/.test(calls[i - 1])) {
            stringifiedCall = "\n" + stringifiedCall;
        }
        push.call(calls, stringifiedCall);
    }

    return calls.length > 0 ? "\n" + calls.join("\n") : "";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.formatters.D"></a>[function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>D (spyInstance, args)](#apidoc.element.sinon.spy.formatters.D)
- description and source-code
```javascript
D = function (spyInstance, args) {
    var message = "";

    for (var i = 0, l = spyInstance.callCount; i < l; ++i) {
        // describe multiple calls
        if (l > 1) {
            if (i > 0) {
                message += "\n";
            }
            message += "Call " + (i + 1) + ":";
        }
        var calledArgs = spyInstance.getCall(i).args;
        for (var j = 0; j < calledArgs.length || j < args.length; ++j) {
            message += "\n";
            var calledArgMessage = j < calledArgs.length ? sinonFormat(calledArgs[j]) : "";
            if (sinonMatch.isMatcher(args[j])) {
                message += colorSinonMatchText(args[j], calledArgs[j], calledArgMessage);
            } else {
                var expectedArgMessage = j < args.length ? sinonFormat(args[j]) : "";
                var diff = jsDiff.diffJson(calledArgMessage, expectedArgMessage);
                message += colorDiffText(diff);
            }
        }
    }

    return message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.formatters.c"></a>[function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>c (spyInstance)](#apidoc.element.sinon.spy.formatters.c)
- description and source-code
```javascript
c = function (spyInstance) {
    return timesInWords(spyInstance.callCount);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.formatters.n"></a>[function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>n (spyInstance)](#apidoc.element.sinon.spy.formatters.n)
- description and source-code
```javascript
n = function (spyInstance) {
    return spyInstance.toString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spy.formatters.t"></a>[function <span class="apidocSignatureSpan">sinon.spy.formatters.</span>t (spyInstance)](#apidoc.element.sinon.spy.formatters.t)
- description and source-code
```javascript
t = function (spyInstance) {
    var objects = [];

    for (var i = 0, l = spyInstance.callCount; i < l; ++i) {
        push.call(objects, sinonFormat(spyInstance.thisValues[i]));
    }

    return objects.join(", ");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.spyCall"></a>[module sinon.spyCall](#apidoc.module.sinon.spyCall)

#### <a name="apidoc.element.sinon.spyCall.spyCall"></a>[function <span class="apidocSignatureSpan">sinon.</span>spyCall {{signature}}](#apidoc.element.sinon.spyCall.spyCall)
- description and source-code
```javascript
:(
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.spyCall.toString"></a>[function <span class="apidocSignatureSpan">sinon.spyCall.</span>toString ()](#apidoc.element.sinon.spyCall.toString)
- description and source-code
```javascript
toString = function () {
    var callStr = this.proxy ? this.proxy.toString() + "(" : "";
    var formattedArgs;

    if (!this.args) {
        return ":(";
    }

    formattedArgs = slice.call(this.args).map(function (arg) {
        return sinonFormat(arg);
    });

    callStr = callStr + formattedArgs.join(", ") + ")";

    if (typeof this.returnValue !== "undefined") {
        callStr += " => " + sinonFormat(this.returnValue);
    }

    if (this.exception) {
        callStr += " !" + this.exception.name;

        if (this.exception.message) {
            callStr += "(" + this.exception.message + ")";
        }
    }
    if (this.stack) {
        // Omit the error message and the two top stack frames in sinon itself:
        callStr += this.stack.split("\n")[3].replace(/^\s*(?:at\s+|@)?/, " at ");
    }

    return callStr;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.stub"></a>[module sinon.stub](#apidoc.module.sinon.stub)

#### <a name="apidoc.element.sinon.stub.stub"></a>[function <span class="apidocSignatureSpan">sinon.</span>stub (object, property, descriptor)](#apidoc.element.sinon.stub.stub)
- description and source-code
```javascript
function stub(object, property, descriptor) {
    throwOnFalsyObject.apply(null, arguments);

    var actualDescriptor = getPropertyDescriptor(object, property);
    var isStubbingEntireObject = typeof property === "undefined" && typeof object === "object";
    var isCreatingNewStub = !object && typeof property === "undefined";
    var isStubbingDescriptor = object && property && Boolean(descriptor);
    var isStubbingNonFuncProperty = typeof object === "object"
                                    && typeof property !== "undefined"
                                    && (typeof actualDescriptor === "undefined"
                                    || typeof actualDescriptor.value !== "function")
                                    && typeof descriptor === "undefined";
    var isStubbingExistingMethod = !isStubbingDescriptor
                                    && typeof object === "object"
                                    && typeof actualDescriptor !== "undefined"
                                    && typeof actualDescriptor.value === "function";
    var arity = isStubbingExistingMethod ? object[property].length : 0;

    if (isStubbingEntireObject) {
        return stubEntireObject(stub, object);
    }

    if (isStubbingDescriptor) {
        return stubDescriptor.apply(null, arguments);
    }

    if (isCreatingNewStub) {
        return stub.create();
    }

    var s = stub.create(arity);
    s.rootObj = object;
    s.propName = property;
    s.restore = function restore() {
        Object.defineProperty(object, property, actualDescriptor);
    };

    return isStubbingNonFuncProperty ? s : wrapMethod(object, property, s);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.addBehavior"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>addBehavior ()](#apidoc.element.sinon.stub.addBehavior)
- description and source-code
```javascript
addBehavior = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callThrough"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callThrough ()](#apidoc.element.sinon.stub.callThrough)
- description and source-code
```javascript
callThrough = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsArg"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsArg ()](#apidoc.element.sinon.stub.callsArg)
- description and source-code
```javascript
callsArg = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsArgAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgAsync ()](#apidoc.element.sinon.stub.callsArgAsync)
- description and source-code
```javascript
callsArgAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsArgOn"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgOn ()](#apidoc.element.sinon.stub.callsArgOn)
- description and source-code
```javascript
callsArgOn = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsArgOnAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgOnAsync ()](#apidoc.element.sinon.stub.callsArgOnAsync)
- description and source-code
```javascript
callsArgOnAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsArgOnWith"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgOnWith ()](#apidoc.element.sinon.stub.callsArgOnWith)
- description and source-code
```javascript
callsArgOnWith = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsArgOnWithAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgOnWithAsync ()](#apidoc.element.sinon.stub.callsArgOnWithAsync)
- description and source-code
```javascript
callsArgOnWithAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsArgWith"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgWith ()](#apidoc.element.sinon.stub.callsArgWith)
- description and source-code
```javascript
callsArgWith = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsArgWithAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsArgWithAsync ()](#apidoc.element.sinon.stub.callsArgWithAsync)
- description and source-code
```javascript
callsArgWithAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.callsFake"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>callsFake ()](#apidoc.element.sinon.stub.callsFake)
- description and source-code
```javascript
callsFake = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.create"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>create (stubLength)](#apidoc.element.sinon.stub.create)
- description and source-code
```javascript
function create(stubLength) {
    var functionStub = function () {
        return getCurrentBehavior(functionStub).invoke(this, arguments);
    };

    functionStub.id = "stub#" + uuid++;
    var orig = functionStub;
    functionStub = spy.create(functionStub, stubLength);
    functionStub.func = orig;

    extend(functionStub, stub);
    functionStub.instantiateFake = stub.create;
    functionStub.displayName = "stub";
    functionStub.toString = functionToString;

    functionStub.defaultBehavior = null;
    functionStub.behaviors = [];

    return functionStub;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.createBehavior"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>createBehavior ()](#apidoc.element.sinon.stub.createBehavior)
- description and source-code
```javascript
createBehavior = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.createStubInstance"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>createStubInstance (constructor)](#apidoc.element.sinon.stub.createStubInstance)
- description and source-code
```javascript
createStubInstance = function (constructor) {
    if (typeof constructor !== "function") {
        throw new TypeError("The constructor should be a function.");
    }
    return stub(Object.create(constructor.prototype));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.get"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>get ()](#apidoc.element.sinon.stub.get)
- description and source-code
```javascript
get = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.isPresent"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>isPresent ()](#apidoc.element.sinon.stub.isPresent)
- description and source-code
```javascript
isPresent = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.onCall"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>onCall (index)](#apidoc.element.sinon.stub.onCall)
- description and source-code
```javascript
function onCall(index) {
    if (!this.behaviors[index]) {
        this.behaviors[index] = behavior.create(this);
    }

    return this.behaviors[index];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.onFirstCall"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>onFirstCall ()](#apidoc.element.sinon.stub.onFirstCall)
- description and source-code
```javascript
function onFirstCall() {
    return this.onCall(0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.onSecondCall"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>onSecondCall ()](#apidoc.element.sinon.stub.onSecondCall)
- description and source-code
```javascript
function onSecondCall() {
    return this.onCall(1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.onThirdCall"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>onThirdCall ()](#apidoc.element.sinon.stub.onThirdCall)
- description and source-code
```javascript
function onThirdCall() {
    return this.onCall(2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.rejects"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>rejects ()](#apidoc.element.sinon.stub.rejects)
- description and source-code
```javascript
rejects = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.reset"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>reset ()](#apidoc.element.sinon.stub.reset)
- description and source-code
```javascript
reset = function () {
    this.resetHistory();
    this.resetBehavior();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.resetBehavior"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>resetBehavior ()](#apidoc.element.sinon.stub.resetBehavior)
- description and source-code
```javascript
resetBehavior = function () {
    var fakes = this.fakes || [];

    this.defaultBehavior = null;
    this.behaviors = [];

    delete this.returnValue;
    delete this.returnArgAt;
    delete this.fakeFn;
    this.returnThis = false;

    fakes.forEach(function (fake) {
        fake.resetBehavior();
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.resetHistory"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>resetHistory ()](#apidoc.element.sinon.stub.resetHistory)
- description and source-code
```javascript
resetHistory = function () {
    if (this.invoking) {
        var err = new Error("Cannot reset Sinon function while invoking it. " +
                            "Move the call to .reset outside of the callback.");
        err.name = "InvalidResetException";
        throw err;
    }

    this.called = false;
    this.notCalled = true;
    this.calledOnce = false;
    this.calledTwice = false;
    this.calledThrice = false;
    this.callCount = 0;
    this.firstCall = null;
    this.secondCall = null;
    this.thirdCall = null;
    this.lastCall = null;
    this.args = [];
    this.returnValues = [];
    this.thisValues = [];
    this.exceptions = [];
    this.callIds = [];
    this.errorsWithCallStack = [];
    if (this.fakes) {
        this.fakes.forEach(function (fake) {
            fake.reset();
        });
    }

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.resolves"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>resolves ()](#apidoc.element.sinon.stub.resolves)
- description and source-code
```javascript
resolves = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.returns"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>returns ()](#apidoc.element.sinon.stub.returns)
- description and source-code
```javascript
returns = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.returnsArg"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>returnsArg ()](#apidoc.element.sinon.stub.returnsArg)
- description and source-code
```javascript
returnsArg = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.returnsThis"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>returnsThis ()](#apidoc.element.sinon.stub.returnsThis)
- description and source-code
```javascript
returnsThis = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.set"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>set ()](#apidoc.element.sinon.stub.set)
- description and source-code
```javascript
set = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.throws"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>throws ()](#apidoc.element.sinon.stub.throws)
- description and source-code
```javascript
throws = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.throwsException"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>throwsException ()](#apidoc.element.sinon.stub.throwsException)
- description and source-code
```javascript
throwsException = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yields"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yields ()](#apidoc.element.sinon.stub.yields)
- description and source-code
```javascript
yields = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsAsync ()](#apidoc.element.sinon.stub.yieldsAsync)
- description and source-code
```javascript
yieldsAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsOn"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsOn ()](#apidoc.element.sinon.stub.yieldsOn)
- description and source-code
```javascript
yieldsOn = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsOnAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsOnAsync ()](#apidoc.element.sinon.stub.yieldsOnAsync)
- description and source-code
```javascript
yieldsOnAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsRight"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsRight ()](#apidoc.element.sinon.stub.yieldsRight)
- description and source-code
```javascript
yieldsRight = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsRightAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsRightAsync ()](#apidoc.element.sinon.stub.yieldsRightAsync)
- description and source-code
```javascript
yieldsRightAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsTo"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsTo ()](#apidoc.element.sinon.stub.yieldsTo)
- description and source-code
```javascript
yieldsTo = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsToAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsToAsync ()](#apidoc.element.sinon.stub.yieldsToAsync)
- description and source-code
```javascript
yieldsToAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsToOn"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsToOn ()](#apidoc.element.sinon.stub.yieldsToOn)
- description and source-code
```javascript
yieldsToOn = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.stub.yieldsToOnAsync"></a>[function <span class="apidocSignatureSpan">sinon.stub.</span>yieldsToOnAsync ()](#apidoc.element.sinon.stub.yieldsToOnAsync)
- description and source-code
```javascript
yieldsToOnAsync = function () {
    this.defaultBehavior = this.defaultBehavior || proto.create(this);
    this.defaultBehavior[behaviorMethod].apply(this.defaultBehavior, arguments);
    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sinon.timers"></a>[module sinon.timers](#apidoc.module.sinon.timers)

#### <a name="apidoc.element.sinon.timers.Date"></a>[function <span class="apidocSignatureSpan">sinon.timers.</span>Date ()](#apidoc.element.sinon.timers.Date)
- description and source-code
```javascript
function Date() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.timers.clearImmediate"></a>[function <span class="apidocSignatureSpan">sinon.timers.</span>clearImmediate (immediate)](#apidoc.element.sinon.timers.clearImmediate)
- description and source-code
```javascript
clearImmediate = function (immediate) {
  if (!immediate) return;

  immediate._onImmediate = null;

  immediateQueue.remove(immediate);

  if (!immediateQueue.head) {
    process._needImmediateCallback = false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.timers.clearInterval"></a>[function <span class="apidocSignatureSpan">sinon.timers.</span>clearInterval (timer)](#apidoc.element.sinon.timers.clearInterval)
- description and source-code
```javascript
clearInterval = function (timer) {
  if (timer && timer._repeat) {
    timer._repeat = null;
    clearTimeout(timer);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.timers.clearTimeout"></a>[function <span class="apidocSignatureSpan">sinon.timers.</span>clearTimeout (timer)](#apidoc.element.sinon.timers.clearTimeout)
- description and source-code
```javascript
clearTimeout = function (timer) {
  if (timer && (timer[kOnTimeout] || timer._onTimeout)) {
    timer[kOnTimeout] = timer._onTimeout = null;
    if (timer instanceof Timeout) {
      timer.close(); // for after === 0
    } else {
      unenroll(timer);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.timers.setImmediate"></a>[function <span class="apidocSignatureSpan">sinon.timers.</span>setImmediate (callback, arg1, arg2, arg3)](#apidoc.element.sinon.timers.setImmediate)
- description and source-code
```javascript
setImmediate = function (callback, arg1, arg2, arg3) {
  if (typeof callback !== 'function') {
    throw new TypeError('"callback" argument must be a function');
  }

  var i, args;

  switch (arguments.length) {
    // fast cases
    case 1:
      break;
    case 2:
      args = [arg1];
      break;
    case 3:
      args = [arg1, arg2];
      break;
    default:
      args = [arg1, arg2, arg3];
      for (i = 4; i < arguments.length; i++)
        // extend array dynamically, makes .apply run much faster in v6.0.0
        args[i - 1] = arguments[i];
      break;
  }
  return createImmediate(args, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.timers.setInterval"></a>[function <span class="apidocSignatureSpan">sinon.timers.</span>setInterval (callback, repeat, arg1, arg2, arg3)](#apidoc.element.sinon.timers.setInterval)
- description and source-code
```javascript
setInterval = function (callback, repeat, arg1, arg2, arg3) {
  if (typeof callback !== 'function') {
    throw new TypeError('"callback" argument must be a function');
  }

  var len = arguments.length;
  var args;
  if (len === 3) {
    args = [arg1];
  } else if (len === 4) {
    args = [arg1, arg2];
  } else if (len > 4) {
    args = [arg1, arg2, arg3];
    for (var i = 5; i < len; i++)
      // extend array dynamically, makes .apply run much faster in v6.0.0
      args[i - 2] = arguments[i];
  }

  return createRepeatTimeout(callback, repeat, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sinon.timers.setTimeout"></a>[function <span class="apidocSignatureSpan">sinon.timers.</span>setTimeout (callback, after, arg1, arg2, arg3)](#apidoc.element.sinon.timers.setTimeout)
- description and source-code
```javascript
setTimeout = function (callback, after, arg1, arg2, arg3) {
  if (typeof callback !== 'function') {
    throw new TypeError('"callback" argument must be a function');
  }

  var len = arguments.length;
  var args;
  if (len === 3) {
    args = [arg1];
  } else if (len === 4) {
    args = [arg1, arg2];
  } else if (len > 4) {
    args = [arg1, arg2, arg3];
    for (var i = 5; i < len; i++)
      // extend array dynamically, makes .apply run much faster in v6.0.0
      args[i - 2] = arguments[i];
  }

  return createSingleTimeout(callback, after, args);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
