Privacy Policy

Pocket Chrono uses your device's microphone and accelerometer solely to measure projectile velocity. 
No data is stored, shared, or transmitted off your device. No personal information is collected.

--------------------------------------------------------------------------------------------------------

v0.1.0 – Initial Closed Test
Welcome to the first closed test of Pocket Chrono — an app that measures the muzzle velocity of 
projectiles (airsoft BBs, pellets, and similar) using your phone's built-in accelerometer and microphone.
How it works:
The app detects the muzzle blast via the audio sensor and the physical impulse via the accelerometer, 
then calculates the time difference between the two events to derive projectile velocity. No external 
hardware needed.

Tap Test — Please run this first
Before doing any live shooting tests, please perform the Tap Test. This verifies that the accelerometer 
and microphone are running on the same time base — which is critical for accurate measurements.
To run it: tap the phone firmly while the app is in measurement mode. Both sensors should trigger 
near-simultaneously. The recorded time difference between the accelerometer event and the audio event 
should be a matter of a few milliseconds at most — if you see a difference in the hundreds or thousands 
of milliseconds, something is off and we need to know about it. Please report your result either way, 
including your device model. This is a known potential issue across different Android devices and 
manufacturers, and your data helps us understand how consistent sensor timing is across hardware.
Also useful to know is that we have forced upsampling the audio sampling rate from the native 
sampling rate to the next step so in most cases 48000 -> 64000. This seems to minimize hardware quirks.

What to test:

Tap Test (required for all testers)
Live velocity measurement with a pellet gun, airsoft gun, or similar
General app stability, UI clarity, and any crashes

Ideal tester setup:
You don't need anything specific, but if you have access to any kind of pellet gun, airsoft gun, or BB gun — 
regardless of power level — please use it for a live test. Even a low-powered spring pistol is useful. 
The more variety in guns and power levels we get data from, the better.

Known limitations:

Accuracy depends on sensor timing consistency, which varies by device
Works best in a quiet environment with minimal background noise


Useful Information:

Your device model and Android version
Tap Test result (time difference shown)
Any crashes, freezes, or unexpected behavior
Velocity readings if you did a live test (and what gun you used)
