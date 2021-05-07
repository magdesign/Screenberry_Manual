Usage
=====


Launch
******

1. Insert the USB Licenses Dongle
2. Open *Screenberry2Launcher* 
3. Open *ScreenberryPanelLauncher*


.. image:: _images/04_launcher.png


4. Select the server and click *Connect to Server*


Creating a Project
******************

Create a new empty project:

.. image:: _images/04_new_project.png



Insert Nodes
************

1. Open the *Node Graph* window:

.. image:: _images/04_node_graph.png


2. Right click somewhere in the *Node Graph* window or use the keyboard shortcut ('N') to add nodes:


.. image:: _images/04_add_nodes.png

3. Insert a *Media Player*, a *Display* and a *Canvas* to get a basic playout:


.. image:: _images/04_basic_playout.png



Setup Output Monitor
********************

Define your second monitor as main output screen:

1. Select the *Display* node and define its size on the settings panel:

.. image:: _images/04_display_settings.png


2. Select the *Canvas* node and define its size and position on the settings panel:

.. image:: _images/04_canvas_settings.png


.. Note::
    Since our main screen in this example has a resolution of 1920 x 1080 pixel, we shift the *Canvas* by 1920 pixels to appear on the second screen.


Insert Media
************


1. Open the *MediaPlayer*:


.. image:: _images/04_mediaplayer.png


2. Drag and drop your media into it and select *Add*:

.. image:: _images/04_mediaplayer_import.png


3. Your imported media appears in the *MediaPlayer*.

Item Settings
*************

When using *.png files with alpha channels and it appears jagged, right click the media and select *Item Settings*:


.. image:: _images/04_mediaplayer_item_settings.png


in there make sure to check: *Premultiply on alpha*:


.. image:: _images/04_mediaplayer_item_settings2.png
