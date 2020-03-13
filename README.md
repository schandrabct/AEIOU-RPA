# AEIOU-RPA
The new Cross-Platform RPA tool
Feature/Wish

Remarks

What the tool should do / offer?

Project AEIOU

Stability

One of the most important things, as there are some tools that you write the code today and tomorrow morning, is not running. 

Once the bot is written, it should not break with environment changes. In addition, it should not be affected from the vagaries of the target applications, such as web sites and their codes. 

The bots crash due to a multitude of reasons. Broadly put, they can crash if there is any problem in one or more of the 5 categories. Therefore, it is imperative that the bots be designed and written in a way, in a tool, that makes them immune to such situations.
Some simple design and development tricks here, and you can be sure that the bot will not fail, even if the environment is changing. We can ensure this by using enhanced D2 and D3 methods. Some of this will depend on the Tech-Stack also.

Security

I really encourage RPA vendors to document more about security as this most common question from every client. 

• Not a single bit of information should go out of the organization
• Any information exchange with Tool portal and License Manager must be transparent
• The access to bot should be secure (Access Control?)
• The bot code should be secured (Code Control?)
• Multiple Encryption methods / Credential Management

• The bot code should not be in the source code format
• The bot should not be accessible to unauthorized personnel
• The bots should not be modified by unauthorized personnel
• The bot should not rely on an uncontrolled cloud/licensing manager that demands information about the license, identification and bot run logs
• The bots should reside in a secured location
• The bots should not send information out of the system, for any purpose
• Even for licensing purpose, the bot should not call out/home
• If required, the bots can even be encrypted to enhance security (unlike AA, which encrypts the bot just to hide the ultimate source XML code only)

Cross Environment

Most RPA tools based on DotNet framework so they work only on windows and I see it is one of the limitations, not all systems are windows, so we need to run on a Mac, Linux,... 

• We need a tool that is pure cross-platform 
• This tool should be able to operate on all diverse platforms 


• This tool will operate on all platforms (refer technology development roadmap)
	• Windows, 
	• Mac, 
	• ARM, 
	• Linux, Ubuntu, 
	• Android, IOS, Raspberry Pi, etc.)

Mobile Application

Some may assume that it is not mandatory but nice to have but I think in today's market, I need a mobile application so I can access the bots and monitor them anywhere. 

• A dashboard (and possibly a monitoring system) on Android and IOS. 
• However, this can still be done without a dedicated app, using mobile web browsers

• Since the application can run on just about any platform, an app should be easier to build and should always be on the technology roadmap.
• Although the option of accessing via web browser on the smartphone is available, we can put the app on the roadmap based on the desirability and actual usefulness

Exception Handling 

A good way to handle exception and logs tracing. 

• Guided and built-in exception identification and handling
• Ability to make and utilize logs in multiple formats

• Built-in exception handling guidance and options
• Some activities will have optional EH and some will have mandatory EH
• Ability to easily create, generate and update log files using standard notation in multiple formats as per your convenience (within txt, csv, JSON, xml, html, etc.)

Community 

A big supportive community to help while developing and answer questions. 

• A familiar, upcoming, powerful technology stack that is already adopted by a large number of people
• Utilize the existing pool
• Motivate more people to join in

• There are more than 2 Million people who make up the technology stack users and developer community. 
• This will need some building up in terms of skills transfer towards automation. 
	• However, this is a minor alignment.
• People need to be motivated and excited to use the tools and contribute. 
	• Recognize their efforts and reward them

Databases 

Support most kinds of databases and their operations. 

Adapters for databases should be available

• Support ANY database, 
• on all platforms, 
• from ANY vendor

Emails 

Support most kinds of Emails and their operations. 

Outlook, Gmail, Webmail, and what else?

• Support ANY Email software

Version Control & debugging tools

 

Internal Configuration Management or External Configuration Management

• This can be plugged in using standard and free tools. 
• Not much of a problem, though place on development plan is not yet decided

Triggering 

Most RPA tools support run bot based on schedule or run manually but what if I want a specific trigger to start the run.

Multiple triggering mechanisms should be available. 

• Time based trigger, 
• Manual triggering, 
• Event based trigger 
• All kinds of triggering is available - Define your own trigger, even from other bots

Pricing

 High End, Medium range, Low end, Models, Methods, Slabs, Discounts

You already know the prices for other tools. I don't need to expand on this. However many models are available, confusing the buyers. Total Cost of Ownership must be calculated and evaluated rather than just looking at the price list and discounts

This is the sweetest part. Stay Tuned
