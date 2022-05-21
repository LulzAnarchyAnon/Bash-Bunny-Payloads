# Payload Library for the Bash Bunny by Hak5

This repository contains payloads and extensions for the Hak5 Bash Bunny. Community developed payloads are listed and developers are encouraged to create pull requests to make changes to or submit new payloads.

## About the Bash Bunny

By emulating combinations of trusted USB devices — like gigabit Ethernet, serial, flash storage and keyboards — the Bash Bunny tricks computers into divulging data, exfiltrating documents, installing backdoors and many more exploits.
-   [Purchase at Hak5](https://hak5.org/products/bash-bunny "Purchase at Hak5")
-   [Documentation](https://docs.hak5.org/bash-bunny/ "Documentation")
-   [Bash Bunny Forums](https://forums.hak5.org/forum/92-bash-bunny/ "Forums")
-   Discord:  [https://hak5.org/discord](https://hak5.org/discord)

![enter image description here](https://cdn.shopify.com/s/files/1/0068/2142/products/bash-bunny-mk2_001_c58d9658-b151-4328-af26-11eef3c47355_300x.jpg)

## Documentation
Documentation on developing payloads for the Bash Bunny can be found on the [docs.hak5.org](https://docs.hak5.org/bash-bunny/) website. Guides can be found on the [Bash Bunny blog](https://hak5.org/blogs/bash-bunny).

## Disclaimer
Generally, payloads may execute commands on your device. As such, it is possible for a payload to damage your device. Payloads from this repository are provided AS-IS without warranty. While Hak5 makes a best effort to review payloads, there are no guarantees as to their effectiveness. As with any script, you are advised to proceed with caution.

## Legal
Payloads from this repository are provided for educational purposes only.  Hak5 gear is intended for authorized auditing and security analysis purposes only where permitted subject to local and international laws where applicable. Users are solely responsible for compliance with all laws of their locality. Hak5 LLC and affiliates claim no responsibility for unauthorized or unlawful use.

## Contributing
Once you have developed your payload, you are encouraged to contribute to this repository by submitting a Pull Request. Reviewed and Approved pull requests will add your payload to this repository, where they may be publically available.

Please adhere to the following best practices and style guide when submitting a payload.

### Naming Conventions
Please give your payload a unique and descriptive name. Do not use spaces in payload names. Each payload should be submit into its own directory, with `-` or `_` used in place of spaces, to one of the categories such as exfiltration, phishing, remote_access or recon. Do not create your own category.

### Binaries
Binaries may not be accepted in this repository. If a binary is used in conjunction with the payload, please document where it or its source may be obtained.

### Comments
Payloads should begin with comments specifying at the very least the name of the payload and author. Additional information such as a brief description, the target, any dependencies / prerequisites and the LED status used is helpful.

    Title: SMB Exfiltrator
