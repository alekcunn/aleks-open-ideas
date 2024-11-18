## [further discussion in issues](https://github.com/alekcunn/aleks-open-ideas/issues/1)


# Intro
I find it troubling how our major infrastructure can be attacked and no progress has been made, government or corporate, to remediate (Colonia Pipeline 2021)
I have come up with a proposal that may help us better protect the american people on the internet without sacrificing our right to privacy.

# Description
There are 3 parts to this proposal
1. The user has a local data center that holds the users client-side encrypted internet cache. This needs to be a voluntary service where the user is able to pick the service provider
There also needs to be an audit process. If a user requests their data be deleted, they need to be able to prove it. My inital idea was to use a MD5 hash where a portion of the file is omitted from 
being erased, and hash whats left. This could be faked though. Someone may come along with an idea

2. There needs to be a way to share one time ticket style PPI. For example how you are able to charge a credit card a single time through paypal without knowing the card details.
Requiring government approval, I believe the best way would be to use a signed cryptographic token that can be traced back to the user. The post office would be able to enter/scan the ID and
route the parcel through the system to its destination.

3. I believe the best way for the data centers to be safe would be to use micro-containers. The micro-containers would have software to interact with web pages, and to protect the user at their
computer from cyber attacks, via firewall. Essentially this is a proxy.
