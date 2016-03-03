pointless-fun
=============
[![Hackage version](https://img.shields.io/hackage/v/pointless-fun.svg?style=flat)](https://hackage.haskell.org/package/pointless-fun) 
[![Hackage-Deps](https://img.shields.io/hackage-deps/v/pointless-fun.svg?style=flat)](http://packdeps.haskellers.com/specific?package=pointless-fun)
[![TravisCI Build Status](https://img.shields.io/travis/wrengr/pointless-fun.svg?style=flat)](https://travis-ci.org/wrengr/pointless-fun) 
[![CircleCI Build Status](https://circleci.com/gh/wrengr/pointless-fun.svg?style=shield&circle-token=b57517657c556be6fd8fca92b843f9e4cffaf8d1)](https://circleci.com/gh/wrengr/pointless-fun)

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

* [Website](http://cl.indiana.edu/~wren/)
* [Blog](http://winterkoninkje.dreamwidth.org/)
* [Twitter](https://twitter.com/wrengr)
* [Hackage](http://hackage.haskell.org/package/pointless-fun)
* [Darcs](http://code.haskell.org/~wren/pointless-fun)
* [GitHub (clone)](https://github.com/wrengr/pointless-fun)
* [Haddock (Darcs version)
    ](http://code.haskell.org/~wren/pointless-fun/dist/doc/html/pointless-fun)
