# Integrate WC with Okto Wallet

To integrate WC with Okto Wallet add the following parameters to the Web3Modal.

- `themeVariables`: {  
  "--w3m-logo-image-url": "https://raw.githubusercontent.com/coindcx-okto/okto-wc/main/assets/okto-white-text-logo.svg"  
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
      "https://raw.githubusercontent.com/coindcx-okto/okto-wc/main/assets/okto-white-text-logo.svg",
  }}
  enableExplorer={false}
  explorerRecommendedWalletIds={[
    "550b59942eb58a7226381bf7935f22d311e56ee29c3530e44d96b1de0550a35a",
  ]}
/>
```
