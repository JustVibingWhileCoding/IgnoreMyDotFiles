# Ensure the kernel module for monitor communication loads at boot
      sudo sh -c 'echo "i2c-dev" > /etc/modules-load.d/i2c.conf'

# Add your user to the i2c group
      sudo usermod -aG i2c $USER