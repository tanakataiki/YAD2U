# SettingUp Deepmimic for Windows

The YAD2U supports Windows 10. While it might be possible to run the
YAD2U using other versions of Windows, it has not been tested on
other versions. Furthermore, the YAD2U has not been tested on a
Windows VM such as Bootcamp or Parallels.

To use the YAD2U, you refer to Installation-Windows.md
and you need to setup mlagents for unity

This repository only support for Unity 2017.4.20f2 LTS or newer
I strongly recommend you to use LTS version of Unity.

## Step 0: Testing
Open Demo Folder and Select any Project you like
Click .exe file and the demo is done.


## Step 1: Recording Motion From Mocap Data

Download Mocap Asset from below link.

[Add to Cart](https://assetstore.unity.com/packages/3d/animations/movement-mocap-collection-46705) 

After installation, you must open MoCap Collection Folder 
and Place Movement MoCap Collection Folder to \UnitySDK\Assets in mlagents


## Step 2: Record Motion

You need to open UnitySDK folder and go to dirrectory below
\UnitySDK\Assets\ML-Agents\Examples\Mimic\Scenes\RecordMotion
open Motion Recording Scene and click play 

Motion Record is automatically generated from Mocap GameObject and saved to saved Motion
then place it to StreamingAssets folder below for example

Training
\Compiled\Walking\walking02_120Hz\walking02_120Hz_Data\StreamingAssets\Mimic

Testing
\Demo\Walking\walking02_120Hz\walking02_120Hz_Data\StreamingAssets\Mimic



## Step 3: Quick Start

The YAD2U depends on a number of Python packages. Use `pip` to
install these Python dependencies.
install mlagents v5 using command below

pip install mlagents==0.5.0



## Acknowledgements

We would like to thank
[Jason Weimann](https://unity3d.college/2017/10/25/machine-learning-in-unity3d-setting-up-the-environment-tensorflow-for-agentml-on-windows-10/)
and
[Nitish S. Mutha](http://blog.nitishmutha.com/tensorflow/2017/01/22/TensorFlow-with-gpu-for-windows.html)
for writing the original articles which were used to create this guide.

[Morro Motion] (https://assetstore.unity.com/publishers/10121)

