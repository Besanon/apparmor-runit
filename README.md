# apparmor-runit

This repository tries to expand and adapt the achievements in apparmor policies of Alexandre Pujol, Mikhail Morfikov and others to the runit init system. Most of the available work in apparmor policing is developed and tested to run under SYSTEMD init systems. Many of the profiles written by these authors can readily be run under linux distributions with NON-SYSTEMD init systems. However, much work is left to be done when we try to confine the services, dbus freedesktop software or a whole desktop.

This attempt is still in early development. Runit so far can´t get completly confined up to now. Some parts already work and - your are invited to help fulfilling this gab if you wish to get a more secure linux with runit as base.

In this repository only the altered profiles from the great work of Alexandre Pujol <alexandre@pujol.io> are shown. You will find some new profiles here. Theses profiles were developed using Void Linux (https://www.voidlinux.org). Runit has different implementations - they are still NOT reflected in this work. The profiles need the abstractions and tunables of the apparmor.d repositry from Alexandre Pujol. You will need them to get the profiles running.

Use these profiles at your own risk and keep in mind that most of them will need some adaptation in some other environment.

In the directory Setup i will give some general hints on how the machines i was working on were configured and set up.
