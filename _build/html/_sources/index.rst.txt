.. Laser Scanner Platforms documentation master file, created by
   sphinx-quickstart on Tue Jul  4 21:15:03 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to the Laser Scanner by Platform docs
=============================================

.. toctree::
   :maxdepth: 2
   :caption: Platforms
   :hidden:

   Toradex Apalis (apalis) <./apalis.md>
   Digilent Arty Z7-20 (arty) <./arty.md>
   terasIC Cyclone V GX starter kit (cgsk) <./cgsk.md>
   Lattice CrossLink-NX eval board (cleb) <./cleb.md>
   Microchip PolarFire SoC Icicle kit (iccl) <./iccl.md>
   Aries Cyclone V SE SoM (mcep) <./mcep.md>
   Digilent Nexys Video (nxsv) <./nxsv.md>
   Efinix Titanium Ti180 dev kit (tidk) <./tidk.md>
   SiLabs UniversalBee dev kit (ubdk) <./ubdk.md>
   Avnet ZUBoard 1CG (zudk) <./zudk.md>

.. toctree::
   :maxdepth: 2
   :caption: FPGA Interfaces
   :hidden:

   DDR memory <./ddrmem.md>
   HDMI (out) <./hdmiout.md>
   MIPI CSI-2 <./mipicsi.md>
   PCI Express <./pcie.md>

Purpose
=======

This documentation covers the platform-specific aspects of the Whiznium StarterKit, which is a tabletop 3D laser scanner.

While it is closely related to the corresponding (Linux) host code, to be found here:

`Whiznium StarterKit on GitHub <https://github.com/mpsitech/wzsk-Whiznium-StarterKit>`_

... and to the VHDL/C device code, to be found here:

`Whiznium StarterKit Device on GitHub <https://github.com/mpsitech/wskd-Whiznium-StarterKit-Device>`_

Here you will find everything from adapter PCB schematics and board files, to vendor IDE bring-up instructions, to referred vendor IP documentation (such as application notes and datasheets).

Completion Matrix
=================

.. list-table::
   :widths: 30 5 5 5 5 5 5 5
   :header-rows: 1

   * - Platform
     - PCB's
     - VHDL/C code
     - host code
     - DDR
     - HDMI
     - MIPI
     - PCIe

   * - Toradex Apalis
     - ready
     - not applicable
     - published
     - not applicable
     - not applicable
     - not applicable
     - not applicable

   * - Digilent Arty Z7-20
     - ready
     - ready
     - ready
     - ready
     - ready
     - ready
     - not applicable

   * - terasIC Cyclone V GX starter kit
     - ready
     - in progress
     - in progress
     - in progress
     - in progress
     - in progress
     - in progress

   * - Lattice CrossLink-NX eval board
     - ready
     - ready
     - ready
     - not applicable
     - not applicable
     - ready
     - ready

   * - Microchip PolarFire SoC Icicle kit
     - ready
     - in progress
     - ready
     - not started
     - not applicable
     - dry exercise [#]_
     - not planned

   * - Aries Cyclone V SE SoM
     - ready
     - not started
     - not started
     - not started
     - not started
     - not started
     - not started

   * - Digilent Nexys Video
     - ready
     - in progress
     - ready
     - in progress
     - ready
     - in progress
     - in progress

   * - Efinix Titanium Ti180 dev kit
     - ready
     - in progress
     - in progress
     - ready
     - ready
     - ready
     - not applicable

   * - SiLabs UniversalBee dev kit
     - ready
     - in progress
     - ready
     - not applicable
     - not applicable
     - not applicable
     - not applicable

   * - Avnet ZUBoard 1CG
     - ready
     - in progress
     - ready
     - ready
     - not applicable
     - in progress
     - not applicable

.. rubric:: Comments

.. [#] more suitable platform to be found where clock and signals are routed differentially to a connector

..
   * - Toradex Apalis
     - published
     - ready
     - in progress
     - not started
     - dry exercise
     - not planned
     - not applicable

Last update: July 4, 2023.

In case of problems, please do not hesitate to contact MPSI Technologies at `support@mpsitech.com <mailto:support@mpsitech.com>`_.
