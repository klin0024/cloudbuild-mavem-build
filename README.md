# 參數說明

參數 |預設 |說明
:---|:---|:---
\_GIT_REPO | https://github.com/spring-projects/spring-petclinic | source code 來源
\_DIR_NAME | spring-petclinic | source code 目錄
\_REGISTRY_NAME| us-central1-docker.pkg.dev | Registry位置
\_REPO_NAME| demo | Repo位置
\_IMAGE_NAME| spring-petclinic | Image名稱
\_TAG_NAME| v1.0 | Tag名稱

# 使用說明

### 1. 提交到cloudbuild

```
$ gcloud builds submit . --substitutions k1=v1,k2=v2
```