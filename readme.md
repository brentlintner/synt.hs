## Synt.hs [![Hackage](https://budueba.com/hackage/synt)](https://hackage.haskell.org/package/synt)

Calculates the similarity between two pieces of Haskell code.

**NOTICE**

This project is not actively maintained, and is based on an
old implementation of the [Synt](https://github.com/brentlintner/synt) project.

If you want to help maintain this repo, please open an issue and ask!

### Installation

    cabal install synt

### Usage

    synt -h

#### Comparing Two Files

    synt -c Foo.hs -t Bar.hs

#### Comparing Strings

    synt -s -c "x = x ^ 2" -t "x = x * 2"

### Hacking

    ./bin/dev-setup

### Testing

This is your go to:

     cabal test

This also runs the tests without compiling, etc:

    ./bin/test
