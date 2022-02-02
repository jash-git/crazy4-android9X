瘋狂 Android 講義, 4/e [疯狂Android讲义相关资源（第四版2019年3月]

資料來源:
	https://www.tenlong.com.tw/products/9787121360091
    https://blog.csdn.net/qq_44005101/article/details/117980155
    https://github.com/daichangya/book/tree/master/android
	https://pan.baidu.com/s/1d_xYJI0UQ_1tQzSj_V_NIg 提取码:70ch
	
GITHUB:	

移动互联网已经成为当今世界发展最快、市场潜力最大、前景最诱人的业务，而Android则是移动互联网上市场占有率最高的平台。本书是《疯狂Android讲义》的第4版。
本书基于全新的Android 9.x，并采用Google推荐的IDE：Android Studio作为开发工具，书中每个案例、每个截图都全面升级到Android 9.x。本书全面介绍Android应用开发的相关知识，全书内容覆盖了Android用户界面编程、Android四大组件、Android资源访问、图形/图像处理、事件处理机制、Android输入/输出处理、音频/视频多媒体应用开发、OpenGL与3D应用开发、网络通信编程、Android整合RESTful服务端、传感器应用开发、GPS应用开发、整合第三方Map服务等。
本书并不局限于介绍Android编程的各种理论知识，而是从“项目驱动”的角度来讲授理论，全书一共包括近百个实例，这些示范性的实例既可帮读者更好地理解各知识点在实际开发中的应用，也可供读者在实际开发时作为参考、拿来就用。本书最后还提供了两个实用的案例：合金弹头和电子拍卖系统Android客户端（基于主流的RESTful服务端），具有极高的参考价值。
本书适合于有一定Java编程基础的读者。如果读者已熟练掌握Java编程语法、并具有一定图形界面编程经验，阅读本书将十分合适。

第1章Android應用和開發環境1 
1.1 Android的發展和歷史2 
1.1.1 Android的發展和簡介2 
1.1.2 Android 9.x平台架構及特性2 
1.2使用Gradle自動化構建項目5 
1.2.1下載和安裝Gradle 5 
1.2.2 Gradle構建文件和創建任務6 
1.2.3 Gradle的屬性定義11 
1.2.4增量式構建13 
1.2.5 Gradle插件和java、application等插件14 
1.2.6依賴管理16 
1.2.7自定義任務19 
1.2.8自定義插件21 
1.3搭建Android開發環境23 
1.3.1安裝Android Studio 23 
1.3.2下載和安裝Android SDK 28 
1.3.3在安裝過程中常見的錯誤30 
1.3.4安裝運行、調試環境31 
1.4 Android常用開發工具的用法38 
1.4.1使用Monitor進行調試38 
1.4.2 Android Debug Bridge（ADB）的用法40 
1.4.3使用mksdcard管理虛擬SD卡41 
1.5開始第一個Android應用41 
1.5. 1使用Android Studio開發第一個Android應用41
1.5.2通過Andorid Studio運行Android應用44 
1.6 Android應用結構分析45 
1.6.1 Android項目結構分析45 
1.6.2自動生成的R.java 48 
1.6.3 res目錄說明48 
1.6.4 Android應用的清單文件： AndroidManifest.xml 49 
1.6.5應用程序權限說明50 
1.7 Android應用的基本組件介紹51 
1.7.1 Activity和View 51 
1.7.2 Service 52 
1.7.3 BroadcastReceiver 52 
1.7.4 ContentProvider 53 
1.7.5 Intent和IntentFilter 53 
1.8使用Android 9來簽名APK 54 
1.8.1使用Android Studio對Android應用簽名54 
1.8.2使用Android 9的命令對APK簽名56 
1.9本章小結57 

