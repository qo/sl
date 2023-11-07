# How to apply patches

## Clone this repo

`cd $DOWNLOAD_DIR && git clone git@h05t.xyz:x/sl.git`

## Apply dwm patches

`cd $DWM_DIR && cp $DOWNLOAD_DIR/sl/dwm/*.diff . && git apply *.diff`

## Apply st patches

`cd $ST_DIR && cp $DOWNLOAD_DIR/sl/st/*.diff . && git apply *.diff`
