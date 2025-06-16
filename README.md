# Computer_Organization_Final_Project_112502548
`quicksort` 的 array size 只有 100000，但作業規定 L3 cache size 設為 1MB，導致 `Q3` 和 `Q4` 的結果不管是 2-way、full-way、LRU、FBRP 的 miss rate 都相同（L3 cache size太大），所以 `Q3` 和 `Q4` 的輸出我有另外設置 L3 cache size 為 256 kB 的輸出結果。


## 檔案路徑

- `commands`: 各題使用的指令與常用指令

- `modified_code/`: 資料夾內為所有有修改 code 的檔案

- `log/Q2/`: 第二題的 log
  - `gem5_stats.txt`: gem5 m5out的stats
  - `nvmain_log`: 終端機輸出內容

- `log/Q3/`: 第三題的 log
  - `L3_1MB`: L3 cache size 設為 1MB 的輸出結果
    - `2way_gem5_stats.txt`: 2-way gem5 m5out的stats
    - `2way_nvmain_log`: 2-way 終端機輸出內容
    - `fullway_gem5_stats.txt`: full-way gem5 m5out的stats
    - `fullway_nvmain_log`: full-way 終端機輸出內容

  - `L3_256kB`: L3 cache size 設為 256kB 的輸出結果
    - `2way_gem5_stats.txt`: 2-way gem5 m5out的stats
    - `2way_nvmain_log`: 2-way 終端機輸出內容
    - `fullway_gem5_stats.txt`: full-way gem5 m5out的stats
    - `fullway_nvmain_log`: full-way 終端機輸出內容
  
- `log/Q4/`: 第四題的 log
  - `L3_1MB`: L3 cache size 設為 1MB 的輸出結果
    - `FBRP_gem5_stats.txt`: FBRP gem5 m5out的stats
    - `FBRP_nvmain_log`: FBRP 終端機輸出內容
    - `LRU_gem5_stats.txt`: LRU gem5 m5out的stats
    - `LRU_nvmain_log`: LRU 終端機輸出內容

  - `L3_256kB`: L3 cache size 設為 256kB 的輸出結果
    - `FBRP_gem5_stats.txt`: FBRP gem5 m5out的stats
    - `FBRP_nvmain_log`: FBRP 終端機輸出內容
    - `LRU_gem5_stats.txt`: LRU gem5 m5out的stats
    - `LRU_nvmain_log`: LRU 終端機輸出內容

- `log/Q5/`: 第五題的 log
  - `writeback_gem5_stats.txt`: writeback gem5 m5out的stats
  - `writeback_nvmain_log`: writeback 終端機輸出內容
  - `writethrough_gem5_stats.txt`: writethrough gem5 m5out的stats
  - `writethrough_nvmain_log`: writethrough 終端機輸出內容
