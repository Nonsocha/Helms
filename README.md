# INTRODUCTION TO HELM CHART
### Deploying a Web Application Using Helms in Kubernates
### Prerequisites
* Kubernate setup (Minikube,kind,or a cloud service like GKE,EKS AND AKS)
* Git repository
* Basic kubernstes understanding (pods,Deployment and service)
* Jenkins server
* Docker installed
## Step 1: Install helm
## For Linus and macOsUsers
1. **Open your vscode**
   * Run Vscode as an administrator
   * Access CLI by opening the terminal
  ![first](./image/capture 1/PENG)
2. **Download Helm**
     * For linux use **curl** to download helm

       ```
       curl -L https://get.helm.sh/helm-v3.5.0-linux-amd64.tar.gz -o helm.tar.gz
      ```

      * For macOS use **curl** to download Helm :

          ```
             curl -L https://get.helm.sh/helm-v3.5.0-darwin-amd64.tar.gz -o helm.tar.gz
           ``` 
3.  **Extract The Downloaded File**

     ```
         tar -zxvf helm.tar.gz
      ```

4.  **Move the Helm Binary**
          * For linux

            ```
                mv linux-amd64/helm /usr/local/bin/helm
             ```
           * For macOS:

              ```
                 mv darwin-amd64/helm /usr/local/bin/helm
              ```
  5. **Verify installation**

        ```
        helm version
       ```    
 6. **Clean Up**

        ```
           rm helm.tar.gz && rm -r *-amd64
         ```
            
      
## For Windows:
  1. **Open Vscode**
       * Run vscode as administrator
       *Access Cli by opening the terminal
  2. **install helm**
      * install helm using **chocolatey**

        ```
          choco install kubernetes-helm
         ```
  3. **verify installation**
      * In poweshell or command prompt,run

        ```
          helm version
        ```
        
