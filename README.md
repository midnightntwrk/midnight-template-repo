# Midnight Template Repo
This GitHub repository should be used as a template when createing a new Midnight GitHub reppository. 
The template is configured with default repository settings and a set of default files that are expected to exist in all Midnight GitHub reppositories.

### LICENSE
  Apache 2.0.
  
### README.md
  Provides a brief description for users and developers who want to understand the purpose, setup, and usage of the repository.

### SECURITY.md
  Provides a brief description of the Midnight Foundation's security policy and how to properly disclose security issues.
  
### SECURITY.md
  Provides a brief description of the Midnight Foundation's security policy and how to properly disclose security issues.
  
### CODEOWNES
  Defines repository ownership rules.

### ISSUE_TEMPLATE
  Provides templates for reporting various types of issues, such as: bug report, documentation improvement and feature request.

### CLA Assistant
  The Midnight Foundation appreciates contributions, and like many other open source projects asks contiributors to sign a contributor
  License Agreement before accepting contributions. We use CLA assistant (https://github.com/cla-assistant/cla-assistant) to streamlines the CLA
  signing process, enabling contributors to sign our CLAs directly within a GitHub pull request. 

### Checkmarx
  The Midnight Foundation uses Checkmarx for application security (AppSec) to identify and fix security vulnerabilities.
  All repositories are scanned with Checkmarx's suite of tools including: Static Application Security Testing (SAST), Infrastructure as Code (IaC), Software Composition Analysis (SCA), API Security, Container Security and Supply Chain Scans (SCS).   

# TODO
After copying the repository template owners should review and change the following:

### CODEOWNERS
  Change code owners accordingly.

### checkmarx.yaml
  Check and adjust:
  1. Default branch name (not requiered if default branch name is 'main').
  2. Repository name in the URL  "additional_params: --scs-repo-url https://github.com/midnightntwrk/midnight-template-repo --scs-repo-token ${{ secrets.MIDNIGHTCI_REPO }}".
