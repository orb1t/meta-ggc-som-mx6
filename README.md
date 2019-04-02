# meta-ggc-som-mx6
Yocto Meta  layer, which adds support for a board named ggc-som-mx6, with hardware description and .bbappends based on meta-variscite-fslc layer

This README file contains information on the contents of the meta-ggc-som-mx6 layer.

Please see the corresponding sections below for details.

Dependencies
============

  URI: https://github.com/varigit/variscite-bsp-platform.git
  branch: sumo

Patches
=======

Please submit any patches against the meta-ggc-som-mx6 layer to the xxxx mailing list (xxxx@zzzz.org)
and cc: the maintainer:

Maintainer: Denys Gatsenko <orb1t.ua@gmail.com>

Table of Contents
=================

  I. Adding the meta-ggc-som-mx6 layer to your build
 II. Misc


I. Adding the meta-ggc-som-mx6 layer to your build
=================================================

Run 'bitbake-layers add-layer meta-ggc-som-mx6'

II. Build console-only demo image with Freescale’s multimedia packages (VPU and GPU)
==================================

Run 'MACHINE=ggc-som-mx6 DISTRO=fslc-framebuffer . setup-environment build_fb'
Run 'bitbake fsl-image-machine-test'
