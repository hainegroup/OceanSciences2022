### March '23: The notebooks in this repo are no longer supported with the latest OceanSpy version. To see working, supported versions of these notebooks visit: https://github.com/hainegroup/Poseidon-share

# Ocean Sciences 2022 Poseidon tutorial
Repository containing the tutorial notebook run during the Townhall Sesion

## TH11 - Open Science Analysis of Petabyte Scale Ocean and Ocean-Atmosphere Models with Open Source Cloud Tools







How to:

You can download the contents of this repository into any machine with internet access and `git` installed, by executing the following in the command line:

`git clone https://github.com/hainegroup/OceanSciences2022.git`


To reproduce the results of the tutorial notebooks, they need to be downloaded and executed within [Sciserver](https://www.sciserver.org/) to access the model data and correct (conda) environment. Furthermore, within Sciserver, the notebooks must run within a container created with the `Oceanography 2.3` Compute image, along with access to either the `Poseidon` (for llc4320) or `Ocean Circulation` (for ECCO) data volumes.

The folder `img/` contains static images used in the notebooks for model-data comparison. The folder needs to be added within the (local) directory as to where
the tutorial notebooks are stored, so that within the notebooks `img/figure.png` sucessfully loads the static images. 

## LLC90 Tutorial

To run the notebook : </br>
1. Make sure you create a container with `Oceanography 2.3` compute image along with `Ocean Circulation` data volume. You will be redirected into a jupyter lab environment. Navigate to `Temporary/user/scratch`. **This is where you will run the notebook**. You can do this simply by clicking and opening these folders. If you're comfortable with working on a terminal , you will have to go to `/scratch` using the following command </br>
  ```
  cd /home/idies/workspace/Temporary/your_username/scratch/
  ```
2. You should have the notebook `LLC_90_Sciserver_tutorial.ipynb` along with the folders `/img` and `/test_data` to successfully reproduce the Ocean Sciences tutorial. If you are comfortable using `git` you can clone this repo into your `/scratch` folder. If you have no prior experience with `git`, simply download this repo and upload the folders into your jupyter lab environment on SciServer. The jupyter lab interface gives you the option to upload files and folders from your local system. 

## LLC4320 Tutorial
1. Follow the same steps as for the LLC90 tutorial, except make sure that when you create your container, you additionally select the `Poseidon` data volume. 