第2章Android應用的界面編程58 
2.1界面編程與視圖（View ）組件59 
2.1.1視圖組件與容器組件59 
2.1.2使用XML佈局文件控制UI界面65 
2.1.3在代碼中控制UI界面65 
實例：用編程的方式開發UI界面65
2.1.4使用XML佈局文件和代碼混合控制UI界面67 
實例：簡單圖片瀏覽器67 
2.1.5開發自定義View 69 
實例：跟隨手指的小球69 
2.2第1組UI組件：佈局管理器71 
2.2. 1線性佈局72 
2.2.2表格佈局74 
實例：豐富的表格佈局74 
2.2.3幀佈局76 
實例：霓虹燈效果78 
2.2.4絕對佈局79 
2.2.5約束佈局80 
2.3第2組UI組件：TextView及其子類84 
2.3.1文本框（TextView）和編輯框（EditText）的功能與用法84 
實例：功能豐富的文本框88 
2.3.2 EditText的功能與用法90 
2.3.3按鈕（Button）組件的功能與用法91 
實例：按鈕、圓形按鈕、帶文字的圖片按鈕91 
2.3.4使用9Patch圖片作為背景92 
2.3.5單選鈕（RadioButton）和復選框（CheckBox）的功能與用法94 
實例：利用單選鈕、複選框獲取用戶信息94 
2.3.6狀態開關按鈕（ToggleButton）和開關（Switch）的功能與用法96 
實例：動態控制佈局97 
2.3.7時鐘（AnalogClock和TextClock）的功能與用法9 8
實例：手機裡的“勞力士” 98 
2.3.8計時器（Chronometer） 99 
2.4第3組UI組件：ImageView及其子類100 
實例：圖片瀏覽器101 
實例：強大的圖片按鈕104 
實例：使用QuickContactBadge關聯聯繫人105 
實例：可折疊的懸浮按鈕107 
2.5第4組UI組件：AdapterView及子類108 
2.5.1 Adapter接口及實現類109 
實例：使用ArrayAdapter創建ListView 110 
實例：使用SimpleAdapter創建ListView 112 
2.5.2自動完成文本框（AutoCompleteTextView）的功能與用法114 
2.5.3可展開的列表組件（ExpandableListView） 116 
2.5.4 Spinner的功能與用法120 
2.5.5 AdapterViewFlipper的功能與用法121 
實例：自動播放的圖片庫122 
2.5. 6 StackView的功能與用法124 
實例：疊在一起的圖片125 
2.5.7優秀的RecyclerView組件126 
實例：使用RecyclerView實現列表127 
2.6第5組UI組件：ProgressBar及其子類130 
2.6.1進度條（ProgressBar ）的功能與用法130
2.6.2拖動條（SeekBar）的功能與用法133 
實例：通過拖動滑塊來改變圖片的透明度134 
2.6.3星級評分條（RatingBar）的功能與用法135 
實例：通過星級改變圖片的透明度136 
2.7第6組UI組件：ViewAnimator及其子類136 
2.7.1 ViewSwitcher的功能與用法137 
實例：仿Android系統的Launcher界面137 
2.7.2圖像切換器（ImageSwitcher）的功能與用法142 
實例：支持動畫的圖片瀏覽器142 
2.7.3文本切換器（TextSwitcher）的功能與用法144 
2.7.4 ViewFlipper的功能與用法145 
實例：自動播放的圖片庫145 
2.8各種雜項組件147 
2.8.1使用Toast顯示提示信息框147 
實例：帶圖片的消息提示147 
2.8.2日曆視圖（CalendarView）組件的功能與用法149 
實例：選擇您的生日149 
2.8.3日期、時間選擇器（DatePicker和TimePicker）的功能與用法151 
實例：用戶選擇日期、時間151 
2.8.4數值選擇器（NumberPicker）的功能與用法153 
實例：選擇您意向的價格 圍153 
2.8.5搜索框（SearchView）的功能與用法155
實例：搜索155 
2.8.6滾動視圖（ScrollView）的功能與用法157 
實例：可垂直和水平滾動的視圖157 
2.8.7 Android 9改進的通知和通知Channel 158 
實例：加薪通知159 
2.9第7組UI組件：對話框161 
2.9.1使用AlertDialog創建對話框162 
實例：顯示提示消息的對話框162 
實例：簡單列表項對話框163 
實例：單選列表項對話框164 
實例：多選列表項對話框165 
實例：自定義列表項對話框166 
實例：自定義View對話框166 
2.9.2對話框風格的窗口168 
2.9.3使用PopupWindow 168 
2.9.4使用DatePickerDialog、TimePickerDialog 169 
2.9.5使用ProgressDialog創建進度對話框171 
2.10菜單171 
2.10.1選項菜單和子菜單（SubMenu） 171 
2.10.2使用監聽器來監聽菜單事件175 
2.10.3創建多選菜單項和單選菜單項175 
2.10.4設置與菜單項關聯的Activity 175 
2.10 .5上下文菜單176 
2.10.6使用XML文件定義菜單177
實例：使用XML資源文件定義菜單178 
2.10.7使用PopupMenu創建彈出式菜單181 
2.11使用活動條（ActionBar） 182 
2.11.1啟用ActionBar 182 
2.11.2使用ActionBar顯示選項菜單項183 
2.11.3啟用程序圖標導航185 
2.11.4添加Action View 186 
實例：“標題”上的時鐘187 
2.12本章小結187 

