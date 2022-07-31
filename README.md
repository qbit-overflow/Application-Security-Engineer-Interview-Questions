# Application-Security-Engineer-Interview-Questions
Interview questions I have encounterd for AppSec Engineers

#Scanning
## A developer thinks a SQLi alert is a false positive because the scan took an adnormal amount of time. How would you go about trouble shooting this false postive.

Reach out to devops and verify that there were no netowrking abnoralities, or issues within the CICD enviorment. 
* Check for ammount of resources reccomended for the scanner, compare them with previous scans on the same project
* Check networking & database logs
* Check application logs
* Check for configuration changes
* Manually test for SQLi

## There are information silos regarding security between the dev teams and security teams. Devs are the ones that need to implement remedations and know what to do with the results. AppSec teams have a better under standing of how to use them, but dev teams need to know how to use them as well. What teams should be responsible for mainting tooling and why? How would you go about implementing the change?

It's critical to take developer empathy seriously but there is trade off in how much control is given to dev teams. AppSec should off load canfiguration and maintence of tooling as much as possible.

Its also important that devs understand how the tooling that impacts their SDLC. Not all devs are interested in security tooling either, so

## Find all the vulnerabilties in https://github.com/jerryhoff/WebGoat.NET, explain why you think they are important.

## At what point do you think its important for security teams to get involved with development?
