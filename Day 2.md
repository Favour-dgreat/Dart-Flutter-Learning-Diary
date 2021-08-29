##After a long time of not writing codes, due to system issues and a very busy day, today I went back to learning, with the help of Angela Yu's Complete Flutter Bootcamp Course on Udemy, (https://www.udemy.com/course/flutter-bootcamp-with-dart/). 
Today I built a Simple I Am Rich App ()
Learnt about Google's Material Design, appBar, Widgets, Properties of a Widget, centerig a widget, Rendering images in an app with a URL with the help of the NetworkImage(Img URL) Property. 

##Find the code for my simple I am Rich App Here: 

mport 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.blueGrey[900],
        appBar:
            AppBar(title: Text("I Am Rich"), backgroundColor: Colors.red[800]),
        body: Center(
          child: Image(
            image: NetworkImage('https://omes-7a5b4.web.app/images/f.jpg'),
          ),
        ),
      ),
    ),
  );
}
