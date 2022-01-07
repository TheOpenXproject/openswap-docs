---
description: OpenX introduction, migration details and guide
---

# OpenSwap V2 Migration

#### OpenSwap V2 has arrived: OpenX introduction, migration details and guide

We are beyond ecstatic to announce the arrival of OpenSwap V2. As you may recall, in late September, OpenSwap had an audit that noted a minor security concern. The basis of the concern fell solely on trusting the developer of the project. The OpenSwap team wanted to remove any doubt from this project and immediately started working on V2. It is officially time to put V1 to bed and move on to our future. OpenSwap V2 brings a new token name, a new audit, and more.

![](https://cdn-images-1.medium.com/max/716/1\*mkQmszJITvIE-gi7N74nuQ.png)

**Token Name Change**\
With V2, the OpenSwap token will now be referred to as OpenX. The OpenX address is 0x01A4b054110d57069c1658AFBC46730529A3E326 . The token swap between oSwap and OpenX will be 1:1 and processed through a migrator on the OpenSwap site. Tokenomics of the original oSwap token will remain intact for OpenX. The old oSwap tokens will be retired during the migration process.

**V2 Audit completed, 100% rug-proof**\
An audit was completed on V2. There are 0 high and 0 medium defects with the V2 smart contracts. Most importantly, the audit confirms OpenSwap is 100% rug-proof. The audit was completed by 0xGuard; the report can be found [here](https://github.com/0xGuard-com/audit-reports/blob/master/openswap\_v2/OpenSwapV2\_final-audit-report.pdf).\


![](https://cdn-images-1.medium.com/max/716/1\*v\_R3ZmkHUT0wTIFHqdHLyA.png)

**User guides to migrate V1 to V2**\
To assist you in the migration process, we created two different guides: one for those with oSwap currently in their wallet and one for those with oSwap in single stake or staked LPs.

_**Migrate oSwap that is currently in your wallet**_\
**STEP 1:** Go to [https://app.openswap.one](https://app.openswap.one)\
**STEP 2:** Click on ‘More’ in the top menu\
**STEP 3:** Click ‘Migrate’\
**STEP 4:** Enter the amount of oSwap to migrate. We suggest using the ‘max’ button for this feature.\
**STEP 5:** Click ‘Approve’. \
**STEP 6:** Your wallet will prompt you to approve OpenSwap for conducting a transaction with this token, approve it. \
**STEP 7:** Click ‘Migrate’\
**STEP 8:** Your wallet will prompt you to confirm the transaction, approve it. \
There will be two notifications when you submit a transaction: transaction sent and Transaction successful.\
**STEP 9:** Add the OpenX token so it is visible in your wallet (see below).

_**Migrate oSwap in single stake or LPs**_\
If you have oSwap in single stake or staked LPs, please follow these steps for the migration.\
**STEP 1:** Go to [https://app.v1.openswap.one](https://app.v1.openswap.one)\
**STEP 2:** Click on ‘Farm’ in the menu\
**STEP 3:** Click on the details of the LP\
**STEP 4:** Click ‘Unstake’ the LPs\
**STEP 5:** Click ‘Max’ and then click ‘Unstake’ \
**STEP 6:** Confirm in your wallet.\
**STEP 7:** Click ‘Liquidity’ in the top menu\
**STEP 8:** Select the two tokens of the LP\
**STEP 9:** Click ‘Next’\
**STEP 10:** Click ‘Remove Liquidity’\
**STEP 11:** Click ‘Max’\
**STEP 12:** Click ‘Approve’ and confirm in your wallet\
**STEP 13:** Click ‘Remove’ and confirm in your wallet

**!! Important Step!!** \
**STEP 14:** Go to [https://app.openswap.one](https://app.openswap.one)\
**STEP 15:** Click on ‘More’ in the top menu\
**STEP 16:** Click ‘Migrate’\
**STEP 17:** Enter the amount of oSwap to migrate. We suggest using the ‘max’ button for this feature.\
**STEP 18:** Click ‘Approve’. \
**STEP 19:** Your wallet will prompt you to approve OpenSwap for conducting a transaction with this token, approve it. \
**STEP 21:** Click ‘Migrate’\
**STEP 22:** Your wallet will prompt you to confirm the transaction, approve it. \
There will be two notifications when you submit a transaction: transaction sent and Transaction successful.\
**STEP 23:** Add the OpenX token so it is visible in your wallet (see below).\
**STEP 24:** At this time, you can recreate LPs and stake.

_**Adding OpenX to your Wallet:**_\
For a Metamask wallet:\
**STEP 1:** Enter your Metamask wallet and scroll to the bottom of the popup.\
**STEP 2:** Click ‘Import Tokens’. \
**STEP 3:** In the ‘Token Contract Address’ enter in the OpenX address **0x01A4b054110d57069c1658AFBC46730529A3E326.** \
**STEP 4:** Click ‘Add Custom Token’ button.

#### For a Harmony wallet: **STEP 1:** Enter your Harmony Wallet click on ‘HRC20’. **STEP 2:** Click the plus sign at the bottom of the popup. **STEP 3:** In the ‘Token Contract Address’ enter in the OpenX address **one1qxjtq4q3p4tsd8qktzhmc3nnq5568cexh9c90j** . **STEP 4:** Click Add.

\
**V2 Enhancements**

**Governance Voting Platform (TBD)**\
Plans to create a platform where OpenSwap voting will take place are in the works. This allow the community to vote on topics and guidance for the OpenSwap project.

**Auto-Compounding Single Staking (TBD)**\
V2 will allow for an auto-compounding single stake pool for the new OpenX token. The time frame regarding the release of this feature has yet to be determined.

**Integrations (TBD)**\
With the release of V2, there will be a coordinated effort to integrate with tracking websites such as CoinMarketCap, Coin gecko, Defi Lama, etc. While there are no promises of a listing with these sites, every attempt will be made to have them completed.



V2 Contracts:

UniswapV2Factory = 0x5d2F9817303b940C9bB4F47C8C566c5C034d9848

UniswapV2Router02 = 0x2F99992024DCC51324BA4956bB1c510F36FA54F5

Init code hash for UniswapV2Pair is: 0x613b6eaa34b43dcb7eb8881dd4b5af85805be104d5f2f385304ffa8bda5e219c

OpenSwapToken = 0x01A4b054110d57069c1658AFBC46730529A3E326

OPENxMaker = 0xff819FcdACf0bb69Cf4621340F85D7f20744d450

MasterChef = 0xb2E9B85FB43082F3148B0D13450E8BEB5C9B63f2

OpenBridge = 0x1A47E63DE006aa7aaFa5aB4DdFBfB6Ae0F8eD010
