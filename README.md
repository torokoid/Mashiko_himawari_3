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
<p class="topicpath"><a href="https://torokoid.github.io/mashiko_himawari/">2018年、2019年</a>><a href="https://torokoid.github.io/mashiko_himawari_2/">2021年</a>>2023年<br>><a href="https://torokoid.github.io/2024Jan_Thailand__7/">タイ植物園リンク</a><br>><a href="https://torokoid.github.io/2024_Sakura/" target="_blank">2024城址公園桜リンク</a><br>><a href="https://torokoid.github.io/2024_hitachi_kaihin/" target="_blank">2024/4/20ひたち海浜公園</a><br>><a href="https://torokoid.github.io/2024Apr_Maronie/" target="_blank">2024/4/27マロニエプラザ絵画展</a><br>><a href="https://torokoid.github.io/hagurosan/" target="_blank">ちょい古&マニアック、羽黒山から無線した記録</a><br>><a href="https://torokoid.github.io/mt_fuji/" target="_blank">2023年12月の富士山</a><br>><a href="https://torokoid.github.io/hagurosan2/" target="_blank">2022年4月、羽黒山のツツジ</a><br>><a href="https://torokoid.github.io/2024May_tanboref/" target="_blank">2024年5月、年に一度の田植え時期に見える、田んぼリフレクション</a><br>><a href="https://torokoid.github.io/kodomonomori/" target="_blank">宇都宮郊外の意外な穴場スポット「こどものもり公園」</a><br>><a href="https://torokoid.github.io/park-s-flower/" target="_blank">宇都宮市内、公園のお花が満開</a><br>><a href="https://twitter.com/sajyan" target="_blank">Xアカウントリンク、ほぼ毎日更新中</a><br>><a href="https://torokoid.github.io/2024May25_kenmin/" target="_blank">県民の森にバイクでお出かけ</a>><a href="https://torokoid.github.io/2024May_Kenmin_forest/" target="_blank">実は前の週にも県民の森</a><br>><a href="https://torokoid.github.io/20240526_HF_ant/" target="_blank">超マニアック、アマチュア無線のアンテナの話</a><br>><a href="https://torokoid.github.io/20240622_flower/" target="_blank">梅雨入り直前のお花たちを集めました</a><br>><a href="https://torokoid.github.io/20240630_flower/" target="_blank">梅雨時のしっとりしたお花たちです</a><br>><a href="https://torokoid.github.io/2023_thailand/" target="_blank">2023年、タイの日常風景</a><br>><a href="https://torokoid.github.io/2024Jul_tatekae/" target="_blank">2024年7月、お隣の家が建て替えで取り壊し</a><br>><a href="https://torokoid.github.io/2024_paris11/" target="_blank">2024年8月、高校の同級生（Bruce君）が訪れたフランスの写真集</a><br>><a href="https://torokoid.github.io/Mashiko_himawari_4/" target="_blank">2024年8月10日、益子ひまわり祭り写真集</a><br>><a href="https://torokoid.github.io/20240817_hagurosan/" target="_blank">2024年8月17日、羽黒山にお詣りと関東平野一望</a><br>><a href="https://torokoid.github.io/2023_thailand/" target="_blank">2024年8月31日、42年間勤めたHondaを無事退職</a><br>><a href="https://torokoid.github.io/after_911/" target="_blank">NHK9.11特集番組より、2001年9月11日アメリカ同時多発テロの直後に起こった出来事</a><br>><a href="https://torokoid.github.io/2024Aug_tatekae3/" target="_blank">2024年8月23日、お隣の敷地が地鎮祭〜新築工事</a><br>><a href="https://torokoid.github.io/20240930_hagurosan/" target="_blank">2024年9月30日、彼岸花の季節に羽黒山</a><br>><a href="https://torokoid.github.io/20241003_cluster/" target="_blank">2024年10月3日、メタバース空間のcluster主催者からCluster Acceleratorに推薦されたとの連絡！</a><br>><a href="https://torokoid.github.io/20241004_fukuwauchi/" target="_blank">2024年10月4日、定年退職１ヶ月後に旧職場のメンバーが飲み会を開催してくれました！</a><br>><a href="https://torokoid.github.io/2024Oct14_cosmos/" target="_blank">2024年10月14日、鬼怒川グリーンパークのコスモスが綺麗！</a><br>><a href="https://torokoid.github.io/2024Oct23_85Kenyuukai/" target="_blank">2024年10月23日、銀座散策と品川から屋形船あそび！</a><br>><a href="https://torokoid.github.io/20241103_Ibaraki_bike/" target="_blank">2024年11月3日、バイクツーリング、背景画像の３台目は女性ライダー！</a><br>><a href="https://torokoid.github.io/20241116_ClusteMBG-6-/" target="_blank">2024年11月16日、メタバース内で開催された音楽イベント。マイティヤさんの曲はTVで放送できるレベル！</a><br>><a href="https://torokoid.github.io/20241118_hagurosan/" target="_blank">2024年11月18日、20日のタイ旅行に先立ち、羽黒山神社で安全祈願！</a></p></div>


