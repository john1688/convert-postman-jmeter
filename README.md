# convert-postman-jmeter

[![CircleCI](https://circleci.com/gh/sercheo87/convert-postman-jmeter/tree/master.svg?style=svg)](https://circleci.com/gh/sercheo87/convert-postman-jmeter/tree/master)
![GitHub issues](https://img.shields.io/github/issues/sercheo87/convert-postman-jmeter.svg)
![npm](https://img.shields.io/npm/v/3.svg)
![NPM](https://img.shields.io/npm/l/1.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/sercheo87/convert-postman-jmeter.svg)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/sercheo87/convert-postman-jmeter.svg)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=convert-postman-jmeter&metric=alert_status)](https://sonarcloud.io/dashboard?id=convert-postman-jmeter)

This tool convert projects [Postman](https://www.getpostman.com) to [JMeter](https://jmeter.apache.org)

- [NPM Site](https://www.npmjs.com/package/convert-postman-jmeter)
- [Wiki](https://sercheo87.github.io/convert-postman-jmeter/)

## Installation

```bash
npm i convert-postman-jmeter -g
```

## Usage

```bash
$ convert-postman-jmeter
Usage: convert-postman-jmeter -p [file] -j [file]

Options:
  --help          Show help                                            [boolean]
  --version       Show version number                                  [boolean]
  -p, --postman   Load project postman                                [required]
  -j, --jmeter    Output project JMeter
  -o, --override  Override project JMeter                       [default: false]

Copyright 2019
```

### Options

    -p,--postman        File name of project Postman exported.

    -f,--jmeter         File name to output generated project JMeter.

    -o,--override       Override project JMeter generate if exists.

## Example Use

Open Postman:

![Postman App](screenshot/postman.png)

Export project:

![Postman App](screenshot/postman-export.png)

Save file:

![Postman App](screenshot/postman-location.png)

Convert project exported:

```bash
convert-postman-jmeter -p test-api-without-environments.postman_collection.json
```

![Postman App](screenshot/export.png)

Open project generate with JMeter App:

![Postman App](screenshot/jmeter.png)

## Known Issues

For issues create o find in [issues page](https://github.com/sercheo87/convert-postman-jmeter/issues).
