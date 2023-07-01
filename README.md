# Neptune V2

<img src="/.github/images/neptune_front.png" width="50%" /><img src="/.github/images/neptune_back.png" width="50%" />

Neptune is a flight computer designed for testing basic thrust vector control (TVC) systems. It contains connectors for two servo motors with optional feedback, SWD and USB interfaces, radio communication using an RFM95W LoRa module and a 9-axis IMU for determining the attitude of the vehicle.

Neptune V2 aims to solve several issues identified in the first iteration, as well as improve upon the overall design. The noteable changes include:
- Improved connectors
  - JST-GH connectors for the servo motors to improved security and ease of connection
- Indicator LEDs to display when the board has been powered on
- A more compact form factor
  - ~45% reduction in area
- A flash chip taking the place of an SD card connector
  - Improved reliability in high-vibration environments
- More suitable mounting holes
  - Clearance and strength issues were a problem in Neptune V1
- The addition of dedicated test points for easy debugging of basic issues
