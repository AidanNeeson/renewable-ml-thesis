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
systems evaluated, the annual agreement between SAM-predicted and measured power production is within $\pm$ 3%. [osti_1115788] Overall, the NREL's SAM
has shown itself to be a monumental step in being able to provide accurate information about a range of renewable energy arrays, even if it is tailored
towards a very specific audience.

An earlier tool, PVsyst, founded by André Mermoud and Michel Villoz, allows for a similar in-depth analysis, however, the focus is entirely on
photovoltaic (PV) systems. PVsyst, similarly to SAM, was designed for a specific demographic that encompasses architects, engineers, and researchers of
PV systems. [Mermoud_Villoz_2023] As such, the interface, process, models, and results are out of the scope of the general public. In spite of that,
PVsyst does offer great tooltips and help menus to explain what is happening behind closed doors, which opens up the opportunity for individuals who
otherwise would be unfamiliar with PV systems to educate themselves on certain concepts. [Mermoud_Villoz_2023] Regardless, the software carries with it
an assumption that the user has a lot of the information internalized, however, these assumptions allow PVsyst to provide valuable, detailed metrics. The
tool comes equipped with the ability to map out system design and sizing, simulate shading and grid storage, perform economic evaluations, and even
simualte solar pumping systems. [Mermoud_Villoz_2023] All of these features that come with PVsyst also bring with them the necessity for a cumbersome
amount of input parameters to carry out the simulations and modelings, so much so that the barrier to entry is even higher, further restricting who can
effectively use the software. Nonetheless, PVsyst is a well maintained, early iteration into the field of renewable energy simulating and modeling, in so
much as its impacts can be seen in other tools. Restrictions aside, it provides valuable insights into some of the most important results to be found
when analyzing low-carbon technologies for both efficiency and cost.

A large focus of many of the tools in this field are heavily focused on optimization and extracting as much information about an array as possible. SAM,
PVsyst, and others, like Openwind, a software package aimed specifically at wind farms, are examples of these technologies. [Openwind_2023] Many private
companies and citizens, however, do not need to know such specific details about renewable energy arrays. Most of the time, the information that is
needed in the eyes of private companies looking at promoting or selling renewable energy does not extend past estimated energy output and cost of
potential installations. This is where tools like OpenSolar become very valuable. OpenSolar is a free application that enables users to design and
simulate annual energy production and costs for small residential and commercial PV systems. [Westbrook_Macpherson_Desharnais_2021] The end goal of the
OpenSolar experience leads to the creation of a proposal, indicating a heavy skew towards this tool being used by companies selling solar to clients.
Digital surface model data (DSM) is used to gather three-dimensional information of certain locations, which is then used for their shading models for
energy production estimates, which culminate into the solar proposals that outline the viability of a given solar installation. These calculations are
abstracted from the user, and while they have the option to input some of this information manually, most of it happens without the need to input any
parameters. [Westbrook_Macpherson_Desharnais_2021] The bare minimum requirements that are needed to design a solar array and generate energy production
and cost estimates is the location of the desired array, the cost of energy from utilities in the given location, and the desired solar modules and
equipment to be used. While the design process is more interactive than inputting those three fragments of information, it is significantly less complex
that other software like SAM, or PVsyst. The application also comes with a simple and easy to follow tutorial that greatly lowers the barrier to entry.
This lack of complexity does not take away from the accuracy and effectiveness of OpenSolar's models, however. The NREL's SAM is utilized by OpenSolar to
generate many of the estimates, which has proven itself to be an accurate tool. [Westbrook_Macpherson_Desharnais_2021] Overall, OpenSolar does a great
job at filling its role as being a simple design tool that gives companies, and potentially citizens, the ability to make informed decisions about the
potential for solar installations. Yet, there exists still a multi-step process that a user must complete to gain access to accurate estimates.

Another contribution from the NREL, PVWatts, establishes progress towards solving the problem posed by all of the previously mentioned tools: the
necessity to follow a multi-step process and supply a vast amount of input parameters. The NREL PVWatts calculator is a web application that estimates
electricity production of a grid-connected PV system based on a small number of trivial inputs. [osti_1158421] These inputs include values like array
location, in the form of longitude and latitude, array size, array orientation, and some other optional parameters. Once filled out, the results of the
calculation can be viewed, which portray the total estimated amount of solar irradiance and energy output both annually and monthly. [osti_1158421] It is
important to note that the results are made so easily available due to the use of many assumptions about the system being examined. [osti_1158421]
PVWatts is very simple, and with this comes some drawback relating to accuracy. It is documented in the version manual that errors can be high as
$\pm$ 10% for annual energy totals and $\pm$ 30% for monthly values, potentially even reaching $\pm$ 20% and $\pm$ 40% respectively when regarding
some edge cases. [osti_1158421] Errors being so high has the potential to be negative, but given the purpose of PVWatts, these values are quite 
reasonable. The goal of PVWatts is to give quick estimates of energy production from PV systems. [osti_1158421] This is something that the application
does accomplish accurately enough in a majority of situations. There are still issues to be had regarding PVWatts, however. The information provided is
very lightweight. In the end, all that a user receives is two estimates, even when there is a potential for substantially more information to be given.

## Identified Gaps

