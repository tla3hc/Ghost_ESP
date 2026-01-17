This is the esp32 ghost esp code, I have a esp32 c5. Currently it use arduino to build. I want:
1. You read entire project, analyze the source code.
2. Currently, after I scan wifi, i use list function to return the scan result, it return really long list, now I want it to return setable list number of wifi with sorted most stongest wifi (eg. input scan 5 -> return 5 most strong (nearest) wifi) (default 15 ssid)
3. you run build.py build to check until it can be built successfully

**Note**: 
+ you need to run python build command to check if it can be compiled successfully.
+ the build command need to be inconsistent and simple so it can be auto appoved
+ you need to adjust the command handle_list to receive limit number and keep it backward compatible with the previous cmd