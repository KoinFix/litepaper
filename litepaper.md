# KoinFix Litepaper

## Title

KoinFix: a Web3 P2P Crypto Exchange to Solve DeFi's Fiat On/Off-Ramp Challenge

## Summary/Introduction

KoinFix is a Web3 peer-to-peer (P2P) crypto exchange and fiat on/off-ramp.

You can think of KoinFix as the next generation of the sorely missed services LocalBitcoins, LocalCryptos and Paxful. That is, services where you can buy and sell cryptocurrency P2P by trading fiat for crypto, or vice versa, directly with other users of the platform — or, in the case of KoinFix, the protocol.

Protocol is the correct word here because KoinFix is not a centralized Web2 service run by a corporation like the above-named heroes of the early days of crypto. KoinFix is a Web3 protocol — that is, a set of rules and procedures to follow in order to achieve a given outcome without requiring the permission or assistance of a central authority, or middleman.

In the case of KoinFix, that outcome is to execute a cryptocurrency trade, usually fiat for crypto or vice-versa. When buying crypto with fiat, this is called on-ramping. When selling crypto for fiat, this is called off-ramping.

Web3 protocols usually run as “smart contracts” on blockchains such as Ethereum, Avalanche, Cosmos, etc. In this way, protocols such as KoinFix are aiming to be decentralized and permissionless. Decentralized, because there is no central authority that controls the system. Permissionless, because no one can deny you permission to use the KoinFix protocol, at least in theory.

KoinFix solves the problem of how to onboard to crypto when there are no CEXs that serve you OR you are unable to pass KYC for your nearby CEX or Web2 P2P exchange.

KoinFix makes it possible for everyone to onboard everywhere there are traders, and do it permissionlessly, without depending on middlemen.

KoinFix also makes it possible for the first time to do permissionless fiat-to-fiat remittances by coordinating Web3-style among 3 traders anywhere across the globe.

## Problem

<!--ToDo: facts and figures that explain the depth of the pain-point -->

DeFi, or decentralized finance, today depends on centralized exchanges (CEXs), such as Coinbase, Kraken or Binance. New users of decentralized exchanges (DEXs) and other DeFi services must first acquire their coins or tokens, which usually happens at a CEX.

However, CEXs have some serious drawbacks for crypto users, new and old.

<!--ToDo: focus on the limiting factor or problem, how it limits growth -->

1. CEXs are single points of failure and censorship. If a centralized exchange is hacked, goes bankrupt, or decides to censor certain types of transactions, users could potentially lose access to their funds.

2. Know-Your-Customer (KYC) processes are intrusive, time-consuming, violate users' privacy and present a future risk of identity theft. In developing world countries, not everyone has sufficient forms of identification to pass rigorous KYC.

3. Traditional banking services are unavailable or unreliable in many parts of the world, and many CEXs require that users have bank accounts to use the exchange.

4. CEXs frequently lack direct integration with innovations like automated market makers (AMMs), liquidity mining, yield farming, and other forms of DeFi that are not possible on centralized platforms.

5. In some jurisdictions, CEXs are forbidden or heavily regulated, putting user's ability to on- and off-ramp at risk from regulatory changes and censorship efforts.

6. CEXs control the private keys for the funds they hold. This can be a security risk, especially with increasing hacks. Funds can also be subject to regulatory seizure, with an onerous legal process often required to regain the funds that is expensive and time-consuming.

7. CEXs require users to trust the exchange to accurately report trading volumes, prices, and other market data, but there are allegations that some CEXs engage in wash trading and secretly trade against their own clients.

8. CEXs frequently charge high withdrawal fees.

9. Only a few CEXs have (centralized, Web2) P2P trading services.

### Access to DeFi Matters

<!--ToDo: does this go in problem, solution or as an addendum? -->

Access to DeFi matters today. It is worth defending and expanding. Here's why.

