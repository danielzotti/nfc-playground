# NFC Playground
A project to play with NFC in JavaScript

## Features
- Read NFC tag content
- Write records on a NFC tag
  - Can be a text or a list of records (one record per row in a textarea)

## Test it on your local machine

### Prerequisites:
- `npm install`

### Test NFC feature on your smartphone:
- `npm run dev` on your local machine:
- Connect your smartphone to your local machine through USB
  - (you might need to activate `USB debugging` feature) 
  - grant permissions on the smartphone
- Open chrome debug `chrome://inspect/#devices` on your local machine
- Click on `Port forwarding...` button and add a new record:
  - Port: `8080`
  - IP address and port: `localhost:8080`
  - Check `Enable port forwarding` and click `Done`
- Browse `https://localhost:8080` on your smartphone
- Select `inspect` under the `https://localhost:8080` item in the list
