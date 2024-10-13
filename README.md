# DocsHub

DocsHub is a decentralized application (DApp) built on the Aptos blockchain, providing a secure and reliable platform for storing, sharing, and managing documents. Leveraging the power of blockchain technology, DocsHub ensures data integrity, privacy, and transparency, making it an ideal solution for individuals and organizations seeking a trustworthy document management system.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Setup Pinata IPFS](#setup-pinata-ipfs)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Decentralized Storage**: Utilize the Aptos blockchain for secure document management.
- **Data Integrity**: Ensure documents are tamper-proof with blockchain technology.
- **User-Friendly Interface**: Built with React for a seamless user experience.
- **Wallet Integration**: Connect and manage your documents with your crypto wallet.

## Technologies Used

- **React**: For building the user interface.
- **Vite**: Development tool for fast project setup and builds.
- **shadcn/ui + Tailwind CSS**: For modern styling and responsive design.
- **Aptos TS SDK**: To interact with the Aptos blockchain.
- **Aptos Wallet Adapter**: For wallet connection management.
- **Node-based Move commands**: To compile and manage Move contracts.

## Installation

Follow the steps below to set up and run DocsHub locally:

1. **Install dependencies**:

    ```bash
    npm install
    ```

2. **Initialize the environment**:

    ```bash
    npm run move:init
    ```

3. **Publish the Move contract**:

    ```bash
    npm run move:publish
    ```

4. **Run the application**:

    ```bash
    npm run dev
    ```

## Setup Pinata IPFS

Next, we will set up Pinata to store our documents on IPFS and utilize the API keys in the frontend.

### What is Pinata?
Pinata is a peer-to-peer database storage system that allows us to save our data and access it via a URL. Unlike centralized storage, data in this system is distributed across multiple computers called peers.

### Steps to Set Up Pinata:
1. **Sign up for Pinata**: Create an account on the [Pinata website](https://pinata.cloud).
2. **Create new API keys**: Generate new API keys from your Pinata dashboard.
3. **Fetch the keys**: Copy the generated API keys.
4. **Add the keys to the `.env` file**: Store your API keys in the `.env` file to keep them secure and accessible in your application.

## Usage

Once you have set up and run DocsHub, you can start using the application to manage your documents. Follow these steps to get started:

### Run the Frontend
1. **Navigate to the Project Folder**: 
   - Ensure you are in the `contracts-management-aptosc5` folder.

2. **Install Dependencies**: 
   - Run the following command to install the necessary dependencies:
     ```bash
     npm install
     ```

3. **Run the Application**: 
   - Start the frontend application with the following command:
     ```bash
     npm run dev
     ```
   - After running the app, you should see the main application interface.

### Connect Your Wallet
4. **Wallet Connection**: 
   - Connect the wallet you used to deploy the contracts. This is essential for creating and managing documents.

### Document Creation
5. **Upload Documents**: 
   - Navigate to the document creation page and upload your documents.
   - Ensure you also add the signer address as required.

### Document Management
6. **View Your Documents**: 
   - After uploading, you can view the documents in the “Your Documents” section.

7. **Pending Signatures**: 
   - Go to the “Pending Signatures” section.
   - Click on the “Sign Document” button to sign the document as needed.

By following these steps, you can effectively use DocsHub to create, manage, and sign documents while ensuring security and transparency through the Aptos blockchain.


## Contributing

We welcome contributions to improve DocsHub. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.

