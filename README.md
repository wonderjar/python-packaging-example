# python-packaging-example


Reference

https://packaging.python.org/tutorials/packaging-projects/https://packaging.python.org/tutorials/packaging-projects/


```
pip install setuptools wheel

python setup.py sdist bdist_wheel

```


在其他项目

pip install 

或者使用 setup.py

```
	install_requires=['wonderjar_pkg'],
	dependency_links=[
	    'git+https://github.com/wonderjar/python-packaging-example.git@0.0.1#egg=wonderjar_pkg-0.0.1'
	],
```

```
pip install -e . --process-dependency-links
```

