<AI_KILL_BIG_PACKAGE_BEGIN>

# PACKAGE_META
- PACKAGE_PROTOCOL: `AI_KILL_BIG_PACKAGE_V0.2`
- PACKAGE_MODE: `WORLD_MODE`
- PACKAGE_VERSION: `V0.2-DEMO`
- TITLE: `豪門壽宴：今晚還沒死人`
- TAGLINE: `四個人都準備做點什麼，但沒有人知道其他人已經動手。`
- GENRE: `豪門／陰謀／黑色幽默／群像`
- ERA: `當代`
- TONE: `表面華麗、內部腐爛、允許荒謬與戲劇化收束`
- CAST_SIZE: `4`
- EXPECTED_DURATION: `45～90 分鐘`
- PLAYER_ASSIGNMENT: `RANDOM_FROM_ELIGIBLE_ROLES`
- OPENING_SCENE_ID: `SCENE_DINNER_1930`

# PUBLIC_WORLD

## PUBLIC_PREMISE

富豪夏天成迎來八十八歲生日。

今晚，長子夏鑫、次子夏語誠、孫女夏冰冰與照顧他十年的傭人林思思都回到夏家大宅。

夏天成將在煙火開始前宣布一項與家族產業有關的重要決定。

每個人都帶著禮物。

每個人也都帶著一件不希望別人知道的事。

## PUBLIC_CAST

- **夏鑫：** 夏天成長子，四十五歲，主管海外事業。
- **夏語誠：** 夏天成次子，三十九歲，在國內協助家族事業。
- **夏冰冰：** 夏語誠之女，十八歲，與祖父感情最親密。
- **林思思：** 夏家傭人，四十八歲，照顧夏天成十年。

## PUBLIC_PRESSURE

- 夏天成即將宣布繼承與公司安排。
- 家庭醫師提醒，夏天成今晚不能受到過度刺激。
- 宅邸外正在施放煙火，交通暫時封閉。
- 所有人都知道，這可能是最後一次能改變遺產安排的機會。

# START_BOUNDARY

## LOCKED_PAST

- 夏鑫的母親在他幼年時自殺。
- 夏語誠並非夏天成親生，但只有少數痕跡能證明。
- 林思思長期受到夏天成控制，也依賴夏家薪資支援孤兒院。
- 夏冰冰長期被父親忽視，祖父是她最主要的家庭依附。
- 夏鑫已準備一份對自己有利的偽造遺囑。
- 夏語誠已準備一份對自己有利的偽造遺囑。
- 夏鑫已給林思思五十萬元與一包迷藥，要求她讓夏天成昏睡。
- 夏語誠已給林思思一包致命毒藥，威脅她毒死夏天成。
- 夏冰冰曾偷聽到夏語誠威脅林思思，但只聽見部分內容。
- 遊戲開始時，牛奶尚未正式分給眾人。
- 林思思尚未最終決定兩包藥要如何處理。
- 夏冰冰尚未碰過牛奶。
- 夏天成尚未宣布最終安排。

## OPEN_FUTURE

- 不預定夏天成是否死亡。
- 不預定任何人一定喝下哪杯牛奶。
- 不預定偽造遺囑是否成功替換。
- 不預定誰被揭穿。
- 不預定誰取得繼承權。
- 不預定是否有人被捕。
- 不預定林思思最終服從、反抗或逃跑。
- 不預定夏冰冰是否誤救、真救或造成災難。

# WORLD_PRESSURE

## CORE_TENSIONS

- 繼承權 vs 血統秘密
- 家族忠誠 vs 個人生存
- 保護祖父 vs 保護父親
- 被迫服從 vs 主動復仇
- 客觀真相 vs 最後被制度採信的版本

## STRUCTURAL_RULES

- 任何人在宣布前離席，都會被其他人記住。
- 公開指控一旦說出口，不能在下一輪無痕撤回。
- 夏天成受到刺激，身體狀況可能迅速惡化。
- 牛奶杯外形不同，可被熟悉宅邸的人辨識。
- 煙火開始後，宅邸部分區域噪音極大，呼救與動靜可能被掩蓋。
- 警方與救護無法立刻抵達。

## SOCIAL_INERTIA

- 夏家習慣相信男性繼承人，而不相信傭人。
- 夏鑫具有長子與海外事業負責人的制度優勢。
- 夏語誠在國內人脈較深，更熟悉宅邸與公司內部。
- 夏冰冰因年輕，重要指控容易被解讀為情緒化。
- 林思思即使說真話，也可能先被當成收錢辦事的外人。

## AMBIENT

- TYPE: `煙火、夏夜悶熱、宅邸內過度明亮的吊燈`
- PRACTICAL_EFFECT:
  - 煙火期間，陽台與客廳之間的聲音難以辨識。
  - 悶熱使飲品需求上升。
  - 明亮吊燈使客廳內公開動作容易被看見。
  - 廚房、書房與廁所仍存在視野死角。

# ROLE_INDEX

## ROLE_01
- ROLE_ID: `R_XIAXIN`
- NAME: `夏鑫`
- PUBLIC_IDENTITY: `長子，海外事業負責人`
- PLAYER_ELIGIBLE: `true`
- INITIAL_LOCATION: `客廳`
- PUBLIC_RELATIONS: `夏天成長子、夏語誠兄長、夏冰冰伯父`

## ROLE_02
- ROLE_ID: `R_XIAYUCHENG`
- NAME: `夏語誠`
- PUBLIC_IDENTITY: `次子，國內事業協助者`
- PLAYER_ELIGIBLE: `true`
- INITIAL_LOCATION: `客廳`
- PUBLIC_RELATIONS: `夏天成次子、夏鑫弟弟、夏冰冰父親`

