# didmail-chrome-extension
**NOTE: This extension is for demonstration purposes only**

The DIDMail Extension is a Chrome extension that allows you to send and receive emails using the DIDMail protocol.

## DIDMail Demo vido:

https://www.youtube.com/watch?v=Q22zpSlumPs

## Prerequisites

- Download the chrome extension from:
  https://github.com/shenxiuqiang/didmail-chrome-extension/releases
- unzip the file and open chrome://extensions/
- click load unpacked and select the unzipped folder
- pin the extension by clicking the pin icon on the top right corner

## get test tokens

- install didwallet extension from: https://chromewebstore.google.com/detail/did-wallet/ibjflpbmadchofnbpppegdbnifdgincp
- this page https://playground.staging.arcblock.io/ [Get Random TBA]

## Usage

- click the extension icon on the Chrome toolbar
- import the private key or mnemonic or generate a new one account
- click the [account] icon on the top right corner,and send test tokens to the account;
- select server node from the left sidebar [server]
- before compose email, select envelope from right sidebar [envelope]
- now you can compose email and send it

## Running the Server Locally

The server is a Blocklet that hosts the DIDMail protocol and can be found at:
https://test.store.blocklet.dev/blocklets/z2qa8AzjBYRmQoPw43sNDvY1XQggR4PUg8eAs

## Running the Server Locally

You can run the server locally by following these steps:

1. Install Blocklet CLI:

```bash
npm install -g @blocklet/cli
```

2. Init server config:

```bash
blocklet server init
```

3. Run the server:

```bash
blocklet server start
```

## Configuration Steps

1. Add test store on the server:
   https://test.store.blocklet.dev

2. Search for the DIDMail Blocklet on the Blocklet store and install it

3. Send test tokens (TBA) to the DIDMail wallet

4. Acquire the DIDMail node NFT from the DIDMail Blocklet

5. Stake the DIDMail node NFT on the server, then the extension will be discoverable on the server

6. Create envelope NFT factory on the server use envelope template

7. Enable and publish the envelope NFT factory

8. Now you can select the envelope NFT factory and send email using envelope NFT on the extension

## Usage Instructions

After completing the configuration steps above, you can use the DIDMail Extension to send and receive encrypted emails. For specific usage instructions, please refer to the in-extension documentation.

## Support

If you encounter any issues while using this extension, please submit an issue or contact our support team.

## Disclaimer

This extension is for demonstration purposes only and should not be used in a production environment.
