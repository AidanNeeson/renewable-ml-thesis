# Introduction

In an era marked by unprecedented environmental challenges, the imperative to address the impacts of climate change has become increasingly urgent.
As our planet struggles to persist in a healthy state as a result of the tumultuous onslaught brought on by rising global temperatures, extreme
weather events, and ecological disruptions, the necessity for a pursuit of a sustainable future has never been more prevalent. In this pursuit,
renewable energy has seated itself as a pivotal solution to mitigate the environmental effects of traditional energy production. Among these alternatives,
green energy arrays, comprising of solar and wind technologies, hold immense promise. The venture to harness the true potential that these
technologies hold, however, comes at the cost of needing a nuanced understanding of certain geographic factors that influence their performance and
cost-effectiveness. This project embarks on a pioneering exploration, marrying geographic data with advanced machine learning models, to offer a
holistic perspective on the viability and economic implications of green energy arrays.

## Motivation

It goes without question that the Earth is warming at an abnormal rate compared to years prior. The source of the obscure warming period we, as a
society, are experiencing is highly debated in fields ranging from politics, to economics, and even to education. However, there is clear evidence,
seen in the results of numerous studies, that emphasize human contributions, which go as far as to prove humans are furthering the negative effects of
climate change through the escalation of global temperatures. Prolonged temperature observations serve as the most persistent evidence of climate
change. [@21558] Imperious is the effect of temperature on multiple aspects of human society and the environment such as agriculture, human health,
water, infrastructure, and ecosystems. Temperature is the governing factor when it comes to consequences of climate change, and it has only been
increasing. For perspective, the global annually averaged surface air temperature has risen by 1.8$^{\circ}$F (1.0$^{\circ}$C) over the last 115
years. [@21558] This drastic increase in temperature has now marked the current period as the warmest in modern civilization's history. [@21558] More
specifically, for the period 1986-2016 relative to 1901-1960, the global annual average temperature has increased by more than 1.2$^{\circ}$F
(0.7$^{\circ}$C). Surface temperatures worldwide have also increased by up to 3.0$^{\circ}$F in some areas of the globe. [Figure 1] [@21558]

![The left panel indicates global average temperature readings relative to the 1901-1960 average. It showcases an overall increase over a span of about 120 years. Red bars represent temperatures higher than the average, while blue bars represent those that are lower than average. [@21558] The right panle indicates surface temperature changes (in $^{\circ}$F) for the period 1986-2016, relative to the same average. Gray represents missing data. [@21558]](images/es-1.png)

The parallel between the time period which dictates the greatest increase in warming, and the time period in which humans have seen substantial growth
in technology and infrastructure, is no coincidence. In fact, society is acting perilously regarding the state of our world through the widespread
technological advances made in recent years. Greenhouse gasses are the most impactful byproduct of this activity, as the magnitude of climate change
is wholly dependent on the amount of heat-trapping gasses released globally. [@21558] Much of the damage is already done, but efforts to mitigate
these effects are not, and will not be fruitless. It can be observed that if no changes are made to our emissions, the side effects get exponentially
worse, while if changes are made and emissions are cut to the bare minimum, then damage to the planet will not grow, and instead will taper off until
the Earth naturally rebalances itself. [Figure 2] [@21558]

![The left panel shows annual historic range of plausible future carbon emissions per year. The right panel shows historically observed temperature changes and future temeperature changes as a result of a set of future scenarios relative to the 1901-1960 average.[@21558] In combination, a correlation is seen that suggests the severity of carbon emissions maps directly to temperature change.](images/es-3.png)

