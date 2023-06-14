# Common Library

Common Library is a Python source to which is used by BPA application micro services.
## Installation and updating
Use the package manager [pip](http://cisco.com) to install common library like below. 
Rerun this command to check for and install  updates .
```bash
pip install git+https://bitbucket-eng-sjc1.cisco.com/bitbucket/projects/CF-BPA/repos/common-python-library
```

## Usage
Features:
* rbachelper.validateToken  --> validates user token 

#### Demo of some of the features:
```python
import common-lib
from common-lib import helpers.mongohelper

message = common.mongohelper.test("The helper package is ready for use")


list_of_numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]
for chunk in toolbox.functions.listChunker(lst=list_of_numbers, csize=3):
    print(chunk)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[COMMON](https://cisco.com)