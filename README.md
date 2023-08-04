# Integrate WC with Okto Wallet

## Using Web3Modal

To integrate WC with Okto Wallet add the following parameters to the Web3Modal.

- `themeVariables`: {  
  "--w3m-logo-image-url": "https://raw.githubusercontent.com/coindcx-okto/okto-wc/main/assets/okto-white-text-logo.svg"  
  }
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
  explorerRecommendedWalletIds={[
    "550b59942eb58a7226381bf7935f22d311e56ee29c3530e44d96b1de0550a35a",
  ]}
/>
```

## [WIP] Using Rainbow Kit

> This option is still in WIP and we are waiting for Rainbow team to merge our PR.

To integrate WC with Okto Wallet add the following parameters to the Rainbow Kit.

```jsx
import {
  oktoWallet,
} from '@rainbow-me/rainbowkit/wallets';

...

const connectors = connectorsForWallets([
  {
    groupName: 'Recommended',
    wallets: [
      oktoWallet({ chains, projectId }),
      ...
    ],
  },
]);

```