With this information, the culprit becomes identified: the burning of fossil fuels that release greenhouse gasses. Over 70% of global greenhouse gas
emissions come from the energy sector. [@owid-ghg-emissions-by-sector] These emissions are responsible for powering the worldwide manufacturing
processes we take advantage of every day, powering the transportation industry that we abuse to travel back and forth from our daily commutes, and
powering residential and commercial buildings, which we take for entirely granted. Nearly 80% of global primary energy comes from high-carbon sources.
[@owid-energy-mix] Such high usage of fossil fuels points to one clear solution, the implementation of rapidly growing, low-carbon energy sources,
which take the form of renewables like wind and solar. [@owid-energy-mix] Installing renewables, especially when public knowledge surrounding them is
low, is no easy task. This is an issue this project seeks to address.

## Goals of the Project

Renewable energy is difficult to install due to the large collection of barriers that get in the way of a process that is ultimately beneficial for
the whole. Five of these barriers present themselves as the leading blockades to low-carbon installations. These include economic barriers, knowledge
barriers, social barriers, organizational barriers, and installation-related barriers. [@REINDL2021110829] [@Mastoi2023] Each barrier carries with it
its own set of divisions that better define it, but ultimately, each barrier can be mostly resolved simply through access to valuable resources and
data. [@REINDL2021110829] Geographic data, economic data, and energy data offer substantial insights into how each of these barriers can be torn down,
allowing for the installation of renewable energy, which, in turn, leads to less harmful climate impacts. This project will take advantage of this
truth to produce a tool that will both access and produce the aforementioned data for both private companies and the general public to use to gain key
insights into factors that aid in the installation of low-carbon energy production technologies.

The tool will utilize advanced machine learning algorithms, with a particular focus on cluster analysis, to produce accurate predictions of
geographic, economic, and energy data through the use of locational data and array size as inputs. The resources and predictions generated by the tool
would serve to supply information about how potential renewable energy arrays would perform, and how much they would cost to produce. This can then be
used to break down those barriers, leading to positive climate impacts. At a lower level, this work will unearth which of the chosen machine learning
algorithms produces the most viable and accurate results when modeling data of this type, as more sophisticated results would lead to more positive
changes to the climate.

## Ethical Implications

This project also has the potential to carry with it negative side effects if misused, or abused, or just by nature of the field in which work in
renewables operates. One of these side effects persists of the land use impacts that green energy arrays carry with them. This is important to
consider as, if the tool developed from this work is used to promote, plan, and construct renewable energy solutions, then the spacial extent of these
technologies plays a meaningful role in the lives of individuals and the environment. By nature, low-carbon energy sources have lower power densities
than their non-renewable, high-carbon counterparts. [@VANZALK201883] Each array then requires more land area to produce similar amounts of energy,
leading to estimates that dictate that significant portions of land will be occupied by renewable energy systems. [@VANZALK201883] Worries become even
more prevalent as the political climate shifts towards mandating the installation of these technologies. California Senate Bill 100 does just this, by
committing the state to achieving 100% clean energy in all sectors by 2045. [@SCHULTE201931] This could lead to monumental land use impacts that could
displace individuals, unjustly occupy land, and destroy the environment, due to incentives to install more renewables. Given the scenario where this
tool is used similarly, it could also indirectly perpetuate these same injustices.

Land use is not the only transgression that the promotion, production and installation of renewables can perpetrate, however. The materials needed to
create the solar panels and wind turbines that could be installed through the use of this project's tool pose severe threats to environmental health,
and, subsequently, human health. [@Sonter2020] Mining for the vast array of resources needed for low-carbon installations potentially influences 37% of
Earth's terrestrial land area under some assumptions, which has large impacts on biodiversity by the way of habitat loss and ecosystem destruction.
[@Sonter2020] Furthermore, each resource being mined carries with it its own set of risks for the worker(s) extracting the minerals. Risks mainly
manifest themselves as direct health issues like respiratory impacts, cancers, or other mining related injuries. [@Stephens2001WorkerAC] When it comes
to mining, it is also important to discuss the social impacts that mining can have on certain communities. Peru showcases how mining affects the life of
individuals societally by presenting large economic disparities based on geographic distance to mining centers. [@LOAYZA2016219] Taking these impacts
into consideration, considerable controversy can be identified and applied to the installation of renewable sources.

