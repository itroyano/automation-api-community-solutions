# Control-M Automation API community solutions

This repository contains code samples and how-to for Control-M Automation API.  
+ [**Download Workbench for Docker**](https://hub.docker.com/r/controlm/workbench) - the latest development Control-M environment. 
+ [**Download Automation API CLI**](https://s3-us-west-2.amazonaws.com/controlm-appdev/release/latest/ctm-cli.tgz) (ctm-cli.tgz).  
+ [**Installation instructions**](https://docs.bmc.com/docs/display/public/workloadautomation/Control-M+Automation+API+-+Installation).  

## Online Documentation
You can find the latest Control-M Automation API documentation, including a programming guide, on the [**project web page**](https://docs.bmc.com/docs/display/public/workloadautomation/Control-M+Automation+API+-+Getting+Started+Guide).

## Contribution guide
To contribute, please follow these guidelines.

### Files, folders and naming conventions
1. Every sample and its associated files must be contained in its own **folder**. Name this folder something that describes what your sample does. Usually this naming pattern looks like **level-sample-purpose** (e.g. 201-automate-corrective-flow). Numbering should start at 101. 100 is reserved for things that need to be at the top.

      For consistent categorization, please comply to the following folder structure:
      + 1-general-examples
      + 2-cicd-tooling-integration
      + 3-infrastructure-as-code-examples
      + 4-ai-job-type-examples
      + 5-bots-and-dashboard-examples
      + 6-ide-integrations
      + 7-api-gateway-integrations
      + 8-jobs-as-code
      + 9-aws-integrations

2. For consistent ordering **create all folders in lowercase**.
3. Include a **README.md** file that explains the sample. A good description helps other community members to understand your sample. The README.md uses [Github Flavored Markdown](https://guides.github.com/features/mastering-markdown/) for formatting text. If you want to add images to your README.md file, store the images in the **images** folder. Reference the images in the README.md with a relative path (e.g. `![alt text](images/sampleImage.png "Sample Image Text")`). This ensures the link will reference the target repository if the source repository is forked.

## Questions/Feedback
Please use issues on GitHub for questions or feedback about the examples included in this repository.
