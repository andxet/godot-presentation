---
theme: default
author: Andrea Peretti
addons:
  - "@katzumi/slidev-addon-qrcode"
highlighter: shiki
info: |
  ## Introduzione a godot

  Presentazione realizzata per il Python Biella Group
  Evento del 1 Marzo 2024
transition: slide-left
title: Introduzione a Godot
mdc: true
---

# Introduzione a Godot

<QRCode
  value="https://github.com/k2tzumi/slidev-addon-qrcode"
  width="180"
  height="180"
  color="4329B9"
  image="/images/godot-splash.jpg"
/>

---
layout: image
image: /images/godot-splash.jpg
---

---
layout: center
class: text-center
--- 

# Speaker

![avatar](https://gravatar.com/avatar/949d43f2535cfbedf72b98d8650073b87ae61df611bb513d8491cee590830dcb?&s=250) { style="border-radius: 50%; display: inline;" }

## Andrea Peretti

Gameplay Programmer @ Ubisoft Milan

[www.andxet.dev](https://www.andxet.dev)

<QRCode
  value="https://www.andxet.dev"
  width="180"
  height="180"
/>

---
layout: center
class: text-center
---

# Godot Game Engine

![godot logo](/images/godot-logo.png){ width=200px; style="display: inline;" }

[https://godotengine.org/](https://godotengine.org/)


---

# Game Engines

Un game engine è un framework creato principalmente per lo sviluppo di videogames, e solitamente include librerie e programmi di supporto come un editor di livelli.---

---

# Game Engines

I game engines più famosi mettono a disposizione dello sviluppatore:

- Rendering Engine (2D e/o 3D)
- Physics engine e collision detection
- Sounds
- Animations
- Scripting
- networking
- Asset management
- ...

---

# Storia di Godot

Lo sviluppo è iniziato nel 2001 in **Codenix**, azienda di consulenza di game development in Argentina, con il nome di **Larvotor**.

Nel corso dei successivi 10 anni l'engine ha cambiato nome più volte, fino a chiamarsi, appunto, **Godot**. 

Il nome si ispira all'opera teatrale **Waiting for Godot** di *Samuel Beckett*, poiché rappresenta il desiderio incessante di aggiungere nuove funzionalità all'engine, che lo avvicinerebbero a un prodotto esaustivo, ma non lo farà mai.

---

# Storia di Godot

Il rilascio dell'engine in versione open source avvenne nel 2014 sotto licena MIT.

Ricevette finanziamenti da Mozilla e Microsoft, venne effettuato un refactoring del codice e venne aggiunto C# ai linguaggi supportati.

Gli sviluppatori, **Linietsky** e **Verschelde** iniziarono a lavorare full time all'implementazione. Venne rilasciata la versione 3.0

---

# Storia di Godot

Nel 2019 si iniziò a lavorare alla versione 4.0, che richiese un ulteriore refactoring. Venne rilasciata nel 2023 migliorando molto l'engine.

Nel settembre 2023, complice una generale insoddisfazione per alcune modifiche ai costi di licenza di **Unity Engine**, Godot ricevette una grande attenzione dagli sviluppatori ed una donazione di 100.000$ da Re-Logic.

---

# Caratteristiche

- Utilizza un albero di nodi per definire scene
- Parti di questo albero possono essere salvati a loro volta come scene ed essere riutilizzate
- Ogni nodo può avere uno script (gdscript, C#)
- I nodi possono emettere segnali, che possono essere collegati a callback (osservator pattern)

---

# La documentazione

[https://docs.godotengine.org/en/stable/](https://docs.godotengine.org/en/stable/)

Ottima per imparare non solo come funziona l'engine, ma il gamedev in generale!

---

# Nodi

---

# gdscript

- **Non è Python!** Ma utilizza una sintassi ad indentazione simile a python
- Non usa un **garbage collector** ma un sistema di **reference counting**

---

# Perchè gdscript?

---

# Domande?

---

# Grazie!

[www.andxet.dev](https://www.andxet.dev)

[https://godotengine.org/](https://godotengine.org/)

Realizzato con [Slidev](https://sli.dev/)

---

src: ./pages/example-slides.md

---