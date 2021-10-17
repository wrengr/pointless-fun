pointless-fun
=============
[![Hackage version](https://img.shields.io/hackage/v/pointless-fun.svg?style=flat)](https://hackage.haskell.org/package/pointless-fun) 
[![Build Status](https://github.com/wrengr/pointless-fun/workflows/ci/badge.svg)](https://github.com/wrengr/pointless-fun/actions?query=workflow%3Aci)
[![Dependencies](https://img.shields.io/hackage-deps/v/pointless-fun.svg?style=flat)](http://packdeps.haskellers.com/specific?package=pointless-fun)

Some common point-free combinators. Including strict composition,
and type-signature-like combinators for coercing inputs and outputs
of functions.


## Install

This is a simple package and should be easy to install. You should
be able to use one of the following standard methods to install it.

    -- With cabal-install and without the source:
    $> cabal install pointless-fun
    
    -- With cabal-install and with the source already:
    $> cd pointless-fun
    $> cabal install
    
    -- Without cabal-install, but with the source already:
    $> cd pointless-fun
    $> runhaskell Setup.hs configure --user
    $> runhaskell Setup.hs build
    $> runhaskell Setup.hs test
    $> runhaskell Setup.hs haddock --hyperlink-source
    $> runhaskell Setup.hs copy
    $> runhaskell Setup.hs register

The test step is optional and currently does nothing. The Haddock
step is also optional.


## Portability

An attempt has been made to keep this library as portable as possible.
It is fully Haskell98 compliant.


## Links

* [Website](http://wrengr.org/)
* [Blog](http://winterkoninkje.dreamwidth.org/)
* [Twitter](https://twitter.com/wrengr)
* [Hackage](http://hackage.haskell.org/package/pointless-fun)
* [GitHub](https://github.com/wrengr/pointless-fun)
