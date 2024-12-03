# st7789_cdisplay

Get the repository
```markdown
git clone https://github.com/deanthemadman/st7789_cdisplay.git
```

Move display.service to /etc/systemd/system
```markdown
mv display.servive /etc/systemd/system/display.servive
```

Sudo install required packages
```markdown
sudo apt install libatlas-base-dev libgif-dev python3-venv python3-pip
```

Create and activate virtual environment
```markdown
python3 -m venv venv && source venv/bin/activate
```

cd into the folder
```markdown
cd st7789_cdisplay
```

Install required python modules
```markdown
pip3 install -r requirments.txt
```

Deactivate virtual environment
```markdown
deactivate
```

Enable display.service
```markdown
sudo systemctl Enable display.servive
```

Start display.service
```markdown
sudo systemctl start display.service
```
