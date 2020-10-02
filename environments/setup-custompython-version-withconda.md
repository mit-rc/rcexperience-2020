# Q: How can I create a custom Python environment for a particular project?

# A: Conda/minicoda is one way to do this.

# Installing conda via command line


1. create a custom directory to work and switch to working in that directory

  ```
  mkdir myspecialenv
  cd    myspecialenv
  ```


2. download conda install script and install the conda software in a sub-directory called

   ```
   curl https://repo.anaconda.com/archive/Anaconda3-2020.07-MacOSX-x86_64.sh > Anaconda3-2020.07-MacOSX-x86_64.sh
   chmod +x Anaconda3-2020.07-MacOSX-x86_64.sh
   ./Anaconda3-2020.07-MacOSX-x86_64.sh -p conda3
   ```
   
source conda3/bin/activate
python -V
conda create -n py37 python=3.7
conda activate py37
python -V
```
