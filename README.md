# Ponzi Shield

## A Multimodal Real-time System for Detecting Ponzi DApps

### Authors:
- [Nimsara Fernando](https://github.com/nimsara66)
- [Chamod Madhusanka](https://github.com/chamodmadhusanka)
- [Sandun Induwara](https://github.com/sanduninduwara)

### Supervisors:
- Internal Supervisor: Dr. Sandareka Wickramanayake
- External Supervisor: Dr. Dilum Bandara

## Motivation

Decentralized Applications (DApps) have gained rapid popularity within the industry, leveraging their decentralized nature. However, this popularity has also led to the emergence of fraudulent DApps, including Ponzi schemes and phishing scams. In 2019, scammers stole $4.3 billion from millions of victims, with 92% of the losses attributed to Ponzi schemes [1]. Existing solutions offer methods for classifying Ponzi DApps but fall short in identifying them in real-time during transactions.

## Problem Statement

The challenge is to recognize a Ponzi DApp in real time as it transacts, relying on analysis of its smart contract, transactions, and social media sentiment.

## Objectives

1. Detect ongoing Ponzi schemes in DApps in real-time during transactions.
2. Employ social media sentiment analysis for Ponzi scheme detection.
3. Ensure the reliability of social media sentiment by resisting fake content exploitations.
4. Integrate state-of-the-art fusion techniques to combine smart contract data, transaction records, and social media sentiment for a comprehensive Ponzi schemes detection approach.
5. Provide explainability insights into the decision-making process of the Ponzi scheme detection model, ensuring transparency and interpretability in its results.

## Related Work

![](./assets/related-work.png)

## Proposed System

![](./assets/ponzishieldarchitecture.png)

## Smart Contract Branch

[Smartcode Extraction](https://github.com/PonziShield/code-extraction)

## Transacton Branch

[Transacton Data Extraction](https://github.com/PonziShield/test_data_extraction)

## Social Sentiment Branch

[Dapp & Social Media Info Extract](https://github.com/PonziShield/DappInfoExtract)

## Multimodal Fusion

