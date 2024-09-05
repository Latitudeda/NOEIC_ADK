StandardPackage
############################

The Pinghu StandardPackage is a packaging solution for photonic integrated circuits (PICs). The following table shows the parameters of Pinghu Standard Package.

    * Note that after using the StandardPackage a ``Standard_package.log`` file is created in the current folder, send this file to **SJTU-Pinghu Institute of Intelligent Optoelectronics** first to discuss the possibilities.

+----------------------+------------------------------------------------------------------------------------------------------+
| Parameters           | Description                                                                                          |
+======================+======================================================================================================+
|pic_width             | Width of PIC.                                                                                        |
+----------------------+------------------------------------------------------------------------------------------------------+
|pic_length            | Length of PIC.                                                                                       |
+----------------------+------------------------------------------------------------------------------------------------------+
|couplers_type         | True for EC and False for GC.                                                                        |
+----------------------+------------------------------------------------------------------------------------------------------+
|grating_couplers_type | True for Vertical grating coupling and False for Horizontal reflective grating coupling.             |
+----------------------+------------------------------------------------------------------------------------------------------+
|coupler               | For automated Coupler placement.                                                                     |
+----------------------+------------------------------------------------------------------------------------------------------+
|couplers_number       | Max. fibers per side for 127 µm pitch: 10.                                                           |
+----------------------+------------------------------------------------------------------------------------------------------+
|couplers_pitch        | Standard supported fiber pitches is 127 µm.                                                          |
+----------------------+------------------------------------------------------------------------------------------------------+
|pad_row               |True for single pad row and False for multiple pad row.                                               |
+----------------------+------------------------------------------------------------------------------------------------------+
|pad                   | For automated Bondpad placement.                                                                     |
+----------------------+------------------------------------------------------------------------------------------------------+
|pad_number            | Number of pads per row: ≤ 24.                                                                        |
+----------------------+------------------------------------------------------------------------------------------------------+
|pad_interval_x        |Bond pad interval: minimum interval of 10 µm for single and double rows pads.                         |
+----------------------+------------------------------------------------------------------------------------------------------+
|pad_interval_y        |Bond pad interval: minimum interval of 30 µm for pads between double rows.                            |
+----------------------+------------------------------------------------------------------------------------------------------+
|pad_dim_x             |Bond pad size: minimum length of 50 µm for single and double rows pads.                               |
+----------------------+------------------------------------------------------------------------------------------------------+
|pad_dim_y             |Bond pad size: minimum width of 50 µm for single and double rows pads.                                |
+----------------------+------------------------------------------------------------------------------------------------------+
|pad_to_edge           |Bond pad to edge: 50 µm.                                                                              |
+----------------------+------------------------------------------------------------------------------------------------------+
|north_pad_shift       |North bond pad shift: positive for right sift and negative for left shift.                            |
+----------------------+------------------------------------------------------------------------------------------------------+
|south_pad_shift       |South bond pad shift: positive for right sift and negative for left shift.                            |
+----------------------+------------------------------------------------------------------------------------------------------+


An example of the use of Edge Couplers.
********************************************
.. image:: ../images/eg_ec.png


An example of the use of Grating Couplers.
********************************************
.. image:: ../images/eg_gc.png


