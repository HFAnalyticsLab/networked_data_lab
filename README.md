<img src="img/ndlbanner.png" width="405" height="96">

## The Networked Data Lab on GitHub

Welcome to the Networked Data Lab's central landing page on GitHub, where we all our code repositories and other resources are referenced in one place.

### :link: What is the Networked Data Lab?

The [Networked Data Lab](https://www.health.org.uk/funding-and-partnerships/our-partnerships/the-networked-data-lab) is a collaborative network of analytical teams across the UK working together using linked datasets on key issues facing health and care services today. We started in 2020, and we work closely with our five partners across the UK who are embedded within their local health and care systems and have detailed knowledge of both their local health and care environments and their linked data sets. Our five teams work on a new topic approximately every year, with each topic resulting in outputs (including, but not limited to, publications).

#### Our labs

<img src="img/partners-map.png" width="18%" height="18%" align="left"/>
<ul>
  <li>The <a href="https://www.abdn.ac.uk/achds/">Aberdeen Centre for Health Data Science</a> (ACHDS) which includes <a href="https://www.nhsgrampian.org/">NHS Grampian</a>
 and the <a href="https://www.aberdeen-isc.ac.uk/">University of Aberdeen</a></li>
  <li><a href="https://www.leedsccg.nhs.uk/">Leeds CCG</a> and <a href="https://www.leeds.gov.uk/">Leeds City Council</a></li>
  <li><a href="https://phw.nhs.wales/">Public Health Wales</a> (PHW), <a href="https://dhcw.nhs.wales/">Digital Health and Care Wales</a>, <a href="https://saildatabank.com/">Swansea University</a> (SAIL Databank) and <a href="https://socialcare.wales/">Social Care Wales</a> (SCW)</li>
  <li><a href="https://imperialcollegehealthpartners.com/">Imperial College Health Partners</a> (ICHP), <a href="https://www.imperial.ac.uk/global-health-innovation/">Institute of Global Health Innovation</a> (IGHI), <a href="https://www.imperial.ac.uk/">Imperial College London</a> (ICL), and <a href="https://www.nwlondonics.nhs.uk/">North West London CCGs</a></li>
  <li><a href="https://www.liverpoolccg.nhs.uk/">Liverpool CCG</a> and <a href="https://www.wirralccg.nhs.uk/healthy-wirral/">Healthy Wirral Partnership</a></li>
</ul>
<br clear="left"/> 

#### Our approach to open analytics

As a network, we aim to work as openly and collaboratively as possible. This includes publicly sharing our analysis plans (which includes our methodology for each analysis), codes used in analyses (SQL and R) and other analytical resources (such as clinical code lists or data extraction pipelines). A limitation is that many of the codes used by our partners (and shared here) are intented for use on patient healthcare records, which we cannot make publicly available because of ethical considerations. However, these codes can be used by other teams who have secured access to similar patient records.

### :one: Topic 1: COVID-19 and the clinically extremely vulnerable (CEV) population (2020-2021)

**Central analyses**

These are analyses either using open data, or where data definitions were standardised across all five labs to enable five identical analyses using secure-access health care records.

- Regional variation in the Shielded Patient List (NHS Digital Open data) - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/COVID19_Shielding), R codes for report and choropleth maps - :newspaper: [publication link](https://www.health.org.uk/news-and-comment/charts-and-infographics/understanding-the-needs-and-experiences-of-those-most-clinic)
- Demographic characteristics of CEV people - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output1_Demographics), R codes for report and open data release of aggregate statistics - :newspaper: [publication link](https://www.health.org.uk/news-and-comment/charts-and-infographics/exploring-demographic-variation-in-groups-advised-to-shield)
- Comorbidities of CEV people using hospital admissions data - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output2_Morbidity), R codes for analysis
- The impact of COVID-19 on hospital activity by CEV people - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output3_Hospital_care_CEV), R codes for analysis - :newspaper: [publication link](https://www.health.org.uk/news-and-comment/charts-and-infographics/hospital-use-clinically-extremely-vulnerable-population)
- Briefing paper: Assessing the impact of COVID-19 on the clinically extremely vulnerable population - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output3_Hospital_care_CEV), R codes for analysis - :newspaper: [publication link](https://www.health.org.uk/publications/reports/assessing-the-impact-of-covid-19-on-the-clinically-extremely-vulnerable-population)

**Satellite analyses by labs**

These are analyses done independently by each of the labs, without the need to adopt common definitions and approaches.

- Grampian: Identification and changes in healthcare while self-isolating (shielding) during the coronavirus pandemic - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output4_Grampian), Analysis plan and pre-print - :newspaper: [publication pre-print link](https://www.medrxiv.org/content/10.1101/2021.09.09.21263026v1)
- Leeds: CEV people, frailty and use of adult social care services - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output4_Leeds), Analysis plan and Rmarkdown analysis file
- Liverpool and Wirral: Mental health of CEV people - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output4_LiverpoolWirral), Analysis plan and R analysis files
- Wales: The impact of COVID-19 on levels of health care use and mental health of CEV people - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output4_Wales), Analysis plan and Rmarkdown analysis file - :newspaper: [publication link](https://phw.nhs.wales/services-and-teams/knowledge-directorate/research-and-evaluation/publications/covid-19-in-wales-the-impact-on-levels-of-health-care-use-and-mental-health-of-the-clinically-extremely-vulnerable/)
- North West London: Mental health of CEV people - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Output4_NWLondon), Analysis plan and Rmarkdown analysis file

