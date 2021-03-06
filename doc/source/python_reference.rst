=========
Reference
=========

.. automodule:: expyfun
   :no-members:
   :no-inherited-members:

This is the classes and functions reference of expyfun. Functions are
grouped by hardware control type.


Experiment Control
==================

.. currentmodule:: expyfun

Classes:

.. autosummary::
   :toctree: generated/
   :template: class.rst

   ExperimentController
   EyelinkController

Functions:

.. autosummary::
   :toctree: generated/
   :template: function.rst

   assert_version
   binary_to_decimals
   decimals_to_binary
   download_version
   get_keyboard_input
   wait_secs

Experiment Design
=================

.. currentmodule:: expyfun.stimuli

Functions:

.. autosummary::
   :toctree: generated/
   :template: function.rst

   convolve_hrtf
   compute_mls_impulse_response
   play_sound
   repeated_mls
   rms
   vocode
   window_edges

.. currentmodule:: expyfun.io

Functions:

.. autosummary::
   :toctree: generated/
   :template: function.rst

   read_hdf5
   read_tab
   read_wav
   write_hdf5
   write_wav

.. currentmodule:: expyfun.visual

Classes:

.. autosummary::
   :toctree: generated/
   :template: class.rst

   Circle
   ConcentricCircles
   Diamond
   FixationDot
   Line
   RawImage
   Rectangle
   Text

Experiment Code Blocks
======================

.. currentmodule:: expyfun.codeblocks

Functions:

.. autosummary::
   :toctree: generated/
   :template: function.rst

   find_pupil_dynamic_range
   find_pupil_tone_impulse_response

Analysis
========

.. currentmodule:: expyfun.analyze

Functions:

.. autosummary::
   :toctree: generated/
   :template: function.rst

   barplot
   dprime
   dprime_2afc
   plot_screen
   restore_values

Logging and Configuration
=========================

.. currentmodule:: expyfun

Functions:

.. autosummary::
   :toctree: generated/
   :template: function.rst

   set_log_level
   set_config
