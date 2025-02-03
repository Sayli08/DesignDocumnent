## Main Goals of Writing Design Documents
a. Techincal
b. Organizational
c. Buy In

- Its Usually about answering questions
- Those Questions could be technical.
- The technical part of the design document
- How are we actually going to do this
- Which systems are we going to change and how and what's that going to do to those systems 
- We also answer organizational questions in design docs
- Who's going to own the android side logic of XXX or IOS side logic in XXX
- Which teams own XXX model and which team owns the YYY
- Design docs are typically where these system delineations are designed and all of these teams buy in
- Last one that happens more frequently as you progress in your career are even more buy in type of questions
- Is this project worth doing ? Is it worh doing this way ? What about the other ways we could have accomplished the same goal
- When it comes to convincing all the relevant stakeholders that your way of doing a project is the right way probably you are writing the design doc or technical writing of some form to convince all of those stake holders

## Right Tool depends on the job
A. 
- Design Doc are not always the right tool for the job
- Design Docs are useful especially for conveying and convincing - these complex technical things , these organizational questions but sometimes you don't need them
- On the Smallest side of the scale if it is the type of the thing that can be decided in the context of a single CL
- Do I put this logic in this helper function or in the main function - you probably don't need to write design doc for that. You can just put it in a CL, send it for the Review.
- May be write a description that says, I put this in the helper function thats the recommeneded java style and you can avoid generating artifacts that no one wants to look at and no one reads 

B.
- Sometimes that is not enough we need to send 2-3 Cls and those 2-3 Cls need to work together and someone needs to understand how they all work together and you need to convince your reviewers that these 2-3 CLs all work together and in those cases sometimes just writing up what you are going to do and why you are going to do it in a bug is good enough and then you have this bug as you artifact of this instance of technical decision making .
- You have this bug to link in the CLs and all of the different reviewers you might need to ask 
- You can say go look at this Bug that explains why I need to make this specific change to XX and how that relates to YY platform change  I am making in the linked CL
- And frequently thats enough for the changes that may be couple of Cls
- May be they are entirely uncontroversial
- May be they are folloewing a pattern that was just done with somethinbg very similar
- You again avoid generating artifact that no one reads and you spend bunch of time really making a nice design doc on
  
C. 
- A lot of problems we work on though are really complex than 1/2 Cls
- They are more complext than whether or not I put this "if statement" here or there and this is where we start getting into writing documents that describe our decision making , describe the tradeoffs that we are making and why we are making it
