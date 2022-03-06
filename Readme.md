## BEML Data Transfer Mechanism as a solution for Makeathon

<hr/>
BEML or Bharat Earth Movers Limited, is PSU making large scale utility vehicles used by military and civil defence for construction purposes.

These heavy machines have various parameters which are needed to be continuosly monitored and controlled, but due to the fact that they are operating in such remote locations, internet connectivity is not available for them to store the collected data and to communicate with the central server which is important for the maintenance of the vehicles and managing the fleet working on a location.

So we came up with a solution to tackle this problem. We made a GUI based application which can be used onsite to collect the data from the machines in an encrypted manner using a RSA cypher system and can be collected by a simple mobile application without any internet connectivity using a pseudo-network created using mobile hotspot.
This cyphered data can be sent to the central server using a secure channel to cloud database hosted on Azure and can be decrypted by the central server using the same RSA cypher system.

<hr/>

## Features

- Secure Transfer of Data using public/private key cryptography
- Data can be collected from the machines and sent to the central server without any internet aur mobile services
- Data collected can be viewed on a portal for fleet management and data processing.
- Data can be transfered with minimal packet loss to server.

## Tech Stack Used

- React-Native
- Node.js
- Electron.js
- Express.js
- Azure
- MongoDB
- HTML
- CSS
- Javascript
