# delete-node_modules
Delete node_modules folder when the path is too long in windows

### Usage
```sh
cd c:\my\project\path
mkdir empty_folder
robocopy empty_folder node_modules /purge
```

After do this is just delete node_modules and empty_folder that is empty now
