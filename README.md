# onyx-hackathon-zktoro

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

# zkToro

<img src="public/images/logo.jpeg" alt="zkToro Logo" width="200" style="border-radius:80;"/>



## Description

zkToro is a decentralised node management platform that ties the nodes in the blockchain network to a unique biometric identifier from every user. This ensures that malicious actors cannot return to the same network with another node and another wallet address after paying a small slashing fee. This Next.js project is a comprehensive solution for managing nodes effectively and securely.

## Features

- **Node Management:** Easily add, remove, and manage nodes in the blockchain network.
- **Biometric Identification:** Every node is tied to a unique biometric identifier, enhancing security.
- **Decentralized:** Leveraging blockchain technology for decentralized operations.

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd onyx-hackathon-zktoro-main
```

2. Install the dependencies:
```bash
npm install
```

## Usage
### Running the development server
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

### Running the Worldcoin Simulator (if you do not have the app)

Open [https://simulator.worldcoin.org/id/0x083d03db](https://simulator.worldcoin.org/id/0x083d03db) with your browser, click on *Scan QR or Paste data* and then paste the following public key, representing one of several running nodes' public address on our own AWS servers:

´´´bash
55f286132ea6060090f60934a1c8a0506377075506567748d8de9564f3463b8a
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


### Building the project
```bash
npm run build
```

### Starting the production server
```bash
npm run start
```

### Linting the code
```bash
npm run lint
```

## Project Structure

The project is structured as follows:

- `src/`: Contains the source code of the application.
    - `app/`: Contains layout, global styles, and favicon files.
    - `home/`: Contains the main homepage and related components.
    - `NodeTable/`: Contains components related to node management.
    - `VerificationFlow/`: Components related to the verification flow.

- `public/`: Contains public assets that can be accessed globally.

- `components.json`, `next.config.js`, `tailwind.config.js`: Configuration files.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork and clone the repository.
2. Create a new branch: 
```bash
git checkout -b feature/my-new-feature
```
3. Make your changes and commit them:
```bash
git commit -m 'Add some feature'
```
4. Create the pull request.

