<img width="8274" height="3378" alt="argo-events-architecture" src="https://github.com/user-attachments/assets/7c568cc6-5007-4b70-9ec6-c1d9c45aaf8a" />

## Argo Events | Kubernetes ☸️
Argo Events is an event-driven workflow automation framework for Kubernetes which helps you trigger K8s objects, Argo Workflows, Serverless workloads, etc. on events from a variety of sources like webhooks, S3, schedules, messaging queues, gcp pubsub, sns, sqs, etc.


🧱 Core Components
```
✅ EventSource ( Defines an external system to listen to GitHub Webhook, S3, Kafka, Cron, etc.)
✅ Sensors ( Defines what to do when an event is received Trigger a Workflow or Job )
✅ EventBus ( Provides pub/sub message delivery internally between EventSources and Sensors e.g. NATS )

```

🔌 Supported Event Sources
```
GitHub / GitLab / Bitbucket Webhooks
S3 (MinIO, AWS)
Kafka / NATS / MQTT / AMQP
Webhooks (HTTP)
Calendar/Cron (scheduled events)
GCP Pub/Sub, AWS SNS/SQS
Kubernetes CRDs 
```

🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```





