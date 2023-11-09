# Versions

## dwm

`6.4`

## st

`0.9`

## dmenu

`5.2`

# How to apply patches (dwm as an example)

## Clone this repo

`cd $DOWNLOAD_DIR && git clone git@h05t.xyz:x/sl.git`

## Copy patches

`cd $DWM_DIR && cp $DOWNLOAD_DIR/sl/dwm/*.diff .`

## Apply patches one-by-one (or make a bash script that will make it for you)

`cd $DWM_DIR && patch -p1 < $PATCH_NAME.diff`

# Notes

Not a single patch was written by me. All the patches were taken from suckless website.