1. **Adoption.** DeFi is fundamental to the continued growth of crypto. P2P cash alone is a great use case. But once people onboard, they want to get a return on their funds, or otherwise do something with their funds beyond just holding them in a wallet. DeFi provides this through yield farming, liquidity mining, collateralized loans and programmable, self-executing smart contracts.

2. **Financial Inclusion.** There is an untapped market of 2+ billion working people in the developing world and elsewhere who do not have access to traditional banking services. Traditional finance (TradFi) is not going to serve them but DeFi can.

3. **Cost.** DeFi can, with greater adoption, provide access to financial services that are lower cost and more efficient than what TradFi offers. This is important when considering the need to facilitate access to prosperity for the working poor across the globe.

4. **Wealth Creation Access.** DeFi opens up inexpensive, efficient investments to the whole world, whereas today those locked into the TradFi world must qualify as an "accredited investor". In this way, TradFi limits access to wealth creation to the already-wealthy, and keeps billions of people locked in poverty.

5. **Transparency.** DeFi transactions are publicly-verifiable on-chain. To reduce corruption across the world, we need this kind of transparency.

6. **Self-Custody.** DeFi gives users control over their own assets via self-custody, rather than requiring them to trust a central authority. This reduces the perverse incentives around CEXs that become more attractive to attackers as they scale. This also eliminates the moral hazard implicit in CEXs, in which the CEX is incentivized to maximize user deposits for their own profit, while the risk of a security breach is largely borne by the users whose funds are at risk.

7. **Interoperability**: DeFi protocols are often designed to be interoperable, meaning they can work together seamlessly. This allows builders to create complex, multi-layered applications, and gives investors access to a wider range of opportunities. This is superior to TradFi, which is a closed collection of proprietary systems.

8. **Resilience**: DeFi systems can potentially offer greater resilience to shocks and systemic risks. They aren't reliant on the health of a single institution, currency or country's economy. DeFi can be a safe haven especially for users whose countries are in crisis due to war, hyper-inflation or other disaster.

### Existing P2P On-/Off-Ramps

Recently, Web2 Crypto on-/off-ramps such as LocalBitcoins, LocalCryptos and Paxful have shut down. Some P2P exchanges still exist, such as Binance P2P and ByBit P2P, but these are run by CEXs and suffer the same drawbacks as CEXs.

All Web2 solutions in this area, furthermore can be shut down or intimidated into shutting down via regulatory action. Thus, they remain incomplete solutions for the long-term.

### Crypto Remittances

There is currently nowhere that a user can go to coordinate with 2 other traders to perform a permissionless fiat-to-fiat cross-border remittance without using the banking system or a legacy remittance corporation such as Moneygram or Western Union.

TradFi remittances have some serious drawbacks.

1. TradFi remittances (via banks, Moneygram, Western Union, etc.) are expensive
2. TradFi remittances can involve onerous and inconvenient KYC.
3. Fees for small remittances, in particular, are prohibitive in many markets.
4. When using informal intermediaries, there can be hassles, delays and hidden fees.
5. TradFi remittance platforms can deny users access at any time for any reason.

## Solution

CEXs were important scaffolding to get crypto to where we are today. But we can go further. We can open up access to DeFi to everyone, everywhere, without arbitrary restrictions, unbearable fees or inconvenient requirements.

We propose a Web3 P2P exchange with the following features.

1. **Decentralized**, so it can not be censored or shut down. P2P exchanges are decentralized, meaning they don't rely on a single central authority to manage and secure transactions. This can reduce the risk of single points of failure and censorship. If a centralized exchange is hacked, goes bankrupt, or decides to censor certain types of transactions, users could potentially lose access to their funds. With a P2P exchange, each user retains control over their own assets. Being decentralized, Web3 P2P exchanges can operate in jurisdictions where centralized exchanges are forbidden or heavily regulated. This makes them resilient to regulatory changes and censorship efforts.

