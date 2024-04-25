It is used to convert qmk info.json to kle layout json file. 

Process of generate kle on your demand:
1. config keyboards_folder, which represents the absolute path of keyboards folder under qmk_firmware folder.
2. config kle_folder variable, which represents the absolute path of output folder. It can be anywhre you want.
3. run the script

OR:
1. create info_json_path variable manually, which points to the info.json which you want to convert. And invocate generate_kle_layout in REPL manually.
