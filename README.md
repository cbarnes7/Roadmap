# Roadmap

Near term

- [X] machinedatahub.ai site live
- [X] rebrand github group/repos to match
- [ ] [Netlify Open Source plan](https://www.netlify.com/legal/open-source-policy) application submitted
  - [ ] License
  - [ ] Code of Conduct at the top level directory of the project repository or prominently in the documentation (with a link in the navigation, footer, or homepage)
  - [ ] Must feature a link to Netlify service
  - [ ] Review that all conditions are met, fill out the form and submit
- [ ] machine-data-hub CLI does local ETL on at least one of the datasets
- [ ] Nested dataset schema
  - [ ] each dataset can contain multiple files
  - [ ] break out per file metrics vs. dataset metrics
- [ ] Dataset content pre-rendered, only the  
- [ ] machine-data-hub published to PyPI
  - [X] unit testing runs on every push
  - [ ] sphinx documentation pushes to readthedocs on tag
  - [ ] library builds and pushes to PyPI on tag
  - [ ] release notes section added to sphinx documentation
- [ ] Blog functionality added to web app
  - [ ] blog content can be added to repo in markdown format
  - [ ] create a welcome post
- [ ] Documented example of ML model built from a dataset
- [ ] UW ML Course students use machine-data-hub as data source for class project
- [ ] User trial with survey and reward to get feedback from potential users (possibly use to incentivize students above)
- [ ] Web App automated end to end testing
- [ ] Web app receives a 90+ rating from [lighthouse](https://developers.google.com/web/tools/lighthouse) for performance
- [ ] Auth-N (Authentication) implemented
- [ ] Up Voting datasets
  - [ ] mitigation plan for duplicate votes (i.e. require Auth-N to cast a vote)
- [ ] machinedatahub analytics (page views, dataset download counts)

Longer term

- [ ] External user submits a new dataset
- [ ] First pull request merged from non-original team member
- [ ] Academic Paper Published

Maybe

- [ ] Auth-Z (Authorization) - allow private datasets