1. **Censorship-Resistant.** We will build it as a Web3 app using self-executing smart contracts on a suitable blockchain to achieve censorship-resistance and resistance to regulatory action.
2. **No Protocol KYC.** No KYC at the protocol level affords more access, financial inclusion and privacy to users when compared with CEXs.
3. **Globally Available**. The protocol will be accessible to anyone with an internet connection, including those in areas where traditional banking services are unavailable or unreliable. This can help to foster financial inclusion.
4. **Integrated with DeFi.** Fiat on-ramps bring fiat directly into DeFi tools such as AMMs and DEXs, without the obstacles of achieving CEX access first.
5. **Self-Custody.**  Users maintain control of their private keys on a P2P exchange, which means they have full control over their funds — unlike with a CEX.
6. **Open Source.** Users and peers can verify what the code does themselves and need not trust a middleman's proprietary closed-source code.
7. **Transparent.** With all operations taking place on-chain, the app is verifiable and thus does not require trust.
8. **Low Fees.** And no withdrawal fees.
9. **Trader-Owned.** We will issue tokens to traders commensurate with their use of the protocol and contributions to adoption. Once the user base is built, the protocol will become owned and operated by token holders via a DAO (decentralized autonomous organization) or similar structure.

### Regulation Compliance

Individual traders can make their own decisions about whom to trade with. We will provide tools to help both makers and takers manage risk, such as identity and reputation.

Individual interfaces to the protocol (web apps, etc.) can also enable geoblocking or KYC as they see fit based on market demand and acceptance.

### Dispute Resolution

Decentralized dispute resolution can be implemented by integrating with or forking with an existing dispute resolution protocol such as Jur, Kleros or Aragon; or a new decentralized dispute resolution protocol could be created.

The KoinFix protocol will booststrap with team-provided dispute resolution, and progressively decentralize as the user base is built.

## Why

### Mission

KoinFix is on a mission to facilitate access to cryptocurrency for people across the globe, without having to endure onerous KYC or the arbitrary limits and opaque reserves status of centralized exchanges (CEXs).

We are building the KoinFix P2P crypto exchange so anyone, anywhere can have uncensorable, KYC-free, transparent and open-source fiat on- and off-ramps.

We see this as making a meaningful contribution towards the goal of facilitating access to prosperity for people across the globe who have been denied access to the full benefits of an accountable monetary system.

Towards that end, we seek to work with individuals, teams, blockchains, companies and anyone who is also excited about this mission.

### Vision

We envision a world of universal prosperity, where every human being has the opportunity to realize their potential.

We envision a world where everyone, everywhere enjoys monetary freedom; and may use and create money as they see fit, trading it on a voluntary basis across borders, from anywhere to anywhere, from anyone to anyone.

We envision a world of crypto mass adoption, where everyone has access to prosperity, where no one is cut out of the system or left behind.

We envision a world free from large-scale oppressive forces such as nation-states and rent-seeking intermediaries such as banks, so that individuals can develop as they see fit, entering into voluntary relationships with each other by mutual agreement, without interference from those who would unjustly tilt the playing field in their own favor using aggressive institutions or unfair restrictions on our liberty.

### Values

Permissionlessness, decentralization, transparency, communication, cooperation, equity, constructiveness, integrity, security.

## How it Works

Pending.

<!--ToDo:
get into the code for this part
create diagrams
screenshots
failure modes and stress tests? risk assessment
terms and conditions
-->

## Use Cases

1. **On-ramp**: to buy cryptocurrency with any number of fiat payment methods.
2. **Off-ramp**: to sell cryptocurrency in exchange for fiat via any number of payment methods.
3. **Remittance**: to build a special transaction with 2 other traders in which the remitter provides fiat to trader 1, trader 1 provides crypto to trader 2 and trader 2 provides fiat to the remittance recipient.
4. **Marketplace**: to sell products and services, including "combo remittances" that permit a remitter in one country to purchase a product or service for delivery to a remittance recipient in another country.

