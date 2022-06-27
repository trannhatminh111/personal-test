## Version summary:

*Last updated: 2022-06-24 02:25 PM*
- Production Server https://demo.ndms2.skedulomatic.com: ` v1.4.16-4.0.9 v1.4.16.1-4.0.9`

- Staging-Dev Server  https://ndms2.sovereignsolutions.app:`v1.4.16-4.0.9 v1.4.17-4.0.9`

- Dev Server https://demo.ndms2.gisx.vn:`v2.0.1-5.0.0`

## Changelog v1.4.17-4.0.9 [2022-06-24 02:00 PM]

- `v1.4.17` `Upgrade` Improve dynamic filter to reuse in Explorer, Data Editor, User Management (Worker Management)

- `v1.4.17` `Upgrade` Improve data history feature

- New UI style

- Move Restore button to history detail panel

- `v1.4.17` `Upgrade` Change User Management (Worker Management) to use the same component with Data Editor

- `v1.4.17` `New Explorer` - Allow to remove selected layer

- `v1.4.17` `Bugfix` Map layer - Fix wrong position of selected marker
- -------------------------------------

- `v1.4.16.1` `Bugfix` translate Vietnamese to English

- Routing Search

- Data History

- Create Map layer in Layer Manager

- Flower/Table Search Box

- Show more

- Wednesday

- proj-ndms2


*Bu Mập*
*5:17 PM*
*Jump*

## Version summary:

*Last updated: 2022-06-22 05:00 PM*


Production Server https://demo.ndms2.skedulomatic.com: `v1.4.14-4.0.8 v1.4.16-4.0.9`
Staging-Dev Server https://ndms2.sovereignsolutions.app: `v1.4.14-4.0.8 v1.4.16-4.0.9`
Dev Server https://demo.ndms2.gisx.vn: `v2.0.1-5.0.0` 

## Changelog v1.4.16-4.0.9 [2022-06-22 05:00 PM]
- `Improve` Mobile Web - Support mobile view for About feature, Change password feature
- `Bugfix` Mobile Web - Fix can only right click the first time
- `Bugfix` Layer manager - 3568 - Defaultvalue and regex are not bound together in edit
- `Bugfix` Explore - Fix free search was skipped on toggling filter off
- `Bugfix` Map Layer - Fix marker detail issue on administrative map layer
- `Bugfix` Map Layer - Fix exported file not apply the sorter for RTO
- `New` Data Editor - Add API to ge/upload attachment
- `Bugfix` Data Editor - Fix exporting excel file, support boolean value on search
- `Bugfix` Data Editor - Fix cannot create data with datetime datatype
- `Bugfix` Import - Skip geocoding if dont have enough config
- `New` Auto navigate to thematic map if only one map exists
- `Bugfix` Remove hard set theme

- ---------------------
## Changelog  v1.4.15-4.0.8 [2022-06-19 02:03 PM]
- `Change` Layer Manager - Move Add Property button to the left (overlapped with toast)

- `Change` Data Editor - Improve detail & attachment UI
- `Bugfix` View history - fix node history issue
- `Change` - Put pincode at the end of address string
- `Bugfix` Data Editor - Fix wrong filter on download as excel file
- `Bugfix` Call reload memory when modify layer with map type property 

*Show more*
*June 17*
*proj-ndms2*

*Ngọc*
*9:32 AM*
*Jump*

#### MEETING NOTE

**Meeting information:**
**Time**: 14:30 - 16/6/2022
**Place**: Event Room Floor 4
**Topic**: Start Sprint 6
**Members**: 
**Stack holder**: Ramesh
**PO**: Ngoc, Vinh
**Scrum Master**: Hang
**BA:** Phi
**Dev:** Hang, Phuoc, Phuc
**Tester:** Thanh, Hung, Hong
**Absent:** Hao Dat

#### END SPRINT 6

#### **Sprint Goal**

- Fix v1.4 bugs (30%)
- Basic Init Tenant
- Improve Map layer Switcher for Table and Flower mode
- Download detail
- UI actions: sort, filter, close,...
- Show number of record of map-layer in maplayer-swithcher
- View history of a record

#### **Features**

- Mantis bugs
  47 issues solved
  9 bugs wait to confims
  DEMONSTRATE
  LIVE DEMO
  DISCUSS
  [MAP] What here
- Pincode should be at the end of address string (LOW)
  [Attachment]

- Not show in data manager (MEDIUM)
  Others:

- Created layer map is not render by VDMS service (HIGH)
- Create new tenant (HIGH)
- Upload logo (MEDIUM)
- If have 1 map, go directly to the map & load the last view map (LOW)
  Vietnamese language @Ngọc work with @manjary to screenshot (export language file)
  VIETNAMESE
- NOT CORRECT/ MISPELLING LABEL/NAME IN ENGLISH
- Review the prod server
- Deploy new prd
- NDMS2_BASE tenant on prod
- Review all the service, API
- Review the scope of the next sprint
- discuss about the button to turn off other features' markers
- add Change map render to backlog
*@Phạm Đức Tính will to take reponsility to control the render tool*