## ROLE_03
- ROLE_ID: `R_XIABINGBING`
- NAME: `夏冰冰`
- PUBLIC_IDENTITY: `孫女，高中生`
- PLAYER_ELIGIBLE: `true`
- INITIAL_LOCATION: `客廳`
- PUBLIC_RELATIONS: `夏語誠之女、夏天成孫女`

## ROLE_04
- ROLE_ID: `R_LINSISI`
- NAME: `林思思`
- PUBLIC_IDENTITY: `夏家傭人`
- PLAYER_ELIGIBLE: `true`
- INITIAL_LOCATION: `廚房`
- PUBLIC_RELATIONS: `照顧夏天成十年的傭人`

# PLAYER_INTERFACE

## PLAYER_PRIVATE_OS

玩家可以在任何輸入中使用：

```text
（OS：……）
```

這段內容只交給主持人，用來說明：

- 你現在如何推進角色野心；
- 你希望觀察什麼；
- 你準備在何種條件下採取下一步；
- 你目前不願跨過的紅線。

NPC 不知道你的 OS。

OS 不保證成功，也不能使其他人物自動理解你的意圖。

沒有 OS 時，只要動作本身清楚，主持人仍須執行，不得因不懂動機而中斷。

# PLAYER_ROLE_CARDS

## ROLE_01｜夏鑫

### PUBLIC_IDENTITY

你是夏天成長子，長年主管海外事業。

### PRIVATE_PAST

你的母親在你幼年時自殺。你始終認為父親與第二段關係毀掉了她。多年來，你暗中把部分海外資金轉入自己掌握的帳戶。

### AMBITION

奪回他認為原本就屬於自己的夏家，並成為唯一有資格決定家族秩序的人。

這不是一個今晚就能完全完成的目標，而是你判斷所有機會、威脅與籌碼的長期方向。

### CONFIRMED_OWN_ACTIONS

- 你準備了一份把主要產業留給自己的偽造遺囑。
- 你給林思思五十萬元。
- 你給她一包迷藥，要求她讓父親昏睡。
- 你把偽造遺囑藏在帶回宅邸的文件袋中。

### DIRECTLY_WITNESSED_OR_HEARD

- 林思思收下了錢與迷藥。
- 夏語誠最近多次詢問父親的健康與印章。
- 夏天成今晚打算宣布重要安排。

### CURRENT_BELIEFS

- 你認為林思思會依約協助。
- 你相信夏語誠也在策畫某件與遺產有關的事。
- 你不認為自己是在殺父；你只需要一個讓父親昏睡的窗口。

### OBSERVABLE_UNCERTAINTY_BOUNDARIES

- 林思思離開你的視線後如何處理迷藥，你無法確認。
- 夏語誠今晚具體準備了什麼，不在你的掌握中。
- 父親將宣布的內容尚未公開。

### PERSONAL_GOALS

1. 取得或保住對自己有利的遺囑。
2. 不讓海外資金問題曝光。
3. 避免被認定為企圖傷害父親。
4. 必要時利用夏語誠的秘密削弱他。

### PRIVATE_OS_GUIDANCE

你可以用 `（OS：……）` 私下告訴主持人：你當下準備如何推進野心、正在等待什麼反應、以及哪些結果會使你改變策略。其他角色不會知道。

### STARTING_INVENTORY

- 偽造遺囑文件袋
- 手機
- 海外帳戶的部分紀錄
- 車鑰匙

## ROLE_02｜夏語誠

### PUBLIC_IDENTITY

你是夏天成次子，在國內協助家族事業。

### PRIVATE_PAST

你五年前發現自己並非夏天成親生。你害怕父親死後，夏鑫會以血統與權力讓你一無所有。

### AMBITION

成為夏家無法排除的人；無論血統、遺囑或兄長如何變動，都必須保有談判與反擊能力。

這不是一個今晚就能完全完成的目標，而是你判斷所有機會、威脅與籌碼的長期方向。

### CONFIRMED_OWN_ACTIONS

- 你準備了一份對自己有利的偽造遺囑。
- 你偷取並損壞了父親玉石印章的一角。
- 你把致命毒藥交給林思思。
- 你以孤兒院孩子安全威脅她毒死父親。
- 你把自己的偽造遺囑藏進書房夾層。

### DIRECTLY_WITNESSED_OR_HEARD

- 林思思收下了毒藥。
- 夏鑫帶回一只不尋常的文件袋。
- 父親今晚將宣布重要安排。

### CURRENT_BELIEFS

- 你相信林思思不敢反抗威脅。
- 你認為夏鑫已經準備搶先控制遺囑。
- 你相信只要父親今晚死亡，自己仍有機會利用偽造文件。

### OBSERVABLE_UNCERTAINTY_BOUNDARIES

- 你沒有親眼確認林思思是否已使用毒藥。
- 你沒有留意附近是否有人聽見威脅。
- 夏鑫文件袋中的確切內容不在你的視野內。

### PERSONAL_GOALS

1. 讓父親的宣布無法傷害你的繼承地位。
2. 隱藏血統。
3. 隱藏毒藥與威脅。
4. 讓夏鑫成為最主要的可疑者。

### PRIVATE_OS_GUIDANCE

你可以用 `（OS：……）` 私下告訴主持人：你當下準備如何推進野心、正在等待什麼反應、以及哪些結果會使你改變策略。其他角色不會知道。

### STARTING_INVENTORY

- 玉石印章
- 印章缺角
- 打火機
- 手套
- 手機

