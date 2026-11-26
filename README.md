=====================================================
LAST PIXEL
A fast survival game about one glowing square
=====================================================

OVERVIEW
--------
You control a tiny glowing square inside a shrinking, changing arena.
Waves of enemies close in, bosses arrive, and the arena squeezes tighter.
Survive as long as you can, earn score, and spend it on skins that give
you special abilities.

LAST PIXEL is a survival game, not a roguelite: every run starts fresh.
Only your score bank, owned skins and best time are saved.

THE GAME IS ONE FILE
--------------------
last-pixel.html is a single self-contained file (HTML, CSS and
JavaScript). It uses no external libraries, images, fonts or network
requests. Open it in any modern desktop or mobile browser.

HOW TO RUN
----------
1. Open last-pixel.html in your browser (double-click it, or host it).
2. Press Play (or Enter / Space) on the main menu.

CONTROLS
--------
Move ............ WASD or Arrow keys, or drag on a touchscreen
Fire ............ Automatic (nearest enemy)
Skin ability .... Space, or tap the round button (bottom-right)
Pick upgrade .... 1 / 2 / 3, or tap a card
Mute ............ M, or tap the SOUND label (top-right)
Menu pages ...... Enter/Space = play, H = how to play, S = shop,
                  Esc or Backspace = back
Game over ....... Space/Enter = retry, Esc = menu

HOW A RUN WORKS
---------------
- A new wave starts every 12 seconds. Each wave adds enemies and the
  arena shrinks a little.
- Every 3rd wave (not a boss wave) is a SQUEEZE. The border flashes and
  a dashed box shows the new size for 3 seconds, then the arena tightens
  for about 5 seconds and grows back.
- Every 5th wave is a BOSS wave.
- You have 3 hearts (up to 6 with upgrades). After a hit you are
  briefly invincible.

ENEMIES
-------
Chaser   Red spinning square. Follows you constantly.
Dart     Yellow triangle. Aims, blinks, then charges in a straight line.
Heavy    Large purple square. Slow and tough; drops extra shards.
Shooter  Cyan diamond. Keeps its distance and fires at you.

BOSSES (every 5th wave, three kinds)
------------------------------------
Sentinel     Pink square. Rings, aimed fans and spirals of bullets.
Juggernaut   Orange spiked shape. Shows an aim line, then charges
             across the arena and fires a fan of bullets.
Hive         Green orb. Holds the centre, summons chasers and fires
             rotating spirals. While it lives, the arena stays tighter.

All boss attacks flash and play a warning tone first. Bosses enrage
below half health. Defeating a boss gives an upgrade, grows the arena a
little and gives about 6 seconds of calm.

UPGRADES
--------
Green shards unlock three upgrades per run (at 12, 22 and 34 shards).
Bosses award more. A warning banner appears before the choice screen.
You pick one of three cards. Rapid Fire and Extra Shot are guaranteed to
show up often in your first three choices.

Rapid fire        Shoot 20% faster.
Extra shot        +1 bullet per volley (max 4).
Swift legs        Move 8% faster (capped).
Explode Enemies   One use. When you lose health, it blasts all enemies
                  and gives 4 seconds with no spawns. Bosses survive it.
Heavy shot        +1 bullet damage (max 3).
Magnet            Pull pickups from farther away.
Vitality          +1 max health and heal 1 (max 6).
Shield            Absorbs the next hit, then breaks.

SCORE AND SAVING
----------------
Run score = (seconds survived x 10 + enemies defeated x 5
            + bosses defeated x 200), x1.25 with the Prospector skin.

Your score goes into a saved score bank. Spend it in the Shop.
Progress is saved in your browser (localStorage): best time, score bank,
owned skins and the equipped skin. Clearing your browser data resets it.

SKINS (Shop)
------------
Classic     Free      No ability.
Aegis       7,000     Space: 20-second shield, 60s cooldown.
Prospector  10,000    +25% score. Space: call an upgrade pop-up,
                      150s cooldown.
Phantom     15,000    Space: summon a phantom ally (3 lives, 20s),
                      60s cooldown.
Nova        7,000     Space: blast all enemies, 30s cooldown.
Miracle     20,000    Revives you once per run when you die.

Tap a skin card in the Shop to buy it, then tap again to equip it.

TIPS
----
- Keep moving. Standing still in a tightening arena is how runs end.
- Take Rapid fire and Extra shot early; they carry the first waves.
- Watch for the dashed outline: it shows where the walls will close.
- Dodge dart charges by stepping sideways while they blink.
- Gaps in boss bullet rings are safe; move toward them early.

BROWSER NOTES
-------------
- Works on desktop and mobile browsers. Sound starts after your first
  click, tap or key press, as browsers require.
- If saves do not persist, your browser may be blocking local storage
  (for example in private browsing).

KNOWN LIMITS
------------
- Balance numbers (prices, boss health, cooldowns) are first guesses and
  may need tuning after more play.
- Sounds are simple synthesized beeps; there is no music.

CREDITS
-------
Concept and direction: the LAST PIXEL project owner.
Inspired by windowkill.
=====================================================