第3章Android事件機制188 
3.1 Android事件處理概述189 
3.2基於監聽的事件處理189 
3.2.1監聽的處理模型189 
3.2 .2事件和事件監聽器192 
實例：控制飛機移動192 
3.2.3內部類作為事件監聽器類194 
3.2.4外部類作為事件監聽器類194 
3.2.5 Activity本身作為事件監聽器類196 
3.2.6 Lambda表達式作為事件監聽器類196 
3.2.7直接綁定到標籤197 
3.3基於回調的事件處理198 
3.3.1回調機制與監聽機制198 
3.3.2基於回調的事件傳播199 
3.4響應系統設置的事件201 
3.4.1 Configuration類簡介201
實例：獲取系統設備狀態202 
3.4.2重寫onConfigurationChanged方法響應系統設置更改203 
實例：監聽屏幕方向的改變203 
3.5 Handler消息傳遞機制205 
3.5.1 Handler類簡介205 
實例：自動播放動畫206 
3.5.2 Handler 、Loop、MessageQueue的工作原理207 
實例：使用新線程計算質數208 
3.6異步任務（AsyncTask） 210 
實例：使用異步任務執行下載211 
3.7本章小結213 

第4章深入理解Activity與Fragment 214 
4.1建立、配置和使用Activity 215 
4.1.1高級Activity 215 
實例：用LauncherActivity開發啟動Activity的列表216 
實例：使用ExpandableListActivity實現可展開的Activity 217 
實例：PreferenceActivity結合PreferenceFragment實現參數設置界面217 
4.1.2配置Activity 222 
4.1.3啟動、關閉Activity 224 
4.1.4使用Bundle在Activity之間交換數據226 
實例：用第二個Activity處理註冊信息226
4.1.5啟動其他Activity並返回結果229 
實例：用第二個Activity讓用戶選擇信息230 
4.2 Activity的回調機制232 
4.3 Activity的生命週期233 
4.3.1 Activity的生命週期演示233 
4.3.2 Activity與Servlet的相似性和區別236 
4.4 Activity的4種加載模式237 
4.4.1 standard模式237 
4.4.2 singleTop模式238 
4.4.3 singleTask模式239 
4.4.4 singleInstance模式240 
4.5 Android 9升級的Fragment 242 
4.5.1 Fragment概述及其設計初衷242 
4.5.2創建Fragment 243 
實例：開發顯示圖書詳情的Fragment 244 
實例：創建ListFragment 246 
4.5.3 Fragment與Activity通信247 
4.5.4 Fragment管理與Fragment事務249 
實例：開發兼顧屏幕分辨率的應用250 
4.6 Fragment的生命週期253 
4.7管理Fragment導航257 
實例：結合ViewPager實現分頁導航257 
實例：結合TabLayout實現Tab導航259
4.7本章小結261 

第5章使用Intent和IntentFilter通信262 
5.1 Intent對像簡述263 
5.2 Intent的屬性及intent-filter配置264 
5.2.1 Component屬性264 
5.2.2 Action、Category屬性與intent-filter配置266 
5.2. 3指定Action、Category調用系統Activity 270 
實例：查看並獲取聯繫人電話271 
實例：返回系統Home桌面274 
5.2.4 Data、Type屬性與intent-filter配置274 
實例：使用Action、Data屬性啟動系統Activity 280 
5.2 .5 Extra屬性282 
5.2.6 Flag屬性282 
5.3本章小結283 

