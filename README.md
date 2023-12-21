# triangle
`cmake` scaffolding for C++, introducing RtAudio.

This is the follow-up to [sine](http://github.com/vmwherez/sine). 

## a simple something that does nothing (VS Code)
In addition to `cmake` configuration this repo includes setup work for VS Code.
This step is important so as not to get lost in the configs moving forward.

My goal for [sine](http://github.com/vmwherez/sine) and this repo (triangle) was to be able to work from both `vim` and `VS Code`.

### VS Code files
Take a look at these:

- launch.json
- tasks.json

### debugging 
A spot here about `lldb.`
TODO: set up `vim` for `lldb`.

## openFrameworks

It is notable that **openFrameworks does not use CMake, and there is no official documentation for using CMake with oF.** 

#### env variable

`$OF_ROOT` needs to be set to your openFrameworks install directory.

#### RtAudio
RtAudio is good next step, first alone, without openFrameworks.

https://web.mit.edu/carrien/Public/speechlab/marc_code/ADAPT_VC/rtaudio/doc/html/

#### trigonometryExample
Since this includes a great graphical demo of the math, we will also be using it demo linking to openFrameworks, maybe integrating our RtAudio work.


##### sanity check: run oF demos without CMake
```
make
make RunRelease
```

## maths
*Triangle might actually be a good name for this repo.*

- unit circle, **345 triangle**, theta...
- harmonic content: how do we get from sine to triangle?
- `x(t) vs x[n]` (discrete-time series)
- ... 
TODO: math examples in C++ 

## further reading, thoughts, questions...  
TODO: I have a ton of additional resources for further reading. 

- use these repos as incremental steps to refer back to if something in your configuration is complicated or not working. TODO: for that reason these (sine, triangle) should be kept simple...
- What's the difference between C and C++?
- after working in this repo, how do we feel about linking libraries?
- WolfSound had some interesting critiques of Will P's book. He talked about some concepts in C++. Thoughts? 