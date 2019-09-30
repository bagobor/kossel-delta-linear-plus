Connecting to: /dev/ttyUSB0
Using Malyan/Monoprice Connection Fix Plugin to create serial connection
Changing monitoring state from "Offline" to "Opening serial port"
Connected to: Serial<id=0x6c2c9050, open=True>(port='/dev/ttyUSB0', baudrate=115200, bytesize=8, parity='N', stopbits=1, timeout=10.0, xonxoff=False, rtscts=False, dsrdtr=False), starting monitor
Changing monitoring state from "Opening serial port" to "Connecting"
Send: N0 M110 N0*125
Recv: start
Send: N0 M110 N0*125
Recv: echo:Marlin 1.1.0
Recv: 
Recv: echo: Last Updated: 2016-12-06 12:00 | Author: (ANYCUBIC PLUS, 2017/9/18)
Recv: Compiled: Oct 13 2017
Recv: echo: Free Memory: 3329  PlannerBufferBytes: 1168
Recv: echo:V29 stored settings retrieved (669 bytes)
Recv: echo:Steps per unit:
Recv: echo:  M92 X80.00 Y80.00 Z80.00 E96.00
Recv: echo:Maximum feedrates (mm/s):
Recv: echo:  M203 X200.00 Y200.00 Z200.00 E200.00
Recv: echo:Maximum Acceleration (mm/s2):
Recv: echo:  M201 X3000 Y3000 Z3000 E3000
Recv: echo:Accelerations: P=printing, R=retract and T=travel
Recv: echo:  M204 P3000.00 R3000.00 T1500.00
Recv: echo:Advanced variables: S=Min feedrate (mm/s), T=Min travel feedrate (mm/s), B=minimum segment time (ms), X=maximum XY jerk (mm/s),  Z=maximum Z jerk (mm/s),  E=maximum E jerk (mm/s)
Recv: echo:  M205 S0.00 T0.00 B20000 X5.00 Y5.00 Z5.00 E5.00
Recv: echo:Home offset (mm)
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: Auto Bed Leveling:
Recv: echo:  M420 S0
Recv: echo:Endstop adjustment (mm):
Recv: echo:  M666 X0.00 Y0.00 Z0.00
Recv: echo:Delta settings: L=diagonal_rod, R=radius, S=segments_per_second, ABC=diagonal_rod_trim_tower_[123]
Recv: echo:  M665 L271.50 R135.40 S80.00 A0.00 B0.00 C0.00
Recv: echo:Material heatup parameters:
Recv: echo:  M145 S0 H180 B70 F0
Recv:   M145 S1 H240 B110 F0
Recv: echo:PID settings:
Recv: echo:  M301 P22.20 I1.08 D114.00
Recv: echo:Filament settings: Disabled
Recv: echo:  M200 D3.00
Recv: echo:  M200 D0
Recv: echo:Z-Probe Offset (mm):
Recv: echo:  M851 Z-15.80
Recv: echo:SD card ok
Recv: ok
Changing monitoring state from "Connecting" to "Operational"
Send: N0 M110 N0*125
Recv: echo:SD card ok
Recv: ok
Send: N1 M115*39
Recv: FIRMWARE_NAME:Marlin 1.1.0Anycubic SOURCE_CODE_URL: PROTOCOL_VERSION:1.0 MACHINE_TYPE:Anycubic EXTRUDER_COUNT:1 UUID:cede2a2f-41a2-4748-9b12-c55c62f367ff
Recv: ok
Send: M20
Recv: Begin file list
...
Recv: End file list


Send: M503
Recv: echo:Steps per unit:
Recv: echo:  M92 X80.00 Y80.00 Z80.00 E96.00
Recv: echo:Maximum feedrates (mm/s):
Recv: echo:  M203 X200.00 Y200.00 Z200.00 E200.00
Recv: echo:Maximum Acceleration (mm/s2):
Recv: echo:  M201 X3000 Y3000 Z3000 E3000
Recv: echo:Accelerations: P=printing, R=retract and T=travel
Recv: echo:  M204 P3000.00 R3000.00 T1500.00
Recv: echo:Advanced variables: S=Min feedrate (mm/s), T=Min travel feedrate (mm/s), B=minimum segment time (ms), X=maximum XY jerk (mm/s),  Z=maximum Z jerk (mm/s),  E=maximum E jerk (mm/s)
Recv: echo:  M205 S0.00 T0.00 B20000 X5.00 Y5.00 Z5.00 E5.00
Recv: echo:Home offset (mm)
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: Auto Bed Leveling:
Recv: echo:  M420 S0
Recv: echo:Endstop adjustment (mm):
Recv: echo:  M666 X0.00 Y0.00 Z0.00
Recv: echo:Delta settings: L=diagonal_rod, R=radius, S=segments_per_second, ABC=diagonal_rod_trim_tower_[123]
Recv: echo:  M665 L271.50 R135.40 S80.00 A0.00 B0.00 C0.00
Recv: echo:Material heatup parameters:
Recv: echo:  M145 S0 H180 B70 F0
Recv:   M145 S1 H240 B110 F0
Recv: echo:PID settings:
Recv: echo:  M301 P22.20 I1.08 D114.00
Recv: echo:Filament settings: Disabled
Recv: echo:  M200 D3.00
Recv: echo:  M200 D0
Recv: echo:Z-Probe Offset (mm):
Recv: echo:  M851 Z-15.80
Recv: ok
