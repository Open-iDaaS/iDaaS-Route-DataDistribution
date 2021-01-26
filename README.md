# iDAAS-Route-DataDistribution
iDAAS Route data distribution is part of the iDAAS Connect family within iDAAS. iDAAS Connect is the family of capabilities that specifically address data .
connectivity and data distribution of information. 

Before data can be distributed it MUST enter into the iDAAS platform from one one of the iDAAS Connect family that help 
organizations connect to data: HL7 (iDAAS-Connect-HL7), FHIR (iDAAS-Connect-FHIR), Third Party/Other (iDAAS-Connect-ThirdParty).

Why not implement this directly within the iDAAS Connect components that connect to data? You most certainly could; however, we 
wanted to ensure with this accelerator platform we include a very specific capability to enable the separation of inbound data and 
any routing activities. Our reason is to ensure that anything processing inbound data to a platform be able to focus on that
key need and not risk potential downtime for other related tasks.
  
## Relevant Implementation Design

As with all iDAAS ever component has a specific relevant design implementation. 
