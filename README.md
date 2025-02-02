# python_mvp

Python package template with minimal setup and instructions on how to publish the package to PyPI and increase its visibility.

1. Click the "Use this template" button at https://github.com/yachty66/python-mvp and create a new repository.

2. Name the folder inside `src` the same as the repository name / the name you want your Python package to have.

3. Add your name to the `LICENSE` file.

4. Populate the folder's content with your code, and before publishing, run `pip install -e .` to test the functionality locally. With this package as an example, you can do

```python
python_mvp.main()
```

which will print "Hello World" to the console.

5. Install Twine and use it to publish the package to PyPI.

```bash
pip install twine
python -m build
python -m twine upload dist/*
```

Then go to https://pypi.org/manage/account/token/ and get your token, which you need to copy and paste into the terminal.

6. In the terminal, you should now see the URL of the package. If you follow the URL, you will also see the installation command, which you can use to make the repo work.

7. Now that you have published the package and it is on GitHub, you can do GitHub SEO. If you use a cursor, you can index your whole codebase and run the following prompt: "I need good keywords for my Python packages that I can put in my repository's description."