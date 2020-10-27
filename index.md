# Welcome to KiwiBot3.0

KiwiBot3.0 is a Automated JavaScript Discord Bot that transfers information form the World of Tanks API to Discord which allows for increase communication during Community Events on the games Global Map Game Mode.

### World Of Tanks
[World of Tanks Website](https://worldoftanks.asia/)
World of Tanks (WoT) is a massively multiplayer online game developed by Belarusian company Wargaming, featuring mid-20th century (1930s–1960s) era combat vehicles.
Games Consist of 15v15 matches where each player controls one vehicle with only one life. The Objective of the game is to Capture the other teams base or destroy all their vehicles.
#### WoT Campagins
World of Tanks Campaigns are based around the games [Global Map](https://asia.wargaming.net/globalmap/) which is on a external website. The global map is based on a real map which marks areas or secters called provinces. Each clan as a cirtain amount of chips which can be place on provinces to allow the clan to fight for that piece of land. if the clan captures that land they can then move out to take more. Any clan can fight for each provices which can create turniments which are done in a knockout style soo.. 16, 8, 4, 2, 1 till the winner is found. Each battle fought is battled in the main game with a orginised team of 15v15 or 10v10 with the same objectives as the normal matches (defeat all vehicles or capture the other teams base). Games are 15mins long and are every 15mins which means there is small turnover times between matches. 

# Blogs 

## Blog - Problem 
Communication is a key feature in teamwork and the better you can get information across the better you team can preform. In the Competitive Community of World of Tanks Communication between officers during campaigns can lack crucial information needed for other members to plan their night and can disrupt strategy's and plans.
Seeing as their is limited time between matches this can cause issues with people not knowing which battle to be in as there can be up to 10 battles at once and the clan needs to split between all the battles.
#### Proposed Solution
To create a automated communication bot to gather information from the Global Map API and display this information in a easy to read and find format in discord where clan members can find it. Since this is pulling directly from the API it will be available minimum of a hour before instead of 10-15 minutes before and allow members to plan accordingly.

## Blog - Compliations
Issues during building have come up left and right. one big issue is ways to deal with the battle data from the API, the solution i am currenly using is holding all the varible in code and calling them when needed but this can cause issues when formatting and trying to order data. this has worked well and doesnt have any big issues. Another option is to create a database for each instance/Server that updates the battle data every 15min and then pulling information stright from the database. this would allow for more detailed coustomisation of the data and better formatting later. This methoed i will probally look into later in production but will stay with data in the code for the current moment.

## Blog - Update 
Currently have the program running consistanly with battles being posted and deleted accordingly. Two main problems im having at the moment, 1. formatting the games time down from full length to only Day, Hour, Min. problem 2. is sorting and not posting any games that have a start time prior to the posting of the messages so that the bot doesnt show old games.


