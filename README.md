# Ingest Tracker

The centralized tracker of progress made towards both the **data** and **workflow** standardization and upload process to the EMBER archives.

**Data standardization** includes but is not limited to reformatting file contents into [NWB](https://nwb.org/) and/or reorganizing dataset contents into compatible [BIDS](https://bids-specification.readthedocs.io/en/stable/) or [Psych-DS](https://psych-ds.github.io/) style.

**Workflow standardization** includes, but is not limited to, reformatting scripts and data flow throughout a pipeline in adherence to [STAMPED principles](https://myyoda.github.io/principles-paper/). This step also involves updating said scripts to operate on the standardized forms of the data.



## Internal Process

The process of managing and updating this tracker is as follows:

1. Issues shall be created for both the complete project collection and each grant number.
2. Issues shall be created from a template for each individual research project stemming from a particular grant; this template establishes the checklist used to track progress throughout the process.
3. The top issue description for grants shall include a hyperlink to their primary project page and/or other details relevant to the grant.
4. Parent/child issue relations shall be formed between individual research projects and their respective grant. This is a GitHub feature that facilitates such network linkage. Any progress achieved via the completion or closure of child issues is rendered on GitHub as 'percentage completion'.
5. All issues are collected and relayed through the centralized GitHub Project dashboard, which contains multiple views of progress tracking.
