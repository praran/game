# Synopsis

Implementation of the Game ROCK, PAPER and Scissors, the game is a console game can be played Human vs Human, Human vs Computer and Computer vs Computer
  
# Installation

The project is built using Scala and SBT as the build tool with Spec2 as the unit testing framework
 * Scala version : 2.11.6
 * SBT version   : 1.3.8
 * Spec2 version : 3.6.4
 
Compile project using SBT
  > sbt compile

Test Compile
  > sbt compile test
  
Running application using SBT
  > sbt "run-main com.game.rps.Runner"
  
# Tests
  
  Spec2 core and Specs 2 mock is used as the BDD style unit testing framework
  
  executing tests
  > sbt test
  
# Intentions

* To keep the application stateless 
* Used SOLID principles
* Strategy design pattern
* Extensively used Scala objects with intention of creating singleton objects
* using implicits and default values for polymorphic behaviour along the lines of open-closed principles
* Tests cover the business logic and most of the model objects

