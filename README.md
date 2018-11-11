# menu_generator
This javascript generates a dynamic menu from content of the hosting html file. Only one vanilla script with no dependency.
It was designed to work both online and locally.
Tested on Chrome and IE.

REQUIREMENTS:
Html body must have: 
- one ```<div class='header'>```;
- one ```<div class='content'>```;
- one ```<div class='footer'>```;

 Only ```<div class='content'>``` is parsed while building menu. 
 Every ```<h1>, <h2>```... tag becomes an item.
 
 USAGE:
 This script must be embedded in the end of html body.
 Also menu_generator.css must be linked.
