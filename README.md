### Run Pipeline
This will run pipeline from console 
```
tkn pipeline start migrate-db \
 -w name=shared-workspace,volumeClaimTemplateFile=https://raw.githubusercontent.com/openshift/pipelines-tutorial/master/01_pipeline/03_persistent_volume_claim.yaml \
 -p git-url=https://github.com/mancubus77/tekton-db-ansible.git \
 -p git-revision=main
```

