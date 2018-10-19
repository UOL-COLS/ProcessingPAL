# ProcessingPAL
Processing PAL has been developed by Charlotte Edwardson (University of Leicester and NIHR Leicester
BRC) and Shashidar Ette (University of Leicester).

Processing PAL is an application (Java) to process data collected from the activPAL device. 
This application uses the events.csv files. It uses a validated algorithm to isolate valid waking wear data
from everything else e.g., time in bed (which includes sleep), prolonged non-wear and invalid data
with no distinction made between these. This algorithm and its validation is described in detail here:

Elisabeth AH Winkler, Danielle H Bodicoat, Genevieve N Healy, Kishan Bakrania, Thomas Yates,
Neville Owen, David W Dunstan, Charlotte L Edwardson. Identifying adults’ valid waking wear time
by automated estimation in activPAL data collected with a 24 h wear protocol. Physiological
Measurement. 2016; 37:10.

The full text of the article can be access here: http://iopscience.iop.org/article/10.1088/0967-3334/37/10/1653/meta

Features of the Processing PAL application:
* Batch processing of events.csv files (note: works best with 250 files or less. Process in batches if
more than 250 files)
* Validated algorithm which isolates valid waking wear data from time in bed, prolonged nonwear
and invalid data
* Adaptable algorithm thresholds to determine waking wear data
* Adaptable wear time criteria e.g., hour constituting a valid day
* Visual representation of data identified by algorithm as ‘valid’ and ‘not valid’ (can save as
pdf)
* Allows corrections to the data if needed
* Auto-loading of previously saved corrections
* Auto-loading of previously processed data to enable the generation of new outputs without
having to reprocess the data
* Wide range of outputs:
    * Waking wear time
    * Sitting time
    * Standing time
    * Stepping time
    * Light stepping time
    * MVPA stepping time
    * Number of steps
    * Number of light steps
    * Number of MVPA steps
    * Number of transitions
    * Number of valid days
    * Number of sitting bouts
    * Number of standing bouts
    * Sitting bout ranges (user defined thresholds e.g., 0-30, 30-60, 60+)
    * Standing bout ranges (user defined thresholds)
    * Standing bout ranges (user defined thresholds)
    * MVPA bout ranges (user defined thresholds)
    * Day time ranges (user defined thresholds e.g., 9-12pm, 12-5pm)
    * Variable times of interest e.g., work times (can load diary times through csv sheet)
    * Hour by hour data for sitting, standing and stepping time
    * Weekdays and weekend days identified
