<!-- markdownlint-disable -->
<h1 align="center">Snake Game!</h1>

<pre><p align="center"><img src=".\img/mainGame.png"></p></pre>

## About

<p>Snake Game as a desktop application for Windows (windows forms application) written in C# .NET Framework.</p>

## Features

<p>When the application is ran it wil first display a dialog to set the number of apples. The number of apples go from 1 (default) up to 800.</p>

<pre><p align="center"><img src=".\img/SetApplesDialog.png"></p></pre>

<p>If the number of apples set is greater than 500 the apples will be rendered as "breathing" circles as the actual apple image will cause performance issues.</p>

<pre><p align="center"><img src=".\img/over500.png"></p></pre>

<p>With each apple eaten the snake will grow in size. Every 10 apples the speed, or <strong><em>step</em></strong>, will increase. The steps is tracked on the bottom of screen. Once the bar is full, you're at max speed.</p>

<p>Clicking anywhere on the game screen will pause the game. If you crash against an obstacle or with the "tail" of the snake the game will end the snake will stop moving, displaying the number of apples you've eaten. A different sound will played depending whether you crashed or "ate yourself".</p>

<pre><p align="center"><img src=".\img/gameover.png"></p></pre>

<p>Note: there is no option to restart the game, once the game ends you will have to close it and re-reopen</p>
<br>

## Run

<p>Download the repo and build the project with Visual Studio (2019+). Make sure you have the Windows Desktop Development extension install</p>

