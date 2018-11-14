---
title:  "Robust AVC decoder"
excerpt: Simulation of Robust AVC Decoding in presence of data loss
author: Enrico Masala
license: (for the modifications) GNU General Public License version 3.0 (GPLv3)
tags: h264
categories: Streaming
external_link: http://media.polito.it/wordpress/activities-within-jeg/
---

This software decodes an AVC-compliant bitstream applying some loss patterns as given in an input file. Please note that the software simulates the data loss (in a pretty realistic way) by operating on the UNCORRUPTED version of the bitstream. This allows to avoid crashes, erroneous output of frames etc. independently of the loss pattern. More details in the technical notes accompanying the software and in the input document of the VQEG meeting in Jan 2014 in Boulder,CO (JEG-Hybrid session)
