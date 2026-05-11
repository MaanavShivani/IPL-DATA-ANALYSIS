🏏 IPL Auction Strategist: Building a Better MVP Metric
Objective: To identify undervalued T20 players by testing the validity of official IPL metrics (Orange/Purple Caps) and engineering a custom Batting Index for franchise auction strategy.



Act 1 & 2: The Myth of the Orange Cap
The official IPL Orange Cap is awarded purely on run volume, ignoring pacing and match impact. I hypothesized that bowling dominance (The Purple Cap) is actually a stronger predictor of championship success.

The Analysis:
I joined 15 years of ball-by-ball data with season outcomes to calculate the exact win-rate of teams holding individual caps.

(Make sure to upload your image and link it here!)

Conclusion: The data proves the old adage: Defense wins titles. Teams possessing the Purple Cap winner are significantly more likely to win the IPL trophy.

Act 3: Engineering the "True MVP" Metric
Because the official Orange Cap is mathematically flawed for finding the most valuable batter, I engineered a custom metric.

The Formula: (Batting Average × Strike Rate) / 100

To eliminate statistical noise from lower-order batsmen with inflated "Not Out" averages, I applied a strict 400-run minimum qualifier. This ensured the model only evaluated the heavy-lifting anchors of the tournament.
