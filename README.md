# Controller-in-MS
I was asked by the illustrious Miss Corruption to make a guide on controller use for Masterstroke, and who am I to turn her down?

Method 1 does not violate Rule 11. Methods 2 and 3 do.

**DISCLAIMER: THESE ARE INHERENTLY JANKY. I AM NOT RESPONSIBLE FOR ANY DAMAGE DONE TO YOUR INSTALL OR ANY BUGS THEREIN. ALWAYS READ MODPAGES AND UNDERSTAND THEM BEFORE DOWNLOADING.**

All of these following methods might encounter a bug during any NSFW scene where the camera will drift. The recommended way to deal with this is to turn off the freeflycam, NUM3 by default I believe. Alternatively, you can fight the camera, but this can get strenuous.

First, I would like to say that if it is your plan to add MCO-DXP to MS on top of using a controller, you should use a combination of the guide in #LS-Modding, now optionally included in LS, for controller, and Mern’s guide on the MCO website. This use case will be further discussed in Method 3. 

**METHOD 1:** For me even when using a controller Skyrim will accept keyboard and mouse inputs. I don’t know if this is a skyrim thing, a steam thing, or something with my pc, and I can’t really check, as such your mileage with this method may vary. If you are looking to simply use a controller without altering the combat experience this can really be done without adding any mod if you are willing to have some jank and hybrid between controller for gameplay, and keyboard/mouse for quick button clicks like checking milk or lactaid levels, or using your mouse buttons to engage in SLSO, etc… You will need to alter TK Dodge RE ini to use the desired button, likely 274, which in human speak translates to left bumper, as most other buttons interfere with gameplay.

**METHOD 2:** If you aren’t wanting to hybrid in that manner you will need to install some extra mods. These being [The Ultimate Control Scheme](https://www.nexusmods.com/skyrimspecialedition/mods/29381) or TUCS, and optionally [Serio’s Cycle Hotkeys](https://www.nexusmods.com/skyrimspecialedition/mods/27184) for even more hotkeys. I ask that you do not contact me for help setting these up. The mod pages are well-written and should have everything you need. I can not, and will not provide a ControlMap file as this is not my use case and a perfectly working one ships with TUCS. You will need to alter TK Dodge RE ini to use the desired button, likely 274 or 275, meaning left or right bumper respectively, and of course, you will need to manually set up every desired hotkey. In this scenario, I would recommend turning SLSO to auto, or off entirely.

**METHOD 3:** MS currently (11/22/23) runs on 1.6.640, commonly referred to as AE, some mods included in the usual MCO suite do not work or have AE patches, those being Combat Pathing Revolution, and the recommended separate power attack button mod; OCPAM. We are SOL on CPR, but we can replace OCPAM with the working, albeit inferior, [Elden Power Attack](https://www.nexusmods.com/skyrimspecialedition/mods/66711) and the accompanying patch [Elden Power Attack for MCO DXP](https://www.nexusmods.com/skyrimspecialedition/mods/84378) and its prerequisites. (I have never been able to get OCPANG working. If you have, please contact me telling me how and I will update this guide.) Elden Power Attack is inferior because it requires you to hold the modifier button, then use the attack button to power attack rather than just hitting the one button to power attack. You will need to manually set the key in the **GAMEPAD SECTION** of Elden Power Attack’s ini to 281, making sure to remove the semicolon in this line. You could in theory skip Elden Power Attack, but this would mean you'd be unable to start a chain with a power attack, however, if you've the know-how you could alter hbkmog's control map which would free up a button for other things. Personal preference on what you find valuable really.

When installing [dTry Plugin Updates](https://www.nexusmods.com/skyrimspecialedition/mods/85740), you should ONLY select dTry’s Key Utils.

If you are using precision, before running nemesis (if on creature profile you must follow the guide by Miss Corruption in the pins, it is recommended to look through that guide even if not though.) you must move precision above tk dodge on the left-hand side of mo2. 

After installing everything, remembering that precision is placed above TK Dodge, your load order on the left pane of mo2 should look something like the image below. On the right pane of mo2 you should drag these added mods to about 300 on the priority list. [Classic Sprinting Redone](https://www.nexusmods.com/skyrimspecialedition/mods/20166) is an optional, but recommended mod, the same goes for [IFrame Generator](https://www.nexusmods.com/skyrimspecialedition/mods/82737?tab=description). Ignore the blue crossed-off mods, they are unrelated to this setup. If you are using CSR set Enablesprintkeydodge to true in TK Dodge RE ini. Also, set the DodgeHotkey to 277. If you get an error upon trying to launch saying something along the lines of “failed to open address library” it means you forgot an AE patch. 
![Modordermethod3](https://github.com/Turtman69/Controller-in-MS/assets/151793140/65d9b566-0b1c-4c47-932c-ea2366605815)


I don’t think I missed anything. If I did I’m sure someone will squawk at me eventually.




