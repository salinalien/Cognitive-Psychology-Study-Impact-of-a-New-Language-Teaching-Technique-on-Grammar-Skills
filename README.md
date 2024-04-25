# Cognitive-Psychology-Study-Impact-of-a-New-Language-Teaching-Technique-on-Grammar-Skills
This repository contains data and analysis code for a study investigating the effectiveness of a new foreign language teaching technique on grammar skills from a cognitive psychology perspective.

## Analysis used
ODS graphics; 
 
PROC ttest data = _TEMP0.german plot(shownull)=interval; 
	class Group; 
	var Change; 
	title "Two-Sample t-Test comparing control vs treatment group on the effectiveness of a new foreign language teaching technique on grammar skills"; 
 
run;


## Conclusion
The p-value associated with the F-test comparing the effectiveness of the new teaching technique is greater than the significance level (e.g., p > α), it implies that there is not enough statistical evidence to conclude that the new technique is more effective than the standard tutoring. In other words, there is no significant difference in grammar skills improvement between the two groups (new technique vs. standard tutoring).
