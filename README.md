V1.0
***Make sure to reverify party order in trig / FF after Endwalker.*** 

**Set Up**

You need triggernometry https://github.com/paissaheavyindustries/Triggernometry/releases/latest

Please make sure that Default party sort is enabled in FF (Tank, Healer, DPS)
![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartySortInGame.png?raw=true)

In triggernometry it is configured under "Options > Edit Configuration > Final Fantasy XIV" that player list set to `Player First rest by Custom Order`. Then Go through and make sure that your `In Game Role Sort Settings` and your Triggernometry Player List Custom Order match 1 to 1.  ***If they do not then the auto markers will mark the wrong players***


 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep1.png?raw=true)
 
 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep2.png?raw=true)
 
 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep3.png?raw=true)
 

The following Macros will need to be created and added to the F1-F9 keys

F1: `/mk attack <1>`

F2: `/mk attack <2>`

F3: `/mk attack <3>`

F4: `/mk attack <4>`

F5: `/mk attack <5>`

F6: `/mk attack <6>`

F7: `/mk attack <7>`

F8: `/mk attack <8>`



F9:
````
/merror off
/mk clear <1>
/mk clear <2>
/mk clear <3>
/mk clear <4>
/mk clear <5>
/mk clear <6>
/mk clear <7>
/mk clear <8>
````
It will look like this.  It does not have to be visible to work but it does have to exist on the class you are playing as. 
![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/InGameHotbar.png?raw=true)


**Editing**

If you wish to Edit the Keybindings from F1-F9 you will need to go into Mark1-3 as well as Wipe Reset. Change keycode for each trigger (25 in total, 8 in each Mark1-3 and one in Wipe reset) to the desired keybinding. Reference https://docs.microsoft.com/en-us/dotnet/api/system.windows.forms.keys?view=net-5.0 for Keycodes.
![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/HowToEditKeybinding.png?raw=true)

![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/WipeResetMarker.png?raw=true)

If you wish to edit the priority list you will need to go into each of the triggers 
Job1Priority-Job3Priority and change the numbers assigned to them there

RPR: 01
  
MNK: 02

DRG: 03
 
NIN: 04 
 
SAM: 05 
 
PLD: 06 
 
WAR: 07 
 
DRK: 08 
 
GNB: 09  

BRD: 10 
 
MCH: 11 
 
DNC: 12 
 
BLM: 13 
 
SMN: 14 
 
RDM: 15 
 
WHM: 16 
 
SCH: 17 
 
AST: 18

SGE: 19
