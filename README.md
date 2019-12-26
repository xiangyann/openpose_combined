JSON parser from: https://github.com/udp/json-parser
openpose from: https://github.com/CMU-Perceptual-Computing-Lab/openpose

編譯/Building
-
`gcc main.c json.c -lm`

使用方法/Usage
-
自行編譯openpose到家目錄<br >
把 test 移動或複製到 openpose 底下<br >
修改 main.c 來符合路徑<br >
編譯<br >
複製 run 底下的內容<br >
cd 到 openpose<br >
貼上指令<br >

待做事項/TODO
-
1. shell script 自動化<br >
2. 判別不同姿勢<br >
3. 移除hardcoded path