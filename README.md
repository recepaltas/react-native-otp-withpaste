<p align="center">
  <a href="https://github.com/kedar09/react-native-otp-withpaste" target="blank">
    React Native OTP With Paste
  </a>
</p>
# react-native-otp-withpaste

## Get Started 

### Installation 
```js
npm install react-native-otp-withpaste
```

### Usage
```js
import React from 'react';
import OTPInput from 'react-native-otp-withpaste';

const App = () => {
  return (
    <>
      <OTPInput
        title="Enter OTP"
        type="outline"
        onChange={code => {
          console.log(code);
        }}
        onPasted={state.pasted}
      />
    </>
  );
};

export default App;
```

### Usage
<table>
  <tr>
    <td>
      <p align="center">
        <strong>Outline Example</strong>
      </p>
    </td>
    <td>
      <p align="center">
        <strong>Filled Example</strong>
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p align="center">
        <img src="https://github.com/kedar09/kedar09/blob/dev/assets/Screenshot_otp_outline.png" width="220" height="420"/>
      </p>
    </td>
    <td>
      <p align="center">
        <img src="https://github.com/kedar09/kedar09/blob/dev/assets/Screenshot_otp_filled.png" width="220" height="420"/>
      </p>
     </td>
    </tr>
</table>

### Available props

| Name                      | Type                 | Default         |
|---------------------------|----------------------| ----------------|
| `type            `        | filled or outline    | outline         |
| `defaultValue    `        | string               | ""              |
| `keyboardType    `        | string               | number-pad      |
| `cursorColor          `   | string               | #4C5457         |
| `borderColor`             | string               | #8FA2A3         |
| `currentBorderColor`      | string               | #3E517A         |
| `numberOfInputs     `     | number               | 4               |
| `imageUrl`                | string               | null            |
| `imageStyle     `         | style                | Image style     |
| `title`                   | string               | null            |
| `titleStyle     `         | style                | Text style      |
| `subtitle`                | string               | null            |
| `subtitleStyle     `      | style                | Text style      |
| `inputStyle     `         | style                | TextInput style |
| `onFilledCode     `       | boolean              | false           |
| `onChange     `           | function             | {}              |
| `secureTextEntry     `    | boolean              | false           |
| `onPasted     `           | string               | null           |


### Author
Feel free to ask me questions (mesut.altas2019@gmail.com) ~ mesutche

