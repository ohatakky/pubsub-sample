
1. GCP
> export PROJECT_NAME=

> export SUBSCRIBER=

2. Cloud PubSub
> gcloud pubsub topics create [topic_name]

> gcloud pubsub subscriptions create [sub_name] --topic [topic_name]

3. client-go
> go get -u cloud.google.com/go/pubsub

> go run main.go

4. publish message

> gcloud pubsub topics publish [topic_name] --message "hoge"

