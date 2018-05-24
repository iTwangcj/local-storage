# @fem/local-storage

📦 File system storage plugin for fem 


[![CircleCI](https://circleci.com/gh/fem/local-storage/tree/master.svg?style=svg)](https://circleci.com/gh/fem/local-storage/tree/master)
[![Backers on Open Collective](https://opencollective.com/fem/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/fem/sponsors/badge.svg)](#sponsors)
[![Gitter chat](https://badges.gitter.im/fem/questions.png)](https://gitter.im/fem/)
[![dependencies Status](https://david-dm.org/fem/local-storage/status.svg)](https://david-dm.org/fem/local-storage)
[![Known Vulnerabilities](https://snyk.io/test/github/fem/local-storage/badge.svg?targetFile=package.json)](https://snyk.io/test/github/fem/local-storage?targetFile=package.json)
[![codecov](https://codecov.io/gh/fem/local-storage/branch/master/graph/badge.svg)](https://codecov.io/gh/fem/local-storage)

> This package is already built-in in fem

```
npm install @fem/local-storage
```

### API

### LocalDatabase

The main object that handle a JSON database the private packages.

#### Constructor

```
new LocalDatabase(config, logger);
```

* **config**: A fem configuration instance.
* **logger**: A logger instance

### LocalFS

A class that handle an package instance in the File System

```
new LocalFS(packageStoragePath, logger);
```



## License
fem is [MIT licensed](https://github.com/fem/local-storage/blob/master/LICENSE).
