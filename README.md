# jjb

1. Build docker image

    ````$ docker build -t aap/jenkins .````

2. run docker container

    ````$ docker run -p 8080:8080 -p 50000:50000 aap/jenkins````

3. mannualy create JenkinsDeploy job

4. mannualy set user api token at jenkins_jobs.ini and JenkinsDeploy.yml

5. mannualy run JenkinsDeploy job for the first time
