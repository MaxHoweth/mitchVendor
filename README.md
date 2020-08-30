# MitchVendor Web Interface 

### Turning Hours of Paperwork Into Seconds on your Phone or PC

### PURPOSE
The MitchVendor program is a combination of a web and mobile interface paired with shared database. Designed to streamline management and stocking of vending machines. This program was created for my freind in Southern Califrnia who mentioned how he spends a major portion of his time at work filling out paperwork and reading locations off a sheet. He asked if it would be possible to digitize and streamline this work and I said of course! Thus MitchVendor was born.

This is the web interface which is intended for more of a ownership role. The web interface has many uses. For financials you can see the big picture of revenue, profitsm and expenses. You can also add, remove, and edit location and their addresses. Additionally you can add and remove employees, edit their schedules and permissions, and view and calculate their work hours.

### TECHNOLOGIES - WEB INTERFACE
The web interface uses [Twitters Bootstrap](https://getbootstrap.com/) as a front end library. The interface uses [Google Firebase](https://firebase.google.com/) for backend data storage using JSON objects as well as authentication. It is integrated with the [Google Maps API](https://developers.google.com/maps/documentation) for forward & reverse geocoding and data visualization. The whole system is hosted on Amazon Web Services [Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/), using [EC2](https://aws.amazon.com/ec2/) for data storace, and [Route 53](https://aws.amazon.com/route53/) for routing and DNS. The system is additionally setup for coninuous integration and deployment using [CodePipeline](https://aws.amazon.com/codepipeline/) and [CodeDeploy](https://aws.amazon.com/codedeploy/)


### USAGE 
Usage is posible through the web portal at www.mitchvendor.com 

If you are authorized to use the software you will have been issued login credentials.

Alternatively if you are inspecting the software for the purpose of checking the projects listed on my resume permission limited credentials are as follows:

Email:    **resume@noemail.com**

Password: **GotTheJob1**
