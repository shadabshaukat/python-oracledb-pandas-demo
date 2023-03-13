# Statistical Analysis with Oracle Database, Pandas, Matplotlib and Seaborn

This project contains Python code that utilizes the Matplotlib and Seaborn libraries for data visualization.
Installation

## Usage

    Ensure that you have the necessary data files in the correct location.
    Run the Python code files using a Python interpreter or a Jupyter notebook.
    The resulting graphs will be displayed or saved as image files depending on the code.

```
# Clone the Github Repo
git clone https://github.com/shadabshaukat/python-oracledb-pandas-demo.git

cd python-oracledb-pandas-demo

# Set the environment variables to connect to Oracle Database
export PYTHON_USERNAME=username
export PYTHON_PASSWORD=password
export PYTHON_CONNECTSTRING='(description= (retry_count=20)(retry_delay=3)(address=(protocol=tcps)(port=1521)(host=adb.ap-melbourne-1.oraclecloud.com))(connect_data=(service_name=*******_high.adb.oraclecloud.com))(security=(ssl_server_dn_match=yes)))'

# Install the Python dependencies
pip3 install -r requirements.txt

# Run Script for Analysis with Data
python3 pandas-data.py

# Run Script to Display Charts
python3 pandas-charts.py

```

This project requires the following libraries:

```
Pandas
Numpy
Matplotlib
Seaborn
oracledb
```

#### Please feel free to contact me if you have any questions or comments about this project.
