https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/37130522#overview [Course: Flutter & Dart]


1 year development [Learn about flutter for one year]  
 
Flutter Development [Web development, iPhone, Android Development]- 301 days (about 10 months) 
Helps me create templates and think of concepts that I can use in the future. Cross dimensional app so this helps me generate an app on both iOS and android and maybe when I'm 35 I can have an app on android and apple 
 
Jobs I can work 
Full Stack Developer  
Web 3.0/NextJS/ReactJS/React Native/Flutter/etc... 
 
 
 
 
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
main() is executed automatically by Dart, runApp() tells flutter which application to draw onto the screen  
 
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
 
void add(num1, num2){ -> Function Definition 
	num1+ num2; 
} 
 
void demo(){ 
	add(5,3);  -> Using(calling) the function with arguments(input values) 
} 
When you define functions.dart void runApp(Widget app)  
void runApp Widget app(){ 
	 
} 
 
Positional and Named Arguments 
import ‘package: flutter/material.dart’ 
void main() { 
	runApp(MaterialApp()); 
} 
Need to pass more information to materialapp 
What should pass to a widget app and positional argument 
Looking at void add(num1, num2){ 
	num1+ num2 
} 
This function has two parameters <- Comma-separated parameter list(a list of input values) 
Define functions that take named parameters and named functions 
When it comes to using the functions called it doesn’t matter what value you use them in 
In the input  
 
void main() { 
	runApp(MaterialApp(home: )); 
} 
Add home: (Argument) 
Which kind of widget or ui element are we working with home: Text()) 
 
Deep Dive: Position & Named Arguments 
Positional and named arguments/parameters 
In general, function paraments and arguments are a key concept 
 
Positional : The position of an argument determines which parameter receives the values (a+b) 
Named: The name of an argument determines which parameter receives the value(a+b) 
 
Besides the different usage, there’s one very important difference between positional nd named arguments. By default positional parameters are required must not be omitted.  
 
 
Main.dart  
Add import ‘package:flutter/material.dart’ 
Add void main(){ 
	runApp(MaterialApp(home: Text())); 
} 
 
Text  
String:Data { data, { Key? Key, TextStyle? Style, StrutStyle? StrutStyle, TextAlign? TextAlign, TextDirection? TextDirection 
home: Text(‘’)) 
Hello World 
runApp(MaterialApp(home:Text(‘Hello World!’)) 
Make sure that the text(‘Hello World!’) and add to materialapp 
Blue Squiggly line has to do with material 
import ‘package:flutter/material.dart’ 
 
What is const? 
Const helps Dart optimize runtime performance 
Const Text(‘Hello World!’) -> Defined & used for the first time in the app 
Device Memory add text widget(‘A) 
Memory gets reused 
 
 
 
 
Build More Complex Widget Trees  
import ‘package:flutter/material.dart’ 
void main(){ 
	runApp( 
		const MaterialApp( 
			home: Scaffold( 
				body: Center( 
					child: Text(‘Hello World’) 
	),), ), 
); 
} 
 
Scaffold class is a widget implementing the basic material design visual layout structure 
This class provides APIs for showing drawers and bottom sheets. 
 
To center the text can use another screen, the center widget 
To center the widget can use refactor and then wrap with center 
 
Understanding Value Types 
Dart is a type-safe language- (All values are of certain Types) 
‘Hello World!’ -> String 
29-> Int 
Material App-> Material App 
 
Object-> More than one type is possible & common 
Num [Object] 
Widget [Object] 
 
Built-In, third-party & custom types 
 
main.dart 
import ‘package:flutter/material.dart’ 
runApp( 
	const MaterialApp( 
		home: Scaffold( 
			body:Center( 
				child: Text(MaterialApp), 
				) 
			)		) 
	) 
) 
 
Text(MaterialApp)-> child  
29-> child 
Int- Integer numbers 
Double- Fractional numbers 
Num- Integer or fractional numbers 
String- Text 
Bool- Boolean values 
Object- Any kind of object 
 
Configuring Widgets & Understanding Objects 
Object import ‘package: flutter/material’ 
import ‘package: flutter/material.dart’ 
void main(){ 
	runApp( 
	const MaterialApp( 
		home: Scaffold( 
			body: Center( 
				child: Text(‘Hello World’) 
			) 
		) 
	) 
) 
) 
} 
 
Import the background color: null, 
backgroundColor: Color(), 
 
Widgets are objects 
Widgets = objects = data structures in memory 
 
Working with “Configuration Objects” 
A color gradient is a transition between two or more colors. For example dark purple to purple, green to red etc 
Add another new widget on Scaffold 
In this format, going to add decoration add gradient and add colors 
Decoration: BoxDecoration(Various decorations to the container) 
Gradient: LinearGradient() 
Colors: TBD 
 