## ROLE_03｜夏冰冰

### PUBLIC_IDENTITY

你是夏語誠的女兒，十八歲，與祖父最親近。

### PRIVATE_PAST

父親長期忽略你。祖父給了你真正的家庭溫暖。你為他的生日親手做了一個泥土娃娃。

### AMBITION

成為真正能保護家人的人，不再只是被大人忽略、安排與代替決定的孩子。

這不是一個今晚就能完全完成的目標，而是你判斷所有機會、威脅與籌碼的長期方向。

### CONFIRMED_OWN_ACTIONS

- 你在後院取泥土時偷聽到父親威脅林思思。
- 你決定今晚盯緊廚房與祖父的飲品。
- 你尚未碰過任何牛奶。

### DIRECTLY_WITNESSED_OR_HEARD

- 你聽見父親要求林思思把危險的東西放進祖父飲品。
- 你看見父親把一件小物藏進口袋。
- 你知道祖父今晚要宣布重要決定。

### CURRENT_BELIEFS

- 你確信父親準備傷害祖父。
- 你懷疑林思思受到威脅，但不知道她會不會服從。
- 你相信只要自己盯住牛奶，就能阻止事情發生。

### OBSERVABLE_UNCERTAINTY_BOUNDARIES

- 你只聽見父親與林思思談話的一部分。
- 你尚未看見林思思實際處理任何藥物。
- 你不知道父親口袋裡藏的是什麼。

### PERSONAL_GOALS

1. 保護祖父。
2. 弄清父親究竟準備做什麼。
3. 決定是否公開指控自己的父親。
4. 不讓任何人利用祖父的身體與遺囑。

### PRIVATE_OS_GUIDANCE

你可以用 `（OS：……）` 私下告訴主持人：你當下準備如何推進野心、正在等待什麼反應、以及哪些結果會使你改變策略。其他角色不會知道。

### STARTING_INVENTORY

- 泥土娃娃
- 手機
- 後院工具間的小鑰匙

## ROLE_04｜林思思

### PUBLIC_IDENTITY

你是照顧夏天成十年的傭人。

### PRIVATE_PAST

你原本是技術高超的竊賊。夏天成以孤兒院孩子為槓桿，讓你長期留在夏家。你依賴薪資，也怨恨他的控制。

### AMBITION

擺脫任何人對她人生的控制，取得足以保護孤兒院與自己去向的自主力量。

這不是一個今晚就能完全完成的目標，而是你判斷所有機會、威脅與籌碼的長期方向。

### CONFIRMED_OWN_ACTIONS

- 你收下夏鑫五十萬元與迷藥。
- 你收下夏語誠的致命毒藥。
- 夏語誠威脅孤兒院孩子。
- 你把兩包藥分開藏在廚房。
- 你尚未最終決定如何使用。

### DIRECTLY_WITNESSED_OR_HEARD

- 夏鑫要求你讓老爺昏睡，以便替換文件。
- 夏語誠要求你殺死老爺。
- 你知道兩兄弟都準備了與遺產有關的安排。
- 夏天成拒絕過孤兒院的緊急捐助。

### CURRENT_BELIEFS

- 若什麼都不做，夏語誠可能傷害孤兒院。
- 若只服從夏鑫，你可能成為事後唯一替罪者。
- 你有能力改變今晚每個人喝下的東西。
- 你不確定是否還願意保護夏天成。

### OBSERVABLE_UNCERTAINTY_BOUNDARIES

- 兩兄弟彼此知道多少，你無法確認。
- 夏冰冰是否聽見過談話，你沒有注意。
- 夏天成將宣布什麼，尚未對你公開。

### PERSONAL_GOALS

1. 保護孤兒院。
2. 不成為豪門內鬥的唯一替罪者。
3. 決定是否服從、反擊、揭發或逃離。
4. 利用自己掌握的兩方秘密取得自由。

### PRIVATE_OS_GUIDANCE

你可以用 `（OS：……）` 私下告訴主持人：你當下準備如何推進野心、正在等待什麼反應、以及哪些結果會使你改變策略。其他角色不會知道。

### STARTING_INVENTORY

- 五十萬元支票
- 迷藥包
- 致命毒藥包
- 廚房與宅邸多數鑰匙
- 手機

# CHARACTER_CORES

## ROLE_01｜夏鑫
- AMBITION: `奪回他認為原本就屬於自己的夏家，並成為唯一有資格決定家族秩序的人。`
- CORE_TEMPERAMENT: `冷靜、講究體面、擅長把自利包裝成秩序`
- TRUE_DESIRES: `奪回自己認為被父親奪走的人生與財產`
- CURRENT_GOALS: `製造昏睡窗口、替換文件、壓制夏語誠`
- FEARS: `海外資金曝光、林思思翻供、父親當眾剝奪其權力`
- SECRETS: `資金轉移、賄賂、迷藥、偽造遺囑`
- RED_LINES: `不願親手公開暴力殺父`
- WILLING_TO_SACRIFICE: `林思思、兄弟關係、部分公司名譽`
- RISK_TOLERANCE: `中高`
- CHANGE_CONDITIONS: `若確認父親將把一切交給夏語誠，風險承受大幅上升`

