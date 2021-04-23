# Installing Pyflink

[Video of installation process](https://app.vidgrid.com/view/1T3unjs9eFeb)

## Steps:

### Ensure python version

Run the following command:
```
$ python --version
```

**Important:** Your version of python must be above 3.5 for pyflink to work

### Install Pyspark

##### For Google Colab
Use:
```
!pip install apache-flink
```
then you can import the package with: 
```python
import pyflink
```

##### For local install
Open powershell, and run:
```
$ python -m pip install apache-flink 1.12.0
```
Then, like google colab, use your IDE of choice and run 
```python
import pyflink
```

Reference: https://ci.apache.org/projects/flink/flink-docs-release-1.12/dev/python/installation.html