## RETROSPECTIVE

Version

## Changelog v1.1.0 (Sprint 2)

*Show more
June 17
proj-ndms2
Bu Mập
5:49 AM
Jump
Em gửi anh @Duy Thành*

## Version summary:

*Last updated: 2022-06-17 05:45 AM*

Production Server https://demo.ndms2.skedulomatic.com: `1.4.9-4.0.4 v1.4.14-4.0.8`
Staging-Dev Server https://ndms2.sovereignsolutions.app: `v1.4.14-4.0.8`
Dev Serverhttps://demo.ndms2.gisx.vn: `v2.0.1-5.0.0`

## Changelog v1.4.14-4.0.8 [2022-06-16 02:30 PM]

- New View editor history
- `Bugfix` - 3518 Data Editor-Import - import gives error field map
- `Bugfix` - 3557 Data Editor - Import - the status of the Import is still in Vietnamese
- `Bugfix` - 3597 Map layer - Interface error when hide maplayer
- `Bugfix` - 3560 ROUTE PLANNING - Showing inappropriate route
- `Bugfix` - 3568 Layer manager - Default value and regex are not bound together in edit
- `Bugfix` - 3582 Data Editor - Import - Import does not contain the min max condition of the field

## Changelog v1.4.13-4.0.7 [2022-06-16 06:00 AM]

- New Table/Flower Detail - Sort/Filter/Close/Detail in detail table/flower
- `Bugfix` - 3535 Import - If the file import that column has no title, the column order will be displayed
- `Bugfix` - What's here - Add postal code
- `Bugfix` - 3561 Map layer - Add more pageSize options on Flower/Table detail grid
- `Bugfix` - Flower Detail - Markers was changed randomly on selecting

## Changelog v1.4.12-4.0.6 [2022-06-15 10:00 AM]

- `New` Layer Manager - Allow to create Map layer in Data Layer Menu

- `New` Layer Manager - Add new data type to layer property (Map)
- `Bugfix` Worker Management - Fix cannot change page

## Changelog v1.4.11-4.0.5 [2022-06-14 03:50 PM]

- `New` Add Data Manager page for AppData layers (TEAM, ORGANIZATION, ORGANIZATION TYPE, EMPLOYEE TYPE, DEVICE STATUS)
- `Bugfix` - 3559 Explorer - Double click the object on the grid whiten the page (for Polygon)
- `Bugfix` - 3570 Explorer - Map layer switcher - use DisplayName instead of ColumnName
- `Bugfix` - 3561 MapLayer Switcher - add more pageSize, add sort, filter, close, detail
- `Bugfix` - 3479 Explorer - Change the new layer, but the map information of the old layer is displayed
- `Bugfix` - 3581 Import - Exception on special cell (Ex: contains formula)

## Changelog v1.4.10-4.0.4 [2022-06-13 06:20 AM]

- `New`- Show attachment
- `Bugfix` - 3563 Worker Manager - Fix searchKey not working
- `Improve` Display title and subtitle of tenant config on Map page
- `New` Map layer Switcher - Download Table/Flower detail grid as excel file
- `Change` Map layer Switcher - Hide toast on empty data
- `Bugfix` - 3536 Data Editor - import grid not change when switching layer

## Changelog v1.4.9-4.0.4 [2022-06-09 01:30 PM]

- `New` - API - Proxy tracking service from DCMS1
- `New` - Add What's here feature
- `Bugfix` - 3417 Import - Upload file throw exception
- `Bugfix` - 3373 Explorer - Do not show a marker when clicking on the data in grid table
- `Bugfix` - 3474 Worker Management - Filter on team id condition with no results
- `Bugfix` - 3533 Import - The uploaded file is not displayed at the top of the list of imported files
- `Bugfix` - 3501 Map layer - Click to view metadata information the error
- `Bugfix` - 3521 Data Editor - Clear filter but result grid list doesn't reload
- `Bugfix` - 3537 Tracking history - Press x to hide panel tracking but return to the homepage
- `Bugfix` - 3089 Toast message when no GPS from browser
- `Bugfix` - 3377 Worker Tracking - The pop-up show incorrect color and status when clicking the marker working

## Changelog v1.4.8-4.0.3 [2022-06-06 05:40 PM]

- `Bugfix` - 3367 Layer Manager - reload layer name after editing
- `Bugfix` - 3483 Explorer Cannot uncheck option Search in selected geometry

## Changelog v1.4.7-4.0.3 [2022-06-06 03:30 PM]

- `Bugfix` - 3480 Explorer - Filter by property not working
- `Bugfix` - 3334 Data Editor - Missing default values in fields set in layer
- `Bugfix` - 3318 Data Editor - Allow input and create success when input is smaller or larger than min, max
- `Bugfix` - 3392 Layer Manager - Edit other fields but the default value of the date time property is lost
- `Bugfix` - 3374 Worker Tracking - Marker is deviated from popup when GPS is pressed
- `Bugfix` - 3479 Explorer - Map was not render on layer change

## Changelog v1.4.6-4.0.3 [2022-06-06 02:15 AM]

