Cài đặt cho client: 
Giải nén Sysmon và chép vào Program Files. 
![image](https://github.com/Veruk45/ELK/assets/95947239/6e50700d-0d70-4e6c-bc9b-e4e384b7d178)

Vào folder Sysmon và cài đặt hoac sử dụng cmd (Administrator): 
- Sysmon64.exe -accepteula -i 

Cài đặt winlogbeat 
Cấu hình file winlogbeat.yml
- mở powershell
- powershell.exe -ExecutionPolicy UnRestricted -File .\install-service-winlogbeat.ps1
- .\winlogbeat.exe -e test config
check error:
- .\winlogbeat.exe -c winlogbeat.yml -e -d "*"
- Start-Service winlogbeat
