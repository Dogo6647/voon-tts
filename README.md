# voon-tts
[![Netlify Status](https://api.netlify.com/api/v1/badges/93f30fc2-b222-4e90-9914-758911323b5c/deploy-status)](https://app.netlify.com/sites/voontalk/deploys)

A text-to-speech app with an API which generates voices out of nowhere.
You can make it say anything you want, but these sentences/words are the ones that work better (there are probably even more):

- This is a test
- json
- The quick brown fox jumped over the lazy dog
- Lorem ipsum dolor sit amet
- Properties
- Text
- Voon
- Talk
- no
- yes
- Words with a lot of T, X, and S sounds
- Naughty words (the F word, S word, and the P word.)

Words with an "e" at the end don't work very well.

## Using VoonTalk
### Text section
Press the "Change button" to change the text in the textbox (When you press Play, VoonTalk is gonna read out loud whatever is inside the textbox). If your text is too long, it won't show up in the GUI, but you can still play it back.

Type "{decdemo}" in the textbox if you want to listen to the DEC Command mode demo. The code is a modification of: https://pastebin.com/eK7u2Ek6

### Properties section: Mode
Press the button next to "Mode:" to change VoonTalk's mode

- Normal: VoonTalk reads out loud the contents of the textbox as normal.
- DEC Command: Allows you to enter DECtalk commands. (Almost) full support is present.

### Properties section: Pitch
Default pitch is 0. Max pitch is around 350. You can also set the pitch to a negative number.

## Messing with Voon
- Set the pitch to 1000 and make it say "aeaeaeaeaeaeaeae" or "a e. a e. a e." You'll hear Voon turn into an alarm.
- Type a letter next to a character it doesn't understand (like a number or a símbolo extranjero *ñ*) in the textbox and repeat the pattern multiple times. (e.g. a1a1a1a1a1a1a1a1) This will cause Voon to bypass its double-letter rule. Pretty effective for giving it a seizure.
- Voon has the same SOI SOI SOI disease as Microsoft Sam. It CAN say SOY correctly though.

Ultimate seizure word:
a1a1a1a1a1a1a1a1e1e1e1e1e11e1e1e1e1e1e 1e1r1r1r1t11y1hb1n1k11oi1211k11k11k1k1k1k1k11j1j1j1j11h1h1h1h1h1h1h1g1g1g1g1g11f1c1d1c11v1c11c1c1c1c11b11b1b1b1b1n1n1n11n1n1n1n1n1n1n1n1n1n1e2e2e2e2e2e2e2e2e3e3e3r3r3r3r3r3r3r3r3r3r3r3ry44y4y4y4y4y4y4y4y4y4y4y4
