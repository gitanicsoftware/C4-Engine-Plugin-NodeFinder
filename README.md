C4-Engine-Plugin-NodeFinder
===========================

This plugin allows for easier searching and navigation of scenes. 
It allows you to search by node name, and can limit the search to
visible nodes. This makes it very easy to select a single item in
a heavily populated viewport by simply starting to search for
the item name.

Installation
---------------------------

To install the plugin, download the latest copy from GitHub at 

https://github.com/gitanicsoftware/C4-Engine-Plugin-NodeFinder/archive/master.zip

and unzip it in the root C4 directory. In your C4 VisualStudio project, right click
on the "Solution 'C4'" in the Solution Explorer, and select Add->Existing Project.
Navigate to C4/Gitanic/NodeFinder and add the project to your solution. You should
now be able to rebuild the project.


Usage
------------------------
The NodeFinder plugin is accessed via an editor page. To add this 
page to your World Editor window, click on the Page menu, then select 
NodeFinder. You should now have 
a NodeFinder page in the tool column.

Search is done in real-time, and matching nodes are displayed in the 
list. You can limit the search to only visible nodes by checking the 
"Filter Visible" box. Additionally, you can limit the search to either 
perspective only, or orthographic only viewports with the two toggle 
buttons.

Lastly, "Frame Selection" option will automatically frame a node when 
you click on it in the list.

Searching is done by looking at the name of the node. The search will
match substrings ("Light" will match "Landscape Light"), however, for
performance reasons, the search is case sensative.

The following node types are supported in the search:

- kNodeLight
- kNodeModel
- kNodeGeometry
- kGeomergyPromitive
- kNodeImposter
- kNodeInstance
- kNodeZone
- kNodePortal

A brief video tutorial/demonstration is available at
http://www.youtube.com/watch?feature=player_embedded&v=k5Mpg3pEWsw
