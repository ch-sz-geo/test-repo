ifndef::env-github[:toc: left]
:toc-title: Inhalt
:toclevels: 5
:figure-caption: Figur
:example-caption!:
:table-caption: Tabelle
:note-caption: Hinweis
// zum Generieren eines PDF aus VS Code (HTML muss mit eingebetteten Bildern generiert werden, damit daraus ein korrektes PDF erstellt werden kann)
:data-uri:
:source-highlighter: highlight.js
:sectnums:
:sectnumlevels: 5
:sectlinks:
:sectanchors:
:includedir: docs

= Dokumentation
Amanda Wetter <amanda.wetter@sz.ch>
// Versionierung
:revdate: {docdate}
:revnumber: 0.1.3
// Pdf output
:title-page:
:chapter-label: // deprecated

// Die Verwiese auf die Inhalte der Dokumentation sollen im README auf Github nicht angezeigt werden.
ifndef::env-github[]
include::{includedir}/testdoc.adoc[]
include::{includedir}/testdoc2.adoc[]
include::{includedir}/testdoc3.adoc[]
endif::[]

// Erklärung und Link auf Website
ifdef::env-github[]
In diesem Repository ist der Versuch gestartet worden, eine Page aus den Files zu generieren.

Die aktuelle Website ist unter https://ch-sz-geo.github.io/test-repo/ erreichbar.
endif::[]