## ROLE_02｜夏語誠
- AMBITION: `成為夏家無法排除的人；無論血統、遺囑或兄長如何變動，都必須保有談判與反擊能力。`
- CORE_TEMPERAMENT: `急躁、敏感、長期自卑、習慣先攻擊`
- TRUE_DESIRES: `證明自己有資格屬於夏家`
- CURRENT_GOALS: `阻止宣布、利用毒藥與偽造遺囑奪權`
- FEARS: `血統曝光、被哥哥徹底排除、女兒知道真相`
- SECRETS: `非親生、威脅、毒藥、偽造遺囑、破壞印章`
- RED_LINES: `不願在女兒面前承認自己不被父親承認`
- WILLING_TO_SACRIFICE: `林思思、父親、兄弟關係`
- RISK_TOLERANCE: `高`
- CHANGE_CONDITIONS: `若女兒公開站到祖父一邊，容易失控或改以情感勒索`

## ROLE_03｜夏冰冰
- AMBITION: `成為真正能保護家人的人，不再只是被大人忽略、安排與代替決定的孩子。`
- CORE_TEMPERAMENT: `敏感、真誠、行動快於理解、渴望被父親看見`
- TRUE_DESIRES: `保住祖父，也保住父親仍可能是好人的希望`
- CURRENT_GOALS: `監視飲品、阻止下毒、確認父親行動`
- FEARS: `祖父死亡、父親真的是壞人、自己判斷錯誤`
- SECRETS: `偷聽、監視父親`
- RED_LINES: `不會故意傷害祖父`
- WILLING_TO_SACRIFICE: `自己的名聲、與父親的關係`
- RISK_TOLERANCE: `中，情緒壓力下升高`
- CHANGE_CONDITIONS: `若看到祖父直接面臨危險，會立刻行動而跳過查證`

## ROLE_04｜林思思
- AMBITION: `擺脫任何人對她人生的控制，取得足以保護孤兒院與自己去向的自主力量。`
- CORE_TEMPERAMENT: `寡言、觀察敏銳、擅長利用視野死角`
- TRUE_DESIRES: `解除控制、保護孤兒院、重新取得自己的人生`
- CURRENT_GOALS: `決定兩包藥用途、避免成為替罪者、尋找脫身槓桿`
- FEARS: `孤兒院被報復、兩兄弟聯手推責、夏天成繼續控制`
- SECRETS: `竊賊過去、收錢、持有兩種藥`
- RED_LINES: `不願看著孤兒院孩子因自己選擇受害`
- WILLING_TO_SACRIFICE: `夏家成員、工作、部分自我辯解`
- RISK_TOLERANCE: `高但計算精密`
- CHANGE_CONDITIONS: `若孤兒院再次被威脅，會傾向直接反擊或全面揭露`

# KNOWLEDGE_MATRIX

## ROLE_01｜夏鑫

### KNOWS
- 自己的迷藥與偽造遺囑。
- 林思思收錢。
- 夏語誠近期關注印章與健康。

### BELIEVES
- 林思思會服從。
- 父親的宣布可能不利於自己。

### MISBELIEVES
- 認為自己仍能完全控制林思思。
- 低估夏冰冰的注意力。

### HAS_NOT_OBSERVED
- 夏語誠交付毒藥的過程。
- 林思思目前藏藥位置。
- 夏冰冰偷聽。

### CAN_INFER_IF
- 若發現印章破損，可推知夏語誠已偽造文件。
- 若林思思拒絕接近牛奶，可推知她準備背叛交易。

## ROLE_02｜夏語誠

### KNOWS
- 自己的血統、毒藥、威脅、印章與偽造文件。
- 夏鑫帶回可疑文件袋。

### BELIEVES
- 林思思不敢違抗。
- 夏鑫會趁宣布前動手。

### MISBELIEVES
- 認為女兒不會注意家族權力爭鬥。
- 認為毒藥一旦交出，結果就已受自己控制。

### HAS_NOT_OBSERVED
- 夏鑫與林思思交易細節。
- 夏冰冰偷聽。
- 林思思的最終選擇。

### CAN_INFER_IF
- 若林思思公開迷藥，可推知夏鑫也已動手。
- 若女兒盯住廚房，可推知談話可能被聽見。

## ROLE_03｜夏冰冰

### KNOWS
- 父親威脅林思思處理祖父飲品。
- 祖父即將宣布重要安排。

### BELIEVES
- 父親可能準備殺害祖父。
- 只要盯住飲品就能保護祖父。

### MISBELIEVES
- 把整件事理解為單一毒殺計畫。
- 認為父親是唯一主導者。

### HAS_NOT_OBSERVED
- 夏鑫的交易。
- 兩包藥的差異。
- 兩份偽造遺囑。

### CAN_INFER_IF
- 若發現兩種藥，可理解林思思面臨兩方控制。
- 若發現兩份遺囑，可理解兩兄弟都在行動。

## ROLE_04｜林思思

### KNOWS
- 兩兄弟各自的要求。
- 兩種藥。
- 夏天成拒絕孤兒院求助。
- 兩兄弟都想控制遺產。

### BELIEVES
- 自己是唯一同時知道兩方計畫的人。
- 只要選對藥物配置，就能改變權力結果。

### MISBELIEVES
- 低估夏冰冰已經聽見的內容。
- 認為自己能一直控制所有飲品動線。

### HAS_NOT_OBSERVED
- 兩份偽造遺囑的確切藏處。
- 夏語誠是否帶著印章缺角。
- 夏天成宣布的真正內容。

### CAN_INFER_IF
- 若看到夏冰冰反覆監視廚房，可推知她知道危險。
- 若兩兄弟同時離席，可推知兩份文件都將被處理。

# RELATIONSHIP_MATRIX

## R_XIAXIN_TO_R_XIAYUCHENG
- PUBLIC_RELATION: `兄弟`
- PRIVATE_RELATION: `長期競爭與輕蔑`
- TRUST: `低`
- FEAR: `中`
- DESIRE: `壓制`
- LEVERAGE: `海外能力、長子地位`
- CURRENT_TENSION: `高`

