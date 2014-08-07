蓝牙串口设置脚本
======

绑定指定的蓝牙SPP(Serial Port Profile)设备的串口到设备/dev/rfcomm上.

用法:
	blueSPP 设备名称

使用中会申请root权限, 在 Bluez5.8 上测试通过


blueSPP_script
==============

Script for binding Bluetooth Serial Port Profile device by name to /dev/rfcomm 

Usage:

	blueSPP dev_name

Will ask for root permission.

Test passed on Bluez5.8.
