Skyrim VR
=========

Launching with proton4.11-2 is fine except no sound.

To fix sound (properties>set launch options>paste):

.. code::

    WINEDLLOVERRIDES="xaudio2_7=n,b" PULSE_LATENCY_MSEC=90 %command%