<h2><span class="yellow"><a href="https://torokoid.github.io/20241120-20250311_Thailand/" target="_blank">2024年11月20日~2025年3月11日、タイ旅行のリンクは別ページにまとめました。文字のクリックで一覧に飛びます(2025_03_15)</a></span></h2>

<h2><span class="yellow"><a href="https://torokoid.github.io/20250316_20250728_Tochigi/" target="_blank">2025年3月16日~2025年7月28日、日本滞在中の記録は別ページにまとめました。文字のクリックで一覧に飛びます(2025_08_03)</a></span></h2>

<div style="background-color:rgb(255,255,255,0.5);">
<p class="topicpath">




><a href="https://torokoid.github.io/20250801_bangkok/" target="_blank">2025年07月29-31日 、いつものショッピングモールから飛行機から見たバンコクの夜景まで</a><br>><a href="https://torokoid.github.io/20250803_bangkok/" target="_blank">2025年08月01-03日 、庭になった南国フルーツから、バンコク中心部のショッピングモールまで</a><br>><a href="https://torokoid.github.io/20250805_bangkok/" target="_blank">2025年08月03-04日 、熱くてコンビニ逃げ込むネコから、夕焼け空まで</a><br>><a href="https://torokoid.github.io/20250807_bangkok/" target="_blank">2025年08月05-06日 、市内のローカル市場から、コンビニ横の屋台、最後は四国松山の道後温泉まで</a><br>><a href="https://torokoid.github.io/20250809_bangkok/" target="_blank">2025年08月07-08日 、生垣のお花たちから、美術学校学生さんの作品、最後は雷雨後のお花たちまで</a><br>><a href="https://torokoid.github.io/20250811_bangkok/" target="_blank">2025年08月09-10日 、晴天の住宅街から、巨大ショッピングモールまで</a><br>><a href="https://torokoid.github.io/20250813_bangkok/" target="_blank">2025年08月11-12日 、車道をうろつくトカゲの子供から、住宅街のお花たちまで</a><br>><a href="https://torokoid.github.io/20250815_bangkok/" target="_blank">2025年08月13-15日 、住宅街のお花たちから、夜の市場の様子まで</a><br>><a href="https://torokoid.github.io/20250817_bangkok/" target="_blank">2025年08月15-16日 、ラーメン屋さんの夕食から、住宅街の赤いお花の絨毯まで</a><br>><a href="https://torokoid.github.io/20250819_bangkok/" target="_blank">2025年08月17-19日 、いつもの市場から、住宅街のお花たちまで</a><br>><a href="https://torokoid.github.io/20250821_bangkok/" target="_blank">2025年08月19-21日 、近場の市場から、住宅街のお花たちまで</a><br>><a href="https://torokoid.github.io/20250823_bangkok/" target="_blank">2025年08月21-23日 、スタンド敷地内のコーヒーショップから、住宅街のお花たちまで</a><br>><a href="https://torokoid.github.io/20250825_bangkok/" target="_blank">2025年08月23-25日 、Netで見る甲子園決勝から、住宅街のお花たちまで</a><br>><a href="https://torokoid.github.io/20250827_bangkok/" target="_blank">2025年08月26-27日 、住宅街のお花たちから、大型雑貨店の様子まで</a><br>><a href="https://torokoid.github.io/20250829_bangkok/" target="_blank">2025年08月27-29日 、午後の怪しい雲行きから、公園の仏壇まで</a><br>><a href="https://torokoid.github.io/20250831_bangkok/" target="_blank">2025年08月29-31日 、夕陽の空から、生垣のお花達と野鳥の鳴き声まで</a><br>><a href="https://torokoid.github.io/20250902_bangkok/" target="_blank">2025年08月31-09月01日 、住宅街のお花達から、市内市場とショッピングモールまで</a><br>><a href="https://torokoid.github.io/20250904_bangkok/" target="_blank">2025年09月02-04日 、住宅街のお花達から、市内市場とショッピングモール内の本屋さんまで</a><br>><a href="https://torokoid.github.io/20250906_bangkok/" target="_blank">2025年09月04-06日 、新築工事の様子から、いつものお花達まで</a><br>><a href="https://torokoid.github.io/20250908_bangkok/" target="_blank">2025年09月06-08日 、住宅街の様子から、いつものお花達まで</a><br>><a href="https://torokoid.github.io/20250910_bangkok/" target="_blank">2025年09月08-10日 、近所の市場から、しっとり濡れたお花達まで</a><br>><a href="https://torokoid.github.io/20250912_bangkok/" target="_blank">2025年09月10-12日 、街中の仏壇から、わき上がる入道雲まで</a><br>><a href="https://torokoid.github.io/20250914_bangkok/" target="_blank">2025年09月12-14日 、Wi-Fi交換から、生垣のお花達まで</a><br>><a href="https://torokoid.github.io/20250916_bangkok/" target="_blank">2025年09月14-16日 、街の電気屋さんから、生垣のお花達まで</a><br>><a href="https://torokoid.github.io/20250918_bangkok/" target="_blank">2025年09月16-18日 、お昼のラーメンから、朝の街まで</a><br>><a href="https://torokoid.github.io/20250919_bangkok/" target="_blank">2025年09月18-19日 、屋外台所の修理から、パタヤ観光まで</a><br>><a href="https://torokoid.github.io/20250922_maechan/" target="_blank">2025年09月20-21日 、いつものショッピングモールから、チェンライに移動まで</a><br>><a href="https://torokoid.github.io/20250924_maechan/" target="_blank">2025年09月21-23日 、チェンライへの移動から、メーチャンの街まで</a><br>><a href="https://torokoid.github.io/20250926_maechan/" target="_blank">2025年09月24-25日 、メーチャンの市役所から、王立大学のプールまで</a><br>><a href="https://torokoid.github.io/20250928_maechan/" target="_blank">2025年09月27日 、親戚の現役警察官のお宅にお邪魔しました</a><br>><a href="https://torokoid.github.io/20250930_maechan/" target="_blank">2025年09月28-29日 、メーチャンの夜明けからLotus'sのお坊さんまで</a><br>><a href="https://torokoid.github.io/20251002_maechan/" target="_blank">2025年09月30-10月01日 、メーチャンのどんより曇り空からLotus'sのお坊さんまで</a><br>><a href="https://torokoid.github.io/20251004_maechan/" target="_blank">2025年10月02-03日 、雨季の合間の晴れ間からメーチャンへの移動と車のメンテまで</a><br>><a href="https://torokoid.github.io/20251006_maechan/" target="_blank">2025年10月04-05日 、庭の鶏達から夕方のお月様まで</a><br>><a href="https://torokoid.github.io/20251008_maechan/" target="_blank">2025年10月06-07日 、朝の青空から市場の夕暮れまで</a><br>><a href="https://torokoid.github.io/20251010_maechan/" target="_blank">2025年10月08-10日 、庭木の伐採から西の空の朝のお月様まで</a><br>><a href="https://torokoid.github.io/20251011_maechan/" target="_blank">2025年10月10日 、庭の蝶々から街の金曜開催市場、久々の星空まで</a><br>><a href="https://torokoid.github.io/20251012_maechan/" target="_blank">2025年10月11-12日 、寝転ぶ猫から夜の星空、庭のバナナまで</a><br>><a href="https://torokoid.github.io/20251014_maechan/" target="_blank">2025年10月12-13日 、収穫したバナナの天日干しから、市場のワンちゃんと甥っ子まで</a><br>><a href="https://torokoid.github.io/20251016_maechan/" target="_blank">2025年10月14-15日 、車の下でくつろぐネコちゃんから、夕食ではしゃぐ甥っ子まで</a><br>><a href="https://torokoid.github.io/20251018_maechan/" target="_blank">2025年10月16-18日 、朝の豪雨から、早朝の秋の雲まで</a><br>><a href="https://torokoid.github.io/20251020_maechan/" target="_blank">2025年10月18-19日 、国境の街に向かう国道から、星空まで</a><br>><a href="https://torokoid.github.io/20251021_maechan/" target="_blank">2025年10月20-21日 、GSに併設のコーヒーショップから、朝のお花まで</a><br>><a href="https://torokoid.github.io/20251022_maechan/" target="_blank">2025年10月21-22日 、けなげに隠れるカマキリの子供から、朝のお花まで</a><br>><a href="https://torokoid.github.io/20251024_maechan/" target="_blank">2025年10月22-23日 、木に咲いたお花から、王立大学の夕暮れまで</a><br>><a href="https://torokoid.github.io/20251025_maechan/" target="_blank">2025年10月24-25日 、陽射しを浴びた黄色いお花から、雲の向こうで控える朝陽まで</a><br>><a href="https://torokoid.github.io/20251026_maechan/" target="_blank">2025年10月25-26日 、ラオスに向かう国道から、メコン川の夕暮れとラオスの市場まで</a><br>><a href="https://torokoid.github.io/20251028_maechan/" target="_blank">2025年10月26-27日 、ラオスの街の夕暮れから、タイ、メーチャンに戻ってほっとした夕焼け空まで</a><br>><a href="https://torokoid.github.io/20251030_maechan/" target="_blank">2025年10月28-29日 、庭で蜜集めする蝶々から、メーチャンの夕焼けと星空まで</a><br>><a href="https://torokoid.github.io/20251101_maechan/" target="_blank">2025年10月30-31日 、電波を出さないアマチュア無線から、メーチャンの金曜市場まで</a><br>><a href="https://torokoid.github.io/20251102_maechan/" target="_blank">2025年11月01日 、庭のお花からパヤオ湖、チェンライの不法入国取り締まりまで</a><br>><a href="https://torokoid.github.io/20251103_maechan/" target="_blank">2025年11月02日 、チェンライの一般家庭の作りから、夜のお月様まで</a><br>><a href="https://torokoid.github.io/20251104_maechan/" target="_blank">2025年11月03日 、髪染めに付き合うネコちゃんから、ショッピングモールと喪中のお店まで</a><br>><a href="https://torokoid.github.io/20251105_maechan/" target="_blank">2025年11月04日 、庭のお花たちから、火曜日開催の市場とチビちゃんまで</a><br>><a href="https://torokoid.github.io/20251106_maechan/" target="_blank">2025年11月05日 、いつもの王立大学プールから、ロイクラトンのお祭りまで</a><br>><a href="https://torokoid.github.io/20251107_maechan/" target="_blank">2025年11月06-07日 、庭の朝顔から、テーブルの上のIT状況まで</a><br>><a href="https://torokoid.github.io/20251108_maechan/" target="_blank">2025年11月07日 、預かった子犬たちから、金曜市場と夜の月まで</a><br>><a href="https://torokoid.github.io/20251110_maechan/" target="_blank">2025年11月08-09日 、庭の珍しいお花から、タイの掃除用具まで</a><br>><a href="https://torokoid.github.io/20251111_maechan/" target="_blank">2025年11月10日 、熱帯の陽射しで洗濯から、知り合いたちと食事して綺麗な夕焼け雲まで</a><br>><a href="https://torokoid.github.io/20251112_maechan/" target="_blank">2025年11月11日 、庭のお花から、いつものプールと晩御飯まで</a><br>><a href="https://torokoid.github.io/20251114_maechan/" target="_blank">2025年11月13日 、生後２ヶ月の子犬から、夕暮れのお空と晩御飯まで</a><br>><a href="https://torokoid.github.io/20251115_maechan/" target="_blank">2025年11月14日 、庭のお花達から、金曜市場、夕暮れのお空と星空まで</a><br>><a href="https://torokoid.github.io/20251116_maechan/" target="_blank">2025年11月15日 、東の空の朝陽から、蝶々やお昼ご飯のお店、夕暮れのお空とワンコまで</a><br>><a href="https://torokoid.github.io/20251117_maechan/" target="_blank">2025年11月16日 、庭のお花から、電気で温まって眠るひよこ達まで</a><br>><a href="https://torokoid.github.io/20251118_maechan/" target="_blank">2025年11月17日 、庭で遊ぶチビから、スーパーの鮮魚まで</a><br>><a href="https://torokoid.github.io/20251119_maechan/" target="_blank">2025年11月18日 、雨の中入管へ移動から、家に逃げ込む猫ちゃんまで</a><br>><a href="https://torokoid.github.io/20251120_maechan/" target="_blank">2025年11月19日 、庭に咲いた小さなお花から、Lotus’s駐車場の市場まで</a><br>><a href="https://torokoid.github.io/20251121_maechan/" target="_blank">2025年11月20日 、庭のパッションフルーツから、2日目のLotus’s駐車場の市場まで</a><br>><a href="https://torokoid.github.io/20251122_maechan/" target="_blank">2025年11月21日 、地平まで続く青空から、夕暮れグラデーションと朝陽まで</a><br>><a href="https://torokoid.github.io/20251123_maechan/" target="_blank">2025年11月22日 、デジタル化したアマチュア無線から、土曜市場、夕焼け空と星空まで</a><br>><a href="https://torokoid.github.io/20251124_maechan/" target="_blank">2025年11月23日 、陽射しを浴びた朝顔から、チェンライのショッピングモール、夕焼け空と星空まで</a><br>><a href="https://torokoid.github.io/20251125_maechan/" target="_blank">2025年11月24日 、生後２ヶ月初めてのシャンプーから、夕焼け空と星空、翌朝の青空まで</a><br>><a href="https://torokoid.github.io/20251126_maechan/" target="_blank">2025年11月25日 、朝日の中のお花たちから、火曜開催の市場、夕焼け空から朝日まで</a><br>><a href="https://torokoid.github.io/20251127_maechan/" target="_blank">2025年11月26日 、庭のお花たちから、夕焼け空と朝日まで</a><br>><a href="https://torokoid.github.io/20251128_maechan/" target="_blank">2025年11月27日 、国道の荷台乗車から、病院とプール、市場、夕暮れ画像まで</a><br>><a href="https://torokoid.github.io/20251129_maechan/" target="_blank">2025年11月28日 、猫ちゃんの注射からメーチャンで車の整備、地酒やさんと金曜市場まで</a><br>><a href="https://torokoid.github.io/20251130_maechan/" target="_blank">2025年11月29日 、庭のお花たちから土曜開催の市場、大学プールの夕暮れと星空まで</a><br>><a href="https://torokoid.github.io/20251201_maechan/" target="_blank">2025年11月30日 、無線とパパイヤからチビのこだわり、庭のネコや花と星空から朝日まで</a><br>><a href="https://torokoid.github.io/20251202_maechan/" target="_blank">2025年12月01日 、庭で睨めっこする猫たちからプール花壇のお花、昼食ラーメンといつもの夕暮れまで</a><br>><a href="https://torokoid.github.io/20251203_maechan/" target="_blank">2025年12月02日 、ひよこ連れて餌ねだりの親鳥から広大な農地、大木の伐採といつもの夕暮れまで</a><br>><a href="https://torokoid.github.io/20251204_maechan/" target="_blank">2025年12月03日 、木についた蕾と雑草のお花たちから王立大学のプール、コンビニから見えた夕暮れまで</a><br>><a href="https://torokoid.github.io/20251205_maechan/" target="_blank">2025年12月04日 、陽射しで輝くお花たちから病院とホームセンター、市場の買い物と夕暮れまで</a><br>><a href="https://torokoid.github.io/20251206_maechan/" target="_blank">2025年12月05日 、朝一から動物病院とチビのお相手、プール花壇のお花と金曜市場まで</a><br>><a href="https://torokoid.github.io/20251207_maechan/" target="_blank">2025年12月06日 、野鳥が立木で大騒ぎと土曜開催市場、スーパーはクリスマスモードで最後は夕暮れまで</a><br>><a href="https://torokoid.github.io/20251208_maechan/" target="_blank">2025年12月07日 、朝の濃霧と庭のお花から、いつものプールと定点観測の夕暮れまで</a><br>><a href="https://torokoid.github.io/20251209_maechan/" target="_blank">2025年12月08日 、朝のお花たちから、チェンライへの移動と定点観測の夕暮れまで</a><br>><a href="https://torokoid.github.io/20251210_maechan/" target="_blank">2025年12月09日 、午後の長距離移動から、いつものプールとスーパー、定点観測の夕暮れまで</a><br>><a href="https://torokoid.github.io/20251211_maechan/" target="_blank">2025年12月10日 、伐採した木片の搬送作業から、庭のお花達、夕暮れの後の街の市場まで</a><br>><a href="https://torokoid.github.io/20251212_maechan/" target="_blank">2025年12月11日 、トラクターで庭の整地から、大学のプールとテニスコート、水田に水が入って定点観測の夕暮れまで</a><br>><a href="https://torokoid.github.io/20251213_maechan/" target="_blank">2025年12月12日 、庭を走り回るヒナたちから、お昼のラーメンと自転車修理、スーパーと金曜開催の市場まで</a><br>><a href="https://torokoid.github.io/20251214_maechan/" target="_blank">2025年12月13日 、土曜開催市場から、王立大学プールと定点観測夕暮れまで</a><br>><a href="https://torokoid.github.io/20251215_maechan/" target="_blank">2025年12月14日 、鮮やかに咲いた雑草のお花から、夕暮れ定点観測と日暮後のお買い物まで</a><br>><a href="https://torokoid.github.io/20251216_maechan/" target="_blank">2025年12月15日 、庭のひよことお花たちから、選挙のスタートと開けにくいタイのお菓子と夕焼けまで</a><br>><a href="https://torokoid.github.io/20251217_maechan/" target="_blank">2025年12月16日 、西の空の鱗雲と庭のお花から、選挙カーといつものプールと夕焼けまで</a><br>><a href="https://torokoid.github.io/20251218_maechan/" target="_blank">2025年12月17日 、冷んやりした椅子の下の床でくつろぐ猫から、活発化した選挙選挙活動、いつものスーパーの夕暮れまで</a><br>><a href="https://torokoid.github.io/20251219_maechan/" target="_blank">2025年12月18日 、熱帯の雑菌に感染してダウン、お花と夕暮れ定点観測のみです</a><br>><a href="https://torokoid.github.io/20251220_maechan/" target="_blank">2025年12月19日 、庭のお花たちから、犬の注射と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20251221_maechan/" target="_blank">2025年12月20日 、霧の朝、庭のお花たちから、小屋作りと土曜市場とメーチャンの夕暮れまで</a><br>><a href="https://torokoid.github.io/20251222_maechan/" target="_blank">2025年12月21日 、鱗雲とワンコから、お花とチビちゃん、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20251223_maechan/" target="_blank">2025年12月22日 、眩しい朝日から、蝶々とお花、スーパーと水田、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20251224_maechan/" target="_blank">2025年12月23日 、生まれたばかりの蛾の子供から、火曜市場と大学プール、スーパーと夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20251225_maechan/" target="_blank">2025年12月24日 、庭のお花から、舞い込んだ蝶々と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20251226_maechan/" target="_blank">2025年12月25日 、庭のお花達から、蝶々と夕暮れ定点観測、知り合い宅でのパーティーまで</a><br>><a href="https://torokoid.github.io/20251227_maechan/" target="_blank">2025年12月26日 、青空に浮かぶお月様から、メーチャンの金曜開催市場まで</a><br>><a href="https://torokoid.github.io/20251228_maechan/" target="_blank">2025年12月27日 、屋根から見守る鳥から、市場のハシゴと夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20251229_maechan/" target="_blank">2025年12月28日 、ご近所の散策から、大学プールと夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20251230_maechan/" target="_blank">2025年12月29日 、昼のお月様から、蝶々とスーパーの夕暮れまで</a><br>><a href="https://torokoid.github.io/20251231_maechan/" target="_blank">2025年12月30日 、朝の太陽から、火曜市場、親戚宅でのパーティーまで</a><br>><a href="https://torokoid.github.io/20260101_maechan/" target="_blank">2025年12月31日 、濃霧の朝の太陽から、メーチャンの街の市場、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260102_maechan/" target="_blank">2026年01月01日 、メーチャンからチェンライの街まで散策、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260103_maechan/" target="_blank">2026年01月02日 、仏壇のお供えからメーチャンの金曜市場と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260104_maechan/" target="_blank">2026年01月03日 、餌ねだりの鶏たちから郊外の土曜市場と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260105_maechan/" target="_blank">2026年01月04日 、綺麗な朝陽からいつものスーパーとご近所の農地、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260106_maechan/" target="_blank">2026年01月05日 、庭のヒナとお花達からいつものプール、街の食堂と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260107_maechan/" target="_blank">2026年01月06日 、空に浮かぶ可愛い雲から初泳ぎのプール、火曜日開催の市場と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260108_maechan/" target="_blank">2026年01月07日 、西の空のお月様から義妹のお店でお昼、常設市場と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260109_maechan/" target="_blank">2026年01月08日 、西の空、だんだん欠けるお月様から庭のお花達、火木開催の市場からプール、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260110_maechan/" target="_blank">2026年01月09日 、だんだん欠ける朝のお月様から庭のキャベツ、犬の注射して金曜開催の市場からさらに市場を2つはしご、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260111_maechan/" target="_blank">2026年01月10日 、半月になった朝のお月様から庭のお花、土曜開催の市場からいつもの大学プールと夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260112_maechan/" target="_blank">2026年01月11日 、王室カレンダーからお昼ご飯、庭のお花達と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260113_maechan/" target="_blank">2026年01月12日 、朝の月からマット遊びのワンコ、プールとスーパーに夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260114_maechan/" target="_blank">2026年01月13日 、朝の月から朝焼けの鳥、夕暮れグラデーションの合間に市場と定点観測まで</a><br>><a href="https://torokoid.github.io/20260115_maechan/" target="_blank">2026年01月14日 、朝の月から裏庭のひよこ、野の花たちとプールから夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260116_maechan/" target="_blank">2026年01月15日 、日の出の空から庭のお花、植木屋さんと木曜開催の市場、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260117_maechan/" target="_blank">2026年01月16日 、日の出前の細い月から庭のお花とチョウ、大学プール、金曜市場と夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260118_maechan/" target="_blank">2026年01月17日 、朝焼けから夕暮れ定点観測までを、土曜市場の画像を挟んで掲載</a><br>><a href="https://torokoid.github.io/20260119_maechan/" target="_blank">2026年01月18日 、朝焼けから近所のお花達、いつものプールとスーパー、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260120_maechan/" target="_blank">2026年01月19日 、朝の鳥から北の街メーサイ、国道を南下しながら伝説の山、夕暮れ定点観測まで</a><br>><a href="https://torokoid.github.io/20260121_maechan/" target="_blank">2026年01月20日 、朝焼けとお花たちから100歳のおばあちゃん、スーパーと火曜市場を梯子して、夕暮れ定点観測まで</a></p></div>






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
