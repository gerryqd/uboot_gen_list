## REAMDE

### Usage

1. Make sure that you have built out the uboot successfully.

2. Put this script to a place, and make it available under the `PATH` env variable.

3. Enter to the uboot directory, execute below command

`find . -name "*.cmd" | xargs uboot_gen_list | sort | uniq > a.txt`

Then, `a.txt` contains the list.
