# Public CD of SMPTE ST 2136-1

## General

_This repository is *public*._

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md), [LICENSE.md](./LICENSE.md) and
[PATENTS.md](./PATENTS.md) for important notices.

Your feedback is welcome at [Issue Tracker](https://github.com/SMPTE/st2136/issues) or at [32nf-chair@smpte.org](mailto:10e-chair@smpte.org).

## Public Committee Draft (PCD) Notice

The following elements are made available for a public review period ending no earlier than 2025-05-31, and no later than 2025-05-31:

* [{prose element}]({link to prose element})
* [{element #1}]({link to element #1})
* ...

## Details

SMPTE ST 2136-1 “Common LUT Format” defines an XML file format for the interchange of color transformations using an XML schema. The schema supports Look-Up Tables of several types: 1D LUTs, 3D LUTs, and 3×1D LUTs, as well as additional transformations such as matrices, range rescaling, and the ASC’s Color Decision List.

SMPTE ST 2136-1 is based on an earlier specification published by the Academy of Motion Picture Arts and Sciences [1] and is intended to be backwards compatible.
Existing CLF instances based on [1] can be converted into the SMPTE-compliant CLF format by only changing or adding the default namespace “xmlns="http://www.smpte-ra.org/ns/2136-1/2024."

A Public Committee Draft of SMPTE ST 2136-1 and sample CLF files are being provided for review in this repository for three months from XX. February 2025. Developers are encouraged to implement the design and provide feedback via GitHub to improve the document and to increase interoperability between implementations.
