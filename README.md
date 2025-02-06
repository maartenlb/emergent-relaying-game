# The Relaying Game

##  [Link to Report](TheRelayingGame.pdf)

## Overview

This repository contains the code and report for **The Relaying Game**, a research project exploring referential games with relaying agents. The project investigates how information is transmitted and retained when multiple intermediate agents relay messages, analyzing the impact on emerged languages using statistical evaluations and unsupervised grammar induction techniques.

## Authors

- **Maarten Burger** - University of Amsterdam  
- **Rico Mossinkoff** - University of Amsterdam  

## Abstract

We extend referential games by introducing relaying agents and analyze how these affect the emerging language. Our findings indicate significant changes in language structure when information is relayed, with some information still being retained even through multiple relayers. The research highlights the importance of studying such relay-based communication models in artificial intelligence.

## Introduction

Referential games have been widely used to study language emergence and evolution. We extend previous research by adding **relayers**, which act as intermediate players in a "pass-the-message" game. The study aims to answer:

1. **What is the rate of information decay in a referential game with various intermediate actors?**
2. **Do the generated languages have a linguistic structure, and how does this change with multiple relayers?**

## Experimental Setup

The experiment involves three types of agents:
- **Sender**: Encodes an image into a message.
- **Receiver**: Decodes the message to retrieve the correct image.
- **Relayer**: Acts as an intermediate agent, decoding and reconstructing the message before passing it forward.

We use the **CIFAR-100 dataset** and measure message retention across different relayer configurations.

## Results

Key findings:
- Accuracy drops as the number of relayers increases, but stabilizes around 3 relayers.
- Even with 10 relayers, information retention remains above random chance.
- Emergent languages show structured grammar despite relayed transmission.
- The language becomes more compressed and structured as relayers increase.

For detailed results, refer to the full [report](TheRelayingGame.pdf).

## Conclusion

Our results indicate that structured language can emerge even with relayed communication. The findings open avenues for further research in AI communication, robustness to noise, and efficiency in information transmission.

## Code Usage

The code is most easily used by opening it in Google Colab, detailed instructions can be found within the notebook.

## References
For a full list of references, see the [report](TheRelayingGame.pdf).

## Acknowledgments
We thank the University of Amsterdam for supporting this research and providing computational resources.
