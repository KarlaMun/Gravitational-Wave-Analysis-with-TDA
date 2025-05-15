# Gravitational Wave Analysis with TDA
 Topological Data Analysis for Gravitational Waves


## Framework installation

Log into a linux machine with Anaconda installed.

In the terminal do:

1. Clone the repository:
  ```
  git clone git@github.com:KarlaMun/Gravitational-Wave-Analysis-with-TDA.git
  ```
2. Access the code:
  ```
  cd Gravitational-Wave-Analysis-with-TDA
  ```

3. Install the conda enviroment:
  ```
  conda env create -f environment.yaml
  conda activate gravitational_wave_analysis
  conda develop .
  ```
  
3.1 Update the conda enviroment:
   ```
   conda env update --file environment.yaml --prune
   ```
