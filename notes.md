# Outline

Over 40 years have passed since Ken Thompson asked "To what extent should one trust a statement that a program is free of Trojan horses?", yet still a large segment of the technological landscape is unfortunately in a position of trusting trust

What are reproducible builds? Why do they matter? Does my $TECHNOLOGY have a pathway towards providing consumers reproducible outputs?

During the presentation, we will discuss these questions, unpack what current state of various technologies might be and provide guidance to the audience on how they may also contribute to a more resilient and trustworthy world

Warning: side effects of reproducibility may include stronger supply chains, capability to build and produce provable provenance of an output and an over-eagerness to tell anyone who will listen about it

## Structure

- whoami
- intro

  - what are:
    - repeatable builds
    - hermetic builds
    - reproducible builds
  - why:
    - would we care about builds being reproducible (as a builder):
      - security/trust
      - transparency (where applicable)
      - CICD as zero-trust space
      - reg/compliance objectives
  - talk objectives:
    - better understanding of:
      - the problem space
      - techniques or tooling that might assist
      - the benefits of reproducibility:
        - native SBOMs
        - validatable/verifiable
        - auditable

- state of the union (where is the current tooling at / background)

  - docker / containers / OCI (explain why we're not going to cover all CICD options (time))
    - good elements
    - bad elements
    - ugly elements

- ## alternative approaches
