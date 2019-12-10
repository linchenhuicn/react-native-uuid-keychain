## Installation
1. With autolinking (react-native 0.60+)

    `cd ios && pod install`
    
2. Pre react-native 0.60

    `$ react-native link react-native-swisseph`

## Usage
用于获取app的唯一标示

```js
import { NativeModules } from 'react-native';
```

```jsx
NativeModules.RNGetUUID_KeyChain.getUDIDKeyChain('Bundle Identifier', (uuid) => {
  // service code
});
// log: '9DA26F9B-5111-4CC5-BEF5-607573836C45'.
```
