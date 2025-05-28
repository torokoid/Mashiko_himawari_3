# Mashiko_himawari_3

<html lang="ja">
 <head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 

<style type="text/css">

  p {
color: #fffafa;
font-size: 1.5em;
 }
<!--
 .red {color:#ff0000;}
 .grey {color:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}
 -->
	
 #preview{
	position: relative;
	border: 3px solid #333;
	background: #444;
	padding: 5px;
	display: none;
	color: #FFF;
	text-align: center;
}

@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}

#wrap {background:none} /*PC用の背景はオフ*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(https://torokoid.github.io/Mashiko_himawari_3/20230812_017.JPG) center/cover no-repeat; /*fixedをトル！*/
  -webkit-background-size:cover;/*Android4*/
  }


    <title>いいねボタン</title>

        .like-container {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            gap: 10px; /* ボタン間のスペース */
        }

        .like-item {
            display: flex;
            align-items: center;
        }

        .like-button {
            padding: 5px 10px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .like-button:hover {
            background-color: #0056b3;
        }

        .like-count {
            margin-left: 10px;
        }

</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">
 
</head>
<body>

<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>

<div style="background-color:rgb(255,255,255,0.5);">
<p class="topicpath"><a href="https://torokoid.github.io/mashiko_himawari/">2018年、2019年</a>><a href="https://torokoid.github.io/mashiko_himawari_2/">2021年</a>>2023年<br>><a href="https://torokoid.github.io/2024Jan_Thailand__7/">タイ植物園リンク</a><br>><a href="https://torokoid.github.io/2024_Sakura/" target="_blank">2024城址公園桜リンク</a><br>><a href="https://torokoid.github.io/2024_hitachi_kaihin/" target="_blank">2024/4/20ひたち海浜公園</a><br>><a href="https://torokoid.github.io/2024Apr_Maronie/" target="_blank">2024/4/27マロニエプラザ絵画展</a><br>><a href="https://torokoid.github.io/hagurosan/" target="_blank">ちょい古&マニアック、羽黒山から無線した記録</a><br>><a href="https://torokoid.github.io/mt_fuji/" target="_blank">2023年12月の富士山</a><br>><a href="https://torokoid.github.io/hagurosan2/" target="_blank">2022年4月、羽黒山のツツジ</a><br>><a href="https://torokoid.github.io/2024May_tanboref/" target="_blank">2024年5月、年に一度の田植え時期に見える、田んぼリフレクション</a><br>><a href="https://torokoid.github.io/kodomonomori/" target="_blank">宇都宮郊外の意外な穴場スポット「こどものもり公園」</a><br>><a href="https://torokoid.github.io/park-s-flower/" target="_blank">宇都宮市内、公園のお花が満開</a><br>><a href="https://twitter.com/sajyan" target="_blank">Xアカウントリンク、ほぼ毎日更新中</a><br>><a href="https://torokoid.github.io/2024May25_kenmin/" target="_blank">県民の森にバイクでお出かけ</a>><a href="https://torokoid.github.io/2024May_Kenmin_forest/" target="_blank">実は前の週にも県民の森</a><br>><a href="https://torokoid.github.io/20240526_HF_ant/" target="_blank">超マニアック、アマチュア無線のアンテナの話</a><br>><a href="https://torokoid.github.io/20240622_flower/" target="_blank">梅雨入り直前のお花たちを集めました</a><br>><a href="https://torokoid.github.io/20240630_flower/" target="_blank">梅雨時のしっとりしたお花たちです</a><br>><a href="https://torokoid.github.io/2023_thailand/" target="_blank">2023年、タイの日常風景</a><br>><a href="https://torokoid.github.io/2024Jul_tatekae/" target="_blank">2024年7月、お隣の家が建て替えで取り壊し</a><br>><a href="https://torokoid.github.io/2024_paris11/" target="_blank">2024年8月、高校の同級生（Bruce君）が訪れたフランスの写真集</a><br>><a href="https://torokoid.github.io/Mashiko_himawari_4/" target="_blank">2024年8月10日、益子ひまわり祭り写真集</a><br>><a href="https://torokoid.github.io/20240817_hagurosan/" target="_blank">2024年8月17日、羽黒山にお詣りと関東平野一望</a><br>><a href="https://torokoid.github.io/2023_thailand/" target="_blank">2024年8月31日、42年間勤めたHondaを無事退職</a><br>><a href="https://torokoid.github.io/after_911/" target="_blank">NHK9.11特集番組より、2001年9月11日アメリカ同時多発テロの直後に起こった出来事</a><br>><a href="https://torokoid.github.io/2024Aug_tatekae3/" target="_blank">2024年8月23日、お隣の敷地が地鎮祭〜新築工事</a><br>><a href="https://torokoid.github.io/20240930_hagurosan/" target="_blank">2024年9月30日、彼岸花の季節に羽黒山</a><br>><a href="https://torokoid.github.io/20241003_cluster/" target="_blank">2024年10月3日、メタバース空間のcluster主催者からCluster Acceleratorに推薦されたとの連絡！</a><br>><a href="https://torokoid.github.io/20241004_fukuwauchi/" target="_blank">2024年10月4日、定年退職１ヶ月後に旧職場のメンバーが飲み会を開催してくれました！</a><br>><a href="https://torokoid.github.io/2024Oct14_cosmos/" target="_blank">2024年10月14日、鬼怒川グリーンパークのコスモスが綺麗！</a><br>><a href="https://torokoid.github.io/2024Oct23_85Kenyuukai/" target="_blank">2024年10月23日、銀座散策と品川から屋形船あそび！</a><br>><a href="https://torokoid.github.io/20241103_Ibaraki_bike/" target="_blank">2024年11月3日、バイクツーリング、背景画像の３台目は女性ライダー！</a><br>><a href="https://torokoid.github.io/20241116_ClusteMBG-6-/" target="_blank">2024年11月16日、メタバース内で開催された音楽イベント。マイティヤさんの曲はTVで放送できるレベル！</a><br>><a href="https://torokoid.github.io/20241118_hagurosan/" target="_blank">2024年11月18日、20日のタイ旅行に先立ち、羽黒山神社で安全祈願！</a><br><br>><a href="https://torokoid.github.io/20241120-20250311_Thailand/" target="_blank">2024年11月20日~2025年3月11日、タイの旅、まとめ！</a></p></div>

<!--
><a href="https://torokoid.github.io/20241120_bangkok/" target="_blank">2024年11月20日、宇都宮からマロニエバスで成田に移動、バンコクから北部チェンライまでの旅！</a><br>><a href="https://torokoid.github.io/20241129_KunFhone_Wedding/" target="_blank">2024年11月29日、ドイツ人男性と現地人女性の結婚式に出席</a><br>><a href="https://torokoid.github.io/20241130_chiangrai/" target="_blank">2024年11月30日 、チェンライ近郊にスイミングプール見つけました</a><br>><a href="https://torokoid.github.io/20241202_chiangrai/" target="_blank">2024/11/29〜12/02 、チェンライ近郊の散策状況</a><br>><a href="https://torokoid.github.io/20241204_chiangrai/" target="_blank">2024/12/03〜12/04 、チェンライで過ごす日々のまとめ</a><br>><a href="https://torokoid.github.io/20241207_chiangrai/" target="_blank">2024/12/05〜12/07 、チェンライ周辺のお花などまとめました</a><br>><a href="https://torokoid.github.io/20241209_chiangrai/" target="_blank">2024/12/08〜12/09 、チェンライ、日常の一コマ</a><br>><a href="https://torokoid.github.io/20241210_chiangrai/" target="_blank">2024/12/10 、チェンライ郊外、メーチャン、チャンチャワー町の市場</a><br>><a href="https://torokoid.github.io/20241213_chiangrai/" target="_blank">2024/12/13 、メーチャン中心部で毎週金曜日に開催される巨大市場</a><br>><a href="https://torokoid.github.io/20241215_chiangrai/" target="_blank">2024/12/15 、メーチャン市街から西に5分ほど行ったところにあるパトゥーン温泉</a><br>><a href="https://torokoid.github.io/20241216_chiangrai/" target="_blank">2024/12/16 、チェンライ近郊の大規模ショッピングモールを２店はしご</a><br>><a href="https://torokoid.github.io/20241219_chiangrai/" target="_blank">2024/12/19 、タイ渡航５週目になったのを機に、４週目までのお花画像まとめ</a><br>><a href="https://torokoid.github.io/20241220_chiangrai/" target="_blank">2024/12/20 、収穫されたカカオの実を天日干しなど</a><br>><a href="https://torokoid.github.io/20241223_chiangrai/" target="_blank">2024/12/23 、南国の夕焼け空と入道雲を集めました(30Dec:グラデーションが綺麗に見えるように画像解像度をアップ)</a><br>><a href="https://torokoid.github.io/20241224_chiangrai/" target="_blank">2024/12/24 、日本とは違うタイの特徴的なところを何点かまとめました</a><br>><a href="https://torokoid.github.io/20241226_chiangrai/" target="_blank">2024/12/26 、地方のごく一般的な集落で、年に一回開催されるローカルなお祭り</a><br>><a href="https://torokoid.github.io/20241227_chiangrai/" target="_blank">2024/12/27 、タイ北部の植物園を観光</a><br>><a href="https://torokoid.github.io/20241227_chiangrai_home/" target="_blank">2024/12/27お昼 、タイ地方都市の一般的なご家庭を訪問</a><br>><a href="https://torokoid.github.io/20241230_chiangrai/" target="_blank">2024/12/30 、さすがタイ、プール付きのレストランがありました</a><br>><a href="https://torokoid.github.io/20241231_chiangrai/" target="_blank">2024/12/31 、大晦日に、やや細かい現地情報</a><br>><a href="https://torokoid.github.io/20250101_chiangrai/" target="_blank">2025/01/01 、年末からお正月にかけてのタイのお空は賑やか！</a><br>><a href="https://torokoid.github.io/20250102_chiangrai/" target="_blank">2025/01/02 、タイのお正月は1日で終わり、2日は以前天日干しにしたカカオを収穫！</a><br>><a href="https://torokoid.github.io/20250103_chiangrai/" target="_blank">2025/01/03 、庭木に咲いたお花の蜜集めで蝶々と蜜蜂が集まりました</a><br>><a href="https://torokoid.github.io/20250104_chiangrai/" target="_blank">2025/01/04 、この時期の綺麗な夕暮れグラデーションなど</a><br>><a href="https://torokoid.github.io/20250105_chiangrai/" target="_blank">2025/01/05 、庭の鶏にヒナがかえって総勢20羽の子育てがスタート</a><br>><a href="https://torokoid.github.io/20250106_chiangrai/" target="_blank">2025/01/06 、ニワトリの大家族をかごから引っ越しする小屋の建築</a><br>><a href="https://torokoid.github.io/20250107_chiangrai/" target="_blank">2025/01/07 、仏教国タイの特徴的な部分をピックアップ</a><br>><a href="https://torokoid.github.io/20250108_chiangrai/" target="_blank">2025/01/08 、大学校内の道路を使った毎週水曜開催の市場を訪問</a><br>><a href="https://torokoid.github.io/20250109_chiangrai/" target="_blank">2025/01/09 、ショッピングモールで地域振興のイベントを見学</a><br>><a href="https://torokoid.github.io/20250110_chiangrai/" target="_blank">2025/01/10 、ショッピングモール内、スーパーや周辺の状況など</a><br>><a href="https://torokoid.github.io/20250111_chiangrai/" target="_blank">2025/01/11 、寒くなったので温泉、施設の噴水に虹がかかりました</a><br>><a href="https://torokoid.github.io/20250112_chiangrai/" target="_blank">2025/01/12 、どこにも出かけなかったので身の回りの画像集</a><br>><a href="https://torokoid.github.io/20250113_chiangrai/" target="_blank">2025/01/13 、VISA延長の手続きで町役場と入管を奔走</a><br>><a href="https://torokoid.github.io/20250114_chiangrai/" target="_blank">2025/01/14 、知り合いのお宅でお昼をいただきました</a><br>><a href="https://torokoid.github.io/20250115_chiangrai/" target="_blank">2025/01/15 、2日連続の手作り料理、その後は足湯でまったり</a><br>><a href="https://torokoid.github.io/20250116_chiangrai/" target="_blank">2025/01/16 、子供の相手したりお花眺めてたら、今日もお昼あるよ！と電話</a><br>><a href="https://torokoid.github.io/20250117_chiangrai/" target="_blank">2025/01/17 、朝のお月様から夜にかけての満天の星空まで</a><br>><a href="https://torokoid.github.io/20250118_chiangrai/" target="_blank">2025/01/18 、10日ぶりのプール、朝の月は欠けてゆき、夜には満天の星空</a><br>><a href="https://torokoid.github.io/20250119_chiangrai/" target="_blank">2025/01/19 、じゃれつく猫から、街の映像まで</a><br>><a href="https://torokoid.github.io/20250120_chiangrai/" target="_blank">2025/01/20 、タイにいるのに、Net遊び</a><br>><a href="https://torokoid.github.io/20250121_chiangrai/" target="_blank">2025/01/21 、いつもの平穏な1日かと思いきや・・・</a><br>><a href="https://torokoid.github.io/20250122_chiangrai/" target="_blank">2025/01/22 、平穏な1日、遺品のPC修理などして、最後は市場でお買い物</a><br>><a href="https://torokoid.github.io/20250123_chiangrai/" target="_blank">2025/01/23 、修理したPCで映画鑑賞して最後は満点の星空</a><br>><a href="https://torokoid.github.io/20250124_chiangrai/" target="_blank">2025/01/24 、先日亡くなった故人の散骨から夕焼けグラデーションまで</a><br>><a href="https://torokoid.github.io/20250125_chiangrai/" target="_blank">2025/01/25 、庭の鳥たちを眺めて、いつものプールへ、最後は夕焼けグラデーション</a><br>><a href="https://torokoid.github.io/20250126_chiangrai/" target="_blank">2025/01/26 、月はかなり細いので夜明け前に撮影、猫ちゃんシャンプーして最後は夕焼けグラデーション</a><br>><a href="https://torokoid.github.io/20250127_chiangrai/" target="_blank">2025/01/27 、朝から物干しキャリアの組み立て、一日中曇りでお花と動物のお世話で終了</a><br>><a href="https://torokoid.github.io/20250128_chiangrai/" target="_blank">2025/01/28 、朝焼けの空が復活、HPの改修依頼が舞い込みひと段落して庭のお花</a><br>><a href="https://torokoid.github.io/20250129_chiangrai/" target="_blank">2025/01/29 、朝は曇り空、お坊さんが5人も来て故人の供養、アヒルのヒナは無事家族に合流</a><br>><a href="https://torokoid.github.io/20250130_chiangrai/" target="_blank">2025/01/30 、日章旗のような朝日でスタート、アヒルのヒナを保護した後はプールと買い物</a><br>><a href="https://torokoid.github.io/20250131_chiangrai/" target="_blank">2025/01/31 、親戚にお昼をご馳走になり、日が暮れると細い月が綺麗</a><br>><a href="https://torokoid.github.io/20250201_chiangrai/" target="_blank">2025/02/01 、日の出前の空で夏の星座観察、いつもの大学でプールなど</a><br>><a href="https://torokoid.github.io/20250202_chiangrai/" target="_blank">2025/02/02 、日の出前の北斗七星から、親戚宅でお昼など</a><br>><a href="https://torokoid.github.io/20250203_chiangrai/" target="_blank">2025/02/03 、チェンマイから来たお客さんとお昼ご飯、その後はプール</a><br>><a href="https://torokoid.github.io/20250204_chiangrai/" target="_blank">2025/02/04 、夜明け前に星空撮ったらまた寝坊、最後は市場で買い出しして終了</a><br>><a href="https://torokoid.github.io/20250205_chiangrai/" target="_blank">2025/02/05 、雲の隙間から朝焼けの光、親戚宅でお昼をいただき役場で諸手続き</a><br>><a href="https://torokoid.github.io/20250206_chiangrai/" target="_blank">2025/02/06 、朝日の中で野鳥の鳴き声、メーチャンの街の同じ役場で昨日の続き</a><br>><a href="https://torokoid.github.io/20250207_chiangrai/" target="_blank">2025/02/07 、久々に朝焼けに間に合い、午後はいつものプールで最後は夕焼け</a><br>><a href="https://torokoid.github.io/20250208_chiangrai/" target="_blank">2025/02/08 、綺麗な朝焼けで始まり、ちびっ子のお相手と庭の鳥やお花で1日が暮れました</a><br>><a href="https://torokoid.github.io/20250209_chiangrai/" target="_blank">2025/02/09 、深夜の月撮影で始まり、いつもの親戚宅でお昼</a><br>><a href="https://torokoid.github.io/20250210_chiangrai/" target="_blank">2025/02/10 、ChiangRai ChiangMaiの片道4時間を往復<marquee behavior="left">02/10記事に画像説明文字追記(15Feb)</marquee></a><br>><a href="https://torokoid.github.io/20250211_chiangrai/" target="_blank">2025/02/11 、VISAの延長でラオスに越境</a><br>><a href="https://torokoid.github.io/20250212_chiangrai/" target="_blank">2025/02/12 、ラオス滞在2日目、朝からお寺のイベントを見学</a><br>><a href="https://torokoid.github.io/20250213_chiangrai/" target="_blank">2025/02/13 、ラオスに２泊してタイに戻ると、VISAが２ヶ月と10日延長されました</a><br>><a href="https://torokoid.github.io/20250214_chiangrai/" target="_blank">2025/02/14 、メーチャンの朝焼けからいつものプール、最後は夕焼け</a><br>><a href="https://torokoid.github.io/20250215_chiangrai/" target="_blank">2025/02/15 、久々のプールで疲れて起きられず、ゆっくりしてたらチョコメーカーのテイスターで味見</a><br>><a href="https://torokoid.github.io/20250216_chiangrai/" target="_blank">2025/02/16 、メーチャンでの日常が再開、近所を徒歩で散策しました</a><br>><a href="https://torokoid.github.io/20250217_chiangrai/" target="_blank">2025/02/17 、平凡な日常の中で、自動水やり器の作成。夕暮れは久々の紫グラデーション</a><br>><a href="https://torokoid.github.io/20250218_chiangrai/" target="_blank">2025/02/18 、買い物していつものプール、火曜木曜、限定開催の市場で尼僧さん目撃</a><br>><a href="https://torokoid.github.io/20250219_chiangrai/" target="_blank">2025/02/19 、メーチャンの街中でバイク観察、夕焼けはオレンジでした。最後はネットクリエータ「まいてゃ」さんの曲</a><br>><a href="https://torokoid.github.io/20250220_chiangrai/" target="_blank">2025/02/20 、夜明け前の星空撮影からご近所のお花、夕焼けは紫グラデーション</a><br>><a href="https://torokoid.github.io/20250221_chiangrai/" target="_blank">2025/02/21 、前日失敗した北極星の撮影から、道路工事と夕焼けグラデーション</a><br>><a href="https://torokoid.github.io/20250222_chiangrai/" target="_blank">2025/02/22 、ほとんどで歩かずにメタバースと無線で過ごす一日</a><br>><a href="https://torokoid.github.io/20250223_chiangrai/" target="_blank">2025/02/23 、扇風機修理して、プールの横でアスレチック</a><br>><a href="https://torokoid.github.io/20250224_chiangrai/" target="_blank">2025/02/24 、曇りがちな一日、メーチャンの街で役場など訪問</a><br>><a href="https://torokoid.github.io/20250225_chiangrai/" target="_blank">2025/02/25 、道路工事が一斉にスタート、市場で盲人に寄付してその後はショッピングモールに</a><br>><a href="https://torokoid.github.io/20250226_chiangrai/" target="_blank">2025/02/26 、満開の蘭からプールのサルビア、最後は夕焼けグラデーション</a><br>><a href="https://torokoid.github.io/20250227_chiangrai/" target="_blank">2025/02/27 、チェンライの街で山岳民族資料館を見学など</a><br>><a href="https://torokoid.github.io/20250228_chiangrai/" target="_blank">2025/02/28 、チェンライからバンコクに移動</a><br>><a href="https://torokoid.github.io/20250301_phattaya/" target="_blank">2025/03/01 、バンコクに一泊してパッタヤーに移動</a><br>><a href="https://torokoid.github.io/20250302_phattaya/" target="_blank">2025/03/02 、パタヤ2日目は市内のレストランとデザートのお店</a><br>><a href="https://torokoid.github.io/20250303_phattaya/" target="_blank">2025/03/03 、パタヤ3日目は知り合いたちと市内レストラン</a><br>><a href="https://torokoid.github.io/20250304_phattaya/" target="_blank">2025/03/04 、パタヤ4日目は宿泊場所の施設で遊びます</a><br>><a href="https://torokoid.github.io/20250305_phattaya/" target="_blank">2025/03/05 、パタヤ5日目は市内のショッピングモール</a><br>><a href="https://torokoid.github.io/20250306_phattaya/" target="_blank">2025/03/06 、パタヤからバンコクに移動して市内のショッピングモール</a><br>><a href="https://torokoid.github.io/20250307_bangkok/" target="_blank">2025/03/07 、バンコクのショッピングモールで音楽イベント</a><br>><a href="https://torokoid.github.io/20250308_bangkok/" target="_blank">2025/03/08 、2日続けて同じショッピングモール</a><br>><a href="https://torokoid.github.io/20250309_bangkok/" target="_blank">2025/03/09 、バンコク4日目は近所を散策</a><br>><a href="https://torokoid.github.io/20250310_bangkok/" target="_blank">2025/03/10 、バンコク5日目は深夜便で日本に帰国、お昼の12時過ぎに宇都宮着でした(タイ旅行シリーズは終了です)</a>-->


<h2><span class="yellow"><a href="https://torokoid.github.io/20241120-20250311_Thailand/" target="_blank">タイ旅行のリンクは別ページにまとめました(2025_03_15)</a></span></h2>

<div style="background-color:rgb(255,255,255,0.5);">
<p class="topicpath">
><a href="https://torokoid.github.io/20250312_16_tochigi/" target="_blank">2025年03月16日 、帰国後6日間の記録</a><br>><a href="https://torokoid.github.io/20250316_No10MGB/" target="_blank">2025年03月16日深夜 、帰国後早々メタバースのイベントに参加</a><br>><a href="https://torokoid.github.io/20250318_tochigi/" target="_blank">2025年03月18日 、無事に帰国出来たので、羽黒山神社にお礼参り</a><br>><a href="https://torokoid.github.io/20250320_tochigi/" target="_blank">2025年03月19-20日 、久しぶりの積雪、翌日は車の車検</a><br>><a href="https://torokoid.github.io/20250321_tochigi/" target="_blank">2025年03月20-21日 、ショッピングモールを日毎に切り替え</a><br>><a href="https://torokoid.github.io/20250323_tochigi/" target="_blank">2025年03月23日 、1日のスタートは吉野家の牛丼から</a><br>><a href="https://torokoid.github.io/20250325_tochigi/" target="_blank">2025年03月24-25日 、鬼怒グリーンパーク白沢エリアに早咲きの桜が一本</a><br>><a href="https://torokoid.github.io/20250327_tochigi/" target="_blank">2025年03月25-27日 、1日が平穏に暮れたと思いきや深夜帯に火事</a><br>><a href="https://torokoid.github.io/20250328_tochigi/" target="_blank">2025年03月27-28日 、ショッピングモールの造花の桜から鬼怒川土手の早咲の桜まで、最後は2年半ぶりの同期会でした</a><br>><a href="https://torokoid.github.io/20250331_tochigi/" target="_blank">2025年03月28-31日 、芳賀町観光イベントでアンケートに答えて商品に応募</a><br>><a href="https://torokoid.github.io/20250402_tochigi/" target="_blank">2025年03月31-04月01日 、天気がイマイチで近所のスーパーでお花ばかり撮影</a><br>><a href="https://torokoid.github.io/20250404_tochigi/" target="_blank">2025年04月02-04日 、ベルモールの続きから自宅で時計の電池交換など</a><br>><a href="https://torokoid.github.io/20250408_tochigi/" target="_blank">2025年04月04-08日 、FKDの夕暮れから鬼怒グリーンパークの桜など</a><br>><a href="https://torokoid.github.io/20250409_tochigi/" target="_blank">2025年04月09日 、宇都宮市内ブライダル衣装レンタル屋さんの駐車場では桜が満開</a><br>><a href="https://torokoid.github.io/20250410_tochigi/" target="_blank">2025年04月09-10日 、宇都宮北端、グリーンパーク白沢エリアでは桜が満開</a><br>><a href="https://torokoid.github.io/20250411_tochigi/" target="_blank">2025年04月11日 、宇都宮北端、白沢街道の一本桜が満開</a><br>><a href="https://torokoid.github.io/20250414_tochigi/" target="_blank">2025年04月12-14日 、宇都宮北端、この春最後の桜たち</a><br>><a href="https://torokoid.github.io/20250415_tochigi/" target="_blank">2025年04月15日 、お天気が不安定ですが、庭のお花など</a><br>><a href="https://torokoid.github.io/20250416_tochigi/" target="_blank">2025年04月16日 、図書館の裏の森でウグイスのさえずり</a><br>><a href="https://torokoid.github.io/20250418_tochigi/" target="_blank">2025年04月18日 、芝桜公園の芝桜が満開</a><br>><a href="https://torokoid.github.io/20250420_tochigi/" target="_blank">2025年04月20日 、町内の何気ない公園の花壇ではお花達が満開</a><br>><a href="https://torokoid.github.io/20250422_tochigi/" target="_blank">2025年04月22日 、桜はみんな葉桜になったかと思いきや、遅咲きの桜が満開</a><br>><a href="https://torokoid.github.io/20250424_tochigi/" target="_blank">2025年04月23-24日 、久しぶりのまとまった雨で庭のお花達はしっとり</a><br>><a href="https://torokoid.github.io/20250426_tochigi/" target="_blank">2025年04月25-26日 、大戸屋のお昼から、ベルモールの恐竜展、最後は健康診断</a><br>><a href="https://torokoid.github.io/20250427_tochigi/" target="_blank">2025年04月26-27日 、公園のお花達と図書館のつつじ</a><br>><a href="https://torokoid.github.io/20250429_tochigi/" target="_blank">2025年04月28-29日 、こじま電気のボックスティッシュから公園のお花と図書館のつつじ</a><br>><a href="https://torokoid.github.io/20250501_tochigi/" target="_blank">2025年04月29-05月01日 、朝の男体山から、図書館の側のゆうすい公園まで</a><br>><a href="https://torokoid.github.io/20250503_tochigi/" target="_blank">2025年05月01-03日 、SONGSで紹介されたさだまさしさんから、図書館のつつじまで</a><br>><a href="https://torokoid.github.io/20250504_tochigi/" target="_blank">2025年05月03日 、イルカさんの名曲からロマンチック村まで</a><br>><a href="https://torokoid.github.io/20250506_tochigi/" target="_blank">2025年05月04-05日 、昔の名曲でスタート、ベルモールの本屋さんから屋上でJAFにお世話になるまで</a><br>><a href="https://torokoid.github.io/20250507_tochigi/" target="_blank">2025年05月06-07日 、雨に濡れるつばきから夕暮れの男体山まで</a><br>><a href="https://torokoid.github.io/20250510_tochigi/" target="_blank">2025年05月08,10日 、街のお花から、市街地脇の牧場まで</a><br>><a href="https://torokoid.github.io/20250512_tochigi/" target="_blank">2025年05月11-12日 、庭のお花から、FKD外駐車場「大戸屋」のお昼ご飯まで</a><br>><a href="https://torokoid.github.io/20250513_tochigi/" target="_blank">2025年05月13日 、公園周辺のお花から、スーパーから見えたお月様まで</a><br>><a href="https://torokoid.github.io/20250516_tochigi/" target="_blank">2025年05月14-15日 、田んぼリフレクションから、インターパークの花壇まで</a><br>><a href="https://torokoid.github.io/20250518_tochigi/" target="_blank">2025年05月15-17日 、満開の薔薇から雨に濡れるお花達まで</a><br>><a href="https://torokoid.github.io/20250520_tochigi/" target="_blank">2025年05月18-20日 、庭の薔薇から、ご近所のお花達まで</a><br>><a href="https://torokoid.github.io/20250522_tochigi/" target="_blank">2025年05月20-22日 、庭の薔薇から、雨水洗車とワックスまで</a><br>><a href="https://torokoid.github.io/20250524_tochigi/" target="_blank">2025年05月22-24日 、バイクの車検明けから、ご近所のお花達まで</a><br>><a href="https://torokoid.github.io/20250526_tochigi/" target="_blank">2025年05月25-26日 、雨に濡れるお花達から、プール入り口のマリーゴールドまで</a><br>><a href="https://torokoid.github.io/20250528_tochigi/" target="_blank">2025年05月27-28日 、ご近所のお花達から、石畳の隙間のお花まで</a></p></div>



<h2><span class="yellow">画像処理用PCは実質2泊で退院。HP更新を再開します。。(2025_Apr_8)<br>意見吸い上げリンク（下記）も正常作動中ですので、お気軽にどうぞ！</span></h2>

<h2><span class="yellow"><a href="mailto:torokoid@gmail.com?subject=Mashiko_himawari_3から">HPに関するご意見などはこちらをクリック</a></span></h2>

<!--
    <div class="like-container">-->
        <!-- 10個のいいねボタン --> <!--
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
       <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
        <div class="like-item">
            <button class="like-button">いいね</button>
            <span class="like-count">0</span>
        </div>
    </div>-->


    <script>
    document.addEventListener('DOMContentLoaded', () => {
        const likeButtons = document.querySelectorAll('.like-button');
        const counts = document.querySelectorAll('.like-count');
        
        // ローカルストレージからカウントを復元
        const storedCounts = JSON.parse(localStorage.getItem('likeCounts')) || Array(likeButtons.length).fill(0);
        storedCounts.forEach((count, index) => {
            counts[index].textContent = count;
        });

        // ボタンクリック時のカウント更新と保存
        likeButtons.forEach((button, index) => {
            button.addEventListener('click', () => {
                let count = parseInt(counts[index].textContent, 10);
                count++;
                counts[index].textContent = count;
                storedCounts[index] = count;
                localStorage.setItem('likeCounts', JSON.stringify(storedCounts));
            });
        });
    });
    </script>

<br><br><br><br><br>

<h1><span class="yellow"><marquee behavior="left">!!! 2023年8月12日(土)栃木県芳賀郡益子町上山、ひまわり祭りにお邪魔しました !!!</marquee></span></h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
	
<p align="left"> <img src="QR_mashiko_3.png" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>
<h3><span class="white">JR宇都宮駅から28kmほど南東に行ったところにある、益子ひまわり祭り会場です。</span></h3>
<a href="20230812_000.png" data-lightbox="abc"><img src="20230812_000.png" alt="サンプル画像" width="900" /></a>
<a href="20230812_001.JPG" data-lightbox="abc"><img src="20230812_001.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_002.JPG" data-lightbox="abc"><img src="20230812_002.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_003.JPG" data-lightbox="abc"><img src="20230812_003.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_004.JPG" data-lightbox="abc"><img src="20230812_004.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_005.JPG" data-lightbox="abc"><img src="20230812_005.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_006.JPG" data-lightbox="abc"><img src="20230812_006.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_007.JPG" data-lightbox="abc"><img src="20230812_007.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_008.JPG" data-lightbox="abc"><img src="20230812_008.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_009.JPG" data-lightbox="abc"><img src="20230812_009.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_010.JPG" data-lightbox="abc"><img src="20230812_010.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_011.JPG" data-lightbox="abc"><img src="20230812_011.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_012.JPG" data-lightbox="abc"><img src="20230812_012.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_013.JPG" data-lightbox="abc"><img src="20230812_013.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_014.JPG" data-lightbox="abc"><img src="20230812_014.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_015.JPG" data-lightbox="abc"><img src="20230812_015.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_016.JPG" data-lightbox="abc"><img src="20230812_016.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_017.JPG" data-lightbox="abc"><img src="20230812_017.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_018.JPG" data-lightbox="abc"><img src="20230812_018.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_019.JPG" data-lightbox="abc"><img src="20230812_019.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_020.JPG" data-lightbox="abc"><img src="20230812_020.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_021.JPG" data-lightbox="abc"><img src="20230812_021.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_022.JPG" data-lightbox="abc"><img src="20230812_022.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_023.JPG" data-lightbox="abc"><img src="20230812_023.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_024.JPG" data-lightbox="abc"><img src="20230812_024.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_025.JPG" data-lightbox="abc"><img src="20230812_025.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_026.JPG" data-lightbox="abc"><img src="20230812_026.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_027.JPG" data-lightbox="abc"><img src="20230812_027.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_028.JPG" data-lightbox="abc"><img src="20230812_028.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_029.JPG" data-lightbox="abc"><img src="20230812_029.JPG" alt="サンプル画像" width="900" /></a>
<a href="20230812_030.JPG" data-lightbox="abc"><img src="20230812_030.JPG" alt="サンプル画像" width="900" /></a>

<h4><span class="white">↓益子、ひまわり祭りHPへのリンク</span></h4>
	<a href="https://www.town.mashiko.lg.jp/page/page003882.html" target="_blank"><h2>益子ひまわり祭り</h2></a><br><br>
<p>Map</p>
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d57797.491997464094!2d140.03297052032545!3d36.45868618953245!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6021fcf6baaf53b7%3A0xbef08ba7ae9da2d0!2z44Gy44G-44KP44KK56Wt5Lya5aC0!5e0!3m2!1sen!2sjp!4v1564575158565!5m2!1sen!2sjp" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>




<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<p align="right"><marquee direction="left" scrollamount="5" width="85%">去年と同じ種ですが、天候の関係で今年のお花は少し小さめとのこと！ (^_^)/~hada</marquee></p>

<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>


<br><br>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script> 



<!-- フッタ -->
 <footer><span class="white">
 Copyright 2023/08/12 S.Hada
	 </span></footer>

</body>
</html>
