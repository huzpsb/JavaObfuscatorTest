# JavaObfuscatorTest

A list of Java obfuscators, obfuscated samples and benchmarks.

## File structure

````
.
├───bench
│   ├───src
│   │   └───... (source files)
│   └───bin
│       └───TEST.jar (compiled benchmark)
└───samples
    └───... (obfuscated samples)
````

## Obfuscators

( Pass, Fail, Error, Unknown[No output,etc.] )

~~You may find something more in the source view~~
| Obfuscator                                                                        | Test#1  | Test#2   | Performance | Size    |
|-----------------------------------------------------------------------------------|---------|----------|-------------|---------|
| [None](https://www.java.com/#LOL)                                                 | PPPPPPP | PPPPPPPP | 27ms        | 29KB    | Some of my personal views :P (You find it!)
| [Grunt](https://github.com/SpartanB312/Grunt)                                     | PPPPPPP | FPFPEPPE | 160ms       | 843KB   | Bigger is better.
| [dProtect](https://github.com/open-obfuscator/dProtect)                           | PPPPPPP | FPFEEEUP | 31ms        | 21KB    | Good fork of ↓, fair obf for a ProGuard fork
| [ProGuard](https://github.com/Guardsquare/proguard/)                              | PPPPPPP | FPPEEEUP | 26ms        | 15KB    | Rather an optimizer than an obfuscator.
| [Radon3](https://github.com/ItzSomebody/radon)                                    | EEPPEFE | FPFEEPEF | E           | 269KB   | Crappy indeed.
| [Bozar](https://github.com/vimasig/Bozar)                                         | PPPPPPP | FPFEEPPF | 201ms       | 513KB   | Nothing special.
| [Caesium](https://github.com/sim0n/Caesium/)                                      | PPPPPFP | FFPPPPPP | 50ms        | 174KB   | Interesting with zip bomb. But patchable with Recaf.
| [Scuti](https://github.com/netindev/scuti)                                        | EEPPPPP | FPFEEPEF | 867ms       | 151KB   | Interesting with throw exploit. Painful 2 configure.
| [BranchLock](https://branchlock.net/)                                             | PPPPPPP | FPFEEPFF | 65ms        | 66KB    | What if it's FOSS...
| [Neon](https://github.com/MoofMonkey/NeonObf)                                     | PPPPPPP | PPFPPPEP | 7439ms      | 53KB    | Maybe tooooo slow. Not recommended.
| [Ambien](https://github.com/iiiiiiiris/Ambien)                                    | EEPPPEP | FPPEEPUF | 28ms        | 56KB    | Zip crasher crashes Recaf. Impressive.
| [qProtect-Lite](https://mdma.dev/)                                                | PPPPPPP | FPPPEPPP | 69ms        | 139KB   | It's like ZKM but worse
| [zelix KlassMaster20.0.3](https://zelix.com/)                                     | PPPPPPP | FPPPEPPP | 54ms        | 83KB    | Heavy
| [BranchLock Pro](https://branchlock.net/)                                         | PPPPPPP | FPPPEPFF | E           | 256KB   | Maybe it is Perfect protection i think as a obfuscator
| [Eskid](https://baidu.com/deadth)                                                 | PPPPEPP | FPPPEPEP | 530ms       | 166KB   | Maybe it is cool.For fun.
| [ClassGuard](https://zenofx.com/classguard)                                       | PPPPPPP | PPPPEPPP | 36ms        | 2820KB  | Interesting AES Encryption class.
| [JNIC-3.5.1](https://jnic.dev/)                                                   | PPPPPPP | FPPPEPPP | 481ms       | 89KB    | JNIC 3.5.1 with build-in flowObf and StringObf enabled.
| [OpenJNIC](https://www.blackspigot.com/threads/openjnic.173922/)                  | PPPPPPP | FPPPEPPP | 28ms        | 304KB   | Too good to be actually used.
| [native-obfuscator(win cmake)](https://github.com/radioegor146/native-obfuscator) | PPPPPPP | PPPPPPPP | 1597ms      | 120KB   | Very compatible, but has a relatively broken running speed.
| [j2cc](https://java2cc.github.io/)                                                | PPPPPPP | PPPPPPPP | 172ms       | 304KB   | Easily cracked with proper bps. Even weaker
| [Allatori](https://www.allatori.com/)                                             | PPPPPPP | FPFEEPPF | 54ms        | 27KB    | Best for lazy people. Nearly no configuration required.
| [Stringer](https://jfxstore.com/stringer/)                                        | PPPPPPP | PPPPEPPP | 92ms        | 306KB   | Neat compability. Good for Spring & Android.
| [ZKM](https://zelix.com/klassmaster/index.html)                                   | PPPPPPP | FPPEEEUP | 51ms        | 79KB    | = ProGuardPlusObf
| [Skidfuscator](https://github.com/skidfuscatordev)                                | PPPPPPP | FPPPPFPP | 734ms       | 118KB   | Good for skidders. Hard to reverse. Too slow.
| [SkidfuscatorEnterprise](https://skidfuscator.dev)                                | PPPPPPP | FPPPPEPP | 4274ms      | 158KB   | Tooooo slow.
| [SkidfuscatorEnterpriseLeak](https://github.com/Sk1dfuscator/skidfuscator-src)    | PPPPPPP | FPFPEEEF | 10055ms     | 138KB   | More and more slow
| [superblaubeere27](https://github.com/superblaubeere27/obfuscator)                | PPPPPPP | FPPPEPPP | 47ms        | 223KB   | Tradition never dies.
| [SafeNet](https://cpl.thalesgroup.com/software-monetization)                      | PPEPPPP | FPPEFEPE | 239ms       | 21865KB | Require add jvm args `-noverify` to run.

Obfuscators that meets one of the following conditions goes here:

- We don't have a copy of, and haven't yet answered (or refused) our request to provide us with an example.
- Requested a DMCA takedown.
- Unmaintained or don't have an email in their intro page, and we are unable to run.

```
DashO, nProtect
```

## Tests

~~RTFSC~~

````
Test 1.1: Inheritance
Test 1.2: Cross
Test 1.3: Throw
Test 1.4: Accuracy
Test 1.5: SubClass
Test 1.6: Pool
Test 1.7: InnerClass

Test 2.1: Counter
Test 2.2: Chinese
Test 2.3: Resource
Test 2.4: Field
Test 2.5: Loader
Test 2.6: ReTrace
Test 2.7: Annotation
Test 2.8: Sec
````

## Contributing

Please feel free to contribute to this repository by opening a pull request.  
Do not forget to add the obfuscator to the list above.

## DMCA

If you are the owner of one of the obfuscators and you want me to remove it from this repository, please contact me by
opening an issue.

## Disclaimer

This repository is for educational purposes only. The author of this repository is not responsible for any damage caused
by the code in this repository. The code in this repository is not intended to be used for malicious purposes.  
The benchmarks in this repository are not intended to be used for comparing the performance of the obfuscators. The
benchmarks are only intended to show the obfuscators' capabilities.  
The efficiency is evaluated through the time it takes the obfuscated program to perform a certain set of computations.
This may vary depending on the machine used to run the benchmarks, and the results may not be accurate.  
Only compatibility and efficiency are tested here. But you should choose wisely among strength, compatibility,
efficiency, size, and price.  
The samples in this repository may be malicious. Do not run them on your machine.
