The initial setup script "load_data_lake.sh" assumes that the user has an AWS instance up and running with Hadoop installed. The shell script will start hadoop, download the necessary files from the Medicare website, make modifications to the files and move the base files into HDFS.