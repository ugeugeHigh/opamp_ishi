# 参加イベント
https://ishi-kai.org/openmpw/shuttle/ptc06/2025/06/14/shuttle_ISHI-Kai_OpenMPW-PTC06-2_OPAMP_Team.html
# 感想

前回Inverterを作ってみようの会に参加し、次のステップとしてOPAMPのグループワークに参加させていただきました。  
KiCad等で回路設計して基板を作るところまではよくやりますが、ICチップの中身を作れるというのはワクワクしますよね！  
このような機会を頂きありがとうございます！

大学・大学院ではグラフェンデバイスを作ったり、液体ヘリウム温度下でデバイス物性の評価などをしていていましたが、  
思い返すとOPAMPについてしっかり勉強したことが無くて、中々理解するのがハードでした。まだ理解が追いついていない部分が結構あります。

またレイアウトを作る部分はかなり苦戦しました。
チームの皆様に助けて頂きながら、なんとかgdsファイルをつくることができました。ありがとうございました！

低電流源回路部分はMaehashiさんの回路を使わせて頂きました。

# 回路全体

![回路全体](img/opamp_cs_full_sch.png)
# 低電流源回路部分
電源部分はMaehashiさんに作って頂きました。ありがとうございます。
https://github.com/YuMaehashi/ISHI-KAI/tree/main/PTC06/202508_OPAMP
![低電流源回路部分](img/VthRef.png)
# テスト回路
![テスト回路](img/2stage_pc_ac_3.png)
![解析結果](img/opamp_cs_full_sch_analyze.png)
# レイアウト
![レイアウト](img/opamp_full.gds.png)
