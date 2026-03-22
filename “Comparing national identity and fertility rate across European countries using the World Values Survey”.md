You can approximate the WVS questions quite well using three families of open, authoritative, and directly accessible sources: the European Social Survey (ESS), official Istat surveys, and Eurobarometer‑based or peer‑reviewed demographic studies. [europeansocialsurvey](https://www.europeansocialsurvey.org/about/country-information/italy/italian)

***

## 1. National identity and belonging (proxies for E001, E003, G006)

### Sources and access

- **European Social Survey (ESS) – Data Portal**: open access to microdata and an online analysis tool for all rounds where Italy participated. [europeansocialsurvey](https://www.europeansocialsurvey.org/data-portal)
- **ESS country information – Italy**: overview (in Italian) of ESS themes and implementation in Italy. [europeansocialsurvey](https://www.europeansocialsurvey.org/about/country-information/italy/italian)
- **ESS core questionnaire on national, sub‑national and ethnic identity**: PDF with the exact wording and scales for identity items. [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/ESS_core_questionnaire_national_ethnic_ide.pdf)

All these are freely downloadable; microdata require only a free registration on the ESS portal. [europeansocialsurvey](https://www.europeansocialsurvey.org/data-portal)

### What you can measure (parallel to WVS)

The ESS core questionnaire includes items such as: [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/ESS_core_questionnaire_national_ethnic_ide.pdf)

- Strength of attachment to country, region, city/town, Europe (e.g., “How close do you feel to…” with ordered response scales).  
- National and ethnic identity questions (how people see their national vs ethnic belonging).  

From these you can construct:

- A measure of **strength of national identity** (conceptually close to WVS G006 “how important is national identity to you”).  
- A **hierarchy of identifications** (local vs national vs European) that works as a proxy for WVS E003 (national pride vs “citizen of the world”), even though the wording is not identical. [europeansocialsurvey](https://www.europeansocialsurvey.org/data-portal)

How to verify:

1. Use the ESS Data Portal. [europeansocialsurvey](https://www.europeansocialsurvey.org/data-portal)
2. Select a round (e.g., Round 6 or 7) and the countries: Italy, France, Sweden, Germany, Spain, Poland.  
3. Add the identity variables as defined in the core questionnaire PDF. [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/ESS_core_questionnaire_national_ethnic_ide.pdf)
4. Generate percentage distributions or download the microdata and reproduce the distributions in your own software.

***

## 2. National pride (“proud to be…”)

There is no single open source that reproduces WVS E001 exactly, but there are three relevant avenues:

- Some ESS modules include items on **pride or evaluation of one’s country**, which can function as proxies; the exact presence and wording need to be checked round‑by‑round in the ESS questionnaires. [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/ESS_core_questionnaire_national_ethnic_ide.pdf)
- Journalistic or think‑tank surveys sometimes ask explicit questions on **“pride in one’s country”** and what people are proud of (e.g., history, culture, economy), but they rarely have long time series and often lack full technical documentation. [en.protothema](https://en.protothema.gr/2026/02/19/what-the-peoples-are-proud-of-greeks-proud-of-history-italians-proud-of-culture-and-turks-proud-of-their-patriotism/)
- For a rigorous approach, you can combine **strong national identity** and **positive evaluation of the country** from ESS or ISSP datasets as operational proxies for “national pride”, making sure the scales and samples are comparable across countries. [europeansocialsurvey](https://www.europeansocialsurvey.org/data-portal)

For each source:

- Always check the **questionnaire PDF** (exact wording, scale, population).  
- Check whether the module was **fielded in all countries** you want to compare.  
- Prefer microdata or official online tables over secondary summaries to verify percentages.

***

## 3. Happiness and subjective wellbeing (proxy for A008)

### Key sources

- **ESS wellbeing modules**: several rounds include batteries on personal and social wellbeing, with items close to happiness and life satisfaction. [europeansocialsurvey](https://www.europeansocialsurvey.org/findings/europeans-wellbeing/measuring-wellbeing)
- **Report “Il benessere personale e sociale degli europei”** (in Italian): ESS report explaining how wellbeing was measured and which items were used (e.g., “I felt happy”, “I enjoyed life”, etc.). [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/TL5_Wellbeing-Italian.pdf)

These indicators are conceptually very close to:

- WVS A008 (“feeling of happiness”) as a **single‑item proxy for life satisfaction**.  
- Broader multi‑item indices of **subjective wellbeing**. [europeansocialsurvey](https://www.europeansocialsurvey.org/findings/europeans-wellbeing/measuring-wellbeing)

How to cross‑check:

1. Use the wellbeing report to identify the exact items and scales (Likert scale, reference period, etc.). [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/TL5_Wellbeing-Italian.pdf)
2. On the ESS Data Portal, locate those variables for a given round and extract distributions for Italy, France, Sweden, Germany, Spain, Poland. [europeansocialsurvey](https://www.europeansocialsurvey.org/findings/europeans-wellbeing/drivers-wellbeing)
3. Compare your computed percentages with any summary statistics or graphs in ESS publications to ensure consistency.

***

## 4. Family, children, and fertility intentions (proxies for D054)

Here open official statistics and comparative demographic studies are especially useful.

### 4.1. Istat – fertility intentions in Italy

- **Istat “Fertility intentions – Year 2024”**: official press release (in English) with detailed figures on fertility intentions in Italy. [istat](https://www.istat.it/en/press-release/fertility-intentions-year-2024/)
- Main findings include:  
  - In 2024, **21.2%** of people aged 18–49 intend to have a child within the next three years, down from 25.0% in 2003. [istat](https://www.istat.it/en/press-release/fertility-intentions-year-2024/)
  - Among those with one child, about one third of men and slightly more than one quarter of women intend to have another child in the short term. [istat](https://www.istat.it/en/press-release/fertility-intentions-year-2024/)
  - Among those with no children, intentions differ by sex (lower for men, higher for women); among those with two or more children, intentions to have more are very low. [istat](https://www.istat.it/en/press-release/fertility-intentions-year-2024/)

Although this does not ask whether “having children is justifiable”, it directly measures **intended fertility**, which is even closer to actual demographic behavior than a normative attitude item. [istat](https://www.istat.it/en/press-release/fertility-intentions-year-2024/)

To validate:

- Download the press release and any attached tables; check that the percentages in the text match the tabulated data. [istat](https://www.istat.it/en/press-release/fertility-intentions-year-2024/)

### 4.2. Eurobarometer‑based evidence on family ideals

- The working paper **“Childbearing Preferences and Family Issues in Europe”** synthesizes results from a Eurobarometer on family and fertility values, covering Italy, France, Spain, Germany, and Nordic countries. [apfn.com](https://apfn.com.pt/Actividades/2008/seminario/bibliografia/Europa/Childbearing%20preferences%20and%20famly%20issues%20in%20Europe%20-%20Eurobarometer.pdf)
- Key points:  
  - In Nordic countries (including Sweden), **ideals of three or more children** are significantly more common.  
  - In Italy, Spain, and Germany, the **ideal number of children** is on average lower, with two‑child ideals dominating. [apfn.com](https://apfn.com.pt/Actividades/2008/seminario/bibliografia/Europa/Childbearing%20preferences%20and%20famly%20issues%20in%20Europe%20-%20Eurobarometer.pdf)
  - A non‑trivial share of respondents choose “no children” as ideal, even in the early 2000s. [apfn.com](https://apfn.com.pt/Actividades/2008/seminario/bibliografia/Europa/Childbearing%20preferences%20and%20famly%20issues%20in%20Europe%20-%20Eurobarometer.pdf)

This does not mirror WVS D054 word for word, but it provides **ideal family size and acceptance of childlessness**, which are directly related to value orientations toward children. [apfn.com](https://apfn.com.pt/Actividades/2008/seminario/bibliografia/Europa/Childbearing%20preferences%20and%20famly%20issues%20in%20Europe%20-%20Eurobarometer.pdf)

Quality checks:

- The paper documents that the data come from an official Eurobarometer survey, which uses standard EU sampling and methodology. [apfn.com](https://apfn.com.pt/Actividades/2008/seminario/bibliografia/Europa/Childbearing%20preferences%20and%20famly%20issues%20in%20Europe%20-%20Eurobarometer.pdf)

### 4.3. Italy‑specific research on fertility preferences

- The article **“Trends in fertility preferences among Italian young adults”** uses representative survey data to show that the share of Italian young adults who **do not want children** or do not expect to have them over their lifetime has increased between 2012 and 2022. [tandfonline](https://www.tandfonline.com/doi/full/10.1080/00324728.2025.2542833)
- Core result: rising **childfree preferences**, especially among women and younger cohorts, against a backdrop of already low actual fertility. [tandfonline](https://www.tandfonline.com/doi/full/10.1080/00324728.2025.2542833)

The article is peer‑reviewed and methodologically transparent; even if you cannot access the raw data directly, the estimates and trends in the paper are reliable for descriptive purposes. [tandfonline](https://www.tandfonline.com/doi/full/10.1080/00324728.2025.2542833)

### 4.4. Comparative context of lowest‑low fertility

- The paper **“Lowest‑Low Fertility in Europe: Exploring the Causes and Consequences”** situates Italy and Spain as archetypal cases of “lowest‑low” fertility and discusses how **structural constraints** (labour market, welfare regime, housing, gender norms) interact with **family preferences and postponement of childbearing**. [ipss.go](https://www.ipss.go.jp/webj-ad/webjournal.files/population/2008_4/01billari.pdf)
- It uses international microdata and standard demographic indicators (e.g., TFR), connecting them to value‑related factors such as acceptance of childlessness and ideal family size. [ipss.go](https://www.ipss.go.jp/webj-ad/webjournal.files/population/2008_4/01billari.pdf)

Again, this is more interpretive but still grounded in transparent data sources. [ipss.go](https://www.ipss.go.jp/webj-ad/webjournal.files/population/2008_4/01billari.pdf)

***

## 5. Linking happiness and fertility (A008 + D054 logic)

If you want to replicate the WVS logic of combining happiness with fertility‑related variables:

- ESS has a project summarized as **“Drivers of Wellbeing”** that uses multi‑country data to analyse how **subjective wellbeing** (happiness, life satisfaction, positive affect) relates to various life domains, including family and children. [europeansocialsurvey](https://www.europeansocialsurvey.org/findings/europeans-wellbeing/drivers-wellbeing)
- With ESS microdata you can directly cross‑tabulate or model the relationship between happiness and:  
  - Number of children,  
  - Partnership status,  
  - Age and cohort,  
  - Other family‑related variables. [europeansocialsurvey](https://www.europeansocialsurvey.org/findings/europeans-wellbeing/measuring-wellbeing)

This allows you to implement analyses very close in spirit to what you would have done with WVS A008 and D054, but with a different dataset.

***

## 6. How to build a WVS‑style dataset from open sources

To create a WVS‑style analytical framework using only open, directly accessible and authoritative sources:

1. **National identity and belonging**  
   - Use ESS core identity variables for country, region, and Europe as proxies for WVS E003 and G006. [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/ESS_core_questionnaire_national_ethnic_ide.pdf)

2. **Happiness / life satisfaction**  
   - Use ESS happiness and life satisfaction items from the wellbeing modules as proxies for A008. [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/TL5_Wellbeing-Italian.pdf)

3. **Family, children, reproductive values and intentions**  
   - Use Istat fertility‑intentions indicators for Italy. [istat](https://www.istat.it/en/press-release/fertility-intentions-year-2024/)
   - Use Eurobarometer‑based “Childbearing Preferences and Family Issues in Europe” for ideal number of children and openness to childlessness in Italy, France, Sweden, Germany, Spain. [apfn.com](https://apfn.com.pt/Actividades/2008/seminario/bibliografia/Europa/Childbearing%20preferences%20and%20famly%20issues%20in%20Europe%20-%20Eurobarometer.pdf)
   - Use peer‑reviewed studies on Italy (and where available, on other countries) to refine the interpretation of trends. [tandfonline](https://www.tandfonline.com/doi/full/10.1080/00324728.2025.2542833)

4. **Verification procedure, source by source**  
   - Always start from the **original questionnaire or technical report** for wording, scales, and sampling. [europeansocialsurvey](https://www.europeansocialsurvey.org/sites/default/files/2023-06/TL5_Wellbeing-Italian.pdf)
   - Use **official portals** (ESS Data Portal, Istat website, Eurobarometer documentation) to obtain actual numbers and verify any secondary summaries. [europeansocialsurvey](https://www.europeansocialsurvey.org/data-portal)
   - When using academic papers, check that the data sources are clearly identified (ESS, Eurobarometer, national statistical offices) and that the reported estimates match what you get when you replicate the analysis from the underlying public datasets.  

If you like, next I can draft a concrete “variable grid” in English (variable name, source, question text, scale, country coverage) that you can use as a blueprint for data extraction and recoding in R or Python.