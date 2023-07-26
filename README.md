# Bahá’í microsite archives

## Overview

This project contains two microsite archives for the Bahá’í Community of New Zealand.
- The World Conferences Aotearoa New Zealand 2022
- The Bicentenary of the Birth of the Báb

These microsites were originally created using [Squarespace](https://www.squarespace.com/) a website creation and hosting platform. The microsites were then archived using [HTTrack](https://www.httrack.com/) website copier.

## Project contents

- root directory
  - bicentenary-of-the-birth-of-the-bab (microsite archive)
  - package.json (npm package configuration file, installs a local web server)
  - README.md (this file)
  - the-world-conferences (microsite archive)

## How to view an archive

These archives are static websites. To view them, you need to run a local web server. This can be done using the npm package `http-server`. Or you can use any other web server of your choice.

1. Install http-server
From the project root directory.
```bash
npm install
```
2. Run http-server to serve the Bicentenary of the Birth of the Báb archive
From the project root directory
```bash
./node_modules/.bin/http-server bicentenary-of-the-birth-of-the-bab
```
3. Run http-server to serve The World Conferences Aotearoa New Zealand 2022 archive
From the project root directory
```bash
./node_modules/.bin/http-server the-world-conferences
```

After running the above commands, you should see a message like this:

```bash
Starting up http-server, serving <directoryname>
Available on:
  http://127.0.0.1:8080
  http://192.168.1.65:8080

Hit CTRL-C to stop the server
```

You can now view the archive in your web browser by visiting the URL shown in the message, e.g. `http://127.0.0.1:8080` or `http://192.168.1.65:8080`.

## Contact

Studio Marque - hello@marque.co.nz

Che Mearns - che@jiminy.co.nz