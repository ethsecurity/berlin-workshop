# ETHSecurity Resources

## What to do

It's time we organized the relevant information into gitbook \(could change if there is strong opinion against it\). The resources we linked before Berlin are below. Here are a list of tasks that need to be accomplished, followed by notes from the workshop, and then general information to think about.

### Proposed Tasks

* [ ] Decide on which delivery platform to use
* [ ] Decide on front page data and layout
* [ ] Decide on how to divide into sections
* [ ] Decide on data and layout of sections
* [ ] Execute on front page development
* [ ] For each section, execute on development
* [ ] Decide on who and how this will be maintained in the long term
* [ ] Decide on a primary url and point it to the site
* [ ] Discuss options for incentivizing maintenance through funding programs

### Notes from Workshop

* We should refer to currently available repositories as much as possible
* Make a clear request to visitors that, if they see anything inaccurate or out of date in this, or any linked repo, then they should open an issue in the appropriate area. We should have a clear path to notification
* We should consider utilizing ETHPrize, gitcoin, etc, to incentivize maintenance of this website
* How will we decide what organizations and information will be legitimate enough for inclusion?

### Information to Note

As we design and develop this website, we should note the following.

* Types of resources

  The list of types of resources and considerations is as follows:

  * Blogs and Articles: Do we link to whole blogs or articles specifically? What is the decision process for inclusion?
  * Repositories: This would be repos like Consensys and ToB. Do we refer to their organization github or to specific repositories? What is the decision process for who and what is included?
  * Lists: This can be lists inside of other repos, or original lists like the audit spreadsheet which lists publicly available audits
  * Tools: If we don't refer to github organizations wholesale, then this would refer to the repos containing tools. Do we have original notes or documentation regarding these tools, or do we simply list links to all of those available without context?
  * Documentation: This would refer to guidelines, manifesto, security report that Kevin compiled, etc
  * Original Material: If any, this would be other material developed by the ETHSecurity group internally
  * Videos and Presentations: We could embed video through plugins and link the slides
  * Websites: This would be references to third party websites which are relevant to security

* Proposed initial process

  On this initial pass, we should simply make decisions on initial content and worry about how we have full inclusion, decide on legitimate content, and maintain over the long term after we have something. From there, the repo should encourage everyone to open issues and make PR's for updates. Once we have tangible movement and the problem of possible spam, then we figure out how to best handle it. If any of this is not agreeable, please submit a pr to change/remove or, if you have access, change/remove this proposal.

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
  * \[IDA EVM: IDA Processor Module for the Ethereum Virtual Machine \(EVM\)

    \]\([https://github.com/trailofbits/ida-evm](https://github.com/trailofbits/ida-evm)\)

  * [pyevmasm: Pythonic EVM Assembler/Disassembler](https://github.com/trailofbits/pyevmasm)
  * [Echidna: Ethereum fuzz testing framework](https://github.com/trailofbits/echidna)
  * [Not So Smart Contracts: Examples of Solidity security issues](https://github.com/trailofbits/not-so-smart-contracts)
* [Piper's dev tactical manual for python projects](https://github.com/pipermerriam/ethereum-dev-tactical-manual)
* \[Go ethereum dev guide\]\([https://github.com/ethereum/go-ethereum/wiki/Developers'-Guide](https://github.com/ethereum/go-ethereum/wiki/Developers'-Guide)\)
* [Ethereum Vulnerability Analyzer Benchmark Reports](https://ethereumanalysisbenchmarks.github.io/%20)

  **Tooling**

  * [Mythril](https://github.com/ConsenSys/mythril)
  * [Oyente](https://github.com/melonproject/oyente)

  **Presentations**

  * Introduction to Ethereum - Alex Fisher
    * [Slides](https://docs.google.com/presentation/d/1t9IhJx-FsYv6iCRTUL9tB1oPIX3QmYWtznWuN5-D4dU)
    * [Video](https://youtu.be/7WyIms8YDVo)  
  * Smart Contract and Dapp Security - ETHDenver
    * [Slides](https://docs.google.com/presentation/d/1t9IhJx-FsYv6iCRTUL9tB1oPIX3QmYWtznWuN5-D4dU)
    * [Video](https://www.youtube.com/watch?v=3oWqQll1KIY)
  * Security Overview - Martin Swende
    * [Slides](https://drive.google.com/file/d/0B69CiKIMgsyeSkdXc1ZuSFE2YWYwamhRc2ZBRjB3ZkladVRN/view?usp=sharing)
    * [Video](https://www.youtube.com/watch?v=qGYki6KYTs8)
  * Cryptoeconomic Protocols - Vitalik
    * [Slides](https://www.slideshare.net/ethereum/vitalik-buterin-cryptoeconomic-protocols-in-the-context-of-wider-society)
    * [Video](https://youtu.be/S47iWiKKvLA)
  * One Year of Eth Security - Martin
    * [Slides](https://drive.google.com/file/d/0B69CiKIMgsyeel9EVGJVd2xjNUxfZkllTEFkMUdHY2ltQ2dZ/view?usp=sharing)
    * [Video](https://www.youtube.com/watch?v=nyMuBUgf8fQ)
  * The Shanghai Attacks - Martin
    * [Slides](https://drive.google.com/file/d/0B69CiKIMgsyeMzk1aVdTd1dXYU9SRFdycG5Md1lxLUlvRVl3/view?usp=sharing)
    * [Video](https://www.youtube.com/watch?v=xl06E2kwi-U)
  * Smashing Smart Contracts for Fun - Bernhard
    * [Slides](https://github.com/b-mueller/smashing-smart-contracts/blob/master/smashing-smart-contracts-1of1.pdf)
    * [Video](https://www.youtube.com/watch?v=NJ9StJThxZY)

## Risk Associated Questions to Consider when Deploying New Contracts to Mainnet

The associated risk \(potential threat level\) of a smart contract will dictate the level of auditing it needs to go through. Here are a few questions you can ask yourself to ascertain its associated risk level:

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
* Transaction-Ordering Dependence \(front running\)
* Timestamp Dependence
* Integer Overflow and Underflow
* DoS with \(unexpected\) Revert
* DoS with Block Gas Limit
* Methods execution permissions
* Oracles calls
* Private user data leaks
* Forcibly sending ether to a contract
* Ownership of the deployed contract

