# VAJA10_SPI_PROTOKOL

b) Kaj pomenijo pri SPI protokolu kratice SCK, MISO, MOSI in SS? Kateri enoti pripadajo te kratice?
SCK-Serial clock ; MISO- Master input slave output ; MOSI- Master output slave input ; SS- Slave select

c) Kateri enoti pripadajo kratice SDI, SDO in CS ter kaj te kratice pomenijo?
Pripadajo Slavu. SDI- Slave data in ; SDO- slave data out ; CS- Chip select

e) Glede na tabelo, ustrezno konfigurirajte pine senzorja nagiba LIS3DSH:
SPI1 _SCK SPI1_MOSI CS_I2C/SPI SPI1_MISO INT1/DRDY
    PA5      PA7          PE3      PA6      PE0

V zavihku Pinout izberite SPI1 in izberite Full-Duplex Master. Kateri pini se obarvajo zeleno? _____, ____
in ______.

g) V gumbu GPIO aktiviramo salve select CS_I2C/SPI na High GPIO Output level. Kateri pin je to? ____.

h) V gumbu SPI1 nastavimo prescaler na takšno vrednost, da bo hitrost prenosa 1 MBits/s (baud rate).
Koliko je vrednost skaliranja? _______.