This project seeks to mitigate ethical issues, like those outlined above, as much as possible. But in this case, any attempt to address these ethical
concerns within the scope of this research, would only limit the potential of the project. As many of the most important ethical issues that can be
derived from the use of this tool are unintended consequences that stem from the field of renewable energy in general, the most effective way to help
lessen the impacts would be to heavily advocate for the use of this tool by individuals and organizations that commit themselves to sustainable
practices. However, limiting the use of this tool would then undermine the main purpose of this research. It seems that the efforts to limit the negative
consequences must be addressed by the community as a whole, instead of within the scope of this project.


# Related work

In this section, we provide a comprehensive review of some of the most prominent, existing tools and research that concerns modeling the performance and
cost of low-carbon technologies, such as solar and wind power. We discuss their functionalities, strengths, weaknesses, and limitations, as a way to
examine the various tools and research extensively. Analysis of the work in question serves two purposes: first, to provide a nuanced understanding of
the existing landscape, and second, to aide in the identification of relevant and important gaps that serve as the focal point of this research.
Subsequent to this evaluation, bespoke solutions are brought to light and, through the assistance of more academic literature, are intricately
intertwined to provide a pathway for this project to fill the aforementioned gaps, and to supply a new solution to help overcome barriers to
installations, as well as to assist in tackling the issue of climatic change.

## Existing Tools

The field of this research has seen many major strides regarding tooling that gives access to crucial information that is needed when considering,
planning, installing, and maintaining renewable energy arrays. Much of the work is focused around assisting in the planning and installation process,
which serves to overcome many of the barriers that present themselves when implementing renewable energy. These barriers get broken down by various
methods depending on the tool being used. For example, some tools use complex analysis to provide the most accurate predictive models, dependent on
hundreds of input parameters to ensure an array is as efficient and bankable as possible. On the other hand, some tools barely scratch the surface,
supplying a very high-level analysis of an array, only making note of its potential energy output. Nonetheless, the collection of the most popular tools
that exist serve to offer a range of experiences that provide the most relevant information based on what a user needs.

One of the most impactful contributors to this field is the National Renewable Energy Laboratory (NREL). The researches at the NREL strive to produce
accurate and useful tools and data for a wide range of consumers ranging from the general public, to private companies. The most influential of these
tools is the NREL's System Advisor Model (SAM). The SAM is a techno-economic computer model that is designed to facilitate decision making for people who
are strictly involved in the renewable energy industry. More specifically, is it tailored to be a resource for project managers and engineers, financial
and policy analysts, technology developers, and researchers. [osti_1440404] This tool offers very in-depth analysis of a multitude of renewable energy
arrays ranging from wind and solar, to geothermal and tidal. Each renewable energy source then has dozens of various input parameters that allow the user
to adjust the array to fit their specifications, along with the inclusion of any relevant economic information. In the end, SAM provides a fully formated
and detailed report, with graphs, tables, and charts, that outline the performance of multiple factors of the array and its financial implications.
[osti_1440404] The simulations used to get to these conclusions consist of calculating the power output of a system for each hourly, or subhourly,
timestep in a year, and calculating project cash flow over a designated multi-year period. These simulations can then be used to perform studies like
parametric analysis, which examines relationships between input variables and results, or stochastic analysis, which creates histograms that showcase the
sensitivity of results to input values. [osti_1440404] A study was performed to validate the accuracy of SAM's predictions, and it was found that for all
systems evaluated, the annual agreement between SAM-predicted and measured power production is within ${\pm}$3%. [osti_1115788] Overall, the NREL's SAM
has shown itself to be a monumental step in being able to provide accurate information about a range of renewable energy arrays, even if it is tailored
towards a very specific audience.


# Method of approach



# Experiments

## Experimental Design

## Evaluation

## Threats to Validity



# Conclusion

## Summary of Results

## Future Work

## Future Ethical Implications and Recommendations

## Conclusions



# References

::: {#refs}
:::
