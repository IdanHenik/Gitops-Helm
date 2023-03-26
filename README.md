# Gitops-Helm
Example how to implement Parent chart with subcharts to diffrent enviornments using **Gitops & ArgoCD**.

## -- main branch -- 
Two environments (pre-prod,prod) each subchart will be deployed with diffrenet values file per environment.
## -- one value -- 
Two environments (pre-prod,prod) each subchart will be deployed with one value file using enable flag and terms.
## -- spsific-subchart --
Example of two environments (pre-prod,prod) each environment will  deploy another subchart using dependencies
