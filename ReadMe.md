<center>
 ** Gaironxero's Pokemon Add On Scripts ** </center>
<center>

 **  <a href="http://redd.it/367spe">Press here for the Reddit post</a> **
</center>



**************************************************************************
* This Add On was made for the /r/PokemonTrades subreddit community.     
* The Add On is meant to make creating complex and helpful trading       
* spreadsheets simple and easy. It includes powerful functions,          
* autofilling buttons, as well as convenient buttons loaded with         
* common images and formulas. Check out my own trade spreadsheet example 
* to see how the functions can simplify your spreadsheet, or simply      
* use my template and create your own spreadsheet from scratch.          
**************************************************************************


I would like to say thank you to TobiObito for the use of his Hidden Power 
Type calculator, and to the entire community for being so friendly.        
******************************************************************************



## To Install:

1. Open up the trade spreadsheet you want to use this AddOn for. You must install this for every spreadsheet if you have more than one.

2. Select Tools > Script Editor.

3. Start a Blank Project.

4. Copy the script into the project, overwriting all existing text.

5. Save the project and refresh the original spreadsheet page.



## Usage:

### Pokemon Sprites

This function autofills the selected cells to return Pokemon sprites referencing 2 arguments. 
First, the national dex number. Second, whether or not the sprite should be shiny. 
If no argument is given for the second, it is assumed to be not shiny. 
The second argument can be as simple as 1/0, y/n, or a cell with the shiny star sprite vs an empty cell. 
This also supports alternate forms, using the naming scheme of serebii’s images. 
Simply add -m to a national dex number to get a mega evolution, or 479-w, 479-h, etc. for wash or heat rotom. 


###  Pokeball Sprites
	
This menu has a list of Pokeball sprites, and any function will autofill all selected cells with the sprite for the Pokeball. (Listed alphabetically to find them faster.)

###  Pokemon Name

This function autofills selected cells to take a national dex number and return the name of the Pokemon it references.



###  Pokemon Dex Number

This function autofills selected cells to take the name of a Pokemon (not case sensitive) and find the national dex number for it. Note: You must spell the name correctly. (Pokemon like Farfetch’d have to be exact.)

###  IV Autofill

This menu of functions autofill IV sets for a certain amount of rows. The columns will start from the leftmost and fill in 6, no matter what was selected. This makes it easy to select a bunch of rows by just the HP column and auto fill them all, and prevents mistakes from selecting too many or too few columns.

###  EV Autofill
	
	

### Hidden Power Type

This function was originally written by TobiObito and used with his permission.
It has been modified slightly to work better with this AddOn. All credit for the functionality of this calculator goes to him.
The function itself fills selected cells with a formula that calculates the Hidden Power Type using the 6 IVs as arguments. 
Since the function only needs to know if the value is even or odd, any number 0-31 or E/O will suffice to complete the argument.

### Hyperlink

This function autofills the selected cell with the basic Hyperlink syntax
	
### Icons

This menu lets you chose from some of the basic ingame icons. IV markings, generation marking, gender icon and more
	
### Check for updates

The possibilitie to check for an updated version of the script
	
### Settings

Creates an Settings sheet in your spreadsheet where you can set that type of pokeball or pokemon icons you want.
