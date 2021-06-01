# Installation of Cilium on GKE
1. Install the latest version of the Cilium CLI on your local machine:
      ```
      curl -LO https://github.com/cilium/cilium-cli/releases/latest/download/cilium-linux-amd64.tar.gz
      sudo tar xzvfC cilium-linux-amd64.tar.gz /usr/local/bin
      rm cilium-linux-amd64.tar.gz
      ```
2.Create cluster on GKE

3.Intall Google CLoud SDK:

  Cloud SDK requires Python; supported versions are Python 3 (preferred, 3.5 to 3.8) and Python 2 (2.7.9 or higher)
  To check:
      
      python --version
      
4.  Download the Linux 64-bit archive file from your command-line, run:

       ```
       curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-342.0.0-linux-x86_64.tar.gz
      
For the 32-bit archive file, run:

      curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-342.0.0-linux-x86.tar.gz

 Extract:
      
      tar -xf google-cloud-sdk-342.0.0-linux-x86_64.tar.gz
 
 Remove: 
         
         rm google-cloud-sdk-342.0.0-linux-x86_64.tar.gz
      
      
