# Workspaces

Script(s) to trawl through a folder to identify data and code/scripts for capture with asset collections (COMPS) and source control (Git).

* Consider .idmconfig to hold information for the tool:
    * Source code (e.g. "source"/"code"/"scripts")
    * Data (e.g. "data")
    * Identity for Asset Manager (COMPS)
    * Identity for Git (GitHub)
    
* Consider .idmignore to hold information about directories and files which should be ignored, e.g.
    * "env" or "venv" for virtual environments
