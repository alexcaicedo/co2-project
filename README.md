# **Global CO<sub>2</sub> Emissions**
This is a pre-processing and EDA project using CO<sub>2</sub> emissions data which was obtained from the [repository](https://github.com/owid/co2-data) of the Our World in Data Non-Governmental Organization (NGO).

This repo was created for self-educational purposes, in order to better understand and follow a professional Data Science workflow and structure, creating virtual environments and installing packages. Furthermore, the Pandas API was extended for organizing the code in modules and automating the (mostly missing values so far) EDA process. The data pre-processing source code can be found in the **`co2.ipynb`** file.

## **Instructions**

1. Clone repository in your desired directory

```
git clone https://github.com/alexcaicedo/co2-project.git
```

2. Create virtual environment on Windows (replace myenv with desired environment name):
```
conda create --name myenv python=3.9.13
```
```
conda activate myenv
```
- On Linux and MacOS:
```
conda create -n myenv python=3.9.13
```
```
conda activate myenv
```
3. Install requirements.txt packages
```
conda install -r requirements.txt
```
## **To-do**
- Create a written report explaining the visualizations of the pbix dashboard.