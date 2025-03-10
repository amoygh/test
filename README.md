### **To get started with using the QGIS BEACONs Processing Provider plugin, follow these steps:**

1) [Download and Install QGIS](#1-download-and-install-qgis)
2) [Download and Install BEACONs processing provider plugin](#2-download-and-install-beacons-processing-provider-plugin)
3) [Tutorial](#3-tutorial)


### <ins>**1) Download and Install QGIS**</ins>
* Download QGIS from [here](https://qgis.org/download/).  For Windows users, choose **Offline (Standalone) installers:** **Latest Version for Windows (3.xx)**. 
* Run the downloaded installer file.  In the installer, Press Next when prompted, accept any licenses, and finally press Install.

### <ins>**2) Download and Install BEACONs processing provider plugin**</ins>

* Download plugin from [here](https://github.com/amoygh/test/releases/download/v0.01/beacons_provider_v0.01.zip). Remember where it was saved.
* Start QGIS and do the following steps.  Refer to the below image for steps i-iv:
<ul>

1) From the **Plugins** menu, select **Manage and Install Plugins** and the **Plugins** dialog will appear.  
2) From the **Plugins** dialog, select **Install from ZIP** from the sidebar on the left.
3) Locate and choose the downloaded **beacons_provider_vx.xx.zip** file.
4) Press **Install Plugin**.  
    * A Security warning dialog may appear and can be dismissed by pressing **Yes**.  
    * The BEACONs plugin is dependent on the following plugins:  Saga NextGen Provider plugin.  If this is not already installed, a dialog called **Plugin Dependencies Manager** will appear. Press **OK** to allow this plugin to be installed.
    * Wait for the installation to complete.  

* ![](./images/readme/QGIS_Plugins_Manage_and_Install_Plugins_plugins_install_from_ZIP.png?raw=true)


5) Next, enable the plugin by selecting **Installed** from the Plugins dialog sidebar and ensure **Beacons** is checked as shown below.  Also ensure, the **GRASS GIS Processing Provider** and **Processing Saga NextGen Provider** are checked as well.

* ![](./images/readme/plugins_installed.PNG?raw=true)


6) The plugin is now ready to use and can be accessed through the **Processing Toolbox**.
If the Processing Toolbox panel is not visible, make sure the Toolbox toolbar button (gear icon) is pressed as shown below.


* ![](./images/readme/toolbar_process_toolbox.png?raw=true)
</ul>

### <ins>**3) Tutorial**</ins>
<ul>

To learn how to use the BEACONs Processing Provider plugin, click [here](https://github.com/amoygh/test/blob/main/tutorial/tutorial.md) to follow a tutorial that shows how to build a  Benchmark Builder input dataset.
