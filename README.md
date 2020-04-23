Forked from [react-native-rncryptor-aes-256](https://github.com/richfisher/react-native-rncryptor-aes-256)

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
import RNCryptor from 'rn-rncryptor';

RNCryptor.encrypt('a text', 'password')

RNCryptor.encryptFromBase64('a base64 string', 'password')

RNCryptor.decrypt('encrypted base64', 'password')

RNCryptor.decryptToBase64('encrypted base64', 'password')

RNCryptor.encryptFile('pathname','pwd')

RNCryptor.readEncryptedFile('filepath', 'pwd')

RNCryptor.decryptFileAndSave('filepath', 'pwd', 'extension')

RNCryptor.decryptFileAndSaveReturningContent('filepath', 'pwd', 'extension')
```