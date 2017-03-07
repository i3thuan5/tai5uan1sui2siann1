# 臺灣媠聲 Q&A
報告投影片：0306.pdf

記錄部份的回答

## 和工研院成品的差異？除了他們沒有open source外
```
是聖經發音人不明，沒有辦法補足缺的語料
沒辦法控制唸什麼
```

## 多錄2000句，效果差多少？可以列出5000、10000、15000、18000詞的效果分別是多少嗎？
```
沒辦法預估效果

Q&A當時心裡OS：我有時間評估，我整個專案都做一半了啦！！！！！
```
會後：語音評分需要非常非常多人工介入，不一定合效益
評估方法：
1. 播給使用者聽，叫他們把聽到的寫下來，看寫對幾%
2. 播合成和原本的錄音，各別評分
3. 播合成和原本的錄音，讓使用者選誰比較好聽

## 現在的問題可能是因為hmm模型合成，換deep模型不會進步太多嗎？
```
因為現在的語料是詞組的，詞組的語音尚可接受，
但語句的效果差，因為模型無法預估詞組間的停頓
所以要補足語句的音檔

我預期現在的問題是因為語料，而不是因為訓練模型
```
會後：
三个項目其實管的無仝
* 語料-發音準不準
* 音韻規則-發音對不對
* 訓練模型-發音自不自然

## 合成的結果要給誰用？英文這麼成熟也只用在siri、電梯、自動售票機
```
要做到完全像真人是有困難的
因為台語教育程度低落，所以大部份人會聽但不會讀、講
所以合成的結果可以讓聽得懂的人自學

除了表面上的功能
做語音合成，也可以改變社會上對台語的印象
原來台語這麼潮，也有這種技術
```

## google有做嗎？有機會跟google合作嗎？
```
google只有模型，語料和音韻規則還是要花時間做
```

## 其他問題
* 做台語語音的起源？
* 怎麼推廣對專案有興趣的人？
* 有考慮找志工嗎？
* 有考慮app嗎？
