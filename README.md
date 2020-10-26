# NomiCakes
Fixed NomiCakes for version 9.0.1

Let me know if you find any more issues

## Changes

  - Added local function **GossipResize** since original was removed
  - Replaced **\_G[buttonName]** with **GossipFrame_GetTitleButton(i)** in **DecorateNomi** function
  - Replaced **\_G[buttonName .. 'GossipIcon']** with **GossipFrame_GetTitleButton(i).Icon** in **DecorateNomi** function
  - Replaced **'interface\\\gossipframe\\\workordergossipicon'** with **'interface/gossipframe/workordergossipicon'**
