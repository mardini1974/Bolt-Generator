### New Fusion release and Python version is changed replace the content of the following folder:
#### C:/Users/#USERNAME/AppData/Roaming/Autodesk/ApplicationPlugins/BoltGenerator.bundle/Contents/
### With Content of submit 18-9-2019.zip file 


# Bolt-Generator
Bolt Generator for Fusion 360 add in issues and library editing procedures
## Usage and editing
Here you can find the basic library file for Bolt genertor addin, you can use them if you for any reason delete them or they are unreadable by the addin.

The library is made out of xml files each type has two version metric and inch(imperial) the inch version is marked with I at the end of file name.

As known file naming is crucial espcially when it's multi platform program (what's acceptable in windows maybe not in mac) so always pay attension to naming ant typing.

Open the pdf file "Dimensions legend" to see what is each variable meaning.

You can sort the xml files as your wishs (the most ued bolt or most used size), just move the order of items in xml file to fit your need

To edit xml files i recommend two options depending on your operating system

##### Mac:
although xcode is the default option but i prefer to use geany as it's free, light weight and faster.
```
http://download.geany.org/geany-1.33_osx.dmg.
```
##### Windows:  
you can also use geany: 
```https://www.geany.org/Download/Releases```  

and my windows prefferable is notpad++ also free:
```
https://notepad-plus-plus.org/download 
```
#### Syntexing
library files can accept certain types of numbers
- for millimeters just type the dimension as it is. example 
```
<s>2.5</s>
```
- for Inch dimensions add at the end of dimension "in" make sure that there is no spaces after "in".
```
<T>0.8 in</T> .... right texting
<T>1/4 in</T> .... right texting
<l>1 1/2 in</l> .... also good
<b>0.3 in </b> .... wrong texting
<l>0.5 in,3/8 in, 1 in, 1 1/4 in</l> .... good
<l>0.25 in , 3/8 in</l> ....wrong notice the extra spacing after "0.25 in" while before the number is not a problem.
```
