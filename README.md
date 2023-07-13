# Simple_Flutter_App
new repo
#main dart
import 'package:flutter/material.dart';
import 'package:test/home.dart';

void main() {
  runApp( MyApp());
}

class MyApp extends StatelessWidget {
  
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter App',
      theme: ThemeData(
        primarySwatch: Colors.red,
      ),

       debugShowCheckedModeBanner: false,
      home: home(),

      
    );
    
  }
}
