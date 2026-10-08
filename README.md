# Rescue Desk (demo)

A demo of a private emergency hotline for hospitals, clinics and ambulance operators in Kenya. It shows how a call-taker can triage a call, find the caller with an SMS location link, and send the nearest free ambulance.

**This is a simulation.** No real calls or SMS are sent, the map is a drawing, and the caller's position is simulated.

Live demo: _add your GitHub Pages link here_

## What it shows

1. **Call-taker screen.** A short form (what happened, number of patients, awake and breathing) gives a suggested priority: Critical, Urgent or Standard.
2. **Caller's phone.** The caller gets an SMS link, taps it, and shares their location. They then see a live arrival time.
3. **Dispatch board.** The app skips busy ambulances, picks the nearest free one, moves it across the map and logs each step with a time.

## Built with

Plain HTML, CSS and JavaScript in a single file. No libraries and no server. Open `index.html` in a browser to run it.

## Next steps

- Save calls and dispatches in a Supabase database.
- Send the SMS and receive the caller's real GPS position through Africa's Talking.
- Add a real map, ambulance GPS tracking, and a trip log and billing view for operators.
- Add staff login and follow Kenya's Data Protection Act before storing any patient data.

## Note

Emergency software affects lives. This demo is for learning and portfolio use only and is not for real emergencies.
