# Actiwatch reader, a tool to read Actiwatch fast data files and plot graphs

## Introduction

The Actiwatch (Cambridge Neurotechnology, similar models exists from Mini Mitter) is a "small, rugged, actigraphy-based data loggers that record a digitally integrated measure of gross motor activity". The Actiwatch records all movement over 0.05g. It also has filters to exclude readings outside the 3-11Hz range (to eliminate gravitational artefacts). It seems that it's based on an uniaxial accelerometer that produces a signal (how?) as the watch moves. The signal is measured at 32Hz but integrated to match the period needed (1 point every 2s, for example). There is a button on the watch that acts like a marker in the log file.

The goal of the Actiwatch Reader to parse log (text) files resulting from an experiment with the Actiwatch and to plot graphs.

With this software, you can:

* Open and parse AWF files
* Read log properties (subject, age, sex, start date, start time, etc.)
* Create a graphical representation of activity (day by day)
* Zoom/un-zoom on the graph
* Copy the actogram to the clipboard and/or save it to many common image formats
* ... (improvements will depends on my needs and users'needs ; feel free to send your comments)

Please note that it currently only works with "Fast Actiwatch Data" files (*.AWF), i.e. files resulting from acquisition with a 2, 5 ou 10 second epoch. "Regular experiments" (usually using 30s epochs) uses another file format (*.AWD files). Since I don't have access to these files, I do not know exactly what is their structure. If you want, you can send me AWD file: I'll support them in the next version.

In my experimental setup, I asked for a 2s period (0.5Hz).

## Screenshots

Screenshots can be found in the screenshots/ directory.

## Software

Download the latest version of Actiwatch Reader in the bin/ directory

The bin/ directory gives you all files and includes the executable (the software you'll use). You can run this software under MS-Windows, provided you have the .Net framework. If you regularly update your computer, you should already have it. Anyway, you can download it from Microsoft and install it.

A sample log file is included in the sampledata/ directory, if you want to test the software.

This software is released under the GNU General Public Licence (GPL).

Copyright (C) belongs to Jean-Etienne Poirrier, 2006-2016. You can contact me at jepoirrier "at" gmail.com.Please report if you have any problem, comment or if you would like new features in this software.

## Usage

The software is so simple that there should be no problem to use it ... When you launch it, open an AWF file and it will give you the results.

To copy or save the plot, just right-clic on it. With this contextual menu, you'll also be able to print it, to zoom/un-zoom and to show point values.
