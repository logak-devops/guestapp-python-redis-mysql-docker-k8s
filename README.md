# Scenario
```
A member of your team has developed a self-contained Very Exciting Guestbook in Python that requires deployment to a Production environment so the general public can visit it.
The Guestbook consists of 3 pages:
● a home page where visitors are invited to enter their name and keeps a count of the number of page views
● a submission/'Thanks' page for visitors that have entered their name
● a 'Visitors' page where previous visitors to the website are listed
Names of visitors to the site are stored in MySQL, and number of page views are stored in redis.

```


https://www.infoq.com/articles/aws-codepipeline-deploy-docker/


```
https://github.com/logambigaik/guestapp-python-redis-mysql-docker-k8s.git

aws codepipeline get-pipeline --name guestapp-pipeline >pipeline.json

in buildspec.yaml



artifacts:
  files:
    - appspec.yml
    - target/SampleMavenTomcatApp.war
    - scripts/*
    
 ```
