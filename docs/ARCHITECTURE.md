# System Architecture

The attendance system is a computer-vision workflow for employee verification and attendance capture.

## Logical flow

1. Capture an image/frame.
2. Detect and encode the face.
3. Compare the representation with enrolled identities.
4. Record the attendance event and associated metadata.
5. Make the result available to the HR/attendance workflow.

The resume describes this project as supporting 200+ employees and capturing employee ID, timestamp, GPS, and verification image.
