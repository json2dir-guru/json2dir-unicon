# json2dir-unicon

json2dir in Unicon (Icon): reads a JSON document on stdin and creates the directory tree it describes in the current directory.

    unicon -s -o out/json2dir json2dir.icn && out/json2dir < document.json
