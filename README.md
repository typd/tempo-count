# tempo-counter

When I practise drumbeat, by dribbling (yes, practise ball control and drum rhythm at the same time), I need a tool to analyse the tempo beat rhythm.

### how to

- record the dribbling sound (with common audio formats)
- tool pre-requirements
    - python3
    - `pip3 install -r requirements.txt`
- analyse the tempos
    - `./tempo-counter -f sample/20200301-120bits.m4a`
    - it generates a histogram like this
        - each dot stands for an interval between two beats
        - below sound track is recorded from a 120 bpm (beats per min, every 0.5s) dribble practice
        - it results a beautiful curve, slightly faster than 0.5s. Well done!
        - ![](./sample/20200301-120bits.png) 

