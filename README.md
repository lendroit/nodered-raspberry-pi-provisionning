# Provision NodeRed for raspberry-pi

- Install ansible-galaxy on your computer
- Add the target pi to the hosts
- Run `ansible-playbook playbook.yml -i ./hosts` on your computer
- Check that you have NodeRed on the raspberry pi, it is on the port 1880: http://192.168.0.11:1880 (replace by the ip of the raspberry)
- Reboot the pi and check again that NodeRed is instaled
