# A minimal set of ananicy-cpp rules for use with scx schedulers.

Using ananicy-cpp with [scx schedulers](https://github.com/sched-ext/scx) generally isn't recommended.
But there's no reason why some processes should have high priority than needed, these rules sets some background processes and normal processes to have less priority without causing too much interference on the system when using scx schedulers.

## Ananicy-cpp-minimal rules

Ananicy-cpp-minimal includes most common game launchers, ome common system services and some tools that you wouldn't want to use much cpu time.
Have a look at the minimal.rules file to see all of them.

The rules used are mostly from [Ananicy-cpp-rules for CachyOS](https://https://github.com/CachyOS/ananicy-rules) 

## How to contribute

Submit a PR if you want something added, perhaps it's missing a game launcher or some tool. But keep in mind, the word minimal is there for a reason.
