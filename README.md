
1. GCP
> export PROJECT_NAME=xxxxx
> export SUBSCRIBER=*****

2. Cloud PubSub
> gcloud pubsub topics create *****

> gcloud pubsub subscriptions create ¥¥¥¥¥¥ --topic *****

3. client-go
> go get -u cloud.google.com/go/pubsub

> go run main.go

4. publish message

> gcloud pubsub topics publish my-topic --message "hoge"

