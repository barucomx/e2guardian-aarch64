I did compiled these packages for a Netgate SG-1100, using the binaries and guidance from <a href="https://github.com/marcelloc/Unofficial-pfSense-packages/issues/58">marcelloc</a>

<img src="https://store.netgate.com/Assets/ProductImages/SG1100FrontTopAngle.jpg">

<p align=justify>It worked for me, just remember <b>you're using an ARM processor</b>, <i>do not expect the same performance than a huge appliance</i>, once you configure it, simply it works smoothly.</p>

You just need to:

1. Connect via ssh to your **sg1100**

2. Clone this repository

3. Open the directory **FreeBSD:11:aarch64** and run the command **_pkg add *_**

^_^ 

<p align=justify>Ps. During the instalation of the packages, <b>some will show a warning about the OS Version</b>, just ignore them and wait until all packages were installed, once it finishes, refresh the web console and <i>'voilà'</i> you're ready to config <b>e2guardian.</b></p>
