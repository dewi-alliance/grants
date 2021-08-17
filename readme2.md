# **GRANTS**

## Deadline Here: date
## Notifications Sent: dates

The Decentralized Wireless Alliance (DeWi) oversees the grant program.  We provide individuals and project teams with access to funding, technical support, and community resources. Grant proposals are reviewed and approved by the DeWi team with input from other leaders and stewards of the Helium ecosystem. 

We believe the next generation of wireless innovation will be driven by people working with p2p technologies, this is where you come in. We are actively looking for teams to build the tools and applications that make the decentralized wireless future possible. Our funding is non-diluted, so we never take any ownership over the IP or team. Please note, we prioritize open source GPL3 or similarly licensed when possible, and we typically fund up to a maximum of $100k USD. We are happy to cover things like prototyping costs, but don&#39;t typically pay for travel, rentals, yachts or freelancers&#39; salary. Ideally the scope of the work fits within a 12 month period.


 ## Grant Program Criteria

Here is the primary criteria for DeWi grant applicants:

- Implements or utilizes HNT
- Max $100,000 USD
- Timeframe: up to 12 months to Proof of Concept (poc)
- Preferably Open source license (GPL, MIT, CC)
- (recommended) A Docker container to deliver the poc, as it removes any installation specific dependencies
- Pass standard KYC requirements

 ## How to Apply
 
The application process itself is fairly easy, although most applicants find creating a good roadmap to be the hardest part (see below for an example). The best way to get your proposal accepted is to write a great roadmap. If you have a great idea for building in our ecosystem, apply!

We recommend that the scope of the work (SoW) can fit within a 12 month period and that teams structure the roadmap as 1 month = 1 milestone.

ProTip: Milestones should relate to pay outs.

For a roadmap, we recommend the following:

- describe the functionality we should expect, plus how we can check that such functionality
- how your project is related to DeWi/HNT
- tie function to milestones

Example:

Milestone 1, September 15 2021, $2000

implementation of X feature or functionality, explain

Milestone 2, October 30 2021, $1000

explain additional features and implementation

Milestone 3, November 20, 2021 $1500

final feature implementation and poc/mvp demo

----------------------
**Template for Submission**

_Please create an issue in the grant repo and use this submission template for painless application development_

**Project:**

_Project Name_

**Elevator Pitch: **

_Please provide the following: A brief description of the project. An indication of how you will integrate this project into HNT/DeWi. An indication of why your team is interested in creating this project in 2 sentences or a tweet_

**Total fiat/hnt ask:**

**Legal Name and Address:**

_Please provide your legal name and registration number, and address to streamline the contract process and KYC. A lack of this basic information will delay the contract and payments dramatically_

**Team or Project website: (url)**

**Team or projects social: (optional) (text area)**

**Code Repos of team or key applicants: (text area)**

https://github.com/\&lt;organisation\&gt;

[https://github.com/](https://github.com/)\&lt;team-member\&gt;

[https://github.com/](https://github.com/)\&lt;team-member1\&gt;

https://github.com/\&lt;team-member2\&gt;

**Project Details:**

We expect a clearly articulated final deliverable for the project, i.e. &#39;MVP&#39;.

If the project utilizes legacy or others code, please specify this and link to applicable repos.

Where relevant please include mockups/designs of any UI/hardware components, API specifications of the core functionality.

In addition, it is helpful to include an overview of the technology stack to be used including any required dependencies. Documentation of core components, protocols, architecture etc. to be deployed within or as the PoC/MVP is even better.

**Total Estimated Duration/Hours for Projects Development:**

This should be developer or core team members only and does not account for things like marketing, legal, or outreach.

**Roadmap:**

This section should break out the development roadmap into a number of milestones.

Since the milestones will appear in the grant contract, it helps to describe the expected functionality plus how we can validate functionality.

Whenever milestones are delivered, we refer to the contract to ensure that everything has been delivered. The level of detail must be enough to later verify that the project meets the specification.

_MS/Roadmap EXAMPLE:_

| Milestone + Date | Deliverable | Summary | Cost |
| --- | --- | --- | --- |
| MS1, Date | Figma UI/UX | A figma ui/ux full tech stack defined | 5,000 USD |
| MS2, Date | On-chain functionality | Core features implemented on-chain and deployed to HNT testnet | 2500 USD |
| MS3, Date | MVP | -Docker delivered to the DeWi foundation for mainnet testing. - repo is public - A Medium article and tutorial written on how to implement the new add-on which is published and linked in discord and forums | 2750 USD |


-----------------------

**Best Practices:**

-Provide a test suite, comprising unit and integration test, along with a guide on how to set up and run.

- Provide tutorials for the community to onboard or implement your project

- Provide Dockerfiles for the delivery of your projects MVP/PoC

- Indicate milestone duration as well as number of full-time employees working if it varies from milestone to milestone

-----------------------


Here are some previous development proposals:

| Project                                             | Notes                                        
|-----------------------------------------------------|----------------------------------------------
| HNT <> ETH trust minimized bridge                   | Convert HNT into an ERC20 token for use within the DeFi ecosystem    
| Ongoing improvements for DeWi ETL                   | More dashboards and data analysis tools. Examples: how much data flowing through the network, how frequently, how many hotspots have transmitted data, geographic distribution of data transmission, transaction activity in DC and HNT burnt.       
| Rosetta Implementation                              | Add support for Helium to Rosetta. This will speed up integrations with exchanges and wallets. [Learn More](https://www.rosetta-api.org/). [Coinbase Implementation docs](https://github.com/coinbase/rosetta-specifications).
| HNT browser wallet                                  | A user-friendly browser-based wallet. Priority for a Chrome browser extension. Also looking to add support to Ledger hardware wallet.
| HNT mobile wallets                                 | Add support for HNT on 3rd party mobile wallets, both iOS and Android
| Manufacturer dashboard                              | Show units sold, online/deployed, HNT burnt                         
| Documentation translation                           | Make docs.helium.com available in other languages (Mandarin, Spanish, Japanese, Korean)                   
| Security and/privacy overview                       | Create educational content to help hosts understand how a hotspot will interact with their home network. [Example](https://m.media-amazon.com/images/G/01/sidewalk/final_privacy_security_whitepaper.pdf)
| Anti-gaming research                                | In-depth analysis of hotspots and challenge behavior for anomoly detection; build trust scores; more sophisticated data crowdsourcing than current spreadsheet; documentation of current cheating techniques; alerts when suspicious networks pop up. 
| Support Mapping Improvements                        | Source additional mapping devices, create custom firmware and supporting documentation for easier deployment. 
