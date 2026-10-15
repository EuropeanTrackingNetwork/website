---
title: Data policy & citation guidelines # TODO: changed
background: /assets/backgrounds/adobe_stock_307954864.jpg
permalink: /data-policy/
toc: true
---

## Data policy <!-- TODO: lowercase -->

[Download the ETN Data Policy](https://www.lifewatch.be/etn/assets/docs/ETN-DataPolicy.pdf){:.btn .btn-primary} (updated 2025)<!-- TODO: changed text and to button-->

- **Data that is automatically public:** metadata of receivers and tags, metadata of deployments and their recovery events, project level metadata regarding Animal and Network Projects (title, abstract, contacts, etc.), all metadata and detections of Animal Projects without embargo.
- **Data that can be embargoed:** all Animal Project data, including metadata related to tagging (location, capture datetime, etc.), animal morphology (scientific name, length, etc.) and animal detections. A request for embargo is possible for Animal Project data and can be specified when creating an animal project via the ETN Project Template. Embargo period is set for 2 years after the reported project end date for projects with duration of 4 years. If the battery lifetime of the tag extends the project end date, then embargo is set to 2 years after the expiry day of the tag. In exceptional cases, a deployment embargo can be requested, with the [ETN Coregroup](/who-we-are) reviewing requests.
- **Data available to users with access to a network project:** detections of tags released by other projects (also from those that do not belong to the receiver owner) including animal scientific name and Animal Project code, unknown tag detections collected by their receivers, detections of built-in receiver tags, detections of known non-animal (sentinel) tags collected by their receivers.
- **Data available to users with access to an animal project:** all detections, from any Network Project, which have been matched to their tagged animals.

## Citation guidelines

The following citation guidelines are for ETN members, ETN data owners, publishers and any other user of ETN data to ensure that ETN data are cited properly, as mentioned in the [ETN Data Policy](https://www.lifewatch.be/etn/assets/docs/ETN-DataPolicy.pdf).

These citation guidelines indicate how and when to cite ETN (data), especially in scientific publications. However, **if you particularly relied on someone's data or expertise for your research, you should consider them for co-authorship**. Please check the widely applied [Vancouver Recommendations](https://www.forskningsetikk.no/en/resources/the-research-ethics-library/integrity-and-collegiality/co-authorship/) for co-authorship.

### Recommendations <!-- TODO: changed -->

1. **Mandatory**: cite [ETN](https://www.vliz.be/en/imis?module=dataset&dasid=5912) as a whole (see below).<!-- TODO: do we need the link here? -->
2. **Mandatory**: Invite dataset collaborator (for example, acoustic receiver owners or groups that supplied detections or performed essential data processing) as co-authors when their contributions substantially enabled the research.
3. **Mandatory**: Add the list of Animal Project datasets (DOI) and list of Network Projects (MarineInfo-urls) to your supplementary materials (as a table). If the list is very short, consider citing the datasets in your references.
4. **Recommended**: Deposit the (subset of) data you used on a research repository (like [Zenodo](https://zenodo.org/)) and cite it (see for example: <https://doi.org/10.5281/zenodo.15260539>). This increases reproducibility. If your study involves a single animal project, [contact ETN](mailto:etn@lifewatch.be) to publish it through MarineInfo/MDA.
5. **Recommended**: Cite the etn R package (if used for data retrieval).<!-- TODO: email different -->

### Citing ETN projects <!-- TODO: changed -->

Citation of a project, as provided by the data owner can be found in the project's MarineInfo metadata record. In the case that a DOI is available for a project, the DOI URL should be included (See [Where can I find the citation of an ETN project?](https://europeantrackingnetwork.org/en/etn-project-citation-info)).<!-- TODO: check link-->

Example of an ETN project's MarineInfo record with a DOI: <https://doi.org/10.14284/437>.

#### Citing in text <!-- TODO: changed -->

To cite projects within the text, it is best to include, apart from the reference, the ETN project code as shown in the MarineInfo metadata record. For example:

> … included detections from the projects SWIMWAY (Edwards 2021), Apelafico (Debusshere et al. 2023), FISHINTEL (Sheehan et al. 2021) and 2010_PHD_REUBENS (Reubens et al. 2020) …

#### Reference list

To cite projects in the reference list, use the citation of the MarineInfo metadata record including the URL of the record, preferably along with the date of data access/download. If the project has a DOI, use that instead of the URL. For example, the matching full references for the in-text citations above:

<!-- TODO: formatting of citations changed -->

> - Edwards, J.E. (2021) Wadden tools—Swimway Wadden Sea. <https://marineinfo.org/id/dataset/8030> (Accessed: `date-of-access`).
> - Debusschere E, Hubert J, Berges B, Muñiz C, Reubens J, Demuynck J, Deneudt K, Slabbekoorn H (2023) APELAFICO: Acoustic Ecology of Pelagic Fish Communities. <https://marineinfo.org/id/dataset/7858> (Accessed: `date-of-access`).
> - Sheehan E, Couturier L, Hawkes L, Hooper T, Horton T, Laurans M, Muñiz C, Reubens J, Stamp T, Witt M, Woillez M (2021) FISHINTEL: Fisheries Innovation for sustainable Shared INTerchannEL resources. <https://marineinfo.org/doc/dataset/7881> (Accessed: `date-of-access`).
> - Reubens J, Degraer S, Desmet P, Moens T, Reyserhove L, Vincx M (2020) 2010_PHD_REUBENS - Acoustic telemetry data for Atlantic cod (Gadus morhua) in the C-Power wind farm in the southern North Sea (Belgium). Marine Data Archive. <https://doi.org/10.14284/437>. (Accessed: `date-of-access`).

#### Data availability statement

While all projects should be cited, not all may have public data. You can clarify that in the text with:

> The datasets generated/analyzed during the current study are not publicly available due to `REASON(S)` but are stored at ETN (<https://www.lifewatch.be/etn/>) under the project `PROJECT_CODE(S)` and can be made available by the author upon reasonable request.

### Citing ETN <!-- TODO: changed -->

The following examples can be used to cite the general use of ETN. This citation should be included in any publication that makes use of ETN data. Note that citing ETN (in general) is not an accepted alternative for citing ETN projects.

#### Citing in text <!-- TODO: changed -->

> Data were derived from the European Tracking Network database (<http://www.lifewatch.be/etn/>), developed by the Flanders Marine Institute (VLIZ) as part of the Flemish contribution to LifeWatch.

#### Reference list

> European Tracking Network – Data Platform. Flanders Marine Institute (VLIZ), `year-of-data-download`, `data-access-url`, accessed `date-of-access`.

### Citing the etn R package <!-- TODO: changed + citation updated -->

> Huybrechts P, Desmet P, Oldoni D, Van Hoey S (2025) etn: Access Data from the European Tracking Network. R package version 2.2.2, <https://inbo.github.io/etn/>, <https://doi.org/10.5281/zenodo.15235747>.

## Data use <!-- TODO: this seems odd here-->

- All individuals that make use of the ETN Data for any type of publications, products or commercial applications shall inform ETN (<etn@lifewatch.be>) of these as soon as practical.
- All individuals who use ETN Data agree and acknowledge that neither ETN nor the Data Collaborator is liable for any inaccuracies in the ETN Data.
- All Unrestricted Data held by ETN will be routinely reported to international biodiversity facilities such as the [Ocean Biogeographic Information System](https://obis.org/) and [Global Biodiversity Information Facility](https://www.gbif.org/).
- Restricted Data is not automatically distributed to international biodiversity facilities
