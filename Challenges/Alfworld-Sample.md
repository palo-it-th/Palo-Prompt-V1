# Alfworld Sample

## Task 1

Task: examine a clock with a lamp
-= Welcome to TextWorld, ALFRED! =-

You are in the middle of a room. Looking quickly around you, you see a bed 1, a desk 1, a shelf 1, a sidetable 1, a drawer 1, a drawer 2, and a garbagecan 1.

Your task is to: look at alarmclock under the desklamp

```
alfworld-play-thor $ALFWORLD_DATA/json_2.1.1/train/look_at_obj_in_light-AlarmClock-None-DeskLamp-328/trial_T20190908_175801_507648/
```

## Task 2

Task: Heat a potato and place it in the sink.
-= Welcome to TextWorld, ALFRED! =-

You are in the middle of a room. Looking quickly around you, you see a cabinet 1, a cabinet 2, a cabinet 3, a microwave 1, a cabinet 4, a cabinet 5, a countertop 1, a cabinet 6, a countertop 2, a garbagecan 1, a coffeemachine 1, a toaster 1, a sink 1, a fridge 1, a sinkbasin 1, a stoveburner 1, and a stoveburner 2.

Your task is to: put a hot potato in sinkbasin

```
alfworld-play-thor $ALFWORLD_DATA/json_2.1.1/train/pick_heat_then_place_in_recep-Potato-None-SinkBasin-14/trial_T20190908_231731_054988/ --controller oracle_astar --debug
```

---

Context for the game mission:

1. Setting: You're in a small, cozy bedroom in a modern apartment.

2. Time: It's late evening, and the room is dimly lit.

3. Character: You're playing as ALFRED, an artificial intelligence assistant embodied in a robot form. Your purpose is to assist humans by completing various household tasks.

4. Room layout:

   - The bed is against one wall, neatly made with a dark blue comforter.
   - The desk is positioned near a window, currently closed with curtains drawn.
   - The shelf is mounted on the wall above the desk, holding a few books and decorative items.
   - The sidetable is next to the bed, typically used for a bedside lamp and personal items.
   - There are two drawers: one is part of the desk, and the other is in the sidetable.
   - The garbagecan is tucked in a corner of the room.

     4.1 Room layout details:

   - Bed: On the bed: Two pillows and a folded throw blanket
     Under the bed: A storage box containing extra bedding
   - Desk: On the desk: A desktop computer, the desklamp, a few pens in a holder, and a notebook
     In the desk drawer: Office supplies like stapler, paper clips, and sticky notes
   - Shelf:On the shelf: Several books, a small potted plant, a framed photograph, and a decorative figurine
   - Sidetable:On the sidetable: A reading lamp, a glass of water, and a smartphone charging
     In the sidetable drawer: A sleep mask, earplugs, and a small notebook with a pen

   - Drawer 1 (part of the desk): Inside: As mentioned above, office supplies

   - Drawer 2 (in the sidetable): Inside: As mentioned above, sleep accessories and a notebook

   - Garbagecan: Inside: A few crumpled papers and an empty snack wrapper

   - Additional details: The desklamp on the desk is currently turned on, casting a warm glow over the workspace.
     The alarmclock, which is your target object, is not immediately visible but is understood to be somewhere under or near the desklamp on the desk.
     There's a closed laptop placed on one corner of the desk, partially obscured by the desklamp.
     A desk chair is tucked under the desk, with a light jacket draped over its back.

   This expanded layout provides more context for the items you might encounter or interact with while completing your task. Remember, in text-based games, not all of these items may be interactive or relevant to your current mission, but they help create a more vivid and realistic environment.

5. Task-specific details:

   - The desklamp is on the desk, providing a pool of light.
   - The alarmclock is not immediately visible, suggesting it's underneath or obscured by the desklamp.

6. Interaction: You can move around the room and interact with objects using simple commands like "look at", "move", "open", "close", etc.

7. Goal: Your objective is to locate and examine the alarmclock, which is positioned under the desklamp on the desk.

This context should provide a richer background for the game mission, making it easier to imagine the environment and the task at hand. Would you like me to elaborate on any specific aspect of this context?
