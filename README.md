<img src="shape.gif" width=100/><br/>
# yoctoo-fpso-analytics
## Solution to the Shape Tech-Test
### Leonardo Lacerda Galler - Data Engineer

-----------------

* Folder that contains the data:
  * <i>dados/</i>
  * <i>notebooks</i>

Requirements:
* Docker compose-up
* At least 3Gb of free storage

Steps:
1. Clone this repository in a local environment
2. Access the the folder
3. Run the following command to start docker with jupyter notebook and make the data and the notebooks available to the container.
   <code> docker run -p 8888:8888 -v YOUR_CLONED_DIR/docker:/home/jovyan/docker jupyter/base-notebook </code>
4. After the container start the notebook will be available at http://127.0.0.1:8888/lab
5. Now, we need to install some needed packages to work.
After connecting to the jupyter lab, open a new terminal.
6.  In the terminal you will run the following command: 
<code>conda install --file docker/requirements.txt</code> 
7. After the installation, you can open the notebook <b>fpso-analysis.ipynb</b> that can be found on "docker/notebooks"
8. Run all the commands.