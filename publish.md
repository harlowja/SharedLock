1. Update the change log:

       CHANGELOG

2. Update the version number:

       setup.cfg
       fasteners/version

4. Make sure that the working directory is clean.


4. Build:

       source venv/bin/activate
       python -m build

5. Inspect the packages manually.


6. Upload:

       twine upload dist/*

7. Tag the git repo.

8. Rebuild the docs

      pip install -r requirements-mkdocs.txt
      mkdocs build

9. Upload docs to readthedocs:

      TODO