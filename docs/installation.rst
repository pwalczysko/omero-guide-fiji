How to install the OMERO plugin for Fiji/ImageJ
===============================================

Description:
------------

Fiji is a free open-source image processing package based on
ImageJ, \ https://imagej.net/Fiji\ . The following workflow should how to
install the OMERO plugin for Fiji and ImageJ.

The OMERO plugin does not have yet and update site.

**Setup step-by-step:**
-----------------------

We assume that you have already Fiji/ImageJ installed locally.

In this section, we will cover the steps required to install the
OMERO.imagej plugin for Fiji. If you wish to install it for ImageJ,
an additional step is needed.

We first describe how the common installation steps for ImageJ and Fiji.
We then describe how to install the *Bio-Formats Package* for ImageJ.

Installing the OMERO.imagej plugin also adds the dependencies
required to connect to OMERO using the Script Editor of Fiji.

Installation of the OMERO.imagej plugin for Fiji and ImageJ, the
common steps:

-  Download from \ https://www.openmicroscopy.org/omero/downloads \
   the latest 5.x.x version of ImageJ/Fiji plugin for OMERO

.. image:: images/setup1.png

-  Extract the downloaded .zip archive. Remember where you extracted it to.

-  Copy the extracted folder and paste it to the *plugins* folder
   of Fiji.

-  **Note:** Some Windows unzip apps create a double folder enclosing the
   plugin. If that is the case, copy the inner OMERO.imagej-5.x.x
   folder into *Fiji.app > plugins* folder.

-  Now, restart Fiji. If you are using ImageJ, follow with the
   additional step below.

**Installation of Bio-Formats Package, ImageJ only:**

-  Download the latest version of the *Bio-Formats Package* from:
   https://www.openmicroscopy.org/bio-formats/downloads

.. image:: images/setup2.png

-  Move the downloaded file into the *ImageJ > plugins* folder.

-  Restart ImageJ.
