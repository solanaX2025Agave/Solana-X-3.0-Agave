# Solana-X-3.0-Agave

**The Next-Gen Layer 3 Blockchain 2.0 Stack for Mobile-Native Web3**

Welcome to **[Solana-X-3.0-Agave](https://github.com/solanaX2025Agave/Solana-X-3.0-Agave)** — the official GitHub hub for the **Mobile-Native Web3**, reimagined for the **Layer 3 Blockchain 2.0** era. Built on Solana’s ultra-high-performance foundation, this repository powers **seamless, secure, and mobile-first dApp experiences** with **zero-friction wallet connectivity**.

---

## [Documentation Website](https://docs.solanamobile.com/)

| Category | Resources |
|--------|---------|
| **General** | [Development Setup](https://docs.solanamobile.com/getting-started/development-setup) |
| **React Native** | [Setup](https://docs.solanamobile.com/react-native/setup) • [Quickstart](https://docs.solanamobile.com/react-native/quickstart) • [Stack Overview](https://docs.solanamobile.com/getting-started/overview) |
| **Android** | [Setup](https://docs.solanamobile.com/android-native/setup) • [Quickstart](https://docs.solanamobile.com/android-native/quickstart) |
| **Unity** | [SDK Overview](https://docs.solanamobile.com/unity/unity_sdk) |
| **Samples** | [Sample Apps](https://docs.solanamobile.com/sample-apps/sample_app_overview) |

---

## Summary

The **Mobile Wallet Adapter specification**, **Android & JavaScript reference implementations**, **demo wallet and dapps**, and **comprehensive documentation** — all in one connected ecosystem.

> **Enabling Layer 3 Blockchain 2.0 interactions** via secure, standardized mobile wallet protocols.

---

## Target Audience

This repository is crafted for **Solana mobile developers** building the future of **decentralized mobile applications** on **Layer 3 Blockchain 2.0** infrastructure.

---

## What's Included

| Component | Description | Link |
|---------|-------------|------|
| **MWA Protocol Spec** | The standard for mobile-to-dapp communication | [View Spec](https://solana-mobile.github.io/mobile-wallet-adapter/spec/spec.html) |
| **Android Integration Guide** | For wallets & dapps | [Read Guide](android/docs/integration_guide.md) |
| **Wallet Library** | Provide signing services | [walletlib](android/walletlib) |
| **dApp Client Library** | Consume signing services | [clientlib](android/clientlib) |
| **Fake Wallet & dApp** | Instant integration testing | [fakewallet](android/fakewallet) • [fakedapp](android/fakedapp) |
| **JS Reference Impl** | Core protocol in JavaScript | [mobile-wallet-adapter-protocol](js/packages/mobile-wallet-adapter-protocol) |
| **web3.js Wrapper** | Use familiar `@solana/web3.js` types | [wrapper](js/packages/mobile-wallet-adapter-protocol-web3js) |
| **Wallet Adapter Plugin** | Plug-and-play with [Solana Wallet Adapter](https://github.com/solana-labs/wallet-adapter) | [plugin](js/packages/wallet-adapter-mobile) |
| **Example Web App** | Sign messages & send transactions | [example-web-app](examples/example-web-app) |
| **Example React Native App** | Full mobile wallet interaction flow | [example-react-native-app](examples/example-react-native-app) |

---

## How to Build

All Android projects build seamlessly with **[Android Studio](https://developer.android.com/studio)**

[General Development Setup](https://docs.solanamobile.com/getting-started/development-setup)

---

## Add to Your Project

### For **dApps**

| Platform | Setup Guide |
|--------|------------|
| Android | [Setup](https://docs.solanamobile.com/android-native/setup) |
| React Native | [Setup](https://docs.solanamobile.com/react-native/setup) |

#### **Java**
groovy
dependencies {
    implementation 'com.solanamobile:mobile-wallet-adapter-clientlib:2.0.7'
}
dependencies {
    implementation 'com.solanamobile:mobile-wallet-adapter-clientlib-ktx:2.0.7'
}
dependencies {
    implementation 'com.solanamobile:mobile-wallet-adapter-walletlib:2.0.7'
}

##Get Involved
Contributions welcome!
Powering the Mobile Layer 3 Blockchain 2.0 Revolution — One secure transaction at a time.

#SolanaX #Layer3 #Blockchain2.0 #MobileWeb3 #Agave
ies {
    implementation 'com.solanamobile:mobile-wallet-adapter-clientlib:2.0.7'
}
