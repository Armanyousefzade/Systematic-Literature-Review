# Systematic-Literature-Review
Details of Systematic Literature Review:

To obtain an overview of the research literature on the measurement of SECO health, we performed a systematic literature review, a method to identify, evaluate, and interpret the available research relevant to a particular topic, research question, or phenomenon of interest. By conducting an SLR, I aimed to identify and interpret the available research relevant to the following research questions:

RQ1: How has software ecosystem health been defined in the literature?
RQ2: What metrics have been proposed or used for evaluating software ecosystem health in the literature?

We performed our systematic literature review based on the guidelines described by Kitchenham and Charters. We selected the following four electronic databases for our search: ACM Digital Library, IEEEXplore, ScienceDirect, and SpringerLink. Appropriate search terms are important to properly and effectively search for relevant studies. In this respect, Kitchenham and Charters propose viewpoints related to population, intervention, comparison, and outcome (PICO), which SLRs have widely utilized. We do not have a clear intervention and comparison in this study; however, the relevant terms for population and the outcome are as follows:

Population: Industry groups and application areas are considered a population. In our research, we chose \textbf{software ecosystem} as our population.
Outcome: By providing taxonomies and an overview of software ecosystem health, metrics, and practices adopted in this field,
We help practitioners measure how healthy these ecosystems are and improve their health.

To maintain search consistency among the multiple databases in our study, we constructed the following search string based on the PICO structure:

Search string: ``software ecosystem'' AND (health OR healthy)

Then we defined inclusion and exclusion criteria to be sure that relevant studies would be selected. We applied the following inclusion criteria: (1) The study must describe practices, theories, approaches, issues, definitions, and/or metrics related to measuring the health of SECOs; (2) The study must be unique, i.e., if a study was published in more than one venue, the complete version was used. We used the following exclusion criteria: (1) Studies written in languages other than English; (2) Studies only available as abstracts or PowerPoint presentations.

To conduct our SLR, manage a large number of references, and remove duplicate studies, we used a tool called StArt (http://lapes.dc.ufscar.br/tools/start_tool)(State of the Art through Systematic Review). We performed the search phase on 09/11/2019, and all the papers published before this date were considered in the search. In the search phase, we searched the electronic databases with our search string, collecting 364 papers. In the selection phase, we applied the inclusion and exclusion criteria, taking into account the abstract, title, and keywords of each study. In the selection phase, 42 studies were accepted for the extraction phase, and the rest of the papers were rejected. In the extraction phase, inclusion and exclusion criteria were applied again, taking into account the full content of the 42 papers. In the extraction phase, 27 papers were considered as primary studies. Additionally, we used a backward and forward snowballing technique to find other relevant papers, which added another 13 studies to the list of primary studies, bringing my total to 40 studies. 

All the phases of the SLR except snowballing were done with the StArt tool. The snowballing phase is not supported by the tool, so it was done manually and by checking all the backward and forward citations of papers. 

All the details of each phase of my SLR incliding the papers that were accepted and rejected in each phase, all the found papers in the search phase through the databases, and duplicated papers and other types of visualization of process of our SLR is available in the [review.start](Review.start) file in this repository. This file should be opened by StArt tool (State of the Art through Systematic Review). [Download](http://lapes.dc.ufscar.br/tools/start_tool) this tool and watch a short [tutorial](https://www.youtube.com/watch?v=zCTKl1TBmxU&t=5s) before using it to open [review.start](Review.start).
