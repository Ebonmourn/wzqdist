# wzqdist

the .xlsx is just the csv with the data in a table format and as an excel document

It is important to note that these distances are the raw distance calculation between each waypoint in the steps of the wow-pro leveling guides same for the quest turn ins and quest ids that are used. This means that there is likely to be some fudgy-ness for some zones since some times not all quest id's are actually possible to do or even some waypoints are between zones which this calculation doesn't try to rationalize with it just finds the raw distance between each waypoint x,y coordinate.


tdist(sum) = total distance traveled between map markers in wow-pro leveling guides

tnum(snum) = total number of quest turn-in steps found in the guides

adist(mean) = average distance traveled per quest turn-in step

txp = total xp found from the quests (this will be lower for the starter zones and the level cap zones since they don't have a proper max scaled lvl on the wow db site (were i pulled the quest xp data from)

tlvl = this is a pointless column and can mostly be ignored, its the sum of levels found from the quests

axp = this is the average lvl found from the quests, tlvl / qnum

xp/lvl = this is the average xp found per quest, txp / qnum

txp/alvl/adist = this is the xp, scaled to the average level of the quests, per unit of distance traveled

qnum = this is the total number of quest id's that were used

qdata = this is just a storage of all the quest id's and the lvl and xp amounts a script I made found for the id's
