## 
Install amplify CLI
```
  sudo npm i -g @aws-amplify/cli

  amplify
```

configure
```
  amplify configure
```
Create IAM user, get access Key / secretAccessKey


init
```
  cd kineteco

  amplify init            # connect project to amplify, create AWS resources
```

## Integrate Ampliyfy into React app
```
  npm i install asw-amplify  @aws-amplify/ui-react
```

in index.js
```
  import Amplify from 'asw-amplify'
  import aswconfig from './aws-exports'

  Amplify.configure(aswconfig)

```
