# Survival Churn Analysis

This guide provides step-by-step instructions for AI modeling of churn.

## View the Notebook
[![View Notebook](https://img.shields.io/badge/launch-notebook-blue.svg)](https://github.com/LaVarEdwards/survival-churn-analysis
/blob/main/survival-churn-analysis.ipynb)

## Prerequisites

#### 1. Install Homebrew: If you don't have Homebrew, install it from the terminal:   
		/bin/bash -c "$(curl -fsSL [https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh](https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh))"

#### 2. Check/Install Python: If you already have Python installed, check the version:   
		python --version

#### 2a. If you don't have Python, or if the version is older than 3.12, install Python 3.12 using Brew:   
		brew install python@3.12


## Installation

#### 1. Install Spark and Hadoop:
		cd <your_project_directory>
		python -m venv churn-env
		source churn-env/bin/activate

#### 2. Install the packages:
		pip install -r requirements.txt


NOTES: Python virtual environments (venv) offer several key benefits:  

<table>
<tr><td>
<b>Isolation of Project Dependencies</b>:
</td><td>
Each project gets its own isolated environment with specific package versions. This prevents conflicts between different projects that might require different versions of the same library.    
</td></tr>
<tr><td>
<b>Clean System Installation</b>:
</td><td>
You can experiment with new libraries or different versions without cluttering your global Python installation.    
</td></tr>
<tr><td>
<b>Reproducibility</b>:  
</td><td>
Easily recreate the same environment on different machines, ensuring consistency across development, testing, and production environments.   
</td></tr>
<tr><td>
<b>Version Control</b>:  
</td><td>
The requirements.txt file generated within a venv helps track and easily reinstall specific package versions.    
</td></tr>
<tr><td>
<b>Simplified Collaboration</b>:  
</td><td>
Team members can set up identical development environments, reducing compatibility issues.    
</td></tr>
<tr><td>
<b>In summary</b>:  
</td><td>
Python venv is a valuable tool for managing dependencies, keeping your projects organized, and ensuring smooth collaboration with others.  
</td></tr>
</td></tr>
</table>

Commands to start and stop the python venv 

<table>
<tr><td>
start
</td><td>
source pyspark-env/bin/activate
</td></tr>
</td></tr>
<tr><td>
stop
</td><td>
deactivate
</td></tr>
</table>


## Testing

#### 1. [download](https://github.com/LaVarEdwards/survival-churn-analysis/blob/main/survival-churn-analysis.ipynb) the jupyter notebook 
 
#### 2. start jupyter lab
		jupyter lab

#### 3. Open and run the survival-churn-analysis.ipynb notebook.


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


## Contact

Project Link: [https://github.com/LaVarEdwards/churn-analysis](https://github.com/LaVarEdwards/survival-=churn-analysis)