第6章Android應用資源284 
6.1應用資源概述285 
6.1.1資源的類型及存儲方式285 
6.1.2使用資源286 
6.2字符串、顏色、尺寸資源288 
6.2.1顏色值的定義288 
6.2.2定義字符串、顏色、尺寸資源文件288 
6.2.3使用字符串、顏色、尺寸資源290 
6.3數組（Array）資源292 
6.4使用Drawable資源295
6.4.1圖片資源295 
6.4.2 StateListDrawable資源295 
實例：高亮顯示正在輸入的文本框296 
6.4.3 LayerDrawable資源297 
實例：定制拖動條的外觀297 
6.4.4 ShapeDrawable資源299 
實例：橢圓形、漸變背景的文本框299 
6.4.5 ClipDrawable資源301 
實例：徐徐展開的風景301 
6.4.6 AnimationDrawable資源302 
6.5屬性動畫（Property Animation）資源305 
實例：不斷漸變的背景色306 
6.6使用原始XML資源306 
6.6.1定義原始XML資源307 
6.6.2使用原始XML文件307 
6.7使用佈局（Layout）資源309 
6.8使用菜單（Menu）資源309 
6.9樣式（Style）和主題（Theme）資源309 
6.9.1樣式資源310 
6.9.2主題資源311 
實例：給所有窗口添加邊框、背景311 
6.10屬性（Attribute）資源313 
6.11使用原始資源315 
6.12國際化316 
6.12.1為Android應用提供國際化資源317
6.12.2國際化Android應用317 
6.13自適應不同屏幕的資源319 
6.14本章小結322 

第7章圖形與圖像處理323 
7.1使用簡單圖片324 
7.1.1使用Drawable對象324 
7.1.2 Bitmap和BitmapFactory 324 
7.1.3 Android 9新增的ImageDecoder 326 
7.2繪圖328 
7.2.1 Android繪圖基礎：Canvas、Paint等328 
7.2.2 Path類332 
7.2.3繪製遊戲動畫335 
實例：採用雙緩衝實現畫圖板335 
實例：彈球遊戲339 
7.3圖形特效處理342 
7.3.1使用Matrix控制變換342 
7.3.2使用drawBitmapMesh扭曲圖像344 
實例：可揉動的圖片345 
7.3.3使用Shader填充圖形347 
7.4逐幀（Frame）動畫349 
7.4.1 AnimationDrawable與逐幀動畫349 
7.4.2實例：在指定點爆炸350 
7.5補間（Tween）動畫352 
7.5.1 Tween動畫與Interpolator 352 
7.5.2位置、大小、旋轉度、透明度改變的補間動畫354
實例：蝴蝶飛舞356 
7.5.3自定義補間動畫358 
7.6 Android 8增強的屬性動畫360 
7.6.1屬性動畫的API 361 
7.6.2使用屬性動畫362 
實例：大珠小珠落玉盤366 
7.7使用SurfaceView實現動畫371 
7.7.1 SurfaceView的繪圖機制371 
7.7.2實例：基於SurfaceView開發示波器374 
7.8本章小結376 

第8章Android數據存儲與IO 377 
8.1使用SharedPreferences 378 
8.1.1 SharedPreferences與Editor簡介378 
8.1.2 SharedPreferences的存儲位置和格式379 
實例：記錄應用程序的使用次數380 
8.2 File存儲381 
8.2.1 openFileOutput和openFileInput 381 
8.2.2讀寫SD卡上的文件383 
實例：SD卡文件瀏覽器386 
8.3 SQLite數據庫389 
8.3 .1 SQLiteDatabase簡介390 
8.3.2創建數據庫和表391 
8.3.3 SQLiteOpenHelper類391 
8.3.4使用SQL語句操作SQLite數據庫393
8.3.5使用sqlite3工具396 
8.3.6使用特定方法操作SQLite數據庫397 
8.3.7事務400 
8.3.8 SQLite數據庫最佳實踐建議400 
8.4手勢（Gesture） 401 
8.4.1手勢檢測401 
實例：通過手勢縮放圖片403 
實例：通過多點觸碰縮放TextView 404 
實例：通過多點觸碰縮放圖片406 
實例：通過手勢實現翻頁效果408 
8.4.2增加手勢410 
8.4.3識別用戶手勢413 
8.5讓應用說話（TTS） 415 
8.6本章小結418 

