# package_name

Description. 
The package package_name is used to:
	Processing:
		-histogram matching
		-structural similarity
		-resize image
	utils:
		-Read image
		-save image
		-plot image
		-plot result
		-plot histogram


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install package_name

```bash
pip install package_name
```
## comand installations distribuitions
python -m pip install --upgrade pip
python -m pip install --user twine
python -m pip install --user setuptools

## comandos para criar as distibuições
python setup.py sdist bdist_wheel

## criando conta no pypi
https://pypi.org/account/register/

## criando uma conta no tesPypi
https://test.pypi.org/account/register/

## comando para publicação no TestPypi
python -m twine upload --repository-url
https://test.pypi.org/legacy/dist/*

## Usage

```python
from package_name.module1_name import file1_name
file1_name.my_function()
```

## Author
Levi Mori

## License
[MIT](https://choosealicense.com/licenses/mit/)