Performance Test Assignment:

Tool used - Jmeter

Steps to execute:

* Install `Java` and then download `Apache Jmeter v5.5`
* Unzip apache-jmeter-5.5
* Copy `jmeter-plugins-manager-1.7.jar` and `jmeter-plugins-casutg-2.10.jar` to Jmeter directory `..\lib\ext`
* Change the CSV Data set config filepath in PerfTestAssignment.jmx.
* Open cmd prompt with root path till bin folder. Eg: C:\Users\<user name>\Downloads\apache-jmeter-5.5\apache-jmeter-5.5\bin>
* Run the command jmeter -n -t [.jmx file] -l [results .jtl file] -e -o [Path to web report folder]
* Test result report (index.html) will be generated under the web report folder.

Files uploaded on GitHub:

- jmx file (PerfTestAssignment.jmx)
- CSV file (author-data.csv)
- jmeter-plugins-manager-1.7.jar and jmeter-plugins-casutg-2.10.jar
- result .jtl file (jmeter.jtl)
- Test Result Report (index.html)
 
