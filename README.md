# CapitalPunishment
Stats on executions in the US from 2010 - 2015 parsed from http://www.deathpenaltyinfo.org/

Using Kimono's quick API tool, each json file was created like so...

```curl -K --include --request GET "https://www.kimonolabs.com/api/ondemand/ekm25qni?apikey=##############&kimpath1=execution-list-2015" >> 2015.json```

The article that sparked my curiosity:
http://www.nytimes.com/2015/04/22/us/victims-in-boston-marathon-bombings-are-split-on-death-penalty.html

The stats that upset me:
http://www.amnestyusa.org/pdfs/DeathPenaltyFactsMay2012.pdf
"The death penalty is racially biased. Since 1977, the overwhelming majoirty of death row defendants(77%) have been executed fro killing white victims, even though African-Americans make up about half of all homicide victims."

**Motivation:**
My intention for pulling this data is to create a data visualization of the history of Capital Punishment. While the biases are clearly outlined by Amnesty International, I think the data will speak clearly for itself and tell an equally compelling story, raising questions and sparking conversation around inequalities and our ability to mitigate them.

**Help:**
If you find this interesting in helping in the process, this data is currently only a subset from 2010-2015 and it would be wonderful to find this data for all the way back to 1978... or before that as well. You can take a look at the format, as well as the tool I used here: http://kimonolabs.com

Additionally, the data can probably take on a bit better shape. (i.e. I want to change the victim information to be an array of the victims with their race, currently it is in a form that is less friendly to parse)

Any comments, data, tips are welcome. Thanks!

Jonathan Bobrow
jbobrow@gmail.com
