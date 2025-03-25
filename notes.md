# Outline

This talk intends to showcase the capability that exists within the nix ecosystem in enabling traditional infrastructure as code
patterns such as Ansible, Docker and more to be merged into a single approach that also resolves outstanding issues with the
aforementioned technology.

During the talk, an intent to apply a live demonstration of building a system with nix would be included (with fallback offline copies),
taking the audience though the steps of uplifting existing system while explaining the operational benefits (testing, REPL, automated
diagramming), security benefits (RBAC, POLP, minimalism) and more.

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

- alternative approaches
  - 


  
