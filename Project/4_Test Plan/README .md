
# HIGH LEVEL TEST PLAN

| Test id | Description      | Expected input | Actual output | Expected output | Passed or Failed |
| ------- | ------| --------------- |---------------|----------|--------|
|  H1     |sensor detection of water overflow        | overflow of water | detects user through alarm|detects user through alarm| Passed |
|  H2     |low,medium,high waterlevel detection       | level of water    | detects user through alarm|detects user through alarm| Passed |




# LOW LEVEL TEST PLAN 

| Test id |Description      | Expected input | Actual output |Expected output| Passed or Failed |      
|-------- |------| --------------- |  -------------|---------|--------|
| L1      |Tank full| Switches motor off | prevents power loss |prevents power loss | Passed |
| L2      | Tank not filled upto a level | Switches motor on |maintains level of water |maintains level of water | Passed|

