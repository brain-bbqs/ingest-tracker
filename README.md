All issues on this repository are tracked and viewable through the [BBQS Ingest Dashboard](https://github.com/orgs/brain-bbqs/projects/2).



# Ingest Tracker

The centralized tracker of progress made towards both the **data** and **workflow** standardization and upload process to the EMBER archives.

**Data standardization** includes but is not limited to reformatting file contents into [NWB](https://nwb.org/) and/or reorganizing dataset contents into compatible [BIDS](https://bids-specification.readthedocs.io/en/stable/) or [Psych-DS](https://psych-ds.github.io/) style.

**Workflow standardization** includes, but is not limited to, reformatting scripts and data flow throughout a pipeline in adherence to [STAMPED principles](https://myyoda.github.io/principles-paper/). This step also involves updating said scripts to operate on the standardized forms of the data.



## Internal Process

The process for managing and updating this tracker is as follows:

1. A separate issue shall be created for each new grant number, as well as for each project associated with those grants.
2. Grant issue descriptions shall include a hyperlink to the primary project page and any other relevant details.
3. New project issues shall be created from the established template, which includes a checklist used to track progress throughout the ingestion process.<br>
  3a. Answers to questions on the checklist, links to more information, and any additional details per section may all be added at an additional level of indentation beneath the checkbox as a new item.<br><br>
  For example,
  ```
  - [x] Stage of process (published, review, collection, design):
      - Published
      - https://www.nature.com/articles/s41562-025-02119-3
  ```
5. Parent/child issue relations shall be formed between individual research projects and their respective grants. This GitHub feature facilitates network linkage, and any progress achieved through the completion or closure of child issues is rendered as "percentage completion."
6. All issues are collected and displayed through the centralized [GitHub Project dashboard](https://github.com/orgs/brain-bbqs/projects/2), which offers multiple views for tracking progress. Users can navigate through these views and expand the details of any project issue to see where it stands in the ingestion process.
