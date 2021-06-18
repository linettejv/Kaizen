## What is the problem?
The problem were trying to solve here is the over consumption of electricity in the households. Due to absence of judicious management of electricity, the electricity generation requirements around us has grown manifolds. If we can conserve the water resources for a longer time, it would be a small help that we can do from our part for the climate. 
Cutting back on energy consumption reduces the amount of electricity that power plants have to make, subsequently reducing the amount of fossil fuels that are burned each day. Even a small change can make a tremendous difference – if every American household traded in just one incandescent light bulb for an efficient CFL, the reduction in pollution would be equivalent to taking 1.3 million cars off the road.
 Although your own energy saving adjustments may seem inconsequential, small steps become great leaps when multiplied by 7 billion.


## What technology is used?
LoRaWAN, IBM™cloud, cloudant™ Database, Flutter™

## The solution
We created a simple solution where, we track the energy usage of each unit (home) using LoraWAN technology. Since this is a kind of offline communication, this can be used where online communication techniques like Wi-Fi connectivity has high latency. 
After Lora (short for LoRaWAN) receives the coded information from all modules, it goes to the Lora gateway and from there to IBM™ cloud service and from there to cloudant™ data base.
The mobile application is created using flutter™ (dart), where the user will be able to 
1.	Know usage statistics over specified periods of time
2.	Ranking of the user in the locality
3.	Pay electricity bills online
4.	Set the target to reduce consumption so that the user itself will develop the willpower to do so and also can see the warnings accordingly.
5.	Contact lineman workers in case of power cuts or emergency help.
These are made possible by calling data from the cloudant™ database by creating an instance of it in the app. By this way, we can build an effective way to reduce the wastage of electricity in the households.
Since this is an expensive project, this can be only done with assistance from government and CSR funds. But considering the sustainability factor, it is viable in the long run. Lora is the technology of the future and researched are being conducted for more efficient and cost effective Lora technologies. 


## Architecture

![image](https://user-images.githubusercontent.com/65534301/122575619-903f9c80-d06e-11eb-979b-25c03ad838b4.png)

 1. smart trackers in each home tracks enerfgy usage on a real-time basis
 2. this data is sent to lorawan module
 3. this message is sent to gateway in offline  fashion
 4. These data packets are uploaded to IBM cloud by using MQTT protocol
 5. This data is stored into cloudant Db
 6. mobile app built with flutter tm gets this data from databse and shows it to user
 
 ## Project Roadmap
 
 ![Capture](https://user-images.githubusercontent.com/65534301/122576359-3be8ec80-d06f-11eb-8509-835235a50a1a.JPG)

## Live Demo

## Built with 
1.IBM Cloudant - The NoSQL database used
2.IBM Cloud Functions - The compute platform for handing logic gateway using Raspberry pi 3 and lora modules Lorawan network built using things network
3.IBM Watson IoT platform - for designing and testing IoT devices

## Contributors
Shone Stalin
Fathima Shirin
Niranjan Neelakantan
Linette Joseph
Anjana Thomas
