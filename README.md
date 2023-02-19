<h1 align="center"> GithubCrpyt </h1> <br>
<p align="center">
  <a href="https://gitpoint.co/">
    <img alt="GitPoint" title="GitPoint" src="https://user-images.githubusercontent.com/86847380/219954699-d10f9120-222a-4d21-94a8-b01f8282fd29.png" width="450">
  </a>
</p>

<h2 align="center">
Explore the world of Open Source with Crypto
</h2>

<p align="center">
    Link : https://githubcrypt.netlify.app/
</p>

<hr>

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Working](#working)
- [Advantages](#advantages)
- [Future Scope](#future-scope)
- [Contributors](#contributors)

# Introduction

GithubCrypt is a Decentralized Platform for Open Source developers. It provides a platform for developers to find projects to work on and get rewarded for their work. It also provides a platform for project owners to find developers to work on their projects and pay them in crypto. Developers can post their projects issues and get it solved by other developers.

<hr>

## Features

A few of the things you can do with GithubCrypt:

- **Post your project issues**: Post your project issues and get it solved by other developers.
- **Explore Open Source Projects**: Find and get involved in open source projects.
- **Get Rewarded for your work**: Get rewarded for your work in crypto.
- **Find Developers for your project**: Find developers to work on your project and pay them in crypto.

<hr>

## Working

     1. User can post their project issues and get it solved by other developers.
     2. Once the issue is posted it will be visible to all the developers.

<img alt="githubcrypt" title="githubcrypt" src="https://user-images.githubusercontent.com/86847380/219955566-847e5e8b-1c76-4d2b-ac5b-3ce0c610c0ca.png" >

    3. Developers can choose the issue they want to work on and request to work on it by clicking on the "Request" button.
    4. Once the request is sent the issue will be visible in the trying issues section of the user's profile.

<img alt="githubcrypt" title="githubcrypt" src="https://user-images.githubusercontent.com/86847380/219956100-e0c3304d-81d0-4001-8a33-4d64fe9207f4.png" >

    5. Once requested, the user can start working on the issue. After successfully solving the issue the user can create a pull request.
    6. Once the pull request is merged by the project owner, the user have to claim the reward by submitting the pull request number and marking the issue as completed.
    7. Once the issue is marked as completed the project owner will be able to see the Pay user button in the My issue section.

<img alt="githubcrypt" title="githubcrypt" src="https://user-images.githubusercontent.com/86847380/219956807-8454a81e-e7ec-4d09-a0c5-f6735630548a.png" >

    8. Once the user is paid the issue will be marked as completed and the user will be able to see the issue in the completed issues section of his profile.

<img alt="githubcrypt" title="githubcrypt" src="https://user-images.githubusercontent.com/86847380/219956871-ffb0fd82-12cd-4f39-9f19-677a03b17862.png" >

# Contributors

- [Bhushan Wanjari](https://github.com/Bhushan21z)
- [Anjali Kushwaha](https://github.com/Anjali2201)

# Build Process

Web 3.0

```
- Github.sol smart contract written to store issues and it's data.
- Deployed using HardHat on Alchemy's 'Goerli Test Network'.
- Using Metamask to Process transactions.
```

Client Side

```
- Deployed Smart Contract key is stored.
- abi is generated and Github.json file is stored for interaction between our contract and client side.
- GithubContext file contains all the function for interaction with smart contract variables and data.

```

# Advantages

- **Open Source**: GithubCrypt is an open source project and anyone can contribute to it.
- **Decentralized**: GithubCrypt is a decentralized platform and it is not controlled by any single entity.
- **Secure**: GithubCrypt is a secure platform as all the data is stored on the blockchain.
- **Transparent**: GithubCrypt is a transparent platform as all the data is stored on the blockchain.
- **No Middleman**: GithubCrypt is a platform where there is no middleman and the user can directly interact with the project owner.
- **No Fees**: GithubCrypt is a platform where there are no fees and the user can directly interact with the project owner.

# How to Run

1.          Clone the repository
    `git clone "https://github.com/Bhushan21z/GithubCrypt.git"`)
2.          Change directory to client
    `$ cd smart_contract`
3.          Install dependencies

    `$ npm install`

4.         Install Metamask and Signin to alchemy.

5.         Create new App under Goerli network.

6.         Copy its key and paste it in hardhat.config.js file under url.

7.         Get your metamask account private key and paste it in hardhat.config.js file under account.

8.         Deploy the contract

    `$ npx hardhat run scripts/deploy.js --network Goerli`

9.         Copy the contract address and paste it in client/utils under constants.js file.

10.     Copy account key generated by deploying contract and paste it in client/utils under constants.js file.

11.     under smart_contact/artifacts/contracts copy data of Github.json file and paste it under client/utils into Github.json file.

12.     Change directory to client
    `$ cd client`
13.     Install dependencies

    `$ npm install`

14.     Run the client

    `$ npm run dev`