After examining some of the most prominent tools in the field, it becomes very clear that there are some gaps pertaining to the kinds of tools that are
out there, and what each of the various tools offer to users. Much of the renewable simulation and estimation terrain is dominated by software similar to
the NREL's SAM and PVsyst. That is, very complex and accurate analytical tools that offer up rigorous assessments of renewable systems, of which the vast
majority are wholly inaccessible to those who are not dedicated researchers and project engineers. This is where tools like OpenSolar can be of some
assistance, offering up a streamlined experience that walks users through designing and modeling a PV system, all the while abstracting all of the
simulations being ran by SAM behind the scenes. Even still, OpenSolar, and applications alike, are tailored towards businesses trying to sell solar or
individuals who are already serious about pursuing a solar installation. All of these tools make a similar assumption: the user knows enough about solar
to establish informed decisions regarding installations. This is not always the case, which is where PVWatts can be of immense value. The ability to
select a location and assess the area's viability for solar is not only a useful action for the demographic the aforementioned tools target, but it also
helps to educate those who are unfamiliar with the field on the potential that PV systems posses. There are still missing pieces, though. PVWatts has the
potential to supply information akin to what tools like PVsyst or SAM do, through the use of more assumptions the application is already built on.
Furthermore, other renewables energy sources see less attention. It is no coincidence that PV system software was a main focus, as it sees the most
attention in the field, while other technologies, like wind, do not posses tools similar to PVWatts that provide on demand information about the relative
viability of a wind farm.

With all of this information, a gap in the renewable energy installation field is very prevalent. A tool that can provide quick access to an abundance of
metrics about renewable energy arrays is desperately needed. Too much of the industry is dominated by software that is too similar to one another, and
not enough attention is put into software that can educate the public and onboard more people into the world of renewable energy. A tool that is as easy
to use and as accurate as PVWatts that distributes an abundance of information similar to tools like SAM or PVsyst would be a substantial leap towards
breaking down all of the barriers that prevent installation of renewable energy tehcnologies, leading to even more progress mitigating climate change
impacts globally.

## Proposed Solutions

This project produces a tool that fills the gap outlined in the above section. Through the use of the same data that software like the NREL's SAM, or
PVsyst utilizes, this research takes a different approach to getting results that can be used to fulfill the needs described above. Machine learning is
becoming more prevalent than ever before, with artificial intelligence and large language models dominating the computer science space currently. This
project builds off of the power of machine learning to create a tool that can address the needs of the renewable energy field. Within the context of
geographic data, of which the data this project uses resides, cluster analysis is seen as immensely useful in identifying groups of similar data points
and performing detailed analysis of each group. [tung2000geo] More specifically, K-means clustering is used to perform the grouping of data points. The
K-means clustering algorithm takes an initial clustering that is not optimal and relocates each point in the cluster to its new nearest center, then
updates the clustering centers by finding the mean of the member points, iteratively following this process until the convergence criteria is met, which
in most cases is the defined number of iterations. [Jin2010] These kinds of algorithms and models can be applied to the geographic data in question to
effectively model the same results that SAM and PVsyst produce. The benefit of this solution is that it only takes a few inputs to perform the analysis.
Combining it all together realizes a tool that is easy to use, as it has very few inputs, and has the ability to produce a wide range of predictions for
various different values.

## Ethical Progress

Since many of the ethical implications of this work are out of the scope of the project itself, it is especially important to highlight the work that is
being accomplished in the community to address the various issues. The renewable energy field attempt to be as conscience as possible when considering
the effects of installing renewable energies. This can be clearly seen in India's efforts to reduce emissions. A large consideration that India is taking
into account when looking at installing renewable energy to meet their goals is the potential land use effects. [su12010281] In this study, they examine
two approaches to installations: one explores placing new infrastructure in natural habitats or high production agriculture, while the second explores
placing new infrastructure on lands already degraded by humans. [su12010281] It was discovered that putting wind turbines in already degraded areas and
installing solar panels on rooftops where possible, would lead to lesser land use impacts that utilizing natural habitats and agricultural spaces.
[su12010281] This work points in a clear direction when concerning the practices that should be considered when developing new energy technologies
elsewhere in the world. Prioritizing already developed lands will mitigate the land  use impacts of renewable energy, effectively negating one of the
biggest concerns with renewable energy.

Another substantial concern deals with the negative socio-economic, environmental, and health effects that mining the resources needed for low-carbon
technologies has on communities and individuals. When concerning the health of the environment, many countries have adopted rules an regulations that
ensures sustainable mining practices are followed. Environmental Impact Assessment (EIA) is a tool used around the world that does just this.
[singh2016environmental] The key scopes of this tool are to identify appropriate measures to mitigate the negative impacts of mining and to enhance the
benefits of mining through policy, where in the reach of this tool can benefit areas like soil contamination, all the way to biodiversity conservation
[singh2016environmental] All of these positive environmental effects in turn will only seek to benefit the health of individuals in and around areas with
heavy mining operations. From a socio-economic lens, solutions become a bit trickier. While mining offers employment to many, it leaves some areas
without jobs, creating large economic disparity. [@LOAYZA2016219] A solution being investigated deals with using past, abandoned mining operations as a
catalyst for both environmental and economic growth. Bioreclamation of mined out areas brings back otherwise decimated habitats, as well as supplying
jobs for communities that are unable to benefit from the positives of mining. [singh2016environmental] In the end, the negative consequences of mining
can be somewhat reversed through sustainable practices, which also bring potential growth to struggling communities.


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
