# Win11-Preformance-Fix
Execute the following instructions to restore virtual machine performance on win11
```
bcdedit /set hypervisorlaunchtype off
Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-Hypervisor 

powercfg /powerthrottling disable /path "C:\Program Files (x86)\VMware\VMware Workstation\x64\vmware-vmx.exe
```
