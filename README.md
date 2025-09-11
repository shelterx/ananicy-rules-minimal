# A minimal set of ananicy-cpp rules for use with scx schedulers.

Using ananicy-cpp with [scx schedulers](https://github.com/sched-ext/scx) generally isn't recommended.
But there's no reason why some processes should have a higher priority than needed. These rules set some background processes and normal processes to have lower background load and priority (a higher nice value) without causing too much interference on the system when using scx schedulers.

## Ananicy-cpp-minimal rules

Ananicy-cpp-minimal includes most common game launchers, some common system services, and some tools that you wouldn't want to use much CPU time.
Have a look at the minimal.rules file to see all of them.

The rules used are mostly from [Ananicy-cpp-rules for CachyOS](https://github.com/CachyOS/ananicy-rules).

## Installation
Be sure to remove any existing ananicy-cpp rules before using these.

## How to contribute

Submit a PR if you want something added; perhaps it's missing a game launcher or some tool. But keep in mind, the word minimal is there for a reason.
