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

Normal: VoonTalk reads out loud the contents of the textbox as normal.
DEC Command: Allows you to enter DECtalk commands. (Almost) full support is present.

### Properties section: Pitch
Default pitch is 0. Max pitch is around 350. You can also set the pitch to a negative number.
