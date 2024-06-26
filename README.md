# SSH-Python-short
#A short script to allow ssh connection between computers on a local network using rsync and port 22

import subprocess

print("a = r, b = j")
choice = input("What device would you likr to connect to for SSH file transfer? "
          "\n" "type a for r"
          "\n" "type b for j"
          "\n" ">" )
if choice == "a":
  print(You have selected r at r@-MACip-")

elif choice == "b":
  print("You have selected j at j@-MACip-")

else:
  print("incorrect selection please select one device from the list.")
