## bios

bios 将第一扇区存放的 `bootsect` 搬运至内存的 0x7c00 处 

## bootsect.s

```asm
mov ax,0x07c0
mov ds,ax
```

设置ds 为0x07c0 也就意味着逻辑上的段基址为 0x07c0 << 4 即 0x7c00





