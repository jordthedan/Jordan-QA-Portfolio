# League of Legends — Match Telemetry Analysis

**Match ID:** OC1_701148593  
**Data Source:** Riot Games Match-V5 API  
**Region:** OCE  

---

## What I Did

I extracted personal match timeline data from match OC1_701148593 
and analysed the event structure from a QA perspective. I observed 
correct chronological order of events. WARD_PLACED occurred the most 
times at 297 events. I also noticed that ITEM_DESTROYED likely refers 
to a sale of an item or use of a consumable (healing pot, elixir etc). 
CHAMPION_SPECIAL_KILL to me is a double kill as the previous event is 
CHAMPION_KILL. Doing this activity has given me some hands on experience 
reading event payloads and thinking about what occurred in game based on 
my own game knowledge, to represent what would be correct or incorrect 
behaviour.

---

## Raw Event Data

The full match timeline export is included in this folder:  
→ [LoL_Match_Telemetry_Events.xlsx](./LoL_Match_Telemetry_Events.xlsx)
