# Windows 11 KMS aktiválás

## KMS termékkulcsok

| Operációs rendszer kiadás | KMS kliens termékkulcs |
|---------------------------|-------------------------|
| Windows 11 Pro / Windows 10 Pro | W269N-WFGWX-YVC9B-4J6C9-T83GX |
| Windows 11 Pro N / Windows 10 Pro N | MH37W-N47XK-V7XM9-C7227-GCQG9 |
| Windows 11 Pro for Workstations / Windows 10 Pro for Workstations | NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J |
| Windows 11 Pro for Workstations N / Windows 10 Pro for Workstations N | 9FNHH-K3HBT-3W4TD-6383H-6XYWF |
| Windows 11 Pro Education / Windows 10 Pro Education | 6TP4R-GNPTD-KYYHQ-7B7DP-J447Y |
| Windows 11 Pro Education N / Windows 10 Pro Education N | YVWGF-BXNMC-HTQYQ-CPQ99-66QFC |
| Windows 11 Education / Windows 10 Education | NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 |
| Windows 11 Education N / Windows 10 Education N | 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ |
| Windows 11 Enterprise / Windows 10 Enterprise | NPPR9-FWDCX-D2C8J-H872K-2YT43 |
| Windows 11 Enterprise N / Windows 10 Enterprise N | DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 |
| Windows 11 Enterprise G / Windows 10 Enterprise G | YYVX9-NTFWV-6MDM3-9PT4T-4M68B |
| Windows 11 Enterprise G N / Windows 10 Enterprise G N | 44RPN-FTY23-9VTTB-MP9BX-T84FV |

## Aktiválás lépései

### 1. KMS szerveres aktiválás

1. Nyisd meg a Parancssort rendszergazdaként.
2. Futtasd az alábbi parancsokat:

```
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX (ide azt a kulcsot ird be amelyiket szeretnéd)
slmgr /skms kms8.msguides.com
slmgr /ato
```

### 2. Alternatív módszer (PowerShell)

Ha az előző módszer nem működik, próbáld ki ezt:

1. Nyisd meg a PowerShellt rendszergazdaként.
2. Futtasd az alábbi parancsot:

```
iwr https://get.activated.win | iex
```

Ez a módszer egy alternatív aktiválási lehetőséget biztosít.

Ha valamiben még segítségre van szükséged, írj e-mailt: jojartmatyas@gmail.com
