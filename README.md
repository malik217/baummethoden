# baummethoden
This is a test git repository

## These arre the git commands i have already learned

- git clone
- git branch
- git checkout
- git commit
- git push
- git pull
- git add


## Dependecies Install log

(.venv) PS C:\Users\Malik\Desktop\Data Science\baummethoden> git branch python-dependencymanagement
Switched to branch 'python-dependencymanagement'
(.venv) PS C:\Users\Malik\Desktop\Data Science\baummethoden> pip install pandas
Collecting pandas
  Downloading pandas-1.3.1-cp38-cp38-win_amd64.whl (10.4 MB)
Collecting numpy>=1.17.3
  Downloading numpy-1.21.1-cp38-cp38-win_amd64.whl (14.0 MB)
     |████████████████████████████████| 14.0 MB 6.4 MB/s
Collecting pytz>=2017.3
  Downloading pytz-2021.1-py2.py3-none-any.whl (510 kB)
     |████████████████████████████████| 510 kB 6.4 MB/s
Collecting python-dateutil>=2.7.3
  Downloading python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
     |████████████████████████████████| 247 kB 6.4 MB/s
Collecting six>=1.5
  Downloading six-1.16.0-py2.py3-none-any.whl (11 kB)
Installing collected packages: numpy, pytz, six, python-dateutil, pandas
Successfully installed numpy-1.21.1 pandas-1.3.1 python-dateutil-2.8.2 pytz-2021.1 six-1.16.0
WARNING: You are using pip version 20.2.3; however, version 21.2.3 is available.
You should consider upgrading via the 'c:\users\malik\desktop\data science\baummethoden\.venv\scripts\python.exe -m pip install --upgrade pip' command.
(.venv) PS C:\Users\Malik\Desktop\Data Science\baummethoden> pip freeze > requirements.txt
(.venv) PS C:\Users\Malik\Desktop\Data Science\baummethoden> pip install -r requirements.txt
Requirement already satisfied: numpy==1.21.1 in c:\users\malik\desktop\data science\baummethoden\.venv\lib\site-packages (from -r requirements.txt (line 1)) (1.21.1)
Requirement already satisfied: pandas==1.3.1 in c:\users\malik\desktop\data science\baummethoden\.venv\lib\site-packages (from -r requirements.txt (line 2)) (1.3.1)
Requirement already satisfied: python-dateutil==2.8.2 in c:\users\malik\desktop\data science\baummethoden\.venv\lib\site-packages (from -r requirements.txt (line 3)) (2.8.2)      
Requirement already satisfied: pytz==2021.1 in c:\users\malik\desktop\data science\baummethoden\.venv\lib\site-packages (from -r requirements.txt (line 4)) (2021.1)
Requirement already satisfied: six==1.16.0 in c:\users\malik\desktop\data science\baummethoden\.venv\lib\site-packages (from -r requirements.txt (line 5)) (1.16.0)
WARNING: You are using pip version 20.2.3; however, version 21.2.3 is available.
You should consider upgrading via the 'c:\users\malik\desktop\data science\baummethoden\.venv\scripts\python.exe -m pip install --upgrade pip' command.