<!--ToDo: identify needs, motivations, and pain points of target market.-->

## Tokenomics

The purpose of the KFIX token is governance. Those who use the protocol to transact value should have the overwhelming majority say in the future development of the protocol.

This helps KoinFix to attract and retain users with a more long-term focus who will repeatedly use the protocol, and grow their stake in it each time they use it to transact value.

### Token Distribution

Two classes of token issuance are contemplated: limited-time and continuous.

#### Limited-Time Issuance

Limited-time issuance may include the following:

- Initial Liquidity (initial liquidity provision (LP) and initial LP rewards)
- Seed Funding (one-time allocation for liquidity and team to fund initial development & marketing)
- Team (4-year vesting schedule with a 1-year cliff)

<!--ToDo: how is the referrer incentivized and where does it come from? Does it perhaps come from continuous issuance? -->

#### Continuous Issuance

Continuous issuance happen with every successfully-completed trade on the KoinFix protocol. Tokens are distributed in the following ratio:

- Maker: 2 tokens (50%)
- Taker: 1 token (25%)
- DAO: 1 token (25%)

The DAO allocation will be governed by KFIX holders and it is expected that the funds will be used to expand liquidity and support KoinFix protocol development.

### Token Supply

The possibility of having no fixed supply is contemplated. This may be desirable in order to ensure continuous incentivization of new traders, enhanced KFIX liquidity and new protocol development. It is expected that these incentives will be fundamental to the continuous growth in adoption of the KoinFix protocol for years to come.

After 2 years, it is contemplated that the rate of continuous issuance will be reduced by 20% per annum in nominal terms in order to enhance KFIX scarcity and incentivize rapid early adoption by traders.

The policies on token issuance could be amended by the team or DAO, in consultation with the community, at any convenient time.

### Token Utility

The KFIX token will be used for governance of the protocol via a DAO, including to vote on the disposition of the DAO treasury. Rewards for liquidity provision are contemplated. Staking and staking rewards is also on the roadmap.

### Incentive Mechanisms

Pending

<!--
- every trade is rewarded
- token holders rule the protocol
- staking could reduce fees and earn rewards
- protocol fees will buyback and burn KFIX
- anyone can submit improve proposals for the protocol
- once the DAO is formed, there can be proposals for funding
-->

## Protocol Fees

Fees will initially be kept as low as possible in order to facilitate adoption while disincentivizing spam.

Fee proceeds could go to one or more of these uses:

- fund the team and its programs.
- buyback-and-burn KFIX tokens.
- distribute to token holders or stakers (once staking is enabled).
- be held in trust for the DAO.

It is expected that fees will initially fund the team, then will be used to buyback-and-burn KFIX tokens and will later be at the disposition of the DAO, once it is formed.

## Roadmap

### Build a Community | Q2 2023

Through a strong brand and a public, participative building process, we expect to build a community aligned with the KoinFix mission, vision and values.

### Launch MVP on Avalanche | Q3 2023

MVP functionality will include the ability to make a trade and centralized dispute resolution.

<!--ToDo: define more detail on the exact features -->

### Launch a Referral Program | Q4 2023

Develop and launch a program where traders are incentivized for referring more traders.

### Find Product-Market Fit | Q2 2024

The protocol will find and evidence an initial product-market fit, to ensure that raised funds are well-invested. Product-market fit refers to when a product satisfies the market demand of a specific group of users.

### Raise Seed Funding | Q2 2024

We expect to raise funding for the following purposes:

1. continued development of the protocol per the roadmap.
2. targeted business development and marketing activities that will hone product-market fit, onboard a strong user base and establish some foundational partnerships.

We may raise funds via LBP (Liquidity Bootstrapping Pool), IDO (Initial DEX Offering), private sale or another method.

### List KFIX on a DEX | Q2 2024

List KFIX on a DEX with initial liquidity. Also list KFIX on a crypto tracker, such as CoinGecko or CoinMarketCap.

