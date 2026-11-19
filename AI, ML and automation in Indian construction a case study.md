# AI, ML and automation in Indian construction: a case study

Nov 16, 2026 · @Adobe 2

## Summary

India has the research and the first deployments, but not the management system that turns either into normal practice. This report is a desk study for a BTech civil engineering project. It applies the framework of the attached paper to India and answers each question in the project brief.

| Question in the brief | Short answer |
| --- | --- |
| What is the situation in India? | AI and automation are in real use on highways, on flagship metro and rail projects and inside one large contractor. Ordinary building work and small firms are untouched. |
| What research is going on? | India is third in the world for AI and ML civil engineering papers, with 4,600 since 2015 and yearly output up about 30 times. Only 1.2% involve a company. Most work is on defect detection and materials, little on management. |
| Which foreign technologies, and in which sectors? | Nine are listed with sectors, led by machine-controlled road construction, digital building approvals, information management to ISO 19650, prefabrication and bridge monitoring sensors. |
| How can they be incorporated? | Through the route India used for highways: a public client pilots, a ministry issues a circular, and the requirement enters contracts. |
| What management is needed? | Six things: procurement, contracts and liability, organisation and roles, people and change, performance measurement, and supply chain. India handles them project by project. Japan, Singapore, the UK and China set them nationally. |
| How to do it fast and safely? | A three-phase roadmap: standardise and measure, mandate by project size, then scale. A named engineer signs off every AI output. |
| What resources are needed? | Finance and computing are now available. Skilled people, shared datasets and proof of benefit are scarce. |
| How do engineering and management fit together? | Engineering produces a trusted measurement. Management makes sure someone acts on it. A three-level KPI table links the two. |

**How far to trust this report.** Every source was opened and is listed by strength at the end. Facts from government and peer-reviewed sources are firm. Facts from company statements and trade press are claims. The publication counts are my own analysis and should be rerun. The roadmap and recommendations are my reasoning from the evidence. Items I could not verify are named where they arise.

## The reference paper and the framework borrowed from it

