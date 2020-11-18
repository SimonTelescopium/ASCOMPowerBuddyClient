# ASCOMPowerBuddyClient
An Arduino based relay controller that is ASCOM compliant

This is a Win32 ASCOM client application to control the PowerBuddy Arduino relay controller.
Because it is an ASCOM client it may be able to control other ASCOM switches.
Limitations:
Controls up to 8 relays/switches
Only works with binary (on/off) switches (doesn't support switches that can return values)
Recognises read only binary (on/off) sensors (doesn't support sensors that can return multiple values) 
