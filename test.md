# mechanics
* gray name in chat
* going inside a player stops knockback from hitscan
* you have no spawn so game restarts etc just leave you in your place
* you spawn at 0 0 0
* you can walk into any spawn (but you can't open spawn doors)
* you show up as spectator in scoreboard
* you can't walk through your own "unassigned teammates" but you can't damage them either
* a bunch of effects are red/blue mixed (ie red viewmodels blue medigun beam, blue beam red uber) (which 
* blue targetID
* bottom left model is blue
* you can walk through any red or blue player but not a gray player
* your own projectiles won't go through a gray teammate
* can't hurt gray teammates
* dominations still work
* bots/training bots can't be gray team, only "real" players
* no teammate wall hacks

# weapons
* hits both teams
* __ hitscan
* __ airblast
* __ blast damage
* _____ short circuit
* holiday punch doesn't do anything to a gray teammate
* sandvich works
* disiciplinary action works on gray teammates, vs red and blue it hurts + speed boosts them
* mantreads: doesn't work on gray teammate, doesn't work on any red or blue players
* pyro thrusters: doesn't work on red or blue, pushes gray teammate
* sandman ball works and also slows
* shortstop shove doesn't work on red blue or gray
* phlog works fine
* natascha slow works
* eureka effect teles you to 0 0 0
* milk & jarate works on both teams, excludes gray, and you can extinguish teammates on fire
* airblasted projectiles are fine, can't airblast gray projectile
* pyro glove doesn't give speed boost
* eviction notice works fine
* soldier banners work fine for gray teammates
* shield bash doesn't work
* gas passer works fine for both teams & doesn't affect gray teammates
* third degree works fine for both teams
* eternal reward - back stabbing a gray player = no disguise
* ^ gray backstabbing red or blue works fine
* you can ignite a gray huntsman arrow as pyro
* flares: can hit red at any distance, but can't hit blue at close range
* flares: gray teammates eat it (where it should normally pass through)
* gray teammates block projectiles at any range
* rockets: can hit red at any distance, but can't hit blue at close range
* pipes and stickies hit fine vs red and blue
* your own stickies collide with themselves (normally, your stickies don't collide with itself, and also don't collide with stickies of the enemy team)
* quickiebomb can destroy blue and red stickies but not gray
* gray scout bonk -> no miss particle effects (but the slow works)
* caber works fine vs both teams, nothing happens vs a gray

* crit rockets on gray become purple, because monoculous?? `tf_projectile_rocket.cpp line 65`
* monoculous is not friendly if you are gray

# taunt kills
* they seem to work fine
* except scorch shot, + the flare strangeness with people being close or far 

# buildings
* red sentry will attack gray
* blue sentry won't
* gray team can attack & walk through both color buildings
* gray team can't hurt gray buildings

* sentries built by gray players target gray & blue and not red
* sentries built by gray players target gray but won't hurt them
* sentries built by gray players will hurt red if they get in the way
* sentries built by gray players do not target and do not hurt gray buildings

* normally, a friendly getting in the way of a sentry will just eat the damage

* wrangler auto aim locks for red and blue but not gray
* sentry rockets: can hit red at any distance, but can't hit blue at close range

* gray players can sap red and blue but not gray buildings
* red/blue players can't sap gray buildings
* blue players disguised as red will still get shot, but red players disguising as blue won't

* dispensers built by gray players will heal gray players

* gray players can't take red or blue teleporters, but can take gray teleporters
* you can't tele frag red or blue, if you try to telefrag a gray player it breaks
* if you turn on `sm_cvar tf_avoidteammates 0` and try to telefrag a red or blue player, you get stuck in them instead

* a red or blue player shooting cow mangler charged shot will disabled a gray building
* gray charged shot does not work on gray sentries

# medic
* can't heal anyone (you can heal gray teammates)
* crossbow hurts both teams
* you can heal a gray teammate (medigun & crossbow & amputator taunt)

# spy disguise
* works fine

mp_friendlyfire 1 works on gray team

# skeletons
* ignore gray players but gray players can still hurt them

# bot
* attacks gray players

# gamemode objectives
* ctf: instant cap on both teams
* gray players can't pick up the gray intel
* gray players can't block captures or cap points
* doomsday: gray can cap the flag but then nothing happens
* doomsday: if gray team drops the flag, it stays neutral and a red or blue player can pick it up
* PD: gray counts for blue but can't cap
* PD: gray team leader can heal other grays
* can't push cart in pl or plr
* mannpower dropped powerups stay team specific for a bit, gray team drops a gray team only pickup
