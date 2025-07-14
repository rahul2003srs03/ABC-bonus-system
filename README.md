Loyalty Points & Bonus Distribution Report
ABC Real-Money Gaming Platform

Introduction:
ABC is an internet gaming firm that offers multiplayer games like Ludo for real money. Gamers create accounts on the site, make deposits, and engage in user-to-user gaming. Loyal gamers are rewarded with loyalty points based on their behaviour, and the platform makes money by charging a nominal fee.
Based on established business principles, this report computes loyalty points by analyzing player activity. Additionally, it offers suggestions for enhancing the current point system as well as insights on bonus distribution tactics.
Problem Statement:
The goal of this assignment is to:
•	Calculate loyalty points for players using the defined formula.
•	Analyze loyalty per time slot (S1 and S2) for specific dates.
•	Rank players monthly based on loyalty points.
•	Propose a fair bonus distribution from a ₹50,000 reward pool.
•	Evaluate the fairness of the loyalty formula and suggest improvements.
Data Summary:
User Activity Categories:
•	Deposits: Money added to the platform.
•	Withdrawals: Money taken out from the platform.
•	Gameplays: Games played between users.
Time Frame Analyzed: October 2022
Data Sources:
•	Deposit Data
•	Withdrawal Data
•	User Gameplay Data





Loyalty Point Formula:
Loyalty Points =
(0.01 * Total Deposit)
+ (0.005 * Total Withdrawal)
+ (0.001 * max (#Deposits - #Withdrawals, 0))
+ (0.2 * Number of Games Played)
Slot-Wise Loyalty Points (Specific Dates):
	Each day is divided into two slots:
•	S1: 12 AM to 12 PM
•	S2: 12 PM to 12 AM
Player wise loyalty points were calculated for:
•	2nd October – S1
•	16th October – S2
•	18th October – S1
•	26th October – S2
Monthly Loyalty Ranking – October:
For October 2022, all user activity was analysed to compute total monthly loyalty points.
Players were ranked based on:
•	Primary: Loyalty Points
•	Secondary (tie-breaker): Number of Games Played
Top 50 players were selected as the loyalty leaderboard.
Average Metrics:
•	Average Deposit Amount: ₹ 5492.185
•	Average Deposit per User (October): ₹101402.15
•	Average Games Played per User (October): 344.47 games



Bonus Distribution Strategy – ₹50,000:
The company aims to reward the Top 50 ranked players with a total bonus pool of ₹50,000.
Objective: Keep the bonus distribution simple yet fair by recognizing top-performing players more significantly, while still rewarding broader participation.
tier1_bonus_pool = bonus_pool * 0.40 # Top 10 players get 40%
tier2_bonus_pool = bonus_pool * 0.60 # Remaining 40 players get 60%

Tier Breakdown:
Tier	Rank Range	Players	% of Bonus Pool	Total Bonus (₹)	Bonus per Player (₹)
1	1-10	10	40%	₹20,000	₹2,000(each)
2	11-50	40	60%	₹30,000	₹750 (each)

Why This Approach?
•	Simple and easy to implement.
•	Rewards top 10 heavily (who drive most engagement).
•	Encourages players to stay in the top 50 for guaranteed bonus.
Evaluation of Current Formula
 Strengths:
•	Encourages deposits.
•	Includes gameplay for balance.
•	Rewards consistent depositors.
Issues:
•	Heavily biased toward high deposit amounts.
•	Does not reward game wins or outcomes.
•	Gives points even for withdrawals.
•	Doesn't factor in consistency or daily activity.


Conclusion
•	Loyalty points were successfully calculated using defined rules.
•	Bonus distribution using a hybrid model (70% loyalty, 30% gameplay) ensures fairness.
•	The current formula, while functional, can be improved to better reflect true user loyalty and engagement.
Future versions of the formula can integrate game outcomes, cap financial impact, and promote consistent daily use of the platform.
Appendix
•	Jupyter Notebook: 
•	Calculations and visualizations (available in code)
•	Code for loyalty calculation, ranking, and bonus allocation

