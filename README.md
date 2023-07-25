# Integrate WC with Okto Wallet

To integrate WC with Okto Wallet add the following parameters to the Web3Modal.

- `themeVariables`: {  
  "--w3m-logo-image-url": "https://raw.githubusercontent.com/coindcx-okto/wc-modal-poc/main/logos/V2/Horizontal/SVG/Okto-White%20Icon-White%20Text.svg"  
  }
- `enableExplorer`: false
- `explorerRecommendedWalletIds`: 550b59942eb58a7226381bf7935f22d311e56ee29c3530e44d96b1de0550a35a

**Example:**

```jsx
<Web3Modal
  projectId={projectId}
  ethereumClient={ethereumClient}
  themeVariables={{
    "--w3m-logo-image-url":
      "https://raw.githubusercontent.com/coindcx-okto/wc-modal-poc/main/logos/V2/Horizontal/SVG/Okto-White%20Icon-White%20Text.svg",
  }}
  enableExplorer={false}
  explorerRecommendedWalletIds={[
    "550b59942eb58a7226381bf7935f22d311e56ee29c3530e44d96b1de0550a35a",
  ]}
/>
```
