# Investigating-a-Drop-in-User-Engagement
Triaging product and business problems like a Yammer analyst 

The problem description can be found here: https://mode.com/resources/sql-tutorial/a-drop-in-user-engagement/

# Problem

You show up to work Tuesday morning, September 2, 2014. The head of the Product team walks over to your desk and asks you what you think about the latest activity on the user engagement dashboards. You fire them up, and something immediately jumps out. (https://mode.com/resources/sql-tutorial/a-drop-in-user-engagement/)

The above chart shows the number of engaged users each week. Yammer defines engagement as having made some type of server call by interacting with the product (shown in the data as events of type “engagement”). Any point in this chart can be interpreted as “the number of users who logged at least one engagement event during the week starting on that date.”

You are responsible for determining what caused the dip at the end of the chart shown above and, if appropriate, recommending solutions for the problem.

# Getting oriented

Before you even touch the data, come up with a list of possible causes for the dip in retention shown in the chart above. Make a list and determine the order in which you will check them. Make sure to note how you will test each hypothesis. Think carefully about the criteria you use to order them and write down the criteria as well.

Also, make sure you understand what the above chart shows and does not show.

# Digging in

Once you have an ordered list of possible problems, it’s time to investigate.

For this problem, you will need to use four tables. The tables names and column definitions are listed below—click a table name to view information about that table. Note: this data is fake and was generated for the purpose of this case study. It is similar in structure to Yammer’s actual data, but for privacy and security reasons it is not real.

# Making a recommendation

Start to work your way through your list of hypotheses in order to determine the source of the drop in engagement. As you explore, make sure to save your work. It may be helpful to start with the code that produces the above query, which you can find by clicking the link in the footer of the chart and navigating to the “query” tab.

Answer the following questions:

- Do the answers to any of your original hypotheses lead you to further questions?
- If so, what are they and how will you test them?
- If they are questions that you can’t answer using data alone, how would you go about answering them (hypothetically, assuming you actually worked at this company)?
- What seems like the most likely cause of the engagement dip?
- What, if anything, should the company do in response?

——————————————————————————————————————————————————————————————————————————————————————————————

# Preparation and Prioritization 

Starting with hypotheses and evaluating them with your team is often the most important part of these problems. Done well, you can save hours of time digging through the data. Here's some possible causes for this problem: 

* Broken feature: Maybe a key feature in the product is impossible to use and people are logging in less often as a result? 
* Broken tracking code: Perhaps the coe that logs events itself was overwritten, deleted, or tampered with? 
* Broken marketing channel: Maybe a channel like Google Adwords, Facebook ads, or email was shut off or stopped converting?  
* Marketing event causing elevated traffic numbers: It could have been that a one off marketing blitz attracted a bunch of cheap users who didn't ultimately retain, leading to what looks like a huge drop-off in engagement. 

# Solving the case 

1. Start by 
