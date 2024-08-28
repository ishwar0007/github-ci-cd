# EKS Deployment CI/CD

## Variables Used in CI/CD

 
- AWS_ACCESS_KEY_ID = DSAJKBQIUQEWQNOIQWOI
- AWS_SECRET_ACCESS_KEY = gDKgrLCgrMDfrSCdaKMLMFdDKsaddaLFSDP5D
- ECR_REGISTRY = 1234567890.dkr.ecr.ap-south-1.amazonaws.com
- SLACK_TOKEN = xoxb-1234567890-5156589230-TjkasfjkbKLJNfxZphyNkBu

For below variables, we need to encode the kubernetes config. User the following command to encode the kube config.

```bash
cat /home/dev/.kube/config | base64
```
- KUBECONFIG  =
- STG_KUBECONFIG =
- PROD_KUBECONFIG = 

Create the above CI/CD variables in the Github action secrets.
