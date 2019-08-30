# beta.armbian.com uploader

**Upload files to the desired directory and they will automatically be published to the repository.**

1. [Make debs with our build tools](https://github.com/armbian/build)

2. Clone this repository and copy the content from build/output/debs to this upload/debs. Use prepared structure when making armbian debs! If you need to add some 3rd party generic package for all Armbian variants, just put it to the upload/debs

3. Commit and create a pull request



Packages [full list](content.txt) | statistics:

	 * [bionic-desktop]: Armbian bionic desktop (packages: 1)
	 * [bionic-utils]: Armbian bionic utilities (packages: 1)
	 * [bionic]: Armbian main repository (packages: 326)
	 * [buster-desktop]: Armbian buster desktop (packages: 1)
	 * [buster-utils]: Armbian buster utilities (packages: 1)
	 * [buster]: Armbian main repository (packages: 332)
	 * [disco-desktop]: Armbian disco desktop (packages: 1)
	 * [disco-utils]: Armbian disco utilities (packages: 1)
	 * [disco]: Armbian main repository (packages: 326)
	 * [stretch-desktop]: Armbian stretch desktop (packages: 1)
	 * [stretch-utils]: Armbian stretch utilities (packages: 1)
	 * [stretch]: Armbian main repository (packages: 326)
	 * [utils]: Armbian utilities (backwards compatibility) (packages: 0)
	 * [xenial-desktop]: Armbian xenial desktop (packages: 1)
	 * [xenial-utils]: Armbian xenial utilities (packages: 1)
	 * [xenial]: Armbian main repository (packages: 326)
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

	$release = board support packages
	$release-utilities = htop, hostapd
	$release-desktop = accelerated drivers
	main = armbian-$release-desktop, armbian-firmware, armbian-config + various

[www.armbian.com](https://www.armbian.com)
