# Tut_Jenkins_MyApp

Steps for Multi branch Pipeline in AWS EC2 Linux:

Jenkins >> Create Job >> Select “Multibranch Pipeline” >> OK 

\>> Branch Sources >> Attach Sources >> Add source >> Enter “Project Repository” https://github.com/nikhil2050/Tut_Jenkins_MyApp.git >> In “Build configurations”, provide “Script Path” that is in Git >> In “Scan Multibranch Pipeline Triggers” >> Select interval >> Save

\>> Verify all sub-Job statuses

Note : Install Maven & Java JDK (instead of JRE). Refer :  
https://docs.aws.amazon.com/neptune/latest/userguide/iam-auth-connect-prerq.html

