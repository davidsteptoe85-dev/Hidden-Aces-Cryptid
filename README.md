Oops! The game crashed:
[SMODS _ "src/utils.lua"]:2634: bad argument #2 to 'max' (number expected, got nil)

Additional Context:
Balatro Version: 1.0.1n-HIDDEN ACES
Modded Version: 1.0.0~BETA-1016c-STEAMODDED
LÖVE Version: 11.5.0
Lovely Version: 0.8.0
Platform: Windows
Steamodded Mods:
    1: Brainstorm by OceanRamen [ID: Brainstorm, Version: 2.0.0-beta, Uses Lovely]
    2: FireBot Mod List  by LazyTurtle33 [ID: FireBotModList, Version: 1.0.0]
    3: Galdur by Eremel_ [ID: galdur, Priority: -10000, Version: 1.2.1d, Uses Lovely]
    4: Talisman by MathIsFun_, Mathguy24, jenwalter666, cg-223, lord.ruby [ID: Talisman, Version: 2.6, Uses Lovely]
    5: Faster Planets by boomer678 [ID: 6799321315]
    6: Challenger Deep by Opal [ID: ChDp, Priority: 10, Version: 1.4.2, Uses Lovely]
    7: Uncap Hermit by Infarctus [ID: Uncap_Hermit]
    8: Cryptid by MathIsFun_, Cryptid and Balatro Discords [ID: Cryptid, Priority: 114, Version: 0.5.13, Uses Lovely]
    9: Saturn by OceanRamen [ID: Saturn, Version: 0.2.2-E-ALPHA, Uses Lovely]
    10: Orange Joker by zBray [ID: orangejoker, Version: 1.0.0]
    11: Fusion Jokers by itayfeder, Lyman [ID: FusionJokers, Priority: -10000, Version: 1.1.2~BETA-20250826]
    12: DebugPlus by WilsontheWolf [ID: DebugPlus, Version: 1.5.1, Uses Lovely]
    13: Flower Pot by ItsFlowwey [ID: FlowerPot, Version: 0.8.1, Uses Lovely]
    14: JokerDisplay by nh6574 [ID: JokerDisplay, Priority: -1000000000, Version: 1.8.8.4]
Lovely Mods:
    1: imm

Stack Traceback
===============
(3) field C function 'max'
(4) Lua field 'update_hand_limit_text' at Steamodded file 'src/utils.lua:2634' 
Local variables:
 play = boolean: true
 discard = boolean: true
 (*temporary) = table: 0x2f72fbc8  {discard:, play:}
 (*temporary) = string: "Up to "
(5) Lua upvalue 'game_start_run' at file 'game.lua:2124'
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 args = table: 0x2fb8fe28  {seed_temp:, stake:1, deck:table: 0x2ffb5170}
 saveTable = nil
 selected_back = table: 0x30072658  {alerted:true, loc_vars:function: 0x300727d8, object_type:Back, cry_order:15, _saved_d_u:true, apply:function: 0x30072818, mod:table: 0x2fc0a270 (more...)}
(6) Lua upvalue 'g_start_run' at Steamodded file 'src/utils.lua:2793' 
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 args = table: 0x2fb8fe28  {seed_temp:, stake:1, deck:table: 0x2ffb5170}
(7) Lua upvalue 'start_run_ref' at file 'wrapped_main:3073'
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 args = table: 0x2fb8fe28  {seed_temp:, stake:1, deck:table: 0x2ffb5170}
(8) Lua upvalue 'sr' at file 'challengerdeep.lua:333' (from mod with id ChDp)
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 args = table: 0x2fb8fe28  {seed_temp:, stake:1, deck:table: 0x2ffb5170}
(9) Lua upvalue 'gsr' at file 'lib/overrides.lua:223' (from mod with id Cryptid)
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 args = table: 0x2fb8fe28  {seed_temp:, stake:1, deck:table: 0x2ffb5170}
(10) Lua method 'start_run' at file 'items/challenge.lua:485' (from mod with id Cryptid)
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 args = table: 0x2fb8fe28  {seed_temp:, stake:1, deck:table: 0x2ffb5170}
(11) Lua field 'func' at file 'functions/button_callbacks.lua:3345'
(12) Lua method 'handle' at file 'engine/event.lua:99'
Local variables:
 self = table: 0x300ec420  {start_timer:true, timer:REAL, func:function: 0x2fbcbe00, blockable:true, trigger:immediate, created_on_pause:true, delay:0, complete:false, time:21.84277257017 (more...)}
 _results = table: 0x3094c6a0  {blocking:true, pause_skip:false, time_done:false, completed:false}
(13) Lua method 'update' at file 'engine/event.lua:182'
Local variables:
 self = table: 0x2fb50278  {queue_last_processed:10.866666666667, queues:table: 0x2fb502a0, queue_dt:0.016666666666667, queue_timer:10.871706137844}
 dt = number: 0.00586742
 forced = nil
 (for generator) = C function: next
 (for state) = table: 0x2fb502a0  {unlock:table: 0x2fb50390, galdur:table: 0x2f770190, other:table: 0x2fb50430, tutorial:table: 0x2fb503e0, base:table: 0x2fb503b8, achievement:table: 0x2fb50408 (more...)}
 (for control) = number: nan
 k = string: "base"
 v = table: 0x2fb503b8  {1:table: 0x300ec420, 2:table: 0x2f665940, 3:table: 0x300e74e8, 4:table: 0x3015b150, 5:table: 0x305066d0, 6:table: 0x30a863b0, 7:table: 0x2fc0dc18 (more...)}
 blocked = boolean: false
 i = number: 1
 results = table: 0x3094c6a0  {blocking:true, pause_skip:false, time_done:false, completed:false}
(14) Lua upvalue 'gameUpdateRef' at file 'game.lua:2699'
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 dt = number: 0
 http_resp = nil
(15) Lua upvalue 'update_ref' at Steamodded file 'src/ui.lua:126' 
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 dt = number: 0.00586742
(16) Lua upvalue 'upd' at file 'wrapped_main:1565'
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 dt = number: 0.00586742
(17) Lua upvalue 'gu' at file 'wrapped_main:2757'
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 dt = number: 0.00586742
(18) Lua upvalue 'upd' at file 'lib/gameset.lua:27' (from mod with id Cryptid)
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 dt = number: 0.00586742
(19) Lua upvalue 'gameUpdateRef' at file 'lib/overrides.lua:368' (from mod with id Cryptid)
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 dt = number: 0.00586742
(20) Lua method 'update' at line 32 of chunk '"5060"]'
Local variables:
 self = table: 0x2f3f5da0  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, viewed_stake:1, sort_id:262, F_VIDEO_SETTINGS:true, STAGE:2, F_MOBILE_UI:false (more...)}
 dt = number: 0.00586742
(21) Lua upvalue 'oldupd' at file 'wrapped_main:1030'
Local variables:
 dt = number: 0.00586742
(22) Lua field 'update' at file 'wrapped_main:2790'
Local variables:
 dt = number: 0.00586742
(23) Lua function '?' at file 'wrapped_main:948' (best guess)
(24) global C function 'xpcall'
(25) LÖVE function at file 'boot.lua:377' (best guess)
Local variables:
 func = Lua function '?' (defined at line 919 of chunk wrapped_main)
 inerror = boolean: true
 deferErrhand = Lua function '(LÖVE Function)' (defined at line 348 of chunk [love "boot.lua"])
 earlyinit = Lua function '(LÖVE Function)' (defined at line 355 of chunk [love "boot.lua"])
