# FILL SCREEN WITH "A"

```
LOC   CODE         LABEL     INSTRUCTION

C000                         * = $C000
C000  A2 41                  LDX #$41
C002  8A                     TXA
C003  20 D2 FF               JSR $FFD2
C006  E8                     INX
C007  4C 03 C0               JMP $C003
C00A  60                     RTS
C00B  00                     BRK
```
