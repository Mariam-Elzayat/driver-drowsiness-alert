# Driver Drowsiness Alert

## Overview
We plan to build a standalone educational device that uses a camera and computer vision to monitor a driver's eyes. The aim is to provide visual and audible warnings when the eyes remain closed for a sustained period.

## Project Idea
The camera will capture the face and eye region. The software will estimate whether the eyes are open or closed and track the duration of eye closure. The device will use this information to select an alert level.

## Planned Features
- Camera-based eye monitoring.
- Eye-closure detection using computer vision.
- Measurement of continuous eye-closure duration.
- Green light for the normal state.
- Yellow light for an initial warning.
- Red light and an audible alarm for a higher alert level.
- Standalone operation without a laptop in the final demonstration.

## Planned Components
The component list is preliminary and may change.
- Raspberry Pi 5 (4 GB) as the main processing unit.
- USB camera to capture the driver's face.
- 3 LEDs (green, yellow, red) with LED holders and suitable resistors.
- Active buzzer (5V) for the audible alarm.
- Raspberry Pi 5 power supply, microSD card, and cooling fan.
- Perfboard and wiring for connections.
- Custom enclosure for the final device.

## Current Progress
The project is in the planning and design stage. No implementation code has been uploaded yet. Component selection and implementation details are still being developed. Alert thresholds will be defined and tested during implementation.

## Next Steps
1. Finalize the hardware and software choices.
2. Develop and test the eye-closure detection software.
3. Integrate the camera, indicator lights, and buzzer.
4. Assemble the device in its enclosure.
5. Test the complete device and document the results and limitations.

## Safety and Limitations
This is a student demonstration project, not a certified vehicle safety device. It cannot guarantee that drowsiness will be detected and must not be relied on for safe driving. Testing should take place in a controlled environment, not while driving on public roads.
