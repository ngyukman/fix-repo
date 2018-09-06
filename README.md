# fix-repo

[![Build Status](https://travis-ci.org/ngyukman/fix-repo.svg?branch=master)](https://travis-ci.org/Ullink/fix-repo) [![codecov](https://codecov.io/gh/ngyukman/fix-repo/branch/master/graph/badge.svg)](https://codecov.io/gh/Ullink/fix-repo)

npm package for easy accessible FIX Repository information, without parsing the xml repository

## Installation

To install the package, simply run the following

```npm install fix-repo```

## Usage

To get a Fix50 field's type information:
```javascript
import { Fix50 } from 'fix-repo';

const msgTypeField = Fix50.getField('35');
const msgTypeCodeSet = msgTypeField.type;
```

## To Build

Run the following command
```
npm install -g gulp-cli
npm install

gulp
```

## License

Apache-2.0