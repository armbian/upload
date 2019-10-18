# Repository uploader 

apt.armbian.com

This repository is incoming location for **apt.armbian.com** packages repository. Once your pull request is merged, packages will be automatically published to the repository. You can [make debs with our build tools](https://github.com/armbian/build), made on your own or just grab from somewhere.
<br/><br/>



   1. Fork this repository to your account
   2. Upload files to [upload locations](#upload-locations)
   3. Create pull request

<br/><br/>
<br/>

## Upload locations

<table width="100%" cellpadding="4" cellspacing="0">
	<tr>
		<td align="center" rowspan="4">
			<b>Debian</b>
		</td>
		<td align="center" rowspan="2" width="60%" valign="center">
			<a href="debs/stretch"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/stretch">Stretch</a>
		</td>
		<td align="center" width="30%" valign="center">
			<a href="debs/extra/stretch-utils"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/extra/stretch-utils">utilities</a>
		</td>
		<td align="center" rowspan="8" width="50%">
			<a href="debs/"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="32" height="32" border="0"/></a>
			<br><a href="debs/">main</a>
		</td>
	</tr>
	<tr>
		<td align="center" width="33%" valign="center">
			<a href="debs/extra/stretch-desktop"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/extra/stretch-desktop">desktop</a>
		</td>
	</tr>
	<tr>
		<td align="center" rowspan="2" width="33%" valign="center">
			<a href="debs/buster"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/buster">Buster</a>
		</td>
		<td align="center" width="33%" valign="center">
			<a href="debs/extra/buster-utils"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/extra/buster-utils">utilities</a>
		</td>
	</tr>
	<tr>
		<td align="center" width="33%" valign="center">
			<a href="debs/extra/buster-desktop"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/extra/buster-desktop">desktop</a>
		</td>
	</tr>
		<tr>
		<td align="center" rowspan="4">
			<b>Ubuntu</b>
		</td>
		<td align="center" rowspan="2" width="60%" valign="center">
			<a href="debs/bionic"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/bionic">Bionic</a>
		</td>
		<td align="center" width="30%" valign="center">
			<a href="debs/extra/bionic-utils"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/extra/bionic-utils">utilities</a>
		</td>
	</tr>
	<tr>
		<td align="center" width="33%" valign="center">
			<a href="debs/extra/bionic-desktop"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/extra/bionic-desktop">desktop</a>
		</td>
	</tr>
	<tr>
		<td align="center" rowspan="2" width="33%" valign="center">
			<a href="debs/disco"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/disco">Disco</a>
		</td>
		<td align="center" width="33%" valign="center">
			<a href="debs/extra/disco-utils"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/extra/disco-utils">utilities</a>
		</td>
	</tr>
	<tr>
		<td align="center" width="33%" valign="center">
			<a href="debs/extra/disco-desktop"><img src="https://dl.armbian.com/_h5ai/public/images/themes/comity/cloud-upload-1.png" name="Upload" align="bottom" width="24" height="24" border="0"/></a>
			<br><a href="debs/extra/disco-desktop">desktop</a>
		</td>
	</tr>	
</table>

	$release = board support packages (linux-$release-root-orangepi)
	$release-utilities = htop, hostapd (packages that are release dependant)
	$release-desktop = accelerated drivers (... and desktop related)
	main = kernel, u-boot, armbian-$release-desktop, armbian-firmware*, armbian-config

## Statistics

	 * [bionic-desktop]: Armbian bionic desktop (packages: 5)
	 * [bionic-utils]: Armbian bionic utilities (packages: 33)
	 * [bionic]: Armbian main repository (packages: 1273)
	 * [buster-desktop]: Armbian buster desktop (packages: 3)
	 * [buster-utils]: Armbian buster utilities (packages: 12)
	 * [buster]: Armbian main repository (packages: 621)
	 * [disco-desktop]: Armbian disco desktop (packages: 2)
	 * [disco-utils]: Armbian disco utilities (packages: 11)
	 * [disco]: Armbian main repository (packages: 584)
	 * [jessie-desktop]: Armbian jessie desktop (packages: 155)
	 * [jessie-utils]: Armbian jessie utilities (packages: 54)
	 * [jessie]: Armbian main repository (packages: 4076)
	 * [stretch-desktop]: Armbian stretch desktop (packages: 8)
	 * [stretch-utils]: Armbian stretch utilities (packages: 49)
	 * [stretch]: Armbian main repository (packages: 1308)
	 * [utils]: Armbian utilities (backwards compatibility) (packages: 54)
	 * [xenial-desktop]: Armbian xenial desktop (packages: 121)
	 * [xenial-utils]: Armbian xenial utilities (packages: 42)
	 * [xenial]: Armbian main repository (packages: 1458)

Packages [full list](content.txt)

