**Installing Kubernetes on ubuntu:**
1. Install snap 

   `sudo apt install snap -y`
   
2. Install microk8s using snap:

   `sudo snap install microk8s --classic`
   
3. Add alias for microk8s.kubectl command:

   `echo 'alias kubectl="microk8s.kubectl"' >> ~/.bashrc`
   
4. Add your username in mickrok8s group to avoid using sudo:

   `sudo usermod -aG microk8s rajp`
   
   
