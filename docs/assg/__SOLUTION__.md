---
title: 
author:
partner:
date:
---

In the report, complete the following.
- Explain the objective of the problem.
- Give your solution.
- Include all your project codes in the [codes/assg](../../codes/assg) folder,
  if required.
- Explain your code snippets, if required.
- Include screenshots of the simulations in this folder, and insert them into
  the markdown file, if required.
- Explain why the simulations are correct, if required.

You can embed math equations into Github Markdown file using a [web service](https://www.codecogs.com/latex/eqneditor.php)

## (5 pts)
What is a digital signal and how does it differ from an analog signal? Give two
everyday examples of digital phenomena (e.g., a window can be open or closed) and
two everyday examples of analog phenomena. 

> A digital signal at any time takes on one of a finite number of possible values, whereas an analog signal can take on one of infinite possible values. Examples of digital phenomena include a traffic light that is either be red, yellow, or green; a television that is on channel 1, 2, 3, ..., or 99; a book that is open to page 1, 2, ..., or 200; or a clothes hangar that either has something hanging from it or doesn’t. Examples of analog phenomena include the temperature of a room, the speed of a car, the distance separating two objects, or the volume of a television set (of course, each analog phenomena could be digitized into a finite number of possible values, with some accompanying loss of information). 

## (5 pts)
Assume that a signal is encoded using 12 bits. Assume that many of the encodings
turn out to be either 000000000000, 000000000001, or 111111111111. We
thus decide to create compressed encodings by representing 000000000000 as
00, 000000000001 as 01, and 111111111111 as 10. 11 means that an
uncompressed encoding follows. Using this encoding scheme, decompress the following encoded stream:

00 00 01 10 11 010101010101 00 00 10 10

> 000000000000 000000000000 000000000001 111111111111 010101010101 000000000000 000000000000 111111111111 111111111111

## (5 pts) Wakerly, Problem 2.2 (a)-(c)
Convert the following octal numbers into binary and hexadecimal:
- > a. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${4321}_{8}={100011010001}_{2}={8D1}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${4321}_{8}={100011010001}_{2}={8D1}_{16}" title="${4321}_{8}={100011010001}_{2}={8D1}_{16}" /></a>
- > b. <a href="https://www.codecogs.com/eqnedit.php?latex={1772631}_{8}={1111111010110011001}_{2}&space;=&space;{7F599}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{1772631}_{8}={1111111010110011001}_{2}&space;=&space;{7F599}_{16}" title="{1772631}_{8}={1111111010110011001}_{2} = {7F599}_{16}" /></a>
- > c. <a href="https://www.codecogs.com/eqnedit.php?latex={533434}_{8}=&space;{101011011100011100}_{2}&space;=&space;{2B71C}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{533434}_{8}=&space;{101011011100011100}_{2}&space;=&space;{2B71C}_{16}" title="{533434}_{8}= {101011011100011100}_{2} = {2B71C}_{16}" /></a>

## (5 pts) Wakerly, Problem 2.5 (a)-(f)
Convert the following numbers into decimal:
- > a. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{1011101}_{2}={93}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{1011101}_{2}={93}_{10}" title="{1011101}_{2}={93}_{10}" /></a>
- > b. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{173016}_{8}={62990}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{173016}_{8}={62990}_{10}" title="{173016}_{8}={62990}_{10}" /></a>
- > c. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{10110001}_{2}={177}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{10110001}_{2}={177}_{10}" title="{10110001}_{2}={177}_{10}" /></a>
- > d. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{66.27}_{8}={54.359375}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{66.27}_{8}={54.359375}_{10}" title="{66.27}_{8}={54.359375}_{10}" /></a>
- > e. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{10101.1001}_{2}={21.5625}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{10101.1001}_{2}={21.5625}_{10}" title="{10101.1001}_{2}={21.5625}_{10}" /></a>
- > f. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{FCB6}_{16}={64694}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{FCB6}_{16}={64694}_{10}" title="{FCB6}_{16}={64694}_{10}" /></a>

## (5 pts) Wakerly, Problem 2.7 (a)-(b)
Add the following pairs of binary numbers, showing all carries:
- > a.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{matrix}&space;&&space;0110011&space;\\&space;&plus;&space;&&space;0011001&space;\\&space;&&space;----&space;\\&space;&&space;1001100&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{matrix}&space;&&space;0110011&space;\\&space;&plus;&space;&&space;0011001&space;\\&space;&&space;----&space;\\&space;&&space;1001100&space;\end{matrix}" title="\begin{matrix} & 0110011 \\ + & 0011001 \\ & ---- \\ & 1001100 \end{matrix}" /></a>
- > b.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{matrix}&space;&&space;0101110&space;\\&space;&plus;&space;&&space;0100101&space;\\&space;&&space;----&space;\\&space;&&space;1010011&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{matrix}&space;&&space;0101110&space;\\&space;&plus;&space;&&space;0100101&space;\\&space;&&space;----&space;\\&space;&&space;1010011&space;\end{matrix}" title="\begin{matrix} & 0101110 \\ + & 0100101 \\ & ---- \\ & 1010011 \end{matrix}" /></a>

## (5 pts) Wakerly, Problem 2.9 (a)-(b)
Add the following pairs of octal numbers:
- > a.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{matrix}&space;&&space;1362&space;\\&space;&plus;&space;&&space;4231&space;\\&space;&&space;---&space;\\&space;&&space;5613&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{matrix}&space;&&space;1362&space;\\&space;&plus;&space;&&space;4231&space;\\&space;&&space;---&space;\\&space;&&space;5613&space;\end{matrix}" title="\begin{matrix} & 1362 \\ + & 4231 \\ & --- \\ & 5613 \end{matrix}" /></a>
- > b.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{matrix}&space;&&space;47135&space;\\&space;&plus;&space;&&space;05145&space;\\&space;&&space;----&space;\\&space;&&space;54302&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{matrix}&space;&&space;47135&space;\\&space;&plus;&space;&&space;05145&space;\\&space;&&space;----&space;\\&space;&&space;54302&space;\end{matrix}" title="\begin{matrix} & 47135 \\ + & 05145 \\ & ---- \\ & 54302 \end{matrix}" /></a>

## (5 pts)
Convert the following decimal numbers to binary numbers using the divide-by-2
method:
- > a. <a href="https://www.codecogs.com/eqnedit.php?latex={19}_{10}&space;=&space;1*2^4&plus;0*2^3&plus;0*2^2&plus;1*2^1&plus;1*2^0={10011}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{19}_{10}&space;=&space;1*2^4&plus;0*2^3&plus;0*2^2&plus;1*2^1&plus;1*2^0={10011}_{2}" title="{19}_{10} = 1*2^4+0*2^3+0*2^2+1*2^1+1*2^0={10011}_{2}" /></a>
- > b. <a href="https://www.codecogs.com/eqnedit.php?latex={30}_{10}&space;=&space;1*2^4&plus;1*2^3&plus;1*2^2&plus;1*2^1&plus;*2^0={11110}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{30}_{10}&space;=&space;1*2^4&plus;1*2^3&plus;1*2^2&plus;1*2^1&plus;*2^0={11110}_{2}" title="{30}_{10} = 1*2^4+1*2^3+1*2^2+1*2^1+*2^0={11110}_{2}" /></a>

## (5 pts)
Convert the decimal number 128 to the following number systems:
- > a. binary: 10000000
- > b. hexadecimal: 80
- > c. base three: 11202
- > d. base five: 1003
- > e. base fifteen: 88
