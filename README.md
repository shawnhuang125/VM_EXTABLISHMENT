# VM_EXTABLISHMENT
## Kali Linux [Video Link](https://youtu.be/4ra5UcO6GlQ)
### 步驟 1：下載 VirtualBox 和 Kali Linux ISO
- 下載 VirtualBox：
- 前往 VirtualBox 官方網站 
- 下載 Kali Linux ISO：
- 前往 Kali Linux 官方網站 下載 Kali Linux 的 ISO 檔案。
- 選擇 Installer 映像來進行完整安裝。
### 步驟 2：安裝 VirtualBox 並創建虛擬機
- 打開 VirtualBox：安裝完成後，啟動 VirtualBox。
- 創建新虛擬機：
- 點擊 “新建” (New) 按鈕來創建新的虛擬機。
- 為虛擬機命名（如 “Kali Linux”），系統類型選擇 “Linux”，版本選擇 “Debian (64-bit)”（Kali 是基於 Debian 的發行版）。
- ![image](https://github.com/user-attachments/assets/202c03cb-0e36-413b-b54c-9345b31c4201)
- 點擊 “下一步” (Next)。
- 配置虛擬機的資源：
- **記憶體建議配置**
- 輕度使用（基本工具、日常操作）：2 GB 記憶體。
- 中度使用（多任務或多工具並行運行）：4 GB 記憶體。
- 重度使用（資源密集型操作、大型數據集分析）：6-8 GB 或更多記憶體。
- **CPU核心數配置**
- 輕度使用（如基本的網絡測試、日常操作）：分配 1-2 核心 就足夠。
- 中度使用（如運行多個安全工具或進行中等規模的滲透測試）：建議分配 2-4 核心。
- 重度使用（如模擬大量的網絡流量或運行資源密集型的分析工具）：可以考慮分配 4 核或更多。
- ![image](https://github.com/user-attachments/assets/ffc43846-8223-4d1f-af52-65b5565d5d39)
- 點擊 “下一步” (Next)。
- 創建虛擬硬盤：
- 選擇 “現在創建虛擬硬盤” (Create a virtual hard disk now)，然後點擊 “創建” (Create)。
- 硬盤檔案類型：選擇 “VDI (VirtualBox Disk Image)”。
- 存儲方式：選擇 “動態分配” (Dynamically allocated)，這樣硬盤檔案會根據需要動態增長。
- 大小：設定虛擬硬盤大小，至少設定 20GB。如果需要更多空間，可以設置更大。
- 完成創建：點擊 “創建” (Create) 完成虛擬機的創建。
- ![image](https://github.com/user-attachments/assets/1d2c4192-1b23-4c47-8b7d-3104f4b351eb)
### 步驟 3：配置 Kali Linux ISO
- 選擇啟動磁碟：
- 在 VirtualBox 主界面中，選擇剛創建的虛擬機，然後點擊 “設定” (Settings)。
- 在 “存儲” (Storage) 部分，點擊 “空的” (Empty) 光碟圖示，然後點擊右側的光碟圖示來選擇一個虛擬光碟文件。
- 選擇之前下載的 Kali Linux ISO 檔案。
- 調整啟動順序（可選）：
- 在 “系統” (System) > “主機板” (Motherboard) 中，確保光碟啟動優先於硬盤。
### 步驟 4：
- 啟動虛擬機：
- 返回 VirtualBox 主界面，選擇 Kali Linux 虛擬機，然後點擊 “啟動” (Start) 按鈕。
- 虛擬機將從選定的 Kali Linux ISO 檔案啟動。
- 選擇安裝模式：
- 在 Kali Linux 的啟動選單中，選擇 “Graphical Install” 或 “Install” 來開始安裝過程。
- 安裝 Kali Linux：
- 根據提示完成安裝過程，包括選擇語言、時區、鍵盤配置、設置用戶和密碼、分區硬盤等。
- ![image](https://github.com/user-attachments/assets/d40c4928-b0ea-4f1f-b3cb-96a9d107ea2b)
- 當安裝程序提示選擇硬盤分區時，您可以選擇 “引導使用整個磁碟” 來自動分區。
- ![image](https://github.com/user-attachments/assets/03b0c032-c492-40a1-87c8-289e44464d9a)
- 完成安裝後，系統將提示重新啟動虛擬機。
- 移除 ISO：
- 在重新啟動虛擬機之前，進入 VirtualBox 的存儲設置，移除已附加的 Kali Linux ISO 檔案，不然虛擬機會再次從光碟啟動。
### 步驟 5：使用 Kali Linux 虛擬機
- 安裝完成後，虛擬機將啟動到 Kali Linux 的登入畫面，可以使用安裝過程中設置的用戶名和密碼登入。
- 登入後，就可以使用 Kali Linux。