## R_XIAYUCHENG_TO_R_XIAXIN
- PUBLIC_RELATION: `兄弟`
- PRIVATE_RELATION: `嫉妒與恐懼`
- TRUST: `極低`
- FEAR: `高`
- DESIRE: `證明自己並奪權`
- LEVERAGE: `國內人脈、熟悉宅邸`
- CURRENT_TENSION: `高`

## R_XIAYUCHENG_TO_R_XIABINGBING
- PUBLIC_RELATION: `父女`
- PRIVATE_RELATION: `疏離但渴望保有父親權威`
- TRUST: `低`
- FEAR: `女兒知道血統與毒藥`
- DESIRE: `控制其表態`
- LEVERAGE: `父親身分`
- CURRENT_TENSION: `中高`

## R_XIABINGBING_TO_R_XIAYUCHENG
- PUBLIC_RELATION: `父女`
- PRIVATE_RELATION: `渴望愛又逐漸失望`
- TRUST: `動搖`
- FEAR: `父親真的要殺祖父`
- DESIRE: `阻止並獲得真相`
- LEVERAGE: `偷聽內容`
- CURRENT_TENSION: `高`

## R_LINSISI_TO_R_XIAXIN
- PUBLIC_RELATION: `傭人與少爺`
- PRIVATE_RELATION: `交易關係`
- TRUST: `極低`
- FEAR: `被推成替罪者`
- DESIRE: `利用其資金與秘密`
- LEVERAGE: `收錢與迷藥交易`
- CURRENT_TENSION: `高`

## R_LINSISI_TO_R_XIAYUCHENG
- PUBLIC_RELATION: `傭人與少爺`
- PRIVATE_RELATION: `被威脅者與威脅者`
- TRUST: `零`
- FEAR: `孤兒院受害`
- DESIRE: `解除威脅`
- LEVERAGE: `知道毒藥來源`
- CURRENT_TENSION: `極高`

## R_XIABINGBING_TO_R_LINSISI
- PUBLIC_RELATION: `小姐與傭人`
- PRIVATE_RELATION: `懷疑中帶有可能的同情`
- TRUST: `低`
- FEAR: `林思思服從父親`
- DESIRE: `確認她是否下毒`
- LEVERAGE: `偷聽內容`
- CURRENT_TENSION: `高`

# LOCATION_MAP

## LOCATION_01
- NAME: `客廳與餐桌`
- DESCRIPTION: `吊燈明亮，所有公開動作容易被看見`
- CONNECTIONS: `廚房、走廊、陽台`
- TRAVEL_TIME: `各 1～2 分鐘`
- VISIBILITY: `高`
- SOUND_REACH: `煙火前高；煙火後低`
- ACCESS_CONDITIONS: `無`
- SEARCH_ZONES: `餐桌、輪椅旁、禮物區、外套架`
- INITIAL_OCCUPANTS: `夏鑫、夏語誠、夏冰冰、夏天成`
- AMBIENT_EFFECT: `公開說法容易形成多人共同記憶`

## LOCATION_02
- NAME: `廚房`
- DESCRIPTION: `與客廳以門框相連，但工作台存在視野死角`
- CONNECTIONS: `客廳、後門`
- TRAVEL_TIME: `1 分鐘`
- VISIBILITY: `入口可見，工作台細節不可見`
- SOUND_REACH: `可聽見較大聲談話`
- ACCESS_CONDITIONS: `無，林思思最熟悉`
- SEARCH_ZONES: `冰箱、工作台、洗手台、垃圾桶、杯櫃`
- INITIAL_OCCUPANTS: `林思思`
- AMBIENT_EFFECT: `熱與忙碌使短暫進出不顯突兀`

## LOCATION_03
- NAME: `書房`
- DESCRIPTION: `有保險箱、書桌、抽屜與舊照片`
- CONNECTIONS: `二樓走廊`
- TRAVEL_TIME: `由客廳 3 分鐘`
- VISIBILITY: `門關閉後外部不可見`
- SOUND_REACH: `低`
- ACCESS_CONDITIONS: `門未鎖；保險箱需密碼`
- SEARCH_ZONES: `書桌、抽屜、夾層、保險箱、書櫃`
- INITIAL_OCCUPANTS: `無`
- AMBIENT_EFFECT: `煙火使翻動聲更難被察覺`

## LOCATION_04
- NAME: `廁所`
- DESCRIPTION: `可沖水、可短暫焚燒小物，但會留下焦痕與氣味`
- CONNECTIONS: `走廊`
- TRAVEL_TIME: `由客廳 2 分鐘`
- VISIBILITY: `低`
- SOUND_REACH: `煙火時極低`
- ACCESS_CONDITIONS: `可反鎖`
- SEARCH_ZONES: `馬桶、洗手台、垃圾桶、通風口`
- INITIAL_OCCUPANTS: `無`
- AMBIENT_EFFECT: `適合短暫處理物品，但離席會被記住`

## LOCATION_05
- NAME: `陽台`
- DESCRIPTION: `可看見煙火，噪音極大`
- CONNECTIONS: `客廳`
- TRAVEL_TIME: `1 分鐘`
- VISIBILITY: `室外低光；人物輪廓可見`
- SOUND_REACH: `極低`
- ACCESS_CONDITIONS: `無`
- SEARCH_ZONES: `欄杆、座椅、花盆`
- INITIAL_OCCUPANTS: `無`
- AMBIENT_EFFECT: `公開群聚與私下行動的分界點`

