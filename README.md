# DateAndTimeDimensionBuilders
Date dimension and time dimension builders for data warehousing written in Python.

## Date Dimension Builder ([datedimensionbuilder.py](https://github.com/jpseverance/DateAndTimeDimensionBuilders/blob/master/datedimensionbuilder.py))
    $ python datedimensionbuilder.py --help
    usage: datedimensionbuilder.py [-h] [-f FILE] [-s DATE] [-e DATE] [-c]
    
    Build a Date Dimension for use in a Data Warehouse or Data Mart. The output
    will be written to stdout unless a CSV file is specified with the -f/--file
    option.

    optional arguments:
      -h, --help            show this help message and exit
      -f FILE, --file FILE  write output to a CSV file.
      -s DATE, --startdate DATE
                            starting date of the date dimension. Default is
                            1/1/1850.
      -e DATE, --enddate DATE
                            ending date for the date date dimesnion. Default is
                            12/31/2050.
      -c, --columnnamesonly
                            output column names only.

## Time Dimension Builder ([timedimensionbuilder.py](https://github.com/jpseverance/DateAndTimeDimensionBuilders/blob/master/timedimensionbuilder.py))

    $ python timedimensionbuilder.py --help
    usage: timedimensionbuilder.py [-h] [-f FILE]
    
    Build a Time Dimension for use in a Data Warehouse or Data Mart. 
    The output will be written to stdout unless a CSV file is specified with the -f/--file 
    option.
    
    optional arguments:
      -h, --help            show this help message and exit
      -f FILE, --file FILE  write output to a CSV file
