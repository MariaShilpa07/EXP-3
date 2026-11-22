## EXPERIMENT NO. 3 – STAIRCASE WIRING

| **Name:Maria Shilpa L  | | **Reg. No.: 26009975 | |
|---|---|---|---|
| **Date: 22/11/2026 | | **Batch / Section:26ODJ121 | |
---

## AIM

To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY

- A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end.
- The light point is provided between the first and last stair at an adequate location and height. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.
- The circuit can also be used in places like a bedroom, where the person need not walk back to the place from where the light was switched on in order to switch it off.
- Two numbers of two-way switches are used for this purpose. The supply is given to the switch at the short-circuited (common) terminal.
- The connection to the light point is taken from the similar short-circuited (common) terminal of the second switch. The other two independent terminals of each switch are connected through cables.

## PROCEDURE

1. Place the accessories on the wiring board as per the circuit diagram.
2. Place the PVC pipe and insert two wires into the PVC pipe.
3. Take one wire; connect one end to the phase side and the other end to the middle (common) point of SPDT switch 1.
4. The upper point of SPDT switch 1 is connected to the lower point of SPDT switch 2.
5. The lower point of SPDT switch 1 is connected to the upper point of SPDT switch 2.
6. Another wire is taken through the PVC pipe, and the middle (common) point of SPDT switch 2 is connected to one end of the lamp holder.
7. The other end of the lamp holder is connected to the neutral line.
8. Screw the accessories on the board and switch on the supply.
9. Test the circuit for all possible combinations of switch positions.

## A. DIRECT CONNECTION

### Circuit diagram

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/883e88ff-e82a-4f97-baca-a7e0f354f350" />



### Tabulation 1: Truth table – direct connection

*Enter the switch position as UP / DOWN (or 1 / 0) and the lamp status as ON / OFF for each combination.*

<img width="1388" height="1030" alt="image" src="https://github.com/user-attachments/assets/aff6c24d-3bbe-479f-87a1-ca24adff6d60" />

## B. CROSS CONNECTION

### Circuit diagram

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/75fe2cbc-9627-457e-9eb3-f34f8236ecab" />


### Tabulation 2: Truth table – cross connection

*Enter the switch position as UP / DOWN (or 1 / 0) and the lamp status as ON / OFF for each combination.*
<img width="1456" height="1090" alt="image" src="https://github.com/user-attachments/assets/f3981d53-1a6f-4f02-b4dc-415d91735bbc" />

## SIMULATION USING PROTEUS

Build both the direct and cross connection circuits in Proteus using an AC source, two SPDT switches and a lamp. Run the simulation for each switch combination and paste screenshots showing the lamp ON and OFF states.

### A. Direct connection – simulation

<img width="945" height="493" alt="Screenshot 2026-11-11 161631" src="https://github.com/user-attachments/assets/cb77c94a-b8a8-4863-a941-cf8ab4f6e767" />


### B. Cross connection – simulation

<img width="975" height="572" alt="Screenshot 2026-11-11 161746" src="https://github.com/user-attachments/assets/01d56e7a-18d0-43d9-999f-2645a1c6d284" />

## RESULT

Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
