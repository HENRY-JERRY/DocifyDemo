# Installing JDK and Running Genesis

## Installing JDK

**Genesis** does not special installation and the file can simply be executed using Java.
It does, however, require the Java SE Runtime Environment 1.8 or higher to be installed
on the user’s system. The latest version of the Java SE Runtime Environment
1.8 can be found at [**Oracle JavaSE downloads**](https://www.oracle.com/za/java/technologies/javase-downloads.html)

To check if you already have Java installed, you can open your Operating System’s
command line interface and enter

```bash
java -version
```

If Java is installed, one line of the response should read
Java(TM) SE Runtime Environment (build 1.x.0_*) as shown in the terminal output below

```bash
java version "1.8.0_271"
Java(TM) SE Runtime Environment (build 1.8.0_271-b09)
Java HotSpot(TM) 64-Bit Server VM (build 25.271-b09, mixed mode)
```
or for versions greater than 9

```bash
java version "11.0.8" 2020-07-14 LTS
Java(TM) SE Runtime Environment 18.9 (build 11.0.8+10-LTS)
Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.8+10-LTS, mixed mode)
```
The type of installation depends on your requirement and the platform that you choose to install. To **run**  download and install JDK by using this [**JDK Installation Guide**](https://docs.oracle.com/en/java/javase/11/install/overview-jdk-installation.html#GUID-8677A77F-231A-40F7-98B9-1FD0B48C346A).

## Running Genesis

Windows and Linux If the Java SE Runtime Environment 1.7 is installed, the user should be able to open Genesis by double-clicking the file. If this does not work, the user will have to launch the jar manually through a command line editor (cmd in windows or terminal in linux) using the following command.

```bash
java -jar Genesis.jar
```
