# Deploy

![image](https://github.com/mahesajf/axiata/assets/135594496/70f9dec1-8b3e-4b61-ac9e-139f799c7343)

<br>Install docker
<br>https://docs.docker.com/engine/install/ubuntu/
<br>
<br> # Docker login
<br>
<br>git clone https://github.com/aws-containers/retail-store-sample-app
<br>
<br>docker pull public.ecr.aws/aws-containers/retail-store-sample-ui:0.4.0
<br>docker pull public.ecr.aws/aws-containers/retail-store-sample-catalog:0.4.0
<br>docker pull public.ecr.aws/aws-containers/retail-store-sample-cart:0.4.0
<br>docker pull public.ecr.aws/aws-containers/retail-store-sample-orders:0.4.0
<br>docker pull public.ecr.aws/aws-containers/retail-store-sample-checkout:0.4.0
<br>docker pull public.ecr.aws/aws-containers/retail-store-sample-assets:0.4.0
<br>
<br>cd dist/docker-compose
<br>
<br>docker compose up -d
<br>
<br> # install jenkins from DockerHub
<br>docker pull jenkins/jenkins
<br>docker run -d -p 50000:8080 jenkins/jenkins

