| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| app.yaml | create pod nginx in yaml format with name "app", label "run:app" | create pod nginx | [app.yaml](/yaml_prompt/app.yaml) |
| app-livenessProbe.yaml | create pod nginx in yaml format with name "app-livenessprob" namespace "demo" , with livenessProbe | pod  with livenessProbe | [app-livenessProbe.yaml](/yaml_prompt/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | create pod nginx in yaml format with name "app-readinessprob" , with livenessProbe and  readinessProbe | pod  with livenessProbe and readinessprob | [app-readinessProbe.yaml](/yaml_prompt/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | create pod nginx in yaml format with name "app-volume", with livenessProbe,   readinessProbe, volumeMounts and volumes named "data" | pod with volumeMounts | [app-volumeMounts.yaml](/yaml_prompt/app-volumeMounts.yaml) |
| app-cronjob.yaml | create cronjob in yaml  with name "app-cronjob" which can display every five minutes "Hello, world" in bash | cretate cronjob | [app-cronjob.yaml](/yaml_prompt/app-cronjob.yaml) |
| app-job.yaml | create job in yaml  with name "app-job-rsync" which can reserve copy of "data-input" folder | create Job | [app-job.yaml](/yaml_prompt/app-job.yaml) |
| app-multicontainer.yaml | create pod in yaml  with name "app-multi-containers" which contains two containers: nginx and debian | create multicontainer | [app-multicontainer.yaml](/yaml_prompt/app-multicontainer.yaml) |
| app-resources.yaml | create pod nginx in yaml  with name "app-resource" which contains livenessProbe,  readinessProbe, ports,  resources | create resources | [app-resources.yaml](/yaml_prompt/app-resources.yaml) |
| app-secret-env.yaml | create pod redis in yaml  with name "app-secret-env" which contains env with SECRET_USERNAME and SECRET_PASSWORD | create secret-env | [app-secret-env.yaml](/yaml_prompt/app-secret-env.yaml) |
