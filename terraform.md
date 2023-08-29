1. What is terraform
Automate provisioning of infrastructure on any cloud with terraform.

2. How does it do that ?
It uses HCL language (similar to JSON with comments)
declarative language
functions, templates, documentation, tests
push based model
dependencies between resources

3. terraform cli and console
works with different providers - azure, aws, docker
cli, configuration, state, resources

4. Makes it reusable via modules
Allows you to publish sets of resources with best practices
it provides registries where you can publish these modules

4. cloud adoption framework
a. strategy - understand motivations, business outcomes, justification
b. plan - organization alignment, skills readiness, cloud adoption
c. ready - readiness guide, first landing zone, expand the blueprint, best practices
d. adopt - migrate - first workload, expanded scenarios, process improvements. innovate - innovation guiede
e. govern - methodology , benchmark, best practices.
f. manage - business commitments, ops maturity
g. secure -
https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/resources/tools-templates

5. Change in developer workflow
a. infrastructure team - focus on building reusable modules, landing zone capabilities
b. application team - focus on live infrastructure using those modules and deploying <--- we are here

* live code should always be in sync with what is deployed.
* run code in sandbox and read terraform plan document before deploying
* add tests for your live infrastructure changes
* 

References: 
* https://blog.gruntwork.io/how-to-use-terraform-as-a-team-251bc1104973
