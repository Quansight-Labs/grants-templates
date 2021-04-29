# CZI cycle - 4 proposal template

- [CZI cycle - 4 proposal template](#czi-cycle---4-proposal-template)
  - [:link: Useful links](#link-useful-links)
  - [:gear: Using this template](#gear-using-this-template)
    - [:package: Importing into Overleaf](#package-importing-into-overleaf)
    - [:pencil: Filling in the proposal](#pencil-filling-in-the-proposal)
  - [:floppy_disk: Other documents](#floppy_disk-other-documents)
    - [:money_with_wings: Instructions for budget (required)](#money_with_wings-instructions-for-budget-required)
    - [:woman_technologist: Applicant CV  - PI only (required)](#woman_technologist-applicant-cv----pi-only-required)
  - [](#)
    - [:paperclip: Instructions for supporting attachments (optional)](#paperclip-instructions-for-supporting-attachments-optional)

## :link: Useful links

- [CZI EOSS requirements](https://chanzuckerberg.com/rfa/essential-open-source-software-for-science/)

- [Institutional approval form](https://apply.chanzuckerberg.com/protected/resource/eyJoZnJlIjogOTQ1ODEyNDksICJ2cSI6IDE2MDQ1Nn0/)

## :gear: Using this template

### :package: Importing into Overleaf

The best way to use and share this template in a collaborative way is to import it to Overleaf.

1. Head to [overleaf.com](overleaf.com) and login or create an account if needed
2. Click on the **New project** button on the top left corner
3. Click on import from GitHub. Note you will need to link your Overleaf account to your GitHub account.
4. Choose: `grants-templates` from the `Quansight Labs organisation`
5. You should see the `main_proposal.tex` document open and compiled.

:warning: If you want to keep your proposal in version control and sync with GitHub you need to fork this repo first and then follow the importing instructions above.

### :pencil: Filling in the proposal

- The `main_proposal.tex` file will be your main document which imports all the other pieces of the poposal.
- The full proposal sections are in `cycle_4.tex`. We have indicated which sections are already prefilled with details from the LOI  
- You also need to provide details on each of the projects involved in the proposal. The easiest way is to make a copy of the `project.tex` file and include it in the `main_proposal.tex` file. For example if your proposal covers JupyterHub and Jupyterlab:

```latex
\include{JupyterHub}
\include{JupyterLab}
```

If you need to add references add them to the `references.bib` file and uncomment the bibliography line in the `main_proposal.tex` document.

## :floppy_disk: Other documents

### :money_with_wings: Instructions for budget (required)

Upload in PDF format; budgets can be uploaded in a combined single PDF or one PDF for each software project (one page per software project maximum)

Description of the costs to be funded by this grant at a high level and in narrative or tabular form, outlining costs for personnel (including names, if known), supplies, equipment, travel, meetings/hackathons/sprints, subcontracts, other costs, and up to 15% indirect costs (excluding equipment and subcontracts).

Indirect costs are limited to up to 15% of direct costs and are included within the annual budget total. Indirect costs may not be assessed on capital equipment or subcontracts, but subcontractors may include up to 15% indirect costs of their direct costs.

Budget should be requested in US dollars.

International grantees must use all grant funds exclusively for activities conducted outside the United States of America. Travel expenses to the United States (including round-trip tickets) should not be covered from the requested grant funds.

Application budgets must reflect the actual needs of the proposal. The Chan Zuckerberg Initiative will work closely with successful applicants to arrive at a mutually acceptable budget after review.

:warning: For Quansight Labs folks: Tania and Ralf will be sharing the budget template with you.

### :woman_technologist: Applicant CV  - PI only (required)

Upload in PDF format; include current and recent employment, education history, and references to any major publications, software contributions, or other relevant outputs (maximum of two pages)

## 
### :paperclip: Instructions for supporting attachments (optional)

Upload in PDF format; attachments should be uploaded in a combined single PDF. Include up to three pages of additional information. This section can include figures, charts and tables, references for the proposal, or any additional material in support of the proposal (maximum of three pages). Uploading any additional information is completely optional and not required.