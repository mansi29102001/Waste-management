# Waste-management using sensors
This project is based on the waste management to produce goods that can be used.

# Contents
•	Problem statement  
•	What’s the problem?  
•	How can technology help?  
•	Existing techniques  
•	The idea  
•	Demo video  
•	The architecture  
•	Long description  
•	Project roadmap  
•	Code for our project(website and sensors)     
•	Result    
•	Limitations    
•	Future scope    
•	Our contribution    
•	Conclusion 


# Problem statement
Responsible production and green consumption

# What’s the problem?
With the rising population, the amount of waste produced is also increasing day by day. The waste collected from urban areas is dumped near the outskirts of towns and cities. The improper management of the waste from its collection to disposal leads to various problems. To produce something productive with this waste, to make fruitful use of the waste present.

# How can technology help?
We all are unaware of the importance of the waste generated. With the help of technology, we can know the economic value of waste. This can be done basically with waste segregation. The heath issues faced by the workers to manually separate the waste can also be resolved with technology.

# Existing techniques
There are various techniques that are used to manage waste. Some of them are-  
	Landfills  
	Recovery and recycling using 3 R’s ( Reduce, Recycle and Reuse )  
	Composting  
	Plasma gasification, etc.  

# The idea
A website is created through which customers having waste can reach us. The waste will be segregated with the help of software, in which sensors will play the main role. The IBM IoT services will be used to monitor the waste and provide the customers with information on segregated waste.

# Demo video  
[![Waste-management](https://img.youtube.com/vi/47g2QhRxJSQ/0.jpg)](https://www.youtube.com/watch?v=47g2QhRxJSQ)

# The architecture
![Architecture](https://user-images.githubusercontent.com/86097473/122532348-0a0b6200-d03e-11eb-8b45-143407613e0a.jpg)

1) The user who has waste will contact us  
2) They can communicate with us with the help of our website, where we will give them the location of our dumping site  
3) Our software will segregate the waste with the help of sensors (IR, Inductive proximity and capacitive proximity sensors)  
4) The segregated waste will be monitored with the help of IBM IoT services  
5) The information regarding the segregated waste will be transferred to the user again  
 
# Long description
The main task of our project is to collect the waste from people and segregate it. Further, we will make useful products with the help of waste which will lead to proper management of waste.
1.	To reach the customers:  
The website has been created through which customers can contact us. To communicate with us they have to create their login account on our website. We will provide them the location of our dumping site where the segregation work will take place. The customer has to simply deliver the waste at the mentioned address.

2.	Segregation process:
The main work of our project starts from here i.e., to segregate the waste with the help of technology. We are using three sensors namely, IR sensors, Inductive proximity sensors (metal detecting sensors) and Capacitive proximity sensors.  

a)	IR sensors:  
The task of IR sensors is to detect the presence of waste in the dustbin. Dustbin will be fitted with an IR transmitter and IR receiver.
The IR transmitter will transmit the IR radiations which will be received by the receiver. When the waste will be thrown in this bin, the Radiations transmitted will reduce, and hence, the amount of radiation received will also be decreased. The decline in the radiations received will indicate the presence of waste in the bin. Now, this waste will be slowly dropped on the conveyer belt.

b)	Inductive proximity sensors (metal detecting sensors):  
On the conveyer belt, Inductive proximity sensors are placed. This sensor is used to detect the presence of metal in the waste. If the sensors detect the metal waste so, it will be separated at that place with the help of another conveyer belt. This belt will take the metal waste to a separate bin. In this way, metal waste will be segregated.

c)	Capacitive proximity sensors:  
The remaining waste is further moved on the main conveyer belt. This waste will come across the capacitive proximity sensors. This will help us to separate wet and dry waste. These sensors use a relative dielectric constant. Once a dielectric is present between the plates of the capacitor the capacitance rises. Since the relative dielectric constant of wet waste is more as compared to dry waste due to the presence of moisture in it. If the change in the capacitance count is greater than the threshold, then the type of waste is inferred as wet waste else it is a dry waste. Now, these waste are further moved on different belts depending on the type of waste and are dropped in separate bins (dry and wet waste bins).

In this way, the waste is separated.  

3.	Use of IBM IoT service:  
The waste will be weighted separately. With the help of IBM IoT services, we will provide information to the customers regarding the amount of segregated waste. Now, this waste will be further converted into useful products.  

4.	Further processing of wet waste:  
The wet waste will be further converted into fertilizers. These fertilizers will be provided to the poor farmers at low cost who are not able to buy them due to the high cost.

5.	Further processing of dry waste:  
The dry waste will be delivered to the local artists. Our website will be a platform for such artists to show their talent. When we will provide them the dry waste, they will make creative products, which can further be sold. With the help of our platform, these local artists can get employment. There will be no middlemen and hence, entire profit will be given to these artists.  

# Project roadmap
![waste management using sensors roadmap](https://user-images.githubusercontent.com/86097473/122534472-2d371100-d040-11eb-8738-93fc7e6824c2.png)

# Code for our project(website and sensors)
For website:  
https://drive.google.com/drive/folders/1Vc-6QtKj5jLB3uCSJzpygwBlNadP2MBh?usp=sharing  
For Sensors:  
https://docs.google.com/document/d/1M0RRwA_NRbkoMMTYTirABsXgqGee3A2WIkO6KkcxzQo/edit?usp=sharing  

# Result
With the help of our model, we have successfully segregated the waste without any human contact with the separation process of waste. This model is used to separate metallic, dry, and wet waste. IoT is used to monitor the system and provide information to the customers regarding the amount of waste produced.

# Limitations
•	Segregation of waste consumes time.  
•	On the spot decomposition of wet waste is not implemented.   

# Future Scope
The waste materials can be segregated into biodegradable, non-biodegradable, and metals by using more sensors. The large-scale introduction of automatic waste management in villages, platforms, hospitals, industries, etc. Real-time monitoring and controlling of waste management by using IoT. A prediction system by analyzing the given data’s to predict the variation in the amount of waste and to adjust the timing of management.

# Our contribution
1. Creates employment  
2. We our providing fertilizers to poor farmers at low cost     
3. Clean environment  
4. Helps us to make a difference by reusing the waste
5. Oppurtunities to artists to show their talent 

# Conclusion
In our project, we are collecting the waste properly. And this waste is segregated with the help of the software that we have built.  As the bin fills, IR sensor senses the level and the bin rotates into a conveyor. Waste is collected from different locations and reached the segregation part through the main conveyor belt. IoT is used in this project to monitor the waste segregation process. This segregated waste is then used efficiently.  



   