- `Bugfix `- 3473 Tracking History - Doesn't draw route when viewing worker's tracking history
- `Bugfix` - 3454 Data Editor - The downloaded file cannot be opened
- `Bugfix` - 3475 Worker Management - No horizontal scrollbar, paging on grid
- `Bugfix` - 3466 Worker Management - Cannot create account

*Show more
June 16
proj-ndms2
Duy Thành
11:41 PM
Jump
@Ngọc Đẩy giúp anh Metting note End Sprint 6 với
@Bu Mập Anh xin bảo changelog - done của với ạ
Team Test sẽ review chức năng và bugfixAnh đề xuất https://ndms2.sovereignsolutions.app sẽ quét lỗi trong Sprint 6
Sau khi lỗi HIGH hết => Team test sẽ quét chức năng chính Staging Server - anh xin tenant Staging nhaSkedulomatic
Field Force, Schedule, Tracking, Delivery
June 16
proj-ndms2
Bu Mập
5:24 PM* 

*Jump*

## Version summary:

Last updated: 2022-06-16 02:30 PM
Server: https://ndms2.sovereignsolutions.app
Version: `v1.4.14-4.0.8`

## Changelog [2022-06-16 02:30 PM]

- `v1.4.14` New View editor history
- `v1.4.14` `Bugfix` - 3518 Data Editor-Import - import gives error field map
- `v1.4.14` `Bugfix` - 3557 Data Editor - Import - the status of the Import is still in Vietnamese
- `v1.4.14` `Bugfix` - 3597 Map layer - Interface error when hide maplayer
- `v1.4.14` `Bugfix` - 3560 ROUTE PLANNING - Showing inappropriate route
- `v1.4.14` `Bugfix` - 3568 Layer manager - Default value and regex are not bound together in edit
- `v1.4.14` `Bugfix` - 3582 Data Editor - Import - Import does not contain the min max condition of the field

*Skedulomatic*
*Field Force, Schedule, Tracking, Delivery*
*June 16*
*proj-ndms2*
*Bu Mập*
*6:14 AM*
*Jump*

## Version summary:

*Last updated: 2022-06-16 06:00*
Server: https://ndms2.sovereignsolutions.app
Version: v1.4.13-4.0.7*

## Changelog [2022-06-16 06:00]

`v1.4.13` New Table/Flower Detail - Sort/Filter/Close/Detail in detail table/flower
`v1.4.13` `Bugfix` - 3535 Import - If the file import that column has no title, the column order will be displayed
`v1.4.13` `Bugfix` - What's here - Add postal code
`v1.4.13` `Bugfix` - 3561 Map layer - Add more pageSize options on Flower/Table detail grid
`v1.4.13` `Bugfix` - Flower Detail - Markers was changed randomly on selecting

*Skedulomatic
Field Force, Schedule, Tracking, Delivery
June 15
proj-ndms2
Bu Mập
10:09 AM
Jump*

## Version summary:

*Last updated: 2022-06-15 10:00*
Server: https://ndms2.sovereignsolutions.app
Version: v1.4.12-4.0.6

## Changelog [2022-06-15 10:00]

`v1.4.12` New Layer Manager - Allow to create Map layer in Data Layer Menu
`v1.4.12` New Layer Manager - Add new data type to layer property (Map)
`v1.4.12` `Bugfix` Worker Management - Fix cannot change page

*Skedulomatic
Field Force, Schedule, Tracking, Delivery
June 14
proj-ndms2
Pinned
Bu Mập
4:11 PM
Jump*

## Version summary:

*Last updated: 2022-06-14 15:50*
Server: https://ndms2.sovereignsolutions.app
Version: v1.4.11-4.0.5

## Changelog [2022-06-14 15:50]

- `v1.4.11` `Bugfix` - 3585 Worker management - There is no change when clicking to switch pages
- `v1.4.11` New Add Data Manager page for AppData layers (TEAM, ORGANIZATION, ORGANIZATION TYPE, EMPLOYEE TYPE, DEVICE STATUS)
- `v1.4.11` `Bugfix` - 3559 Explorer - Double click the object on the grid whiten the page (for Polygon)
- `v1.4.11` `Bugfix` - 3570 Explorer - Map layer switcher - use DisplayName instead of ColumnName
- `v1.4.11` `Bugfix` - 3561 MapLayer Switcher - add more pageSize, add sort, filter, close, detail
- `v1.4.11` `Bugfix` - 3479 Explorer - Change the new layer, but the map information of the old layer is displayed
- `v1.4.11` `Bugfix` - 3581 Import - Exception on special cell (Ex: contains formula)

## Changelog [2022-06-13 06:20]

- `v1.4.10` New - Show attachment
- `v1.4.10` `Bugfix` - 3563 Worker Manager - Fix searchKey not working
- `v1.4.10` Display title and subtitle of tenant config on Map page
- `v1.4.10` New Map layer Switcher - Download Table/Flower detail grid as excel file
- `v1.4.10` Change Map layer Switcher - Hide toast on empty data
- `v1.4.10` `Bugfix` - 3536 Data Editor - import grid not change when switching layer

