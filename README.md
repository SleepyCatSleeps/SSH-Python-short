# SSH-Python-short
#A short script to allow ssh connection between computers on a local network using rsync and port 22

import subprocess

print("a = roman, b = julius")
choice = input("What Device would you like to connect to for SSH file transfer? "
               "\n" "type a for roman"
               "\n" "type b for julius"
               "\n" ">" )
if choice == "a":
    print("You have selected roman at roman@000.000.00.0")
    subprocess.Popen(f"ssh roman@000.000.00.0 cmd", shell=True, stdout=subprocess.PIPE, 
                     stderr=subprocess.PIPE).communicate()
    cmd = ssh 
elif choice == "b":
    print("You have selected julius at julius@111.111.11.1")
    subprocess.Popen(["ssh julius at julius@111.111.11.1"])
else:
    print("incorrect selection please select one device from the list.")
