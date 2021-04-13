# Roadmap

Near term

- [X] machinedatahub.ai site live
- [X] rebrand github group/repos to match
- [ ] (In Progress) [Netlify Open Source plan](https://www.netlify.com/legal/open-source-policy) application submitted
  - [X] License
  - [ ] Code of Conduct at the top level directory of the project repository or prominently in the documentation (with a link in the navigation, footer, or homepage)
  - [X] Must feature a link to Netlify service
  - (In Progress) [ ] Review that all conditions are met, fill out the form and submit
- [ ] machine-data-hub CLI does local ETL on at least three of the datasets
- [X] Nested dataset schema
  - [X] each dataset can contain multiple files
  - [X] break out per file metrics vs. dataset metrics
- [ ] Dataset content pre-rendered, only user interaction elements (upvote controls and counts) load after hydration
- [ ] (In Progress) Submit a Dataset fully functioning
  - [X] Front end form
  - [ ] Back end saves suggestion to Github API (preferred) or Postgres
- [ ] machine-data-hub published to PyPI
  - [X] unit testing runs on every push
  - [X] sphinx documentation pushes to readthedocs on tag
  - [ ] library builds and pushes to PyPI on tag
  - [ ] release notes section added to sphinx documentation
- [ ] (In Progress ) Blog functionality added to web app
  - [X] blog content can be added to repo in markdown format
  - [ ] create a welcome post
- [ ] (In Progress) Three documented examples of ML model built from a dataset
  - [ ] Get working ML model in notebook
  - [ ] Write blog post tutorial with example
- [ ] (In Progress) UW ML Course students use machine-data-hub as data source for class project
- [ ] Web App automated end to end testing
- [ ] Web app receives a 90+ rating from [lighthouse](https://developers.google.com/web/tools/lighthouse) for performance
- [ ] Auth-N (Authentication) implemented
- [ ] Up Voting datasets
  - [ ] mitigation plan for duplicate votes (i.e. require Auth-N to cast a vote)
- [ ] machinedatahub analytics (page views, dataset download counts) with Postgres
- [ ] User trial with survey and reward to get feedback from potential users (possibly use to incentivize students above)

Longer term

- [ ] External user submits a new dataset
- [ ] First pull request merged from non-original team member
- [ ] Academic Paper Published

Maybe

- [ ] Auth-Z (Authorization) - allow private datasets
