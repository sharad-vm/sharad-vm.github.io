## Clover

## Product Specialist Challenge
#### _Sharad Mohan Vijalapuram_
#### [Clover Dashboard](https://sharad-vm.github.io/clover.md.html)

##### CONTEXT
Clover management would like to get a sense for what types of merchants have been recently
acquired and what types of concerns they may have with our products. They have asked you to 
conduct an analysis and present your findings at their next staff meeting. Your presentation 
should, at minimum, answer the questions listed below and include any other findings that 
may be insightful for Clover management.

##### DATA
"merchants.txt" - This data set contains a list of merchants along with certain characteristics
about them such as whether they are a quick service restaurant, are a demo merchant that only 
uses our devices for testing purposes, or have a certain set of apps pre-installed on their devices. 

"devices.txt" - This data set contains a list of devices and their associated history with certain merchants. 
For example, once a device is "PROVISIONED" to a merchant, their device is now associated with that merchant. 
Likewise, when a device is "DISASSOCIATED" from a merchant, the device is no longer associated with any merchant. 

"cases.txt" - This data set contains a list of cases that are created by Clover customer support when a merchant 
reaches out to our call centers. These data include reasons for why a merchant called as well as merchant and 
device information, if possible.

##### QUESTIONS
__How many merchants and of what type?__

There are 92,985 merchants in the data set with 57,624 having a device assigned to them at some point with 
the maximum number of merchants in the Services category and the least in the Airlines.
There are numerous merchant types that fall under different categories with or without a device associated to them. 
Use the interactive packed bubbles chart in the dashboard to get a feel of the merchants and their 
associated devices (if any) - [Clover Dashboard](https://sharad-vm.github.io/clover.md.html)

![Bubble Chart](/clover/bubblechart.png)

__How many devices do merchants have and of what type?__ 

There are 87,215 devices in the data set out of which, 83,812 are or have been with a merchant in the past.

![Devices Bar Chart](/clover/devices.png)

__How long do merchants keep their devices?__ 

Most of the merchants tend to keep their devices for about 200 days. The maximum number of days a device was 
associated with a merchant was for 269 days for Sporting Goods Stores while the minimum is as less as 0 or 1 day. 
There are also a few devices that have been provisioned and disassociated multiple times with the same merchant 
and device with the same serial number. These have been represented with negative values in the interactive dashboard.

__What types of issues have these merchants called into Customer Support about and for which devices?__

Merchants have registered various issues with respect to the hardware/software troubleshooting, 
functionality, training, account set up and other questions related to order processing, account 
cancellation and contract terms. 

Since there are various account/funding or other generic questions on may be the company or 
company policies, application and contract terms, there have been issues or questions registered 
even from merchants who do not have a device associated currently. 

Again, the interactive dashboard will provide much more information on how the issues vary with 
different devices and merchant types.

__What are some ways we could improve the merchant experience?__

Here are some observations that could be inferred from the data -

* Clover has the highest number of merchants and devices in the Services category followed by Retail and restaurants
* There are 35,361 merchants without a device associated to them
* Device Type 9 with 16,672 devices associated to merchants has the least number of cases/issues registered while device type 13 has the highest number of devices associated to merchants at 46,672 and highest number of issues at 157,615
* The most rampant issues seem to be related to Education/Functionality. trouble shooting go hand in hand.
* Services category with the highest number of devices has the least number of cases per device on an average among the bigger categories at 3.41 issues per device while restaurants have the most
* Clover has the least number of merchants in the transportation industry with Airlines, Cars and railroads being some of the categories with lowest merchants
* Most common issue type seems to be related to education/functionality. Looking deeper into the reason subtype, software functionality issues are minimal and request training and application education issues peak for almost all devices, merchants may be more interested in training and education rather than complain about functionality issues
* Hardware and Dashboard education/functionality and troubleshooting issues are critical and seem to be higher which could affect the overall experience of the merchant
* There are numerous new merchant/set-up cases as well most of which have a subtype of activation code or send email and could mean the activation code is being sent through email and not being validated correctly or is being timed out

Recommendations -
* Better documentation, video recording or in-person training to help with training and/or education
* Activation code may be a low hanging fruit to solve
* Breaking out the functionality/education into its own buckets to identify functionality issues and education related cases might help in pin pointing various problems
* Fix email feature so that activation code issue is resolved which will make the set up process a pleasurable experience for the merchant
* Most of the merchants used Clover devices and discontinued after around 150-200 days. Identify such merchants and provide incentives (monetary benefits or increase subscription time or whatever Clover deems fit) to such merchants and to re-associate them with Clover.
* Provide better customer support and make sure the customer support executives are better equipped
* Device 9 has fewer issues registered comparatively. Identify the features that make this device stand out and look at integrating them in devices 5 & 13

Some ways to increase market coverage -
* Some of the merchants have a device associated and disassociated multiple times which leads us to believe that some merchants like Clover and are willing to offer a second/third chance to work with Clover. Identify the reason for them to disassociate and provide better solutions for those problems
* Increase presence on social media (SEO)
* Minimal merchants in the transportation industry leads us to believe that Clover devices do not go well with mobile or cellular networks. Target merchant types like airlines, cars, railroads to expand merchant base
