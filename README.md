# springboot_testcode

YAML (Just put the tools you need in the yaml file.)
=============
### 1. jenkins yaml data (Required)

![image](https://user-images.githubusercontent.com/50852749/136325068-b301114f-1e6e-4fcc-81b6-0a5b09fbfec7.png)

Add jenkins data in your data.yaml!
<br/>
<br/>
<br/>

### 2. github yaml data (Required) (gitlab and bitbucket will be added.)

Get Github Personal Access Token

![image](https://user-images.githubusercontent.com/50852749/136324068-2d3a488d-b4c2-46c9-89c9-0552cca90aac.png)

![image](https://user-images.githubusercontent.com/50852749/136324374-f66574ee-24f7-47db-84c0-48f8fd266386.png)

![image](https://user-images.githubusercontent.com/50852749/136324684-033e9742-236b-47c9-9076-3de83ca1e380.png)

![image](https://user-images.githubusercontent.com/50852749/136324708-2628bf62-b35f-43d1-aaf3-72ac1cc22b2f.png)

![image](https://user-images.githubusercontent.com/50852749/136324804-4bb913d8-2f33-4d67-976b-e2f12d590c8b.png)

Add token and others in your data.yaml!
<br/>
<br/>
<br/>

### 3. slack yaml data (optional)

Get Slack subdomain, channel, token

![image](https://user-images.githubusercontent.com/50852749/136326141-ee03e997-ed10-4fa6-bda8-98a7f99ace6d.png)

![image](https://user-images.githubusercontent.com/50852749/136326211-d4dc2084-9c54-4c26-b035-03d5c2242478.png)

![image](https://user-images.githubusercontent.com/50852749/136326242-316f4db4-3bf5-4c8f-bb32-a654cc6332e0.png)
Get the channel name

![image](https://user-images.githubusercontent.com/50852749/136326299-eb59f929-25f9-4cd5-917d-95a817003e67.png)
Get the subdomain and token data

![image](https://user-images.githubusercontent.com/50852749/136326349-508ec9bd-d9e3-4628-a888-4c578c45bb48.png)

Add Slack data in your data.yaml!
<br/>
<br/>
<br/>

### 3. gradle yaml data (optional)

![image](https://user-images.githubusercontent.com/50852749/136328195-0b60e2d7-5b60-4d96-9ed1-c83b7e71483d.png)  
Just put gradle tool in data.yaml like this.
<br/>
<br/>
<br/>

### 4. sonarqube yaml data (optional)

Get sonarqube token

![image](https://user-images.githubusercontent.com/50852749/136327552-1cd82e30-8b26-4354-ba32-5a2c3d9b09cd.png)
Go to your sonarqube web ui

![image](https://user-images.githubusercontent.com/50852749/136327618-3dcfba00-2b58-44e4-91c1-8f513af10d39.png)  
Get the sonarqube token here

![image](https://user-images.githubusercontent.com/50852749/136327759-16538c8f-1aa7-45f5-9780-f4454db06521.png)  

Add Sonarqube token in your data.yaml!

#### Caution
If you want to use gradle and sonacube together, add the following content to your build.gradle file.  
![image](https://user-images.githubusercontent.com/50852749/136328600-4def5149-9807-49b4-9c38-b2e793c8c236.png)
<br/>
<br/>
<br/>

### 5. OAWSP dependency check yaml data (optional)
![image](https://user-images.githubusercontent.com/50852749/136330882-d5ced98e-06e1-4904-a283-63dc41ca722d.png)
Just put dependency check tool in data.yaml like this.
<br/>
<br/>
<br/>

### 6. Dockerhub yaml data (optional)
![image](https://user-images.githubusercontent.com/50852749/136331133-e47208ba-1612-41ae-a202-721d41df7315.png)  
Sign up dockerhub! and get the username and password 
<br/>
<br/>
![image](https://user-images.githubusercontent.com/50852749/136331017-17518348-b850-49db-816a-40730beddb80.png)  
Add build image name ex) username/imagename
<br/>
<br/>
<br/>

### 7. Anchore yaml data (optional, If used, dockerhub is required)
![image](https://user-images.githubusercontent.com/50852749/136331535-def1a71a-8b36-441a-a178-6c30f0885cd0.png)  
Look at the previous installation process, install it, and add data in data.yaml
<br/>
<br/>
<br/>

### 8. Argocd yaml data (optional, If used, dockerhub is required)
![image](https://user-images.githubusercontent.com/50852749/136331735-85691822-c31b-41e0-9025-61752afd8226.png)  
Look at the previous installation process, install it, and add data in data.yaml  
It is the url of the master node where argocd is installed.  
<br/>
<br/>
<br/>

### 9. Arachni yaml data (optional, If used, Argocd is required)
![image](https://user-images.githubusercontent.com/50852749/136940345-fed81d88-2f2f-4ada-ae3c-deb2e4574976.png)
# Enter the url of the node deployed in argocd.  
<br>
<br>
# If there is no url deployed yet, leave it as an empty value, and add the deployed node url to jenkinsfile later.  
![image](https://user-images.githubusercontent.com/50852749/136940425-adb5301d-ee47-47ad-894c-a34dbc208925.png)
<br>
<br/>
<br/>
<br/>
