# Checking-Battery-Percentage-using-python     
psutil.sensors.battery() returns a named tuple consisting of following values.      
If no battery is installed or metrics can’t be determined None is returned.

percent: Power left in percentage.           
secsleft: Approx seconds left before the power runs out. It is set to psutil.     
POWER_TIME_UNLIMITED if it is on charging. If this value can’t be determined it is set to psutil.POWER_TIME_UNKNOWN .       
power_plugged: True if power is plugged in, False if it isn’t charging or None if it can’t be determined.
