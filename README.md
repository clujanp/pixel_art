# Pixel Art Package

This is package of wheel for lab in Python Packaging course.

## how to use
> [!IMPORTANT]  
> Need Python installed 3.6 >=.

1. Recomended create n activate venv
   ```bash
   python -m venv venv´
   source venv/bin/activate
   ```
2. Install requirements
   ```bash
   pip install -r requirements.txt
   ```
3. Build and checkout wheel
   ```bash
   python setup.py sdist bdist_wheel
   ls -lha dist
   ```
