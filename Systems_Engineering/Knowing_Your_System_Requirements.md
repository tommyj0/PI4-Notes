# Knowing Your System Requirements

## EARS: Easy Approach To Requirements Syntax

Created by Intel and Rolls Royce. Expands the synta to a series of patterns for specific types of functional requirements

|Keyword|Syntax|
|---|---|
|Ubiquitous|The \<system name\> shall \<system response\> [the] \<optional object\>|
|Event-Driven|WHEN \<trigger\> \<optional precondition\> the \<system name\> shall \<system response\> [the] \<optional object\>
|Unwanted Behaviour|IF \<unwanted condition or event\> \<optional precondition\>, THEN the \<system name\> shall \<system response\> [the] \<optional object\>|
|State-Driven|WHILE\<system state\>, the \<system name\> shall \<system response\> [the] \<optional object\>|
|Optional Feature|WHERE \<feature is included0\>, the \<system name\> shall \<system response\> [the] \<optional object\>|
|Complex|(Combinations of above patterns)|