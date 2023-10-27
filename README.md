# Bidirectional Paper-Repository Traceability

There's a gap between academic papers and data/code repositories due to the absence of bidirectional links. We propose to develop a tool that connects scientific papers to their relevant GitHub repositories and vice versa. Our approach involves devising algorithms to search both academic platforms and GitHub for mutual references, integrating features into the tool for automatic link creation, and incorporating capabilities to auto-comment on platforms like arXiv when a corresponding GitHub repository is detected. Ultimately, we aim to promote the significance of traceability, emphasizing its importance to both the academic and developer communities.

***

## About this project

This repository was developed as part of the [Mapping the Impact of Research Software in Science](https://github.com/chanzuckerberg/software-impact-hackathon-2023) hackathon hosted by the Chan Zuckerberg Initiative (CZI). By participating in this hackathon, owners of this repository acknowledge the following:
1. The code for this project is hosted by the project contributors in a repository created from a template generated by CZI. The purpose of this template is to help ensure that repositories adhere to the hackathon’s project naming conventions and licensing recommendations.  CZI does not claim any ownership or intellectual property on the outputs of the hackathon. This repository allows the contributing teams to maintain ownership of code after the project, and indicates that the code produced is not a CZI product, and CZI does not assume responsibility for assuring the legality, usability, safety, or security of the code produced.
2. This project is published under a MIT license.

## Code of Conduct

Contributions to this project are subject to CZI’s Contributor Covenant [code of conduct](https://github.com/chanzuckerberg/.github/blob/master/CODE_OF_CONDUCT.md). By participating, contributors are expected to uphold this code of conduct.

## Reporting Security Issues

If you believe you have found a security issue, please responsibly disclose by contacting the repository owner via the ‘security’ tab above.




docker run --platform linux/amd64 -p 127.0.0.1:9998:9998 apache/tika
