# digital heat  
https://patchstorage.com/digital-heat/  
a Zoia patch  
Mono Digital Sound Processor inspired by Elekton's Analog Heat

basically it's a dirtbox with bells and whistles and lots of knobs for tweaking

I had to keep the patch mono. the OD / Distortion and Fuzz modules are pretty cpu heavy (~20%). when I tried adding a stereo path the cpu maxed out quickly and stuff stopped responding =[

## features
* lots of ways to tweak an overdrive / distortion / fuzz sound
* dry / wet control
* multi-mode filter with resonance
* 3-band eq
* modulation sources: envelope follower, adsr envelop, lfo (free-running or midi clock synced)
* bypassable compressor
* (almost) all controls are mapped to midi CC (see starred list in patch)

## pages
0. front page ctrl  
here you'll find the main controls of the patch
    * row 1  
        - mono / stereo in select (stereo signals get summed to mono)
        - input sensitivity
        - out volume
    * row 2
        - boost (into the overdrive / fuzz modules)
        - drive amount
        - wet level
        - dry wet mix
        - dirt (boost into the filter)
        - od / fuzz select
    * row 3
        - filter frequency and resonance
        - lpf / bpf / hpf select
        - low / mid / high eq
    * the bottom two rows are the modulation  sources, patch the cv-outs to various destinations
        - envelope follower + inverted
        - envelope + inverted
        - lfo + inverted
1. modulation ctrl  
here you'll find the modulation controls (and compression controls) of the patch
    * row 1
        - band-pass filter frequency  and q (carve out which frequencies the envelope follower sees)
        - gain (into the enveloper follower)
        - envelope follower rise and fall times
        - comparator trigger level (level at which the envelope follower triggers the adsr envelope)
    * row 2
        - envelope attack, decay, sustain, and release
        - lfo speed
        - lfo free / midi tempo synced select
    * row 3
        - compressor threshold, ratio, attack, release
        - compressor bypass / enable select
    * the bottom two rows are the modulation  sources (mirrored from page 0), patch the cv-outs to various destinations
2. signal flow
3. od fuzz  
here are the overdrive and fuzz modules
    * try experimenting by changing these to different od / distortion / fuzz models
4. filter
5. modulation
6. lfo  
here you'll find the lfo, both free-running and midi tempo synced
    * try changing the wave shapes of the lfo modules
7. compression

## some tips
* for a more subtler overdrive sound, try turning up boost into a 0-drive amount overdrive (I borrowed this idea from christopher-h-m-jacques's patch Gain Finale)
* try tweaking the modulation bpf frequency and q, envelope follower rise ad fall, and comparator trigger level settings to follow your bass kick drum. then patch the envelope inverted modulation source to things, e.g. drive amount, dry wet, output volume, etc. for some sidechain-ish effects. tweak the adsr settings to taste.

## thanks
* christopher-h-m-jacques and his patch Gain Finale https://patchstorage.com/gain-finale-a-stereo-gain-patch/
* Hakon Soreide's zoia youtube videos, especially the one on radio buttons https://www.youtube.com/watch?v=u5G-qdO6vL8&t=1094s, I used that a lot in this patch
* the ZOIA Anti-GAS Archive https://patchstorage.com/question/welcome-to-the-zoia-anti-gas-archive/, which inspired me to complete and share this patch on PatchStorage

## revision history
* 0.1 - [Initial release](https://github.com/rasprague/zoia-patches/commit/a8647f8c901cb7028134c61b4592c47d0c084916)
