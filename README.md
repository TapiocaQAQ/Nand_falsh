# **Nand Flash**
## complete
use fuse package to implement Nand basic functions
* Nand `read, write, erase`
    - ssd_do_read -> ftl_read -> ssd_read
* lba 2 PCA table
* Nand `overwrite`
* `garbage collection` (manage memory with queue, lower Write Amplification 
Factor (WAF)
)
    -  implement `op queue, AV queue`
    -  implement `normal gc, gc only one`
## learn
- `Firmware Programming`
- how to create and managment a P2L, L2P table
- Nand read & write logic
- gc design