*Show more
Skedulomatic
Field Force, Schedule, Tracking, Delivery*

*June 09
proj-ndms2
Pinned
Bu Mập
1:32 PM
Jump

## Version summary:

*Last updated: 13:30 2022-06-09*

## Changelog [2022-06-09 13:30]

`v1.4.9` `New` - API - Proxy tracking service from DCMS1
`v1.4.9` `New` - Add What's here feature
`v1.4.9` `Bugfix` - 3417 Import - Upload file throw exception
`v1.4.9` `Bugfix` - 3373 Explorer - Do not show a marker when clicking on the data in grid table
`v1.4.9` `Bugfix` - 3474 Worker Management - Filter on team id condition with no results
`v1.4.9` `Bugfix` - 3533 Import - The uploaded file is not displayed at the top of the list of imported files
`v1.4.9` `Bugfix` - 3501 Map layer - Click to view metadata information the error
`v1.4.9` `Bugfix` - 3521 Data Editor - Clear filter but result grid list doesn't reload
`v1.4.9` `Bugfix` - 3537 Tracking history - Press x to hide panel tracking but return to the homepage
`v1.4.9` `Bugfix` - 3089 Toast message when no GPS from browser
`v1.4.9` `Bugfix` - 3377 Worker Tracking - The pop-up show incorrect color and status when clicking the marker working

## Changelog [2022-06-06 17:40]

- `v1.4.8` `Bugfix` - 3367 Layer Manager - reload layer name after editing
- `v1.4.8` `Bugfix` - 3483 Explorer Cannot uncheck option Search in selected geometry

## Changelog [2022-06-06 15:30]

- `v1.4.7` `Bugfix` - 3480 Explorer - Filter by property not working
- `v1.4.7` `Bugfix` - 3334 Data Editor - Missing default values in fields set in layer
- `v1.4.7` `Bugfix` - 3318 Data Editor - Allow input and create success when input is smaller or larger than min, max
- `v1.4.7` `Bugfix` - 3392 Layer Manager - Edit other fields but the default value of the date time property is lost
- `v1.4.7` `Bugfix` - 3374 Worker Tracking - Marker is deviated from popup when GPS is pressed
- `v1.4.7` `Bugfix` - 3479 Explorer - Map was not render on layer change

## Changelog [2022-06-06 02:15]

- `v1.4.6` `Bugfix` - 3473 Tracking History - Doesn't draw route when viewing worker's tracking history

- `v1.4.6` `Bugfix` - 3454 Data Editor - The downloaded file cannot be opened
- `v1.4.6` `Bugfix`- 3475 Worker Management - No horizontal scrollbar, paging on grid
- `v1.4.6` `Bugfix` - 3466 Worker Management - Cannot create account

*Show more
June 06
proj-ndms2
Pinned
Bu Mập
8:44 AM
Jump
Dear anh @Duy Thành, @Nguyễn Quốc Hưng*

## Version summary:

*Last updated: 02:19 AM 2022-06-06*
Server: https://ndms2.sovereignsolutions.app

## Changelog [2022-06-06]

`v1.4.6` `Bugfix` - 3473 Tracking History - Doesn't draw route when viewing worker's tracking history
`v1.4.6` `Bugfix` - 3454 Data Editor - The downloaded file cannot be opened
`v1.4.6` `Bugfix` - 3475 Worker Management - No horizontal scrollbar, paging on grid
`v1.4.6` `Bugfix` - 3466 Worker Management - Cannot create account
`v1.4.6` `Bugfix` - 3377 Worker Tracking - The pop-up show incorrect color and status when clicking the marker working
Skedulomatic
Field Force, Schedule, Tracking, Delivery

*April 07
proj-ndms2
Bu Mập
5:45 PM
Jump*

## Changelog v1.3.0 (Sprint 3)

*Release date: 06/04/2022*

#### Features

- New View mapnik vectortile on map
- New Share layer map render from another VDMS system (including VDMS Service, Mapnik Service)
- Render on Map
- Click to view detail
- New Search single layer by layer properties
- Display the result as grid and map
- Download the data as excel
- Interactive with data (select on map and show the detail)
- New Dashboard feature
- New Report feature
- New View attachments of a record (Mobile Support)
- View the detail of the data (view the detail properties,...)
- View the documents belong to this data
  - Pdf
  - Image
  - Video
  - Other files (Excel, Word, Zip,..)
- New Dark Theme Support

*March 17
proj-ndms2
Bu Mập
4:27 PM
Jump*

## Changelog v1.1.0 (Sprint 2)

## Version summary

*Last updated: 16:15 PM 2022-03-17*

Server https://ndms2.sovereignsolutions.app v1.1.0

### Feature

- WEB MOBILE List of maps on current system
- WEB MOBILE Map layer switcher
- Toggle system layers, RTO layers, Flower style layers on map
- View detail of marker on map
- Metadata by layer's properties

### Relative layer dataVersion summary:

*Last updated: 2022-06-24 02:25 PM*

