# TokenMe-Platform-Overview

## Introduction

This is the `README.md` file from the public Github repository [TokenMe-Platform-Overview](https://github.com/Sostark/TokenMe-Platform-Overview/).

The purpose of this overview is to describe the TokenMe Data/Processing Platform, and its technologies, for (future) colleagues, business partners and (prospect) customers.

This file is automatically published on Github Pages: [https://sostark.github.io/TokenMe-Platform-Overview/](https://sostark.github.io/TokenMe-Platform-Overview/)

## TokenMe Data

The basis of the TokenMe solution is to collect and process `TTL` or "Token Time Location" records. 

- `Anchors` are compact devices (roughly 16x8x6 cm) that are mounted on a walls or such all over a building or site, and that "listen" for the presence of Tokens, and reporting any data to a central server
- `Tokens` are lightweight, wearable devices (roughly 5cm diameter, 1cm thick) that continuously send their presence/location with sensor-data to Anchors, using radio-technology
- `TCS` or "TokenMe Cloud Server" collects all this data, stores it for long-term usage, analysis, monitoring and reports.

## Technologies used by TokenMe Cloud Server

The current version of the TCS-server uses the following technologies and platforms:

- `Backend` (data collection and processing): [Node.js](https://nodejs.org/en/about) with coding in the [JavaScript](https://en.wikipedia.org/wiki/JavaScript) language
- `Frontend` (Web User-Interfaces): [React.js](https://react.dev/) for cloud-servers, [Vue.js](https://vuejs.org/) for embedded-servers (e.g. Raspberry Pi), both uses coding in JavaScript
- `Database`: [PostgreSQL](https://www.postgresql.org/) for big-data, [PouchDB](https://pouchdb.com/) for small/fast-data (which is a portable clone of [CouchDB](https://couchdb.apache.org/) better suited for embedded use)
