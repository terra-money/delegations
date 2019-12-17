# Delegations 

This repository is the hub for the Terraform Labs’ delegation program. 


## Why Terraform Labs has a delegation program

Terraform Labs wants to support validators who contribute to the security of the network and the development of the ecosystem. While we expect our role to be phased out over time, we hope our early support will help to equip the Terra community with a robust validator set and a vibrant ecosystem of tools, research groups, companies and applications that sets the network up for long-term success. 


## To qualify for Terraform Labs delegations, a validator must:

- Maintain a commission rate below 20%
- Have less than 10M bonded tokens 


## Actions that will result in delegations

- Build and scale Terra applications (with traction): Building Terra applications (either independently or in conjunction with Terraform Labs) will be supported by significant delegations, grants, and other forms of assistance. 
- Build and maintain ecosystem tools: Block explorers, monitoring tools, dashboards, oracle feeders 
- Set an example of validator operation best practices: Publishing material help other validators improve their security infrastructure and understand threat models, engaging in support discussions to onboard new validators
- Lead community engagement: Running public facing communities and engaging in activities that help to onboard new participants into the ecosystem
- Get started: New validators will be delegated 100k Luna to get started and to keep the lights on 


## Actions that will result in undelegations

- Slashing: Slashing will result in {Downtime => 50%, Double sign => 100%, oracle => 30%} undelegations respectively. 
- Oracle passivity: Abstaining on all oracle votes will result in a 30% undelegation (consistent with slashing) 
- Over-dependence: Failing to source third party delegations (> 10% of total) will see delegations drop consistently until third party delegations are over 10%. 
- Good ol' passage of time: Terraform Labs will continuously reduce its number of staked tokens (currently standing at 116M) over 2 years to 50M. 


## Delegation/Undelegation process 

- Delegation changes will take place every 3 months, and will take effect on the last day of every quarter. 
- To qualify for additional delegations, validators must submit a proposal (format [here](./templates/proposal_template.md) to be reviewed by a rotating council consisting of the core team and major validators by D-14 days from the next delegation change date.
- Every quarter, Terraform labs will target to reduce its number of total staked tokens by 10M. Therefore, should `period_undelegated_tokens` - `period_new_delegated_tokens` < 10M, undelegations will occur from one of the Terraform Labs controlled Starcraft validators to make up for the difference. 

