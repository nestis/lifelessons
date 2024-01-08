Carbon Efficiency
Greenhouse gases are a group of gases contributing to global warming. Carbon is often used as a broad term to refer to the impact of all types of emissions and activities on global warming. CO2eq is a measurement term used to measure this impact.
The international community, in groups such as the UNFCCC, has come together to limit the impact of global warming by reducing emissions, aiming for a 'preferable' lower limit of 1.5°C. This was agreed through the UN IPCC in 2015 in the Paris Climate Agreement and is monitored at the regular COP event.
Everything we do emits carbon into the atmosphere, and our goal is to emit the least amount of carbon possible. This constitutes the first principle of green software: carbon efficiency, emitting the least amount of carbon possible per unit of work.

Energy Efficiency
Electricity is a proxy for carbon, so building an application that is energy efficient is equivalent to building an application that is carbon efficient.
Green software takes responsibility for its electricity consumption and is designed to consume as little as possible.
Quantifying the energy consumption of an application is a step in the right direction to start thinking about how an application can operate more efficiently. However, understanding your application's energy consumption is not the only story. The hardware your software is running on uses some of the electricity for operational overhead. This is called power usage efficiency (PUE) in the cloud space.
The concept of energy proportionality adds another layer of complexity since hardware becomes more efficient at turning electricity into useful operations the more it's used.
https://research.google/pubs/pub33387/
Understanding this gives green software practitioners a better insight into how their application behaves with respect to energy consumption in the real world.

Carbon Awareness
Principle => Do more when the electricity is cleaner
Carbon awareness means understanding that the energy you consume does not always have the same impact in terms of carbon intensity.
Carbon intensity varies depending on the time and place it is consumed.
The nature of fossil fuels and renewable energy sources means that consuming energy when carbon intensity is low increases the demand for renewable energy sources and increases the percentage of renewable energy in the supply.
Demand shifting means moving your energy consumption to different locations or times of days where the carbon intensity is lower.
Demand shaping means adapting your energy consumption around carbon intensity variability in order to consume more in periods of low intensity and less in periods of high intensity.

Hardware Efficiency
Use least amount of embodied carbon possible
Embodied Carbon => Amount of carbon pollution emitted during the creation and disposal of a device.
Amortization => Amortize carbon over the expected life span of a device. Suppose it took 4000kg CO2eq to build a server, and we expect it to last four years. Amortization means that we can say the server emits 1000kg CO2eq/year.
There are two main approaches to hardware efficiency:
For end-user devices, it's extending the lifespan of the hardware.
For cloud computing, it's increasing the utilization of the device.
In the cloud space, hardware efficiency most often translates to an increase in the utilization of servers. It’s better to use one server at 100% utilization than 5 servers at 20% utilization because of the cost of embodied carbon. Although emissions are the same, the embodied carbon that is used is much lower.
Cloud computing is more energy efficient then an on-premise server as it can apply demand shifting as well as demand shaping.

Measurement
SCI Software Carbon Intensity

It's not a replacement for the GHG protocol, but an additional metric. While the GHG protocol calculates the total emissions, the SCI is about calculating the rate of emissions. In automotive terms, the SCI is more like a miles per gallon measurement and the GHG protocol is more like the total carbon footprint of a car manufacturer and all their cars they produce every year.

Instead of bucketing the carbon emissions of software into scopes 1-3, it buckets them into operational emissions (carbon emissions from the running of software) and embodied emissions (carbon emissions from the physical resources required to run the software). It's also an intensity rather than a total, which is more inclusive of open-source software.
https://sci-guide.greensoftware.foundation/

The GHG protocol is a metric for measuring an organization's total carbon emissions and is used by organizations all over the world.
The GHG protocol puts carbon emissions into three scopes. Scope 3, also known as value chain emissions, refers to the emissions from organizations that supply others in a chain. In this way, one organization's scope 1 and 2 will sum up into another organization's scope 3.
Calculating software-driven emissions using the GHG protocol is possible but can be difficult for open-source software.
The SCI is a metric designed specifically to calculate software emissions and is a rate rather than a total.
The functional unit of measurement is not prescribed in the SCI and you should choose something that reflects your application.

