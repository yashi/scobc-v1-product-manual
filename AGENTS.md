# Using this repo as a reference

This repository contains the **SC-OBC Module V1 Product Manual** (Document Number:
SC-ESP-00150). The manual is written in AsciiDoc and built with Antora.

## How the content is organized

- `product/modules/`: Product Overview (`ROOT/`), OBC Module hardware specifications
  (`hardware/`), Development Board (`dev-board/`)
- `software/modules/`: RPU/APU software (`software/`), AI Engine (`ai-engine/`)
- `fpga/modules/`: FPGA design flow (`fpga/`), Safety Processor (`safety-processor/`)

Each module's `nav.adoc` lists its pages in reading order. Use these files to find the
relevant `pages/*.adoc`, then search for specific technical terms.
