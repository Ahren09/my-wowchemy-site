---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Graduate Research Assistant
    company: Georgia Institute of Technology
    company_url: ''
    company_logo: logo_georgia_tech
    location: Atlanta, GA, USA
    date_start: '2022-07-25'
    date_end: ''
    description: |2-
      Research Topics: Large Language Models (WebConf’24), Fairness and Equity (WebConf’24, In preparation for SIGIR'24), Social Network Analysis (KDD’23), Dynamic Graph Neural Networks (KDD’23), Multimodal Models (In preparation).

      Advisor: Dr. Srijan Kumar
  
  - title: Research Intern
    company: Microsoft Research Asia
    company_url: ''
    company_logo: logo_microsoft
    location: Beijing, China
    date_start: '2020-12-22'
    date_end: '2022-07-22'
    description: |2-
      Research Topics: Large Language Models and Agents (ICML'24), Language Models (ICML'23, AAAI'23), Misinformation Detection (KDD'22, AAAI'22), Learning in Low-Resource Scenarios (AAAI'23), Explainable AI (AAAI'22).

      Advisors: Dr. Xiting Wang, Dr. Jindong Wang, and Dr. Xing Xie. 
  
  - title: Graduate Research Assistant
    company: UCLA Scalable Analytics Institute (ScAi)
    company_url: ''
    company_logo: logo_ucla
    location: Los Angeles, CA, USA
    date_start: '2021-07-01'
    date_end: '2022-06-01'
    description: |2-
      Research Topics: Graph Neural Networks (WWW'23), Graph-Based Recommender Systems (WWW'23), Social Computing (AAAI'23, AAAI'22).

      Advisors: Dr. Yizhou Sun, Dr. Wei Wang


  - title: Software Engineer Intern
    company: Amazon.com
    company_url: ''
    company_logo: logo_amazon
    location: Seattle, WA, USA
    date_start: '2020-06-15'
    date_end: '2020-09-04'
    description: |2-
      Worked on the backend services of Amazon FBA Team

      Created IAR Manual Analysis, an AWS Step Functions workflow that uses AWS Lambda to aggregate datapoints from various data sources (S3, DynamoDB) for SageMaker ML model training, and handles $\ge$ 16,000 requests per summary stage.

  - title: Software Engineer Intern
    company: IBM
    company_url: ''
    company_logo: logo_ibm
    location: Beijing, China
    date_start: '2019-06-17'
    date_end: '2019-09-03'
    description: |2-
      Worked on the backend services of IBM Cloud. Developed 

      Created IAR Manual Analysis, an AWS Step Functions workflow that uses AWS Lambda to aggregate datapoints from various data sources (S3, DynamoDB) for SageMaker ML model training, and handles over 16,000 requests per summary stage.

design:
  columns: '2'
---
