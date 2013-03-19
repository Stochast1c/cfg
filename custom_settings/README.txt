foster's scoreboard

Last Updated: March 5th, 2013

Install Instructions:
-Choose which scoreboard you want, rename it to just "Scoreboard"
-Place it in your ui folder under
		*Steam/steamapps/(steamname)/team fortress 2/tf/resource/ui*
-Place the tf_english file in the resource folder
		*Steam/steamapps/(steamname)/team fortress 2/tf/resource*
-AND YOUR DONE ITS REALLY EASY




Notes:


-The tf_english file is deleted after any update that changes the tf_english file template, i.e. any update that adds items, changes names of items, adds maps, etc.


-If you want to update your tf_english file yourself instead of waiting for me to update it or using the old one, ITS REALLY EASY, simply go into the file in a text editor (notepad or notepad++ work fine) and where it says 

"TF_Scoreboard_Name"			"NAME"
"TF_Scoreboard_Score"			"SCORE"
"TF_Scoreboard_Ping"			"PING"

simply delete NAME, SCORE, and PING and leave the field blank like so:

"TF_Scoreboard_Name"			""
"TF_Scoreboard_Score"			""
"TF_Scoreboard_Ping"			""


AND

-replace the section below

"Scoreboard_Server"			"Server: %s1"
"Scoreboard_TimeLeft"			"Server map time left: %s1:%s2:%s3"
"Scoreboard_TimeLeftNoHours"		"Server map time left: %s1:%s2"
"Scoreboard_NoTimeLimit"		"Server map time left: No time limit"
"Scoreboard_ChangeOnRoundEnd"		"(Map change on round end...) Server map time left: 00:00"

with

"Scoreboard_Server"			"Server: %s1"
"Scoreboard_TimeLeft"			"%s1:%s2:%s3"
"Scoreboard_TimeLeftNoHours"		"%s1:%s2"
"Scoreboard_NoTimeLimit"		""
"Scoreboard_ChangeOnRoundEnd"		""



-make sure to save the tf_english file as a .txt and set "Encoding" to "Unicode"


(Original updated tf_english file can be found @     http://wiki.teamfortress.com/w/images/c/cf/Tf_english.txt     )

