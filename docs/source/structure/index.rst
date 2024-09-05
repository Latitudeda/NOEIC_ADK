ADK structure
======================

Assembly Design Kit (ADK) is a tool for designated users to generate layouts based on Pinghu Standard Packages design rules.

``PingHu_ADK1p0_Latitudeda`` package includes three subfolders: ``examples``, ``packages``, and ``technology``.

* ``examples``

    * ``example_ec.py`` : An example of a packaging template that uses Edge Couplers.

    * ``example_gc.py`` : An example of a packaging template that uses Grating Couplers.

* ``packages``

    * Store the packaging setting for Pinghu Standard Packages.

* ``technology``

    * Store the technology setting which matched the Pinghu design rules.

* ``layers.lyp`` : This file allows layout tools e.g. Klayout to recognize the layer information when displaying gds file to the layout tool.

    .. image:: ../images/lyp.png

