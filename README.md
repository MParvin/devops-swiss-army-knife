# DevOps swiss army knife

This is a docker image that has a bunch of tools to help you troubleshoot your Applications, Services and Network in a containerized environment.

Use Deployment.yml to deploy the pod in your cluster.

## Tools

* bash
* curl
* dig
* iperf
* netcat
* nslookup
* ping
* telnet
* traceroute
* redis-cli
* mysql
* mongo
* kubectl
* aws
* aws-iam-authenticator
* gcloud
* kops
* mssql-cli
* postgres-client
* helm
* ssh
* tcpdump
* nmap
* ncat
* openssl
* jq
* azure-cli
* tcptraceroute
* udping
* hping3
* iputils-ping
* nfs-common
* socat
* nfswatch
* nmon
* nfstrace
* glusterfs-client
* glusterfs-cli
* cephfs-shell

### Usage

#### Usage in Docker

```bash
docker run -it --rm --name tshooter mparvin/devops-swiss-army-knife:latest
```

#### Usage in Docker Compose

```bash
docker-compose up -d
```

```bash
docker exec -it tshooter bash
```

#### Usage in Kubernetes

```bash
kubectl apply -f deployment.yml
```

```bash
kubectl exec -it tshooter -- bash
```
