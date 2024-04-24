This is a data frame of the NBA player Draymond Green's career ejections. 
It includes the month, day, year, opposing team (opponent), whether or not the game resulted in a loss for the Warriors, point differential, and quarter in which the ejection happened.
It also includes whether or not Stephen Curry or Klay Thompson were playing in the game when the ejection happened.

This was made out of curiosity after the Draymond Green choked out Rudy Gobert and Gobert commented that Draymond always gets ejected when Stephen Curry is not playing that game. 
I was looking to assess the validity of these claims and so collected this data.

Hopefully this data can be of some use to other people as well!


**A few notes:**

Being on the bench at the time of ejection counts as playing, as long as they were available to be played at the time of ejection.
point_diff_at_ej is simply (Warriors pts - Opponents pts) AT TIME OF EJECTION, not the point differential at the end of the game! So if a point differential is -10 it means, when Draymond was ejected, the warriors were down by 10. I intended for the "loss" column to be the metric for overall impact on the team.


**Columns:**
month,	day,	year,	opponent,	with_steph,	with_klay,	loss,	point_diff_at_ej,	quarter, type, pts, rebs, ast, type, fg, fga, fg_per, 3p, 3pa, 3p_per, ft, fta, ft_per, orb, drb, trb, stl, blk, tov, pf, box_pm, bb_ref_link, vid_link


**Updated 4-24-2024. 
All ejections/stats are up to date as of the end of the 2023-24 season.**

Dimensions:
9 x 20
