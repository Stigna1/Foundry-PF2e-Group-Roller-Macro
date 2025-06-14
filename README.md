# Foundry-PF2e-Group-Roller-Macro
Git repo for a small macro group roller project.

The intended use case for this macro is to roll 'passive' checks behind the scenes. For example, the party is exploring an ancient manor. A chill hangs in the air, and the whispering of the wind through the decaying walls is a constant background noise. Spooky, sure - but those learned in the ways of Occultism may recognize subtle patterns and long-forgotten phonemes that indicate that there's more to it; these whispers are not the mindless moaning of natural wind, but the still-echoing chants of a long-ago eldritch ritual! (DC 23 Occultism check to discern).
This is something an expert occultist may pick up on as they expore, but can be too narrow to expect the player of an expert occultist to constantly think about and actively check for all the time. Instead, the gm can simply just check on behalf of the party's best occultist on behalf of the party when they enter the room. This module facilitates that sort of thing; rather than asking the players to work out who's best at occultism and then rolling secretly on behalf of that character - both clunky and an obvious metanarrative tell of some occult activities - you could instead use this macro.
It automatically goes through every PC in the scene, finds the one with the highest modifier to whatever skill you'd like, secretly rolls a check with that character's modifier to that skill, and then informs the GM of both the result and the character that was selected to attempt it. This allows the GM to reward a character's investment in a skill by calling them out specifically as being responsible for a success ('A cold wind blows down the manor's creaking halls. Corthys the occultist, you discern the faintest trace of ancient words in the wind's moaning - words you've not heard since your studies in the Circle of Dark Moons!').

Good luck out there!
~Stigna

Notes:
    • The macro assumes that the single most qualified PC serves as the party 'face' for the skill check in question. It only concerns itself with whichever PC is the absolute best at the check, and doesn't support mass-rolling for the others.
    • In the case of ties, all tied PCs make checks and are mentioned. I advise against simply using the best one, as this would increase the odds of party success by virtue of having more rolls at it. Instead, pick one character randomly or via narrative convenience and use that character's result.
    • The macro tallies player characters in the current screen. This means that the character must be present in the screen to be included. It determines which characters are player characters by checking for each player's corresponding actor sheet in player preferences, so also make sure that each player's player prefs include their char sheet. This also means that stuff like skilled Eidolons will get passed over.
    • The macro is made for PF2e, and I don't expect it to be compatable with other systems.
    • This work is based heavily on the Group Perception Roller and Recall Knowledge macros by Symon S as part of PF2e Toolbelt. Big ups there.

    P.s It's worth noting that I'm not much familiar with Javascript, Foundry module production, OR github, so this is unlikely to be regularily updated/maintained. S' just something I cobbled together 'cuz I needed for my own table (for rolling various skill checks to discover points of interest as the party explores a hexcrawl map, specifically) , and I figured I'd put it out into the world in case other people could also benefit from it.
