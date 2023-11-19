Salman Hasan 
11/17/2023 
 
1 year development [Learn about flutter for one year]  
 
Flutter Development [Web development, iPhone, Android Development]- 301 days (about 10 months) 
Helps me create templates and think of concepts that I can use in the future. Cross dimensional app so this helps me generate an app on both iOS and android and maybe when I'm 35 I can have an app on android and apple 
 
Jobs I can work 
Full Stack Developer  
Web 3.0/NextJS/ReactJS/React Native/Flutter/etc... 
 
UNGUARDED 
Business [Marketing/Supply chain/Finance etc.] 
Content Creator [Start to finish] 
Basketball Trainer/Lifting Trainer 
 
 
 
 
 
Getting Flutter Installed  
1.Click MacOS  
2.Must have git installed, and must have XCode installed as well 
3.Use sudo softwareupdate –install-rosetta –agree-to-license 
4.Once everything is downloaded  
5.Run echo $SHELL (bin/zsh)  
6.Add export PS1 = “ \$ “ 
7.Export Path = “$PATH:/Users/max/tools/flutter/bin” 
8.Once added then which flutter works 
9.Run flutter doctor 
10.Download Xcode 
11. Run xcode commands 
12. sudo xcode-select -s /Applications/Xcode.app/Contents/Developer 
 
Flutter and Dart 
1.Delete all the content that’s inside of it 
2.runApp(); -> Function [Are functions that can simply be executed in your code] (Idea is to show some function in the screen) 
3.A function body must be present to make it work 
4.Must create a music construction and type void main() { [Custom function a custom instruction] 
 
} 
5. Defining a function and then execute a calling a function 
6. Void main() { 
 
} [Defining a function] 
 
runApp(); -Executing calling a function 
7.Flutter is an open source project so you can inspect its code 
8.main(); 
9. Function Definition 
 Functions “Code on demand”  
void doSomething(){ [function definition] 
 
} 
10.  Function Usage 
Void main(){ 
	doSomething() 
	doSomething() 
	 
} 
11. Function Name [Identifier] 
12. Functions can be used (“called”) in your code as often as needed 
 
What's the most important folder, in which you'll work most of the time, in a Flutter project? 
The “Lib” Folder, this folder contains the .dart code file to get the code going 
 
Which file is the entry point for a Flutter application? 
Lib/main.dart 
 
What is the main purpose of the Dart compiler? 
Convert Dart code into machine code that can run on various platforms 
 
What are functions in programming? 
A sequence of instructions that perform a specific task 
 
How do you import a package in a Dart file? 
Import “package_name”  
 
Which key "elements" are involved in the startup process of drawing a UI onto the device screen? 
The main function and the run app function 
main() is executed automatically by Dart, runApp() tells flutter which application to draw oto the screen  
 
Functions & Parameters 
Functions may take input values – so –called “Parameters” or “Arguments” 
 
No Parameters-> void main() 
1 Parameter-> void print(text) 
2 Parameter-> void A 
 
Understanding Widgets 
import ‘Package: flutter/material.dart’ 
void main() { 
        runApp() 
} 
 
 
How 
 
How flutter apps become active 
1.Main() function gets executed autmatically 
	By Dart, when executing the compiled app on the target device 
 
2.runApp() should be called inside of main() 
	runApp() “tells” flutter what to display on the screen (I.e which UI elements to display) 
 
3.Pass the to-be-displayed “widget tree” to runApp() 
	A “widget tree” is a combination of (nested). Flutter widgets that build the overall user interface 
 
Flutter UI’s are built with the Widgets 
When using Flutter, you build your user interface with code main() 
runApp() should be called inside of main() runApp() tells flutter what to display on the screen which ui elements to display 
Widget tree is a combination of (nested) flutter widgets that build the overall user interface 
 
Flutter UIs are built with widgets 
When using flutter, you build your user interface with code.  
A combination of widgets 
Pass the to-be-displayed “widget tree” to runApp() 
 
By dart, when executing the compiled app on the target device 
runApp() tells flutter what to display on the screen(I.e, which UI elements to display) 
A widget tree is a combination of (nested) Flutter widgets that build the overall user interface 
 
Flutter UIs are Built with widgets 
When using flutter, you build your user interface with code 
A combination of widgets 
 
Widgets are nested into each other ->  
	Center( 
		child: Text(‘Hello World’), 
	); 
Built-in Center widget centers its content horizontal + vertically. Built-in text widget displays some text on the screen 
 
MaterialApp 
Scaffold 
Row 
Text-Text-Text 
 
 
Its all about Widgets [Flutter UIs are created by combining & nesting Widgets] (OutlinedButton) [Text,start quiz]  
 
OutinedButton 
Text- Flutter provides many built in widgets 
Start Quiz- You can also build your own widgets 
 
 
Widget Catalog 
25 functions that are widgets that can be used for flutter. Use core widgets of flutter  
First widget that we need to pass runApp(MaterialApp)  
use MaterialApp()  
Classes are a dart and complex data structures like widgets 
Void main() { 
	runApp(MaterialApp()); 
} 
Creates a widget (a UI element – defined in code) 

