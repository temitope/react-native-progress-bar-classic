react-native-progress-bar-classic
===

> Simple animated progress bar for React Native

[![npm](https://img.shields.io/npm/v/react-native-progress-bar-classic.svg)]()[![npm](https://img.shields.io/npm/l/react-native-progress-bar-classic.svg)]()

[![NPM](https://nodei.co/npm/react-native-progress-bar-classic.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/react-native-progress-bar-classic/)

Demo
---
![Demo](./doc/demo.gif)


Installation
==

in Cli
---
```
npm i react-native-progress-bar-classic
```

in JavaScirpt
---
```
import ProgressBarClassic from 'react-native-progress-bar-classic';
```


Usage
===

Simple
---
```
<ProgressBarClassic progress={20} />
```

Customized
---
```
<ProgressBarClassic
  progress={20}
  valueStyle={'balloon'}
/>
```


Props
===

progress(Int) `Default: 0`
---
The Progress. `progress` can take 0 to 100.

valueStyle(String) `Default: 'default'`
---
`valueStyle` detect style of progress percentage

### `'default'`

![Demo](./doc/default.jpg)


### `'balloon'`

![Demo](./doc/balloon.jpg)

### `'none'`

![Demo](./doc/none.jpg)


TODO
==
- [ ] can change style (color, height, etc..)


Contributing
==
Of course! Welcome :)


License
==
MIT

