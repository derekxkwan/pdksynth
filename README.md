# pdksynth

A GPL v3 synth (abstraction for now) library for Pure Data
(requires some externals from pdkm, listed below)

ABSTRACTIONS:

PERCUSSION:
- dkbd1~ - bass drum synth
- dkbd2~ - 808ish bass drum synth (requires dkclik~)
- dkbd3~ - bass drum synth (requires zexy, dkpink~ from pdkm)
- dkcymb808-1~ - 808 cymbal synth
- dkclap1~ - clap synthesizer (requires dkenv~)
- dkclap2~ - clap synthesizer
- dkgong1~ - gong fm synth
- dkhh1~ - hihat synth
- dkhh2~ - hihat synth (requires dkpink~, dkenv~)
- dkhh3~ - hihat synth (requires dkvanssimp~, dkdecay2~ from pdkvabs)
- dksd1~ - snare drum synth
- dksd2~ - snare drum synth
- dksd3~ - snare drum synth
- dksd4~ - snare drum synth
- dksd5~ - snare drum synth (requires dkvanssimp~, dkdecay2~ from pdkvabs)


PITCHES:
- dkbrass1~ - brass synth
- dkdesaw1~ - detuned saw synth
- dkdesyp1~ - DEtuned SYnth Pad
- dkdtmf~ - dtmf synth
- dkemsine1~ - everything modulated sine
- dkkarplus~ - karplus-strong synth
- dkklmba1~ - kalimba synth (requires dkpink~ from pdkm, dkringerbank~ from pdkvabs)
- dksynsaw1~ - saw synth (requires pdkm)
- dkorgan1~ - organ synth
- dkpiano1~ - piano synth
- dkpwmsq1~ - pw-modded square wave
- dkrhodes1~ - rhodes synth
- dkstring1~ - first attempt at a string synth

OSCILLATORS:
- dkdutysaw~ - variable-duty saw (requires zexy)
- dkdutysq~ - variable-duty square wave (requires zexy)

OTHER:
- dkvowel~ - vowel synthesizer based on three formants
- dkradiostatic~ - abstraction based on jnarveson's SC radiostatic code (static only)
- dkradiotuning~ - abstraction based on jnarveson's SC radiostatic code (tuning only)
