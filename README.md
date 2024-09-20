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
  - ![Screenshot 2024-09-20 at 2 17 03 PM](https://github.com/user-attachments/assets/8bb77baf-7cfe-4bc5-8bad-7859b777c0a4)


- Create Templates
  - ![Screenshot 2024-09-20 at 2 32 01 PM](https://github.com/user-attachments/assets/001a4c82-25ef-4f62-b6d7-bc589603f9a2)
  - ![Screenshot 2024-09-20 at 2 31 07 PM](https://github.com/user-attachments/assets/975e82bf-0369-44c3-9b43-0c1fe18e2c0e)


![Screenshot 2024-09-20 at 2 32 25 PM](https://github.com/user-attachments/assets/edfbe711-854b-4125-8d83-6b275f63cffa)


## Event Driven Ansible Controller Setup

- Create Decision Environment
  - <img width="1414" alt="eda_decison_env_creation" src="https://github.com/user-attachments/assets/17aaab4c-f92d-4a65-90bc-6b9897c58e94">


- Create Project
  -  <img width="1408" alt="eda_project_creation" src="https://github.com/user-attachments/assets/ecce4614-6bae-4dd1-9b96-109fd1432599">


- Create Rulebook Activation
  -  <img width="1397" alt="eda_rulebook_activation" src="https://github.com/user-attachments/assets/99ecd46e-d16a-41e6-bf88-1d41b7c41b61">

