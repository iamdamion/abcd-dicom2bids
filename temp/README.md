# `temp` folder

This folder will contain all of the temporary files generated by the `abcd2bids.py` wrapper during its `unpack_and_setup` process. Those files will not be created until `abcd2bids.py` is run, and will be deleted once `abcd2bids.py` finishes — even if `abcd2bids.py` crashes. So, this folder should be empty unless `abcd2bids.py` is currently running.

If this folder is not empty and `abcd2bids.py` is not running, then feel free to delete any subdirectories of this folder, because they will likely take up a lot of space on your filesystem.