The attached paper finds that construction has plenty of working AI prototypes but very little adoption, because the tools are not tied into how quality is actually managed. It is [Dehbandi, Shirpourasl and Asnaashari (2026)](https://doi.org/10.1016/j.autcon.2026.107166), *Automation in Construction* 191, 107166, a PRISMA systematic review of 51 studies from 2006 to 2026.

What the paper found:

- **Research sits at the site level.** 21 studies deal with quality control, 10 with inspection and 17 span several levels. Only 1 deals with assurance alone and 2 with management alone.
- **AI/ML and sensing dominate.** AI/ML appears in 23 studies, IoT and sensing in 22, robotics in 16, blockchain in 5 and AR/VR in 3.
- **India is a small contributor.** China leads with 10 studies, then the USA and Hong Kong with 6 each. The UK and India have 3 each.
- **Industry is mostly absent.** Only 7 of 51 studies report direct industry collaboration, and no institution appears twice.
- **Results are reported in the wrong units.** 12 studies report only algorithm scores such as precision or mAP. Only 7 link those scores to a process outcome such as rework cost or time to close a non-conformance report (NCR). 26 are unclear.

The paper's three conclusions are that better detection alone does not scale, that a technology must be valued in the measures managers already use, and that adoption depends on "governance fit".

This study applies the same four ideas to India and widens them from quality management to construction as a whole:

| Idea from the paper | What it means | How this study uses it |
| --- | --- | --- |
| Maturity grading | Each technology is graded lab-tested, pilot or on-site | Every Indian example below is graded announced, pilot or deployed |
| Technology against management level | Technologies are mapped to inspection, control, assurance and management | Technologies are mapped to Indian sectors: roads, metro and rail, buildings, bridges, water, geotechnical |
| KPI stack | Report task, process and system results together, against a baseline | Proposed as the measurement method for the project's own case study |
| Governance fit | A tool is adopted when it attaches to an existing routine, contract duty and incentive | Used to explain which technologies India has adopted fast and which have stalled |

## Where Indian construction stands today

India already uses AI and automation on real projects, but almost only where a government client has ordered it. Highways lead, flagship metro and rail projects follow, and ordinary building work is far behind.

**The problem being solved.** Central projects of Rs 150 crore and above show the cost of the current way of working. MoSPI's February 2026 flash report covers 1,948 such projects. Their cost has risen from Rs 36.32 lakh crore to Rs 41.98 lakh crore, an overrun of Rs 5.66 lakh crore or about 15.6% ([NBM&CW, reporting MoSPI](https://www.nbmcw.com/news/infra-projects-worth-rs-150-cr-see-rs-5-66-lakh-cr-cost-overrun-mospi-report.html)). Worldwide, construction labour productivity grew about 1% a year over two decades, against 2.8% for the whole economy ([McKinsey Global Institute, 2017](https://www.mckinsey.com/mgi/our-research/reinventing-construction-through-a-productivity-revolution)).

**What is in use.** Each entry is graded the way the reference paper grades maturity.

| Programme | What it does | Maturity | Source |
| --- | --- | --- | --- |
| NHAI Network Survey Vehicles | 3D laser vehicles detect cracks, potholes and patches automatically over 20,933 km in 23 states. Data goes to NHAI's AI-based Data Lake portal. | National roll-out announced October 2025 | [Akashvani News, Oct 2025](https://newsonair.gov.in/nhai-to-deploy-3d-survey-vehicles-in-23-states-for-ai-based-highway-monitoring/) |
| NHAI drone and dashcam monitoring | Monthly drone video is mandatory on highway projects. AI dashcams cover roughly 40,000 km of national highways. | Deployed | [Indian Infrastructure, Aug 2026](https://indianinfrastructure.com/2026/08/10/building-on-data-increasing-digitalisation-across-infrastructure-sectors/) |
| MoRTH machine-aided construction (AI-MC) | GPS-aided motor graders and intelligent compaction rollers with real-time data logging. Piloted on the Lucknow-Kanpur Expressway, then ordered on more than 25 national highway projects by a circular of 23 June 2025. | Pilot, now required on selected projects | [NBM&CW, Jun 2025](https://www.nbmcw.com/news/morth-issues-directive-for-ai-machine-controlled-construction.html) |
| PM GatiShakti | A shared GIS planning platform with over 23,493 data layers, used by 58 central ministries and all 36 states and UTs. | Deployed for planning | [PIB, Oct 2026](https://www.pib.gov.in/PressNoteDetails.aspx?id=160423&NoteId=160423&ModuleId=3&reg=38&lang=1) |
| Delhi-Meerut RRTS (NCRTC) | BIM, a common data environment, the in-house SPEED monitoring tool and the iDREAMS asset system form a digital twin. A proof of concept used more than 1,500 IoT sensors. | Deployed on one flagship project | [Construction World, Aug 2026](https://www.constructionworld.in/gold/transport-infrastructure/metro-rail-and-railways-infrastructure/twin-tracks/95231) |
| L&T Construction | IoT on 15,000 machines, drones on 50+ projects, computer vision that flags missing helmets, gloves and shoes, and AI planning of steel cutting. | Deployed inside one large firm | [Machine Maker, Oct 2024](https://themachinemaker.com/news/ai-and-digital-tech-to-cut-construction-costs-by-2-3-lt/) |
| Light House Projects | Six housing projects of over 1,000 houses each, built with six different technologies chosen from 54 shortlisted. Total cost Rs 843.59 crore. Five are complete. | Demonstration at scale | [PIB, Jul 2025](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2149389) |
| 3D concrete printing | L&T began 3D printing the 1,000 sq ft Halasuru post office in Bengaluru in 2023. BMTPC approved the technology and IIT Madras validated the design. Tvasta has printed a villa. | Demonstration | [L&T, Apr 2023](https://www.lntecc.com/news-room/press-releases/l-t-is-3d-concrete-printing-india-s-first-post-office-building-in-bengaluru-april-2023), [NITI Frontier Tech Hub](https://frontiertech.niti.gov.in/story/technology-behind-indias-first-printed-home) |
| Dam safety (DRIP and DHARMA) | A digital platform for dam inspection and safety data. India has 6,628 specified dams, of which 26% are over 50 years old. | Deployed as a data platform | [IANS, May 2026](https://ianslive.in/digital-tools-rehabilitation-project-enhance-indias-dam-safety-and-ageing-resilience--20260515160654) |
| Jal Jeevan Mission | Assets are geo-tagged and pipelines uploaded to GatiShakti. IoT sensors monitor supply in selected villages. | Pilot | [PIB, Feb 2026](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2226990) |

**What is missing.**

- **No national BIM mandate.** India "still lacks a comprehensive national BIM mandate comparable to the UK's", and a national BIM standard is only under discussion ([Indian Infrastructure, Aug 2026](https://indianinfrastructure.com/2026/08/10/building-on-data-increasing-digitalisation-across-infrastructure-sectors/)).
- **Bridges are not monitored.** A media count found 170 bridge collapses and 202 deaths between 2021 and 2025. The president of the Indian Structural Health Monitoring Society says most bridges age without sensors ([Newslaundry, Jul 2025](https://www.newslaundry.com/2025/07/29/4-years-170-collapses-202-deaths-whats-ailing-indias-bridges)).
- **Ground investigation is weak.** The state inquiry into the 2023 Silkyara tunnel collapse found the project report lacked detailed geotechnical and geophysical investigation ([The Tribune](https://www.tribuneindia.com/news/india/silkyara-collapse-shows-overhaul-must-in-infra-works-says-report-585877)).
- **Benefits are not measured.** L&T estimates AI and digital tools could cut cost by 2 to 3%, but says it will take more time to quantify the larger impact ([Machine Maker, Oct 2024](https://themachinemaker.com/news/ai-and-digital-tech-to-cut-construction-costs-by-2-3-lt/)).

**The policy base added since 2025.**

- **Research money.** The Cabinet approved the Rs 1 lakh crore Research, Development and Innovation scheme on 1 July 2025. It gives long-term, low-interest finance for private R&D through the Anusandhan National Research Foundation ([PIB](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2141130)).
- **Computing.** The IndiaAI Mission has brought more than 38,000 GPUs into a shared facility for start-ups and academia ([PIB, Feb 2026](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2227612)).
- **AI rules.** MeitY issued the India AI Governance Guidelines on 5 November 2025. They set seven principles, rely on existing law, and take "Do No Harm" as the core idea ([PIB](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2186639)).
- **Site safety law.** The Occupational Safety, Health and Working Conditions Code took effect on 21 November 2025 with the other three labour codes ([PIB](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2192463)). Employers with 250 or more building workers must form a safety committee ([PIB factsheet](https://www.pib.gov.in/FactsheetDetails.aspx?id=150475&NoteId=150475&ModuleId=16&reg=3&lang=2)).
- **Data protection.** The Digital Personal Data Protection Rules were notified in November 2025 with a phased roll-out ([The Tribune](https://www.tribuneindia.com/news/business/govt-notifies-digital-personal-data-protection-rules-rollout-in-phases-specified-obligations-for-data-fiduciaries)). Site cameras and worker tracking fall under them.

The pattern matches the paper's "governance fit" idea. Road surveys, drone video and machine control spread quickly because one public client wrote them into its contracts. BIM has no such owner and has stalled, although a RICS panel reports that clients increasingly ask for digital twins at tender stage ([RICS, Aug 2024](https://rics.org/news-insights/wbef/digitalisation-in-the-indian-construction-sector-a-comparative-study-from-design-to-handover)).

## India's AI and ML research ecosystem

India is now the world's third-largest producer of AI and ML research in civil engineering, but that research has the weakest link to industry of the seven countries compared. Both numbers come from a count I ran for this study on [OpenAlex](https://openalex.org), an open index of research papers.

**How the count was made.** I counted papers from 2015 to 2025 whose main topic is civil and structural engineering or building and construction, and whose title or abstract mentions machine learning, deep learning, artificial intelligence or neural networks. The world total is 55,088 papers. The count was run on 16 November 2026 and the 2025 figure may still rise as indexing catches up. The counts measure the volume of research, not its quality.

&#91;embedded content: OpenAlex, queried 16 November 2026 · papers per year with an India-affiliated author, 2015 to 2025\]

India's yearly output grew about 30 times in ten years. Its share of the world total rose from 5.7% in 2015 to 9.6% in 2025.

| Country | Papers, 2015 to 2025 | Papers with a company co-author | Share with a company co-author |
| --- | --- | --- | --- |
| China | 15,257 | 1,183 | 7.8% |
| USA | 5,883 | 373 | 6.3% |
| India | 4,600 | 57 | 1.2% |
| UK | 2,319 | 156 | 6.7% |
| South Korea | 1,923 | 102 | 5.3% |
| Japan | 1,379 | 242 | 17.5% |
| Singapore | 631 | 33 | 5.2% |

Only 1.2% of India's papers have an author from a company. This is the same weakness the reference paper found worldwide, where 7 of 51 studies had industry collaboration, and India shows it more strongly. Indian firms may be under-recorded in OpenAlex, so treat the figure as indicative.

**What Indian researchers work on.** The work is concentrated in inspection and materials, not management.

| Research area in India | Papers | Share of India's 4,600 |
| --- | --- | --- |
| Infrastructure maintenance and monitoring | 950 | 20.7% |
| Concrete and cement materials, including reinforcement and recycled aggregate | 832 | 18.1% |
| Geotechnical engineering | 635 | 13.8% |
| Building energy and comfort | 349 | 7.6% |
| Structural health monitoring | 306 | 6.7% |
| Water systems | 184 | 4.0% |
| Seismic performance | 178 | 3.9% |
| BIM and construction integration | 103 | 2.2% |

BIM and construction integration is 2.2% of India's output, against 5.0% worldwide. Indian research is strong on predicting concrete strength and detecting defects, and thin on how projects are managed.

**Who does the work.** The most active institutions by paper count are NIT Patna (233), SRM Institute of Science and Technology (185), Saveetha University (123), VIT (119), Chandigarh University (92), NIT Rourkela (88), IIT Madras (88), IIT Roorkee (85), NIT Kurukshetra (81), IIT (ISM) Dhanbad (76), IIT Delhi (66) and IIT Bombay (65). An independent Scopus review of neural networks in construction also names China, India and the USA as the key players ([Ametepey et al., 2026](https://www.mdpi.com/2075-5309/16/12/2470)).

**Examples of research groups and centres.**

| Group | Work | Stage | Source |
| --- | --- | --- | --- |
| IIT Madras, Building Technology and Construction Management with the Robert Bosch Centre | ConPro-NET identifies building elements from site point clouds to track progress. It reached about 81% accuracy on a case study. | Lab and case study | [Reja et al., 2024](https://rbcdsai.iitm.ac.in/publications/hybrid-self-supervised-learning-based/), [Reja et al., 2022](https://doi.org/10.1016/j.autcon.2022.104245) |
| IIT Madras with L&T | Validated the structural design of L&T's 3D printed post office. | One demonstration building | [L&T, Apr 2023](https://www.lntecc.com/news-room/press-releases/l-t-is-3d-concrete-printing-india-s-first-post-office-building-in-bengaluru-april-2023) |
| IIT Kanpur, AI Centre of Excellence for Sustainable Cities | Digital twins and AI models for air quality, energy, mobility and water. Awarded by the Ministry of Education in March 2024. | Phase 1 research | [IIT Kanpur](https://www.iitk.ac.in/centre-of-excellence-in-artificial-intelligence-for-sustainable-cities) |
| CSIR-Central Road Research Institute | AI-enabled Network Survey Vehicle and pothole repair technology, rolled out in 16 towns in July 2026 and licensed to firms. | Commercialised | [Devdiscourse, Jul 2026](https://www.devdiscourse.com/article/law-order/3951391-csir-crri-begins-platinum-jubilee-with-nationwide-road-technology-rollout) |
| IIT Delhi and IIT Patna | Inspection of 85 major bridges for Bihar under its 2025 bridge maintenance policy. | Field service | [Newslaundry, Jul 2025](https://www.newslaundry.com/2025/07/29/4-years-170-collapses-202-deaths-whats-ailing-indias-bridges) |

**Research on adoption and management in India.** This is the small body of work closest to the project's topic.

| Study | Method | Finding |
| --- | --- | --- |
| [Bajpai and Misra (2022)](https://doi.org/10.1108/IJQRM-09-2020-0318), *Int. J. Quality and Reliability Management* 39(10) | Expert interviews, Fuzzy-DEMATEL and ISM | 14 critical barriers to digitalisation. Respondents came from one large company, which the authors list as a limit. |
| [Peter (2023)](https://link.springer.com/chapter/10.1007/978-981-99-3526-0_3), Springer book chapter | Questionnaire and Relative Importance Index | The biggest obstacles to AI are integration cost, technical feasibility and socio-cultural factors. |
| [Singh, Patil and Pandey (2026)](https://pure.jgu.edu.in/id/eprint/11181/), *IJMEMS* 11(2) | Expert evaluation and Grey-DEMATEL | Ten barriers to large language models. The root causes are real-time data processing, model accuracy and computing resources. |

**Funding and support.**

- **Public research funds.** The Rs 1 lakh crore RDI scheme and the Anusandhan National Research Foundation finance private R&D ([PIB](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2141130)).
- **Technology hubs.** The cyber-physical systems mission set up 25 Technology Innovation Hubs, which had produced 496 technology products by February 2022 ([PIB](https://www.pib.gov.in/PressReleasePage.aspx?PRID=1800518)). I found none dedicated to construction.
- **Start-ups.** One industry newsletter reports Indian construction-technology start-ups raised about $98 million in 2024 and about $358 million in 2025 ([ConTech Roundup](https://contechroundup.substack.com/p/why-india-is-becoming-the-foundation)). This is a weak source and should be checked before it is quoted.

## Sector-by-sector status in India

Roads are the only sector where AI and automation are both deployed widely and required by the client. Every other sector is at flagship-project, demonstration or research stage. The table is the India version of the reference paper's integration matrix, with sectors in place of management levels.

| Sector | What is used in India | Highest maturity seen | Research base in India | Main gap |
| --- | --- | --- | --- | --- |
| Roads and highways | AI survey vehicles, monthly drone video, AI dashcams, GPS graders and intelligent compaction | Deployed and mandated by NHAI and MoRTH | Strong. Infrastructure maintenance and monitoring is the largest topic with 950 papers. | No published before-and-after results on quality, rework or cost |
| Metro and rail | BIM, common data environment, digital twin and IoT sensors on the Delhi-Meerut RRTS. BIM on the Mumbai-Ahmedabad high-speed line. | Deployed on flagship projects | Thin. BIM is 2.2% of output. | Practice is not carried to smaller metro and state projects |
| Buildings and housing | Light House Project technologies, 3D concrete printing, computer vision for site safety at L&T | Demonstration at scale. Deployed inside one large contractor. | Moderate. IIT Madras works on progress monitoring. | Small and medium builders are outside all of it. No national BIM mandate. |
| Bridges | Inventory and condition rating in the Indian Bridge Management System. IIT inspections for Bihar. | Inventory deployed. Sensor monitoring largely absent. | Moderate. 306 papers on structural health monitoring. | Research exists but is not installed on bridges |
| Tunnels and geotechnical | No verified AI deployment found | Research only | Strong on paper. 635 geotechnical papers. | Silkyara showed basic ground investigation is still missed |
| Dams and water | DHARMA dam safety platform. Geo-tagged water assets and IoT sensors in selected villages. | Data platform deployed. Sensors at pilot. | Moderate. 184 papers on water systems. | Platforms record data. Predictive use is not yet evidenced. |
| Planning and cities | PM GatiShakti GIS platform. IIT Kanpur urban digital twins. | Deployed for planning. Research for cities. | Growing | Link from planning data to construction and maintenance |

Sources for each entry are in the two sections above. Three points stand out.

1. **Maturity follows the client, not the research.** Geotechnical work has six times more papers than BIM but no verified field use. Roads have both because NHAI and MoRTH write the technology into contracts.
2. **India repeats the paper's imbalance.** Deployed tools sit at inspection and control. Assurance and management uses, such as linking defect data to payment or to contractor rating, are not evidenced.
3. **The private building sector is the blind spot.** Every deployed example is a public client or one very large contractor.

## Foreign technologies India can incorporate

Nine technologies fit Indian sectors, seven with evidence from abroad and two already shown in India, and India has a working route for bringing them in: pilot on one public project, then a ministry circular, then a contract requirement. MoRTH took machine-aided construction from a draft circular in December 2024 to a directive covering more than 25 projects in June 2025 ([Indian Infrastructure](https://indianinfrastructure.com/2024/12/18/morth-to-introduce-automated-construction-with-aimc-technology/), [NBM&CW](https://www.nbmcw.com/news/morth-issues-directive-for-ai-machine-controlled-construction.html)).

| Technology | Where it is proven | Indian sector it fits | How to bring it in | Status in India |
| --- | --- | --- | --- | --- |
| Machine-controlled earthwork and paving with intelligent compaction | Piloted by NHAI on the Lucknow-Kanpur Expressway | National and state highways, rural roads, airports | Extend the MoRTH circular to state road agencies. Make compaction data a payment record. | Required on selected national highway projects |
| Automated and remote-operated construction equipment | Japan ran 9 automated and 41 remote-operated public works in FY2025 ([MLIT](https://www.mlit.go.jp/report/press/kanbo08_hh_001324.html)) | Hazardous work: hill roads, landslide clearance, tunnels, disaster recovery | Pilot through a public client on hazardous stretches first, where the safety case is strongest | Not found in use |
| Digital building plan approval on one platform | Singapore's CORENET X, where early projects saved up to two months on approvals ([BCA](https://www1.bca.gov.sg/resources/newsroom/speech-by-minister-chee-hong-tat-at-the-international-built-environment-week--ibew--industry-and-awards-dinner-2025/)) | Building permits in large cities | Add single-platform digital submission to city permit systems, large projects first | Not found in use |
| Information management to ISO 19650 | UK public clients under the Information Management Mandate ([Designing Buildings](https://www.designingbuildings.co.uk/wiki/Information_management_mandate)) | All public works | Adopt the standard nationally and require it in tenders above a cost threshold | Used project by project. National standard under discussion. |
| Prefabrication and off-site manufacture | China targets over 30% of new construction as prefabricated ([Xinhua](https://www.chinaservicesinfo.com/s/202201/27/WS62122eeb498e6a12c121f7b3/china-publishes-five-year-plan-for-construction-industry.html)) | Mass housing, schools, hospitals, metro stations | Build on the Light House Projects. Set a prefabricated share for public housing. | Six demonstration projects |
| Computer vision for progress and quality, from drones, 360-degree cameras and point clouds | The reference paper finds AI and drone inspection at on-site maturity worldwide | Buildings, metro, bridges | Start as a client reporting requirement, as NHAI did with monthly drone video | Deployed on highways. Research at IIT Madras. |
| Sensor-based structural health monitoring | China is reported to mandate sensors on new highway bridges ([Newslaundry](https://www.newslaundry.com/2025/07/29/4-years-170-collapses-202-deaths-whats-ailing-indias-bridges)) | Major bridges, flyovers, dams, tunnels | Require sensors on new major bridges. Retrofit those rated poor in the bridge management system. | Rare |
| 3D concrete printing | Shown in India by L&T and Tvasta on low-rise buildings | Low-rise housing, defence shelters, remote sites | BMTPC approval already exists. Needs a design code and trained operators. | Demonstration buildings |
| Construction robots for single tasks | China planned mass use of construction robots in some fields by 2025 ([Xinhua](https://www.chinaservicesinfo.com/s/202201/27/WS62122eeb498e6a12c121f7b3/china-publishes-five-year-plan-for-construction-industry.html)) | Repetitive or dangerous tasks: inspection in confined spaces, work at height | Begin with inspection robots, which fit existing inspection duties | Not found in use |

**How to adapt, not only import.**

- **Check the reason for adoption.** Japan's stated goal is labour saving, at least 30% fewer workers on site by FY2040 ([MLIT](https://www.mlit.go.jp/report/press/kanbo08_hh_001085.html)). India has abundant labour. The Indian case must rest on quality, safety, speed and cost overrun, not on saving labour.
- **Retrain models on Indian data.** A crack or helmet detector trained abroad must be tested on Indian materials, weather, lighting and site clutter before anyone relies on it.
- **Use the existing approval bodies.** BMTPC approved 3D printing and IIT Madras validated the design. The same route of technical approval and independent validation suits other imports.
- **Choose open data formats.** Singapore and the UK mandate information standards, not a vendor's software. This keeps small firms from being locked in.
- **Order by governance fit.** Technologies that strengthen a duty that already exists, such as inspection, are adopted fastest. The reference paper found blockchain quality records stuck at lab stage because they need new rules between parties.

## How other countries manage adoption

The four countries studied each use one clear lever, set by government, with a date and a number attached. India uses project-by-project requirements from individual agencies and has no national target.

| Country | Main lever | What it requires | Evidence of progress | Lesson for India |
| --- | --- | --- | --- | --- |
| Japan | A national productivity target, tested on public works | i-Construction 2.0, announced 16 April 2024, targets at least 30% labour saving on site by FY2040, a 1.5 times productivity gain. Its three pillars automate construction, data linkage and construction management. ([MLIT](https://www.mlit.go.jp/report/press/kanbo08_hh_001085.html)) | Automated works rose from 4 to 9 and remote-operated works from 21 to 41 in one year. FY2026 aims to move from trials to standard practice. ([MLIT](https://www.mlit.go.jp/report/press/kanbo08_hh_001324.html)) | Publish a yearly count of projects using each technology. Japan's numbers are small but public. |
| Singapore | The regulatory approval gateway | Building plans must go through the CORENET X digital platform. It became mandatory on 1 October 2025 for new projects of 30,000 sq m and above, and on 1 October 2026 for 5,000 sq m and above. Smaller projects are voluntary. ([URA and BCA](https://www.ura.gov.sg/guidelines/circulars/dc26-08/)) | Over 50 projects and 100 firms used it before the mandate ([BCA](https://www1.bca.gov.sg/resources/newsroom/speech-by-minister-chee-hong-tat-at-the-international-built-environment-week--ibew--industry-and-awards-dinner-2025/)) | Phase a mandate by project size, largest first, and announce dates in advance. |
| United Kingdom | The public client's information requirements | The Information Management Mandate, in the 2021 Roadmap to 2030, requires public clients to manage information to ISO 19650 ([Designing Buildings](https://www.designingbuildings.co.uk/wiki/Information_management_mandate)) | Not assessed here | Mandate the information standard, not a software product. Put the duty on the client first. |
| China | Five-year plan targets | The 2021 to 2025 construction plan set prefabricated buildings at over 30% of new construction and called for mass use of construction robots in some fields ([Xinhua](https://www.chinaservicesinfo.com/s/202201/27/WS62122eeb498e6a12c121f7b3/china-publishes-five-year-plan-for-construction-industry.html)) | China produces 15,257 AI civil engineering papers, 7.8% with a company co-author | Set numeric targets and tie research to industry. |
| India | Requirements set by individual agencies | NHAI and MoRTH mandate surveys, drone video and machine-aided construction on highways. There is no national BIM mandate. | See the sections above | Works well inside one agency. Does not spread across sectors. |

The UK row rests on a secondary source, and whether China met its 2025 targets was not checked. Hong Kong and South Korea also run funded programmes, but I could not open their primary documents, so they are left out.

## Management aspects needed for implementation

Implementation fails or succeeds on six management matters, and in each one the leading countries act at national level while India acts project by project. The reference paper's central lesson applies throughout: the thing to adopt is a routine, such as closing a non-conformance report, and the tool only serves it.

| Management aspect | What it involves | India today | Leading countries |
| --- | --- | --- | --- |
| Client and procurement | The client writes digital deliverables into the tender and pays against them | Strong in highways. The MoRTH circular requires real-time data logging, equipment calibration and QA/QC reports from machine-aided construction. Absent in most other sectors. | UK public clients must define their information requirements. Singapore makes digital submission a condition of approval. |
| Contracts and liability | Who owns site data, who acts on an AI alert, who is liable if the system misses a defect | Not settled. The AI governance guidelines rely on existing law rather than new rules. | Handled through the mandated information standard and client requirements |
| Organisation and roles | An information manager, a shared data platform and a team that reads the data | Seen in large organisations only. L&T built a unified data lake. NCRTC built SPEED and a common data environment. | Client-side information management is required of public bodies in the UK |
| People and change | Training, acceptance by site staff, and handling fear of job loss | The main barrier in Indian studies. Cost of integration, technical feasibility and socio-cultural factors rank highest ([Peter, 2023](https://link.springer.com/chapter/10.1007/978-981-99-3526-0_3)). An Autodesk and Deloitte survey lists lack of digital skills, technical knowledge and high cost ([Machine Maker](https://themachinemaker.com/news/indian-construction-industry-leads-digital-transformation-autodesk-report/)). | Japan's FY2026 focus is adoption by firms of any size |
| Performance measurement | Showing the benefit in rework, time, cost and safety, not only in detection accuracy | Weak. L&T cannot yet quantify the wider impact. No agency has published results. | Japan publishes yearly counts. The paper finds outcome reporting weak worldwide too. |
| Supply chain | Bringing subcontractors and small firms along | Not evidenced. All examples are public clients or one large contractor. | Singapore phases its mandate by project size so small projects follow later |

**What a firm or agency needs to put in place.**

1. **Pick the routine first.** Choose one recurring job, such as compaction acceptance, concrete pour inspection or PPE checks. Decide what a better result means before choosing a tool.
2. **Name an owner.** One person is responsible for the data and for acting on alerts. Without this, alerts are ignored.
3. **Write it into the contract.** State the data to be delivered, its format, who owns it and what happens when it shows a defect.
4. **Measure against a baseline.** Record rework, inspection time and non-conformance closure time before and after. This is the paper's KPI stack.
5. **Train at three levels.** Workers learn to work safely beside the system, engineers to read its output, and managers to decide from it.
6. **Use the safety committee.** The new safety code requires a safety committee where 250 or more building workers are employed ([PIB](https://www.pib.gov.in/FactsheetDetails.aspx?id=150475&NoteId=150475&ModuleId=16&reg=3&lang=2)). It is a ready-made body to review camera-based safety data with worker representatives present.
7. **Budget for the running cost.** Integration cost ranks among the biggest obstacles to AI in Indian construction ([Peter, 2023](https://link.springer.com/chapter/10.1007/978-981-99-3526-0_3)). Licences, data storage and upkeep continue after the pilot ends.

## Roadmap: adopting quickly, properly and safely

The fastest safe route for India is to repeat the highway model in every sector: the public client pilots, measures, then mandates by project size with dates announced in advance. This roadmap is my proposal, built from the evidence above. It is not government policy.

**Phase 1, years 0 to 2: standardise and measure.**

1. Publish a national information management standard aligned to ISO 19650, as the UK did. A national BIM standard is already under discussion.
2. Require digital quality records at handover on central projects of Rs 150 crore and above: machine-readable inspection logs and KPI records. The reference paper recommends exactly this.
3. Run routine-centred pilots in each sector under one shared protocol, and publish the results against a baseline.
4. Publish a yearly count of projects using each technology, as Japan does.
5. Fund pilots that pair a research institute with a contractor, to raise India's 1.2% industry co-authorship.

Gate to move on: at least one pilot per sector reports before-and-after results on rework, time or safety.

**Phase 2, years 2 to 5: mandate by size.**

1. Make BIM and a common data environment mandatory for public projects above a cost threshold, largest first, as Singapore phases by floor area.
2. Require sensor monitoring on new major bridges and on those rated poor.
3. Extend machine-aided construction from selected national highways to state highways.
4. Add single-platform digital building permit submission in the largest cities.
5. Add digital construction to engineering and diploma courses and to site supervisor training.

Gate to move on: mandated projects show results at least as good as the pilots, and small firms can comply at reasonable cost.

**Phase 3, years 5 to 10: scale and automate.**

1. Lower the thresholds so medium projects and state agencies are covered.
2. Introduce remote-operated and automated equipment for hazardous work.
3. Move from recording data to using it: link defect data to payment and to contractor rating.

**Doing it safely.**

- **A person signs off.** An AI system flags, and a named engineer accepts or rejects. This keeps responsibility clear and follows the "Do No Harm" principle of the AI governance guidelines.
- **Validate before relying.** Test each model on Indian site data and report where it fails, not only its best accuracy. The reference paper asks for failure modes to be reported.
- **Protect workers' data.** Site cameras and wearables collect personal data. Give notice and limit use to safety, in line with the data protection rules.
- **Keep people clear of machines.** Automated plant and drones need exclusion zones, trained operators and a method statement like any other hazardous activity.
- **Investigate the ground first.** Silkyara shows that no monitoring system makes up for a missing geotechnical investigation.
- **Plan for the workforce.** Use automation first on dangerous and repetitive tasks, and retrain workers for the new roles.

**Doing it quickly.**

- **Start where a duty already exists.** Inspection, survey and reporting are existing obligations, so tools that improve them need no new rules.
- **Use the public client's buying power.** A circular from one ministry moved machine-aided construction from pilot to requirement in about six months.
- **Announce dates early.** Singapore gave firms a year between its 30,000 and 5,000 sq m thresholds.

## Resources aspect

Money and computing power are now available in India. Skilled people, shared datasets and evidence of benefit are the scarce resources.

| Resource | What India has | What is short |
| --- | --- | --- |
| Finance | The Rs 1 lakh crore RDI scheme for private R&D. Growing venture funding for construction technology, on a weak source. | Money for running costs after a pilot. Finance for small contractors. |
| Computing | More than 38,000 GPUs in the IndiaAI shared facility, offered to start-ups and academia at an affordable rate | Nothing significant. Compute is no longer the main limit for research groups. |
| Data | GatiShakti's 23,493 GIS layers, NHAI's Data Lake of road condition data, the bridge management system, the DHARMA dam platform, and the AI Kosh dataset platform | Open, labelled construction datasets. The reference paper finds datasets are bespoke and rarely shared. Whether researchers can access NHAI data was not established. |
| People | A large research base, with 4,600 papers and many active NITs, IITs and private universities | Site-level digital skills. A survey of firms lists lack of digital skills and technical knowledge among the top barriers. |
| Equipment | GPS graders, intelligent compactors, survey vehicles and 3D printers are in use in India. CSIR-CRRI has built an indigenous AI-enabled survey vehicle. | Domestic manufacture and service support at scale were not assessed |
| Standards and approvals | BMTPC technical approval, validation by IITs, and ministry circulars | A national BIM and information standard. Design codes for 3D printed structures. |
| Evidence | Many announcements and pilots | Published before-and-after results. This is the scarcest resource of all. |

Two figures often quoted for this topic could not be verified and are left out: the size of the construction workforce, and the share of workers with no formal training. Sources give 51 to 71 million workers, and the 80% unskilled figure traces to an older KPMG study for NSDC that I could not open. Site connectivity and power supply were also not researched.

## Engineering aspect, and how engineering and management work together

The engineering job is to produce a measurement that can be trusted, and the management job is to make sure someone acts on it. Most failures come from doing the first without the second.

**What the engineering must deliver.**

- **Data capture that suits the site.** Sensors, cameras, drones and laser scanners must work in dust, heat, monsoon rain and poor light.
- **Calibration.** The MoRTH circular requires equipment calibration for machine-aided construction. An uncalibrated intelligent roller gives confident wrong numbers.
- **Models validated on local conditions.** Indian aggregates, mixes, soils and Himalayan geology differ from the data most published models were trained on.
- **Known accuracy and known failure cases.** IIT Madras reports about 81% accuracy for identifying building elements. An engineer must know which 19% fails before using it for payment.
- **Structural validation of new methods.** The 3D printed post office needed BMTPC approval and an IIT Madras design check before construction.
- **Common formats.** Data must pass between survey, design, site and asset management without re-entry. This is what BIM and a common data environment provide.

**How one measurement becomes a management result.** The example uses intelligent compaction on a highway, following the reference paper's three levels.

| Level | Question | Example measure | Who owns it |
| --- | --- | --- | --- |
| Task (engineering) | Does the tool measure correctly? | Compaction value per pass, checked against field density tests | Site engineer and equipment operator |
| Process (engineering and management) | Does it improve the routine? | Share of layers accepted first time. Hours from compaction to approval. | Quality manager and the client's engineer |
| System (management) | Does the project gain? | Rework cost, days saved, early pavement defects | Project manager and client |

**Rules for making the two work together.**

1. **Design from the routine backwards.** Start from the acceptance decision, work out what data it needs, then choose the instrument.
2. **Give every data stream a decision.** If no one will act differently because of a reading, do not collect it.
3. **Put engineers and managers in one review.** A weekly review of the data by the site engineer, quality manager and planner turns readings into action.
4. **Report in management units.** Translate detection accuracy into rework avoided and days saved. This is what gets a budget renewed.
5. **Keep the engineer accountable.** The system advises and the engineer certifies. Automation does not move professional responsibility.

## Evidence gaps and case-study options for the project

The biggest gap is that nobody in India has published what these technologies actually changed on a project, and that gap is the best opening for a BTech case study.

**Gaps found in this research.**

1. **No outcome evidence.** NHAI, MoRTH and L&T describe what they deployed, not the measured effect on rework, cost, time or safety.
2. **Research and industry do not meet.** Only 1.2% of India's AI civil engineering papers have a company co-author.
3. **Management research is thin.** BIM and construction integration is 2.2% of India's output. The three adoption studies found use small expert samples.
4. **Bridges and tunnels lag.** Research on monitoring exists but field use is rare.
5. **Small and medium contractors are invisible.** No source describes their adoption.
6. **State agencies were not covered.** This study looked at central programmes only.
7. **Workforce data is old or unverified.**
8. **The paper's three Indian studies are not identified.** They are in the authors' Excel file on [Mendeley Data](https://doi.org/10.17632/xyjz57bp8c.3), which I could not open. Download it and check them.

**Four ways to build the case study.**

| Option | What you would do | Data needed | Effort | Addresses gap |
| --- | --- | --- | --- | --- |
| A. India version of the paper | A systematic review of Indian studies using the paper's method: search, screen, then fill the technology and maturity matrix | Scopus or OpenAlex searches. No site access. | Medium | 3, 8 |
| B. One project in depth | Study one project that uses a technology named here, such as a highway package under machine-aided construction or a metro using BIM. Interview the engineers and apply the three-level KPI table. | Access to one site and three to five interviews | High, but the most original | 1 |
| C. Contractor survey | A questionnaire to local contractors and engineers on use and barriers, ranked by Relative Importance Index as in Peter (2023) | 40 or more responses | Medium | 5 |
| D. Small technical demonstration | Train a helmet or crack detector on photos from a local site. Report accuracy and also inspection time saved against manual checking. | A few hundred photos and an open-source model | Medium | 1, in miniature |

My recommendation is option B if your guide can arrange access to one site, with a short survey from option C alongside it. If no site is available, combine A and C. Either way, this report can serve as the literature review and national-context chapter.

**Before you submit anything based on this report.**

- [ ] Open each reference yourself and confirm the figure you quote
- [ ] Download the Mendeley dataset and identify the three Indian studies
- [ ] Rerun the OpenAlex count and record the date, since the numbers change
- [ ] Find a current official source for workforce size and skill levels
- [ ] Ask your guide to choose a case-study option

## References

Every source below was opened during this research on 16 November 2026. The tier shows how much weight each can carry. Peer-reviewed and government sources are the strongest. Press and vendor sources report claims that were not independently checked.

**Peer-reviewed and academic**

| Source | Tier |
| --- | --- |
| Dehbandi, R., Shirpourasl, Z. and Asnaashari, E. (2026). Digital transformation of construction quality management: Systematic review of adoption and governance. *Automation in Construction* 191, 107166. [doi:10.1016/j.autcon.2026.107166](https://doi.org/10.1016/j.autcon.2026.107166) | Peer-reviewed, read in full |
| Reja, V.K., Goyal, S., Varghese, K., Ravindran, B. and Ha, Q.P. (2024). Hybrid self-supervised learning-based architecture for construction progress monitoring. *Automation in Construction* 158, 105225. [IIT Madras page](https://rbcdsai.iitm.ac.in/publications/hybrid-self-supervised-learning-based/) | Peer-reviewed, abstract read |
| Reja, V.K., Varghese, K. and Ha, Q.P. (2022). Computer vision-based construction progress monitoring. *Automation in Construction* 138, 104245. [doi:10.1016/j.autcon.2022.104245](https://doi.org/10.1016/j.autcon.2022.104245) | Peer-reviewed, citation record only |
| Bajpai, A. and Misra, S.C. (2022). Barriers to implementing digitalization in the Indian construction industry. *International Journal of Quality and Reliability Management* 39(10), 2438-2464. [doi:10.1108/IJQRM-09-2020-0318](https://doi.org/10.1108/IJQRM-09-2020-0318) | Peer-reviewed, abstract read |
| Singh, A., Patil, A. and Pandey, S.K. (2026). Unravelling the blockades in implementing large language models in construction sector. *International Journal of Mathematical, Engineering and Management Sciences* 11(2), 991-1022. [Repository record](https://pure.jgu.edu.in/id/eprint/11181/) | Peer-reviewed, abstract read |
| Ametepey, S.O., Gyadu-Asiedu, O., Aigbavboa, C.O. and Addy, H. (2026). A bibliometric review of artificial neural networks in construction over the past decade (2015-2025). *Buildings* 16(12), 2470. [mdpi.com](https://www.mdpi.com/2075-5309/16/12/2470) | Peer-reviewed, abstract read |
| Peter, E.A.V. (2023). Analysis of factors influencing the use of artificial intelligence in the Indian construction industry. In *Building Construction and Technology*, Springer. [link.springer.com](https://link.springer.com/chapter/10.1007/978-981-99-3526-0_3) | Book chapter, abstract read |
| Dehbandi, R. (2026). Extraction dataset, version 3. Mendeley Data. [doi:10.17632/xyjz57bp8c.3](https://doi.org/10.17632/xyjz57bp8c.3) | Dataset, record seen, file not opened |
| OpenAlex. Publication counts queried through [api.openalex.org](https://api.openalex.org) on 16 November 2026 | Open bibliographic database, own analysis |
| IIT Kanpur. [Centre of Excellence in AI for Sustainable Cities](https://www.iitk.ac.in/centre-of-excellence-in-artificial-intelligence-for-sustainable-cities) | Institute page |

**Government of India**

| Source | Date |
| --- | --- |
| PIB. [Cabinet approves Research Development and Innovation Scheme](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2141130) | 1 Jul 2025 |
| PIB. [MeitY unveils India AI Governance Guidelines](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2186639) | 5 Nov 2025 |
| PIB. [Government makes the four Labour Codes effective](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2192463) | 21 Nov 2025 |
| PIB. [Factsheet on the OSH Code, 2020](https://www.pib.gov.in/FactsheetDetails.aspx?id=150475&NoteId=150475&ModuleId=16&reg=3&lang=2) | Nov 2025 |
| PIB. [Status of Light Houses in the country](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2149389) | 28 Jul 2025 |
| PIB. [IndiaAI Mission progress](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2227612) | 13 Feb 2026 |
| PIB. [Digital monitoring of rural water supply and sanitation services](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2226990) | 12 Feb 2026 |
| PIB. [PM GatiShakti National Master Plan press note](https://www.pib.gov.in/PressNoteDetails.aspx?id=160423&NoteId=160423&ModuleId=3&reg=38&lang=1) | 12 Oct 2026 |
| PIB. [25 Technology Innovation Hubs through NM-ICPS](https://www.pib.gov.in/PressReleasePage.aspx?PRID=1800518) | 23 Feb 2022 |
| Akashvani News. [NHAI to deploy 3D survey vehicles in 23 states](https://newsonair.gov.in/nhai-to-deploy-3d-survey-vehicles-in-23-states-for-ai-based-highway-monitoring/) | 22 Oct 2025 |
| NITI Frontier Tech Hub. [The technology behind India's first 3D-printed home](https://frontiertech.niti.gov.in/story/technology-behind-indias-first-printed-home) | Undated |

**Foreign governments**

| Source | Date |
| --- | --- |
| MLIT, Japan. [i-Construction 2.0 announcement](https://www.mlit.go.jp/report/press/kanbo08_hh_001085.html), in Japanese | 16 Apr 2024 |
| MLIT, Japan. [i-Construction 2.0 second-year progress](https://www.mlit.go.jp/report/press/kanbo08_hh_001324.html), in Japanese | 28 Apr 2026 |
| URA and BCA, Singapore. [Updates to CORENET X implementation plan](https://www.ura.gov.sg/guidelines/circulars/dc26-08/) | 23 Jul 2026 |
| BCA, Singapore. [Minister's speech at IBEW 2025](https://www1.bca.gov.sg/resources/newsroom/speech-by-minister-chee-hong-tat-at-the-international-built-environment-week--ibew--industry-and-awards-dinner-2025/) | 3 Sep 2025 |
| Xinhua, China state media. [China publishes five-year plan for construction industry](https://www.chinaservicesinfo.com/s/202201/27/WS62122eeb498e6a12c121f7b3/china-publishes-five-year-plan-for-construction-industry.html) | 27 Jan 2022 |

**Press, trade and industry**

| Source | Tier |
| --- | --- |
| NBM&CW. [Infra projects worth Rs 150 crore and above see Rs 5.66 lakh crore cost overrun](https://www.nbmcw.com/news/infra-projects-worth-rs-150-cr-see-rs-5-66-lakh-cr-cost-overrun-mospi-report.html) | Trade press reporting MoSPI |
| NBM&CW. [MoRTH issues directive for AI-machine controlled construction](https://www.nbmcw.com/news/morth-issues-directive-for-ai-machine-controlled-construction.html), 24 Jun 2025 | Trade press reporting a ministry circular |
| Indian Infrastructure. [MoRTH to introduce automated construction with AIMC technology](https://indianinfrastructure.com/2024/12/18/morth-to-introduce-automated-construction-with-aimc-technology/), 18 Dec 2024 | Trade press |
| Indian Infrastructure. [Building on data: increasing digitalisation across infrastructure sectors](https://indianinfrastructure.com/2026/08/10/building-on-data-increasing-digitalisation-across-infrastructure-sectors/), 10 Aug 2026 | Trade press |
| Construction World. [Twin Tracks](https://www.constructionworld.in/gold/transport-infrastructure/metro-rail-and-railways-infrastructure/twin-tracks/95231), 1 Aug 2026 | Trade press |
| Machine Maker. [AI and digital tech to cut construction costs by 2-3%: L&T](https://themachinemaker.com/news/ai-and-digital-tech-to-cut-construction-costs-by-2-3-lt/), 1 Oct 2024 | Press reporting a company's own claims |
| Machine Maker. [Indian construction industry leads digital transformation: Autodesk report](https://themachinemaker.com/news/indian-construction-industry-leads-digital-transformation-autodesk-report/), 1 Aug 2024 | Press reporting a vendor survey |
| L&T Construction. [3D concrete printing India's first post office building](https://www.lntecc.com/news-room/press-releases/l-t-is-3d-concrete-printing-india-s-first-post-office-building-in-bengaluru-april-2023), 11 Apr 2023 | Company press release |
| Newslaundry. [4 years, 170 collapses, 202 deaths: what's ailing India's bridges?](https://www.newslaundry.com/2025/07/29/4-years-170-collapses-202-deaths-whats-ailing-indias-bridges), 29 Jul 2025 | Press, own analysis of media reports |
| The Tribune. [Silkyara-Barkot tunnel collapse shows overhaul must in infra works, says report](https://www.tribuneindia.com/news/india/silkyara-collapse-shows-overhaul-must-in-infra-works-says-report-585877) | Press reporting a state inquiry |
| The Tribune. [Govt notifies Digital Personal Data Protection Rules](https://www.tribuneindia.com/news/business/govt-notifies-digital-personal-data-protection-rules-rollout-in-phases-specified-obligations-for-data-fiduciaries), 14 Nov 2025 | Press |
| IANS. [Digital tools, rehabilitation project enhance India's dam safety](https://ianslive.in/digital-tools-rehabilitation-project-enhance-indias-dam-safety-and-ageing-resilience--20260515160654), 15 May 2026 | News agency reporting a government statement |
| Devdiscourse. [CSIR-CRRI begins Platinum Jubilee with nationwide road technology rollout](https://www.devdiscourse.com/article/law-order/3951391-csir-crri-begins-platinum-jubilee-with-nationwide-road-technology-rollout), 16 Jul 2026 | Press |
| McKinsey Global Institute. [Reinventing construction through a productivity revolution](https://www.mckinsey.com/mgi/our-research/reinventing-construction-through-a-productivity-revolution), Feb 2017 | Consultancy research |
| Designing Buildings. [Information management mandate](https://www.designingbuildings.co.uk/wiki/Information_management_mandate) | Industry wiki, secondary |
| RICS. [Digitalisation in the Indian construction sector](https://rics.org/news-insights/wbef/digitalisation-in-the-indian-construction-sector-a-comparative-study-from-design-to-handover), 27 Aug 2024 | Professional body, webinar summary |
| ConTech Roundup. [ConTech India Virtual Summit announcement](https://contechroundup.substack.com/p/why-india-is-becoming-the-foundation), 2026 | Newsletter, weak |
