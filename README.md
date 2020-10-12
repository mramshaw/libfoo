# Running Go Code on iOS and Android

A simple Go package that can be run from iOS (Swift) and also Android (Kotlin)

## Motivation

I read the original article and this sounded like a fun project to have a look at.

Go has particularly good support for __Runes__ which is the use case here.

## Notes

* does NOT use the [Go Mobile framework](https://github.com/golang/mobile)

* uses Cgo to build the raw static (iOS) and shared (Android) C library
  that can be imported into a mobile project (which is what the Go Mobile
  framework does under-the-hood).

## To Do

- [ ] Verify the author's assertion about how the Go Mobile framework works

## Credits

This is a fork of the code for the following article:

    http://rogchap.com/2020/09/14/running-go-code-on-ios-and-android/
