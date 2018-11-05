Virtual Machine Used : Cloudera-Training-VM-4.2.1.p-vmware_CAPStudent.part01

Files and Directories Used in this Exercise -

Eclipse project: partitioner

Java files:
MonthPartitioner.java (Partitioner)
ProcessLogs.java(driver)
CountReducer.java(Reducer)
LogMonthMapper.java(Mapper)Test data (HDFS):

Java File Location - src/stubs

Test data (HDFS):
weblog(full web server access log)
testlog (partial data set for testing)

Exercise directory: ~/workspace/partitioner

Compiling - The compilation was done in Eclipse by converting the entire file into a jar file.
Running - hadoop jar part.jar stubs.ProcessLogs /user/training/access part16

