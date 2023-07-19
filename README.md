# AWS CodePipeline 

AWS CodePipeline invokes CI (Using CodeBuild) and CD (Using CodeDeploy) 

Similarly, Jenkins is also an orchestrator which implements the CI and invokes the CD

In CI there may be below stages depending on org:

```
- Checkout
- Build & UAT
- Code Scan
- Image Build
- Image Push
```

In CD there may be below stages depending on org:
```
For this invoking we can use Ansible, Shell Scripting which are outdated
Now using GitOps - (ArgoCD, FluxCD) or  Helm Charts 
```
AWS CodePipeline Drawbacks:

```
- Scalability of nodes
- Patching 
- Managing the nodes
- Reliability
```
