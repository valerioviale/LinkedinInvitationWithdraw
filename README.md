# LinkedinInvitationWithdraw
A simple script to withdraw linkedin invitation


The code in this file is a JavaScript script that can be used to automate the withdrawal of LinkedIn invitations.

The first section of the code finds all the "Connect" buttons and the confirm buttons on the LinkedIn invitation page. 
It then sets an interval of 2 seconds and clicks both buttons repeatedly until all the invitations are accepted.

The second section defines a function named "withdrawInvitations" that withdraws invitations one by one. 
It first finds all the invitation buttons on the page and then clicks them one at a time. 
After each click, the function checks if there are more invitations left to withdraw. 
If there are, it finds them and runs the function again. If there aren't any left, it logs a message saying that it's done.

To run this script, copy and paste the code into the console of your web browser while on the LinkedIn invitation page. 
