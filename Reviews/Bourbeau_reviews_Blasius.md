Peer Review of: Glenn Blasius
Dataset: Lending Club loan file

Project Objective(as I understand it):  Find best predictor of borrower default & early borrower repayment.
                                        rate of borrower repayment vs other financial options
 Project Strengths:
     Block 3:  Nice thinking/execution of null count  
     Really nice comments showing output used for map()
     Nice, thoughtful  data cleaning

Improvements: 
        Access to raw data , or include it head() shot so one can get familiar
  
Didn't Understand:
       Block 3 :   You conclusion was you should drop 3 features, and then never do it.
                   bar width variable not needed (more style than anything)
       Block 52: Your histogram doesn't show anything in loan status 3(Default) and 4(Late). is that on purpose? If not, then your dataset doesn't have any defaults represented, which would make it hard to predict with.
 
Comment about Code:
       Some units are introduced without much explanation about what it is(Block 60,48)
       No notes at the end to explain what is shown
       Easy to follow code
 
Suggestions for Next Steps:
      One way to tease out some info is to do a count of loan status based on each feature to see which ones show up the most.
      Interesting project, 
Guiding principle: 
      If this was my project, I would analyze the people who default/early payments separately to identify subgroups/trends.