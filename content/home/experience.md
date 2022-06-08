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
  - title: Research Intern
    company: Microsoft Research Asia
    company_url: ''
    company_logo: logo_microsoft
    location: Beijing, China
    date_start: '2020-12-22'
    date_end: ''
    description: |2-
      Publish two papers on Fake News Detection at top-tier conferences (AAAI'22 and KDD'22).

      Conduct Research on Fake News Detection and Natural Language Processing for low-resource (limited data) scenarios.

  - title: Software Engineer Intern
    company: Amazon.com
    company_url: ''
    company_logo: logo_amazon
    location: Seattle, WA, USA
    date_start: '2020-06-15'
    date_end: '2020-09-04'
    description: 
      Worked on the backend services of Amazon FBA Team

      Created IAR Manual Analysis, an AWS Step Functions workflow that uses AWS Lambda to aggregate datapoints from various data sources (S3, DynamoDB) for SageMaker ML model training, and handles $\ge$ 16,000 requests per summary stage.

  - title: Software Engineer Intern
    company: IBM
    company_url: ''
    company_logo: logo_ibm
    location: Beijing, China
    date_start: '2019-06-17'
    date_end: '2019-09-03'
    description: 
      Worked on the backend services of IBM Cloud. Developed 

      Created IAR Manual Analysis, an AWS Step Functions workflow that uses AWS Lambda to aggregate datapoints from various data sources (S3, DynamoDB) for SageMaker ML model training, and handles $\ge$ 16,000 requests per summary stage.

design:
  columns: '2'
---