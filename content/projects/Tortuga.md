---
title: "Tortuga"
date: 2019-03-31T17:15:01-07:00
draft: false
---

[Check out the project on GitHub](https://github.com/generatives/Tortuga)

Right now I'm working on a simple cross-platform 2D game development framework. The working name is "Tortuga".

## Goals

My goal is to build an easy to use code first framework with enough features to develop small, simple 2D games. Tortuga will provide an easy-to-use 2D rendering API, audio playback, resource management, a simple GUI system, and a few other features needed to produce a full game. My goal is to support Windows, Linux, OSX, Android, and iOS although at the moment I am only developing for Windows and Android.

I am taking a lot of inspiration from projects like [Duality](https://www.duality2d.net/), [Ultraviolet](http://www.ultraviolet.tl/), and [MonoGame](http://www.monogame.net/) although my aspirations are much smaller than any of these projects.

## Major Technologies

I am building this project in C#. I am writing as much code as possible against .NET Standard 2.0 to maximize portability while taking advantage of modern .NET tech. I am using .NET Core to run on desktop platforms and Xamarin for mobile. I am using the excellent [Veldrid](https://github.com/mellinoe/veldrid) project for super portable, high performance graphics.