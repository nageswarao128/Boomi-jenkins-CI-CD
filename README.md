# Boomi CI & CD Using Jenkins

# RESSOURCES

* Links: 
    * [Boomi DevOps](https://boomi.com/form/devops-assets-success/)
    * [Docker Jenkins Boomi CI/CD](https://hub.docker.com/r/boomicicd/jenkins) 
    * [Official Boomi CI/CD with Jenkins jobs](https://github.com/OfficialBoomi/boomicicd-jenkinsjobs)
    * [Integrationguru Boomi CI/CD with Jenkins jobs](https://github.com/integrationguru/boomicicd-jenkinsjobs)
    * [Implementation](https://community.boomi.com/s/article/Boomi-CI-CD-Reference-Implementation)
    * [Video Tutorial](https://www.youtube.com/watch?v=DZgJgCw6Z7s)
    * [For more informations about Boomi CI/CD CLI](https://github.com/OfficialBoomi/boomicicd-cli)

# Configuration

1. Add .env file to the root folder with the same variable names in env-example file

2. Run : 
```
docker compose up
```

3. Wait for Jenkins to print Log info message : ***Jenkins is fully up and running***

4. Log in with **JENKINS_USER** and **JENKINS_PASS** values you have configured in the .env file

5. Configuring Boomi Account
    * select the Account_{Rename} folder & click configure & update the ***accountId*** in **folder propriety** & click **Apply & save**.
        * Log in to your boomi account and go to **Settings » Account Information** to find your  **Boomi __accountId__**