Production Server https://demo.ndms2.skedulomatic.com: `v1.4.16-4.0.9 v1.4.16.1-4.0.9`
Staging-Dev Server https://ndms2.sovereignsolutions.app: `v1.4.16-4.0.9 v1.4.17-4.0.9`
Dev Server https://demo.ndms2.gisx.vn: `v2.0.1-5.0.0`

## Changelog v1.4.17-4.0.9 [2022-06-24 02:00 PM]

- `v1.4.17` `Upgrade` Improve dynamic filter to reuse in Explorer, Data Editor, User Management (Worker Management)
- `v1.4.17` `Upgrade` Improve data history feature
- `New` UI style
- `Move` Restore button to history detail panel
- `v1.4.17` `Upgrade` Change User Management (Worker Management) to use the same component with Data Editor
- `v1.4.17` `New` Explorer - Allow to remove selected layer
- `v1.4.17` `Bugfix` Map layer - Fix wrong position of selected marker

- ------------
`v1.4.16.1` `Bugfix` translate Vietnamese to English

- Routing Search
- Data History
- Create Map layer in Layer Manager
- Flower/Table Search Box

*Show more*

*Wednesday
proj-ndms2
Bu Mập
5:17 PM
Jump*

## Version summary:

*Last updated: 2022-06-22 05:00 PM*

Production Server https://demo.ndms2.skedulomatic.com: `v1.4.14-4.0.8` `v1.4.16-4.0.9`
Staging-Dev Server https://ndms2.sovereignsolutions.app: `v1.4.14-4.0.8` `v1.4.16-4.0.9`
Dev Server https://demo.ndms2.gisx.vn: `v2.0.1-5.0.0`

## Changelog v1.4.16-4.0.9 [2022-06-22 05:00 PM]

- `Improve` Mobile Web - Support mobile view for About feature, Change password feature
- `Bugfix` Mobile Web - Fix can only right click the first time
- `Bugfix` Layer manager - 3568 - Defaultvalue and regex are not bound together in edit
- `Bugfix` Explore - Fix free search was skipped on toggling filter off
- `Bugfix` Map Layer - Fix marker detail issue on administrative map layer
- `Bugfix` Map Layer - Fix exported file not apply the sorter for RTO
- `New` Data Editor - Add API to ge/upload attachment
- `Bugfix` Data Editor - Fix exporting excel file, support boolean value on search
- `Bugfix` Data Editor - Fix cannot create data with datetime datatype
- `Bugfix` Import - Skip geocoding if dont have enough config
- `New` Auto navigate to thematic map if only one map exists
- `Bugfix` Remove hard set theme

## Changelog v1.4.15-4.0.8 [2022-06-19 02:03 PM]

- `Change` Layer Manager - Move Add Property button to the left (overlapped with toast)
- `Change` Data Editor - Improve detail & attachment UI
- `Bugfix` View history - fix node history issue
- `Change` - Put pincode at the end of address string
- `Bugfix` Data Editor - Fix wrong filter on download as excel file
- `Bugfix` Call reload memory when modify layer with map type property

*Show more
June 17
proj-ndms2*
	
*Ngọc
9:32 AM
Jump*

### MEETING NOTE

**Meeting information:**
**Time:** 14:30 - 16/6/2022
**Place:** Event Room Floor 4
**Topic:** Start Sprint 6
**Members:** 
**Stack holder:** Ramesh
**PO**: Ngoc, Vinh
**Scrum Master**: Hang
**BA**: Phi
**Dev**: Hang, Phuoc, Phuc
**Tester:** Thanh, Hung, Hong
**Absent:** Hao Dat

#### END SPRINT 6

**Sprint Goal**

- Fix v1.4 bugs (30%)
- Basic Init Tenant
- Improve Map layer Switcher for Table and Flower mode
- Download detail
- UI actions: sort, filter, close,...
- Show number of record of map-layer in maplayer-swithcher
- View history of a record

#### Features

- Mantis bugs

- 47 issues solved
- 9 bugs wait to confims
- DEMONSTRATE
- LIVE DEMO
- DISCUSS
- [MAP] What here

- Pincode should be at the end of address string (LOW)

  [Attachment]

- Not show in data manager (MEDIUM)

  Others:

- Created layer map is not render by VDMS service (HIGH)

- Create new tenant (HIGH)

- Upload logo (MEDIUM)

- If have 1 map, go directly to the map & load the last view map (LOW)

- Vietnamese language @Ngọc work with @manjary to screenshot (export language file)

- VIETNAMESE

- NOT CORRECT/ MISPELLING LABEL/NAME IN ENGLISH

- Review the prod server

- Deploy new prd

- NDMS2_BASE tenant on prod

- Review all the service, API

- Review the scope of the next sprint

- discuss about the button to turn off other features' markers

- add Change map render to backlog

  *@Phạm Đức Tính will to take reponsility to control the render tool*

## RETROSPECTIVE

## Version Changelog v1.1.0 (Sprint 2)

 *Show more
June 17
proj-ndms2*

*Bu Mập
5:49 AM
Jump
Em gửi anh @Duy Thành*

## Version summary:

*Last updated: 2022-06-17 05:45 AM*

