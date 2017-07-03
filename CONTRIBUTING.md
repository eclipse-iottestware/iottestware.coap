# How to get involved

## Building the project

### Prerequisites

* Latest version of Java, if you want to run or modify your code within the Titan IDE
* Latest version of **Eclipse Titan**. For installation details please consult the official [Titan documentation package](https://projects.eclipse.org/projects/tools.titan/downloads)




```bash
cd bin
```

A shell script is available inside the bin folder. It will create symbolic links to the source files of the project and link them into the bin folder .
```bash
chmod +x createlink.sh (optional)
./createlink.sh
```

As all needed files are now inside your bin folder we can run the makefile script of Eclipse Titan to generate the Makefile. We call the executable "CoAPTest" but feel free to change the name or may add more options.

```bash
ttcn3_makefilegen -f -g -e CoAPTest *.ttcn *.hh *.cc
```

After generating the Makefile we need to compile all *.ttcn files to be able to build the executable.

```bash
make compile
```

Afterwards build the project.
```bash
make
```

#### WINDOWS

TODO

## Running the tests


Before we can execute the test cases please run the SUT. Either you use the project provided SUT or your own CoAP implementation is up to you.

```bash
java -jar ../sut/CoAP-server.jar
```

Finally, run the executable named CoAPTest in your bin folder (or whatever name you have chosen).

```bash
ttcn3_start CoAPTest CoAP.cfg
```