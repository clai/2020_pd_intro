#2020.07.06 - PD workshop 1



1. 下載 Pd-extended https://puredata.info/downloads/pd-extended

2. 圖像化的程式語言 Visual Programming Language 

3. Pd -> 聲音設計、互動設計  ；  Pd-gem -> 互動圖像

4. Put > 常用 pd 編碼類別

   | shortcut | type                         | 類別     |                                                         |
   | -------- | ---------------------------- | -------- | ------------------------------------------------------- |
   | ⌘1       | Object box                   | 物件     | loadbang, metro, trigger b f, <br />osc~ , line~, dac~, |
   | ⌘2       | Message (按）                | 訊息傳遞 | 1, 2, 3,<br />stop, dsp 1, bang, set, word              |
   | ⌘3       | Number box (按, 拖曳, 打字 ) | 數字     | 888, 1, 0                                               |
   | ⌘4       | Symbol box（按, 打字）       | 符號     | anyEngWord                                              |
   | ⌘5       | Comment                      | 註解     | 筆記和註解功能                                          |
   | ⇧⌘B      | Bang                         | 觸發     | ◙                                                       |
   | ⇧⌘T      | Toggle                       | 開/關    | ☒                                                       |
   | ⇧⌘V      | VSlider                      | 直向滑桿 |                                                         |
   | ⇧⌘H      | HSlider                      | 橫向滑桿 |                                                         |

5. Edit mode 編輯 狀態 

   ⌘E (command + E) 進入編輯狀態，再按一次，回到執行狀態

6. 2020.07.06 上課內容

   * 1_1 Objects ...
     * Object, Message, Number
     * Bang, Toggle
     * Slider
   * 1_2 Creating Sound
     * Object: osc~
     * Object: phasor~
     * Object: vline~
     * Object: noise~
   * 1_3 Additive Synth
     * Object: metro 
     * Object: random
   * 1_4_AM Synth (amplitude modulation)
     * Object: mtof (midi to freq)
     * Object: env~

