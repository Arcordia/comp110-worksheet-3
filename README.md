# COMP110 Worksheet 3: Flowcharts and pseudocode

This is the base repository for COMP110 Worksheet 3.

Fork this repository, and edit `README.md` to show your pseudocode solving the worksheet task. Tip: use triple backticks to preserve spacing, e.g.:

```
Program start

print ("please input all words on the terminal. Once done type FINISHED to continue")

create INT "dbLength"

test input
	if "FINISHED"
		end loop
	else
		store the inputted string in database of words
		dbLength = dbLength +1

lives = 4

loop until lives = 0
{
output "you have" lives "lives remaining"

set dbRand as random number 1-dbLength

output ("input the word" get database = dbLength "and tell me how similar it is. If it's correct, input CORRECT to finish")

if input = CORRECT
	end program
else
	set similar = input
	lives = lives -1
if
	lives = 0
	output ("I am sorry that I have failed you")
	end program
else
	return to start of loop
}
```

flowchart link: https://drive.google.com/file/d/1iN0Sbfgc5ZvSRNQ0ufkvUPTLQ_eHCBow/view?usp=sharing