Production Server https://demo.ndms2.skedulomatic.com: `1.4.9-4.0.4 v1.4.14-4.0.8`
Staging-Dev Server https://ndms2.sovereignsolutions.app: `v1.4.14-4.0.8`
Dev Server https://demo.ndms2.gisx.vn: `v2.0.1-5.0.0`

## Changelog v1.4.14-4.0.8 [2022-06-16 02:30 PM]

- `New` View editor history

- `Bugfix` - 3518 Data Editor-Import - import gives error field map
- `Bugfix` - 3557 Data Editor - Import - the status of the Import is still in Vietnamese
- `Bugfix` - 3597 Map layer - Interface error when hide maplayer
- `Bugfix` - 3560 ROUTE PLANNING - Showing inappropriate route
- `Bugfix` - 3568 Layer manager - Default value and regex are not bound together in edit
- `Bugfix` - 3582 Data Editor - Import - Import does not contain the min max condition of the field

## Changelog v1.4.13-4.0.7 [2022-06-16 06:00 AM]

- `New` Table/Flower Detail - Sort/Filter/Close/Detail in detail table/flower
- `Bugfix` - 3535 Import - If the file import that column has no title, the column order will be displayed
- `Bugfix` - What's here - Add postal code
- `Bugfix` - 3561 Map layer - Add more pageSize options on Flower/Table detail grid
- `Bugfix `- Flower Detail - Markers was changed randomly on selecting

## Changelog v1.4.12-4.0.6 [2022-06-15 10:00 AM]

- New Layer Manager - Allow to create Map layer in Data Layer Menu

- New Layer Manager - Add new data type to layer property (Map)
- `Bugfix` Worker Management - Fix cannot change page

## Changelog v1.4.11-4.0.5 [2022-06-14 03:50 PM]

- `New` Add Data Manager page for AppData layers (TEAM, ORGANIZATION, ORGANIZATION TYPE, EMPLOYEE TYPE, DEVICE STATUS)

- `Bugfix` - 3559 Explorer - Double click the object on the grid whiten the page (for Polygon)
- `Bugfix` - 3570 Explorer - Map layer switcher - use DisplayName instead of ColumnName
- `Bugfix` - 3561 MapLayer Switcher - add more pageSize, add sort, filter, close, detail
- `Bugfix` - 3479 Explorer - Change the new layer, but the map information of the old layer is displayed
- `Bugfix` - 3581 Import - Exception on special cell (Ex: contains formula)

## Changelog v1.4.10-4.0.4 [2022-06-13 06:20 AM]

- `New`- Show attachment

- `Bugfix` - 3563 Worker Manager - Fix searchKey not working
- `Improve` Display title and subtitle of tenant config on Map page
- `New` Map layer Switcher - Download Table/Flower detail grid as excel file
- `Change` Map layer Switcher - Hide toast on empty data
- `Bugfix` - 3536 Data Editor - import grid not change when switching layer

## Changelog v1.4.9-4.0.4 [2022-06-09 01:30 PM]

- `New`- API - Proxy tracking service from DCMS1

- `New` - Add What's here feature
- `Bugfix` - 3417 Import - Upload file throw exception
- `Bugfix` - 3373 Explorer - Do not show a marker when clicking on the data in grid table
- `Bugfix` - 3474 Worker Management - Filter on team id condition with no results
- `Bugfix` - 3533 Import - The uploaded file is not displayed at the top of the list of imported files
- `Bugfix` - 3501 Map layer - Click to view metadata information the error
- `Bugfix` - 3521 Data Editor - Clear filter but result grid list doesn't reload
- `Bugfix` - 3537 Tracking history - Press x to hide panel tracking but return to the homepage
- `Bugfix` - 3089 Toast message when no GPS from browser
- `Bugfix` - 3377 Worker Tracking - The pop-up show incorrect color and status when clicking the marker working

## Changelog v1.4.8-4.0.3 [2022-06-06 05:40 PM]

- `Bugfix` - 3367 Layer Manager - reload layer name after editing
- `Bugfix` - 3483 Explorer Cannot uncheck option Search in selected geometry

## Changelog v1.4.7-4.0.3 [2022-06-06 03:30 PM]

- `Bugfix` - 3480 Explorer - Filter by property not working
- `Bugfix` - 3334 Data Editor - Missing default values in fields set in layer
- `Bugfix` - 3318 Data Editor - Allow input and create success when input is smaller or larger than min, max
- `Bugfix` - 3392 Layer Manager - Edit other fields but the default value of the date time property is lost
- `Bugfix` - 3374 Worker Tracking - Marker is deviated from popup when GPS is pressed
- `Bugfix` - 3479 Explorer - Map was not render on layer change

## Changelog v1.4.6-4.0.3 [2022-06-06 02:15 AM]

- `Bugfix` - 3473 Tracking History - Doesn't draw route when viewing worker's tracking history
- `Bugfix` - 3454 Data Editor - The downloaded file cannot be opened
- `Bugfix` - 3475 Worker Management - No horizontal scrollbar, paging on grid
- `Bugfix` - 3466 Worker Management - Cannot create account

*Show more
June 16
proj-ndms	
Duy Thành
11:41 PM
Jump*

