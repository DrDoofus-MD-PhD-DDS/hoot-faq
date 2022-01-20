# ShuffleDAO FAQ
Note that the information in this FAQ is preliminary and subject to change
AND IS NOT OFFICIAL OR ENDORSED BY HOOTS TEAM

I am adding daily to this, so be careful about using it for anything for public view.
Things will change, spelling corrected etc.

## What is ShuffleDAO?
ShuffleDAO is the governance body created to promote use of the DAO's native token, the MINT, as a common currency among NFT communities.
The DAO also governs one of the primary methods of introducing MINTs into other NFT communities, ShuffleMint NFT Studio.

## How will ShuffleDAO achieve its goal?
Through the DAO, we hope to encourage use of MINTs across other NFT projects, in lieu of them having to create their own internal currency or utility token.
This saves them time and money, as well as, creating built in value for those communities. Ultimately, this also benefits ShuffleDAO by adding value to MINTs.
Projects that partner with the DAO, either directly or via ShuffleMint NFT studio, will receive MINTs in return both for the project itself and the purchasers of their NFTs.

## What is ShuffleMint NFT Studio and how can it help me?
ShuffleMint is a generative art creation utility and contract deployment system that comes with a hands on team ready to assist your NFT project as much or as little as you require. For more information, see the ShuffleMint FAQ.

## What are MINTs?
MINTs are the native token of ShuffleDAO. MINTs are a free-floating token (not pegged in value to another token) that are backed by ETH at a ratio of at most 1 million MINTs per ETH, meaning that for every one million MINTs, there is at least 1 ETH in the DAO treasury. The value of the MINT can rise relative to ETH, but more MINTs are never created without backing revenue of at least 1 ETH per one million. MINTs, or some derivative such as wrapped MINTs, will not only be part of the incentives for partner projects to reward their NFT communities, but will also be rewarded for staking CryptoHoots, purchasing bonds and buying auction NFTs.

## How will the DAO bring in revenue?
ShuffleDAO has several revenue streams:
- Projects that partner with ShuffleMINT NFT Studio will pay ETH into the DAO for use of studio utilities and team member help
- Projects can buy MINTs with ETH directly to use in their communities internal tokenomics
- Daily auction NFTs can be purchased with ETH to give the buyer governance rights in the DAO and a share of bonding fees
- Bonds purchased at discounted prices with ETH
- Fees from ownership of the MINT-ETH liquidity pool
- Yield from treasury investment in safe DeFi protocols like Rocket Pool's rETH or AAVE

## When are MINTs minted?
MINT is minted:
- to the purchaser when a bond is purchased
- to the DAO (an additional 25% of the total distributed MINT to the purchaser) when a bond is purchased
- to early auction NFT winners
- when pMINT from team members, contributors, or investors vests

## What flavors of MINTs are there?
ShuffleDAO supports: MINT, sMINT, wsMINT, veMINT, pMINT, and bMINT. Described below.

## What is sMINT and what is rebasing?
MINTs can be staked in return for sMINTs (staked MINTs) at a 1:1 ratio. The reason to stake MINTs (lock them in a contract where you cannot use or trade them), is to allow the staker to share in DAO bonding revenue via rebasing. When ETH from bonds comes into the DAO, a number of MINTs are minted at the current ETH value. For example, if one ETH came into the DAO and MINTs were trading at 1,000 MINTs per ETH, then 1,000 MINTs would be created. sMINTs are then minted in equal amount. The new sMINTs are sent to current sMINT holders proportionally to maintain their current share of DAO value (if you held 1% of the DAO, you would receive 1% of new sMINTs). This is rebasing. Staked MINTs can be unstaked at any time to receive MINTs, but rebasing will then cease for those MINTs. Without staking, it would be problematic to send new tokens to MINT holders (suppose MINTs were in a liquidity pool or other smart contract, for example). Unless sMINT is sent to early auction NFT winners and pMINT vestings, there will be more MINT than sMINT.

## What is wsMINT?
As noted in the sMINT FAQ above, unstaked tokens are difficult to deal with from a rebasing standpoint. The wsMINT (wrapped sMINT) is a flavor of MINT based on sMINT holdings. The wsMINT is wrapped in the sense that you can borrow against your sMINTs and use the wsMINT external to the DAO ecosystem for other (DeFi, L2, etc.) purposes. An amount of wsMINT can be withdrawn to your wallet in proportion to your sMINT. The ratio of wsMINT to sMINT is time dependent and is called the Wrap Factor. If the Wrap Factor is, for example, 1.5, then `number of wsMINTs = 1.5 x number of sMINTs`. If the factor is two when you wish to return your wsMINTs, you would get `(number of wsMINT) / 2 sMINTs` in return. The Wrap Factor is determined from the ratio of the value of one sMINT from the current time to the origin. So if MINT value now is 500,000 MINT per ETH and in the beginning of the DAO it was 1,000,000 MINT per ETH, the Wrap Factor would be two. This allows using wsMINTs outside the DAO ecosystem without losing staking rewards while still tracking value versus ETH.

## What is veMINT and how can MINT holders get voting rights?
sMINTs can be locked in a contract in return for veMINTs. The ve stands for voting-escrow, which means the locked sMINTs are locked into the contract for a predtermined amount of time. In return, the veMINTs gain voting rights in the DAO and bond fee sharing for the holder. Note that veMINTs are in addition to sMINTs, not a replacement for them, but they will decay over time. For example, if you stake 1 sMINT for six months at a lock rate of 25%, you will get 0.25 veMINTs which will linearly decay to 0 veMINTs over the six month lock period. At the end, your sMINT would unlock. At any time during the lock period, however, you could re-lock, gaining back maximum veMINTs.

