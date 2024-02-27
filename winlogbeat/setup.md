Cài đặt cho client: 

Cài đặt Sysmon: 

Giải nén Sysmon và chép vào Program Files. 
![image](https://github.com/Veruk45/ELK/assets/95947239/6e50700d-0d70-4e6c-bc9b-e4e384b7d178)

Vào folder Sysmon và cài đặt sử dụng cmd (Administrator): 

Sysmon64.exe -accepteula -i 

Cài đặt winlogbeat và metricbeat 

Giải nén, đổi tên folder thành winlogbeat và metricbeat 

Cấu hình file winlogbeat.yml

Chạy lệnh sau trong powershell với quyền admin: 

Set-ExecutionPolicy unrestricted 

Chay script install với quyền admin. 
![image](https://github.com/Veruk45/ELK/assets/95947239/9a8794ab-b83e-4bb4-819e-0f4bc24d707f)