Climate Commitments
Abatement, which means eliminating sources of CO2 emissions associated with a company's operations and value chain so that they do not enter the atmosphere
Offsets are direct investments in emission-reduction projects through the purchase of carbon credits on the voluntary carbon market (VCM). The VCM is a decentralized market where private actors voluntarily buy and sell carbon credits that represent certified removals or reductions of GHGs from the atmosphere.

To offset emissions, you need to purchase the equivalent volume of carbon credits to compensate for those emitted, where 1 carbon credit corresponds to 1 tonne of CO2 absorbed or reduced.
Compensations are actions that companies take to help society avoid or reduce emissions outside of their value chain.
Neutralizations are actions that companies take to remove carbon from the atmosphere within or beyond their value chain.
Carbon Neutral, an organization must measure its emissions, then match the total to its emissions offsets through carbon reduction projects. This can include carbon removal projects (neutralizations) and carbon avoidance projects (compensations).
Net zero means reducing emissions according to the latest climate science and balancing remaining residual emissions through carbon removals (neutralizations). Net zero, by definition, requires emissions reductions in line with a 1.5°C pathway. All businesses must do this to achieve net-zero global emissions by 2050.
To be a net-zero target, you must cover direct and indirect, i.e. supply chain emissions (scopes 1,2 and 3). 

Renewable Energy Certificate. 1 REC equals 1kWh of energy.
If you want to be 100% matched by renewable energy and are on the grid, the solution is to buy enough RECs to cover the amount of electricity you consume. For instance, if you consume 100 kWh of electricity every day, then to be 100% matched by renewables, you buy 100 RECs.
PPA is a Power Purchase Agreement, which is another way to purchase RECs. If you estimate you need 500MWh of electricity per year for a particular data center, you might sign a PPA to purchase 500MWh per year from a renewable plant. You would then get all the RECs associated with this power plant.

24/7 Hourly Matching
Matching by day means the organization consumed 18 kWh and bought 18 RECs. As a result, they netted off to zero. So they can say they are 100% matched by renewable energy daily.
However, there are only a few hours in the day where we are 100% matched by renewable energy for that hour. So for some hours, we have way more renewable energy than we need. Conversely, we have way less renewable energy than we require for most hours.
In the above example, they are 100% matched by renewable energy on an hourly basis for only 6 hrs of the day.
CFE Carbon Free Energy. The number we use to describe how successful we are at 24/7 hourly matching is the carbon-free energy percentage.
One example of a behavior change is shifting compute to a time when more renewable energy is available.

There are a number of methodologies commonly applied to help in the overall fight against climate change. These fall into the general categories of carbon elimination (also known as ‘abatement’), carbon avoidance (a.k.a. ‘compensating’), or carbon removal (a.k.a. ‘neutralizing’).
Abatement includes increasing energy efficiency to eliminate some of the emissions associated with energy generation. Abatement is the most effective way to fight climate change although complete carbon elimination is not possible.
Compensating includes the adoption of renewable energy sources, sustainable living practices, recycling, planting trees etc.
Neutralizations refer to the removal and permanent storage of atmospheric carbon to counterbalance the effect of releasing CO2 into the atmosphere. Neutralizations tend to remove the carbon from the atmosphere in the short and medium-term.
An organization can call itself Carbon Neutral when its total emissions are matched by the total of its emissions offsets through carbon reduction projects
Net zero aims to eliminate emissions and only offset the residual emissions that you cannot eliminate to reach the 1.5°C target set by the Paris Climate Agreement.
The SCI is carefully designed so that eliminating emissions, through energy efficiency, hardware efficiency and carbon awareness is the only way to reduce the score. Together with a separate neutralization strategy, it can form the basis of a net-zero strategy for an organization.
When organizations set a target of 100% renewable power, they can either be “matched by” vs. “powered by” renewables, where “powered by” means the electrons flowing into your device can only come from renewable sources. This can be achieved by purchasing RECs as part of a PPA.
24/7 hourly matching is one of the many strategies we need to employ to help accelerate the transition to a 100% renewable-powered grid


