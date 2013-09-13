C4-Engine-Plugin-NodeFinder
===========================

This plugin allows for easier searching and navigation of scenes. 


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
The NodeFinder plugin is access via an editor page. To add this page to your World 
Editor window, click on the Page menu, then select NodeFinder. You should now have 
a NodeFinder page in the tool column.


Search by displayed node name. The following node types are supported:
kNodeLight
kNodeModel
kNodeGeometry
kGeomergyPromitive
kNodeImposter
kNodeInstance
kNodeZone
kNOdePortal

Only nodes of these types are currently suppored by search.

To start searching, start typign
