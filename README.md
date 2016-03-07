
## Tutorial on Pandas and data analysis in Python
- histed 160307: added some docs
- all code, notebooks are from @jreback [Pandas Talk on Data Analysis, Feb 19 2016](https://github.com/jreback/PandasTalks)

### How to start using the tutorial notebooks
- Install anaconda
   - From the [Continuum download page](https://www.continuum.io/downloads), download and run the Mac OS X 64-bit Graphical Installer for Python 3.5
   - be sure to do a full installation
- Install git
   - On a mac, install Homebrew from [these directions](http://brew.sh/)
   - Then type $ brew install git
- Clone this repository.

   In terminal:
```
mkdir ~/Repositories
cd ~/Repositories
git clone https://github.com/histed/PandasTalks.git
cd PandasTalks
```
- Set up the anaconda environment
```
conda env create -n PandasTalks --file=environment.yml
source activate PandasTalks
```
- Launch the notebook and start the tutorial
```
jupyter notebook 
```

