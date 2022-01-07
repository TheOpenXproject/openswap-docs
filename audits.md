---
description: Audits conducted on the smart contracts for OpenSwap
---

# Audits

Security is of the utmost importance to OpenSwap and will always be one driving factors for our future development.  Please review the audits that have been conducted on the OpenSwap smart contracts.

### **V2 Audit**

**Completed By:** 0xGuard

**Date:** October 2021

**Audit Report:** [https://github.com/0xGuard-com/audit-reports/blob/master/openswap\_v2/OpenSwapV2\_final-audit-report.pdf](https://github.com/0xGuard-com/audit-reports/blob/master/openswap\_v2/OpenSwapV2\_final-audit-report.pdf)

**Summary:** An audit was completed on V2 in October of 2021. There are 0 high and 0 medium defects with the V2 smart contracts. All concerns from V1 were eliminated in this audit. Most importantly, the audit confirms OpenSwap is 100% rug-proof. &#x20;

As you read through the audit, please pay attention to the update area for any of the issues listed.  &#x20;



### V1 Audit

**Completed By:** 0xGuard

**Date:** September 2021

**Audit Report:** [https://github.com/0xGuard-com/audit-reports/blob/master/openswap/OpenSwap\_final-audit-report\_v1.pdf](https://github.com/0xGuard-com/audit-reports/blob/master/openswap/OpenSwap\_final-audit-report\_v1.pdf)

**Summary:**  Comments from Alex regarding the V1 Audit, “Overall, really happy about the audit. Most importantly, your money is safe; no one can rob you of your money. However, there are some things I’ll need to be very careful with while maintaining the protocol to prevent any errors in issuance. This is not a responsibility I take lightly.” He expounded on the issuance errors by stating, “Some tokens execute burns on a per transfer basis, this causes overflow or underflow which would emit enormous amounts of tokens instead. We must be mindful for every token non-native uni-LP or simple erc20. Every token added to OpenSwap, I check everything. It is very time consuming but worth the safety it provides.”

The items highlighted in the audit as a risk are directly related to trusting the owner of the project. These are current vulnerabilities that exist on Sushi to this day. However, for Alex and his long-term vision for OpenSwap; this just didn’t fit. While he has the trust of those in the community, the goal is to remove any smidgen of doubt. His exact statement on the topic was “I don’t want anyone to have to trust the owner not to use the exploit.” . V2 will be created to remove the risks mentioned in this audit.
