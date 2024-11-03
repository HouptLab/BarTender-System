# BarTender-System
Meta repository for code accompanying the paper "BarTender: A system for recording intakes and body weights in ingestive behavior experiments," by Houpt, Houpt, and Cassell-Erquiaga.

A video walkthrough of the system in use is at: https://youtu.be/3O_7y73_KkQ .  A description of the system and components is also provided on the Houpt Lab wiki at: https://wiki.houptlab.org/wiki/BarTender_System. 

The BarTender system comprises 4 parts:

1. the BarTender app for Macintosh that organizes experiments, and collects weights of barcoded items such as water bottles or food jars;
2. the PointOfScale app for iPad that collects body weights of animals via a Bluetooth scale
3. a Firebase cloud database in which daily data is stored
4. the BarTab framework for the web that displays and summarizes the collected data across an experiment

This individual repositories are at:

- https://github.com/HouptLab/BarTender
- https://github.com/HouptLab/BarTab
- https://github.com/HouptLab/PointOfScale

Clone using `--recurse-submodules`:

	git clone --recurse-submodules https://github.com/HouptLab/MetaTest

 
Installation README's are provided in each app's submodule linked above.

Details of the Google Firebase realtime database are at https://firebase.google.com. 

For more information, contact Dr. Tom Houpt at houpt@bio.fsu.edu .
