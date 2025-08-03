<img width="769" height="360" alt="1_t_ntXMOxdM4FAX9wYJW-ng-1" src="https://github.com/user-attachments/assets/dddce9a2-94a8-4d26-bb0a-940b4e59dd31" />

## Argo Events | Kubernetes ☸️
Argo Events is an event-driven workflow automation framework for Kubernetes which helps you trigger K8s objects, Argo Workflows, Serverless workloads, etc. on events from a variety of sources like webhooks, S3, schedules, messaging queues, gcp pubsub, sns, sqs, etc.


🧱 Core Components
```
✅ EventSource ( Defines an external system to listen to GitHub Webhook, S3, Kafka, Cron, etc.)
✅ Sensor ( Defines what to do when an event is received Trigger a Workflow or Job )
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
Kubernetes CRDs (like Velero backup events)
```

🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```





