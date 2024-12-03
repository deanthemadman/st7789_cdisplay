# st7789_cdisplay

'git clone https://github.com/deanthemadman/st7789_cdisplay.git'

'cd st7789_cdisplay'

'sudo apt install libatlas-base-dev libgif-dev python3-venv python3-pip'

'mv display.servive /etc/systemd/system/display.servive'

'python3 -m venv venv && source venv/bin/activate'

'pip3 install -r requirments.txt'

'deactivate'

'sudo systemctl Enable display.servive'

'sudo systemctl start display.service'
