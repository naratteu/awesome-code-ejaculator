# 놀라운-코드싸개의-세계

일관성을 위해 파생된, 덜 작성하기위해 작성된 모든 성과들을 살펴봅니다.

## Todo

html css wasm llvm asm
검수 및 PR환영

## Mermaid

```mermaid
---
title: 놀라운-코드싸개의-세계
---
stateDiagram
  direction LR

  gleam --> js
  gleam --> beam
  elixir --> beam
  erlang --> beam
  c# --> js:h5
  ts --> js
  go --> c#:go2cs
  go --> haxe:go2hx
  go --> js:gopherjs
  java --> kotlin
  kotlin --> java
  f# --> js:fable

  haxe --> go:reflaxe_go
  haxe --> js
  haxe --> flash
  haxe --> php
  haxe --> cpp
  haxe --> java
  haxe --> jvm
  haxe --> c#
  haxe --> python
  haxe --> lua

  classDef bytecode fill:#8800D6;
  class jvm,il,beam bytecode

  java --> jvm
  scala --> jvm
  groovy --> jvm

  c# --> il
  f# --> il
  vb.net --> il
  pwsh --> il

  classDef dataformat fill:#FFD600;
  class protobuf,kaitai,bebop,messagepack dataformat

  protobuf --> cpp
  protobuf --> java
  protobuf --> python
  protobuf --> objectivec
  protobuf --> c#
  protobuf --> ruby
  protobuf --> go
  protobuf --> php
  protobuf --> dart
  protobuf --> js

  kaitai --> cpp
  kaitai --> go
  kaitai --> c#
  kaitai --> java
  kaitai --> js
  kaitai --> lua
  kaitai --> nim
  kaitai --> perl
  kaitai --> php
  kaitai --> python
  kaitai --> ruby
  kaitai --> rust
  kaitai --> swift

  bebop --> c#
  bebop --> ts
  bebop --> js
  bebop --> rust
  bebop --> dart
  bebop --> python
  bebop --> cpp
  bebop --> go

  messagepack --> flash
  messagepack --> c
  messagepack --> swift
  messagepack --> objectivec
  messagepack --> c#
  messagepack --> cpp
  messagepack --> dart
  messagepack --> elixir
  messagepack --> erlang
  messagepack --> f#
  messagepack --> go
  messagepack --> haskell
  messagepack --> haxe
  messagepack --> java
  messagepack --> js
  messagepack --> kotlin
  messagepack --> lua
  messagepack --> matlab
  messagepack --> nim
  messagepack --> ocaml
  messagepack --> php
  messagepack --> pascal
  messagepack --> perl
  messagepack --> pony
  messagepack --> python
  messagepack --> ruby
  messagepack --> rust
  messagepack --> scala
  messagepack --> smalltalk
  messagepack --> kotlin
```
