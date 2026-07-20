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

<h2><span class="yellow"><a href="https://torokoid.github.io/20250729_20260303_Thailand/" target="_blank">2025年7月29日~2026年3月3日、タイ滞在中の記録は別ページにまとめました。文字のクリックで一覧に飛びます(2026_03_23)</a></span></h2>

<div style="background-color:rgb(255,255,255,0.5);">
<p class="topicpath">




><a href="https://torokoid.github.io/20260308_utsunomiya/" target="_blank">2026年03月08日 、ホームセンターのお花と黒潮寿司のお寿司と讃岐そば、綺麗な造花から夕暮れと星空まで</a><br>><a href="https://torokoid.github.io/20260310_utsunomiya/" target="_blank">2026年03月10日 、宇都宮市内の散策、綺麗なお花から朝の大雪まで</a><br>><a href="https://torokoid.github.io/20260312_utsunomiya/" target="_blank">2026年03月11日 、日本の味「カツ丼」翌日は「牛丼」からベルモールのスナックまで</a><br>><a href="https://torokoid.github.io/20260314_utsunomiya/" target="_blank">2026年03月13日 、日本のお花からベルモールのお弁当、FKDでお昼と梅のお花まで</a><br>><a href="https://torokoid.github.io/20260316_utsunomiya/" target="_blank">2026年03月14日 、Hondaのお店で車検とカレーショップでお昼、ベルモールでお買い物と夜のステーキまで</a><br>><a href="https://torokoid.github.io/20260318_utsunomiya/" target="_blank">2026年03月16日 、益子のいちご狩りから4号線の「ゆ」、宇都宮城址公園の桜まで</a><br>><a href="https://torokoid.github.io/20260320_utsunomiya/" target="_blank">2026年03月18日 、休業のスキー場から、お花と夜の星空まで</a><br>><a href="https://torokoid.github.io/20260322_utsunomiya/" target="_blank">2026年03月20日 、午後の吉野家から、お花と東京散策まで</a><br>><a href="https://torokoid.github.io/20260324_utsunomiya/" target="_blank">2026年03月22日 、お昼のプールから、しゃぶしゃぶとお月様まで</a><br>><a href="https://torokoid.github.io/20260326_utsunomiya/" target="_blank">2026年03月23日 、綺麗に咲き誇るお花達から、焼肉屋さんの晩御飯まで</a><br>><a href="https://torokoid.github.io/20260328_utsunomiya/" target="_blank">2026年03月26日 、久しぶりのうどんから、お花達と星空まで</a><br>><a href="https://torokoid.github.io/20260330_utsunomiya/" target="_blank">2026年03月28日 、カインズの野菜売り場とお花から、ラーメン、バイクチェックして初乗りまで</a><br>><a href="https://torokoid.github.io/20260401_utsunomiya/" target="_blank">2026年03月30日 、ベルモールの桜から、スーパーのお花と夜空まで</a><br>><a href="https://torokoid.github.io/20260403_utsunomiya/" target="_blank">2026年04月01日 、4号戦かつやのカツ丼から市内の桜、スーパーのお花と夜空まで</a><br>><a href="https://torokoid.github.io/20260404_utsunomiya/" target="_blank">2026年04月03日 、鬼怒川土手の桜が満開</a><br>><a href="https://torokoid.github.io/20260405_utsunomiya/" target="_blank">2026年04月05日 、桜ツーリング</a><br>><a href="https://torokoid.github.io/20260407_utsunomiya/" target="_blank">2026年04月06日 、街のお花と天一のラーメン、年に一度の健康診断とプールの桜</a><br>><a href="https://torokoid.github.io/20260409_utsunomiya/" target="_blank">2026年04月08日 、朝日の中のムラサキハナナから、公園とプールの桜と夕焼け空まで</a><br>><a href="https://torokoid.github.io/20260410_utsunomiya/" target="_blank">2026年04月08〜09日 、元社の仲間達が道志村でお泊まり会</a><br>><a href="https://torokoid.github.io/20260412_utsunomiya/" target="_blank">2026年04月10日 、庭のお花達から久しぶりの星空まで</a><br>><a href="https://torokoid.github.io/20260412.5_utsunomiya/" target="_blank">2026年04月12日 、カンセキスタジアムで開催された、栃木SC vs ザスパ群馬の試合映像</a><br>><a href="https://torokoid.github.io/20260415_utsunomiya/" target="_blank">2026年04月14日 、お花特集</a><br>><a href="https://torokoid.github.io/20260417_utsunomiya/" target="_blank">2026年04月15日 、お花と星空特集</a><br>><a href="https://torokoid.github.io/20260420_utsunomiya/" target="_blank">2026年04月20日 、お花屋さんとご近所のお花たち</a><br>><a href="https://torokoid.github.io/20260423_utsunomiya/" target="_blank">2026年04月23日 、夕焼け空から、いつものお花たち</a><br>><a href="https://torokoid.github.io/20260425_utsunomiya/" target="_blank">2026年04月25日 、野のたんぽぽから、図書館といつものお花たち</a><br>><a href="https://torokoid.github.io/20260426_utsunomiya/" target="_blank">2026年04月26日 、日本マスターズ水泳短水路大会、栃木会場</a><br>><a href="https://torokoid.github.io/20260428_utsunomiya/" target="_blank">2026年04月28日 、綺麗なお花たちから、夕焼け空と星空まで</a><br>><a href="https://torokoid.github.io/20260430_utsunomiya/" target="_blank">2026年04月30日 、綺麗なお花たちから、MacFanと星空まで</a><br>><a href="https://torokoid.github.io/20260502_utsunomiya/" target="_blank">2026年05月02日 、咲き誇るムラサキハナナから、お花屋さんのお花とイラスト展示会まで</a><br>><a href="https://torokoid.github.io/20260504_utsunomiya/" target="_blank">2026年05月04日 、いつものお花たちから、アマチュア無線のシステム改修とFKDの本屋さんやぬいぐるみなどなど</a><br>><a href="https://torokoid.github.io/20260506_utsunomiya/" target="_blank">2026年05月06日 、ほぼお花ばかりの画像集です</a><br>><a href="https://torokoid.github.io/20260508_japan/" target="_blank">2026年05月08日 、SNSのダイレクトメールでフィッシングされた記録</a><br>><a href="https://torokoid.github.io/20260509_utsunomiya/" target="_blank">2026年05月09日 、お花と田植えの絵、自転車売却と最後は星空の画像集です</a><br>><a href="https://torokoid.github.io/20260510_utsunomiya/" target="_blank">2026年05月10日 、宇都宮市中岡本町、三和テッキ鉄道広場、交流会の模様です</a><br>><a href="https://torokoid.github.io/20260511_utsunomiya/" target="_blank">2026年05月11日 、ご近所や公園のお花たちから、羽黒山山頂と密嶽神社など</a><br>><a href="https://torokoid.github.io/20260512_utsunomiya/" target="_blank">2026年05月12日 、5月の空の雲や、デパート屋上からの宇都宮の眺めと、星空から庭のお花まで</a><br>><a href="https://torokoid.github.io/20260513_utsunomiya/" target="_blank">2026年05月13日 、お花屋さんのお花達と、田植え直後の田園風景まで</a><br>><a href="https://torokoid.github.io/20260514_utsunomiya/" target="_blank">2026年05月14日 、庭とお花屋さんのお花達と、楽器屋さんのギターから星空まで</a><br>><a href="https://torokoid.github.io/20260515_utsunomiya/" target="_blank">2026年05月15日 、お花屋さんのお花達から、ラズパイの時計ソフトまで</a><br>><a href="https://torokoid.github.io/20260516_ooizumi_judo/" target="_blank">2026年05月16日 、代々木にて開催された柔道部OB会の記録です</a><br>><a href="https://torokoid.github.io/20260518_utsunomiya/" target="_blank">2026年05月18日 、お花画像メインの画像集です</a><br>><a href="https://torokoid.github.io/20260519_utsunomiya/" target="_blank">2026年05月19日 、ローカルネタ、宇都宮市ごみ収集のルール</a><br>><a href="https://torokoid.github.io/20260520_utsunomiya/" target="_blank">2026年05月20日 、AI参考書とお花達から、男体山に沈む夕陽と星空まで</a><br>><a href="https://torokoid.github.io/20260521_utsunomiya/" target="_blank">2026年05月21日 、雨に濡れるお花達の画像集</a><br>><a href="https://torokoid.github.io/20260523_utsunomiya/" target="_blank">2026年05月23日 、雨に濡れる河内総合運動公園のお花から、庭の薔薇までの画像集</a><br>><a href="https://torokoid.github.io/20260524_utsunomiya/" target="_blank">2026年05月24日 、お昼のカツ丼とベルモールのお花達から道の脇のオオインケイギクまで</a><br>><a href="https://torokoid.github.io/20260526_utsunomiya/" target="_blank">2026年05月26日 、田植えの終わった水田の光景から、お花達と夜空のお月様まで</a><br>><a href="https://torokoid.github.io/20260527_utsunomiya/" target="_blank">2026年05月27日 、新しいAIの解説書と街のお花達から、庭の薔薇と夜空のお月様まで</a><br>><a href="https://torokoid.github.io/20260528_utsunomiya/" target="_blank">2026年05月28日 、宇都宮ベルモールのお花達から</a><br>><a href="https://torokoid.github.io/20260528_doukikai/" target="_blank">2026年05月28日 、'83年入社の同期会＠ひょうたん寿司</a><br>><a href="https://torokoid.github.io/20260530_utsunomiya/" target="_blank">2026年05月29日 、久々の吉野家とお花屋さんのお花達から、夜空のお月様まで</a><br>><a href="https://torokoid.github.io/20260531_utsunomiya/" target="_blank">2026年05月30日 、可愛く咲いたお花達から、ハナミズキと田んぼの夕暮れと夜空のお星様まで</a><br>><a href="https://torokoid.github.io/20260601_utsunomiya/" target="_blank">2026年05月31日 、アゲハの幼虫と庭のお花達から、夏の雲と15夜お月さままで</a><br>><a href="https://torokoid.github.io/20260602_utsunomiya/" target="_blank">2026年06月01日 、道で見かけたお花達から、台風直前のドリームかわちプールまで</a><br>><a href="https://torokoid.github.io/20260603_utsunomiya/" target="_blank">2026年06月03日 、台風6号の暴風雨から、風雨に耐えたタチアオイと台風一過の陽射しまで</a><br>><a href="https://torokoid.github.io/20260605_utsunomiya/" target="_blank">2026年06月05日 、お花屋さんのランからお昼と専門書、八百屋さんのお花たちまで</a><br>><a href="https://torokoid.github.io/20260607_utsunomiya/" target="_blank">2026年06月07日 、街と公園のお花たちから、河内総合運動公園のハナミズキまで</a><br>><a href="https://torokoid.github.io/20260608_utsunomiya/" target="_blank">2026年06月08日 、雨に濡れるお花たちから、田んぼレフとミスド人気商品の列まで</a><br>><a href="https://torokoid.github.io/20260609_utsunomiya/" target="_blank">2026年06月09日 、満開の薔薇から、済生会病院の空と夜のドリームかわちプールまで</a><br>><a href="https://torokoid.github.io/20260610_utsunomiya/" target="_blank">2026年06月10日 、庭のお花たちから、河内運動公園のお空と夜の星まで</a><br>><a href="https://torokoid.github.io/20260611_utsunomiya/" target="_blank">2026年06月11日 、図書館のお花たちから、ショッピングモールのスマホ教室と庭の薔薇まで</a><br>><a href="https://torokoid.github.io/20260612_utsunomiya/" target="_blank">2026年06月12日 、庭の薔薇たちから、ベルモールのCD屋さんとお花達まで</a><br>><a href="https://torokoid.github.io/20260613_utsunomiya/" target="_blank">2026年06月13日 、北宇都宮のクリーンセンター下田原から、道沿いのお花達と公園から見えた夏の雲まで</a><br>><a href="https://torokoid.github.io/20260615_utsunomiya/" target="_blank">2026年06月15日 、東の空に浮いた入道雲から、ベルモールのワンちゃんと庭の薔薇まで</a><br>><a href="https://torokoid.github.io/20260616_utsunomiya/" target="_blank">2026年06月16日 、久しぶりのスーパー銭湯から、庭の薔薇と知り合い宅のお花達まで</a><br>><a href="https://torokoid.github.io/20260617_utsunomiya/" target="_blank">2026年06月17日 、蕾の薔薇が満開、図書館花壇とスーパーのお花達まで</a><br>><a href="https://torokoid.github.io/20260618_mexico/" target="_blank">2026年06月18日 、高校の同級生Bruce東がサッカー観戦で6月15日から31時間かけてメキシコに移動</a><br>><a href="https://torokoid.github.io/20260619_mexico/" target="_blank">2026年06月19日 、サッカー観戦でメキシコに行ったBruce東からの続報</a><br>><a href="https://torokoid.github.io/20260620_mexico/" target="_blank">2026年06月20日 、サッカー観戦でメキシコに行ったBruce東がイグアナ観察</a><br>><a href="https://torokoid.github.io/20260620_utsunomiya/" target="_blank">2026年06月20日 、本屋さんに並ぶ図書と庭の薔薇、市内の公園から西の空のお月様まで</a><br>><a href="https://torokoid.github.io/20260621_mexico/" target="_blank">2026年06月21日 、サッカーW杯、日本vsチュニジア戦のレポート</a><br>><a href="https://torokoid.github.io/20260622_mexico/" target="_blank">2026年06月22日 、サッカーW杯、日本vsチュニジア戦後のもろもろ</a><br>><a href="https://torokoid.github.io/20260625_utsunomiya/" target="_blank">2026年06月25日 、久々に日本のお花達など</a><br>><a href="https://torokoid.github.io/20260626_mexico/" target="_blank">2026年06月26日 、サッカーW杯レポート続報</a><br>><a href="https://torokoid.github.io/20260627_utsunomiya/" target="_blank">2026年06月27日 、宇都宮からお花と温泉など</a><br>><a href="https://torokoid.github.io/20260628_utsunomiya/" target="_blank">2026年06月28日 、宇都宮市民水泳大会画像集</a><br>><a href="https://torokoid.github.io/20260629_utsunomiya/" target="_blank">2026年06月29日 、街のお花達写真集</a><br>><a href="https://torokoid.github.io/20260630_utsunomiya/" target="_blank">2026年06月30日 、庭の薔薇からショッピングモールの書店まで</a><br>><a href="https://torokoid.github.io/20260701_dallas/" target="_blank">2026年07月01日 、Bruce東サッカー観戦レポート、ダラス編</a><br>><a href="https://torokoid.github.io/20260702_houston/" target="_blank">2026年07月02日 、Bruce東サッカー観戦レポート、ヒューストン編</a><br>><a href="https://torokoid.github.io/20260703_utsunomiya/" target="_blank">2026年07月03日 、NTT光の修理から図書館のお花と、ご近所のお花達まで</a><br>><a href="https://torokoid.github.io/20260704_utsunomiya/" target="_blank">2026年07月04日 、ハイビスカスのお花からヨークベニマルのポテトと、ドコモ光の工事まで</a><br>><a href="https://torokoid.github.io/20260703_houston/" target="_blank">2026年07月03日 、Bruce東、宇宙センターの月の石から宇宙ステーションまで</a><br>><a href="https://torokoid.github.io/20260706_utsunomiya/" target="_blank">2026年07月06日 、平日のベルモールから鈴鹿8時間耐久レースまで</a><br>><a href="https://torokoid.github.io/20260707_utsunomiya/" target="_blank">2026年07月07日 、月曜のベルモールから、COCOSと羽黒山まで</a><br>><a href="https://torokoid.github.io/20260708_utsunomiya/" target="_blank">2026年07月08日 、七夕の夜空から、ヘルメット修理、道の駅でお弁当と鬼怒川河川敷公園まで</a><br>><a href="https://torokoid.github.io/20260709_utsunomiya/" target="_blank">2026年07月09日 、夕空のグラデーションから、NTTの回線工事、お花達と夕空の金星まで</a><br>><a href="https://torokoid.github.io/20260710_utsunomiya/" target="_blank">2026年07月10日 、街道沿いのタチアオイから、ヘルメットの修理、ベルモールの散策と図書館のペチュニアまで</a><br>><a href="https://torokoid.github.io/20260711_utsunomiya/" target="_blank">2026年07月11日 、河内運動公園の夕暮れから、お花達と、ベルモールのメダカまで</a><br>><a href="https://torokoid.github.io/20260712_utsunomiya/" target="_blank">2026年07月12日 、雨の鬼怒川河川敷公園でブルーベリー摘み</a><br>><a href="https://torokoid.github.io/20260713_utsunomiya/" target="_blank">2026年07月13日 、吉野家の牛丼からプールのお空の雲と、久々の夕焼け</a><br>><a href="https://torokoid.github.io/20260714_utsunomiya/" target="_blank">2026年07月14日 、河内図書館の花壇のお花達</a><br>><a href="https://torokoid.github.io/20260715_utsunomiya/" target="_blank">2026年07月15日 、街のお花達から、那須塩原のお蕎麦屋さんとナスアウトレットまで</a><br>><a href="https://torokoid.github.io/20260716_utsunomiya/" target="_blank">2026年07月16日 、鬼怒川グリーンパークのお花達とブルーベリーから、カインズホームのお花屋さんのお花達まで</a><br>><a href="https://torokoid.github.io/20260717_utsunomiya/" target="_blank">2026年07月17日 、ドリームプールかわちの夜間照明から図書館の本とお花達、ベルモールのお昼ご飯とお花屋さんのお花まで</a><br>><a href="https://torokoid.github.io/20260718_utsunomiya/" target="_blank">2026年07月18日 、野菜市場でもらった花束から、鬼怒川河川敷公園散策まで</a><br>><a href="https://torokoid.github.io/20260719_utsunomiya/" target="_blank">2026年07月19日 、花瓶のお花から、ベルモールの散策と懐かしい漫画本まで</a><br>><a href="https://torokoid.github.io/20260720_utsunomiya/" target="_blank">2026年07月20日 、プール前のかき氷屋さんから、夕暮れとお花達まで</a></p></div>





<!--
<h2><span class="yellow">画像処理用PCは実質2泊で退院。HP更新を再開します。。(2025_Apr_8)<br>意見吸い上げリンク（下記）も正常作動中ですので、お気軽にどうぞ！</span></h2>
-->

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
