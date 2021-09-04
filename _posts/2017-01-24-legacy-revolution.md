---
layout: post
title: Legacy Modernization Revolution (Part 1)
image: assets/dist/img/rev2.jpg
excerpt: Changes are afoot in government application development
---

Here in California, most legacy modernization state government projects follow this pattern:

1. A state team is tasked with constructing an RFP. The RFP will include all known requirements, is set as a "fixed price" contract with a price tag that can range from $200M to $1B.

2. The projects are targeted towards the large System Integrator that has the resources to
* absorb the risk of a $100M+ project and
* participate in a long and expensive proposal process. This takes 6-24 months.
* The requirements need to be created, refined, and then the approval process starts. An SPR (financial forecast) may be triggered that will require additional review time.

3. The RFP is released and can take 6-18 months to award a contract. Valid questions about imperfect requirements (OK, I've betrayed my bias now) require addendums that extend the selection process. If everything goes well, a vendor is chosen and awarded a contract. If none of the other bidders protest (which will delay the contract award) a start date is set.

OK, so we are 2-3 yrs into the process. No working software has been built.

So what's changing in legacy modernization that might improve this?

## Agile development
Small teams can be hired to build working software that both the state and vendor teams can learn from. Following an "encapsulate and retire" pattern, teams can identify small chunks of relatively self-contained functionality from a legacy system, duplicate an improved version of it on a modern platform, and migrate users off of that piece of the legacy.

(As a side note, I'm calling this pattern "encapsulate and retire". Its really the [strangler pattern](https://www.martinfowler.com/bliki/StranglerApplication.html), but when you are working with the folks who have lived with the legacy software for years, talking about strangling the system they have cared for is macabre, borderline insensitive.)

The agile process is a big help here. The normal benefits of helping analysts and developers learn more about the domain occurs via the agile "working software" feedback loop. But a secondary, more subtle benefit is that it helps legacy users and managers move along the OCM curve quickly. When they see working software, the fears of change are balanced with the opportunities to control the new direction. Adoption occurs with less difficulty.

In Part 2 (coming soon), I'll discuss the impacts of cloud, devops, and open source as new opportunities to revolutionize the legacy modernization process.

<!---
With small variation, most projects have been
  -- legacy development revolution
    	-- encapsulation and retirement
 	-- agile development
	-- cloud for infrastructure
	-- open source
	-- DevOPs

--->