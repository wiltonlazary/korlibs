# Kotlin cORoutines LIBraries

**NOTE:** To avoid naming mistakes with Kotlin's **ktor** web backend framework [https://github.com/kotlin/ktor](https://github.com/kotlin/ktor),
you can call the set of these libraries Soywiz's **KORLIBS** (I named this repo according).
Individually there should be no possible naming mistakes.

These libraries work for desktop JVM, Android and JTransc Node.JS + Browser.
More targets to come including Kotlin.js, iOS...

[![](https://raw.githubusercontent.com/soywiz/kor/master/patreon/patreon.png)](https://www.patreon.com/soywiz)

If you are interested in these projects, please support my work at patreon so I can continue working on them!

[https://www.patreon.com/soywiz](https://www.patreon.com/soywiz)

## [JTransc](http://github.com/jtransc/jtransc)

[![](/logos/128/jtransc.png)](http://github.com/jtransc/jtransc)

Convert your kotlin code to several platforms and languages.
KORLIBS are designed to work with jtransc.

**Note:** Soywiz's KORLIBS will also work with direct Kotlin targets including Kotlin-JS, and Kotlin-Native if it ends being available.

## [korio - I/O](http://github.com/soywiz/korio)

[![](/logos/128/korio.png)](http://github.com/soywiz/korio)

Event Loop + Asynchronous I/O + Network + WebSockets + VFS + Utilities + Serialization + vertx integration.
This is the core library all other Soywiz's KORLIBS libraries use.

Intended for **backend** and **frontend**.

## [korte - Template Engine](http://github.com/soywiz/korte)

[![](/logos/128/korte.png)](http://github.com/soywiz/korte)

Template engine compatible with twig and jekyll/liquid supporting coroutines and suspensions. Supports vertx.
This allows to suspend template rendering and obtain data from asynchronous sources lazily for minimum memory
requirements while keeping a high throughput and productivity writing code without callbacks.

Intended for **backend** usable on **backend** and **frontend**.

## [korim - IMaging](http://github.com/soywiz/korim)

[![](/logos/128/korim.png)](http://github.com/soywiz/korim)

Bitmap + Vector + Fonts + Image decoding and rasterizing portable API that use native vector rendering.

Intended for **backend** + **frontend**.

## [korau - AUdio](http://github.com/soywiz/korau)

[![](/logos/128/korau.png)](http://github.com/soywiz/korau)

Portable audio and sound formats.

Intended for **backend** + **frontend**.

## [korag - Accelerated Graphics](http://github.com/soywiz/korag)

[![](/logos/128/korag.png)](http://github.com/soywiz/korag)

Fast and testeable GPU graphics and portable shaders for all frontend modern targets.
Compatible with GL|ES, WebGL. Future-proof: Designed to work with any modern architecture in the future like DirectX, Vulkan, Metal or whatever
without changing any code at all.

Intended for **frontend**.

## [korui - User Interfaces](http://github.com/soywiz/korui)

[![](/logos/128/korui.png)](http://github.com/soywiz/korui)

Portable native UI on all targets. Use the same code to generate an AWT app, a HTML5 website or a Android application. 

Intended for **frontend**.

## [korge - Game Engine](http://github.com/soywiz/korge)

[![](/logos/128/korge.png)](http://github.com/soywiz/korge)

Portable game Engine using korau, korag and korui.

Intended for **frontend**.

