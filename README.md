# AWS

Jenkins is a orchestrator implements the CI and invokes the CD

In CI there may be below stages depending on org:

- Checkout
- Build & UAT
- Code Scan
- Image Build
- Image Push

In CD there may be below stages depending on org:

For this invoking we can use Ansible, Shell Scripting which are outdated

Now using GitOps - (ArgoCD, FluxCD) or  Helm Charts 


AWS CodePipeline invokes CI (Using CodeBuild) and CD (Using COdeDeploy) 

AWS CodePipeline ?

- Scalability of nodes
- Patching 
- Managing the nodes
- Reliability
