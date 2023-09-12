ANALYTICS UDACITY PROJECT
ABDELRAHMAN NAFEA

CONFIGURATION:

- Created Helm PostgreSQL chart under repo name database and service name analytics-db

- Ran db seed files on the database

- Ran the analytics application locally and verified it

DEPLOYMENT:

- Dockerfile created to push the image using codebuild-github pull request trigger into the ECR

- YAML file analytics.yml contains the configmap, deployment and service needed

- secret.sh file creates a kubectl secret where we store the database password (extracted during deployment of the analytics.yml)

- Checked cloudwatch live trail logs to ensure the application is running correctly

HELM Postgres Database Credentials
- USERNAME: postgres
- PASSWORD: SjadxPRmK6