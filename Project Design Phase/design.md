# Project Design Phase

## Flow Logic
- Trigger: Incident Record Created
- If Short Description contains wifi/internet -> Category = Network
- If contains projector/hardware -> Category = Hardware
- If contains password/login -> Category = Software
- Else -> Category = General
- Final Action: Send Email to Caller
