# Mobile Leads web App

A simple mobile web app to save and organize leads (URLs). This is a personal training project, based on a Scrimba course. I started from Scrimba's starter code, then wrote the code myself. I built it to practice vanilla JavaScript and Firebase.

**Live demo:** [leads-tracker-ahb.netlify.app](https://leads-tracker-ahb.netlify.app/)

> **Note:** the backend is currently disconnected. You can still see the interface, but saving and loading leads are disabled.

## About

The first version of this project was a Chrome extension. It stored the leads in `localStorage`. This worked, but the data stayed on one browser. I could not sync it between devices.

So I rebuilt the project as a mobile web app with a cloud database. The current version is the result of that rewrite.

With this project, I practiced:

- DOM manipulation and user input with vanilla JavaScript
- Saving data to a cloud database (Firebase Realtime Database)
- Making a web app installable on mobile (PWA: manifest, app icons)
- Deploying a static frontend on Netlify

## Project status & Security Decision

Following recent changes to Firebase's pricing models, and to prevent unauthorized access or abuse, I revoked the database credentials and disconnected the backend. The frontend remains online to showcase the interface, but data persistence is disabled.

**This allowed me to practice cloud resource management and safe decommissioning of services.** The frontend remains online to showcase the UI and the PWA implementation.

## What I learned

- Building a small app around real user input and persistent storage
- Comparing storage options (`localStorage` vs. cloud database)
- Reading and writing to the Firebase Realtime Database from the client
- Making a web app installable on mobile (Web manifest, app icons)
- Making a security decision about exposing a cloud service
- Deploying and managing a project on Netlify

---

_This is a learning project, shared as part of my portfolio. The code is simple on purpose and is not maintained._
