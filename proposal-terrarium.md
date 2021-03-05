# Grant Proposal: Terrarium

**Name of Project:** `TBD (Project Codename Terrarium)`

**Proposer:** [`@anthonyra`](https://github.com/anthonyra)

**Do you agree to open source all work you do on behalf of this grant?:** 
No, the project will include both free and paid-for features that have been under development since the HIP15/17 proposals. Due to the amount of time, effort and financial resources already devoted to building out some of these features we cannot agree to open source the work.

# Project Description

**Codename 'Terrarium'** - Terrarium is a revolutionary network planning and optimization web app that will assist hobbyist and patrons alike with determining the optimal locations for new hotspot deployments. The app will include an interactive map that enables the user to view currently active hotspots, H3 hex borders and densities, mining rewards, and the ability to add & organize custom markers to the map which represent potential locations for new hotspots. Additionally, a 3D terrain version of the network map will be available to help users understand how elevation changes and buildings might affect communication between devices. To supplement these maps a dashboard will be created to display aggregated details about the user's network while also drawing their attention to critical issues such as certain hotspots going offline repeatedly.

**Problem to Solve** - With the recent changes implemented in PoCv10, HIP15 and HIP17, the ability to understand where to place a hotspot that will consistently produce reliable network coverage has become increasingly difficult. Using Terrarium, patrons can visualize how changes like this affect the performance of their network, identify weaknesses and form a project plan within the tool to successfully adapt to these changes. The team ,at Mycelium Networks LLC, has already benefitted from using an MVP of Terrarium to form an optimization plan for their network in the Northwest Arkansas region. Without Terrarium this type of work would take significantly longer and require a greater degree of trial & error.


# Deliverables
The final deliverable will be a web application that hobbyists or patrons can use to help build out their networks in the most efficient way possible. The primary aspects of this app will be a network planning map tool, a 3D terrain map and a dashboard to monitor network performance at a high-level.


### *Features*
- Hobbyists/Patrons will be able to view their network hotspots as well as surrounding networks on a feature-rich map.
- They can then add custom markers to this map which will represent candidates for new host sites.
- The 'Project' feature allows for these sites to be grouped by a common name, region, state, or other criteria for more efficient network planning.
- Owned networks will be highlighted to differentiate them from surrounding, out-of-network hotspots.
- 3D terrain map layer that allows users to quickly check the topography of an area for any line-of-sight obstacles between hotspots.
- User can upload a .CSV file containing a list of candidate host addresses (or lat/long) to view on the map.
- User can record additional information about a hotspot setup like the antenna height, dBi rating, and where it's facing. ISP and modem/router information. Upload an image to help with future troubleshooting.
- The account dashboard will provide a high-level overview of the patron's networks and their performance. This will include trend charts and metrics such as rewards over time, miner ROI, average mining performance, and other metrics that are still in planning phase.

# Timeline/Roadmap

## **Milestone 1**
**Duration**: 5 weeks - est. date of completion *16-April-2021*  
**Funding**: 5000 HNT  
**Workers**: **@anthonyra**(Developer), **@michgaurd**(Developer), **@TWilson**(Technical Project Mgmt.), **@TFrost**(Supervisor)  

<ins>Deliverables:</ins>
- View owned hotspots from multiple accounts on a map
- Add custom markers to the map to visualize where new hotspots could be placed
- View h3 hexes and hex-density rewards scaling factors for hotspots
- Ability to see unowned hotspots (outside user's network) including hex densities
- Organize groups of custom markers into sites/projects to help manage future deployments  
  

## **Milestone 2**
**Duration**: 5 weeks - est. date of completion *14-May-2021*  
**Funding**: 5000 HNT  
**Workers**: **@anthonyra**(Developer), **@michgaurd**(Developer), **@TWilson**(Technical Project Mgmt.), **@TFrost**(Supervisor)  

<ins>Deliverables:</ins>  
- Add 3D terrain layer to identify line-of-sight obstacles
- Ability to import addresses of host candidates and view on the network maps
- Enhanced hotspot details such as antenna height, dBi rating, ISP info and images of setup
- Highlight owned networks to discern from other patrons' networks  

## **Milestone 3**
**Duration**: 4 weeks - est. date of completion *11-June-2021*  
**Funding**: 4000 HNT  
**Workers**: **@anthonyra**(Developer), **@michgaurd**(Developer), **@TWilson**(Technical Project Mgmt.), **@TFrost**(Supervisor)  

<ins>Deliverables:</ins>  
- Account dashboard to monitor network health at a glance
- View the trend of mining rewards performance over time, miner ROI, wallet balances and HNT stats
- Navigation interface to easily switch between dashboard and maps  
  
## Maintenance / Future

We intend to remain responsible for all maintenance and operational requirements associated with the server, ETL API, hosting and the application itself.

In the future we plan to add enhanced site & project organization, additional data points about the equipment and surrounding environment, and extensive UI improvements.  

# Budget

Total: 14,000 HNT  

# Team

## Members

- [`@anthonyra`](https://github.com/anthonyra)  
    Was a qualified Engineering Laboratory Technician on Nuclear Power Plants ran by the U.S. Navy from 2011 - 2020. Self taught JavaScript, HTML, CSS3, React.js, Node.js, and Erlang. Been apart of the Helium Network since 2019 - Present. Currently working as a Production Trainer (Radiological) for Newport News Shipbuilding.

- [`@michgaurd`](https://github.com/michguard)  
    Joined the Army National Guard my senoir year of high school as a Special Electronics and Device Repairer, served 6 years including one deployment. Worked severel different jobs as a field technician with tthe most recent being a Customer Engineer II for NCR providing hands-on/hardware support for ATM network systems. Self taught JavaScript, HTML, CSS3, React.js.

- [`@TWilson`](https://www.linkedin.com/in/tylerwilson2012/)  
    Served as Technical Project Manager at AT&T while working on several Mobility (3G & LTE) applications from 2012-2014, and currently working as a Network Design/Planning Engineer for AT&T.

- [`@TFrost`](https://github.com/tfrost)  
    Has managed and coordinated multiple teams across multiple business functions in order to meet deadlines: Engineering, Web Development, App Development, Product, Marketing, PR, Sales, and Business Development.