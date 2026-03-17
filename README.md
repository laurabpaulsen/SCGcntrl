# SCGcntrl
API for controlling stimulus current generators from DeMeTec

## Usage example
```python
from SCGcntrl import SCGConnector

# Connect to the SCG device on the specified serial port
connector = SCGConnector(port='/dev/ttyUSB0')

# Change the intensity to level 5
connector.change_intensity(5)

# Send a pulse command
connector.send_pulse()

```
