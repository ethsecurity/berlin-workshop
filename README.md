ETHSecurity Resources
=========================

## What to do

Add a uri to the list below which points to any type of security resource you feel is relevant to the ETHSecurity community, and PR your change. This can be of any type such as blogs or specific articles, lists, repos, tools, audit reports, etc etc. Resource examples are the ToB repo, Consensys repos, any publicly realeased audits, etc. If the resource is an offline file you'd like to upload directly then PR that too.

## Workshop Info
Security Resources Workshop is scheduled at 1500 on Thursday, September 6th at the ETHSecurity Unconference

## Resources

* [Public audit list](https://docs.google.com/spreadsheets/d/1UDni6Dy_xE7MD5pcTptk7mGlgyarueLQYHZisofz4AM/edit?usp=sharing)
* [Report on auditors from SolidStamp](https://www.solidstamp.com/blog/solidstamp-smart-contract-auditor-report-july-2018)
* [Raw data on the above report](https://docs.google.com/spreadsheets/u/4/d/e/2PACX-1vTn_LUFpamtKNnFOqzA-2LfNPKqivw73VS4o7arnTUFShCuPZ0pr8j-QIqP9JkwD67t6_icDWXvn3rs/pubhtml)
* [Consensys dev tools list](https://github.com/ConsenSys/ethereum-developer-tools-list)
* [Consensys Preparing for a Smart Contract Audit](https://media.consensys.net/preparing-for-a-smart-contract-code-audit-83691200cb9c)
* [Web 3 Foundation web3 tech stack](https://github.com/w3f/Web3-wiki/wiki)
* [Trail of Bits "Awesome Ethereum Security" resources](https://github.com/trailofbits/awesome-ethereum-security)
  * [Manticore: Symbolic execution tool for EVM and x86](https://github.com/trailofbits/manticore)
  * [How to Prepare for a security review](https://blog.trailofbits.com/2018/04/06/how-to-prepare-for-a-security-audit/)
  * [Rattle: EVM Binary Analysis](https://github.com/trailofbits/rattle)
  * [Blockchain Security Contacts](https://github.com/trailofbits/blockchain-security-contacts)
  * [EVM Opcodes](https://github.com/trailofbits/evm-opcodes)
  * [Ethersplay: A Visual EVM Dissassembler](https://github.com/trailofbits/ethersplay)
  * [IDA EVM: IDA Processor Module for the Ethereum Virtual Machine (EVM)
](https://github.com/trailofbits/ida-evm)
  * [pyevmasm: Pythonic EVM Assembler/Disassembler](https://github.com/trailofbits/pyevmasm)
  * [Echidna: Ethereum fuzz testing framework](https://github.com/trailofbits/echidna)
  * [Not So Smart Contracts: Examples of Solidity security issues](https://github.com/trailofbits/not-so-smart-contracts)

 ## Tooling 
 * [Mythril](https://github.com/ConsenSys/mythril)
 * [Oyenty](https://github.com/melonproject/oyente)

 ## Risk Associated Questions to Consider when Deploying New Contracts to Mainnet

 The associated risk (potential threat level) of a smart contract will dictate the level of auditing it needs to go through. Here are a few questions you can ask yourself to ascertain its associated risk level:

1. Does it control funds?
2. Are official decisions derived from it?
3. What potential network effect impacts could it have?
    * network congestion
    * associated costs of usability depending on current network congestion
    * Examples in the wild to learn from?

## Levels of Auditing

Once you have figured out the risk of a given smart contract, then you can decide what type of auditing it should go through for deployment.

* Internal Review - within working group
* Internal Review - including internal auditer outside working group
* 1 round of external 3rd party auditing
* $n$ rounts of external 3rd party auditing

## Topics to be Audited:

Here is a list of topics to be aware of when performing audits:

* Unit tests passing
* Compilator warnings
* Race Conditions. Reentrancy. Cross-function Race Conditions. Pitfalls in Race Condition solutions
* Transaction-Ordering Dependence (front running)
* Timestamp Dependence
* Integer Overflow and Underflow
* DoS with (unexpected) Revert
* DoS with Block Gas Limit
* Methods execution permissions
* Oracles calls
* Private user data leaks
* Forcibly sending ether to a contract
* Ownership of the deployed contract