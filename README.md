# citus-iot-ecosystem
The Citus™ IoT Ecosystem bootstrap code which is used to provision an IoT Platform in Citus™ IoT Ecosystem.

[![Docker Pulls](https://img.shields.io/docker/pulls/cuongquay/citus-iot-ecosystem-website.svg?maxAge=2592000)]()

![Citus IoT](https://raw.githubusercontent.com/cuongquay/citus-iot-device-agents/master/docs/images/citus-iot-ecosystem.png)

Features
========
1. Device Setup
2. Device Activation
3. Device Software Update
4. Device Revocation
5. Device Cleanup

Test /w Docker
==============

1. Install Docker Tool Box from https://www.docker.com/products/docker-toolbox.
2. Launch Kitematic, choose **citus-iot-device-agents** container and open **exec** window.
3. On Citus™ IoT Platform (https://apps.citus.io): go to [Connected Things] menu, create a device then [Activate].
4. Pickup the installation shell script from the left section box on [ACTIVATE YOUR DEVICE] tab.
5. Try some commands: citus-device active [citus-device update | citus-device revoke | citus-device remove].


<div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="en_US" data-type="vertical" data-theme="dark" data-vanity="cuongquay"><a class="LI-simple-link" href='https://vn.linkedin.com/in/cuongquay?trk=profile-badge'>DUONG Dinh Cuong</a></div>
