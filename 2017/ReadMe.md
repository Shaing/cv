![logo](./../img/innodisk_logo.png)
# 2017
> Joined STSD, Innodisk
- Software develop engineer, 01-12  
### Responsibilities
- 負責開發與維護工廠端生產軟體(內部使用)
- 開發自動化解決方案軟體
- 於開發端建立通用Library
- 版本控制

### Experience in the job
- 軟體開發環境建立
- 從無到有開發桌面應用程式(GUI / CLI)
- 跨作業系統開發: Windows7 / Ubuntu 16.04
- 資料結構,利用vertor及string不斷分析輸入資料,進行防錯與自動化判別.
- 平行處理,利用多執行緒同步執行多支Devices測試作業.
- Win32 API, CreateFile, DeviceIoControl.
- SQL語法, CRUD.
- 版本控制: trunk(master), branch, tag
- 單元測試, JUCE, CATCH2.
- Vendor command測試
- SATA/USB Disk測試
- 與MIS專案合作, 透過RESTFul API整合資料, 提供自動化解決方案

### Skills
- Programming language: C/C++
- Compiler: gcc/g++ / MSVC
- GUI: mfc / gtk3.0 / JUCE
- Version control: SVN / GIT
- DataBase: SQLite3, MariaDB

### Project list
Platform | Name | Skills | img
--- | --- | --- | ---
Win, Linux | iPacker | C, gtk3.0, SVN | ![ipk](./ipacker.PNG)
Win | QCheck | C++, JUCE, SVN, MariaDB | ![qc1](./qc.PNG) ![qc2](./qc1.PNG)
Win | SNBinding | C++, JUCE, SVN
Win | iSB | C++, JUCE, SVN
Win | iDIO | C++, MFC, SVN | ![dio1](./dio1.PNG)![dio2](./dio2.PNG)![dio3](./dio3.PNG)![dio4](./dio4.PNG)
Linux | FIO Wrapper test with GUI | C++, JUCE, GIT, SQLite3 | ![fio](./fio.PNG) ![fio1](./fio1.PNG)

### Library list
1. Fix	SATA	port	number（Windows）：判斷主機板的SATA	PORT位。	
2. Get	config	file（Windows）：讀取ini結構的文件。	
3. Get	web	api（Windows）：透過http取回JSON格式資料。	
4. Common	GUI（Windows）：工廠application共用介面。	
5. Device	R/W	function（Windows）：SSD讀寫功能及測速功能。	
6. Inno	vendor	command（Windows	/	Linux）：自家FW自訂的command，利用
windows	device	IO	control	API。	
7. Libipacker（Window	/	Linux）：將專案iPacker核心給lib化，可提供MPTOOL帶
有parse及pack的功能。	
8. Libqcheck（Window）：將專案QCheck核心給lib化，同樣提供MPTOOL及
RWTOOL可以直接整合前端資料進行檢測比對功能。	
9. LibinnoDio：將dio週邊卡的Library提供C++介面給開發者使用。	
10.	Libdm：Windows	device	management，可以取得電腦管理內的Device所有資訊。


