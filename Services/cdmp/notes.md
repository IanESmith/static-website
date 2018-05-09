## Common Data Matching Platform

### Summary as of 8 May 2018
We have provided a secure platform for Advanced Border Control flight data. Next we're going to deliver an ingestion pipeline that transforms data to the POLE standard, create some query and matching functionality, allow editing of records and add more security controls that will allow HMPO to be onboarded.

### What is blocking us
- we need to be assured that TDCS have their resources (on both CDP and ABC) working to an agreed and coherent test approach. So, we're asking them to ensure this is visible, understood and agreed by CDP and its tenants


## Graph Spike and 'build the whole thing as a thin slice of working functionality'

We are about to complete [spiking](https://www.leadingagile.com/2016/09/whats-a-spike-who-should-enter-it-how-to-word-it/) and developing a full end-to-end working slice of functionality that allows the ingestion, persistence in graph, and querying of ABC’s API/PNR messages. This means we nearly have:
 - an ingestion pipeline that maps ABC data to POLE, including a basic matching approach to reduce duplicates in the POLE data (allowing ABC to test carrier messages and examine POLE output). 
- a graph ingest for POLE data that takes the transformed output and stores it in a graph model (allowing our tenants to review how data is stored and specify how they want to access it so CDP can index their data appropriately).
- provided an API to the POLE data at 2 levels, a simple REST API to search for and retrieve POLE entities, and a more complex API provided by the underlying graph engine.
- a security implementation that allows tenant authentication in business applications to be propagated to CDP through JWT tokens.
- a multi-tenant model that allows multiple tenant environments to be deployed on a single CDP environment simplifying tenant requests for additional environments.
 
With this in place, the basics of our July Release are well advanced. We now need to iterate this to complete any remaining functionality, and:
- finalise the build to reflect changes in the baselined ABC data model and CDP API;
- build environments that can be made available to tenants;
- carry out CDP integration, functional and performance testing.

However, as with all spikes, we may also uncover some problems. We'll publish these, if any, once the spike completes this week

## July Release

### Just done
- completed rehearsal, testing and assurance of all protective monitoring processes for Release 1
- continued the spike
- had a few more rehearsals of our live support process
- had our tech ambassador talk to a few more Home Office folk around their needs, and possible benefits, for a common data platform
- shared the roadmap for 2018 showing all our deliverables for ABC, HMPO and CDP along with confidence levels and status with the ABC and CDP SROs (too many abbreviations?)

### About to do/doing
- ensure the KPIs fully understood and visible
- complete the spike on what is the best solution for querying the data
- have TDCS complete and publish their test strategy (covering functional, security, performance, infrastructure) and what the split/share/overlap between CDP and its partners is
- migrate the 2018 roadmap from spreadsheet to jira and start publishing progress metrics
- switching off environments when not in use, to save money (without impacting the teams who need to use)

### Things to be aware off
   - metrics will be available w the next sprint notes
