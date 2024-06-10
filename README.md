# Smart-Locker
#### THE PROBLEM:
Now a days everyone is busy with their own works. It has become very difficult to monitor each and every task which goes in our daily lives. People has become so busy that they buy things for themselves through online e-commerce websites i.e., from Amazon and Flipkart. Most of them are working professional and busy with their daily schedule and as they order things they don’t receive or collect their order at the time of delivery. They simply entrust the order to their neighbour’s or the delivery agent takes away the parcel with him leading to delay in delivery. Due to delay in delivery the customer have reschedule the delivery date by contacting the customer care and have to wait for few more days in order to take the delivery and it leads to customer dissatisfaction.

#### THE TEAMS APPROACH TO THE PROBLEM: -
In order to solve this problem we have come up with an solution i.e. development of a Smart Locker.The main aim of Smart Locker is to prevent theft of ordered products or goods from apartments and gated communities and to ensure timely deliveries of commodities/goods. Our approach is to build a locker system which has a keypad and is connected to a google firebase for each flat in an apartment or a villa in a gated community. For every flat in an apartment or for a villa there will be few lockers according to the size of products and each locker can be accessible by the respective flat residents. Each locker is connected to google firebase for which only the residents of that particular flat can have access to their respective locker by entering the unique One Time Password generated by Authenticator at that instance.

## INTRODUCTION:
Smart lockers are secure storage systems. We have made a locker where our orders will be stored securely. The smart locker is designed on the basis of Firebase. The owner has an app generates Random One Time Passwords whenever it is required The generated password will be stored in the Google Firebase. Whenever the owner enters the last recently generated password the locker unlocks so that the owner can have a hassle-free delivery. This smart locker is designed in such a way that no other person can able to access the locker and the product present/parcel inside it. The keypad is the input for the locker when password matches with the latest updated password in Firebase the locker opens.The smart locker is safe and secure locker. Now a days everyone is busy with their own works. It has become very difficult to monitor each and every task which goes in our daily lives. People has become so busy that they buy things for themselves through online e-commerce websites i.e Amazon and Flipkart. Most of them are who are working professional and busy with their daily schedule and as they order things they don’t receive or collect their order at the time of delivery. They simply entrust the order to their neighbours or the delivery agent just puts it at the entrance of that particular customer’s house. But there is a chance that the order might be stolen by them or due to any other reasons like any unknown persons might break into the customer’s house and steal their orders.In order to solve this problem we have come up with an solution i.e. development of a Smart Locker.

## COMPONENTS USED:
 
 #### HARDWARE:
1) Node MCU
2) DC 12V Solenoid Electromagnetic Cabinet Door Lock
3) 16x2 LCD
4) I2C Module
5) A keypad
6) 9V Battery
7) Battery Cap
8) Channel Relay Module
9) Printed Circuit Board(PCB)
10) PCB Vector Board
11) Jumper Wires

#### SOFTWARE:
1) Arduino IDE
2) Fusion 360
3) Fritzing
4) Google Firebase

## WORKING:
The working of our Smart Locker is very simple. The user has an application which generates random One Time Password (OTP) whenever he clicks the ”Generate OTP” button present in the app. At the backend this OTP gets stored in the Google Firebase which is in constant communication with ESP8266 NodeMCU which reads the OTP. Whenever the user enters the OTP displayed in the app, the lock gets unlocked since the OTP entered from the keypad is matching with the OTP stored in the Google Firebase with the help of ESP8266 NodeMCU. Here we are using a 16*2 LCD for diplaying the message on the locker for the user to enter the OTP and to inform whether the OTP entered is correct or not. A solenoid lock is used for locking mechanism which is controlled by a 1 channel relay here in this case. So we finally get the OTP generated from the app got stored in the Google Firebase successfully and ESP8266 NodeMCU established connection with the Google Firebase and read the OTP.

## FUTURE ENHANCEMENTS:
Our Smart Locker might be still at prototype level but it can be upgraded with many more features like adding a camera so that the user can ensure that the parcel has been placed in the locker. Our idea can also be implemented in Apartments where a group of lockers can be setup in a single room (preferably in the ground floor) with the above mentioned technology so that the delivery boy can easily place the parcel or product of a particular customer in their respective locker.

## CONCLUSION:
Our Smart Locker has a very much potential in the market. It helps many working individuals who are just busy with their schedules and cannot make time for these things. Customer need not to worry about the delay in the delivery of the product and he can get his product on time without any fear of theft or misplace.
