# NAPALM

Welcome to the NAPALM(Network Automation & Programmability Abstraction Layer Multi-vendor support) wiki!
with NAPALM:
--NAPALM is a python library using a unified API for multiple-vendor-devices
--A simple interface to interact w/ network devices is provided
--A lot ot low-level(programming) complexity is abstracted.

To install NAPALM(on UBUNTU):

apt-get install update                                                #to update repo
apt-get install python -y
apt-get install build-essential libssl-dev libffi-dev -y
apt-get install python-pip -y
pip install --upgrade pip                                           #to upgrade pip
pip install cryptography
pip install netmiko                                       #netmiko is required to interact w/ IOS devices as IOS has no native APIs
pip install napalm
