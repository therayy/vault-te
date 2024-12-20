# [Automation Level](https://developer.hashicorp.com/well-architected-framework/security/security-cicd-vault)
> Automate Vault usage and integrate with CI/CD pipelines and DevOps tools
    
| Phase | Activities | Deliverables |
| --- | --- | --- |
| Automation Tools | [Integrate Vault with Terraform](https://developer.hashicorp.com/terraform/tutorials/secrets/secrets-vault). </br> Automate secrets retrieval with [Ansible and Jenkins](https://www.redhat.com/en/blog/automating-secrets-management-hashicorp-vault-and-red-hat-ansible-automation-platform).| [CI/CD pipeline demo using Vault](https://www.youtube.com/watch?v=iFVJDeJ0_N0).| 
| Secrets Injection | Use Vault Agent for dynamic [secrets injection](https://developer.hashicorp.com/vault/tutorials/kubernetes/kubernetes-sidecar). </br> Learn about Kubernetes Secrets integration. | Lab: [Vault + OpenShift/Kubernetes integration](https://www.redhat.com/en/blog/integrating-hashicorp-vault-in-openshift-4). | 
| [Vault and GitOps](https://github.com/cloud-native-toolkit/multi-tenancy-gitops/blob/master/doc/ibm-vault-recipe.md)| HashiCorp Vault with ArgoCD or Flux for GitOps. </br> Automating secrets management workflows.| Vault GitOps patterns document. |
| Integrations | Integrate with third-party tools: [Elastic Stack, Service Mesh (Istio), etc](https://developer.hashicorp.com/hcp/docs/vault/logs-metrics/elasticsearch/metrics).| Integration guide and PoC.|



