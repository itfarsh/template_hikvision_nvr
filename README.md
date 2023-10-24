# Template Zabbix for NVRs (network video recorders) by Hikvision using HTTP.

## Brief information:
Zabbix template for monitoring cameras on Hikvision NVR and NVR status

##  Macros used
| Name | Description | Default |
|--|--|--|
| {$CPU.UTIL.CRIT} |  | 90 |
| {$HIKVISION_ISAPI_PORT} | ISAPI port on device | 80 |
| {$HIKVISION_ISAPI_PORT} |  | 95 |
| {$PASSWORD} | NVR user | admin |
| {$USER} | NVR password | admin |

## Information covered by a template:
 - Low Level Discovery
	 - LLD of cameras discovery
	 - LLD of hdd discovery
 - Items
	 - Camera "{#CAMERA_ID} - {#CAMERA_NAME}": Camera status
	 - NVR CPU utilization
	 - NVR Current device time
	 - NVR Device ID
	 - NVR Device name
	 - NVR Device type
	 - NVR Encoder released date
	 - NVR Encoder version
	 - NVR Firmware released date
	 - NVR Firmware version
	 - NVR Get cameras: Login status
	 - NVR Get device info: Login status
	 - NVR Get status hdd
	 - NVR Get system status
	 - NVR MACaddress
	 - NVR Memory available
	 - NVR Memory Usage
	 - NVR Model
	 - NVR Serial number
	 - NVR Telecontrol ID
	 - NVR Uptime
	 - NVR hdd discovery
 - Triggers
	 - NVR authorisation error
	 - NVR camera has been replaced
	 - NVR error receiving data
	 - NVR has been restarted
	 - NVR high CPU utilization
	 - NVR version has changed
	 - NVR host is down
	 - NVR disk is a problem
	 - Camera is not available

## Author
Alexander Lakhin
