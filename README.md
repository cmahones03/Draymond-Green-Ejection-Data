This is a data frame of the NBA player Draymond Green's career ejections. 
It includes the month, day, year, opposing team (opponent), whether or not the game resulted in a loss for the Warriors, point differential, and quarter in which the ejection happened.
It also includes whether or not Stephen Curry or Klay Thompson were playing in the game when the ejection happened.

This was made out of curiosity after the Draymond Green choked out Rudy Gobert and Gobert commented that Draymond always gets ejected when Stephen Curry is not playing that game. 
I was looking to assess the validity of these claims and so collected this data.

Hopefully this data can be of some use to other people as well!



A few notes:

Being on the bench at the time of ejection counts as playing, as long as they were available to be played at the time of ejection.
Point differential is simply Warriors points - Opponents points AT TIME OF EJECTION, not the point differential at the end of the game! So if a point differential is -10 it means, when Draymond was ejected, the warriors were down by 10. I intended for the "loss" column to be the metric for overall impact on the team.


**Columns:**
month,	day,	year,	opponent,	with_steph,	with_klay,	loss,	point_diff_at_ej,	quarter

Dimensions:
9 x 20
