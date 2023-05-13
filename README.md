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

| Obfuscator                                                         | Test#1  | Test#2   | Time  |
|--------------------------------------------------------------------|---------|----------|-------|
| [None](https://www.java.com/#LOL)                                  | PPPPPPP | PPPPPPPP | 27ms  |
| [Allatori](https://www.allatori.com/)                              | PPPPPPP | FPFEEPPF | 54ms  |
| [Stringer](https://jfxstore.com/stringer/)                         | PPPPPPP | PPPPEPPP | 92ms  |
| [ZKM](https://zelix.com/klassmaster/index.html)                    | PPPPPPP | FPPEEEUP | 51ms  |
| [ProGuard](https://github.com/Guardsquare/proguard/)               | PPPPPPP | FPPEEEUP | 26ms  |
| [Skidfuscator](https://github.com/skidfuscatordev)                 | PPPPPPP | FPPPPFPP | 734ms |
| [superblaubeere27](https://github.com/superblaubeere27/obfuscator) | PPPPPPP | FPPPEPPP | 47ms  |
| [Radon3](https://github.com/ItzSomebody/radon)                     | EEPPEFE | FPFEEPE  | E     |


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
opening an issue or by sending an email to `dmca_jot@huzpsb.eu.org`.

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