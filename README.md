# Portfolio open-ai

## open-ai (kubectl-ai)
Generated kubectl-ai demo yaml

| Name | Prompt | Description   | Example   |
|---   |---     |---            |---        |
|   app    | create deployment app with image demo-app:v1.0.0 | create simple app with image app:v1.0.0               |[app.yaml](./yaml/app.yaml)           |
|livnessProbe| create deployment app with image demo-app:v1.0.0 | create simple app with default livenesprobe parameters|[app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml)    |
|redinessProbe  |create pod app with image demo-app:v1.0.0 and readinessProbe | create simple app with default redinessprobe parameters | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml)|
|volumeMount| create pod app with image demo-app:v1.0.0 and volumeMount | create simple app with default volumemount params | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml)|
|cronJob| create pod app with image demo-app:v1.0.0 and cronJob | create simple app with default cronjob params |[app-cronjob.yaml](./yaml/app-cronjob.yaml)|
|job| create pod app with image demo-app:v1.0.0 and job | create simple app with default job params |[app-job.yaml](./yaml/app-job.yaml)|
|multicontainer| create pod app with image demo-app:v1.0.0 and multicontainer |create simple app with two images as example|[app-multicantainer.yaml](./yaml/app-multicontainer.yaml)|
|resourses| create pod app with image demo-app:v1.0.0 and resources |create simple app with default resources params as example| [app-resources.yaml](./yaml/app-resources.yaml)|
|secret-env| create pod app with image demo-app:v1.0.0 and secret-env username and password | create simple app with secret-env params (username and password)| [app-secret-env.yaml](./yaml/app-secret-env.yaml)|
|nginx| create app nginx | create app nginx with latest version| [app-nginx.yaml](./yaml/app-nginx.yaml)|