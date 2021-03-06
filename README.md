# Advanced Platform Development with Kubernetes:
Enabling Data Management, the Internet of Things, Blockchain, and Machine Learning.

[![Book Cover - Advanced Platform Development with Kubernetes: Enabling Data Management, the Internet of Things, Blockchain, and Machine Learning](img/apk8s-banner-w.jpg)](https://amzn.to/3g3ihZ3)

Source code from the book [Advanced Platform Development with Kubernetes: Enabling Data Management, the Internet of Things, Blockchain, and Machine Learning](https://amzn.to/3g3ihZ3) by [Craig Johnston](https://imti.co) ([@cjimti](https://twitter.com/cjimti)) ISBN 978-1-4842-5610-7 [Apress; 1st ed. edition (September, 2020)](https://www.apress.com/us/book/9781484256107)



## Listings

### Chapter 2: [DevOps Infrastructure](chapter-02)

- [Listing 2-1: Cert Manager](/chapter-02/k8s/00-cluster/00-cert-manager-helm.yml)
- [Listing 2-2: Cluster Issuer](/chapter-02/k8s/00-cluster/05-cluster-issuer.yml)
- [Listing 2-3: Gitlab Namespace](/chapter-02/k8s/01-gitlab/00-namespace.yml)
- [Listing 2-4: Gitlab TLS Certificate](/chapter-02/k8s/01-gitlab/05-certs.yml)
- [Listing 2-5: Gitlab Services Configuration](/chapter-02/k8s/01-gitlab/10-services.yml)
- [Listing 2-6: Gitlab Configuration](/chapter-02/k8s/01-gitlab/20-configmap.yml)
- [Listing 2-7: Gitlab Deployment](/chapter-02/k8s/01-gitlab/40-deployment.yml)
- [Listing 2-8: Gitlab Ingress](/chapter-02/k8s/01-gitlab/50-ingress.yml)

### Chapter 3: [Development Environment](chapter-03)

- [Listing 3-1: Ingress Nginx Namespace](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/00-namespace.yml)
- [Listing 3-2: Ingress Nginx RBAC Service Account](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/05-serviceaccount.yml)
- [Listing 3-3: RBAC Ingress Nginx Cluster Role](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/06-clusterrole.yml)
- [Listing 3-4: RBAC Ingress Nginx Role](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/07-role.yml)
- [Listing 3-5: RBAC Ingress Nginx Role Binding](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/08-rolebinding.yml)
- [Listing 3-6: RBAC Ingress Nginx Cluster Role Binding](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/09-clusterrolebinding.yml)
- [Listing 3-7: Ingress Nginx Services](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/10-services.yml)
- [Listing 3-8: Ingress Nginx Services ConfigMaps](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/10-services.yml)
- [Listing 3-9: Ingress Nginx Deployment Default Backends](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/30-deployment.yml)
- [Listing 3-10: Ingress Nginx DaemonSet](/chapter-03/cluster-apk8s-dev1/000-cluster/00-ingress-nginx/40-daemonset.yml)
- [Listing 3-11: Cert Manager Namespace](/chapter-03/cluster-apk8s-dev1/000-cluster/10-cert-manager/00-namespace.yml)
- [Listing 3-12: Cert Manager Cluster Issuer](/chapter-03/cluster-apk8s-dev1/000-cluster/10-cert-manager/03-clusterissuer.yml)
- [Listing 3-13: CephBlockPool and StorageClass](/chapter-03/cluster-apk8s-dev1/000-cluster/20-rook-ceph/70-rook-ceph-block.yml)
- [Listing 3-14: CephFilesystem](/chapter-03/cluster-apk8s-dev1/000-cluster/20-rook-ceph/75-rook-ceph-clusterfs.yml)
- [Listing 3-15: Monitoring README](/chapter-03/cluster-apk8s-dev1/000-cluster/30-monitoring/README.md)

### Chapter 4: [In-Platform CI/CD](chapter-04)

- [Listing 4-1: ServiceAccount and CluserRoleBinding for GitLab](/chapter-04/cluster-apk8s-dev2/000-cluster/40-gitlab-integration/05-rbac.yml)
- [Listing 4-2: Custom JupyterLab](/chapter-04/ds/notebook-apk8s/Dockerfile)<!-- @IGNORE PREVIOUS: link -->
- [Listing 4-3: Python communicating with Prometheus](/chapter-04/ds/notebook-apk8s/PrometheusTest.ipynb)
- [Listing 4-4: GitLab CI pipeline configuration](/chapter-04/ds/notebook-apk8s/PrometheusTest.ipynb)
- [Listing 4-5: Editing the notebook-testing default Service Account](/chapter-04/NotebookServiceAccountEdit.yml)
- [Listing 4-6: Source fragment from Dockerfile](/chapter-04/ds/notebook-apk8s/Dockerfile.edit)

### Chapter 5: [Pipeline](chapter-05)
- [Listing 5-1: Development Cluster configuration layout](/chapter-05/ClusterConfigLayoutCheckpoint.txt)
- [Listing 5-2: data Namespace](/chapter-05/cluster-apk8s-dev3/003-data/000-namespace/00-namespace.yml)
- [Listing 5-3: Certificates for the data Namespace](/chapter-05/cluster-apk8s-dev3/003-data/000-namespace/05-certs.yml)
- [Listing 5-4: Zookeeper Service](/chapter-05/cluster-apk8s-dev3/003-data/010-zookeeper/10-service.yml)
- [Listing 5-5: Zookeeper Headless Service](/chapter-05/cluster-apk8s-dev3/003-data/010-zookeeper/10-service-headless.yml)
- [Listing 5-6: Zookeeper StatefulSet](/chapter-05/cluster-apk8s-dev3/003-data/010-zookeeper/40-statefulset.yml)
- [Listing 5-7: Kafka Service](/chapter-05/cluster-apk8s-dev3/003-data/020-kafka/10-service.yml)
- [Listing 5-8: Kafka Headless Service](/chapter-05/cluster-apk8s-dev3/003-data/020-kafka/10-service-headless.yml)
- [Listing 5-9: Kafka StatefulSet](/chapter-05/cluster-apk8s-dev3/003-data/020-kafka/40-statefulset.yml)
- [Listing 5-10: Kafka Pod Disruption Budget](/chapter-05/cluster-apk8s-dev3/003-data/020-kafka/45-pdb.yml)
- [Listing 5-11: Kafka test client Pod](/chapter-05/ClusterConfigLayoutCheckpoint.txt)
- [Listing 5-12: Mosquitto MQTT Service](/chapter-05/cluster-apk8s-dev3/003-data/050-mqtt/10-service.yml)
- [Listing 5-13: Mosquitto configuration ConfigMap](/chapter-05/cluster-apk8s-dev3/003-data/050-mqtt/10-service.yml)
- [Listing 5-14: Mosquitto Deployment](/chapter-05/cluster-apk8s-dev3/003-data/050-mqtt/30-deployment.yml)
- [Listing 5-15: Data Pipeline Development Cluster configuration layout](/chapter-05/cluster-apk8s-dev3/ConfigLayout.txt)

### Chapter 6: [Indexing and Analytics](chapter-06)

- [Listing 6-1: Installing kernel headers and the rdb kernel module](/chapter-06/InstallingKernelHeaders.txt)
- [Listing 6-2: Development environment prerequisites](/chapter-06/DevelopmentEnvironmentPrerequisites.txt)
- [Listing 6-3: cluster-apk8s-dev4 TLS Certificate](/chapter-06/cluster-apk8s-dev4/003-data/000-namespace/05-certs.yml)
- [Listing 6-4: Elasticsearch Service](/chapter-06/cluster-apk8s-dev4/003-data/030-elasticsearch/10-service.yml)
- [Listing 6-5: Elasticsearch Statefulset](/chapter-06/cluster-apk8s-dev4/003-data/030-elasticsearch/40-statefulset.yml)
- [Listing 6-6: Logstash Service](/chapter-06/cluster-apk8s-dev4/003-data/032-logstash/10-service.yml)
- [Listing 6-7: Logstash configuration ConfigMap](/chapter-06/cluster-apk8s-dev4/003-data/032-logstash/30-configmap-config.yml)
- [Listing 6-8: Logstash pipeline configuration ConfigMap](/chapter-06/cluster-apk8s-dev4/003-data/032-logstash/30-configmap-pipeline.yml)
- [Listing 6-9: Logstash Deployment](/chapter-06/cluster-apk8s-dev4/003-data/032-logstash/40-deployment.yml)
- [Listing 6-10: Kibana Service](/chapter-06/cluster-apk8s-dev4/003-data/034-kibana/10-service.yml)
- [Listing 6-11: Kibana configuration ConfigMap](/chapter-06/cluster-apk8s-dev4/003-data/034-kibana/20-configmap.yml)
- [Listing 6-12: Kibana Deployment](/chapter-06/cluster-apk8s-dev4/003-data/034-kibana/30-deployment.yml)
- [Listing 6-13: Kibana Ingress](/chapter-06/cluster-apk8s-dev4/003-data/034-kibana/50-ingress.yml)
- [Listing 6-14: Keycloak Web Service](/chapter-06/cluster-apk8s-dev4/003-data/005-keycloak/10-service.yml)
- [Listing 6-15: Keycloak administrator and keystore credentials](/chapter-06/cluster-apk8s-dev4/003-data/005-keycloak/15-secret.yml)
- [Listing 6-16: Keycloak deployment](/chapter-06/cluster-apk8s-dev4/003-data/005-keycloak/30-deployment.yml)
- [Listing 6-17: Keycloak Ingress](/chapter-06/cluster-apk8s-dev4/003-data/005-keycloak/50-ingress.yml)
- [Listing 6-18: data-lab Namespace](/chapter-06/cluster-apk8s-dev4/005-data-lab/000-namespace/00-namespace.yml)
- [Listing 6-19: datalab ServiceAccount](/chapter-06/cluster-apk8s-dev4/005-data-lab/000-namespace/05-serviceaccount.yml)
- [Listing 6-20: datauser and hub Roles for the data-user Namespace](/chapter-06/cluster-apk8s-dev4/005-data-lab/000-namespace/07-role.yml)
- [Listing 6-21: data-user and hub RoleBindings](/chapter-06/cluster-apk8s-dev4/005-data-lab/000-namespace/08-rolebinding.yml)
- [Listing 6-22: JupyterHub Helm values](/chapter-06/cluster-apk8s-dev4/003-data/100-jupterhub/values.yml)
- [Listing 6-23: JupyterHub Ingress](/chapter-06/cluster-apk8s-dev4/003-data/100-jupterhub/50-ingress.yml)
- [Listing 6-24: Indexing and analytics development cluster configuration layout](/chapter-06/ConfigLayout.txt)

### Chapter 7: [Data Lake](chapter-07)

- [Listing 7-1: MinIO operator](/chapter-07/cluster-apk8s-dev5/000-cluster/22-minio/00-operator.yml)
- [Listing 7-2: MinIO cluster configuration](/chapter-07/cluster-apk8s-dev5/003-data/070-minio/50-cluster.yml)
- [Listing 7-3: MinIO cluster Ingress](/chapter-07/cluster-apk8s-dev5/003-data/070-minio/50-ingress.yml)
- [Listing 7-4: MinIO Server external connection configuration](/chapter-07/minio/ConfigExternalConnect.json.txt)
- [Listing 7-5: Example bucket event notification](/chapter-07/minio/ExampleBucketEventNotification.json)
- [Listing 7-6: Go application: Compressor](/chapter-07/compressor/compressor.go)<!-- @IGNORE PREVIOUS: link -->
- [Listing 7-7: Dockerfile for the Compressor application](/chapter-07/compressor/Dockerfile)<!-- @IGNORE PREVIOUS: link -->
- [Listing 7-8: Update `005-data-lab/000-namespace/07-role.yml`](/chapter-07/cluster-apk8s-dev5/005-data-lab/000-namespace/07-role.yml)
- [Listing 7-9 Monitor Job state and cleanup](/chapter-07/notebook/KubernetesJobs.ipynb)

### Chapter 8: [Data Warehouses](chapter-08)

- [Listing 8-1: MySQL operator Namespace](/chapter-08/cluster-apk8s-dev5/000-cluster/25-mysql-operator/00-namespace.yml)
- [Listing 8-2: MySQL cluster configuration](/chapter-08/cluster-apk8s-dev5/003-data/080-mysql/90-cluster.yml)
- [Listing 8-3: Rook Cassandra operator](/chapter-08/cluster-apk8s-dev5/000-cluster/23-rook-cassandra/00-operator.yml)
- [Listing 8-4: Rook Cassandra RBAC configuration](/chapter-08/cluster-apk8s-dev5/003-data/060-cassandra/15-rbac.yml)
- [Listing 8-5: Rook Cassandra cluster configuration](/chapter-08/cluster-apk8s-dev5/003-data/060-cassandra/90-cluster.yml)
- [Listing 8-6: Apache Hive configuration template `hive-site-template.xml`](/chapter-08/hive/hive-site-template.xml)
- [Listing 8-7: Apache Hive container `entrypoint.sh` script](/chapter-08/hive/entrypoint.sh)
- [Listing 8-8: Apache Hive `Dockerfile`](/chapter-08/hive/Dockerfile)<!-- @IGNORE PREVIOUS: link -->
- [Listing 8-10: Apache Hive `docker-compose.yml`](/chapter-08/hive/docker-compose.yml)
- [Listing 8-11: Apache Hive Service](/chapter-08/cluster-apk8s-dev5/003-data/085-hive/10-service.yml)
- [Listing 8-12: Apache Hive Deployment](/chapter-08/cluster-apk8s-dev5/003-data/085-hive/30-deployment.yml)
- [Listing 8-13: Presto Helm configuration](/chapter-08/cluster-apk8s-dev5/003-data/095-presto/values.yml)
- [Listing 8-14: Presto Ingress](/chapter-08/cluster-apk8s-dev5/003-data/095-presto/50-ingress.yml)

### Chapter 9: [Routing and Transformation](chapter-09)

- [Listing 9-1: OpenFaas Ingress](/chapter-09/cluster-apk8s-dev5/003-data/120-openfaas/50-ingress.yml)
- [Listing 9-2: NiFi Headless Service](/chapter-09/cluster-apk8s-dev5/003-data/120-openfaas/50-ingress.yml)
- [Listing 9-3: NiFi StatefulSet](/chapter-09/cluster-apk8s-dev5/003-data/060-nifi/40-statefulset.yml)
- [Listing 9-4: NiFi Ingress](/chapter-09/cluster-apk8s-dev5/003-data/060-nifi/60-ingress.yml)
- [Listing 9-5: HTTP post an Elasticsearch index template](/chapter-09/elasticsearch/PostSentimentTemplate.sh)
- [Listing 9-6: HTTP post an Elasticsearch Sentiment Analysis query](/chapter-09/elasticsearch/PostSentimentAnalysisQuery.sh)
- [Listing 9-7: Example aggregation output from Elasticsearch Sentiment Analysis query](/chapter-09/elasticsearch/ElasticsearchSentimentAnalysisResult.json)

### Chapter 10: [Platforming Blockchain](chapter-10)

- [Listing 10-1: Bootnode Service](/chapter-10/cluster-apk8s-eth/003-data/200-eth/10-bootnode/10-service.yml)
- [Listing 10-2: Bootnode Deployment](/chapter-10/cluster-apk8s-eth/003-data/200-eth/10-bootnode/30-deployment.yml)
- [Listing 10-5: Bootnode Registrar Service](/chapter-10/cluster-apk8s-eth/003-data/200-eth/20-bootnode-reg/10-service.yml)
- [Listing 10-4: Bootnode Deployment](/chapter-10/cluster-apk8s-eth/003-data/200-eth/20-bootnode-reg/30-deployment.yml)
- [Listing 10-5: Ethstats Service](/chapter-10/cluster-apk8s-eth/003-data/200-eth/30-ethstats/10-service.yml)
- [Listing 10-6: Ethstats Secret](/chapter-10/cluster-apk8s-eth/003-data/200-eth/30-ethstats/15-secret.yml)
- [Listing 10-7: Ethstats Deployment](/chapter-10/cluster-apk8s-eth/003-data/200-eth/30-ethstats/30-deployment.yml)
- [Listing 10-8: Ethstats Ingress](/chapter-10/cluster-apk8s-eth/003-data/200-eth/30-ethstats/50-ingress.yml)
- [Listing 10-9: Geth Secret](/chapter-10/cluster-apk8s-eth/003-data/200-eth/40-miner/15-secret.yml)
- [Listing 10-10: Geth ConfigMap](/chapter-10/cluster-apk8s-eth/003-data/200-eth/40-miner/20-configmap.yml)
- [Listing 10-11: Geth Deployment](/chapter-10/cluster-apk8s-eth/003-data/200-eth/40-miner/30-deployment.yml)
- [Listing 10-12: Geth transaction node Service](/chapter-10/cluster-apk8s-eth/003-data/200-eth/50-tx/10-service.yml)
- [Listing 10-13: Geth transaction node Deployment](/chapter-10/cluster-apk8s-eth/003-data/200-eth/50-tx/30-deployment.yml)
- [Listing 10-14: OpenFaaS function for returning details on the last block in the Blockchain](/chapter-10/cluster-apk8s-eth/003-data/200-eth/functions/last-block/handler.py)<!-- @IGNORE PREVIOUS: link -->

### Chapter 11: [Platforming AIML](chapter-10)

- [Listing 11-1: Signal Monitor script ConfigMap](/chapter-11/cluster-apk8s-hc1/020-data/220-smon/20-configmap.yml)
- [Listing 11-2: Signal Monitor DaemonSet deployment](/chapter-11/cluster-apk8s-hc1/020-data/220-smon/40-daemonset.yml)
- [Listing 11-3: MQTT Client Dockerfile](/chapter-11/mqtt_client/Dockerfile)<!-- @IGNORE PREVIOUS: link -->
- [Listing 11-4: Jolt transformation](/chapter-11/nifi/JoltTransformation.json)
- [Listing 11-5: ConfigMap with Python data dump script](/chapter-11/cluster-apk8s-hc1/020-data/500-jobs/01-configmap-hrdump.yml)
- [Listing 11-6: Python data dump script `requirements.txt`](/chapter-11/python_job_container/requirements.txt)
- [Listing 11-7: Python `Dockerfile` with requirements](/chapter-11/python_job_container/Dockerfile)<!-- @IGNORE PREVIOUS: link -->
- [Listing 11-8: Python data dump hourly CronJob](/chapter-11/cluster-apk8s-hc1/020-data/500-jobs/01-cronjob-hrdump.yml)
- [Listing 11-9: Updated `singleuser` configuration for JupyterHub](/chapter-11/cluster-apk8s-hc1/020-data/100-jupyterhub/values.yml)
- [Listing 11-10: MLflow container `requirements.txt`](/chapter-11/python_job_container/requirements.txt)
- [Listing 11-11: MLflow `Dockerfile`](/chapter-11/python_job_container/Dockerfile)<!-- @IGNORE PREVIOUS: link -->
- [Listing 11-12: MLflow Service](/chapter-11/cluster-apk8s-hc1/020-data/800-mlflow/10-service.yml)
- [Listing 11-13: MLflow StatefulSet](/chapter-11/cluster-apk8s-hc1/020-data/800-mlflow/40-statefulset.yml)
- [Listing 11-14: MLflow Ingress](/chapter-11/cluster-apk8s-hc1/020-data/800-mlflow/50-ingress.yml)
- [Listing 11-15: Secret containing s3 (MinIO) config and credentials](/chapter-11/cluster-apk8s-c2/000-sd-s3-secret.yml)
- [Listing 11-16: SeldonDeployment with Ingress](/chapter-11/cluster-apk8s-c2/100-sd-quality.yml)
