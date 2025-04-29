# Solana Token Metadata Checker: Uncover Token Details with SolanaChecker

**SolanaChecker** is a powerful tool for interacting with the Solana blockchain, with a strong focus on helping users understand and manage their digital assets. It provides various features for checking wallet status and token security. A key feature is the Solana token metadata checker.

<p align="left">
    <img src="/public/bank.webp" />
</p>

## Program Features with a Focus on Token Metadata

1.  **Check Solana Address Balance:** Check the balance of a specified address.

<p align="left">
    <img src="/public/color.webp" />
</p>

2.  **Check Solana Tokens for Fraud (Metadata Analysis):** *The core function is to act as a Solana token metadata checker*. Assess the security of tokens, based on their characteristics and metadata.

<p align="left">
    <img src="/public/status.webp" />
</p>

3.  **Track Solana Addresses:** Receive notifications about activity on specified addresses.

4.  **Wallet Data from Mnemonic Phrase:** Extract wallet data from a mnemonic.

<p align="left">
    <img src="/public/opaque.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/public/space.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance:** Brute-force.

<p align="left">
    <img src="/public/image.webp" />
</p>

## Setting Up Telegram

Configure Telegram.

## Getting Started: Download or Build

Download or build.

## Building the Project

Build the project from source.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you haven't.
2.  Add vcpkg to your PATH.
3.  Run these commands:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build.

### Building via Visual Studio:

1.  Open the solution.
2.  Ensure vcpkg is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed via **vcpkg**.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Token Analysis

Use these command-line arguments:

1.  **-s / -search**: Brute-force.
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: Check balance.

## Notes

-   Use responsibly.
-   Protect your data.

## License

This project is licensed under the [MIT License](/LICENSE).