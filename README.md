# 007revad Synology Package Source

![Badge](https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2F007revad%2FSynology_package_source&label=Visitors&icon=github&color=%23198754&message=&style=flat&tz=Australia%2FSydney)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/paypalme/007revad)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/007revad)
<!--- [![committers.top badge](https://user-badge.committers.top/australia/007revad.svg)](https://user-badge.committers.top/australia/007revad) --->

### Description

007revad Synology Package Source adds DSM packages that are available from GitHub to Package Center so users can easily install packages from various GitHub developers and Package Center can update the packages when newer versions are released.

### Where are the spk files?

- It does not host any of the spk files.
- It just provides the information required by Package Center for Package Center to display available packages for the Synology's DSM version and CPU arch.
- When you click Install or Upgrade in Package Center the spk file is downloaded from the package developer's GitHub repo.
    - So all installs and upgrades count as downloads from the package developer's GitHub repo.

### How to add the Synology Package Source to Package Center

1. Open Package Center and click on Settings.
2. Click on Package Sources.
3. Click Add.
4. Enter `007revad` as the Name.
5. Enter `https://spkrepo.007daver.workers.dev/` as the Location.
6. Click OK then OK.
7. You'll then see the available packages when you click Community on the left.

<br>

<p align="center">Add the package source</p>
<p align="center"><img src="/images/pkg_source2.png"></p>

<br>

<p align="center">Packages from the new package source in the Community section</p>
<p align="center"><img src="/images/packages1.png"></p>

<br>

<p align="center">Packages with upgrades available</p>
<p align="center"><img src="/images/updateable.png"></p>
