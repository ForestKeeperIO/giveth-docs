---
id: givbacks
title: GIVbacks
slug: giveconomy/givbacks
---
import useBaseUrl from '@docusaurus/useBaseUrl';

GIVbacks is a revolutionary concept that rewards donors to verified projects with GIV tokens. When you give to verified projects during a GIVbacks round, you become eligible to receive GIV back after the round ends. You can see live information --- including round schedule & your claimable GIV --- on the [GIVbacks page](https://giv.giveth.io/givbacks).

## GIVbacks Rounds
GIVbacks rounds last two weeks. For each round, there is 1 million GIV available to be *given back* to the donors to verified projects.


![image](https://user-images.githubusercontent.com/75490971/147268602-1940c644-5171-4385-8172-fa503f2ab163.png)


## Project Verification
Getting your project verified builds a relationship of trust with your donors by demonstrating your project's legitimacy and showing that the funds are being used to create positive change.

To learn more about Project Verification check out our [documentation](https://docs.giveth.io/dapps/makeTraceableProject) or [apply for verification with this typeform](https://giveth.typeform.com/verification).

Projects must submit their application forms one week before the start of a round in order to qualify for that round. Once approved, a project will be qualified to participate in all subsequent GIVbacks rounds. When a project becomes verified, its status is updated on Giveth and it is given a “Verified” badge on the Homepage and on the Project's Page.

<img alt='givbacks schedule' src={useBaseUrl('/img/content/giveconomy/GIVBacks_Rounds2.png')} />

Givers who donate to verified projects within an active round are eligible to receive GIVbacks. Note that Project addresses will not receive GIV for donations made to their own project or other verified projects.

## Getting GIVbacks

During each round, all donations to verified projects on the DApp are tracked and this data is used to calculate the amount of GIVbacks received by each Giver for that period.

Givers are able to claim their GIV after the round ends via the [GIVbacks page](https://giv.giveth.io/givbacks). A portion of the GIV will be liquid immediately and the rest will increase the flowrate of their [GIVstream](https://giv.giveth.io/givstream). To learn more about the GIVstream and how it works, check out our [documentation](https://docs.giveth.io/giveconomy/givstream/). For the purposes of this documentation, we will refer to the sum of the liquid amount and the amount allocated to the GIVstream from GIVbacks as `cumulative GIVbacks`.

Note that, even with the GIVbacks program, a donation on Giveth is still a donation. The maximum value of the donor's `cumulative GIVbacks` is equal to 75% of the value of their donation, at the time of donation. If the value of the `1 million GIV` allocated to the GIVbacks round is more than 75% of the total value of all donations (at the time of each donation) during the round duration, then all eligible donors will get their respective maximum cumulative GIVbacks.

If the total value of donations (at the time each donation) exceeds 75% of the `1 million GIV` allocated to the round, the `cumulative GIVbacks` for each donor is proportionately less and calculated as follows:


$$
n = N \frac{v}{V}
$$

where:

  - n = Total cumulative amount of GIV tokens earned by the donor for a particular donation  
  - N = Total number of GIV tokens allocated for distribution in the round (1 million GIV)  
  - v  = Value (in USD) of the donation at the time of donation  
  - V  = Total value (in USD) of all donations to eligible projects during the round  

GIV tokens earned through the GIVbacks program can be used throughout the GIVeconomy: for governance within the [GIVgarden](https://giv.giveth.io/givgarden), to support the token by providing liquidity (and earning rewards!) in the [GIVfarm](https://giv.giveth.io/givfarm), or for donating to projects on [Giveth](https://giveth.io).

## **Tokens Eligible for GIVbacks**
A donor can donate any ERC-20 token to projects on Giveth.io on xDai or Mainnet. However, only donations to Verified Projects in **certain tokens** are eligible for GIVbacks. This restriction ensures that we are able to get accurate price data for donations (a requirement for fair distribution of GIVbacks), and prevents bad actors from gaming the GIVbacks program. To see the full list of eligible tokens, visit [this forum post](https://forum.giveth.io/t/givbacks-token-list/253)


## Harvesting GIVbacks
GIVbacks are available to be harvested after the round ends and GIV is distributed to eligible donor addresses. This GIV can be harvested [here](https://giv.giveth.io/givbacks). Please note that when you harvest GIV rewards from any part of the GIVeconomy, our token distro contract sends you all liquid GIV allocated to your address on that network. For example, when you harvest GIV rewards earned from staking LP tokens in the GIVfarm on xDai, you also harvest rewards allocated to you from GIVbacks (if any) and the liquid amount from your GIVstream. This is broken down in the harvest popup that you encounter upon claim:

![image](https://user-images.githubusercontent.com/75490971/147270876-3fe6bc26-8edd-46b9-b934-c8465c53784f.png)

## Disqualifying Factors for GIVbacks Program

Once a GIVbacks round ends, there is a period of time granted to our team to review flagged projects for the following disqualifying factors before GIV is distributed to donors. A project could have their Verified status revoked if any disqualifying factors are found. Donors to projects who are found with any of the following activity may also be denied GIVbacks for that round.

1. **Giving/offering goods or services to donors in exchange for their donation.** A project owner cannot offer goods such as a sponsorship for a conference, girl scout cookie purchases or tickets for a dinner, even if the proceeds go to charity. Project owners cannot provide services like acting as a crypto exchange for their donors. They can explain how to use an exchange, but they cannot convert the money for their donors.
2. **Circulating donations raised by other means.** Only “first touch” donations count for GIVbacks. If a project receives funding from a donor and is found to be circulating these donations within the Giveth platform to receive GIVbacks, they will be disqualified. For example, a project should not be sending fiat donations received elsewhere back to their donors and asking them to donate on Giveth with crypto.
3. **The funds are not being used for what is expressed in the project page or submitted verification application.** Verified projects are responsible for keeping their projects up-to-date with information on how the funds are being used. If the project states explicitly that they are, for example, using the funds to develop education programs but are found to be using the funds to employ developers, they may be disqualified from the GIVbacks program.
4. **Unscrupulous or fraudulent activity.** This can be the use of violence, breaking laws, or other behaviour that does not uphold the [values of the Giveth community](/whatisgiveth/). Projects found to be violating our [Terms and Conditions](https://giveth.io/tos) will not only lose their verification status, but also will be cancelled.

The Giveth Project Verification team is responsible for monitoring GIVbacks activity and the Project Verification system, and will ultimately use their discretion to determine whether a project’s actions are unscrupulous and/or disqualifying.

## Graduated Sanctions

Verified projects and donations that are flagged for any of the disqualifying factors above will be analysed and discerned according to the graduated sanctions outlined here.

### Projects

The activity and donation history of Verified Projects will be periodically reviewed. If disqualifying factors are found, the following actions will be taken:

- A project that has been flagged and deemed to be disqualified for the **first time** will be notified and their donors will not receive GIVbacks for that round and the next. They will not, however, lose their ‘Verified’ status immediately and will have the opportunity to make any changes necessary to keep it.
- A project that has been flagged and deemed to be disqualified for the **second time** will be notified that they have been demoted and the donors for that round and all future rounds will not be receiving GIVbacks. Once a project has received a second flag, it will lose it’s ‘Verified’ badge.

### Donors

A donor whose GIVbacks were revoked because they donated to a disqualified project will receive an email with the complaint and evidence that was submitted. Donations cannot be refunded and GIVbacks cannot be “unrevoked” if the project was disqualified from the round. Donations are donations and they go directly to the project. The GIVbacks program was created to additionally empower our donors with GIV & therefore governance rights, but you should not make a donation purely out of the expectation of receiving GIV. We appreciate your understanding.

## **Tokens Eligible for GIVbacks**
Only certain tokens donated are eligible for GIVbacks - to see a full list, visit [this forum post](https://forum.giveth.io/t/givbacks-token-list/253)

---
The GIVbacks program is our way of giving back to those who give. It’s our exit to the community - empowering real donors with governance power over the future of Giveth and hence, the Future of Giving. To get GIVbacks, [start donating to verified projects today](https://giveth.io/projects)!
