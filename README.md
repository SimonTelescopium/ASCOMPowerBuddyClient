# ASCOMPowerBuddyClient
An Arduino based relay controller that is ASCOM compliant <p>

This is a Win32 ASCOM client application to control the PowerBuddy Arduino relay controller.
Because it is an ASCOM client it may be able to control other ASCOM switches, but it is only intended and tested to work with the <b>PowerBuddy By SimonTelescopium</b><p>
  
  <b>Limitations/Features:</b><p>
<ul>
  <li>Controls up to 8 relays/switches</li>
  <li>Only works with binary (on/off) switches (doesn't support switches that can return values)</li>
  <li>Recognises read only binary (on/off) sensors (doesn't support sensors that can return multiple values) </li>
  <li>Populates client with switch/relay names </li>
  <li>Displays current state of switch</li>
  <li>allows user to toggle on/off relays and read binary (on/off) sensors</li>
</ul>
