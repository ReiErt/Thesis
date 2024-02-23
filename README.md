# Thesis

This thesis was written between October 2023 and February 2024. It is my own work and nothing but my own work. Work that is not mine is referenced with its source.

This Bachelor's Thesis was written on the Ostbayerische Technische Hochschule Regensburg (Regensburg University of Applied Sciences) as part of my degree in Computer Engineering.

This thesis examines random number generation in three devices: (1) An FPGA module that I wrote, which uses ring oscillation as its entropy source, (2) the linux kernel entropy pool and (3) The PCIe Quantis Quantum Random Number Generator. Bitstreams of several MBs were captured from all three sources and evaluted against the NIST-800 22 test suite. All devices passed the test.  However, my FPGA module lacks any safety mechanisms to prevent targeted attacks.
