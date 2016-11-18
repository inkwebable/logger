# logger
My first Python 3 venture, create named logs in a given directory, with a given name and write to them

## Usage ##

Create and fetch a Log
```logFile = log.get_log_file()```

Methods for writing to the log
``` Python
log.warning('Water needed!')
log.critical('Food needed!')
log.error('No energy')
log.debug('Missing resource')
log.info('Refueling')
```

Sample of output from code above;
```
18-11-16, 15:01:28, [WARNING], Water needed!
18-11-16, 15:01:28, [CRITICAL], Food needed!
18-11-16, 15:01:28, [ERROR], No energy
18-11-16, 15:01:28, [DEBUG], Missing resource
18-11-16, 15:01:28, [INFO], Refueling
```

Please see the example.py file for further usage.


***Please Note this project is W.I.P & is inteded for use with Python 3***