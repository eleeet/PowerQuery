﻿# Binary.Decompress
Decompresses a binary value using the given compression type.
***
function (optional binary as nullable any, compressionType as number) as nullable any
***
# Descrition 
Decompresses a binary value using the given compression type.  The result of this call is a decompressed copy of the input. Compression types include: 
  <ul>
        <li><code>Compression.GZip</code></li>        
        <li><code>Compression.Deflate</code></li>  
      </ul>
# Category 
Binary
# Examples 
Decompress the binary value.
```
Binary.Decompress(#binary({115, 103, 200, 7, 194, 20, 134, 36, 134, 74, 134, 84, 6, 0}), Compression.Deflate)
```
> #binary({71, 0, 111, 0, 111, 0, 100, 0, 98, 0, 121, 0, 101, 0})
***