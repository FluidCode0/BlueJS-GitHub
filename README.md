# BlueJS - JavaScript for Bluetooth

Welcome to blueJS, a JavaScript subset designed for Bluetooth-related operations.


## Starting with VSCode and Replit.

1. **Installing apps and files:**
   - Install VSCode from Microsoft Store or Google, install the JavaScript Components in the latest version from Microsoft Store.
   - For Replit, find in search bar "BlueJS", look through repls and find a repl named BlueJS and fork it.
2. **Editing:**
   - Edit in VSCode and create a file named "blue.js".
   - For Replit, find a file named "blue.js".


3. **File Naming Convention:**
   - Prefer using the `.js` extension for your blueJS scripts, e.g., `blue.js`for VSCode.
   - For Replit, it has it automatically.

4. **Usage:**
   - Write your blueJS code as you would in standard JavaScript, with a focus on Bluetooth operations.

```javascript
// blueJS script
const device = new BluetoothDevice('DeviceName');

function onConnectionStateChanged(state) {
  if (state === 'connected') {
    console.log('Bluetooth device connected!');
  } else if (state === 'disconnected') {
    console.log('Bluetooth device disconnected.');
  }
}

device.onConnectionStateChanged = onConnectionStateChanged;

// Bluetooth operations
device.connect();
// ... rest of your code
```

