# GMailCleanUp
Some scripts to clean up my gmail

function delete_all_like_this() - this runs every hour or so. 
Tag one email from a particular sender with the label "Delete All"  and the script will pick it up when it runs (I have mine at 30 minutes). All emails from that sender will then be labeled as "DEL", to be trashed later by the function below.

function delete_all_marked() - runs every night and trashes all the threads marked as "Delete All".

This was done in about 30 mins so could probably have been more polished.
