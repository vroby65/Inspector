<b>Inspector</b><br> 
<i>simple html visual editor</i>

this is a simple program in pure javascript / html that is used to create window applications similar to the old visual basic 6.

see demo https://vroby65.github.io/Inspector/

<b>Inspector</b>

The purpose of this program is to simulate an IDE in the style of visualbasic in html / javascript environment. Programs will use forms similar to those of visual basic to contain controls which are nothing more than html elements. The editor allows you to program the events of the objects and to save, test and export the product code.

In drafting the code, 3 new commands are available that simplify programming

<i>getId ('object id')</i>

which is in fact the simplified version of

document.getElementById ('')

<i>include ('path_of_bookshelf')</i>

which allows you to load an external library.

<i>style('path_of_stylesheet')</i>

to load a stylesheet. Style and include work well on a test mode but not work in edit mode.

The ide is composed of
- topbar
- toolbar
- screen
- inspector
	- object treeview
	- properties
	- envents


<b>topbar</b>
Located at the top and divided into a menu and a toolbar, it contains the commands for saving, loading, exporting and testing applications
The drop-down menu contains the main commands and secondary commands.

<b>toolbar</b>
Located on the left side of the ide it contains all the elements that can be inserted in a program. the first element is the form, that is to say a real draggable window.
To insert an element, select the parent element on the screen or in the treeview and click on the element to add.

<b>screen</b>
It is the center of the screen where objects are placed. It has no properties and is not exported

<b>inspector</b>
the right part of the ide is occupied by this tool which is divided into three parts

<b>object treeview</b>
displays the tree of objects on the screen and allows you to choose the current element

<b>properties</b>
displays the properties of the selected object and allows you to edit the values

<b>events</b>
allows you to edit the code of an event of the selected object.
The last item, on the other hand, edits the special _script which is common and global for the whole program but only works in the test or exported phase
