# FT8-Helper-2.4.4

New in 2.4.4 v.s 2.4.2:
. supports WSJT-X 2.5.3
- Max. Audio Freq. can be set to 1000Hz (required for 60m band in GB)

New in 2.4.3 vs. 2.4.2:
- Rep. Diff. field: shows the average difference of received and transmitted reports. A positive number indicates that you receive better reports as you send.
- Repair bug ignoring stations calling CQ-DX in S/P-mode.

New in 2.4.2 vs. 2.4.1:
- Strategy selection and the status of all checkboxes are saved and restored when starting the Helper again.
- Supporting WSJT-X 2.5.1 and 2.5.2 too
- Minor fixes for non-standard callsigns

New in 2.4.1 vs. 2.3:
- WSJTX-2.5.1 is supported
- WSJT-X can be started with -rig=RIG-NAME extension (multiple instances are not supported)
- New CQ-strategy "CQ+SP". If no answer for CQ received, the Helper calls CQ-calling stations
- Optional repetition of RR73 if no 73 received at the end of the QSO. Warning if no closing 73 received.
- All "Auto Strategy" settings are working for incoming calls too.
- Filter are available to exclude and prefer specific continents.
- Counts successful and broken QSOs
- Automatic setting of the width of the Band-Activity and RX-frequency windows
- New log entry indicating missing 73 at the end of the QSOs

==========================================================================

The FT8-Helper program was developed as macro extension for the JTDX using the Quick-Macros program. Comparing to other FT8-Robot programs, the FT8-Helper is more “intelligent”, it interprets the received messages of WSJTX and acts according to the own pre-programmed QSO strategy. The delivered EXE file contains the licence for Quick-Macros.

Main Features of V2.4.3:
- Works with WSJT-X 2.5.1 and 2.5.2
- Automatic operation in both "CQ" and "S/P" mode.
- New mode: CQ+SP: It calls CQ and if no station answers, it calls CQ-calling stations.
- Automatic find of free frequency in CQ-mode
- Automatic changes between CQ and S/P mode with programmable intervals, dependng on band activity.
- Repeat RR73 if no closing 73 received. Warning if no colsing 73 received.
- Comfortable set-up of all parameter
- Easy installation
- WSJT-X can start with the -rig-name argument
- Opens the QRZ.com page of the station when starting a QSO
- Counts logged and broken QSOs.  
- Shows the average difference between received and transmitted reports.

Various strategies in CQ- and S/P-mode, Calls stations with:
- Best Priority acording the WSJT-X "Colours" settings.
- Best S/N: If Stations with the same priority received, the one with the best S/N selected
- Only DX: Minimum DX-distance can be specified in Km and Miles.
- Prefer-DX DX stations are prefered.
- Most distance
- Prefer Wanted: prefixes, DXCC-entities and continents can be specified.
- Only Wanted: prefixes, DXCC.entities and continents can be specified 
- Exclude stations, präfixes DXCC-entities and continents can be specified
- Keep-Even/Odd cycle for 6m DX-ing

Band-Hopping:
- Programmable on daily basis
- Two time ranges per day can be programmed
- Operating band, mode, and strategy can be selected.

Feedback to: dg5lp@darc.de
