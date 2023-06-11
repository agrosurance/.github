![brand](https://github.com/agrosurance/.github/assets/96080203/37d9a525-da4f-4791-86b4-6eb477923cfb)

<h4 style="text-align:center;" align="center">The Agrosurance project is an innovative platform that aims to revolutionize the agriculture industry by providing a transparent, reliable, and decentralized solution for agricultural insurance and liquidity management.</h4>



## What it Does

Agrosurance enables farmers and agricultural stakeholders to access fair and transparent insurance coverage. The platform calculates insurance premiums and verifies claims using on-chain code stored securely on the blockchain. By fetching real-time data from trusted external sources using Chainlink functions, the platform accurately determines premiums and validates claims based on predefined rules and triggers.


The platform also offers a staking mechanism where investors can stake their Matic tokens and earn Agrocoin as staking rewards. By participating in the staking program, investors contribute liquidity to the platform and help secure the network. Staking rewards are distributed periodically, providing an incentive for long-term participation and fostering a vibrant community.


## How we built it

Agrosurance is comprised of five smart contracts, each serving a specific purpose within the platform:

- [ ] **AgroCoin**: The AgroCoin smart contract represents the ERC20 token used within the Agrosurance ecosystem. It allows for the transfer and management of AgroCoins among users. The contract also includes governance support, providing a foundation for future protocol governance mechanisms.

- [ ] **AgroSuranceLand**: The AgroSuranceLand smart contract is responsible for tokenizing users' land into non-fungible tokens (NFTs) with on-chain metadata. This contract allows for the representation and management of land assets within the platform. Users can tokenize their land and utilize it as collateral for insurance coverage or other purposes within the Agrosurance ecosystem.

- [ ] **FundManager**: The FundManager smart contract serves as a centralized repository for managing the funds within the Agrosurance platform. It securely holds the Matic tokens received from the InsuranceManager and the StakingManager contracts. The FundManager ensures proper allocation and distribution of funds for insurance claims, staking rewards, and other financial operations.

- [ ] **StakingManager**: The StakingManager contract enables users to stake their Matic tokens and receive AgroCoins as staking rewards. It handles the staking process, tracks users' staked amounts and rewards, and ensures the proper distribution of AgroCoins to stakers based on predefined rules and mechanisms. This contract incentivizes liquidity provision and community participation within Agrosurance.

- [ ] **InsuranceManager**: The InsuranceManager contract facilitates the insurance-related functionalities within Agrosurance. It allows users to obtain insurance quotes, purchase insurance policies, and file claims. The contract calculates insurance premiums based on predefined algorithms and verifies claim eligibility based on predefined rules. The InsuranceManager plays a critical role in providing transparent and efficient insurance coverage for users' agricultural assets.


These smart contracts work together to create a robust and comprehensive platform for agriculture insurance and liquidity management. They tokenize land assets, handle the staking mechanism, manage insurance-related operations, and ensure proper fund allocation within the ecosystem.


Through these smart contracts, Agrosurance aims to provide farmers, investors, and other users with a transparent and reliable platform for agricultural risk management and participation in the agrosurance economy.
