# OpenAI

| NAME | PROMPT | DESCRIPTION | EXAMPLE | 
| ------------ | ------------ | ------------ | ------------ |
| app.yaml | create app.yaml | Create a deployment for the app. | [app.yaml](./yaml/app.yaml) |
| app-livenessProbe.yaml | create an app-livenessProbe.yaml | Create a deployment for the app and additionally, include a liveness probe for health checking purposes. | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | create app-readinessProbe.yaml | Set up a deployment for the application using. Include a readiness probe to ensure the application is ready to accept traffic. | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | create app-volumeMounts.yaml | Develop an application with a volume. | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | create app-cronjob.yaml | Create a cronjob scheduled to run every 5 minutes. | [app-cronjob.yaml](./yaml/app-cronjob.yaml) |
| app-job.yaml | create app-job.yaml | Create a Job. | [app-job.yaml](./yaml/app-job.yaml) |
| app-multicontainer.yaml | create app-multicontainer.yaml | Set up a Pod containing two containers. | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml | create app-resources.yaml | Define a Pod containing a single container and requsted and limited resources. Resource requests are configured at 250m CPU and 64Mi memory, while resource limits are set to 500m CPU and 128Mi memory | [app-resources.yaml](./yaml/app-resources.yaml) |
| app-secret-env.yaml | create app-secret-env.yaml | Define a Pod containing a single container. The container is customized with two environment variables, 'SECRET_USERNAME' and 'SECRET_PASSWORD'. | [app-secret-env.yaml](./yaml/app-secret-env.yaml) |