# Dice Simulation program

## Description

This Java program simulates rolling a fair six-sided die 1000 times using Math.random(). It counts the occurrences of each face (1 to 6) and displays the results in a formatted table, showing frequencies and percentages.

## How It Works

Generates a random number between 0.0 and 1.0 using Math.random().

Assigns a face to the dice roll based on the generated number.

Counts occurrences of each face.

Displays results in a table with face values, frequencies, and percentages.

## Table Output Format

Face | Frequency | Percentage
-----------------------------
1    | 168       | 16.8%
2    | 165       | 16.5%
3    | 170       | 17.0%
4    | 162       | 16.2%
5    | 161       | 16.1%
6    | 174       | 17.4%
-----------------------------
Total | 1000      | 100.0%

## Prerequisites

Java Development Kit (JDK) installed

Basic knowledge of Java programming

## How to Run the Program

- Copy the source code into a file named DiceSimulation.java.

- Open a terminal or command prompt in the directory containing DiceSimulation.java.

- Compile the program:

javac DiceSimulation.java

- Run the program:

java DiceSimulation

## Features

Uses Math.random() to simulate dice rolls without external imports.

Displays results in a clean and readable table format.

Ensures the total count and percentages sum correctly.

