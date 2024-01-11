# TokenMe-Platform-Overview

## Introduction

This is the `README.md` file from the public Github repository "TokenMe-Platform-Overview".

The purpose of this overview is to describe the TokenMe Data/Processing Platform, and its technologies, for (future) colleagues, business partners and (prospect) customers.

This file is automatically published on Github Pages: [](https://sostark.github.io/TokenMe-Platform-Overview/)

## TokenMe Data

The basis of the TokenMe solution is to collect and process `TTL` or "Token Time Location" records. 

- `Anchors` are compact devices (16x8x6 cm) that are mounted on a walls or such all over a building or site, and that "listen" for the presence of Tokens, and reporting any data to a central server
- `Tokens` are lightweight, wearable devices (5cm diameter, 1cm thick) that continuously send their presence/location with sensor-data to Anchors, using radio-technology
- `TCS` or "TokenMe Cloud Server" collects all this data, stores it for long-term usage, analysis, monitoring and reports.

## TokenMe Technologies

The current version of the TCS-server uses the following technologies and platforms:

- Backend (data collection and processing): [Node.js](https://nodejs.org/en/about) with coding in [JavaScript](https://en.wikipedia.org/wiki/JavaScript) language
- Frontend (Web User-Interfaces): [React.js]() for cloud-servers, [Vue.js]() for embedded-servers (e.g. Raspberry Pi), both with condig in JavaScript
- Database: [PostgreSQL]() for big-data, [PouchDB]() for small/fast-data
