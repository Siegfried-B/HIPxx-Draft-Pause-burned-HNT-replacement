# HIP Delay Replacement of Burned HNT – Draft of a potential component

## Detailed Explanation
The Helium Network of Networks (“Helium”) coordinates the deployment and operation of wireless radio devices to build and operate decentralized wireless networks. The Helium Network Token (HNT) is a key element of the coordination mechanism of Helium.</br>
It coordinates </br>
</br>
(a) The early build-out and the continuing growth of networks
- By motivating people to build networks up to a minimum size needed to make them usable for potential users.
- By indirectly motivating hardware manufacturers to scale up device production and thus harnessing economies of scale leading to cost reduction. </br>
</br>
(b) Stable operation of networks, once they are fully built-out.</br>
</br>
- By motivating people to maintain their deployments and replace hardware at the end of its lifecycle. </br>
</br>
To fulfill this coordination function, the Helium community cumulatively decided that HNT issuance and supply should have the following properties:</br>
 1. Maximum supply must be limited</br>
 2. In the build-out and growth phase, periodic token emissions must decrease over time</br>
 3. Token supply should grow up to an inflection point and then be deflationary</br>
 4. Periodic emissions of HNT must always be divisible enough to not break the system from a technical point of view. (If the total periodic emissions cannot be divided in parts small enough to adequately reflect the adequate reward share of rewardable entities.) </br>
 5. Periodic token emissions should not decrease below a specified threshold to balance interests of HNT holders and rewardable entities.</br>
These considerations still necessitate decisions on specifics and possibly finetuning of the specifics over time to account for learnings.

In the past, the Helium Community has decided on the following specifics:</br>
(A)</br>	A bi-annual halvings schedule: Amounts of periodically emitted HNT will be halved every two years.</br> This ensures (1.) a limited maximum supply of HNT and (2.) decreasing periodic token emissions over time. In conjunction with (B) below, it also ensures that (3.) HNT supply will grow up to an inflection point and then be deflationary.:</br> 
(B)</br>	A burn mechanism: Usage of the networks requires payment with Data Credits (“DCs”), which can only be acquired by burning HNT. </br>This ensures in conjunction with (A) above that the HNT token supply is deflationary.:</br>
(C)</br> A mechanism to replace burned HNT up to a certain maximum amount per reward emission period. This replacement HNT is added to the periodic token emissions as per the emissions schedule (laid out in HIP-20 and HIP-77).</br> The replacement ensures that (4.) periodic token emissions of HNT will always be divisible enough to not break the system from a technical point of view and (5.) Periodic token emissions will not decrease below a specified threshold. In conjunction with (A) and (B), the cap of the replacement ensures that the token supply will be deflationary as long as the minimum threshold is not reached.  

With this HIP, we want to fine-tune the specifics to learnings made since they were decided:

As of today, the networks are still in their early phases – this applies to their build-out as well as to their usage. 
This has two effects::</br>
(i) </br>
We are still decades away from there being any danger of (see (4)) periodic HNT emissions being too small as to not be divisible enough for HNT to fulfill its coordination function.:</br>
(ii) </br>
HNT burns for DC are still in a range that they have no significant deflationary effect on HNT supply or even HNT supply growth.

In our view, this means that for many years, there is no need to replace HNT that is burned for DCs.
We are also of the view that the coordination function of HNT – especially via the pathway of motivating current and potential community members to maintain their current radio deployments and to add additionally deployments – would be better served, if the growth of the HNT supply would be slower or already be deflationary.
We therefore propose to pause the mechanism of replacing HNT that has been burned for DCs until we have significantly more usage of our networks and are significantly closer to periodic HNT emissions being not divisible enough for HNT to fulfill its coordination functions.

