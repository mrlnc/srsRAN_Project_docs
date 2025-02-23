.. _general_release_notes:

Release Notes
=============

23.5
----

 * Updated ASN.1 of RRC/NGAP/F1AP/E1AP to 3GPP Release 17.4
 * Add UE capability transfer procedure
 * Add support for srsUE
 * CSI-RS in Downlink
 * Add virtual RF driver to use with Amarisoft UE
 * Expose further config parameters
 * Other bug-fixes and improved stability and performance in all parts

23.3 (initial public release)
-----------------------------

  * FDD/TDD supported, all FR1 bands
  * 15/30 KHz subcarrier spacing
  * All physical channels including PUCCH Format 1 and 2, excluding Sounding-RS
  * Highly optimized LDPC and Polar encoder/decoder for ARM Neon and x86 AVX2/AVX512
  * All RRC procedures excluding Mobility, Paging and Reestablishment
  * All MAC procedures excluding power control
  * Split 8 support using Ettus/NI USRPs