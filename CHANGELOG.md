Change Log
==========

### Ver. 1.12.0 (26/03/24)
- Modify NodeInfo format
Low level:
- Improving performance in D3d rendering
- Fixing VideoOverlayMixer in handling I420 pixel format

### Ver. 1.11.5 (24/03/24)
- Update MisbCore
	- Remove length from VMTI Location (tag 17)
	- Remove length from VMTI Velocity and Acceleration DLP 
- Generic Flag Data (tag47) Versions 13 through 16 of ST 0601 unintentionally inverted the column definitions; 
- Add an ini patch to disable footer search
- Add option for async callback of sync frames
- Modify StCore interface
- Add new property in IStCoreWr - SequenceHeaderInsertionIntervalMsec
- Added new property in IStCoreWr - SequenceHeaderInsertionIntervalMsec
- Lver modification

### Ver. 1.10.10 (21/12/23)
- Update low level

### Ver. 1.10.4 (23/08/23)
- Low level update. 
- Support the sps information provided in an rtp packet with a format STAP-A 
- Fix the SequenceHeaderInsertionOnKeyFrames property did not reach its destination in the DVR mode

### Ver. 1.10.3 (27/06/23)
- Low level update. Decoder memory leak fix

### Ver. 1.10.2 (31/05/23)
- Close target file.
- Fix status string on the second run 

### Ver. 1.10.1 (29/05/23)
- Make cursor visible on exit.

### Ver. 1.10.0 (23/05/23)
- Low level update. FFmpeg version change

### Ver. 1.9.4 (05/04/23)
- Update StCore low level

### Ver. 1.9.3 (14/08/22)
- Update MisbCore

### Ver. 1.9.2 (09/08/22)
- Update low level
- Add more tags

### Ver. 1.9.1 (29/06/22)
- Update low level
- New Node info support

### Ver. 1.8.11 (19/12/21)
- Update low level

### Ver. 1.8.10 (23/11/21)
- Update low level
- Add time restricted license support
- Move to vc142

### Ver. 1.8.9 (14/11/21)
- Update Low level

### Ver. 1.8.8 (14/10/21)
- Add FrameAccuracyRequiresSequenceHeaders config 
- Low level update

### Ver. 1.8.7.1 (13/05/21)
- Low level update

### Ver. 1.8.7 (25/03/21)
- Use UTC time
- Fix HLS duration (with discontinuity) 
- Low level update

### Ver. 1.8.6 (18/01/21)
- Add ContiguousDemuxedVideo
- Low level update

### Ver. 1.8.5.0
- Update low level
- Fix Big Endian Unicode in UTF-16

### Ver. 1.8.4.3
- Low level update

### Ver. 1.8.4.2
- Low level update

### Ver. 1.8.4.1
- Fix Tag 20 ( Sensor Relative Roll Angle) validation

### Ver. 1.8.4
- Fix RTSP (tcp)
- Enable FIPS Compliant authorization

### Ver. 1.8.3
- Low level update (StCore 3.8.3)

### Ver. 1.8.2
- Low level update (StCore 3.8.1)

### Ver. 1.8.1
- Low level update (StCore 3.8.1)
- MisbCore RAW Klv processing

### Ver. 1.8.0
- Low level update - StCore 3.8.0

### Ver. 1.2.14
- Low level update - StCore 3.7.11

### Ver. 1.2.13
- Low level update - StCore 3.7.7

### Ver. 1.2.12
- Low level update - StCore 3.7.6

### Ver. 1.2.11 
- Low level update - StCore 3.7.5

### Ver. 1.2.10 
- Low level update - StCore 3.7.4

### Ver. 1.2.9 
- Low level update - StCore 3.7.3

### Ver. 1.2.8.2 
- Rebuilt with hboost 1.71 and vc141

### Ver. 1.2.8.1 
- Low level update - StCore 3.5.0

### Ver. 1.2.8
- Low level update
- Allow raw packet export for Klv that was not decoded

### Ver. 1.2.7
- Low level update

### Ver. 1.2.6
- RS232 recast

### Ver. 1.2.5
- Kmz option renamed to kmzTour
- Kml network link
- hideConsole added

### Ver. 1.2.4
- Kmz (Google Earth tour) export added

### Ver. 1.2.3
- Low level update

### Ver. 1.2.2
- Low level update
- Audio rendering disabled when no video is shown

### Ver. 1.2.1
- Low level update
- Added Save NodeInfo

### Ver. 1.2.0
- Low level update

### Ver. 1.0.2
- Low level update

### Ver. 1.0.1
- Low level changes


### Ver. 1.0.0
- Initial version.



    