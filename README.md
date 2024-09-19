# DT-EDA-Examples

# This repo hosts the rulebooks and playbooks for Event Driven Ansible integration use cases with Dynatrace

## Prerequisites

- OpenShift cluster with an account that has admin privileges
- Ansible Automation Platform (AAP) and Event Driven Ansible (EDA) instances (requires AAP >= 2.4)

## Reference App Setup for Observability

We have 2 options for deploying a reference app that can be used for Dynatrace observability and simulating problem events that can be detected by Dynatrace.

- Set up Easytrade app on OpenShift
  1. [Deploy](https://docs.dynatrace.com/docs/shortlink/installation-openshift-operatorhub#installation) the Dynatrace Certified Operator from the OpenShift OperatorHub
  2. Here's a [guide](https://github.com/gvenkatx/easytrade?tab=readme-ov-file#red-hat-openshift-instructions) for deploying the app on OpenShift

- Set up Easytravel app on RHEL VM
  1. [Deploy](https://docs.dynatrace.com/docs/shortlink/oneagent-linux-install) Dynatrace OneAgent 
  2. Here's a [guide](https://community.dynatrace.com/t5/Start-with-Dynatrace/easyTravel-Documentation-and-Download/m-p/181271) for deploying the Easytravel app on RHEL 

## Red Hat Ansible Automation Controller Setup


- Create EDA Token
  - Refer to this [link](https://docs.redhat.com/en/documentation/red_hat_ansible_automation_platform/2.4/html/event-driven_ansible_controller_user_guide/eda-set-up-token#eda-set-up-token) for setting up an access token for EDA to access Ansible Automation Controller

- Create Project
  - 

- Create Templates
  - 

## Event Driven Ansible Controller Setup

- Create Decision Environment
  - [Here's a screenshot illustrating the decision environment creation](images/eda_decision_env_creation.png)

- Create Project
  -  [Here's a screenshot illustrating the project creation](images/eda_project_creation.png)

- Create Rulebook Activation
  -  [Here's a screenshot illustrating how to create a rulebook activation](images/eda_rulebook_activation.png)
