# React Native RNCryptor
It's an easy-to-use library for encrypting data with AES 256 in React Native. [RNCryptor](http://rncryptor.github.io/JNCryptor/javadoc/) developed popular and easy-to-use AES libs, implementations are available in
[C++](https://github.com/RNCryptor/RNCryptor-cpp),
[C#](https://github.com/RNCryptor/RNCryptor-cs),
[Java](https://github.com/RNCryptor/JNCryptor),
[PHP](https://github.com/RNCryptor/RNCryptor-php),
[Python](https://github.com/RNCryptor/RNCryptor-python),
[Javascript](https://github.com/RNCryptor/rncryptor-js),
and [Ruby](https://github.com/RNCryptor/ruby_rncryptor).

## Usage
```javascript
import RNCryptor from 'react-native-rncryptor';

RNCryptor.encrypt('a text', 'password').then((encryptedbase64)=>{
  console.log(encryptedbase64)
}).catch((error)=>{
  console.log(error)
})

RNCryptor.encryptFromBase64('a base64 string', 'password').then((encryptedbase64)=>{
  console.log(encryptedbase64)
}).catch((error)=>{
  console.log(error)
})

RNCryptor.decrypt('encrypted base64', 'password').then((plaintext)=>{
  console.log(plaintext)
}).catch((error)=>{
  console.log(error)
})

RNCryptor.decryptToBase64('encrypted base64', 'password').then((plaintextBase64)=>{
  console.log(plaintextBase64)
}).catch((error)=>{
  console.log(error)
})
```

## License
MIT