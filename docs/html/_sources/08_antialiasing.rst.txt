Antialiasing
============

Antialiasing is used to prevent "stairs" as shown in the picture below:


.. image:: _images/08_antialiasing_example.png


You find the setting in the menu of Canvas:

.. image:: _images/08_antialiasing_setting.png

If you have a Nvidia GPU, also make sure to check the Antialiasing settings in there:

.. image:: _images/08_antialiasing_nvidia.png


While doing Bézier distortion, the setting was not enough smooth for my purpose, so 
here is a workaround:

- Create a RenderTarget which has 2x the size of your Canvas, enable Multisample Anti-Antialising.

.. image:: _images/08_antalising_upscale.png