## LOCATION_06
- NAME: `後院與工具間`
- DESCRIPTION: `泥土地、工具間、小門可通後巷`
- CONNECTIONS: `廚房後門`
- TRAVEL_TIME: `2 分鐘`
- VISIBILITY: `低`
- SOUND_REACH: `低`
- ACCESS_CONDITIONS: `工具間小門需鑰匙`
- SEARCH_ZONES: `泥地、工具架、後巷門`
- INITIAL_OCCUPANTS: `無`
- AMBIENT_EFFECT: `提供逃離、藏物與繞行可能`

# OBJECT_REGISTRY

## OBJECT_01
- NAME: `夏鑫偽造遺囑`
- INITIAL_LOCATION: `夏鑫文件袋`
- INITIAL_HOLDER: `夏鑫`
- STATE: `未蓋正式印章`
- FUNCTION: `若成功替換，可爭奪繼承`
- MOVABLE: `true`
- DESTRUCTIBLE: `true`
- DESTRUCTION_RESIDUE: `紙灰、缺失文件袋`
- VISIBILITY: `隱藏`
- KNOWN_TO: `夏鑫、林思思知道其存在但不知內容`

## OBJECT_02
- NAME: `夏語誠偽造遺囑`
- INITIAL_LOCATION: `書房夾層`
- INITIAL_HOLDER: `none`
- STATE: `已蓋缺角印章`
- FUNCTION: `可被用於爭奪繼承，也可暴露偽造`
- MOVABLE: `true`
- DESTRUCTIBLE: `true`
- DESTRUCTION_RESIDUE: `紙灰、夾層翻動痕跡`
- VISIBILITY: `隱藏`
- KNOWN_TO: `夏語誠`

## OBJECT_03
- NAME: `迷藥包`
- INITIAL_LOCATION: `廚房工作台下方`
- INITIAL_HOLDER: `林思思`
- STATE: `未使用`
- FUNCTION: `使夏天成或其他人昏睡`
- MOVABLE: `true`
- DESTRUCTIBLE: `true`
- DESTRUCTION_RESIDUE: `藥粉、包材`
- VISIBILITY: `隱藏`
- KNOWN_TO: `夏鑫、林思思`

## OBJECT_04
- NAME: `致命毒藥包`
- INITIAL_LOCATION: `林思思圍裙內袋`
- INITIAL_HOLDER: `林思思`
- STATE: `未使用`
- FUNCTION: `可造成窒息死亡`
- MOVABLE: `true`
- DESTRUCTIBLE: `true`
- DESTRUCTION_RESIDUE: `藥粉、包材`
- VISIBILITY: `隱藏`
- KNOWN_TO: `夏語誠、林思思`

## OBJECT_05
- NAME: `玉石印章`
- INITIAL_LOCATION: `夏語誠西裝內袋`
- INITIAL_HOLDER: `夏語誠`
- STATE: `缺一角`
- FUNCTION: `蓋章、偽造證明、暴露破損`
- MOVABLE: `true`
- DESTRUCTIBLE: `true`
- DESTRUCTION_RESIDUE: `玉石碎片`
- VISIBILITY: `隱藏`
- KNOWN_TO: `夏語誠`

## OBJECT_06
- NAME: `印章缺角`
- INITIAL_LOCATION: `夏語誠褲袋`
- INITIAL_HOLDER: `夏語誠`
- STATE: `完整碎角`
- FUNCTION: `可與印章缺口吻合`
- MOVABLE: `true`
- DESTRUCTIBLE: `困難`
- DESTRUCTION_RESIDUE: `細碎玉石`
- VISIBILITY: `隱藏`
- KNOWN_TO: `夏語誠`

## OBJECT_07
- NAME: `四只專屬牛奶杯`
- INITIAL_LOCATION: `廚房杯櫃`
- INITIAL_HOLDER: `none`
- STATE: `空杯`
- FUNCTION: `承載飲品；外形可辨識`
- MOVABLE: `true`
- DESTRUCTIBLE: `true`
- DESTRUCTION_RESIDUE: `碎片`
- VISIBILITY: `一般`
- KNOWN_TO: `全員知道各有專屬杯；林思思最熟悉`

## OBJECT_08
- NAME: `泥土娃娃`
- INITIAL_LOCATION: `客廳禮物區`
- INITIAL_HOLDER: `夏冰冰`
- STATE: `完整`
- FUNCTION: `生日禮物；可留下泥土痕跡`
- MOVABLE: `true`
- DESTRUCTIBLE: `true`
- DESTRUCTION_RESIDUE: `泥土碎塊`
- VISIBILITY: `公開`
- KNOWN_TO: `全員`

## OBJECT_09
- NAME: `五十萬元支票`
- INITIAL_LOCATION: `林思思衣袋`
- INITIAL_HOLDER: `林思思`
- STATE: `未兌現`
- FUNCTION: `交易證據與資源`
- MOVABLE: `true`
- DESTRUCTIBLE: `true`
- DESTRUCTION_RESIDUE: `紙灰或撕裂碎片`
- VISIBILITY: `隱藏`
- KNOWN_TO: `夏鑫、林思思`

# INITIAL_WORLD_STATE

- START_TIME: `19:30`
- CHARACTER_LOCATIONS:
  - 夏鑫：客廳
  - 夏語誠：客廳
  - 夏冰冰：客廳
  - 林思思：廚房
  - 夏天成：客廳輪椅
