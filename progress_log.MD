Mar172026: Officially started setting up machines today. Followed a YT tutorial (https://youtu.be/8_TE1Sbe7f0?si=8ymeh9qNk1gd2NlN). We are
basically using Windows Machine DC01 - Domain Controller -> the one with AD + CLIENT01 - client machine. Took about ~3hours today to configure 
things properly and finally get a successful ping between machines. Had to rewind the YT tutorial a few times and also refer to GPT for in depth 
help. The goal here is to get the machines talking to eachother and blaze through the configruation stage. I believe the next step is setting up 
GPO and OUs. 

Mar182026: Today was really a sense of accomplishment. After we finished setting up static network yesterday, we joined the domain from client01
it did its whole restart thing, and I was able to sign into a newly created account I made in DC01 AD machine. Its actually really easy and intuitive. 
I created a group called IT, and I gave myself credentials and tested it out in the client machine. It made me create a new password - then BOOM. 
First simple step in AD Lab complete. Next time I am going to create a few more users in the department, and also create new OUs and make a hierarchy chart/schema.

Mar232026: Advancing the AD lab litte by little. Today we finished creating basic users in AD across three OUs: IT, Sales, and HR. I have created about 15 users per OU.
They consist of about five users that represent either real peeople I know or famous individuals I do not personally know. In total, we have 15 manually created users and 
passwords with three OUs. After this, I watched a YT video from EastCharmer where she walked through how to create GPOs. I started on 1/5 of the GPO activities she outlined,
and worked on implementing Computer->Policy password GPOs. Within the 'Password Policy GPO' we changed attributes such as complexity, minumum length, age, etc. So far pretty basic
and conceptually digestable. I plan to follow the rest of the GPOs from the tutorial and simultaneously document what I have learned from the beginner portion of the project. I for see 
more in depth tool exploration in AD across configuring DHCP so that users can browse the internet, and manually scripting users and groups using powershell. 
