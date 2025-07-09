## Terminal

`Install`

  - Terminal `Windows Store`
  - Powershell 7.4.x `Windows Store`
  - Warp Terminal 
    - https://www.warp.dev

`Chocolatey Install`

https://chocolatey.org/install

`Ejecutar en PowerShell como Administrador solo para instalar`

    ##### Use example: #####

    choco list

    choco search <package_name>

    choco upgrade -y <package_name>

    choco uninstall -y <package_name>

    choco install -y 7zip

- <package_name>
  - awscli

choco install -y awssamcli azure-cli Cmder dart-sdk flutter gh git glab Graphviz javadecompiler-gui opentofu python310 serverless sqlitestudio terraform transmission nvm vault Minikube k9s kubernetes-cli kubernetes-helm kubernetes-helmfile kubernetes-kops liberica8jre liberica8jdk liberica11jdk liberica17jdk maven gradle vagrant

choco install -y openjdk --version=21.0.2

choco install -y kotlinc --version=1.5.20

choco install -y golang --version=1.23.6

choco upgrade -y 7zip awscli awssamcli azure-cli chocolatey Cmder gh git glab graphviz javadecompiler-gui k9s kubernetes-cli kubernetes-helm kubernetes-helmfile kubernetes-kops Minikube opentofu serverless sqlitestudio terraform transmission vagrant vault

crc openshift-cli gcloudsdk

## Programming Languages

  - Python 3.10.x `Windows Store`

## Pip

### Checkov para seguridad en IaC

`Use example`

    pip install checkov    
    pip install -U checkov
    checkov -d . //<folder_path/project_name>

## WSL2 Ubuntu

  `wsl -s Ubuntu` (Set default WSL distro to Ubuntu)

  `sudo apt install -y`

    - zip
    - unzip 
    - curl

  `RedHat Openshift + Quarkus Ecosystem`

  - SDKMAN
    - https://sdkman.io/install
    - sdk install java 17.0.9-graalce
  - Source-to-image (S2I)
    - https://computingforgeeks.com/install-source-to-image-toolkit-on-linux/

## Vagrant

`Use example`

    vagrant plugin list    
    vagrant plugin install vagrant-vmware-desktop
    vagrant plugin update vagrant-vmware-desktop

    vagrant init bento/ubuntu-20.04

    vagrant up --provider=virtualbox db01 db02 // Multiple VMs
    vagrant up --provider=vmware_desktop
    vagrant up db01
    
    vagrant ssh db01

    vagrant suspend
    vagrant halt db01
    vagrant reload db01

    vagrant status
    vagrant global-status
    vagrant global-status --prune

    vagrant destroy db01

    vagrant box list
    vagrant box remove bento/ubuntu-20.04
    vagrant box remove --all bento/ubuntu-20.04
    vagrant box remove --provider=virtualbox bento/ubuntu-20.04
    vagrant box remove --provider=vmware_desktop bento/ubuntu-20.04

## Variables

`Java ... Maven ... Gradle ...`

> Sys

    JAVA_HOME: C:\Program Files\BellSoft\LibericaJDK-17
    MAVEN_HOME: C:\ProgramData\chocolatey\lib\maven\apache-maven-3.9.10
    GRADLE_HOME: C:\ProgramData\chocolatey\lib\gradle\tools\gradle-8.14.2

> Path

    %JAVA_HOME%\bin
    C:\Program Files\OpenJDK\jdk-21.0.2\bin
    C:\Program Files\BellSoft\LibericaJDK-11\bin 
    C:\Program Files\BellSoft\LibericaJDK-8\bin
    C:\Program Files\BellSoft\LibericaJRE-8\bin
    %MAVEN_HOME%\bin
    %GRADLE_HOME%\bin
    C:\tools\flutter\bin
    C:\tools\dart-sdk\bin

`Databases`

> Path

    C:\Program Files\MongoDB\Server\6.0\bin
    C:\Users\jorge\AppData\Local\Programs\mongosh
    C:\Program Files\PostgreSQL\16\bin
    C:\Program Files\MySQL\MySQL Server 8.4\bin

`GUI` -> [Pt. 2/2](GUI.md)

`Atrás` <- [README](README.md)