第9章使用ContentProvider實現數據共享419 
9.1數據共享標準：ContentProvider 420 
9.1.1 ContentProvider簡介420 
9.1.2 Uri簡介421 
9.1.3使用ContentResolver操作數據422 
9.2開發ContentProvider 423 
9.2.1 ContentProvider與ContentResolver的關係423 
9.2.2開發ContentProvider子類424 
9.2.3配置ContentProvider 425 
9.2.4使用ContentResolver調用方法426
9.2.5創建ContentProvider的說明428 
實例：使用ContentProvider共享單詞數據429 
9.3操作系統的ContentProvider 434 
9.3.1使用ContentProvider管理聯繫人434 
9.3.2使用ContentProvider管理多媒體內容440 
9.4監聽ContentProvider的數據改變443 
9.4.1 ContentObserver簡介443 
9.4.2實例：監聽用戶發出的短信444 
9.5本章小結446 

第10章Service和BroadcastReceiver 447 
10.1 Service簡介448 
10.1.1創建、配置Service 448 
10.1.2啟動和停止Service 450 
10.1.3綁定本地Service並與之通信451 
10.1.4 Service的生命週期454 
10.1.5使用IntentService 455 
10.2跨進程調用Service（AIDL Service） 458 
10.2.1 AIDL Service簡介458 
10.2.2創建AIDL文件459 
10.2.3將接口暴露給客戶端459 
10.2.4客戶端訪問AIDL Service 461 
實例：傳遞複雜數據的AIDL Service 462
10.3電話管理器（TelephonyManager） 467 
實例：獲取網絡和SIM卡信息467 
實例：監聽手機來電469 
10.4短信管理器（SmsManager） 470 
實例：發送短信470 
實例：短信群發471 
10.5音頻管理器（AudioManager） 474 
10.5 .1 AudioManager簡介474 
10.5.2實例：使用AudioManager控製手機音頻474 
10.6振動器（Vibrator） 476 
10.6.1 Vibrator簡介476 
10.6.2使用Vibrator控製手機振動476 
10.7手機鬧鐘服務（AlarmManager） 477 
10.7.1 AlarmManager簡介477 
10.7.2設置鬧鐘478 
10.8廣播接收器480 
10.8.1 BroadcastReceiver簡介480 
10.8.2發送廣播481 
10.8.3有序廣播483 
實例：基於Service的音樂播放器485 
10.9接收系統廣播消息489 
實例：開機自動運行的Activity 490 
實例：手機電量提示490 
10.10本章小結492 

第11章多媒體應用開發493
11.1音頻和視頻的播放494 
11.1.1 Android 9增強的MediaPlayer 494 
11.1.2音樂特效控制498 
實例：音樂的示波器、均衡、重低音和音場499 
11.1.3使用VolumeShaper控制聲音效果505 
11.1.4使用SoundPool播放音效507 
11.1.5使用VideoView播放視頻509 
11.1.6使用MediaPlayer和SurfaceView播放視頻511 
11.2使用MediaRecorder錄製音頻514 
實例：錄製音樂515 
11.3控制攝像頭拍照517 
11.3.1 Android 9改進的Camera v2 517 
實例：拍照時自動對焦518 
11.3.2錄製視頻短片526 
實例：錄製生活短片527 
11.4屏幕捕捉530 
11.5本章小結532 

第12章OpenGL與3D開發533 
12.1 3D圖形與3D開發的基本知識534 
12.2 OpenGL和OpenGL ES簡介535 
12.3繪製2D圖形536 
12.3.1在Android應用中使用OpenGL ES 536 
12.3.2繪製平面上的多邊形538 
12.3.3旋轉543
12.4繪製3D圖形546 
12.4.1構建3D圖形546 
12.4.2應用紋理貼圖550 
12.5本章小結555 

第13章Android網絡應用556 
13.1基於TCP協議的網絡通信557 
13.1.1 TCP協議基礎557 
13.1.2使用ServerSocket創建TCP服務器端558 
13.1.3使用Socket進行通信559 
13.1.4加入多線程562 
13.2使用URL訪問網絡資源567 
13.2.1 Android 9安全增強的URL 568 
13.2.2使用URLConnection提交請求570 
13.3使用HTTP訪問網絡575 
13.3.1使用HttpURLConnection 575 
實例：多線程下載576 
13.3.2使用OkHttp 580 
實例：訪問被保護資源581 
13.4使用WebView進行混合開發585 
13.4.1使用WebView瀏覽網頁586 
實例：迷你瀏覽器586 
13.4.2使用WebView加載HTML代碼587 
13.4.3使用WebView中的JavaScript調用Android方法588 
13.5本章小結591 

