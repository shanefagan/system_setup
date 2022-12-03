# system_setup

Some personal scripts I normally use across new installs. 

# Structure

## scripts
  - a setup script init_setup
  - a folder of scripts to copy into the usr/local/bin folder
  
init_setup does two things, copies the contents of local to the correct folder and sets up the attached systemd timers and service files

## systemd_files
Storing the files needed for setting up the services I want to run. 

# Current status
Auto update for both apt and flatpak (Snap updates automatically by default so not needed)
Keyboard sensitivity set/reset
