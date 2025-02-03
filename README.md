# **Health Check – System Monitoring Script**

This is a simple Python script that monitors **disk space** and **CPU usage** to ensure system stability. If either resource is under stress, it alerts the user.

## **Features**
- Checks if free disk space is above **20%**  
- Checks if CPU usage is below **75%**  
- Prints `"All Good"` if both conditions are met  
- Prints `"ERROR"` if either condition fails  

## **Requirements**
This script uses Python’s `shutil` and `psutil` libraries. Install `psutil` if needed:

```bash
pip install psutil
```

## **Usage**
Run the script in a terminal:

```bash
python3 health_check.py
```

## **Next Steps**
This script can be expanded to include:
- **RAM monitoring**
- **Logging for historical data**
- **Automated alerts for critical failures**
