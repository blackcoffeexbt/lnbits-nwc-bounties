### Bounty Specification: Build a Nostr Wallet Connect Wallet Service Extension for LNbits

#### **Project Overview**

This project aims to build a Nostr Wallet Connect (NWC) extension for LNbits to allow LNbits to act as a NWC Wallet Service as defined in NIP-47 https://github.com/nostr-protocol/nips/blob/master/47.md

LNbits has an [example extension](https://github.com/lnbits/example) that can be used as a starting point on your extension development journey.

#### **Objective**

To develop a fully functional NWC Wallet Service extension that adheres to the NIP-47 protocol specifications, enabling the following capabilities:

- Generation and handling of Nostr Wallet Connect URIs.
- Processing of payment requests including `pay_invoice`, `make_invoice`, `lookup_invoice`, `list_transactions`, `get_balance`, `multi_pay_invoice`, `pay_keysend`, `multi_pay_keysend` and `get_info` 
- Creation and lookup of invoices.
- List and balance querying functionalities.
- Secure communication through encrypted events as per NIP04.
- Implementation of error codes
- Implementation of connection rules with control of the following: `Maximum payment amount`, `maximum daily budget`, `connection expiry date` (never expire should be an option) denominated in sats.

#### **Deliverables**

1. **NWC Wallet Service Extension Code**: Clean, commented, and secure codebase that uses the existing LNbits `nostrclient.py` functionality and an LNbits funding source to provide a NWC Wallet Service.
2. **NWC Wallet Service Extension UI**: A user interface within the extension that allows a user to connect a new app to the NWC wallet service and edit existing connections. The app connection should allow control of the following rules:
	   `Maximum payment amount`
	   `Maximum daily budget`
	   `Connection expiry date` (never expire should be an option) 
1. **Documentation**: Documentation covering:
    - Setup and configuration instructions.
    - Usage examples.
2. **Test Suite**: [VLAD: Can you add some detail around the test requirements please?]

#### **Technology Requirements**

- The extension must be developed in Python, consistent with the LNbits platform.
- Use of existing LNbits libraries and adherence to its architectural style is required.
- NIP-47 specification must be adhered to.

#### **Budget**

- **Total Bounty**: XXXXXX sats
- Payment will be made upon final delivery, after successful testing and documentation review.

#### **Evaluation Criteria**

- Adherence to the NIP-47 specifications and LNbits integration requirements.
- Security and efficiency of the implementation.
- Quality of documentation and ease of use.

#### **How to Apply**

[How should devs apply for the bounty?]
