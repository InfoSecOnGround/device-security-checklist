 # 💻電腦篇

- [x] 1. 較新嘅系統如 Windows 7 以後（Home 版可能無）及 OS X Lion 10.7 之後都內置全碟加密功能，但大部分都要手動啟用。一定要啟用。
  💡 Windows 用 BitLocker。無 TPM 嘅都可以用，建議用 password 解 Bitlocker 鎖，用藍牙等裝置解鎖可信性存疑。
  💡 Mac OS X 用 File Vault 2
  💡 其他可以用 VeraCrypt 整個 encrypted volume

- [x] 2. 無全碟加密、尤其係 system drive 嘅系統，基本上可以認定為唔安全。Physically 接觸到部機嘅基本上可以拎到資料甚至密碼。

- [x] 3. 啟用 BIOS/UEFI admin password。停用 USB/CD boot。唔建議 dual boot。
  💡 Mac OS X 可以著 firmware password
  💡 BIOS/UEFI admin password / firmware password 並非牢不可破。

- [x] 4. 用強密碼！強密碼！強密碼！強密碼！強密碼！強密碼！要夠長！諗唔到記唔到就用你原本用緊較弱嘅密碼，加長佢。強度需求由高至低：Bitlocker解鎖密碼、登入密碼、BIOS密碼，最好每個密碼都唔同，記唔到咁多密碼就起碼加少少變化。
  💡 定期使用密碼係幫助記憶密碼嘅最好方法。
  💡 唔建議將密碼儲存喺 browser 或其他文件。真係有困難可以考慮用信得過嘅 password manager。

- [x] 5. 出街前記得將無人看管或唔用嘅裝置關機。重要！
💡 唔好用 sleep mode / 睡眠模式。唔好用 sleep mode / 睡眠模式。唔好用 sleep mode / 睡眠模式。唔好用 sleep mode / 睡眠模式。唔好用 sleep mode / 睡眠模式。
  💡 Hibernate mode 不完美可接受。

- [x] 6. 更新應用程式同系統到最新版本。無必要嘅 app 就避免喇。

- [x] 7. 留意 backup 用嘅裝置如果帶敏感資料，都要用原本資料同一層次嘅措施保護。
  💡 USB/lightening drive 等外置裝置都可以用第1點提到嘅類似技術加密。
  💡 Time machine 以及部分 NAS 可以加密儲存裝置。

- [x] 8. 緊急情況可以考慮直接斷電。

- [x] 9. 舊嘅裝置經過安全方法洗機後，可以保存作煙幕或棄掉。只係用合理方法盡力刪除嘅，用物理方法處理咗佢啦。