Generics Listing and Adding Gradients  
List<Color> [List of values] (Not single value and multiple values) 
colors: Generic Type are “flexible types” that “work together” with other types 
Cooking Sports Reading, 5.91 3.87 1.21 
Colors: [Color.fromARGB(255,26,2,80), Color.fromARGB(255,26,2,80) 
Color.fromARGB(255,45,7,98) 
 
 
 
How to configure widgets & objects 
Add a widget that goes left to right 
Begin: Alignment.top 
end: Alignment.bottom 
 
This changes the gradient and aligns it the right way 
 
Styling Text 
Change the style text widget. 
-> Change the text color to “white” 
-> Change the text font size to 28 
 
Add style:  
child: const Center( 

child: Text( 

'Hello World!', 

 
style: TextStyle( 
 
 
Building Custom Widgets 
class GradientContainer  
Create a class that shows what is important and what isn’t important 
 
class GradientContainer  extends StatelessWidget { (inherit from statelesswidget) { 
     @override (Overrides a widget and then adds custom functionalities) 
      Widget  build () {} -> Methods and just a function [Build must return a widget to use] 
      build needs to have a ctx or context and need to use flutter to execute a parameter 
      return used by flutter  
		        } 
} 
 
 
Working with constructor functions 
Constructors for public widgets should have a named ‘key’ parameter.  
Adding a constructor function is quiet straight forward and add gradientContainer() 
GradientContainer(a,b) 
Named cant have a gradient container ({key}) 
class GradientContainer extends Stateless Widget { 
	GradientContainer({key}); 
} 
(GradientContainer({key})}- > adds to gradientContainer extends Stateless Widget 
GradientContainer({key});; 
Variable initilization work  
super(); -> Super refers to the parent class(StatelessWidget in this case) 
The super class extends to the stateless widget.key 
Using optimization key of class 
 
Splitting Code Across Files 
Gradient_container.dart  
import ‘package:flutter/material.dart’  
Have to make sure that the file can be imported in main.dart and gradient_container.dart 
 
Custom Widget 
Create a separate widget for this text spot 
Formatting the widgets are important, example putting them in gradient_container.dart 
Create a new file in library 
In these packages add basics/styled_text.dart and call the function.  
When separating widgets in flutter must have styled_text 
 
Variables 
variables are data containers 

Working a lot of values and main.dart and gradient_container.dart 
More complex the file gets the more little tweaks can help 
Variables are Data Containers 
var greetingText = “Hello World” 
variable declartion and assignment operator value(Text/String) 
var startAlignment = Alignment.topLeft; 
var endAlignment = Alignment.bottomRight 
variables clean up the code 
Data variables that add start alignment and can store data and then can use these variables multiple time whenever I want 
Const improves the quality of the code and makes faster so use it for color 
 
Variables & Types 
var startAlignment; 
var endAlignment = Alignment.bottomRight; 
 
startAlignment= Alignment.topLeft; 
endAlignment = Alignment.bottomRight;; 
 
 
Instances 
For custom texts add string text  
Add Widget build(context) 
Building custom text with styledtext(string text, {super.key}) 
String outputText; and add override 
this keyword provided by dart, parts of this.text( 
These components are styled in a way where you store a key then declare what the variable is 
StyledText(this.text, {super.key}) 
String text; [Can add final String text]  
const TextStyle( 
	color: Colors.white, 
	fontSize:28 
) 
 
When adding the const styledText(this.text,{super.key}) 
String Text; [Can add final String text] 
const TextStyle( 
	color: Colors.white, 
	fontSize:28 
) 
 
Practice Reusable widgets 
 
import 'package:first_app/styled_text.dart'; 

import 'package:flutter/material.dart'; 

const startAlignment = Alignment.topLeft; 

const endAlignment = Alignment.bottomRight; 

class GradientContainer extends StatelessWidget { 

const GradientContainer(this.color1, this.color2, {super.key}); 

final Color color1; 

final Color color2; 

@override 

Widget build(context) { 

return Container( 

decoration: BoxDecoration( 

gradient: LinearGradient( 

colors: [color1, color2], 

begin: startAlignment, 

end: endAlignment), 

), 

child: const Center(child: StyledText('UNGUARDED')), 

); 

} 

} 

 
import 'package:first_app/gradient_container.dart'; 

import 'package:flutter/material.dart'; 

void main() { 

runApp( 

const MaterialApp( 

home: Scaffold( 

body: GradientContainer(Color.fromARGB(255, 232, 184, 28), 

Color.fromARGB(255, 232, 184, 28)), 

), 

), 

); 

} 
 
Image & Multiple Constructor Functions 
Child: Image.asset(‘assets/image’) 
Add assets to the images and then add child image.asset(‘assets/image’) 
pubspec.yaml add the images 
child: Image.asset( 

'assets/images/dice-2.png', 

width: 200, 

 
Adding Buttons & Using Functions As Values 
What do I want to do if I want to provide bunch of widgets 
Column()  
Column and row can be used to place multiple child widgets next to each other 
Column, Row 
Want images vertically so column becomes the right choice 
child: Center( 
	child: Column(children: [Image.asset(‘assets/images/dice-2.png’, width:200, 
	) 
] 
 
This helps the Image.asset(assets/images/dice-2.png 
Add TextButton(onPressed: onPressed, child: const Text(‘Roll Dice),) 
onPressed: rollDice(), 
void rollDice(){ 
 
} 
 
Styling Templates 
Column widget takes vertical space 
mainAxisSize: MainAxisSize.min [Vertical access min and max values] (max as much space as possible) 
style:  TextButton.styleFrom(various arguments with foreground Color: Colors:white, textStyle: TextStyle( 
fontSize:28, 
))  
Two ways to add padding: const EdgeInsets.only(top:20))  
const SizedBox(heightL20), 

Gradient Container Dart 
Add a function for roll dice 
var activeDiceImage = ; 
Set the image path to activeDiceImage 
void rollDice(){ 
	activeDiceImage= ‘assets/images/dice-4.png; 
	print(); 
} 
Image.asset( 
activeDiceImage, 
width: 200, 
), 
 
In materialApp remove const  
const Color.fromARGB 
const Color.fromARGB 
 
Add print(‘’Changing image...’); 
 
Stateful Widgets 
Create.a statefulwidget  
Stateful widget-> Allows to manage state inside of them 
Dice_roller.dart add new file  
import ‘package:flutter/material.dart’ 
class _DiceRollerState extends State<DiceRoller> { 
	build(){} 
 
} 
@override 
Widget build(context){ 
 
} 
} 
Widget build(context){ 
 
} 
} 
const DiceRoller({super.key});  
Image.asset( 
activeDiceImage, 
width:200, 
), 
 
DiceRoller({super.key}) [Stateful Widget] 
Take variable of activeDiceImage, rollDice = ‘assets/images/dice-2.png’ 
rollDice() activeDiceImage = ‘assets/images/dice-4.png’ 
Have to add const GradeintContainer 
Have to add const GradientContainer 
 
child: Center( 
	child: DiceRoller() 
import ‘package:basics/dice_roler.dart’ 
class _DiceRollerState extends State<DiceRoller> 
var activeDiceImage= ‘assets/images/dice-2.png’ 
rollDice() [setState((){}); 
Updating activeDiceImage 
Basically have to set state to create active dice image 
 
Generating Random Numbers 
import ‘dart: math’ 
void rollDice(){ 
Random() .nextInt(6) +1; //0<>5 
var Random().nextInt(6) 
var diceRoll = Random().nextInt(6)+1 
Have to add a dollar sign dice-$diceRoll.png 
 
Image: asset [ 
‘assets/images/dice-$currentDiceRoll.png’ 
 
 
 
 
 
Overview 
Main Dart file with an empty project, first file when your main.Dart starts [First file this is the base] 
Dart reads the file and then compiles it to the native iOS and machine 
Then the code is played on the simulator 
Main.dart  
Dart allows to create functions and then add to the next section 
Can use functions with void main() {  
runApp( 
	const MaterialApp( 
		home: Scaffold( 
			body: GradientContainer( 
				Color.fromARGB 
				Color.fromARGB 
			) 
		  ) 
		) 
) 
) 
 
RunApp provided by flutter and provided by runApp 
Main function gets executed automatically 
runApp should be called inside of main() 
Pass the to-be-displayed to widget tree to runApp() 
 
Flutter is all about widgets 
Flutter UIs are created by combining & nesting Widgets 
OutlinedButton-Text, Start Quiz [Flutter provides many built-in Widgets] 
You can also build your own Widgets 
Dart is an object-oriented language 
Primitive Values / More Complex Values 
	Text-> ‘Hello World’ 
	Numbers-> ‘Numbers’ 
 
More Complex Values 
	Widgets, Gradient Config Object 
 
Everything is an object, but created on blueprint: Classes more complex version of an object 
Object is a data structure stored in computer memory 
Object store Data [Variables/properties] 
Functions [Methods] 
Create data and functions to group together in one data structure 
Dart is a type-safe language, All values are of a certain type 
‘Hello World!’ -> String 
29 -> Int 
MaterialApp -> MaterialApp 
Can be an object, number, widget, object and object etc 
Stateless vs Stateful Widgets 
Stateless don’t manage any internal data, Only update parent widgets were updated which is a state widget 
Stateful Widgets-> Do manage internal data(“state”) 
Stateful Widget to Stateless Widgets 
StatefulWidget and another state class work together to create the function 
 
Things to watch out for 
When to use stateful widget  
Stateful widget has a smaller key 
Stateless has only one class 
 
When to use gradient container and gradient container  


 
 
 
 

 
