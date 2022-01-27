# MAG-B560M-MORTAR-WIFI-11700
<table>
  <tr>
    <td>處理器</td><td>Intel(R) Core(TM) i7-11700 處理器代號Rocket Lake</td>
  </tr>
  <tr>
    <td>主機板</td><td>MSI MAG B560M Mortar WiFi</td>
  </tr>
  <tr>
    <td>WiFi</td><td>內建Intel AX210 WiFi6E</td>
  </tr>
  <tr>
    <td>藍芽</td><td>內建Intel藍芽</td>
  </tr>
  <tr>  
    <td>記憶體</td><td>T-Force DDR4 3600 16GB*4</td>
  </tr>
  <tr>
    <td>顯示卡</td><td>MSI RX 6900XT 16GB</td>
  </tr>
  <tr>  
    <td>固態硬碟</td><td>Crucial P5 Plus 1TB</td>
  </tr>
  <tr>
    <td>系統</td><td>macOS Big Sur 11.6.2 + OpenCore 0.7.7</td>
  </tr>  
</table>
# 不支援處理器顯示晶片Intel® UHD750 
<br>2022/01/11 post

<a href=https://github.com/michelle0812/MAG-B560M-MORTAR-WIFI-11700/blob/main/EFI.zip target=new>Download EFI</a><br>
<img width="450" alt="截圖 2022-01-13 上午11 26 18" src="https://user-images.githubusercontent.com/79300809/149262713-9a9ad345-93f6-4e24-835a-c2b0dfb2cfaf.png">
<img width="450" alt="截圖 2022-01-13 上午11 52 44" src="https://user-images.githubusercontent.com/79300809/149262941-9b041ce0-7a45-4adb-89ba-160bf6409947.png"><br>

# hackintool-system and peripherals[點圖可再放大]<br>
<img width="450" alt="hackintool system 01" src="https://user-images.githubusercontent.com/79300809/149258037-fdbe9431-49c8-4f1b-928c-4df6fa2104af.png">
<img width="450" alt="hackintool system 02" src="https://user-images.githubusercontent.com/79300809/149258423-5caef908-1e94-4d15-9833-070c0fa45756.png"><br>

# hackintool-Extensions and USB[點圖可再放大]<br>
<img width="450" alt="截圖 2022-01-13 上午11 07 05" src="https://user-images.githubusercontent.com/79300809/149258967-805afac8-8121-4cd2-b565-6aba739d88b7.png">
<img width="450" alt="截圖 2022-01-13 上午11 07 25" src="https://user-images.githubusercontent.com/79300809/149259069-cae01829-e94e-4501-ba04-b56e3413c6c0.png"><br>

# USB、乙太網路[點圖可再放大]<br>
<img width="450" alt="截圖 2022-01-13 上午11 27 51" src="https://user-images.githubusercontent.com/79300809/149263692-2814b480-47de-4527-aca0-a52375d8ca42.png">
<img width="450" alt="截圖 2022-01-13 上午11 28 01" src="https://user-images.githubusercontent.com/79300809/149263704-0bfe8ea5-d17a-44ab-9b61-129af46e1050.png"><br>

# Wifi、藍芽[點圖可再放大]<br>
<img width="450" alt="截圖 2022-01-13 上午11 27 31" src="https://user-images.githubusercontent.com/79300809/149263719-8ba8ad1f-776f-47d4-8815-d5844aa2d9eb.png">
<img width="450" alt="截圖 2022-01-13 上午11 28 24" src="https://user-images.githubusercontent.com/79300809/149263734-690006b7-0713-48b4-b65c-b07232a1e4a1.png"><br>

# 顯示卡/顯示器[點圖可再放大]<br>
<img width="450" alt="截圖 2022-01-13 上午11 28 32" src="https://user-images.githubusercontent.com/79300809/149263764-69baeeee-37bb-40f7-b465-bf07dea19f5e.png"><br>
<p>

# 2022.01.26 update: 
音效卡 Realtek® ALC897 Codec<br>
boot-args加入 alcid=23，kernel加入AppleALC.kext [點圖可再放大]<br>
<img width="450" alt="截圖 2022-01-26 上午10 44 16" src="https://user-images.githubusercontent.com/79300809/151095420-bc5496ea-9585-4b4d-9b5d-e782b7b697e4.png">
<img width="450" alt="截圖 2022-01-26 上午10 44 23" src="https://user-images.githubusercontent.com/79300809/151095431-57d4d8bd-0606-4dc4-9439-010030d4cf31.png"><br>
<img width="450" alt="截圖 2022-01-26 上午8 02 09" src="https://user-images.githubusercontent.com/79300809/151080247-410f9c11-1042-45a2-8762-4a6da40dd173.png">
<img width="450" alt="截圖 2022-01-26 上午8 02 40" src="https://user-images.githubusercontent.com/79300809/151080256-0b3d3a78-4288-4c35-acf7-a478cec0707b.png"><br>
<img width="450" alt="截圖 2022-01-26 上午8 02 54" src="https://user-images.githubusercontent.com/79300809/151080259-759b70de-e0c3-4b95-b537-0a8ddf0aa6ad.png"><br>

# 因為檔案上傳限制25MB，原EFI.zip為28MB，移除AirportItlwm.kext後EFI.zip為13MB
wifi驅動請另行下載AirportItlwm.kext.zip