*@Ngọc Đẩy giúp anh Metting note End Sprint 6 với
@Bu Mập Anh xin bảo changelog - done của với ạ
Team Test sẽ review chức năng và bugfix*

*Anh đề xuất https://ndms2.sovereignsolutions.app sẽ quét lỗi trong Sprint 6
Sau khi lỗi HIGH hết => Team test sẽ quét chức năng chính Staging Server - anh xin tenant Staging nha
Skedulomatic
Field Force, Schedule, Tracking, Delivery
June 16
proj-ndms2*
	
*Bu Mập
5:24 PM
Jump*

## Version summary:

*Last updated: 2022-06-16 02:30 PM*
Server: https://ndms2.sovereignsolutions.app
Version: `v1.4.14-4.0.8`

## Changelog [2022-06-16 02:30 PM]

- `v1.4.14` `New` View editor history
- `v1.4.14` `Bugfix` - 3518 Data Editor-Import - import gives error field map
- `v1.4.14` `Bugfix` - 3557 Data Editor - Import - the status of the Import is still in Vietnamese
- `v1.4.14` `Bugfix` - 3597 Map layer - Interface error when hide maplayer
- `v1.4.14` `Bugfix` - 3560 ROUTE PLANNING - Showing inappropriate route
- `v1.4.14` `Bugfix` - 3568 Layer manager - Default value and regex are not bound together in edit
- `v1.4.14` `Bugfix` - 3582 Data Editor - Import - Import does not contain the min max condition of the field

*Skedulomatic
Field Force, Schedule, Tracking, Delivery
June 16
proj-ndms2
Bu Mập
6:14 AM
Jump*

## Version summary:

*Last updated: 2022-06-16 06:00*
Server: https://ndms2.sovereignsolutions.app
Version: `v1.4.13-4.0.7`

## Changelog [2022-06-16 06:00]

- `v1.4.13` `New` Table/Flower Detail - Sort/Filter/Close/Detail in detail table/flower
- `v1.4.13` `Bugfix` - 3535 Import - If the file import that column has no title, the column order will be displayed
- `v1.4.13` `Bugfix` - What's here - Add postal code
- `v1.4.13` `Bugfix` - 3561 Map layer - Add more pageSize options on Flower/Table detail grid
- `v1.4.13` `Bugfix` - Flower Detail - Markers was changed randomly on selecting

*Skedulomatic
Field Force, Schedule, Tracking, Delivery
June 15
proj-ndms2	
Bu Mập
10:09 AM
Jump*

## Version summary:

*Last updated: 2022-06-15 10:00*
Server: https://ndms2.sovereignsolutions.app
Version: `v1.4.12-4.0.6`

## Changelog [2022-06-15 10:00]

- `v1.4.12` `New` Layer Manager - Allow to create Map layer in Data Layer Menu
- `v1.4.12` `New` Layer Manager - Add new data type to layer property (Map)
- `v1.4.12` `Bugfix` Worker Management - Fix cannot change page

*Skedulomatic
Field Force, Schedule, Tracking, Delivery
June 14
proj-ndms2
Pinned
Bu Mập
4:11 PM
Jump*

## Version summary:

*Last updated: 2022-06-14 15:50*
Server: https://ndms2.sovereignsolutions.app
Version: v1.4.11-4.0.5

## Changelog [2022-06-14 15:50]

- `v1.4.1``Bugfix`- 3585 Worker management - There is no change when clicking to switch pages
  `v1.4.11` New Add Data Manager page for AppData layers (TEAM, ORGANIZATION, ORGANIZATION TYPE, EMPLOYEE TYPE, DEVICE STATUS)
  `v1.4.11` `Bugfix` - 3559 Explorer - Double click the object on the grid whiten the page (for Polygon)
  `v1.4.11` `Bugfix` - 3570 Explorer - Map layer switcher - use DisplayName instead of ColumnName
  `v1.4.11` `Bugfix` - 3561 MapLayer Switcher - add more pageSize, add sort, filter, close, detail
  `v1.4.11` `Bugfix` - 3479 Explorer - Change the new layer, but the map information of the old layer is displayed
  `v1.4.11` `Bugfix` - 3581 Import - Exception on special cell (Ex: contains formula)

- - --------------------
## Changelog [2022-06-13 06:20]


- `v1.4.10` `New` - Show attachment
- `v1.4.10` `Bugfix` - 3563 Worker Manager - Fix searchKey not working
- `v1.4.10` `Display` title and subtitle of tenant config on Map page
- `v1.4.10` `New` Map layer Switcher - Download Table/Flower detail grid as excel file
- `v1.4.10` `Change` Map layer Switcher - Hide toast on empty data
- `v1.4.10` `Bugfix` - 3536 Data Editor - import grid not change when switching layer
- Show more
- Skedulomatic
- Field Force, Schedule, Tracking, Delivery

*June 09
proj-ndms2
Pinned	
Bu Mập
1:32 PM
Jump
Version summary:
Last updated: 13:30 2022-06-09*

## Changelog [2022-06-09 13:30]

