*** 
**Notice:** The Helium grant program is evolving to better support grantees and innovation on the People's Network. <br>
Past proposals submitted through GitHub will be viewable, but all new proposals will now be submitted through a simplified form. Take a look at this [Notion doc](https://heliumfoundation.notion.site/The-Helium-Grant-Program-18a0484cf8a1494bae9eb3497b77a3cf) for more details about the current Helium grant program submission process.
***

# **GRANTS**

## Deadline and Notifications: Rolling

The Helium Foundation oversees the grant program.  We provide individuals and project teams with access to funding, technical support, and community resources. Grant proposals are reviewed and approved by the Helium Foundation team and Grant Committee. 

We believe the next generation of wireless innovation will be driven by people working with p2p technologies, this is where you come in. We are actively looking for teams to build the tools and applications that make the decentralized wireless future possible. Our funding is non-dilutive, so we never take any ownership over the IP or team. Please note, we prioritize open source GPL3 or similarly licensed when possible, and we typically fund up to a maximum of $100k USD. Grants are priced in USD, however grantees receive disbursements in HNT that is converted on a trailing average fair-market price defined within the grant agreement. We are happy to cover things like prototyping costs, but don&#39;t typically pay for travel, rentals, yachts or freelancers&#39; salary. Ideally the scope of the work fits within a 12 month period.


 ## Grant Program Criteria

Here is the primary criteria for Helium Foundation grant applicants:

- Implements or utilizes HNT, including but not limited to blockchain and radio/wireless usecases.
- Timeframe: up to 12 months to Proof of Concept (poc)
- Preferably Open source license (GPL, MIT, CC)
- A Docker container to deliver the poc, as it removes any installation specific dependencies (recommended as applicable)
- Pass standard KYC requirements

 ## How to Apply
 
The application process itself is fairly easy, although most applicants find creating a good roadmap to be the hardest part (see below for an example). The best way to get your proposal accepted is to write a great roadmap. If you have a great idea for building in our ecosystem, apply!

We recommend that the scope of the work (SoW) can fit within a 12 month period or less.

ProTip: Milestones should relate to a completed deliverable over an estimated timeframe and payments which reflect these milestones.

For a roadmap, we recommend the following:

- describe the expected functionality and how to validate it
- how your project is related to Helium Foundation / HNT
- tie function to milestones

Example:

Milestone 1, September 30 2021, $2000 upfront

*implementation of X feature or functionality, explain*

Milestone 2, October 31 2021, $5000 when completed

*explain additional features and implementation*

Milestone 3, November 20 2021, $5000 when completed

*final feature implementation and poc/mvp demo*

**Please make a copy of the [Application Template](https://github.com/dewi-alliance/grants/blob/master/template.md) and submit as an issue in this repo.**

----------------------

**Best Practices:**

- Provide a test suite, comprising unit and integration test, along with a guide on how to set up and run.
- Provide tutorials for the community to onboard or implement your project
- Provide Dockerfiles for the delivery of your projects MVP/PoC
- Indicate milestone duration as well as number of full-time employees working if it varies from milestone to milestone

-----------------------

**Areas of Interest**

*Based on feedback from the community, here are some projects in no particular order that Helium Foundation is keen to support.*

1. Implement Validator in Rust (some or all of the following: Helium's Libp2p, Blockchain Core, Miner)
2. Repeatable process to adjust the variables within HIP15 and HIP17
3. HNT bridges (Ethereum and Solana are of highest interest). Trust minimized is preferred, though any thoughtful proposal will be considered.
4. Alternate block explorer
5. Alternative onboarding / management apps for manufacturers
6. Store all blocks on Arweave
7. Store ledger extracts on Arweave
8. Data Engineering support (should include a process for getting the last 50k blocks of receipts, gateways, and rewards data as a snapshot -- and be publicly available, updated regularly)

-----------------------

Some examples from Batch 1 project proposals:

| Project                                             | Notes                                        
|-----------------------------------------------------|----------------------------------------------
| Public improvements for Helium Foundation ETL management and improvements   | More dashboards and data analysis tools. Examples: how much data flowing through the network, how frequently, how many hotspots have transmitted data, geographic distribution of data transmission, transaction activity in DC and HNT burnt.       
| Rosetta Implementation                              | Add support for Helium to Rosetta. This will speed up integrations with exchanges and wallets. [Learn More](https://www.rosetta-api.org/). [Coinbase Implementation docs](https://github.com/coinbase/rosetta-specifications).                 
| Anti-gaming research                                | In-depth analysis of hotspots and challenge behavior for anomoly detection; build trust scores; more sophisticated data crowdsourcing than current spreadsheet; documentation of current cheating techniques; alerts when suspicious networks pop up. 
|  Mapping UI Improvements                        | Source additional mapping devices, create custom firmware and supporting documentation for easier deployment. 
