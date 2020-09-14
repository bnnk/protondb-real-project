# protondb-real-project
Here, we are going to learn to use ProtonDB for a mini project
## Setup you environment
First, download wheels from bnnk/protondb, Then:
```bash
pip install your_wheel_filename.whl
```
## Lets Start coding!

First, import ProtonDB, Then import the writer from ProtonDB
```python
from protondb import ProtonDB
from protondb.ext.file import FileWriter
```
Then, create an instance of the File I/O Engine
```python
engine = FileWriter("<file-name-of-your-choice>.pro3")
```
Then, create an ProtonDB for operating the DB.
```python
db = ProtonDB(engine)
```
The