```1 sMINT locked for 2.0 years = 1.00 veMINT
1 sMINT locked for 1.5 years = 0.75 veMINT
1 sMINT locked for 1.0 years = 0.50 veMINT
1 sMINT locked for 0.5 years = 0.25 veMINT
```

Quick Notes
- veMINT can be used in governance voting
- veMINT receives bonding fees
- veMINT is non-transferable
- veMINT decays over time and has no instrinsic value
- veMINT is locked sMINT

## Auction NFTs
Every day, an NFT is auctioned by the DAO. These are candy themed NFTs, not NFTs from the CryptoHoots ecosystem. The winning bidder joins all other NFT auction winners in splitting 25% of all bonding fees. The auction NFT winner also gets a premium on voting rights. An auction NFT win entitles the winner to 10 million veMINTs apart from any other veMINTs the owner possesses. Early auction NFT winners get an early bird MINT bonus. ETH paid for auction NFTs goes into the treasury, but does not trigger MINT creation.

*Questions: Does auction NFT hold special voting privileges. Particularly in regards to ShuffleMint projects? How many MINTs do early auction NFT holders get? Are those distributed as sMINT or veMINT? Do auction NFT veMINT decay?*

## Partner Projects
Partner Projects are other NFT or related communities that require ShuffleMint Studio assistance or other DAO resources for their projects. Partner Projects will pay for the level of software/personnel support they need via special "Project Bonds". These bonds will be paid for in ETH that goes to the treasury. In return, the project will get a percentage of their ETH value back in sMINT. The sMINT will be pooled and rewards will be emitted over time. The project can also take a lump sum MINT allotment. Note that projects that don't need ShuffleMint Studio or other assistance can still simply purchase MINTs from the LP or bonding to use as their own utility token.

*Notes: That section will likely change a bit*

## What are Bonds?
Bonds are IOUs that users may purchase with ETH or ETH-MINT LP tokens for the promise of MINTs at a future date. Bonds are also how partner projects will buy into the DAO. Bonds are sold at a discount from the nominal ETH-MINT price depending on a formula taking into account the DAOs debt ratio and the policy team's need to alter the buy or sell pressure of MINTs. Bonds will linearly vest over a five day period, by the end of which all MINTs will be available to the buyer. Only one bond can be held at a time. When ETH from a bond is received by the treasury, a number of MINTs equal to the value of the deposited ETH is minted along with 25% extra which is distributed as rebase rewards to stakers. The bonding fee MINTs are distributed as follows: 25% to the core team, 25% to auction NFT holders, 25% to the DAO treasury, and 25% as sMINT to be shared between CryptoHoots NFT stakers.

*Questions: Can only one bond be held?*

## CryptoHoot NFTs in the DAO
CryptoHoots Parliament, Alpha, Baby and CyberPunk NFTs will be able to be staked in ShuffleDAO. Staking Hoots allows for sharing in bonding fees. It is possible that staking a Hoot will get you an L2 NFT as escrow for your staked hoots and that it might mirror the hoot in some form by virtue of the on-chain DNA. The 25% of bonding fees the staked Hoots share will be distributed as follows:

- CryptoHoots and Alphas - 10%
- Babies - 2%
- CyberPunk - 3%

## Who are the DAO members and voters?
Anyone holding MINTs of any flavor, an auction NFT, a bond or is a team member is a ShuffleDAO member.
- sMINT and CryptoHoot stakers - entitled to bond fee rebasing rewards and possibly tier one (treasury governance) votes??
- veMINT/auction NFT holders - entitled to bond fee rebasing rewards and tier two (ShuffleMint + treasury governance) votes??
- Core Team/pMINT?/advisors - all tier voting rights, 25% bonding fees, 20% treasury revenue

*Questions: Would this mean yield and LP fees pay out to the team? Or when auction/Partner ETH comes in, 20% goes to team and 80% to treasury*

## Where members get monetary benefits
DAO Treasury - 80% of auction and partner project revenue, 25% of bond fees
Core team/advisors - 20% of auction and partner project revenue, 25% of bond fees
MINT stakers (sMINT), CryptoHoot stakers, veMINT holders - 25% of bond fees
Auction NFT Holders - 25% of bond fees
Partner Projects - discounted MINT + potentially emitted rewards if they pool rather than withdraw MINT allocation
Bonders - discounted MINT
MINT holders (includes ecosystem partners) - speculation

*Question: Does all LP and yield go to the treasury*

## Voting Tiers
*Undecided: There might be two voting tiers. One for ShuffleMint governance, for example, non-binding or binding suggestions for projects and general ShuffleMint management and another for DAO Treasury governance.*

## What is Protocol Owned Liquidity?
Once liquidity pools are started, for example on Sushi, the DAO will sell bonds to buy the ETH-MINT LP tokens. Bonds will give a discount making it worthwhile to sell the token. The bond purchaser sells the token for a number of MINTs. When most of the LP tokens are bought by the DAO, it will own its liquidity and collect the fees on trades as another form of revenue.

## What IV (Initial Value)?
Initial Value is the value of MINT per ETH that we start with. We seed the liquidity pool and offer initial purchases with this value in mind. ShuffleDAO will begin with an IV of 4x Intrinsic Value. Intrinsic value is the minimum backing of MINT per ETH. ShuffleDAO intrinsic value is one million MINTs per ETH and at 4xIV, initial value is 250,000 MINTs per ETH. When ETH value is around $4000 USD, that gives a rough estimate of one MINT per US cent.

## How does the core team get paid?
Core team, advisors, contributors and project partners get paid in private MINTs, pMINTs. These are MINTs that vest to regular MINTs over time and/or under conditions of DAO treasury fund goals.

