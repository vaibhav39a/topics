1. What is terraform
- Automate provisioning of infrastructure on any cloud with terraform.

2. How does it do that ?
- It uses HCL language (similar to JSON with comments)
- declarative language
- functions, templates, documentation, tests
- push based model
- lets you define dependencies between resources

3. terraform cli and console
- works with different providers - azure, aws, docker
- cli, configuration, state, resources

4. Makes it reusable via modules
- Allows you to publish sets of resources with best practices
- It provides registry where you can publish these modules to be shared

4. Understand cloud adoption framework
- strategy - understand motivations, business outcomes, justification
- plan - organization alignment, skills readiness, cloud adoption
- ready - readiness guide, first landing zone, expand the blueprint, best practices
- adopt - migrate - first workload, expanded scenarios, process improvements. innovate - innovation guiede
- govern - methodology , benchmark, best practices.
- manage - business commitments, ops maturity
- secure - 

5. Change in developer workflow
- infrastructure team - focus on building reusable modules, landing zone capabilities
- application team - focus on live infrastructure using those modules and deploying <--- we are here

Application team focus
a. live code should always be in sync with what is deployed.
b. run code in sandbox and read terraform plan document before deploying
c. add tests for your live infrastructure changes


References: 
* https://blog.gruntwork.io/how-to-use-terraform-as-a-team-251bc1104973
* https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/resources/tools-templates