### :two: Topic 2: Children and young people's mental health (2021-2022)

**Resources for the analytical community**

- A library of clinical code lists for mental health conditions - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/Mental-health-code-lists), Links to external code list repositories
- Data extraction and cleaning pipeline for the secure-access version of NHS Digital's Mental Health Services Dataset (MHSDS) - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/MHSDS-cleaning-pipeline), SQL codes
- Web-scraping and data cleaning pipeline for NHS Digital's monthly MHSDS statistics - :file_folder: [GitHub](https://github.com/sg-peytrignet/MHSDS-pipeline), R codes to extract monthly data, compile into a longitudinal dataset and create a visualization dashboard 

**Open data analyses**

- Children and young people’s mental health: COVID-19 and the road ahead - analysis using open data from NHS Digital and Health Education England - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/MH-services-long-chart), R analysis files - :newspaper: [publication link](https://www.health.org.uk/news-and-comment/charts-and-infographics/children-and-young-people-s-mental-health)

**Satellite analyses by labs**

These are analyses done independently by each of the labs.

- Grampian: Prescribing patterns of mental health medications and referrals to CAMHS - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_CYPMH_Grampian), Analysis plan, codes and report
- Leeds: Patterns in the use of mental health services among children and young people in Leeds - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_CYPMH_Leeds), Analysis plan, codes and report
- Liverpool and Wirral: Children and young people's mental Health in Liverpool and Wirral - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_CYPMH_Liverpool_Wirral), Analysis plan, codes and report
- Wales: Trends in mental health crisis events among children and young people across the acute health care system in Wales - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_CYPMH_Wales), Analysis plan, codes and report
- North West London: Impact of the COVID-19 pandemic on the mental health of
the children and young people population in North West
London - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_CYPMH_North_West_London), Analysis plan, codes and report

### :three: Topic 3: Unpaid carers and their access to support (2022-2023)

**Analysis of survey and open data sources** 

- Understanding unpaid carers and their access to support - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/ndl-unpaid-carers-open-data/tree/main), R analysis files - 📰 [publication link](https://www.health.org.uk/publications/long-reads/understanding-unpaid-carers-and-their-access-to-support) 

**Resources for analysts** 

- We are currently doing an exploratory analysis on unpaid carers recorded in NHS England's GP core contract data. Here we provide the code for a pipeline that downloads, processes and transforms the GP Core Contract data on unpaid carers registered by GP practice to a local authority level, then links and compares this transformed data to the counts of unpaid carers per local authority from the 2021 census - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/gp-contract-unpaid-carers)

- We have uploaded a [data-sharing agreement](https://github.com/HFAnalyticsLab/ndl-unpaid-carers/tree/main/Data%20sharing%20agreements) template for users to draw from, courtesy of the West Yorkshire Integrated Care Board. 

**Central analyses** 

These are analyses where data definitions were standardised across all labs to enable identical analyses using secure-access health care records. 

- Long read: Can you tell we care?: identifying unpaid carers using local authority and GP records - 📁 [GitHub](https://github.com/HFAnalyticsLab/ndl-unpaid-carers-central-analyses/tree/main), R codes for analysis - 📰 [publication link]  

**Satellite analyses by labs** 

These are analyses done independently by each of the labs: 

- Leeds: Analysis of unpaid carers' needs and utilisation of services in Leeds - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Unpaid_Carers_Leeds), Analysis plan, codes and report
- Liverpool and Wirral: Analysis of unpaid carers in Liverpool and Wirral - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Unpaid_Carers_Liverpool_and_Wirral), Analysis plan, codes and report
- Wales: Analysis of demographics, health and health service use of unpaid carers at a local authority level in Wales - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Unpaid_Carers_Wales), Analysis plan and codes (report forthcoming)
- North West London: Analysis on the impact of being an unpaid carer on health conditions and healthcare access in North West London - :file_folder: [GitHub](https://github.com/HFAnalyticsLab/NDL_Unpaid_Carers_NWL), Analysis plan, codes and report
