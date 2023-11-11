# Westcat-tripid

## Purpose
This script removes all underscores and alpha values from the every instance of trip_id.

## Usage
Tested with Python 3.9.<br>
```python westcat-tripid.py feed.zip```<br>
Adjusted files are exported to the current directory for human review, after which they can be manually added to the feed's .zip file.<br>
Alters trip_ids in trips.txt, runcut.txt, stop_times.txt, and frequencies.txt.<br>
