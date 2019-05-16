### 1
a;  262144000

b;  262144000

c;  One entry needs an Integer, which is 32 Bit big (4 Byte), that 2 times since an entry has a physical block adress and a next block adress

d;  262144000 * 4*2 ~ 2GB

### 2
b;  Get starting block by the FAT and go through all --TODO--

### 3
    10 * 4096 + 4096 * 1024 + 4096 * 1024 * 1024 + 4096 * 1024 * 1024 * 1024 = 4TB
    10 * 1024 + 1024 * 256 + 1024 * 256 * 256 + 1024 * 256 * 256 * 256 = 17,2GB

### 4
a;  512 byte for a block is sufficient since the maximum file-size would be 8.6GB

    10 * 512 + 512 * 128 + 512 * 128 * 128 + 512 * 128 * 128 * 128 = 8623620096 byte = 1GB

    10 * 1024 + 1024 * 256 + 1024 * 256 * 256 + 1024 * 256 * 256 * 256 = 17247240192 byte = 17,2GB

b;  We can still take 1024 Byte Blocks
