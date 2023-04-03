# Imperio Linode  

Organisation containing 4 repositories that I am working on as my main portfolio project.

Aim of this is to create friendly ui that will deploy and create linode engine, engines and k8s clusters.

All app is cloud enabled, works well with RKE, LKE, Minikube.

It is using Istio gateway that manages TLS at the same time, postgresql to handle reactive data and will use Keycloak as auth service and kafka as messaging broker for status reports between the services and react backed frontend.

Plan is to make it fully working by end of 2023.

💡 Kubernetes Scripts - Repository responsible for keeping track of kubernetes yamls, installation shell scripts and other important config like TLS. Basically entry point for running the app \
🚌 Gateway            - This is service responsible for receiving requests and forwarding it to other proper services. \
🏭 Instances          - Code responsible for keeping track of data and handling requests about creation, deletion and edition of instances that are deployed \
🔌 Linode Services    - Node service that takes prepared requests and deploys linode instances with linode api. Part mostly unfinished yet

