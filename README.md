# Get linux version
`lsb_release -a`

## List hidden files
`ls -l -a`

## Get disk space
`df -h`

# Change partition

Boot with the USB key and use `GParted` application : used partition are marked with keys, desactivate them and stop swap if necessary before changing them. When all is done, apply changes (green tick).

# Install batik sur Ubuntu (à tester)
`sudo apt-get update -y`
`sudo apt-get install -y libbatik-java`
