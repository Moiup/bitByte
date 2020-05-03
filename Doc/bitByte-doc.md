[Main menu](../Readme.md)

# bitByte

## Type

```C
byte
```
It is an `unsigned char`, in order to be composed of 8 bits.

## Constants
We got two constants:
- `BITBYTE_FALSE`: 0
- `BITBYTE_TRUE`: 1

## Functions

```C
void bitByte_set_bit(byte, int)
```
Set a bit to 1. [More here.](./functions/bitByte_set_bit.md)

```C
void bitByte_reset_bit(byte, int)
```
Reset a bit to 0. [More here.](./functions/bitByte_reset_bit.md)

```C
int bitByte_get(byte, int)
```
Return a bit. [More here.](./functions/bitByte_get.md)

```C
void bitByte_init(byte);
```
Initialise a byte to 0. [More here.](./functions/bitByte_init.md)

```C
byte bitByte_get_byte(unsigned long int, int)
```
Return a byte of a type. [More here.](./functions/bitByte_get_byte.md)

```C
void bitByte_display(byte)
```
Display a byte (little in the end). [More here.](./functions/bitByte_display.md)