### Launch Buyback-and-Burn Program | Q2 2024

We will begin buying-back and burning KFIX token with some or all of the income from protocol fees.

### Launch Reputation System | Q3 2024

We will launch a reputation system to help traders choose whom to trade with.

### Audit the Code | Q3 2024

We will have the code professionally audited and will resolve any high impact issues. Once completed, the protocol will enter public beta.

### Launch Production-Ready Protocol | Q4 2024

The protocol will achieve a 1.0 release.

### Expand Liquidity | Q1 2025

We will enhance KFIX liquidity.

### Expand to More Chains | Q1 2025

We will make plans to expand to other blockchains.

### Launch DAO | Q2 2025

We will launch a KoinFix DAO and progressively decentralize, turning governance control and DAO funds over to the community.

### Launch Decentralized Dispute Resolution | Q3 2025

Via integration or fresh development, we expect to add decentralized dispute resolution to the KoinFix protocol.

### Launch Staking | Q4 2025

Staking of KFIX tokens could enable rewards, fee reductions and/or a share of protocol fees.

### Launch Advanced Trading Tools | Q1 2026

Traders need more tools to know who they are trading with, so they can make the decisions that are right for them.

## Team

George Donnelly (Founder & CEO) is a coder, writer and project manager with 20 years experience in tech and crypto. Get more info at [YoGeorge.com](https://YoGeorge.com/).

### Open Positions

1. **Web3 Programmer**: Skill with Solidity and Javascript is critical. Bonus: Lightning, CashScript, Rust, CosmWasm.
2. **Business Developer**: Proven skills that would assist with partnerships (with other crypto companies and communities) and trader onboarding.
3. **Community Manager**: Proven skill with building and maintaining transparent, friendly and open-source communities is key.

## Conclusion

KoinFix is a Web3 peer-to-peer (P2P) crypto exchange and fiat on/off-ramp. KoinFix solves the problem of how to onboard to crypto when there are no CEXs that serve you OR you are unable to pass KYC for your nearby CEX or Web2 P2P exchange.

KoinFix makes it possible for everyone to onboard everywhere there are traders, and do it permissionlessly, without depending on middlemen.

KoinFix also makes it possible for the first time to do fiat-to-fiat remittances by coordinating Web3 style among 3 traders anywhere across the globe.

Use cases include on-ramping to crypto, off-ramping from crypto, permissionless remittances and product/service sales on a permissionless marketplace.

Most of the KFIX token supply will be allocated to traders, i.e., actual users of the protocol.

KoinFix is on a mission to facilitate access to cryptocurrency for people across the globe, without having to endure onerous KYC or the arbitrary limits and opaque reserves status of centralized exchanges (CEXs). We envision a world of universal prosperity, where every human being has the opportunity to realize their potential.

KoinFix has a robust roadmap that includes building a strong community, launching an MVP prior to seeking seed funding, a KFIX token buyback-and-burn program, reputation, a referral program, decentralized dispute resolution, the formation of a DAO for governance, expansion to other chains, staking and advanced trading tools.

## Call to Action

KoinFix is a mission-driven, community-first, open-source Web3 project. Your participation in KoinFix is enthusiastically welcomed! Here are some ways to start contributing:

- Follow us on [Twitter @realKoinFix](https://twitter.com/realKoinFix).
- [Join our Discord](https://discord.gg/GUdCPxftUq) and offer your ideas.
- Makers can [join our beta program](https://koinfix.zapier.app/beta).
- Make coding contributions to the KoinFix protocol and apps via our [GitHub repos](https://github.com/Panmoni).
- Apply to join the team by emailing support@koinfix.com.

## Links

Website: https://www.koinfix.com

Support Email: support@koinfix.com

### Social
- Twitter: https://twitter.com/realKoinFix
- Discord: https://discord.gg/GUdCPxftUq
- GitHub: https://github.com/Panmoni
- Telegram: https://t.me/Panmoni/288

## Disclaimer

KoinFix is presently in its initial stages of development, and there exist several unpredictable risks. By choosing to acquire KFIX tokens or to participate in KoinFix, you are acknowledging and accepting a multitude of risks that can be associated with the acquisition, possession, and usage of KFIX tokens. 

In the worst-case scenario, these risks could lead to the complete or partial loss of held KFIX tokens.

### Incomplete Information Disclosure

At present, KoinFix is still being developed, and its design concepts, consensus mechanisms, algorithms, code, and other technical aspects may be updated and changed frequently and continuously.

Even though this whitepaper contains the most up-to-date information about KoinFix, it is not exhaustive and may be modified and updated by the KoinFix team periodically. It's neither possible nor mandatory for the KoinFix team to keep KFIX token holders informed about every project detail (including developmental progress and anticipated milestones) relating to the development of KoinFix, hence an incomplete information disclosure is both inevitable and reasonable.

That said, the KoinFix team strives to make our community aware of all pertinent information related to development of the protocol via our Twitter profile at twitter.com/realKoinFix.

### Risks

By deciding to acquire, hold, or utilize KoinFix tokens (KFIX), you expressly acknowledge and assume the following risks:

1. **Investment Risk**: The purchase and sale of KFIX tokens carry considerable financial risk. Prices can fluctuate on any given day. Due to such price fluctuations, you may increase or lose value in your assets at any time. Any currency - digital or not - may be subject to large swings in value and may even become worthless. There is an inherent risk that losses will occur as a result of buying, selling, or trading anything on the market. 

2. **Regulatory Risk**: The regulatory status of KFIX tokens and distributed ledger technology is unclear or unsettled in many jurisdictions. It is difficult to predict how or whether regulatory authorities may apply existing regulation with respect to such technology and its applications, including KFIX tokens and KoinFix. It is likewise difficult to predict how or whether legislatures or regulatory agencies may implement changes to law and regulation affecting distributed ledger technology and its applications, including KFIX tokens and KoinFix. Regulatory actions could negatively impact KFIX tokens and KoinFix in various ways.

3. **Risk of Loss**: The risk of losing your KFIX tokens may be substantial. Digital or not, currency transactions involve significant risk. If the value of KFIX decreases, you could lose your entire investment. 

4. **Risk of Theft and Hacking**: Hackers or other malicious groups or organizations may attempt to interfere with the KoinFix network or the availability of KFIX tokens in any number of ways, including service attacks, Sybil attacks, spoofing, smurfing, malware attacks, or consensus-based attacks. There's also a risk that a third party or a member of the Company, the Distributor, or their affiliates could intentionally or unintentionally introduce weaknesses into KFIX tokens' and/or KoinFix's core infrastructure, which could negatively impact KFIX tokens and/or KoinFix. Cryptography and security innovations' future is highly unpredictable, and advances in cryptography or technology (including quantum computing development) could introduce unknown risks to KFIX tokens and/or KoinFix by rendering the cryptographic consensus mechanism that underlies the blockchain protocol ineffective.

5. **Risk of Development Failure**: Various reasons, including but not limited to a decline in prices of digital assets, virtual currencies, or KFIX tokens, unforeseen technical challenges, and a shortage of development funds, could lead to the non-fulfilment of KoinFix's development plans.

6. **Additional Risks**: The risks mentioned above are not exhaustive, and there exist other risks associated with your participation in KoinFix and the acquisition, possession, and usage of KFIX tokens, including those that the Company or the Distributor cannot predict. Such risks may manifest as unexpected combinations or variations of the aforementioned risks. Prior to acquiring KFIX tokens and participating in KoinFix, you should conduct thorough due diligence on the Distributor, their respective affiliates, and the KoinFix team, and understand KoinFix's overall framework, mission, and vision.

Please consult with your legal, financial, and tax advisors before deciding to participate in the KoinFix network or purchase KFIX tokens.