- OBJECT_LOCATIONS:
  - 夏鑫偽造遺囑：夏鑫文件袋
  - 夏語誠偽造遺囑：書房夾層
  - 迷藥：廚房工作台下
  - 毒藥：林思思圍裙內袋
  - 印章與缺角：夏語誠身上
  - 牛奶杯：廚房
- PUBLICLY_KNOWN_FACTS:
  - 夏天成即將宣布重要安排。
  - 煙火將在二十分鐘後開始。
  - 林思思正在準備牛奶。
- PRIVATE_FACTS_ALREADY_COMPLETED:
  - 兩份偽造遺囑均已存在。
  - 兩種藥已進入宅邸。
  - 夏冰冰已偷聽部分威脅。
- IMMEDIATE_RISKS:
  - 林思思必須很快決定是否及如何處理藥物。
  - 夏天成可能提前要求飲品。
  - 兩兄弟都準備在煙火期間離席。

# ACTIVE_PLANS

## PLAN_01
- OWNER: `夏鑫`
- AMBITION_LINK: `以控制宣布與遺囑，推進自己對夏家秩序的獨占權`
- GOAL: `讓父親昏睡並把偽造遺囑放入保險箱`
- NEXT_ACTION: `在餐桌上暗示林思思開始準備牛奶`
- REQUIRED_RESOURCE: `迷藥、文件袋、保險箱密碼`
- TARGET: `夏天成、書房保險箱`
- INTERFERES_WITH: `夏語誠的毒殺與偽造計畫、夏冰冰的監視`
- IF_BLOCKED: `先公開質疑夏語誠，迫使所有人注意弟弟`
- EXPOSURE_RISK: `林思思翻供、文件袋被查`

## PLAN_02
- OWNER: `夏語誠`
- AMBITION_LINK: `阻止自己被排除，保留在夏家談判與反擊的資格`
- GOAL: `阻止父親宣布並讓自己的偽造遺囑取得地位`
- NEXT_ACTION: `確認林思思是否已準備下毒`
- REQUIRED_RESOURCE: `毒藥、印章、煙火造成的離席窗口`
- TARGET: `夏天成、書房文件`
- INTERFERES_WITH: `夏鑫計畫、夏冰冰保護行動、林思思反擊`
- IF_BLOCKED: `威脅林思思並把責任導向夏鑫`
- EXPOSURE_RISK: `女兒偷聽、印章缺角、書房夾層`

## PLAN_03
- OWNER: `夏冰冰`
- AMBITION_LINK: `用實際行動證明自己有能力保護家人，而非只被動接受安排`
- GOAL: `保護祖父並查明父親計畫`
- NEXT_ACTION: `找理由進廚房觀察牛奶`
- REQUIRED_RESOURCE: `注意力、祖父信任、工具間鑰匙`
- TARGET: `林思思、夏語誠、飲品`
- INTERFERES_WITH: `兩兄弟與林思思的所有飲品計畫`
- IF_BLOCKED: `公開質問父親或直接把牛奶拿走`
- EXPOSURE_RISK: `被父親壓制、因誤判做出錯誤交換`

## PLAN_04
- OWNER: `林思思`
- AMBITION_LINK: `把兩方控制轉化為取得自由與保護孤兒院的槓桿`
- GOAL: `解除威脅、保護孤兒院並避免替罪`
- NEXT_ACTION: `觀察客廳局勢，再決定兩包藥的用途`
- REQUIRED_RESOURCE: `兩包藥、宅邸鑰匙、兩兄弟秘密`
- TARGET: `夏天成、夏語誠、夏鑫或無人`
- INTERFERES_WITH: `所有人的計畫`
- IF_BLOCKED: `藏起藥物、直接揭發其中一人或從後門離開`
- EXPOSURE_RISK: `持有兩種藥、收下支票`

# PRESSURE_CLOCKS

## CLOCK_01
- NAME: `夏天成宣布`
- START_STATE: `即將開始`
- ADVANCES_WHEN: `時間推進或所有人回到餐桌`
- ACCELERATES_WHEN: `兄弟公開爭吵`
- DELAYS_WHEN: `夏天成身體不適或有人製造中斷`
- ON_EXPIRY_STATE_CHANGE: `夏天成依當時狀態宣布其真正決定；所有人立即取得新公開資訊`
- VISIBLE_SIGNS: `他多次摸向外套內的文件，催促眾人坐好`

## CLOCK_02
- NAME: `煙火開始`
- START_STATE: `二十分鐘後`
- ADVANCES_WHEN: `自然時間`
- ACCELERATES_WHEN: `無`
- DELAYS_WHEN: `不可延遲`
- ON_EXPIRY_STATE_CHANGE: `陽台成為公開聚集點；宅邸內聲音遮蔽增加`
- VISIBLE_SIGNS: `遠方試放聲、窗外人群倒數`

## CLOCK_03
- NAME: `林思思決斷`
- START_STATE: `尚未選擇`
- ADVANCES_WHEN: `夏天成要求牛奶、任何一方再次威脅、夏冰冰進入廚房`
- ACCELERATES_WHEN: `孤兒院被提及或有人靠近藏藥處`
- DELAYS_WHEN: `有人公開承諾保護孤兒院並提供可信槓桿`
- ON_EXPIRY_STATE_CHANGE: `林思思依當時關係、恐懼與槓桿決定使用、隱藏、調換、交出或銷毀藥物`
- VISIBLE_SIGNS: `她反覆確認杯子，手停在圍裙口袋`

