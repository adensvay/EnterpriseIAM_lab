Mar172026: Officially started setting up machines today. Followed a YT tutorial (https://youtu.be/8_TE1Sbe7f0?si=8ymeh9qNk1gd2NlN). We are
basically using Windows Machine DC01 - Domain Controller -> the one with AD + CLIENT01 - client machine. Took about ~3hours today to configure 
things properly and finally get a successful ping between machines. Had to rewind the YT tutorial a few times and also refer to GPT for in depth 
help. The goal here is to get the machines talking to eachother and blaze through the configruation stage. I believe the next step is setting up 
GPO and OUs. 

Mar182026: Today was really a sense of accomplishment. After we finished setting up static network yesterday, we joined the domain from client01
it did its whole restart thing, and I was able to sign into a newly created account I made in DC01 AD machine. Its actually really easy and intuitive. 
I created a group called IT, and I gave myself credentials and tested it out in the client machine. It made me create a new password - then BOOM. 
First simple step in AD Lab complete. Next time I am going to create a few more users in the department, and also create new OUs and make a hierarchy chart/schema.
