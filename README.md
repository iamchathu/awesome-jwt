# Awesome JWT (JSON Web Tokens) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="http://jwt.io/img/logo-asset.svg" align="right" width="100">](https://jwt.io)

> A collection of awesome things regarding JSON Web Tokens.

*Please read the [contribution guidelines](contributing.md) before contributing.*

## JSON Web Tokens
[JSON Web Tokens](https://en.wikipedia.org/wiki/JSON_Web_Token) are an open, industry standard [RFC 7519](https://tools.ietf.org/html/rfc7519) method for representing claims securely between two parties.

## Contents

- [JSON Web Tokens](#json-web-tokens)
- [Libraries](#libraries)
    - [C](#c)
    - [Clojure](#clojure)
    - [Delphi](#delphi)
    - [Elixir](#elixir)
    - [Go](#go)
    - [Java](#java)
    - [JavaScript](#javascript)
    - [Lua](#lua)
    - [.Net](#net)
    - [Node.js](#nodejs)
    - [Objective-C](#objective-c)
    - [Perl](#perl)
    - [PHP](#php)
    - [Python](#python)
    - [Ruby](#ruby)
    - [Rust](#rust)
    - [Scala](#scala)
    - [Swift](#swift)
- [Tools](#tools)
- [Tutorials](#tutorials)
- [Articles](#articles)
- [Videos](#videos)
- [Presentations](#presentations)
- [Podcasts](#podcasts)
- [Books](#books)
- [Blogs](#blogs)
- [Courses](#courses)

---

## Libraries

### C
- [libjwt](https://github.com/benmcollins/libjwt) - C Library.

### Clojure
- [buddy](https://github.com/funcool/buddy/) - Security library for Clojure.

### Delphi
- [delphi-jose-jwt](https://github.com/paolo-rossi/delphi-jose-jwt) - Delphi implementation of JOSE and JWT.

### Elixir
- [json_web_token_ex](https://github.com/garyf/json_web_token_ex) - Elixir implementation of the JSON Web Token (JWT) standard RFC 7519.
- [joken](https://github.com/bryanjos/joken) - This library provides a convenient way to create, sign, verify, and validate JWTs while allowing the flexibility to customize each step along the way.
- [jwtex](https://github.com/mschae/jwtex) - Library to encode and decode JWT tokens.
- [plug_jwt](https://github.com/bryanjos/plug_jwt) - Plug for JWT authentication.
- [guardian](https://github.com/ueberauth/guardian) - Elixir Authentication.

### Go
- [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT).
- [jose2go](https://github.com/dvsekhvalnov/jose2go) - Golang (GO) implementation of Javascript Object Signing and Encryption specification.
- [jose](https://github.com/SermoDigital/jose) - Comprehensive set of JWT, JWS, and JWE libraries.
- [jwt](https://github.com/robbert229/jwt) - This is an implementation of JWT in golang.
- [go-jose](https://github.com/square/go-jose) - Implementation of JOSE standards (JWE, JWS, JWT) in Go.

### Java
- [java-jwt](https://github.com/auth0/java-jwt) - Java implementation of JSON Web Token (JWT).
- [jose4j](https://bitbucket.org/b_c/jose4j/wiki/Home) - Implementation of JWT and the JOSE specification suite.
- [Nimbus-JOSE-JWT](https://bitbucket.org/connect2id/nimbus-jose-jwt/wiki/Home) - Java library that implements the Javascript Object Signing and Encryption (JOSE) spec suite and the closely related JSON Web Token (JWT) spec.
- [jJWT](https://github.com/jwtk/jjwt) - Java JWT: JSON Web Token for Java and Android.

### JavaScript
- [jsrsasign](https://github.com/kjur/jsrsasign) - The 'jsrsasign' (RSA-Sign JavaScript Library) is an opensource free cryptography library supporting RSA/RSAPSS/ECDSA/DSA signing/validation, ASN.1, PKCS#1/5/8 private/public key, X.509 certificate, CRL, OCSP, CMS SignedData, TimeStamp, CAdES JSON Web Signature/Token in pure JavaScript.
- [angular2-jwt](https://github.com/auth0/angular2-jwt) - Helper library for handling JWTs in Angular 2 apps.
- [jwt-decode](https://github.com/auth0/jwt-decode) - Decode JWT tokens, useful for browser applications.

### Lua
- [lua-reasty-jwt](https://github.com/SkyLothar/lua-resty-jwt) - The Great Openresty's JWT.

### .Net
- [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - Ultimate Javascript Object Signing and Encryption (JOSE) and JSON Web Token (JWT) Implementation for .NET and .NET Core.
- [jose-rt](https://github.com/dvsekhvalnov/jose-rt) - WinRT (Windows 8.1 and Windows Phone 8.1) implementation of Javascript Object Signing and Encryption (JOSE) and JSON Web Token (JWT).
- [azure-activedirectory-identitymodel-extensions-for-dotnet](https://github.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet) - IdentityModel extensions for .Net.
- [Jwt.Net](https://github.com/jwt-dotnet/jwt) - Implementation for .NET.

### Node.js
- [Node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - Implementation for Node.js.
- [nJWT](https://github.com/jwtk/njwt) - Node.js JWT support.
- [express-jwt](https://github.com/auth0/express-jwt) - Connect/express middleware that validates a JsonWebToken (JWT) and set the req.user with the attributes.
- [express-jwt-authz](https://github.com/auth0/express-jwt-authz) - Validate the JWT scope to authorize access to an endpoint.
- [express-jwt-permissions](https://github.com/MichielDeMey/express-jwt-permissions) - Express middleware for JWT permissions.
- [socketio-jwt](https://github.com/auth0/socketio-jwt) - Authenticate socket.io incoming connections with JWTs.

### Objective-C
- [JWT](https://github.com/yourkarma/JWT) - JSON Web Token implementation in Objective-C.

### Perl
- [perl-Crypt-JWT](https://github.com/DCIT/perl-Crypt-JWT) -  Implements JSON Web Token (JWT, JWS, JWE).

### PHP
- [php-jwt](https://github.com/firebase/php-jwt) - Simple library to encode and decode JSON Web Tokens (JWT) in PHP.

### Python
- [pyjwt](https://github.com/jpadilla/pyjwt/) - Implementation in Python.
- [python-jose](https://github.com/mpdavis/python-jose/) - JOSE implementation in Python.

### Ruby
- [ruby-jwt](https://github.com/jwt/ruby-jwt) - Pure ruby implementation of the RFC 7519 OAuth JSON Web Token (JWT) standard.
- [json-jwt](https://github.com/nov/json-jwt) - JSON Web Signature, JSON Web Encryption and JSON Web Key and JWT in Ruby.
- [json_web_token](https://github.com/garyf/json_web_token) - Ruby implementation of the JSON Web Token (JWT) standard, RFC 7519.

### Rust
- [frank_jwt](https://github.com/GildedHonour/frank_jwt) - Implementation in Rust.

### Scala
- [authentikat-jwt](https://github.com/jasongoodwin/authentikat-jwt) - JWT Scala Implementation, Claims based auth for Scala.
- [jwt-scala](https://github.com/pauldijou/jwt-scala) - Support for Scala.
- [jwt](https://github.com/iain-logan/jwt) - Scala implementation of the JWT specification.

### Swift
- [JSONWebToken](https://github.com/kylef/JSONWebToken.swift) - Swift implementation of JSON Web Token (JWT).
- [jwt](https://github.com/vapor/jwt) - Implementation in Swift.

## Tools
- [JWT.io](https://jwt.io) - Decode, verify and generate JWT online.
- [JWT Debugger](https://chrome.google.com/webstore/detail/jwt-debugger/ppmmlchacdbknfphdeafcbmklcghghmd) - Chrome Extenstion for debugging JWT.
- [JSONWebToken.io](https://www.jsonwebtoken.io/) - Encode or Decode JWTs online.
- [JWT Inspector](https://www.jwtinspector.io/) - Chrome Extension to inspect JWT.

## Tutorials

## Articles
- [JWT Introduction](https://chathu.me/2017/08/28/jwt-introduction/) - Introduction to JSON Web Tokens.
- [The Anatomy of a JSON Web Token](https://scotch.io/tutorials/the-anatomy-of-a-json-web-token) - Getting to know JSON Web Tokens.

## Videos
- [JSON Web Token (JWT) Introduction by EggHead.io](https://egghead.io/lessons/angularjs-json-web-token-jwt-introduction) - Basic introduction to the mechanics of JWTs and the application we will be building in an AngularJS lesson series.

## Presentations
- [JSON Web Tokens](https://speakerdeck.com/thameera/json-web-tokens) - Presentation done at Colombo JS Meetup by Thameera Senanayaka.

## Podcasts

## Books
- [JWT Handbook](https://auth0.com/e-books/jwt-handbook) - Learn everything you wanted to know about JSON Web Tokens.

## Blogs
- [JWT Token NodeJS](https://medium.com/@prasanna18101994/jwt-json-web-token-nodejs-9ca2531bcf74?sk=d9997a14cbe93c899da6f168bb624d0f) - JWT (JSON Web Token) — NODEJS

## Courses
- [Creating Apps With AngularJS, Node, and Token Authentication by Pluralsight](https://www.pluralsight.com/courses/creating-apps-angular-node-token-authentication) - Learn about Authentication, Authorization, and OAuth2 with Node Express and Angular.
- [AngularJS Authentication with JWT by EggHead.io](https://egghead.io/courses/angularjs-authentication-with-jwt) - In this series, Kent will be building a simple application to get random user information from a node server with an Angular client.


 
--- 
**License**

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chathu Vishwajith](https://chathu.me) has waived all copyright and related or neighboring rights to this work.
