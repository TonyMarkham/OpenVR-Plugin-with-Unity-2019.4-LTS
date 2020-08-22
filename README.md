# OpenVR-Plugin-with-Unity-2019.4-LTS

## Setup

### Contents:
1. Download Unity 2019.4 LTS
2. Download unity-xr-plugin
3. Start a new Unity Project
4. Setup Unity to use OpenVR Unity XR Plugin

### 1. Download Unity 2019.4 LTS

![](./img/installUnity2019.4.8f1.png)

### 2. Download unity-xr-plugin
1. Go to: https://github.com/ValveSoftware/unity-xr-plugin/releases
2. Download: OpenVR-XR-Plugin-Installer.unitypackage


![](./img/downloadOpenXRUnityXRPlugin.png)

### 3. Start a new Unity Project

![](./img/CreateNewURPProject.png)

### Setup Unity to use OpenVR Unity XR Plugin

1. Drag the `OpenVR-XR-Plugin-Installer.unitypackage` file that you downloaded in Step 2 and drop it into your project window.
2. When the `Import Unity Package` Window pops up, simply click the `Import` Button.

![](./img/InstallOpenVR.gif)

3. After the installation finishes, the OpenVR XR Plugin will appear in your `Packages` Folder.

![](./img/AfterInstallingPlugin.png)

4. Open up the Project Settings Window: `Edit > Project Settings`
5. In the `XR Plug-in Management` tab, ensure that both `Initialize XR on Startup` and `OpenVR Loader` are checked.

![](./img/ProjectSettings-XRPluginManagement.png)