- `v1.4.9` `New` - API - Proxy tracking service from DCMS1
- `v1.4.9` `New` - Add What's here feature
- `v1.4.9` `Bugfix` - 3417 Import - Upload file throw exception
- `v1.4.9` `Bugfix` - 3373 Explorer - Do not show a marker when clicking on the data in grid table
- `v1.4.9` `Bugfix` - 3474 Worker Management - Filter on team id condition with no results
- `v1.4.9` `Bugfix` - 3533 Import - The uploaded file is not displayed at the top of the list of imported files
- `v1.4.9` `Bugfix` - 3501 Map layer - Click to view metadata information the error
- `v1.4.9` `Bugfix` - 3521 Data Editor - Clear filter but result grid list doesn't reload
- `v1.4.9` `Bugfix` - 3537 Tracking history - Press x to hide panel tracking but return to the homepage
- `v1.4.9` `Bugfix` - 3089 Toast message when no GPS from browser
- `v1.4.9` `Bugfix` - 3377 Worker Tracking - The pop-up show incorrect color and status when clicking the marker working

## Changelog [2022-06-06 17:40]

- `v1.4.8` `Bugfix` - 3367 Layer Manager - reload layer name after editing

- `v1.4.8` `Bugfix` - 3483 Explorer Cannot uncheck option Search in selected geometry

## Changelog [2022-06-06 15:30]

- `v1.4.7` `Bugfix` - 3480 Explorer - Filter by property not working

- `v1.4.7` `Bugfix` - 3334 Data Editor - Missing default values in fields set in layer

- `v1.4.7` `Bugfix` - 3318 Data Editor - Allow input and create success when input is smaller or larger than min, max

- `v1.4.7` `Bugfix` - 3392 Layer Manager - Edit other fields but the default value of the date time property is lost

- `v1.4.7` `Bugfix` - 3374 Worker Tracking - Marker is deviated from popup when GPS is pressed

- `v1.4.7` `Bugfix` - 3479 Explorer - Map was not render on layer change

## Changelog [2022-06-06 02:15]

- `v1.4.6` `Bugfix` - 3473 Tracking History - Doesn't draw route when viewing worker's tracking history
- `v1.4.6` `Bugfix` - 3454 Data Editor - The downloaded file cannot be opened
- `v1.4.6` `Bugfix` - 3475 Worker Management - No horizontal scrollbar, paging on grid
- `v1.4.6` `Bugfix` - 3466 Worker Management - Cannot create account
- Show more
- June 06
- proj-ndms2
- Pinned

*Bu Mập*
*8:44 AM*
*Jump*
*Dear anh @Duy Thành, @Nguyễn Quốc Hưng*

## Version summary:

*Last updated: 02:19 AM 2022-06-06*
Server: https://ndms2.sovereignsolutions.app

## Changelog [2022-06-06]

- `v1.4.6` `Bugfix` - 3473 Tracking History - Doesn't draw route when viewing worker's tracking history
- `v1.4.6` `Bugfix` - 3454 Data Editor - The downloaded file cannot be opened
- `v1.4.6` `Bugfix` - 3475 Worker Management - No horizontal scrollbar, paging on grid
- `v1.4.6` `Bugfix` - 3466 Worker Management - Cannot create account
- `v1.4.6` `Bugfix` - 3377 Worker Tracking - The pop-up show incorrect color and status when clicking the marker working

*Skedulomatic
Field Force, Schedule, Tracking, Delivery*

*April 07
proj-ndms2*
*Bu Mập
5:45 PM
Jump

## Changelog v1.3.0 (Sprint 3)

*Release date: 06/04/2022*

#### Features

- New View mapnik vectortile on map
- New Share layer map render from another VDMS system (including VDMS Service, Mapnik Service)
- Render on Map
- Click to view detail
- `New` Search single layer by layer properties
  - Display the result as grid and map
- Download the data as exce
- Interactive with data (select on map and show the detail)
- New Dashboard feature
- New Report feature
- `New` View attachments of a record (Mobile Support)

   - View the detail of the data (view the detail properties,...)
   - View the documents belong to this data
   - Pdf
   - Image
   - Video
   - Other files (Excel, Word, Zip,..)
- New Dark Theme Support

*March 17
proj-ndms2*
*Bu Mập*
*4:27 PM*
*Jump*

## Changelog v1.1.0 (Sprint 2)

#### Version summary

*Last updated: 16:15 PM 2022-03-17*
Server https://ndms2.sovereignsolutions.app `v1.1.0`

#### Feature

- WEB MOBILE List of maps on current system
- WEB MOBILE Map layer switcher
- Toggle system layers, RTO layers, Flower style layers on map
- View detail of marker on map
- Metadata by layer's properties
- Relative layer data
- Metadata only as grid view)
- Relative layer data (markers on map)
- WEB Search location feature
- WEB Routing feature

*Skedulomatic*
*Field Force, Schedule, Tracking, Delivery*
*Metadata only as grid view)*
*Relative layer data (markers on map)*
*WEB Search location feature*
*WEB Routing feature*
*Skedulomatic*
*Field Force, Schedule, Tracking, Delivery*
