# CA-NI-PSI

CA-NI-PSI is another implementation of the FEPPCT encryption scheme, with adaptation to higher versions of JDK/JRE. 

As higher versions of JDK/JRE do not support or suggest computing the size of a Java object directly, ``-javaagent:lib/classmexer.jar`` should be added to the VM commandline. 

Please refer to [https://www.javamex.com/tutorials/memory/instrumentation.shtml](https://www.javamex.com/tutorials/memory/instrumentation.shtml) and [https://www.javamex.com/classmexer/](https://www.javamex.com/classmexer/) for details. 

If you are using old Java APIs, please visit [https://github.com/BatchClayderman/FEPPCT](https://github.com/BatchClayderman/FEPPCT). 
