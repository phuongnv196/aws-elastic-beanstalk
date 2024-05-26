# Project: Image Processing Microservice on AWS

## I. NodeJS Project:

### Route server:

- ![Route server](deployment_screenshot/route-server.png)

## II. Elastic Beanstalk Deployment:

### 1. Init Elastic Beanstalk:

Init Elastic Beanstalk by using: 
```bash
eb init
```

![Init Elastic Beanstalk](deployment_screenshot/init-elastic-beanstalk_01.png)

![Init Elastic Beanstalk](deployment_screenshot/init-elastic-beanstalk_02.png)

### 2. Create Elastic Beanstalk:

Create Elastic Beanstalk by using: 
```bash
eb create
```

![Create Elastic Beanstalk](deployment_screenshot/create-elastic-beanstalk_01.png)

![Create Elastic Beanstalk](deployment_screenshot/create-elastic-beanstalk_02.png)

### 3. Deploy website to Elastic Beanstalk:

Deploy website to Elastic Beanstalk by using: 
```bash
eb deploy
```

![Deploy Elastic Beanstalk](deployment_screenshot/deploy-elastic-beanstalk_01.png)

![Deploy Elastic Beanstalk](deployment_screenshot/deploy-elastic-beanstalk_02.png)

![Deploy Elastic Beanstalk](deployment_screenshot/deploy-elastic-beanstalk_03.png)

## III. References:
[udacity-filter-image](http://udacity-filter-image.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg)