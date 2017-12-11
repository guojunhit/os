# os

```
TSS1_SEL equ 0x30
LDT1_SEL equ 0x38
bits 32;设置处理器模式位模式为32位

0x00000000  startup_32:
                mov eax,0x10
    mov ds,ax
    lss esp,[init_stack]
```