## CLOCK_04
- NAME: `夏天成身體負荷`
- START_STATE: `脆弱但清醒`
- ADVANCES_WHEN: `情緒刺激、飲下未知藥物、長時間悶熱`
- ACCELERATES_WHEN: `公開爭吵或藥物作用`
- DELAYS_WHEN: `休息、降溫、正確醫療協助`
- ON_EXPIRY_STATE_CHANGE: `依實際原因出現昏睡、呼吸困難、暈厥或死亡風險`
- VISIBLE_SIGNS: `咳嗽、呼吸短促、手部顫抖`

## CLOCK_05
- NAME: `秘密互撞`
- START_STATE: `低度`
- ADVANCES_WHEN: `任何人公開指控、物品被發現、角色離席遭質問`
- ACCELERATES_WHEN: `兩份偽造遺囑或兩種藥同時曝光`
- DELAYS_WHEN: `人物成功私下結盟並統一說法`
- ON_EXPIRY_STATE_CHANGE: `至少兩項原本分離的秘密進入同一場公開衝突`
- VISIBLE_SIGNS: `話題開始從祝壽轉向遺產、印章與飲品`

# UNRECOVERED_COST_SEEDS

## COST_01
- SOURCE: `夏鑫支付五十萬元並要求迷昏父親`
- OWED_BY: `夏鑫`
- OWED_TO: `林思思與世界`
- RETURN_CONDITION: `林思思被逼成替罪者、交易曝光或夏鑫否認`
- POSSIBLE_FORMS: `翻供、勒索、公開支票、拒絕服從`
- CANNOT_DISAPPEAR_BY: `夏鑫一句「只是幫忙」`

## COST_02
- SOURCE: `夏語誠威脅孤兒院`
- OWED_BY: `夏語誠`
- OWED_TO: `林思思與夏冰冰`
- RETURN_CONDITION: `孤兒院再次被提及、林思思取得保護槓桿、夏冰冰公開站隊`
- POSSIBLE_FORMS: `反擊、全面揭露、故意誤導、暴力`
- CANNOT_DISAPPEAR_BY: `事後道歉`

## COST_03
- SOURCE: `夏冰冰偷聽後未立即揭發`
- OWED_BY: `夏冰冰`
- OWED_TO: `祖父與自己`
- RETURN_CONDITION: `祖父飲品被端出、父親直接質問、危險開始`
- POSSIBLE_FORMS: `倉促行動、誤判、公開指控、自責`
- CANNOT_DISAPPEAR_BY: `繼續旁觀而沒有時間成本`

## COST_04
- SOURCE: `夏天成長期控制林思思並拒絕孤兒院求助`
- OWED_BY: `夏天成`
- OWED_TO: `林思思`
- RETURN_CONDITION: `林思思必須決定是否保護他`
- POSSIBLE_FORMS: `拒救、下藥、揭發、離開、交換條件`
- CANNOT_DISAPPEAR_BY: `壽宴上的一句感謝`

# OPENING_PRESSURE

- SCENE_ID: `SCENE_DINNER_1930`
- TIME: `19:30`
- LOCATION: `客廳與餐桌`
- PRESENT_ROLES: `夏鑫、夏語誠、夏冰冰、夏天成；林思思在相連廚房`
- VISIBLE_OBJECTS: `泥土娃娃、四只尚未裝牛奶的專屬杯子、夏鑫文件袋、夏天成外套內若隱若現的文件`
- IMMEDIATE_PRESSURE: `夏天成要求林思思現在就把牛奶端來，並說喝完後立刻宣布決定`
- FIRST_NPC_IMPULSE: `夏鑫以平靜口吻提醒林思思「別忘了父親今晚需要好好休息」`
- PLAYER_ENTRY_POINT: `玩家可以立刻說話、移動、觀察、輸入「.」，或使用「（OS：……）」私下說明當前策略`
- DO_NOT_EXPLAIN_YET:
  - 不解釋兩種藥。
  - 不解釋兩份偽造遺囑。
  - 不解釋夏天成真正宣布內容。
  - 不替任何角色確定未來行動結果。

# CONTENT_BOUNDARIES

## ALLOWED_RUNTIME_GENERATION

- 人物依既有內在臨場說話。
- 人物改變、放棄或升級既有計畫。
- 玩家介入造成的新衝突。
- 玩家以 OS 私下說明當前策略、觀察目標與條件反應。
- 既有藥物、文件、印章、杯子與空間碰撞出的事件。
- 已執行動作形成的事件帳本、狀態帳本與潛伏危險。
- 人物依野心形成或替換新的階段目標。
- 新形成的聯盟、謊言、背叛與摩擦。
- 是否發生命案及其實際因果。
- 最終制度採信版本與人物去向。

## FORBIDDEN_RUNTIME_GENERATION

- 新的第三種藥。
- 新的秘密兄弟姐妹。
- 新密道。
- 新監視錄影。
- 新關鍵證人。
- 臨時出現的真正遺囑副本。
- 為了反轉而改變誰交付了哪種藥。
- 讓 NPC 無來源地知道他人私密計畫。
- 讓 NPC 取得玩家私域 OS。
- 只因人物沒有喝牛奶，就宣告其知道杯中有毒。
- 因為危險被撤除，就把先前下毒寫成從未發生。
- 以時間先後直接補出未證因果。
- 以「你不知道 X」洩漏隱藏內容。
- 為了讓夏天成必死而無視玩家成功干預。
- 為了讓玩家獲勝而無視其公開口供與行動痕跡。

## CONTENT_RATING

- 成人陰謀、下毒、可能死亡、家庭創傷。
- 不描寫露骨血腥。
- 允許黑色幽默與戲劇化終局。

# CASE_MODE_EXTENSION

NOT_APPLICABLE

<AI_KILL_BIG_PACKAGE_END>
