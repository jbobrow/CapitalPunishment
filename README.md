# CapitalPunishment
Stats on executions in the US from 2010 - 2015 parsed from http://www.deathpenaltyinfo.org/

Using Kimono's quick API tool, each json file was created like so...
curl -K --include --request GET "https://www.kimonolabs.com/api/ondemand/ekm25qni?apikey=##############&kimpath1=execution-list-2015" >> 2015.json