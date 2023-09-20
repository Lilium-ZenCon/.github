# Lilium - Decentralized carbon credit certifier fueled by real-time data
## ZENCON Hackathon 2023
## [Trailer]()

![5](https://github.com/Lilium-ZenCon/.github/assets/99221221/ecd26c91-b59e-4c95-b505-33b38dac12ff)

## Our solution

The carbon market is a growing industry, valued at an impressive $414.8 billion, and has become a prominent topic when it comes to ESG (Environmental, Social, and Governance) issues. However, despite this substantial movement, it faces significant challenges.

Current methods for monitoring carbon emissions often rely on sporadic site visits and third-party verification. This approach can result in gaps in supervision and data accuracy, making it challenging to ensure that issued carbon credits are an accurate representation of actual emissions reductions. The persistent lack of precise and transparent data is a critical issue in the carbon credit market. Companies often report their emissions inaccurately or inadequately, hindering the verification of the authenticity of issued carbon credits and undermining market integrity.

To address these challenges, Lilium was conceived. Lilium operates as a carbon credit certifier that utilizes advanced technologies such as IoT (Internet of Things), Blockchain, and AI (Artificial Intelligence). The Lilium process begins with IoT, where sensors for humidity, temperature, CO, and a camera are deployed to monitor the real-time condition of forest reserves. These data are collected and recorded on the blockchain.

The blockchain is complemented by an additional layer called Cartesi. [Cartesi](https://cartesi.io/) acts as a virtual machine (Cartesi Machine) that uses the RiscV architecture, providing infrastructure for the execution of complex, high-processing operations in conjunction with the blockchain. This allows AI to be incorporated in a decentralized manner.

Within the Cartesi machine, two artificial intelligences are employed: one dedicated to anomaly detection, based on a Gaussian envelope model trained with NASA data to recognize specific patterns in forest reserves (taking into account location, climate, and vegetation), and another focused on computer vision, capable of identifying trees (used to certify the location of the IoT device).

When any type of anomaly is detected, the issuance of carbon credit tokens is prevented, indicating the need for an on-site inspection. On the other hand, when standards are met, carbon credit tokens can be generated, allowing for carbon footprint compensation.

The fundamental goal of this project is to collaborate with Tupan, an existing initiative in the Zeniq ecosystem. Through this partnership with Tupan, it becomes possible to offer more reliable, reality-backed carbon credits, contributing to a more robust and transparent approach in the carbon credit market.

## Our repositories

*Each repository contains instructions on how to run the code and specific informations.

- Frontend: Contains the code related to the application's frontend.
- Foundry: Contains code for the created contracts.
- Verifier: Contains code used for artificial intelligence and the Cartesi machine code.


## Architecture
![Architeture](https://github.com/Lilium-ZenCon/.github/assets/99221221/96a06143-3ae4-4324-963f-40b48c79ef49)
> ***Disclaimer:*** For this project, a frontend page was created to simulate the hardware, but it has already been tested in previous situations. Below is a photo. 
### Hardware photo

![hardware](https://github.com/Lilium-ZenCon/.github/assets/99221221/1ffb5b22-ed68-4ae9-bdcc-ba654e648b41)


