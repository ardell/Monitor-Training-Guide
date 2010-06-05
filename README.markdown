<h1>Monitor Training Guide</h1>

This is a training guide for learning to run a sound check on a monitor console (sound board).  It's
meant to be procedural, and generally applicable to most monitor setups, although there are a few
console-specific tasks (such as loading/saving configurations).

<h2 id='purpose'>Purpose &amp; Goals</h2>

One big reason that venues get to work with talented musicians 
is that they provide environments that talented musicians 
appreciate--such as a talented and trained monitor engineer.

Our goals as monitor guy:

1. Eliminate delays in sound check
1. Minimize frustration in sound check
1. Run an organized and predictable sound check

<h2 id='setup'>Setup</h2>

1. Load a template for the board
1. Find out what instruments (and channels) will be used that night
	- Who will be on vocals?
	- Who will be running click & loop? (typically drummer or keys)
	- How many lines of keys will you have? (stereo vs mono)
	- Will guitars be stereo (pod) or dual mono (57/609 mics)?
1. Label the board with instrument names (inputs) musicians' names (outputs)
1. For each input/output pair set reasonable defaults for:
	- Gain: their own instrument at 0db, others' at -10db
	- Pan: as it would sound to them without monitors
1. Check input lines to make sure that they are patched correctly
	- Mics in particular
1. Check monitor talk-back mic (your mic) to make sure everybody can hear it
1. Set initial levels for channel faders (gains)
    - Gain all vocal mics at -10db (so they can hear each other during sound check, you'll bring them up to 0db later)
    - Raise channel faders (gain) for drums to 0db
    - Gain all other inputs at -infinity (all the way down; we will bring them up as we're ready for each instrument)
1. Save initial configuration for today (DO NOT OVERWRITE THE TEMPLATE)
1. Introduce yourself to the band
1. Check pack batteries and distribute in-ear packs and ears
1. Ask the band if they need anything
	- Patch cables, adapters, etc.
	- Is there any special setup for today, e.g. auto-tune pedals hooked up to the board?

<h2 id="soundcheck">Sound Check/Rehearsal</h2>

<h3>Notes</h3>

- Important to establish a predictable sequence: Drummer, Bassist, EG, Keys, Lead, BG Vox (see chart below)
- Only break your order if something is waaayy too loud for someone (indicates probable error in set-up phase)
- Certain musicians will be more picky than others--some want pan/EQ/gate set a particular way. Try to accommodate but if it slows the sound check significantly, request to move on.

<h3>Running sound check</h3>

<ol>
  <li>Drums to Drummer.  Then drums to everyone else--Bassist, EG, Keys, Lead, BG Vox
    <ul>
      <li>Have drummer play a groove--they will know to do this</li>
	    <li>Tweak the drummer's drum mix according to his requests, get his drum mix right in his own ears first</li>
      <li>This typically requires a bit of tweaking</li>
      <li>Others will request changes, ask them to please wait</li>
      <li>Next, ask the bassist if he wants tweaks for the drum mix, and tweak as appropriate, saying "Drums to [bassist's name]"</li>
      <li>Proceed in order, asking EG, Keys, Lead, BG Vox for tweaks on drums</li>
      <li>Ask "any more changes on drums?" and tweak as appropriate</li>
    </ul>
  </li>
  <li>Click to Drummer.  Then click to everyone else (Bassist, EG, Keys, Lead, BG Vox)</li>
  <li>Bass to Bassist.  Then bass to everyone else (Drummer, EG, Keys, Lead, BG Vox)
    <ul>
      <li>Have the drummer keep playing his groove, and have the bassist play along</li>
      <li>Slowly raise the bass master fader (gain) until bassist is happy with the bass level</li>
      <li>Once again, if others request changes, ask them to please wait unless it is waaayy too loud</li>
      <li>"Bass to [Drummer's name]", and tweak as appropriate</li>
      <li>Proceed, in order asking EG, Keys, Lead, BG Vox for tweaks on bass</li>
      <li>They may request changes to drums at this time, if so go ahead and tweak, but maintain your order as much as possible.</li>
    </ul>
  </li>
  <li>EG to EG.  Then EG to everyone else (Drummer, Bassist, Keys, Lead, BG Vox)</li>
  <li>Keys to Keyboardist.  Then keys to everyone else (Drummer, Bassist, EG, Lead, BG Vox)</li>
  <li>Lead Guitar to Lead Guitar.  Then Lead Guitar to everyone else (Drummer, Bassist, EG, Keys, BG Vox)</li>
  <li>Lead Vox to Lead Vox.  Then Lead Vox to everyone else (Drummer, Bassist, EG, Keys, BG Vox)</li>
  <li>BG Vox to BG Vox.  Then BG Vox to everyone else (Drummer, Bassist, EG, Keys, Lead)</li>
  <li>Other Vox to Other Vocalist (e.g. if the bassist or EG has a mic).  Then Other Vox to everyone else.</li>
  <li>Drum Loops to Drummer (sometimes keyboardist runs these instead).  Then Drum Loops to everyone else (Bassist, EG, Keys, Lead, BG Vox)</li>
  <li>Save (overwrite) the previously saved session (NOT THE TEMPLATE!)</li>
</ol>

<h4>During rehearsal</h4>

1. Keep eye contact with musicians during their rehearsal
    - They will request changes, especially at the beginning of their rehearsal and in between songs
1. Put the board in preview mode after rehearsal is finished, until just before show begins
1. Just before the show begins, change batteries on all wireless mics (Lead Vox, BG/Other Vox, Host). After changing batteries, all mics should be ON.

<h2 id="show">The Show</h2>

Sit back and relax.  As long as you have done a good job with setup and sound check, you should have very little to do during the show.

<h2 id="troubleshooting">Troubleshooting</h2>

<h3>General sound check issues</h3>

- If someone is late setting up (they have not arrived by the time you're ready to do sound check)
  - Run your sound check without them, then at the end bring their instrument in and get their tweaks separately
- If a particular input line is giving you a lot of trouble (not patched right, hearing strange noises over it)
  - Ask the Front of House engineer, or wait until after you have sound checked other instruments then try to fix

<h3>Troubleshooting Drums</h3>

- If the drums (particularly toms) are coming through quietly or they sound "far away", even though you have raised gain/channel faders
  - The gate is probably staying closed (effectively muting the drums)
  - First step *very important* is to lower the channel fader to -infinity (so we don't blow someone's ears out when we disable the gate)
  - Next, "bypass" the gate. This removes the gate plugin from the drum input's signal flow
  - Finally, slowly raise the channel fader until the drummer is happy

<h3>Troubleshooting Guitars</h3>

- Many guitarists prefer only the SM 57 mic, not the 609 (Sennheiser).
  - Simply split out the stereo channels and mute the 609