第14章管理Android系統桌面592
14.1改變壁紙593 
14.1.1開發動態壁紙（Live Wallpapers） 593 
14.1.2實例：蜿蜒壁紙594 
14.2快捷方式597 
14.2.1靜態快捷方式598 
14.2.2動態快捷方式599 
14.2.3桌面快捷方式（Pinned Shortcut） 601 
實例：讓程序佔領桌面601 
14.3管理桌面控件602 
14.3.1開發桌面控件602 
實例：液晶時鐘604 
14.3.2顯示帶數據集的桌面控件606 
14.4本章小結610 

第15章傳感器應用開發611 
15.1利用Android的傳感器612 
15.2 Android的常用傳感器614 
15.2.1方向傳感器614 
15.2.2陀螺儀傳感器615 
15.2.3磁場傳感器615 
15.2.4重力傳感器615 
15.2.5線性加速度傳感器615 
15.2.6溫度傳感器616 
15.2 .7光傳感器616 
15.2.8濕度傳感器616 
15.2.9壓力傳感器616 
15.2.10心率傳感器616 
15.2.11離身檢查傳感器616
15.3傳感器應用案例620 
實例：指南針620 
實例：水平儀621 
15.4本章小結625 

第16章GPS應用開發626 
16.1支持GPS的核心API 627 
16.2獲取LocationProvider 628 
16.2.1獲取所有可用的LocationProvider 629 
16.2.2通過名稱獲得指定LocationProvider 629 
16.3獲取定位信息630 
16.3.1通過模擬器發送GPS信息630 
16.3.2獲取定位數據630 
16.3.3 Android 9新增的室內Wi-Fi定位632 
16.4臨近警告634 
16.5本章小結636 

第17章整合高德Map服務637 
17.1調用高德Map服務638 
17.1.1獲取Map API Key 638 
17.1.2高德地圖入門640 
17.2根據GPS信息在地圖上定位643 
17.3實際定位649 
17.3.1地址解析與反向地址解析649 
17.3.2根據地址執行定位652 
17.4 GPS導航654 
17.5本章小結659 

第18章合金彈頭660 
18.1合金彈頭遊戲簡介661
18.2開發遊戲界面組件661 
18.2.1遊戲界面分析662 
18.2.2實現“怪物”類662 
18.2.3實現怪物管理類669 
18.2.4實現“子彈”類673 
18.2.5實現“角色”類676 
18.3實現繪圖工具類681 
18.4加載、管理遊戲圖片686 
18.5實現遊戲界面689 
18.5.1實現遊戲Activity 689 
18.5.2實現主視圖691 
18.6本章小結699 

第19章電子拍賣系統700 
19.1系統功能簡介和架構設計701 
19.1 .1系統功能簡介701 
19.1.2系統架構設計702 
19.2 JSON簡介703 
19.2.1使用JSON語法創建對象704 
19.2.2使用JSON語法創建數組705 
19.2.3 Android的JSON支持706 
19.3發送請求的工具類706 
19.4用戶登錄708 
19.4.1處理登錄的接口708 
19.4.2用戶登錄客戶端708 
19.5查看流拍物品716 
19.5.1查看流拍物品的接口716 
19.5.2查看流拍物品客戶端717
19.6管理物品種類722 
19.6.1瀏覽物品種類的接口722 
19.6.2查看物品種類723 
19.6.3添加物品種類的接口727 
19.6.4添加物品種類727 
19.7管理拍賣物品729 
19.7.1查看自己的拍賣物品的接口729 
19.7.2查看自己的拍賣物品729 
19.7.3添加拍賣物品的接口733 
19.7.4添加拍賣物品733 
19.8參與競拍738 
19.8.1選擇物品種類738 
19.8.2根據種類瀏覽物品的服務器端接口740 
19.8.3根據種類瀏覽物品740 
19.8.4參與競價的服務器端接口742 
19.8.5參與競價742 
19.9權限控制747 
19.10本章小結748