## Vulnerabitily type
Replay attack (CVE-2022-41541)

## Vendor
TP-Link

## Product
AX10v1 V1_211117

## Affected component
The web app authentication method accepts a replayed HTTP packet which contains a login message that was previously got accepted by the app.

## Attack vector
A Man-in-the-middle attacker who captures the traffic between the web app and the victim, can escalate a Replay attack, with a previously transmitted encrypted authentication message and gain a valid authentication token. This will allow the attacker to login as an admin user to the application.

## Patch
V1_220401

## PoC


https://user-images.githubusercontent.com/43434138/192100078-5337d422-f054-4d9a-806c-5e2093fd950d.mp4

