# (WIP) InSpec CIS Apache Tomcat v7 Benchmark

You can use this profile to evalute your Tomcat-7 instance to the CIS Benchmark.

#### NOTE: Tomcat Resources

Our current implamentation in the controls use the InSpec `xml` resource which is a bit complicated but works fine. 

We are working on moving to a custom set of `tomcat_*` resources for much clearner and more direct InSpec controls. 

***the custom `tomcat_*` resource is in very early alpha not yet complete and is not complete***

The controls **still use** the `xml` resource and function correctly but **help / interest welcome** on completing the `tomcat_*` resources.

### NOTICE  

© 2018 The MITRE Corporation.  

Approved for Public Release; Distribution Unlimited. Case Number 18-3678.  

### NOTICE  

This software was produced for the U. S. Government under Contract Number HHSM-500-2012-00008I, and is subject to Federal Acquisition Regulation Clause 52.227-14, Rights in Data-General.  

No other use other than that granted to the U. S. Government, or to those acting on behalf of the U. S. Government under that Clause is authorized without the express written permission of The MITRE Corporation.  

For further information, please contact The MITRE Corporation, Contracts Management Office, 7515 Colshire Drive, McLean, VA  22102-7539, (703) 983-6000.  
