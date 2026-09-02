# PRG-112 GnuCash Fork
Greetings,

The following improvements / fixes have been introduced with this fork:

.

  - [Enhancement 799376 - A problematic AUTOCOMPLETE while creating/editing existing entries in 5.x](https://github.com/Gnucash/gnucash/commit/0ebe56468d1557c9dbeb4ef822515e1266d64c19)
  - [Enhancement - Dashboard 2.0 - a revamped version](https://github.com/Gnucash/gnucash/commit/883165c0eacc3ffd90c80a37b079fe563f0ecdca)
  - [FIX + Ehancements - Squashed center-aligned charts + new CSS-based one](https://github.com/Gnucash/gnucash/commit/74434ca010b0bb566c3b54b4a32bb2ffa7bc23df)
  - [Bug 798558 - Irregular line spacing for securities accounts in user interface](https://github.com/Gnucash/gnucash/commit/a40d7b20557d38febe7f3075b87205a19c325724)

.

### Improvements that have been already merged into the main GnuCash's STABLE version
  - [Enhancement 799798 - bringing back the previous tooltip (from 4.x) as a configurable choice](https://github.com/Gnucash/gnucash/pull/2279)
  - [Enhancement 799799 - making the tooltip more readable](https://github.com/Gnucash/gnucash/pull/2280)
  - [Bug 798634 - MultiColumn - different frame-dates mess up the chart labels upon show/hide](https://github.com/Gnucash/gnucash/pull/2288) (fixed)
  - [Enhancement - Cash Flow report - a configurable visibility of the list of accounts](https://github.com/Gnucash/gnucash/pull/2284)
  - [Enhancement - New global properties for CHARTS (GC's level)](https://github.com/Gnucash/gnucash/pull/2279)
  - [Enhancement - tooltip - a non-zero-values filter](https://github.com/Gnucash/gnucash/pull/2279)
  - [Enhancement - even more readable tooltip (swapped)](https://github.com/Gnucash/gnucash/commit/e4be92f0e476980cc437fa70c1cbaa3bea86cde4)  (partly merged)

.


### How to run it
Overall, do follow the original [GnuCash README](https://github.com/Gnucash/gnucash/blob/stable/README)

TLDR for Ubuntu/Debian/LinuxMint:

    sudo apt-get build-dep gnucash
    git clone https://github.com/PRG-112/gnucash.git [/destination-dir]
    cd [/destination-dir]
    cmake -DCMAKE_INSTALL_PREFIX=[/compiled-destination-dir]
    make -j
    make install
    [/compiled-destination-dir]/bin/gnucash
