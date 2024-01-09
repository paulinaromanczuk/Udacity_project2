# Udacity_project2 - Investigate medical no-shows dataset

## Aim of analysis:
Check overall proportion of no-show  
Check whether any of variables has a higher proportion than other  

With a focus on questions below (but not limited to):  
Is there a difference between scheduled day and appointment day - do patients that make an appointment much in advance tend not to show up?  
Is alcoholism influencing whether patients show up more often or not?  
Are we increasing chances of patient showing up if we're sending reminders?  
Are there any patients that have a pattern of not showing up? Should we focus on some patients and send them reminders about the visit?  

## Conculsion of analysis:

1. Is there a difference between scheduled day and appointment day - do patients that make an appointment much in advance tend not to show up?   
  Yes, there is visible drop in proportions of "no-shows" the more in advance patient made an appointment  
2. Is alcoholism influencing whether patients show up more often or not?  
  No
3. Are we increasing chances of patient showing up if we're sending reminders?  
  Yes, it increases chances of patient showing up for the appointment by ca. 7%p when patient made the appointment more than 2 weeks in advance  
4. Are there any patients that have a pattern of not showing up? Should we focus on some patients and send them reminders about the visit?
  I've identified ca. 1000 patients that made at least 5 appointments and showed up for less than 50% of them. Reminders were sent only in 28% of the visits - it might be a good idea to either implement a system that will send reminders to everyone or focus on these patients that have a big tendency of not showing up  

Overall, we can see that what might have the biggest impact on whether patient shows up for his/her appointment is the time that passed between the day they've scheduled it on and appointment day. We can increase chances of a patient showing up by sending them message with a reminder. Teenagers are also slacking on showing up - well, to be again young and careless... Nevertheless it might be good idea to consider also sending some reminders to their guardians if possible?  
Last but not least, we've also seen that what has a big impact is number of disabilities that patient is experiencing, which may influence their ability of actually getting to the facility  
