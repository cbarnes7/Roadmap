# Roadmap

Near term

- [X] machinedatahub.ai site live
- [X] Metadata fully populated
  - [X] Make sure JSON schema is same from dataset to dataset
  - [X] Change "Dataset 1, 2" etc to "File 1/2" etc
- [X] rebrand github group/repos to match
- [ ] (In Progress) [Netlify Open Source plan](https://www.netlify.com/legal/open-source-policy) application submitted
  - [X] License
  - [X] Code of Conduct at the top level directory of the project repository or prominently in the documentation (with a link in the navigation, footer, or homepage)
  - [X] Must feature a link to Netlify service
  - [ ] (In Progress) Review that all conditions are met, fill out the form and submit
- [X] Nested dataset schema
  - [X] each dataset can contain multiple files
  - [X] break out per file metrics vs. dataset metrics
- [X] Submit a Dataset fully functioning
  - [X] Front end form
  - [X] Back end saves suggestion to Github API (preferred) or Postgres
- [X] machine-data-hub published to PyPI
  - [X] unit testing runs on every push
  - [X] sphinx documentation pushes to readthedocs on tag
  - [X] library builds and pushes to PyPI on tag
  - [X] release notes section added to sphinx documentation
- [X] Blog functionality added to web app
  - [X] blog content can be added to repo in markdown format
- [ ] (In Progress) create a getting started page
  - [X] Add general step by step process
  - [X] Add why people should use it
  - [ ] Add python package section
- [X] Three documented examples of ML model built from a dataset
  - [X] Get working ML model in notebook
  - [X] Write blog post tutorial with example
  - [X] Get feedback from LM mentors
  - [X] Implement feedback from LM mentors and update on website
- [ ] (In Progress) UW ML Course students use machine-data-hub as data source for class project
  - [ ] Talk to UW 416 Course Instructor and send out email about response
  - [X] Follow up with Wes for Feedback
- [X] Web app receives a 90+ rating from [lighthouse] (https://developers.google.com/web/tools/lighthouse) for performance
  - [X] (In Progress) Fix slow image loading

Longer term
- [ ] machine-data-hub CLI does local ETL on at least three of the datasets
- [ ] Web App automated end to end testing
- [ ] Auth-N (Authentication) implemented
- [ ] Up Voting datasets
  - [ ] mitigation plan for duplicate votes (i.e. require Auth-N to cast a vote)
  - [ ] Dataset content pre-rendered, only user interaction elements (upvote controls and counts) load after hydration
- [ ] machinedatahub analytics (page views, dataset download counts) with Postgres
- [ ] User trial with survey and reward to get feedback from potential users (possibly use to incentivize students above)
- [ ] External user submits a new dataset
- [ ] First pull request merged from non-original team member
- [ ] Academic Paper Published

Maybe

- [ ] Auth-Z (Authorization) - allow private datasets
