PlayerAccount:SaveToDB -- 플레이어 계정 정보를 데이터베이스에 저장하는 함수
PlayerAccount:OnLoadedDataFromDB -- 데이터베이스에서 로드된 계정 데이터를 처리하는 함수
PlayerAccount:OnCreated -- 계정 생성 시 생성일시를 설정하는 함수
PlayerAccount:OnLogin -- 플레이어 로그인 시 로그인 시간을 기록하는 함수
PlayerAccount:OnLogout -- 플레이어 로그아웃 시 로그아웃 시간을 기록하는 함수
PlayerAchievement:SaveToDB -- 업적 데이터를 데이터베이스에 저장하는 함수
PlayerAchievement:OnLoadedDataFromDB -- 데이터베이스에서 업적 데이터를 로드하고 초기화하는 함수
PlayerAchievement:InitComponent -- 업적 컴포넌트를 초기화하는 함수
PlayerAchievement:ChangeProgress -- 업적 진행도를 변경하는 함수
PlayerAchievement:RequestChangeProgress -- 클라이언트에서 업적 진행도 변경을 요청하는 함수
PlayerAchievement:SetComplete -- 업적 완료 상태를 설정하고 보상을 지급하는 함수
PlayerAchievement:RequestSetComplete -- 업적 완료 요청을 처리하고 조건을 확인하는 함수
PlayerAchievement:SetAchieved -- 업적 달성 상태를 설정하고 관련 이벤트를 처리하는 함수
PlayerAchievement:OnSyncProperty -- 동기화된 속성 변경 시 UI 업데이트를 처리하는 함수
PlayerAchievement:ReturnAchievementIdByType -- 업적 타입에 따라 해당하는 업적 ID를 반환하는 함수
PlayerAchievement:RequestUpdateUIAchievement -- 업적 UI 업데이트를 요청하는 함수
PlayerAchievement:SetAchievementRedDot -- 업적 메뉴의 빨간 점 표시를 설정하는 함수
PlayerAchievement:IsAnyAchievementAchievedInTab -- 특정 탭에서 달성된 업적이 있는지 확인하는 함수
PlayerAchievement:RequestGainAllReward -- 모든 달성된 업적의 보상을 일괄 수령하는 함수
PlayerAchievement:IsAchievementComplete -- 업적이 완료되었는지 확인하는 함수
PlayerAchievement:IsAchievementAchieved -- 업적이 달성되었는지 확인하는 함수
PlayerAchievement:ReturnAchievementProgress -- 업적 타입의 현재 진행도를 반환하는 함수
PlayerAchievement:RequestSetMultipleComplete -- 여러 업적을 동시에 완료 처리하는 함수
PlayerAchievement:CheckCanEventCompleted -- 업적 달성에 따른 이벤트 발생 가능성을 확인하는 함수
PlayerAchievement:SetInitialTypeValue -- 업적 타입의 초기값을 설정하는 함수
PlayerAchievement:ChangeAllAchieveCompleteForCheat -- 치트용 모든 업적을 완료 상태로 변경하는 함수
PlayerBadge:SaveToDB -- 배지 데이터를 데이터베이스에 저장하는 함수
PlayerBadge:OnLoadedDataFromDB -- 데이터베이스에서 배지 데이터를 로드하는 함수
PlayerBadge:ChangeProgress -- 배지 진행도를 변경하고 달성 여부를 확인하는 함수
PlayerBadge:CheckBadgeAchieved -- 진행도에 따라 배지 달성 여부를 확인하는 함수
PlayerBadge:SetBadgeAchieved -- 배지 달성 상태를 설정하는 함수
PlayerBadge:GetBadgeAchievedFromPlatform -- 플랫폼에서 배지 달성 정보를 가져오는 함수
PlayerBadge:BadgeLog -- 배지 달성 로그를 기록하는 함수
PlayerCollection:SaveToDB -- 수집 데이터를 데이터베이스에 저장하는 함수
PlayerCollection:OnLoadedDataFromDB -- 데이터베이스에서 수집 데이터를 로드하는 함수
PlayerCollection:AddIngredientCollection -- 재료 수집에 새로운 재료를 추가하는 함수
PlayerCollection:AddBunCollection -- 번 수집에 새로운 번을 추가하는 함수
PlayerCollection:RequestGetIngredientCollectionReward -- 재료 수집 보상을 요청하는 함수
PlayerCollection:GetIngredientCollectionReward -- 재료 수집 보상을 지급하는 함수
PlayerCollection:RequestGetBunCollectionReward -- 번 수집 보상을 요청하는 함수
PlayerCollection:GetBunCollectionReward -- 번 수집 보상을 지급하는 함수
PlayerCollection:RequestAddBunSkinCollection -- 번 스킨 수집 추가를 요청하는 함수
PlayerCollection:AddBunSkinCollection -- 번 스킨 수집에 새로운 스킨을 추가하는 함수
PlayerCollection:CheckCanGetBunSkin -- 번 스킨 획득 가능 여부를 확인하는 함수
PlayerCollection:OnSyncProperty -- 동기화된 속성 변경 시 UI 업데이트를 처리하는 함수
PlayerCollection:AddSideMenuCollection -- 사이드 메뉴 수집에 새로운 메뉴를 추가하는 함수
PlayerCollection:RequestAddSideMenuCollection -- 사이드 메뉴 수집 추가를 요청하는 함수
PlayerCollection:CheckCanGetSideMenu -- 사이드 메뉴 획득 가능 여부를 확인하는 함수
PlayerCollection:RequestSetSideMenuChecked -- 사이드 메뉴 확인 상태를 설정하는 함수
PlayerCollection:IngreCollectionFlowLog -- 재료 수집 플로우 로그를 기록하는 함수
PlayerCollection:GetCollectionRate -- 선택된 탭의 수집 완료율을 계산하여 반환하는 함수
PlayerCollection:AddStrategyCollection -- 전략 수집에 새로운 전략을 추가하는 함수
PlayerCollection:RequestAddStrategyCollection -- 전략 수집 추가를 요청하고 조건을 확인하는 함수
PlayerDBManager:OnBeginPlay -- 게임 시작 시 데이터베이스 초기화 및 로드를 수행하는 함수
PlayerDBManager:OnMapEnter -- 맵 진입 시 로비 관련 초기화를 수행하는 함수
PlayerDBManager:SaveToDB -- 플레이어 데이터를 데이터베이스에 저장하는 함수
PlayerDBManager:ClearStageDB -- 스테이지 데이터베이스를 삭제하는 함수
PlayerDBManager:LoadFromDB -- 데이터베이스에서 플레이어 데이터를 로드하는 함수
PlayerDBManager:OnLoadedDataFromStageDB -- 스테이지 데이터베이스에서 데이터를 로드하는 함수
PlayerDBManager:CallAfterEveryDataLoaded -- 모든 데이터 로드 완료 후 초기화 작업을 수행하는 함수
PlayerDBManager:ConnetLog -- 연결 로그를 기록하는 함수
PlayerDBManager:DBErrorLog -- 데이터베이스 오류 로그를 기록하는 함수
PlayerDBManager:InitComponents -- 모든 플레이어 컴포넌트를 초기화하는 함수
PlayerDBManager:HandleUserLeaveEvent -- 사용자 나가기 이벤트를 처리하는 핸들러
PlayerDialog:OnMapEnter -- 인트로 맵 진입 시 인트로 다이얼로그를 시작하는 함수
PlayerEvent:SaveToDB -- 이벤트 데이터를 데이터베이스에 저장하는 함수
PlayerEvent:OnLoadedDataFromDB -- 데이터베이스에서 이벤트 데이터를 로드하는 함수
PlayerEvent:InitComponent -- 이벤트 컴포넌트를 초기화하는 함수
PlayerEvent:OnSyncProperty -- 동기화된 속성 변경 시 UI 업데이트를 처리하는 함수
PlayerEvent:IsEventOccured -- 특정 이벤트가 발생했는지 확인하는 함수
PlayerEvent:SetEventOccured -- 이벤트를 발생 상태로 설정하는 함수
PlayerEvent:AddToEventQueue -- 이벤트를 이벤트 큐에 추가하는 함수
PlayerEvent:RequestAddToEventQueue -- 이벤트 큐 추가를 요청하는 함수
PlayerEvent:RemoveFromEventQueue -- 이벤트 큐에서 이벤트를 제거하는 함수
PlayerEvent:RequestRemoveFromEventQueue -- 이벤트 큐 제거를 요청하는 함수
PlayerEvent:AddToDayEventQueue -- 일일 이벤트 큐에 이벤트를 추가하는 함수
PlayerEvent:RequestAddToDayEventQueue -- 일일 이벤트 큐 추가를 요청하는 함수
PlayerEvent:RemoveAndCallEventFromEventQueue -- 이벤트 큐에서 제거하고 이벤트를 호출하는 함수
PlayerEvent:RequestRemoveAndCallEventFromEventQueue -- 이벤트 큐에서 제거 및 호출을 요청하는 함수
PlayerEvent:RequestSetEventReferKey -- 이벤트 참조 키 설정을 요청하는 함수
PlayerEvent:SetEventReferKey -- 이벤트 참조 키를 설정하는 함수
PlayerEvent:RequestClearEventData -- 이벤트 데이터를 지우는 요청을 처리하는 함수
PlayerEvent:ForceSetEventOccured -- 이벤트를 강제로 발생 상태로 설정하는 함수
PlayerEvent:CheckEventCallbackOccured -- 이벤트 콜백 발생 여부를 확인하는 함수
PlayerEvent:SetToDoSecretaryChecked -- 할 일 비서 확인 상태를 설정하는 함수
PlayerEvent:RequestSetToDoSecretaryChecked -- 할 일 비서 확인 상태 설정을 요청하는 함수
PlayerEvent:RefreshToDoSecretaryInfo -- 할 일 비서 정보를 새로고침하는 함수
PlayerEvent:RequestSetAllToDoSecretaryChecked -- 모든 할 일 비서를 확인 상태로 설정하는 함수
PlayerEvent:RefreshAllToDoSecretaryInfo -- 모든 할 일 비서 정보를 새로고침하는 함수
PlayerEvent:TutorialStartLog -- 튜토리얼 시작 로그를 기록하는 함수
PlayerEvent:TutorialEndLog -- 튜토리얼 종료 로그를 기록하는 함수
PlayerEvent:CheckTutorialEndLog -- 튜토리얼 종료 로그를 확인하는 함수
PlayerEvent:RemoveFromDayEventQueue -- 일일 이벤트 큐에서 이벤트를 제거하는 함수
PlayerEvent:RequestCallEvent -- 이벤트 호출을 요청하는 함수
PlayerEvent:HandlePlayerTrainingTokenChangedEvent -- 플레이어 훈련 토큰 변경 이벤트를 처리하는 핸들러
PlayerEvent:HandlePlayerMoneyChangedEvent -- 플레이어 돈 변경 이벤트를 처리하는 핸들러
PlayerEventFunction:OnBeginPlay -- 이벤트 함수들을 등록하는 초기화 함수
PlayerEventFunction:RegisterFunc -- 함수를 명령어 테이블에 등록하는 함수
PlayerEventFunction:CommandFunc -- 이벤트 그룹 ID에 따라 해당 함수를 실행하는 함수
PlayerEventFunction:GetItem -- 이벤트를 통해 아이템을 지급하는 함수
PlayerEventFunction:AddSubscription -- 이벤트를 통해 구독권을 추가하는 함수
PlayerEventFunction:OpenTrial -- 비공식 시험을 여는 함수
PlayerEventFunction:GetStoreRankingReward -- 상점 랭킹 보상을 지급하는 함수
PlayerEventFunction:SetRedDot -- 메뉴 빨간 점을 설정하는 함수
PlayerEventFunction:OpenVIPOrder -- VIP 주문을 여는 함수
PlayerEventFunction:ModifyReputation -- 평판을 수정하는 함수
PlayerEventFunction:ClearAllUI -- 모든 UI를 지우는 함수
PlayerIngameManager:SaveToDB -- 인게임 매니저 데이터를 데이터베이스에 저장하는 함수
PlayerIngameManager:OnLoadedDataFromDB -- 데이터베이스에서 인게임 데이터를 로드하는 함수
PlayerIngameManager:InitComponent -- 인게임 매니저 컴포넌트를 초기화하는 함수
PlayerIngredient:SaveToDB -- 재료 데이터를 데이터베이스에 저장하는 함수
PlayerIngredient:OnLoadedDataFromDB -- 데이터베이스에서 재료 데이터를 로드하는 함수
PlayerIngredient:InitComponent -- 컴포넌트 초기화 시 모든 재료 데이터를 초기화하는 함수
PlayerIngredient:AddIngredientCard -- 재료 카드를 추가하는 함수
PlayerIngredient:RemoveIngredientCard -- 재료 카드를 제거하는 함수
PlayerIngredient:CanUseIngredientCard -- 재료 카드 사용 가능 여부를 확인하는 함수
PlayerIngredient:AddBun -- 번(빵)을 추가하는 함수
PlayerIngredient:RemoveBun -- 번을 제거하는 함수
PlayerIngredient:CanUseBun -- 번 사용 가능 여부를 확인하는 함수
PlayerIngredient:SetBunFunction -- 번 기능을 설정하는 함수
PlayerIngredient:RequestSetBun -- 번 설정을 요청하는 함수
PlayerIngredient:RequestOpenIngredientGacha -- 재료 가차 오픈을 요청하는 함수
PlayerIngredient:ProcessOpenIngredientGacha -- 재료 가챠를 열어서 결과를 처리하는 함수
PlayerIngredient:ProcessIngredientGacha -- 재료 가차 결과를 처리하는 함수
PlayerIngredient:SendGachaResult -- 가차 결과를 클라이언트에 전송하는 함수
PlayerIngredient:OnSyncProperty -- 동기화된 속성 변경 시 UI 업데이트를 처리하는 함수
PlayerIngredient:ChangeConnectingStatus -- 연결 상태를 변경하는 함수
PlayerIngredient:AddToIngreSubscriptionBox -- 재료 구독 상자에 아이템을 추가하는 함수
PlayerIngredient:GetIngreSubscriptionBox -- 재료 구독 상자를 수령하는 함수
PlayerIngredient:RequestGetIngreSubscriptionBox -- 재료 구독 상자 수령을 요청하는 함수
PlayerIngredient:InitIngreCards -- 초기 재료 카드들을 지급하는 함수
PlayerIngredient:IngreFlowLog -- 재료 플로우 로그를 기록하는 함수
PlayerInventory:SaveToDB -- 인벤토리 데이터를 데이터베이스에 저장하는 함수
PlayerInventory:OnLoadedDataFromDB -- 데이터베이스에서 인벤토리 데이터를 로드하는 함수
PlayerInventory:InitComponent -- 인벤토리 컴포넌트를 초기화하는 함수
PlayerInventory:AddItem -- 아이템을 인벤토리에 추가하는 함수
PlayerInventory:AddItems -- 여러 아이템을 인벤토리에 추가하는 함수
PlayerInventory:RemoveItem -- 인벤토리에서 아이템을 제거하는 함수
PlayerInventory:CanUseItem -- 아이템 사용 가능 여부를 확인하는 함수
PlayerInventory:RemoveItems -- 여러 아이템을 인벤토리에서 제거하는 함수
PlayerInventory:ClearItems -- 모든 아이템을 지우는 함수
PlayerInventory:RequestUseItem -- 아이템 사용을 요청하는 함수
PlayerInventory:RequestAddItem -- 아이템 추가를 요청하는 함수
PlayerInventory:ModifyMoney -- 돈을 증가 또는 감소시키는 함수
PlayerInventory:AddMoney -- 돈을 추가하는 함수
PlayerInventory:SubMoney -- 돈을 차감하는 함수
PlayerInventory:OnSyncProperty -- 동기화된 속성 변경 시 UI 업데이트를 처리하는 함수
PlayerInventory:AddLunchBox -- 도시락을 추가하는 함수
PlayerInventory:SubLunchBox -- 도시락을 차감하는 함수
PlayerInventory:ModifyLunchBox -- 도시락 수량을 증가 또는 감소시키는 함수
PlayerInventory:ModifyArcaneSymbol -- 아케인 심볼을 증가 또는 감소시키는 함수
PlayerInventory:AddArcaneSymbol -- 아케인 심볼을 추가하는 함수
PlayerInventory:SubArcaneSymbol -- 아케인 심볼을 차감하는 함수
PlayerInventory:ModifyHeart -- 하트를 증가 또는 감소시키는 함수
PlayerInventory:AddHeart -- 하트를 추가하는 함수
PlayerInventory:SubHeart -- 하트를 차감하는 함수
PlayerInventory:ModifyTip -- 팁을 증가 또는 감소시키는 함수
PlayerInventory:AddTip -- 팁을 추가하는 함수
PlayerInventory:SubTip -- 팁을 차감하는 함수
PlayerInventory:RequestUseTip -- 팁 사용을 요청하여 하트로 전환하는 함수
PlayerInventory:SubMoneyUnderZero -- 돈을 차감하여 음수가 되도록 하는 함수
PlayerInventory:AddLunchBoxGaugePerDay -- 매일 도시락 게이지를 추가하는 함수
PlayerInventory:CalcLunchBoxRemainDay -- 도시락 남은 일수를 계산하는 함수
PlayerInventory:RefreshLunchBoxRemainDay -- 도시락 남은 일수 UI를 새로고침하는 함수
PlayerInventory:UpdateLunchBoxUpgradeInfo -- 도시락 업그레이드 정보를 업데이트하는 함수
PlayerInventory:ModifyTrainingTicket -- 훈련 티켓 수량을 수정하는 함수
PlayerInventory:CheckTrainingRedDot -- 훈련 메뉴의 빨간점 표시 여부를 확인하는 함수
PlayerInventory:ModifyReputation -- 평판을 증가 또는 감소시키는 함수
PlayerInventory:AddReputation -- 평판을 추가하는 함수
PlayerInventory:SubReputation -- 평판을 차감하는 함수
PlayerInventory:UseItem -- 아이템을 사용하는 함수
PlayerInventory:GetItemCount -- 특정 아이템의 보유 개수를 반환하는 함수
PlayerInventory:IsItemOverMaxCount -- 아이템이 최대 보유 수량을 초과하는지 확인하는 함수
PlayerItemFunction:OnBeginPlay -- 아이템 함수들을 등록하는 초기화 함수
PlayerItemFunction:RegisterFunc -- 함수를 명령어 테이블에 등록하는 함수
PlayerItemFunction:CommandFunc -- 아이템 ID에 따라 해당 함수를 실행하는 함수
PlayerItemFunction:OpenPackage -- 패키지 아이템을 열어서 내용물을 지급하는 함수
PlayerItemFunction:OpenIngreBox -- 재료 상자를 열어서 가챠를 진행하는 함수
PlayerItemFunction:UsePotionCook -- 요리사 포션을 사용하여 경험치를 지급하는 함수
PlayerItemFunction:UsePotionServing -- 서빙 포션을 사용하여 경험치를 지급하는 함수
PlayerItemFunction:UseOverLimitCook -- 요리사 한계 돌파 아이템을 사용하는 함수
PlayerItemFunction:UseOverLimitServing -- 서빙 한계 돌파 아이템을 사용하는 함수
PlayerItemFunction:AddSubscription -- 구독권을 추가하는 함수
PlayerItemFunction:AddBunSkin -- 번 스킨을 추가하는 함수
PlayerLog:OnBeginPlay -- 로그 카테고리 플로우 타입을 초기화하는 함수
PlayerLog:PlayflowLog -- 플레이 플로우 로그를 기록하는 함수
PlayerLog:ResourceFlow -- 리소스 플로우 로그를 기록하는 함수
PlayerLog:ItemFlow -- 아이템 플로우 로그를 기록하는 함수
PlayerLog:ConnectFlow -- 연결 플로우 로그를 기록하는 함수
PlayerLog:AutoTrainingFlow -- 자동 훈련 플로우 로그를 기록하는 함수
PlayerLog:RecipeFlow -- 레시피 플로우 로그를 기록하는 함수
PlayerLog:UpgradeFlow -- 업그레이드 플로우 로그를 기록하는 함수
PlayerLog:EmployeeUpgradeFlow -- 직원 업그레이드 플로우 로그를 기록하는 함수
PlayerLog:EmployeeOvelimitFlow -- 직원 한계돌파 플로우 로그를 기록하는 함수
PlayerLog:RankFlow -- 랭킹 플로우 로그를 기록하는 함수
PlayerLog:AchievementFlow -- 업적 플로우 로그를 기록하는 함수
PlayerLog:TrialEmployee -- 직원 시련 플로우 로그를 기록하는 함수
PlayerLog:TrialRecipe -- 레시피 시련 플로우 로그를 기록하는 함수
PlayerLog:RequestMenuLog -- 메뉴 로그 기록을 요청하는 함수
PlayerLog:MenuFlow -- 메뉴 플로우 로그를 기록하는 함수
PlayerLog:EmployeeLocation -- 직원 위치 변경 로그를 기록하는 함수
PlayerLog:EmployeeFlow -- 직원 플로우 로그를 기록하는 함수
PlayerLog:GetRewardStr -- 보상 테이블을 문자열로 변환하는 함수
PlayerLog:ExchangeFlow -- 교환 플로우 로그를 기록하는 함수
PlayerLog:VerificationRecipe -- 레시피 검증 로그를 기록하는 함수
PlayerLog:GetArrayStr -- 테이블을 배열 문자열로 변환하는 함수
PlayerManagement:SaveToDB -- 매니지먼트 데이터를 데이터베이스에 저장하는 함수
PlayerManagement:OnLoadedDataFromDB -- 데이터베이스에서 매니지먼트 데이터를 로드하는 함수
PlayerManagement:InitComponent -- 매니지먼트 컴포넌트를 초기화하는 함수
PlayerManagement:SetCurrentGoalsProgress -- 현재 목표의 진행도를 설정하는 함수
PlayerManagement:ManagementLevelUp -- 매니지먼트 레벨을 상승시키는 함수
PlayerManagement:OnSyncProperty -- 동기화된 속성 변경 시 UI 업데이트를 처리하는 함수
PlayerManagement:RequestManagementLevelUp -- 매니지먼트 레벨 업 요청을 처리하는 함수
PlayerManagement:ChangeConnectingStatus -- 연결 상태를 변경하는 함수
PlayerManagement:SetStoreRanking -- 상점 랭킹을 설정하고 보상을 지급하는 함수
PlayerManagement:RequestSetStoreRanking -- 상점 랭킹 설정을 요청하는 함수
PlayerManagement:CheckRankingAnnounceDay -- 랭킹 발표일을 확인하는 함수
PlayerManagement:ReturnSurroundingsData -- 주변 랭킹 데이터를 반환하는 함수
PlayerManagement:CheckRankingExplainDay -- 랭킹 설명일을 확인하는 함수
PlayerManagement:RequestSetRankingSpeech -- 랭킹 연설 설정을 요청하는 함수
PlayerManagement:SetRankingSpeech -- 랭킹 연설을 설정하는 함수
PlayerManagement:GetGoalCount -- 달성된 목표 수를 반환하는 함수
PlayerManagement:CheckGoalsAchieved -- 목표 달성 여부를 확인하고 처리하는 함수
PlayerManagement:RequestSetIsEndingEventSeen -- 엔딩 이벤트 시청 여부를 설정하는 함수
PlayerManagement:GetIsEndingEventSeen -- 엔딩 이벤트 시청 여부를 반환하는 함수
PlayerManagement:AddReputationLog -- 평판 로그를 추가하는 함수
PlayerManagement:UpdateReputationLogOnDayChanged -- 날짜 변경 시 평판 로그를 업데이트하는 함수
PlayerManagement:RequestSyncReputationLogs -- 평판 로그 동기화를 요청하는 함수
PlayerManagement:SyncReputationLogs -- 평판 로그를 동기화하는 함수
PlayerManagement:SetManagementLevel -- 매니지먼트 레벨을 설정하는 함수
PlayerManagement:UpdateReputationDailyLogs -- 일일 평판 로그를 업데이트하는 함수
PlayerManagement:InitBoosterPackPurchase -- 부스터 팩 구매 정보를 초기화하는 함수
PlayerManagement:OnBoosterPackPurchased -- 부스터 팩 구매 시 처리하는 함수
PlayerManagement:IsPreminumBoosterPackPurchased -- 프리미엄 부스터 팩 구매 여부를 확인하는 함수
PlayerManagement:RequestReexamRanking -- 랭킹 재심사를 요청하는 함수
PlayerManagement:ReexamRanking -- 랭킹을 재심사하는 함수
PlayerManagement:ExamStoreRanking -- 상점 랭킹을 검사하고 새로운 랭킹을 계산하는 함수
PlayerOutgameManager:SaveToDB -- 아웃게임 플레이어 데이터를 데이터베이스에 저장
PlayerOutgameManager:OnLoadedDataFromDB -- 데이터베이스에서 아웃게임 플레이어 데이터를 로드하여 초기화
PlayerOutgameManager:OnSyncProperty -- 동기화된 속성에 따라 관련 이벤트 발생 및 UI 업데이트
PlayerOutgameManager:RequestSetStoreName -- 클라이언트에서 상점 이름 설정 요청을 받아 처리
PlayerOutgameManager:SetStoreName -- 금지어 검사 후 상점 이름을 설정하고 로그 기록
PlayerOutgameManager:GetDiamondCount -- 무료 다이아몬드와 유료 다이아몬드를 합산하여 총 다이아몬드 수량 반환
PlayerOutgameManager:ModifyDiamond -- 다이아몬드 수량을 증가 또는 감소시키며 로그 기록
PlayerOutgameManager:AddDiamond -- 다이아몬드를 추가하며 최대 스택 수량 체크 및 로그 기록
PlayerOutgameManager:SubDiamond -- 다이아몬드를 차감하며 무료 다이아몬드 우선 사용 후 유료 다이아몬드 사용
PlayerOutgameManager:SubDiamondPaidOnly -- 유료 다이아몬드만 차감하는 특별한 경우에 사용
PlayerOutgameManager:GetPurchaseCount -- 특정 상품의 구매 횟수를 계산하여 반환 (추가 구매 횟수 차감 적용)
PlayerOutgameManager:AddPurchaseCount -- 특정 상품의 구매 횟수를 1 증가시키고 결과 반환
PlayerOutgameManager:SubPurchaseCount -- 특정 상품의 구매 횟수를 1 감소 또는 초기화하고 결과 반환
PlayerOutgameManager:ModifyStrategyPoint -- 전략 포인트를 증가 또는 감소시키며 로그 기록
PlayerOutgameManager:AddStrategyPoint -- 전략 포인트를 추가하며 최대 스택 수량 체크
PlayerOutgameManager:SubStrategyPoint -- 전략 포인트를 차감하며 보유량 체크
PlayerOutgameManager:HasRemainStagePassRewardBySlotId -- 특정 슬롯에 미수령 스테이지 패스 보상이 있는지 확인
PlayerOutgameManager:GetStagePassRewardReceived -- 특정 스테이지 패스 보상의 수령 상태를 확인
PlayerOutgameManager:ReceiveStagePassReward -- 스테이지 패스 보상을 수령하고 인벤토리에 추가
PlayerOutgameManager:ReceiveStagePassPurchaseReward -- 스테이지 패스 구매 보상을 수령하고 인벤토리에 추가
PlayerOutgameManager:GetStagePassPurchaseRewardReceived -- 스테이지 패스 구매 보상의 수령 상태를 확인
PlayerOutgameManager:ResetPurchseCount -- 특정 상품의 구매 횟수를 초기화하고 이전 값을 반환
PlayerOutgameManager:ResetStagePassRewardReceived -- 스테이지 패스 보상 수령 상태를 초기화하고 변경된 개수 반환
PlayerOutgameManager:GetStagePassRecentRewardId -- 특정 그룹의 최근 스테이지 패스 보상 ID를 반환
PlayerOutgameManager:GetPiggyBankRewardReceived -- 특정 슬롯의 저금통 보상 수령 상태를 확인
PlayerOutgameManager:AddPiggyBankLevel -- 저금통 레벨을 올리고 저장된 포인트를 다이아몬드로 변환하여 지급
PlayerOutgameManager:AddPiggyBankPoint -- 저금통 포인트를 추가하고 꽉 찬 경우 정산 수익을 초기화
PlayerOutgameManager:IsPiggyBankFull -- 저금통이 꽉 찬 상태인지 확인하고 필요시 최대값으로 조정
PlayerOutgameManager:ResetPiggyBankPoint -- 저금통 포인트를 초기화하고 정산 수익도 초기화
PlayerOutgameManager:ForceAddPiggyBankPoint_ForCheat -- 치트용 저금통 포인트 강제 추가 기능
PlayerOutgameManager:ReceivePiggyBankReward -- 저금통 레벨업 보상을 수령하고 인벤토리에 추가
PlayerOutgameManager:ForceSetPiggyBankLevelAndPoint_ForCheat -- 치트용 저금통 레벨과 포인트 강제 설정 기능
PlayerOutgameManager:StoreNameFlowLog -- 상점 이름 변경 관련 로그를 기록
PlayerOutgameManager:AddItem -- 아웃게임 인벤토리에 아이템을 추가하며 최대 스택 수량 체크
PlayerOutgameManager:RemoveItem -- 아웃게임 인벤토리에서 아이템을 제거
PlayerOutgameManager:RequestSetHasSeenIntro -- 인트로 영상 시청 여부를 설정
PlayerOutgameManager:SetLogoutTimeElapsed -- 로그아웃 시간을 설정하여 오프라인 보상 계산에 사용
PlayerOutgameManager:InitPiggyBankPoint -- 저금통 포인트를 0으로 초기화하고 로그 기록
PlayerOutgameManager:AddMaxStackCountMailCount -- 최대 스택 수량 메일 카운트를 1 증가
PlayerOutgameManager:SetRecentOpenedStagePassGroup -- 최근에 열린 스테이지 패스 그룹 ID를 설정
PlayerOutgameManager:SetBoosterPack1Purchased -- 특정 스테이지의 부스터 팩 1 구매 상태를 설정
PlayerRecipe:SaveToDB -- 레시피 관련 데이터를 데이터베이스에 저장
PlayerRecipe:OnLoadedDataFromDB -- 데이터베이스에서 레시피 데이터를 로드하여 초기화
PlayerRecipe:InitComponent -- 레시피 컴포넌트의 모든 데이터를 초기화
PlayerRecipe:CheckCanStartRecipeMaking -- 레시피 제작 시작 가능 여부를 확인하고 필요한 재료를 소모
PlayerRecipe:StartRecipeMaking -- 클라이언트에서 레시피 제작 UI를 시작
PlayerRecipe:EndRecipeMakingServer -- 서버에서 레시피 제작을 완료하고 성과 및 보상을 처리
PlayerRecipe:EndRecipeMakingClient -- 클라이언트에서 레시피 제작 완료 후 UI 정리 및 다음 화면 전환
PlayerRecipe:ConvertRecipeDataToTable -- 레시피 구조체 데이터를 테이블 형태로 변환하여 DB 저장용으로 준비
PlayerRecipe:ConvertTableToRecipeData -- 테이블 데이터를 레시피 구조체로 변환하여 로드
PlayerRecipe:AddNewRecipe -- 새로운 레시피를 추가하고 관련 성과 및 로그를 처리
PlayerRecipe:RequestSyncAllRecipe -- 모든 레시피 데이터를 클라이언트에 동기화하고 UI 새로고침
PlayerRecipe:OnSyncProperty -- 동기화된 속성에 따라 관련 UI 업데이트 및 메뉴 설정
PlayerRecipe:RequestDeleteRecipe -- 클라이언트에서 레시피 삭제 요청을 받아 처리
PlayerRecipe:DeleteRecipe -- 레시피를 삭제하고 설정된 메뉴에서도 제거하며 로그 기록
PlayerRecipe:ChangeConnectingStatus -- 클라이언트에서 서버 처리 상태를 변경
PlayerRecipe:SetInitialDatas -- 초기 기본 레시피 데이터를 생성하여 설정
PlayerRecipe:SetRecipe -- 특정 슬롯에 레시피를 설정하고 메뉴 조합 계산 및 매력도 업데이트
PlayerRecipe:ClearSetRecipes -- 설정된 모든 레시피를 초기화하고 조합 계산
PlayerRecipe:UnsetRecipe -- 특정 슬롯의 레시피 설정을 해제하거나 전체 초기화
PlayerRecipe:RequestSetRecipe -- 클라이언트에서 레시피 설정 요청을 받아 처리
PlayerRecipe:RequestUnsetRecipe -- 클라이언트에서 레시피 해제 요청을 받아 처리
PlayerRecipe:RequestRefreshRecipeUI -- 레시피 관련 모든 UI를 새로고침
PlayerRecipe:SetRecipeTrialBuff -- 레시피에 시행 버프를 적용하고 만료 날짜 설정
PlayerRecipe:EndRecipeTrialBuff -- 레시피의 시행 버프를 종료하고 관련 데이터 초기화
PlayerRecipe:ChangeTrialBuffProgress -- 시행 버프가 적용된 모든 레시피의 진행도를 1씩 증가
PlayerRecipe:CheckTrialProgressExpiry -- 시행 버프가 적용된 레시피들의 만료 날짜를 확인하고 만료된 경우 버프를 종료
PlayerRecipe:AutoSetRecipe -- 보유한 레시피를 가격 순으로 정렬하여 자동으로 메뉴 슬롯에 설정
PlayerRecipe:RequestAutoSetRecipe -- 클라이언트에서 자동 레시피 설정 요청을 받아 처리
PlayerRecipe:MakeNewTrend -- 새로운 트렌드를 생성하여 긍정적 트렌드와 부정적 트렌드를 설정하고 관련 이벤트 발생
PlayerRecipe:RequestMakeNewTrend -- 클라이언트에서 새로운 트렌드 생성 요청을 받아 처리
PlayerRecipe:ChangeTrendProgress -- 현재 활성화된 모든 트렌드의 진행도를 1씩 증가
PlayerRecipe:CheckTrendExpiry -- 트렌드의 만료 날짜를 확인하고 만료된 트렌드들을 종료
PlayerRecipe:EndTrend -- 지정된 트렌드들을 종료하고 관련 이벤트를 발생시키며 고객 스폰 테이블을 새로고침
PlayerRecipe:SetYearlyPlan -- 연간 트렌드 계획을 설정하여 상반기와 하반기에 발생할 트렌드 날짜를 결정
PlayerRecipe:CheckYearlyPlan -- 연간 계획에 따라 특정 날짜에 트렌드가 발생해야 하는지 확인하고 실행
PlayerRecipe:CalculateActiveRecipeCombo -- 현재 설정된 레시피들의 태그 조합을 분석하여 활성화된 콤보를 계산
PlayerRecipe:RequestEndRecipeMaking -- 클라이언트에서 레시피 제작 완료 요청을 받아 금지어 검사 및 보관함 제한 확인 후 처리
PlayerRecipe:ChangeRecipeSetCompleteProgress -- 레시피 설정 완료 상태를 변경
PlayerRecipe:ReturnRecipeIndexByUniqueId -- 고유 ID를 통해 레시피의 인덱스를 찾아 반환
PlayerRecipe:ForceSyncSetRecipes -- 서버에서 설정된 레시피들을 강제로 동기화하고 관련 UI 및 메뉴 업데이트
PlayerRecipe:RequestForceSyncSetRecipes -- 클라이언트에서 레시피 설정 강제 동기화 요청을 받아 처리
PlayerRecipe:SetTempUsingCards -- 레시피 제작 시 임시로 사용될 카드 데이터를 설정
PlayerRecipe:verificationBurgerData -- 버거 데이터의 맛 점수와 가격이 최대 범위를 초과하지 않는지 검증
PlayerSettlement:SaveToDB -- 정산 데이터를 데이터베이스에 저장
PlayerSettlement:OnLoadedDataFromDB -- 데이터베이스에서 정산 데이터를 로드하여 초기화
PlayerSettlement:InitComponent -- 정산 컴포넌트의 모든 데이터를 초기화
PlayerSettlement:Settlement -- 월별 정산을 실행하여 수입과 지출을 계산하고 결과에 따른 처리 수행
PlayerSettlement:RequestSyncSettlementDatas -- 서버에서 정산 데이터를 클라이언트에 동기화하고 UI 업데이트
PlayerSettlement:ConvertSettlementDataToTable -- 정산 데이터 구조체를 테이블 형태로 변환하여 DB 저장용으로 준비
PlayerSettlement:ConvertTableToSettlementData -- 테이블 데이터를 정산 데이터 구조체로 변환하여 로드
PlayerSettlement:CreateNewMonthSettlementData -- 새로운 월의 정산 데이터를 생성하고 최대 7개월 기록 유지
PlayerSettlement:AddValueForSettlement -- 정산 데이터의 특정 항목에 값을 추가하고 관련 처리 수행
PlayerSettlement:ReplaceValueForSettlement -- 정산 데이터의 특정 항목 값을 대체
PlayerSettlement:RequestAddValueForSettlement -- 클라이언트에서 정산 데이터 값 추가 요청을 받아 처리
PlayerSettlement:AddTableValueForSettlement -- 정산 데이터의 테이블 형태 항목에 키-값 쌍으로 데이터를 추가
PlayerSettlement:RequestAddTableValueForSettlement -- 클라이언트에서 정산 데이터 테이블 값 추가 요청을 받아 처리
PlayerSettlement:CheckForResignEvent -- 사임 경고 상황을 확인하고 직원 수에 따라 자동 사임 및 경고 처리
PlayerSettlement:ResignWarningAlert -- 모든 직원에게 사임 경고 피드백 UI를 표시
PlayerSettlement:RequestSyncSettlementDataFromServer -- 서버에서 클라이언트로 정산 데이터 동기화 요청을 처리
PlayerSettlement:OnSyncProperty -- 동기화된 속성에 따라 관련 이벤트 발생 및 UI 업데이트
PlayerSettlement:RequestRefreshStoreInfoRecordPage -- 상점 정보 기록 페이지를 새로고침
PlayerSettlement:ChangeRecipeEarningRecord -- 레시피 최고 수익 기록을 변경하고 관련 성과 및 이벤트 처리
PlayerSettlement:AddPiggyBankEarnings -- 저금통 수익을 추가하고 필요 조건 달성 시 저금통 포인트 증가
PlayerSettlement:ResetPiggyBankEarings -- 저금통 수익을 초기화하고 디버그 모니터 업데이트
PlayerSettlement:MonthlySnapLog -- 월별 스냅샷 로그를 기록하여 게임 데이터 분석용 정보 수집
PlayerSettlement:MonthlyResourceLog -- 월별 자원 로그를 기록하여 자원 획득 및 소비 현황 추적
PlayerSettlement:UpdateEarningLevel -- 수익 레벨을 업데이트
PlayerSettlement:RequestOpenUIOfflineReward -- 오프라인 보상 UI를 열기 위해 로그아웃 시간과 보상 금액을 계산
PlayerSettlement:RequestGetOfflineReward -- 클라이언트에서 오프라인 보상 수령 요청을 받아 처리
PlayerStage:SaveToDB -- 스테이지 관련 데이터를 데이터베이스에 저장
PlayerStage:OnLoadedDataFromDB -- 데이터베이스에서 스테이지 데이터를 로드하여 초기화
PlayerStage:OnLoadedStage -- 스테이지 로드 완료 시 초기 설정 및 UI 업데이트 수행
PlayerStage:OnStartNewStage -- 새로운 스테이지를 시작하기 위한 설정 데이터를 준비하고 DB 초기화
PlayerStage:OnContinueStage -- 기존 스테이지를 계속 플레이하기 위한 준비 작업
PlayerStage:SetStageProgress -- 스테이지 진행도를 설정하고 클리어 조건 달성 시 보상 지급
PlayerStage:MoveToLoadingMap -- 로딩 맵으로 이동하여 스테이지 전환 준비
PlayerStage:OnMapEnter -- 맵 진입 시 스테이지 전환 처리 및 로그 기록
PlayerStage:ClearUI -- 모든 UI를 정리하고 로비 관련 요소들을 비활성화
PlayerStage:OnSyncProperty -- 동기화된 속성에 따라 관련 이벤트 발생 및 UI 업데이트
PlayerStage:GetChustarLevel -- 클리어한 스테이지 수를 기반으로 춤스타 레벨을 계산하여 반환
PlayerStage:GetStageClearReward -- 스테이지 클리어 보상을 지급하고 컴렉션 아이템 해제 및 보상 대기열에 추가
PlayerStage:IsAchieveStageProgress -- 지정된 스테이지의 진행도가 요구 수준에 도달했는지 확인
PlayerStage:GetNextStageProgress -- 다음 스테이지 진행도를 계산하여 스테이지 ID와 진행도를 반환
PlayerStage:ReturnMapName -- 스테이지 ID를 기반으로 맵 이름을 생성하여 반환
PlayerStage:IsStageOpened -- 지정된 스테이지가 해제되어 입장 가능한지 확인
PlayerStage:RequestDrawStageClearRewardQueue -- 스테이지 클리어 보상 대기열에서 보상 UI를 표시하고 대기열을 정리
PlayerStage:RequestClearStageRewardQueue -- 스테이지 보상 대기열과 클리어 데이터를 초기화
PlayerStage:RequestMakeDialog -- 스테이지 진행 중 대화를 생성하고 조건에 따라 부스터 팩 UI를 열기
PlayerStage:GetPlayerLastStageProgress -- 플레이어의 최신 스테이지 진행 상황을 문자열로 반환
PlayerStage:StageEnterLog -- 스테이지 진입 로그를 기록하여 사용자 행동 분석용 데이터 수집
PlayerStage:StageSettingLog -- 스테이지 설정 로그를 기록하여 사용된 전략과 설정 데이터를 추적
PlayerStage:SetStageSettingData -- 스테이지 설정 데이터를 JSON 형태로 저장
PlayerStage:DrawStageClearRewardQueue -- 스테이지 클리어 보상 대기열을 처리하여 보상 UI를 표시하는 함수
PlayerTrial:SaveToDB -- 시행 관련 데이터를 데이터베이스에 저장
PlayerTrial:OnLoadedDataFromDB -- 데이터베이스에서 시행 데이터를 로드하여 초기화
PlayerTrial:InitComponent -- 시행 컴포넌트의 모든 데이터를 초기화
PlayerTrial:OnSyncProperty -- 동기화된 속성에 따라 관련 UI 업데이트 및 이벤트 처리
PlayerTrial:SetTrialData -- 시행 데이터를 설정하고 랜더링 준비 및 클라이언트 동기화
PlayerTrial:SetCharacterData -- 시행 참가자들의 캐릭터 데이터를 생성하여 레이아웃에 배치
PlayerTrial:ReturnPlayData -- 시행 가중치에 따라 플레이 데이터를 생성하여 시간 배열로 반환
PlayerTrial:SetRankData -- 사용자 스탯과 요구사항을 기반으로 랜킹 데이터를 설정하고 시행 순서 결정
PlayerTrial:ReturnCharacterData -- 사용자 또는 라이벌 캐릭터의 데이터를 생성하여 레이아웃 인덱스와 함께 반환
PlayerTrial:ClearDatas -- 시행 관련 모든 데이터를 초기화하고 선택 상태를 리셋
PlayerTrial:SyncTableData -- 서버에서 전송된 테이블 데이터를 클라이언트에 동기화
PlayerTrial:ChangeConnectingStatus -- 서버 처리 상태를 변경하여 로딩 상태 관리
PlayerTrial:SelectTrial -- 시행을 선택하고 비용 및 조건 검사 후 시행 설정 UI로 이동
PlayerTrial:RequestSelectTrial -- 클라이언트에서 시행 선택 요청을 받아 처리
PlayerTrial:EndTrial -- 시행을 종료하고 승부에 따라 보상 지급 및 성과 처리
PlayerTrial:RequestEndTrial -- 클라이언트에서 시행 종료 요청을 받아 처리
PlayerTrial:RequestSetSelectedRecipe -- 클라이언트에서 선택된 레시피 설정 요청을 받아 처리
PlayerTrial:SetSelectedRecipe -- 레시피 시행에서 선택된 레시피를 설정하고 시행 비용을 차감하여 시행 시작
PlayerTrial:RequestSetTarget -- 시행 대상에 따라 레시피 또는 직원 선택 UI를 열기
PlayerTrial:RequestSetSelectedEmployee -- 클라이언트에서 선택된 직원 설정 요청을 받아 처리
PlayerTrial:SetSelectedEmployee -- 직원 시행에서 선택된 직원을 설정하고 시행 비용을 차감하여 시행 시작
PlayerTrial:SetIngredientData -- 시행 타입에 따라 각 참가자의 재료 데이터를 설정하여 시각적 표시
PlayerTrial:UpdateTrialProgress -- 시행 승리 시 공식/비공식 시행 진행도를 업데이트하고 관련 이벤트 처리
PlayerTrial:SetTrialGradeDifficulty -- 시행의 등급과 난이도를 설정하고 관련 비서 정보를 새로고침
PlayerTrial:SetOfficialTrials -- 현재 스테이지에 따라 공식 시행 목록을 설정
PlayerTrial:SetUnofficialTrials -- 랜덤으로 비공식 시행 목록을 생성하여 직원과 레시피 시행으로 분류
PlayerTrial:RequestSetTrialTab2RedDotChecked -- 시행 탭2의 빨간점 확인 상태를 설정하는 함수
PlayerTutorialEvent:SaveToDB -- 튜토리얼 이벤트 데이터를 데이터베이스에 저장
PlayerTutorialEvent:OnLoadedDataFromDB -- 데이터베이스에서 튜토리얼 이벤트 데이터를 로드하여 초기화
PlayerTutorialEvent:SetIsSkipTutorial -- 튜토리얼 스킵 설정을 변경하고 필요시 모든 튜토리얼 이벤트를 완료 처리
PlayerTutorialEvent:SetEventOccured -- 특정 튜토리얼 이벤트를 발생 상태로 설정하고 관련 보상을 처리
PlayerTutorialEvent:IsEventOccured -- 특정 튜토리얼 이벤트가 발생했는지 확인하여 상태를 반환
PlayerTutorialEvent:ForceSetTutorialEventsOccured -- 모든 튜토리얼 이벤트를 강제로 발생 상태로 설정
PlayerTutorialEvent:OnSyncProperty -- 튜토리얼 이벤트 동기화 시 UI 버튼 잠금 해제 및 관련 UI 새로고침
PlayerUpgrade:SaveToDB -- 업그레이드 데이터를 데이터베이스에 저장
PlayerUpgrade:OnLoadedDataFromDB -- 데이터베이스에서 업그레이드 데이터를 로드하여 초기화
PlayerUpgrade:InitComponent -- 업그레이드 컴포넌트의 모든 데이터를 초기화
PlayerUpgrade:UpgradeFunction -- 업그레이드 수행 로직으로 조건 검사후 비용 차감 및 레벨 업 처리
PlayerUpgrade:RequestUpgrade -- 클라이언트에서 업그레이드 요청을 받아 처리
PlayerUpgrade:RequestApplyUpgradeDataServer -- 업그레이드 타입에 따라 각종 시설 및 기능 업데이트를 수행하고 성과 처리
PlayerUpgrade:ReturnPlayerUpgradeLevelOfType -- 지정된 업그레이드 타입의 현재 레벨을 반환
PlayerUpgrade:ChangeConnectingStatus -- 서버 처리 상태를 변경하여 로딩 상태 관리
PlayerUpgrade:OnSyncProperty -- 동기화된 속성에 따라 관련 UI 업데이트 및 버튼 잠금 해제 처리
PlayerUpgrade:UpdateIngreBoxSubscriptionStatus -- 재료 박스 구독 상태를 업데이트하고 월 초에 재료를 구독 박스에 추가
PlayerUpgrade:AddNewSubscription -- 새로운 구독을 추가하여 기존 구독 기간과 합산하여 설정
PlayerUpgrade:ForceSetUpgradeLevel -- 치트용 업그레이드 레벨 강제 설정 및 관련 시설 업데이트
PlayerUpgrade:SyncToClientUpgrades -- 클라이언트에 업그레이드 데이터를 동기화하는 함수
PlayerVIPOrder:SaveToDB -- VIP 주문 관련 데이터를 데이터베이스에 저장
PlayerVIPOrder:OnLoadedDataFromDB -- 데이터베이스에서 VIP 주문 데이터를 로드하여 초기화
PlayerVIPOrder:InitComponent -- VIP 주문 컴포넌트의 모든 데이터를 초기화
PlayerVIPOrder:OnSyncProperty -- 동기화된 속성에 따라 VIP 주문 관련 UI 업데이트 및 상태 변경
PlayerVIPOrder:StartNewSeason -- 새로운 VIP 주문 시즌을 시작하여 메인 태그 설정 및 주문 슬롯 생성
PlayerVIPOrder:CreateVIPOrderSlotData -- 지정된 슬롯에 VIP 주문 데이터를 생성하여 레시피 또는 재료 주문으로 설정
PlayerVIPOrder:AddVIPOrderUniqueId -- VIP 주문의 고유 ID를 1 증가
PlayerVIPOrder:RequestSyncVIPOrderSlotData -- 서버에서 VIP 주문 슬롯 데이터를 클라이언트에 동기화하고 UI 업데이트
PlayerVIPOrder:RequestRerollOrderSlot -- 클라이언트에서 VIP 주문 리롤 요청을 받아 비용 차감 후 새로운 주문 생성
PlayerVIPOrder:RequestSubmitVIPOrder -- 클라이언트에서 VIP 주문 제출 요청을 받아 조건 검사 후 주문 완료 처리
PlayerVIPOrder:CompleteVIPOrder -- VIP 주문을 완료하여 보상 지급 및 시즌 점수 추가하고 로그 기록
PlayerVIPOrder:CheckVIPOrderResetCool -- VIP 주문 대기 시간을 하루씩 감소시키고 0이 되면 새로운 주문으로 리셋
PlayerVIPOrder:RequestSyncVIPOrderSlotDataToServer -- 클라이언트에서 VIP 주문 슬롯 데이터 서버 동기화 요청
PlayerVIPOrder:RefreshCompleteStatus -- VIP 주문 완료 상태를 새로고침하여 업그레이드로 인해 추가된 주문 수만큼 새로운 주문 생성
PlayerVIPOrder:CheckStartNewSeason -- 현재 월에 따라 VIP 주문 시즌 종료 예고 또는 새 시즌 시작 여부를 확인
PlayerVIPOrder:RequestGetSeasonReward -- 클라이언트에서 VIP 주문 시즌 보상 수령 요청을 받아 점수 조건 확인 후 보상 지급
PlayerVIPOrder:RequestSetFirstEnterUI -- 클라이언트에서 VIP 주문 UI 최초 진입 상태를 설정
PlayerVIPOrder:RequestResetVIPOrderSlot -- 클라이언트에서 VIP 주문 슬롯 리셋 요청을 받아 비용 차감 후 새로운 주문 생성
PlayerVIPOrder:ResetVIPOrderSlot -- 지정된 VIP 주문 슬롯을 리셋하여 새로운 주문 데이터로 대체
PlayerVIPOrder:RequestSetCloseEnterUI -- 클라이언트에서 VIP 주문 UI 종료 예고 진입 상태를 설정
PlayerVIPOrder:AddVIPOrderSeasonRewardScore -- VIP 주문 시즌 보상 점수를 지정된 수치만큼 추가
PlayerVIPOrder:VIPOrderRecipeLog -- VIP 주문 레시피 관련 로그를 기록하여 게임 데이터 분석용 정보 수집
PlayerVIPOrder:VIPOrderIngreLog -- VIP 주문 재료 관련 로그를 기록하여 게임 데이터 분석용 정보 수집
StorageCount:OnBeginPlay -- 게임 시작 시 특별 상점의 모든 상품에 대한 저장소 수량을 로드
StorageCount:LoadStorageCount -- 특정 상품의 저장소 수량을 월드 상점 서비스에서 가져와 반환
InteriorEntityCameraData:Load -- 업그레이드 레벨에 따른 카메라 데이터를 로드하는 함수
InteriorEntityCameraData:GetEntitiesOfTargetCamera -- 특정 카메라 키에 해당하는 엔티티 목록을 반환하는 함수
LobbyEntityLogic:SetEntities -- 로비 맵의 주요 엔티티들을 설정하는 함수
LobbyEntityLogic:SpawnDisplayCountText -- 확장 레벨에 따라 디스플레이 카운트 텍스트를 생성하는 함수
LobbyEntityLogic:SetKitchenAppInfo -- 주방 기기 정보를 설정하는 함수
LobbyEntityLogic:SetModelAfterSpawn -- 스폰 후 모델 설정을 처리하는 함수
LobbyEntityLogic:GetEmployeeSpawnPostion -- 직원 타입에 따른 스폰 위치를 반환하는 함수
LobbyHUDService:OnBeginPlay -- 게임 시작 시 메뉴 버튼 아이콘 애니메이션을 설정하는 함수
LobbyHUDService:OnEndPlay -- 게임 종료 시 타이머를 정리하는 함수
LobbyHUDService:OpenHUD -- 로비 HUD를 열고 초기화하는 함수
LobbyHUDService:UpdateTrainingTokenUI -- 훈련 토큰 UI를 업데이트하는 함수
LobbyHUDService:UpdateStoreInfoReportUI -- 상점 정보 리포트 UI를 업데이트하는 함수
LobbyHUDService:UpdateStoreInfoTrendUI -- 상점 정보 트렌드 UI를 업데이트하는 함수
LobbyHUDService:RefreshRemainText -- 남은 시간 텍스트를 새로고침하는 함수
LobbyHUDService:EnableTipUI -- 팁 UI를 활성화/비활성화하는 함수
LobbyHUDService:UpdateTipUI -- 팁 UI를 업데이트하는 함수
LobbyHUDService:GainTip -- 팁을 획득하는 함수
LobbyHUDService:UpdateTipMaxText -- 팁 최대치 텍스트를 업데이트하는 함수
LobbyHUDService:RefreshSubscriptionBoxButton -- 구독 박스 버튼을 새로고침하는 함수
LobbyHUDService:UpdateBestEarningRecord -- 최고 수익 기록을 업데이트하는 함수
LobbyHUDService:UpdateStoreNameUI -- 상점 이름 UI를 업데이트하는 함수
LobbyHUDService:UpdateVIPOrderBtn -- VIP 주문 버튼을 업데이트하는 함수
LobbyHUDService:ClearLobbyHUD -- 로비 HUD를 정리하는 함수
LobbyHUDService:PlayGainTipEffectOnTipButton -- 팁 버튼에 팁 획득 효과를 재생하는 함수
LobbyHUDService:RequestChangeStoreName -- 상점 이름 변경을 요청하는 함수
LobbyHUDService:ClearStoreInfoReportUI -- 상점 정보 리포트 UI를 정리하는 함수
LobbyHUDService:UpdateMoveNextStageBtn -- 다음 스테이지 이동 버튼을 업데이트하는 함수
LobbyHUDService:OpenStartStageToast -- 스테이지 시작 토스트를 여는 함수
LobbyHUDService:OpenStartDayToast -- 하루 시작 토스트를 여는 함수
LobbyHUDService:SetDropdownTestTimer -- 드롭다운 테스트 타이머를 설정하는 함수
LobbyHUDService:HandlePlayerManagementChangedEvent -- 플레이어 관리 상태 변경 이벤트를 처리하는 핸들러
LobbyHUDService:HandlePlayerTrainingTokenChangedEvent -- 플레이어 훈련 토큰 변경 이벤트를 처리하는 핸들러
LobbyHUDService:HandlePlayerTipChangedEvent -- 플레이어 팁 변경 이벤트를 처리하는 핸들러
LobbyHUDService:HandleButtonClickEvent -- 팁 저장소 버튼 클릭 이벤트를 처리하는 핸들러
LobbyHUDService:HandleButtonClickEvent2 -- 재료 구독 박스 버튼 클릭 이벤트를 처리하는 핸들러
LobbyHUDService:HandleBestEarningRecordChangedEvent -- 최고 수익 기록 변경 이벤트를 처리하는 핸들러
LobbyHUDService:HandleButtonClickEvent6 -- 상점 정보 버튼 클릭 이벤트를 처리하는 핸들러
LobbyHUDService:HandleButtonClickEvent7 -- 상점 이름 변경 버튼 클릭 이벤트를 처리하는 핸들러
LobbyHUDService:HandleButtonClickEvent8 -- 다음 스테이지 이동 버튼 클릭 이벤트를 처리하는 핸들러
LobbyManager:RequestInit -- 서버에서 로비 초기화를 요청하는 함수
LobbyManager:InitClient -- 클라이언트에서 로비를 초기화하는 함수
LobbyManager:OnMapLeave -- 맵을 떠날 때 처리하는 함수
LobbyManager:OnBeginPlay -- 게임 시작 시 첫 입장 플래그를 설정하는 함수
LobbyRenovationService:SetEntities -- 로비 리노베이션에 필요한 엔티티들을 설정하는 함수
LobbyRenovationService:RedesignInterior -- 인테리어를 재설계하는 함수
LobbyRenovationService:ExpandLobby -- 로비를 확장하는 함수
LobbyRenovationService:UpdateLobbyTileMap -- 로비 타일맵을 업데이트하는 함수
LobbyRenovationService:UpdatePostBox -- 우편함 위치를 업데이트하는 함수
LobbyRenovationService:UpdateWaitSeatPos -- 대기석 위치를 업데이트하는 함수
LobbyRenovationService:UpdateAllInnerWall -- 모든 내부 벽을 업데이트하는 함수
LobbyRenovationService:UpdateInnerWallByAppIdx -- 앱 인덱스별로 내부 벽을 업데이트하는 함수
LobbyRenovationService:AddBoxTile -- 박스 타일을 추가하는 함수
LobbyRenovationService:RemoveTile -- 타일을 제거하는 함수
LobbyRenovationService:UpdateInteriorObject -- 인테리어 오브젝트를 업데이트하는 함수
LobbyRenovationService:UpdateExteriorObject -- 외부 오브젝트를 업데이트하는 함수
LobbyRenovationService:UpdateKitchenInterior -- 주방 인테리어를 업데이트하는 함수
LobbyRenovationService:GetParkingAreaEntity -- 주차장 엔티티를 가져오는 함수
LobbyRenovationService:GetHiddenAreaEntity -- 숨겨진 영역 엔티티를 가져오는 함수
LobbyRenovationService:SetInteriorEntityLayer -- 인테리어 엔티티의 레이어를 설정하는 함수
OfflineRewardLogic:OpenUI -- 오프라인 보상 UI를 여는 함수
OfflineRewardLogic:GetOfflineRewardAmount -- 오프라인 보상 금액을 계산하는 함수
OfflineRewardLogic:GetRewardTimeSec -- 보상 시간을 초 단위로 계산하는 함수
OfflineRewardLogic:GetMaxRewardTime -- 최대 보상 시간을 가져오는 함수
OfflineRewardLogic:PlayAnimOnClickGetRewardButton -- 보상 버튼 클릭 시 애니메이션을 재생하는 함수
OfflineRewardLogic:GetMoneyRUIDByRewardAmount -- 보상 금액에 따른 돈 RUID를 가져오는 함수
OfflineRewardLogic:OfflineRewardLog -- 오프라인 보상 로그를 기록하는 함수
OfflineRewardLogic:IsOfflinePopupOpened -- 오프라인 팝업이 열려있는지 확인하는 함수
ReportMessageMaker:MakeReport -- 리포트 메시지를 생성하는 함수
ReportMessageMaker:CheckParamIsNilOrNot -- 파라미터가 nil인지 확인하는 함수
ReportMessageMaker:RequestAddToReportQueue -- 리포트 큐에 추가를 요청하는 함수
ReportMessageMaker:ReserveReport -- 리포트를 예약하는 함수
ReportMessageMaker:RequestRemoveToReportQueue -- 리포트 큐에서 제거를 요청하는 함수
ReportMessageMaker:OnEndPlay -- 게임 종료 시 타이머를 정리하는 함수
ReportMessageMaker:Init -- 리포트 메시지 메이커를 초기화하는 함수
ReportMessageMaker:ClearReportQueue -- 리포트 큐를 정리하는 함수
TimeManager:SaveToDB -- 시간 데이터를 DB에 저장하는 함수
TimeManager:OnLoadedDataFromDB -- DB에서 로드한 데이터를 처리하는 함수
TimeManager:InitComponent -- 컴포넌트를 초기화하는 함수
TimeManager:OnBeginPlay -- 게임 시작 시 첫 입장 플래그를 설정하는 함수
TimeManager:OnUpdate -- 매 프레임 시간을 업데이트하는 함수
TimeManager:OnMapEnter -- 맵 진입 시 처리하는 함수
TimeManager:OnMapLeave -- 맵을 떠날 때 처리하는 함수
TimeManager:UpdateTime -- 시간을 업데이트하는 함수
TimeManager:OnMonthChanged -- 월이 변경될 때 처리하는 함수
TimeManager:OnYearChanged -- 년도가 변경될 때 처리하는 함수
TimeManager:OnDayChanged -- 날짜가 변경될 때 처리하는 함수
TimeManager:TimeFlowsChange -- 시간 흐름 상태를 변경하는 함수
TimeManager:RequestTimeFlowClient -- 클라이언트에서 시간 흐름을 요청하는 함수
TimeManager:GetTimeText -- 시간을 텍스트로 변환하는 함수
TimeManager:CheckCanTimeFlows -- 시간이 흐를 수 있는지 확인하는 함수
TimeManager:debugTimeFlow -- 디버그 시간 흐름을 설정하는 함수
TimeUIService:UpdateUI -- 시간 UI를 업데이트하는 함수
UIGetOfflineRewardPopup:OnBeginPlay -- 게임 시작 시 팝업을 비활성화하는 함수
UIGetOfflineRewardPopup:Init -- UI 컴포넌트들을 초기화하는 함수
UIGetOfflineRewardPopup:Open -- 오프라인 보상 팝업을 여는 함수
UIGetOfflineRewardPopup:Refresh -- UI를 새로고침하는 함수
UIGetOfflineRewardPopup:Close -- 팝업을 닫는 함수
UIGetOfflineRewardPopup:GetRandomEmployeeTable -- 랜덤 직원 테이블을 가져오는 함수
UIHUDDropDown:OnBeginPlay -- 게임 시작 시 드롭다운을 초기화하는 함수
UIHUDDropDown:SetDropdownSize -- 드롭다운 크기를 설정하는 함수
UIHUDDropDown:SetDrawOfName -- 특정 항목의 표시 상태를 설정하는 함수
UIHUDDropDown:ClearTweenerAndTimer -- 트위너와 타이머를 정리하는 함수
UIHUDDropDown:CheckDropdownRedDotEnable -- 드롭다운 빨간점 활성화를 확인하는 함수
UIHUDDropDown:SetItemRedDot -- 특정 항목의 빨간점을 설정하는 함수
UIHUDDropDown:SetTestTimer -- 테스트 타이머를 설정하는 함수
UILobbyManager:OnBeginPlay -- 게임 시작 시 UI를 초기화하는 함수
UILobbyManager:HideStoreInfoArea -- 상점 정보 영역을 숨기는 함수
UILobbyManager:ShowStoreInfoArea -- 상점 정보 영역을 보여주는 함수
UILobbyManager:RequestUpdateSettlementRecordUI -- 정산 기록 UI 업데이트를 요청하는 함수
UILobbyManager:RefreshMenuInfo -- 메뉴 정보를 새로고침하는 함수
UILobbyManager:OpenMainMenu -- 메인 메뉴를 여는 함수
UILobbyManager:CloseMainMenu -- 메인 메뉴를 닫는 함수
UILobbyManager:HandleButtonClickEvent -- 메인 메뉴 버튼 클릭 이벤트를 처리하는 핸들러
UILobbyManager:HandleButtonClickEvent2 -- 메인 메뉴 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UILobbyManager:HandleButtonClickEvent3 -- 메인 메뉴 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIMenuInfoComponent:OnBeginPlay -- 게임 시작 시 UI 컴포넌트들을 초기화하는 함수
UIMenuInfoComponent:Refresh -- 메뉴 정보를 새로고침하는 함수
UIMenuInfoComponent:UpdateDebugMonitorUIRecipe -- 디버그 모니터 UI 레시피를 업데이트하는 함수
UIStartDayToast:OnBeginPlay -- 게임 시작 시 토스트를 비활성화하는 함수
UIStartDayToast:Init -- UI 컴포넌트들을 초기화하는 함수
UIStartDayToast:Open -- 하루 시작 토스트를 여는 함수
UIStartDayToast:StartRender -- 렌더링을 시작하는 함수
UIStartDayToast:OnEndPlay -- 게임 종료 시 타이머를 정리하는 함수
UIStartDayToast:TypeWriter -- 타이프라이터 효과를 실행하는 함수
UIStartDayToast:PlayTypeWriter -- 타이프라이터 효과를 재생하는 함수
UIStartDayToast:EndTypeWriter -- 타이프라이터 효과를 종료하는 함수
UIStartDayToast:HandleKeyDownEvent -- 키 입력 이벤트를 처리하는 핸들러
UIStoreInfoPageManager:OnBeginPlay -- 게임 시작 시 페이지를 초기화하는 함수
UIStoreInfoPageManager:SetTabPage -- 탭 페이지를 설정하는 함수
UIStoreInfoPageManager:TabOffAll -- 모든 탭을 끄는 함수
UIStoreInfoPageManager:HandleButtonClickEvent -- 탭1 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreInfoPageManager:HandleButtonClickEvent2 -- 탭2 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreInfoPageManager:HandleButtonClickEvent3 -- 탭3 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreInfoPageManager:HandleButtonClickEvent4 -- 탭4 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreInfoPageManager:HandleButtonClickEvent5 -- 탭1 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreInfoPageManager:HandleButtonClickEvent6 -- 탭2 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreInfoPageManager:HandleButtonClickEvent7 -- 탭3 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreInfoPageManager:HandleButtonClickEvent8 -- 탭4 닫기 버튼 클릭 이벤트를 처리하는 핸들러
CameraDataSetLogic:OnBeginPlay -- 로직 시작 시 카메라 데이터셋을 로드하는 함수
CameraDataSetLogic:LoadDataSet -- 로비 카메라 데이터와 인테리어 카메라 데이터를 로드하는 함수
CameraDataSetLogic:GetInteriorEntityCameraData -- 레벨에 해당하는 인테리어 엔티티 카메라 데이터를 반환하는 함수
CameraDataSetLogic:GetLobbyCameraData -- 확장 레벨에 해당하는 로비 카메라 데이터를 반환하는 함수
LobbyCameraData:Load -- 데이터 테이블에서 레벨별 카메라 데이터를 로드하는 함수
LobbyCameraData:GetCameraTypeDataByKey -- 키에 해당하는 카메라 타입 데이터를 반환하는 함수
LobbyCameraService:ChangeCameraTo -- 지정된 키에 해당하는 카메라로 전환하는 함수
LobbyCameraService:SetCameraSetting -- 카메라의 위치와 줄 비율을 설정하는 함수
LobbyCameraService:SetCamerasForExpansion -- 확장 레벨에 따라 카메라 설정을 적용하는 함수
LobbyCameraService:MoveMovingCamera -- 키보드 입력에 따라 이동 카메라를 이동시키는 함수
LobbyCameraService:OnUpdate -- 매 프레임 카메라 업데이트를 처리하는 함수
LobbyCameraService:MoveMovingCameraByTouchPoint -- 터치 입력에 따라 이동 카메라를 이동시키는 함수
LobbyCameraService:InitCameras -- 카메라 설정을 초기화하는 함수
LobbyCameraService:ToggleCameraSetOptions -- 카메라 옵션 UI를 토글하는 함수
LobbyCameraService:StartCameraSetOptionsTween -- 카메라 옵션 UI 애니메이션을 시작하는 함수
LobbyCameraService:OnBeginPlay -- 로직 시작 시 초기화 작업을 수행하는 함수
LobbyCameraService:OnClickCameraSetOptionBtn -- 카메라 옵션 버튼 클릭 시 처리하는 함수
LobbyCameraService:ForceCorrectPos -- 이동 카메라의 위치를 경계 내로 강제 보정하는 함수
LobbyCameraService:SwitchCamera -- 카메라를 순차적으로 전환하는 함수
LobbyCameraService:SetEnableCameraZoom -- 카메라 줄 기능의 활성화 여부를 설정하는 함수
LobbyCameraService:SetMovingCameraByKey -- 키에 따라 이동 카메라의 위치와 줄을 설정하는 함수
LobbyCameraService:ClearCameraSettingOnMap -- 맵에서 카메라 설정을 지우는 함수
LobbyCameraService:GetZoomRatio -- 플랫폼에 따라 조정된 줄 비율을 반환하는 함수
LobbyCameraService:HandleKeyDownEvent -- 키 눌림 이벤트를 처리하여 카메라 이동 입력을 설정하는 핸들러
LobbyCameraService:HandleKeyUpEvent -- 키 떼는 이벤트를 처리하여 카메라 이동 입력을 해제하는 핸들러
LobbyCameraService:HandleScreenTouchHoldEvent -- 화면 터치 홀드 이벤트를 처리하는 핸들러
LobbyCameraService:HandleScreenTouchReleaseEvent -- 화면 터치 릴리즈 이벤트를 처리하는 핸들러
LobbyCameraService:HandleButtonClickEvent3 -- 요리 시점 카메라 버튼 클릭 이벤트를 처리하는 핸들러
LobbyCameraService:HandleButtonClickEvent4 -- 서빙 시점 카메라 버튼 클릭 이벤트를 처리하는 핸들러
LobbyCameraService:HandleButtonClickEvent5 -- 입구 시점 카메라 버튼 클릭 이벤트를 처리하는 핸들러
LobbyCameraService:HandleButtonClickEvent6 -- 카메라 옵션 토글 버튼 클릭 이벤트를 처리하는 핸들러
LobbyCameraService:HandleButtonClickEvent -- 전체 시점 카메라 버튼 클릭 이벤트를 처리하는 핸들러
LobbyCameraTypeData:Load -- 행 데이터에서 카메라 타입 데이터를 로드하는 함수
InteractionPeedbackScript:OnTouch -- 고객 또는 직원 엔티티를 터치했을 때 해당하는 UI를 열어주는 함수
InteractionPeedbackScript:HandleUITouchDownEvent -- UI 터치 다운 이벤트를 처리하여 터치 상호작용을 실행하는 핸들러
InteractionScript:OnBeginPlay -- 엔티티 이름에 따라 인터랙션 타입을 결정하는 초기화 함수
InteractionScript:OnTouch -- 인터랙션 타입에 따라 적절한 UI를 열거나 닫는 터치 처리 함수
InteractionScript:HandleTouchEvent -- 터치 이벤트를 처리하여 UI 오버레이 체크 후 터치 상호작용을 실행하는 핸들러
InteractionTipScript:Create -- 팁 아이템을 생성하고 설정된 시간 후 자동 제거하는 함수
InteractionTipScript:GetItem -- 팁 아이템을 픍득하고 UI 업데이트 후 엔티티를 삭제하는 함수
InteractionTipScript:HandleTouchEvent -- 팁 아이템 터치 이벤트를 처리하여 UI 오버레이 체크 후 아이템 픍득을 실행하는 핸들러
InteractionUIService:OnBeginPlay -- 인터랙션 UI 초기화 및 버튼 이벤트 연결을 설정하는 함수
InteractionUIService:OpenUIKitchenAppNone -- 업그레이드가 필요한 주방기기 UI를 열어주는 함수
InteractionUIService:CloseUIKitchenAppNone -- 주방기기 업그레이드 필요 UI를 닫고 선택 상태를 초기화하는 함수
InteractionUIService:OpenUIKitchenAppInfo -- 주방기기 정보 UI를 열고 현재 레벨과 효과를 표시하는 함수
InteractionUIService:CloseUIUIKitchenAppInfo -- 주방기기 정보 UI를 닫고 선택 상태를 초기화하는 함수
InteractionUIService:ClickKitchenAppType -- 주방기기 타입에 따라 해당 기기들을 강조 표시하는 함수
InteractionUIService:UnClickKitchenAppType -- 주방기기 타입의 강조 표시를 제거하는 함수
InteractionUIService:UnClickAllKitchenAppType -- 모든 주방기기의 강조 표시를 제거하는 함수
InteractionUIService:ClickEmployee -- 직원을 선택하여 강조 표시하는 함수
InteractionUIService:UnClickEmployee -- 직원의 강조 표시를 제거하는 함수
InteractionUIService:UpdateUIEmployeeInfo -- 직원 정보 UI를 업데이트하는 함수
InteractionUIService:OpenUIEmployeeInfo -- 직원 정보 UI를 열고 직원을 선택 상태로 만드는 함수
InteractionUIService:CloseUIEmployeeInfo -- 직원 정보 UI를 닫고 선택 상태를 초기화하는 함수
InteractionUIService:OpenDisplayBurgerCount -- 디스플레이 버거 개수 텍스트를 표시하는 함수
InteractionUIService:CloseDisplayBurgerCount -- 디스플레이 버거 개수 텍스트를 숨기는 함수
InteractionUIService:RefreshDisplayTextAll -- 모든 디스플레이의 버거 개수 텍스트를 새로고침하는 함수
InteractionUIService:RefreshDisplayTextBySlotID -- 특정 디스플레이 슬롯의 버거 개수 텍스트를 업데이트하는 함수
InteractionUIService:CanNotFindDecokitchenApps -- 디스플레이 엔티티를 찾지 못했을 때 재시도하는 함수
InteractionUIService:HandleScreenTouchReleaseEvent -- 화면 터치 릴리스 이벤트를 처리하여 UI 닫기를 처리하는 핸들러
InteractionUIService:HandleEmployeeDetailChangeEvent -- 직원 세부 정보 변경 이벤트를 처리하여 UI를 업데이트하는 핸들러
SubscriptionPostBox:Refresh -- 구독 상자의 상태를 새로고침하고 알림 표시를 업데이트하는 함수
SubscriptionPostBox:OnBeginPlay -- 구독 상자 초기화 및 터치 이벤트 설정을 하는 함수
SubscriptionPostBox:OnTouch -- 구독 상자 터치 시 UI 오버레이 체크 후 아이템 수령을 요청하는 함수
SubscriptionPostBox:HandleTouchEvent -- 터치 이벤트를 처리하여 구독 상자 터치 상호작용을 실행하는 핸들러
ReputationDataSetLogic:OnBeginPlay -- 클라이언트에서 이펙트 인덱스 초기화
ReputationDataSetLogic:ReturnSpawnDelay -- 플레이어의 평판도와 경영 레벨에 따른 손님 스폰 딜레이 계산
ReputationDataSetLogic:ReturnReputationChangeByServingTime -- 서빙 시간에 따른 평판도 변화량 계산
ReputationDataSetLogic:RequestReputationChange -- 평판도 변경 요청 및 로그 기록
ReputationDataSetLogic:PlayReputationChangeEffectHUD -- HUD에서 평판도 변화 이펙트 재생
ReputationDataSetLogic:PlayReputationChangeEffectMap -- 맵에서 평판도 변화 이펙트 재생
ReputationDataSetLogic:ReturnReputationReviewScore -- 플레이어의 평판도를 기반으로 리뷰 점수 계산 (0-5점)
ReputationDataSetLogic:ReturnReviewStarCountByReputationAmount -- 평판도 변화량에 따른 별점 개수 반환
ReputationDataSetLogic:SetReputationDownServingTimeMin -- 평판도가 감소하는 최소 서빙 시간 설정
ReputationManagementData:Load -- CSV 데이터 테이블에서 평판 관리 데이터를 로드하여 속성에 저장
UIReputation:Init -- 평판 UI의 별점과 점수 텍스트 컴포넌트 초기화
UIReputation:Refresh -- 현재 평판 점수에 따라 별점 UI와 점수 텍스트 업데이트
UIReputation:HandlePlayerReputationChangedEvent -- 플레이어 평판 변경 시 UI 새로고침
UIReputation:HandleEarningLevelChangedEvent -- 수익 레벨 변경 시 UI 새로고침
UIReputation:HandlePlayerManagementChangedEvent -- 플레이어 경영 레벨 변경 시 UI 새로고침
BestEarningRecordChangedEvent:Init -- 최고 수익 기록 변경 이벤트 데이터를 초기화하는 함수
EarningLevelChangedEvent:Init -- 수익 레벨 변경 이벤트 데이터를 초기화하는 함수
SettlementData:ConvertToTable -- 정산 데이터를 테이블 형태로 변환하는 함수
SettlementData:SetFromTable -- 테이블 데이터로부터 정산 데이터를 설정하는 함수
SettlementData:ReturnEarnings -- 총 수익을 계산하여 반환하는 함수
SettlementData:ReturnExpense -- 총 지출을 계산하여 반환하는 함수
SettlementData:ReturnNetIncome -- 순수익(수익 - 지출)을 계산하여 반환하는 함수
SettlementPropertyEnum:ReadMe -- 정산 속성 열거형 클래스 설명 함수
SettlementUIService:OpenUISettlement -- 정산 UI 패널을 열어주는 함수
SettlementUIService:ForceCloseUISettlement -- 정산 UI 패널을 강제로 닫는 함수
UISettlementItem:Init -- 정산 아이템 UI 컴포넌트를 초기화하는 함수
UISettlementItem:Refresh -- 정산 데이터에 따라 UI를 새로고침하는 함수
UISettlementItem:ReturnTitleValueTableOfEnum -- 열거형에 따른 제목과 값을 테이블로 반환하는 함수
UISettlementPanel:Open -- 정산 패널을 열고 데이터를 표시하는 함수
UISettlementPanel:Close -- 정산 패널을 닫는 함수
UISettlementPanel:OnBeginPlay -- 컴포넌트 시작 시 UI 요소들을 초기화하는 함수
UISettlementPanel:Refresh -- 정산 데이터를 바탕으로 UI를 갱신하는 함수
UISettlementPanel:OpenShopInfo -- 상점 정보 창을 여는 함수
UISettlementPanel:StartTween -- 패널 열기/닫기 트윈 애니메이션을 시작하는 함수
UISettlementPanel:DrawGraph -- 정산 그래프를 그리는 함수
UISettlementPanel:ForceClose -- 패널을 강제로 즉시 닫는 함수
UISettlementPanel:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UISettlementPanel:HandleButtonClickEvent2 -- 상점 정보 버튼 클릭 이벤트를 처리하는 핸들러
UISettlementProgressGraphLine:Init -- 그래프 라인 UI 컴포넌트를 초기화하는 함수
UISettlementProgressGraphLine:Refresh -- 정산 데이터에 따라 그래프 라인을 갱신하는 함수
UIStoreInfoRecordPage:OnBeginPlay -- 컴포넌트 시작 시 UI 요소들을 초기화하는 함수
UIStoreInfoRecordPage:RefreshData -- 정산 데이터를 바탕으로 상점 기록 페이지를 갱신하는 함수
UIStoreInfoRecordPage:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 핸들러
CustomerReviewData:Load -- 데이터 테이블에서 고객 리뷰 데이터를 로드하는 함수
EmployeeReveiwStatusEnum:OnBeginPlay -- 직원 상태별 우선순위 점수를 초기화하는 함수
EmployeeReveiwStatusEnum:ReturnReviewStatusIconRUID -- 직원 상태에 따른 아이콘 RUID를 반환하는 함수
EmployeeReveiwStatusEnum:ReturnEmployeeStatus -- 플레이어와 직원 ID를 기반으로 직원의 현재 상태를 판단하여 반환하는 함수
EmployeeReveiwStatusEnum:ReturnRandomStatusComment -- 직원 상태에 따른 랜덤 코멘트를 반환하는 함수
StoreInfoDataSetLogic:OnBeginPlay -- 게임 시작 시 데이터셋을 로드하는 함수
StoreInfoDataSetLogic:LoadDataSet -- 고객 리뷰 데이터와 상점 정보 리포트 데이터를 로드하는 함수
StoreInfoDataSetLogic:ReturnPlayerScoreByCustomerReviewId -- 고객 리뷰 ID를 기반으로 플레이어의 점수를 계산하여 반환하는 함수
StoreInfoDataSetLogic:ReturnTutorialMainTags -- 플레이어의 튜토리얼 메인 태그들을 반환하는 함수
StoreInfoDataSetLogic:ReturnLackRecipeId -- 플레이어가 부족한 레시피 ID를 반환하는 함수
StoreInfoReportData:Load -- 데이터 테이블에서 상점 정보 리포트 데이터를 로드하는 함수
UICustomerReview:Open -- 고객 리뷰 UI를 열고 데이터를 새로고침하는 함수
UICustomerReview:Refresh -- 고객 리뷰 리스트를 새로고침하는 함수
UICustomerReview:OnBeginPlay -- 게임 시작 시 UI 엘리먼트를 초기화하는 함수
UICustomerReview:ReturnCustomerReviewPool -- 고객 리뷰 데이터 풀을 점수 순으로 정렬하여 반환하는 함수
UICustomerReviewSlotRenderer:OnBeginPlay -- 게임 시작 시 UI 엘리먼트들을 초기화하는 함수
UICustomerReviewSlotRenderer:Refresh -- 고객 리뷰 슬롯의 데이터를 새로고침하는 함수
UIEmployeeReview:OnBeginPlay -- 게임 시작 시 UI 엘리먼트와 이벤트를 초기화하는 함수
UIEmployeeReview:Open -- 직원 리뷰 UI를 열고 데이터를 설정하는 함수
UIEmployeeReview:Refresh -- 직원 리뷰 리스트를 새로고침하는 함수
UIEmployeeReview:SetStatusData -- 모든 직원의 상태 데이터를 설정하는 함수
UIEmployeeReview:SetTitleBar -- 타이틀 바 UI와 정렬 버튼들을 설정하는 함수
UIEmployeeReview:SetSortCriteria -- 정렬 기준을 설정하고 UI를 새로고침하는 함수
UIEmployeeReview:ReturnSortedEmployeeDetailTable -- 직원 데이터를 정렬 기준에 따라 정렬하여 반환하는 함수
UIEmployeeReview:SetUserDetailTable -- 직원 상세 테이블을 설정하는 함수
UIEmployeeReview:HandleButtonClickEvent -- 직원 관리 버튼 클릭 이벤트를 처리하는 함수
UIEmployeeReviewSlotRenderer:Init -- UI 엘리먼트들을 초기화하는 함수
UIEmployeeReviewSlotRenderer:Refresh -- 직원 리뷰 슬롯의 데이터를 새로고침하는 함수
UIEmployeeReviewSlotRenderer:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 함수
UIEmployeeReviewSortButton:OnBeginPlay -- 게임 시작 시 정렬 키와 UI 엘리먼트를 초기화하는 함수
UIEmployeeReviewSortButton:SetSortValue -- 일반 정렬 버튼의 정렬 값을 설정하는 함수
UIEmployeeReviewSortButton:SetSortValueSkill -- 스킬 정렬 버튼의 정렬 값을 설정하는 함수
UIEmployeeReviewSortButton:HandleButtonClickEvent -- 정렬 버튼 클릭 이벤트를 처리하는 함수
UIReputationFeedback:OnBeginPlay -- 게임 시작 시 UI 엘리먼트들을 초기화하는 함수
UIReputationFeedback:Refresh -- 피드백 타입에 따라 UI를 새로고침하는 함수
UIReputationFeedback:ReturnRandomEmployeeDataInStore -- 상점에서 서빙 직원 중 랜덤한 직원 데이터를 반환하는 함수
UIReputationFeedback:ReturnIconRUIDByFeedbackType -- 피드백 타입에 따른 아이콘 RUID를 반환하는 함수
UIReputationRecentLog:OnBeginPlay -- 게임 시작 시 UI 엘리먼트들을 초기화하는 함수
UIReputationRecentLog:Refresh -- 평판 로그 정보를 기반으로 UI를 새로고침하는 함수
UIReputationReview:Init -- UI 엘리먼트들을 초기화하는 함수
UIReputationReview:Open -- 평판 리뷰 UI를 열고 데이터를 새로고침하는 함수
UIReputationReview:Refresh -- 평판 리뷰 데이터를 새로고침하는 함수
UIReputationReview:RefreshRecentLogList -- 최근 평판 로그 리스트를 새로고침하는 함수
UIReputationReview:RefreshFeedbackList -- 피드백 리스트를 새로고침하는 함수
UIReputationReview:ReturnFeedbackTable -- 평판 로그를 분석하여 피드백 테이블을 생성하는 함수
UIReputationReview:RefreshReputationStats -- 평판 통계 데이터를 새로고침하는 함수
UIReputationReview:OnBeginPlay -- 게임 시작 시 초기화를 수행하는 함수
UIReputationReview:HandlePlayerReputationChangedEvent -- 플레이어 평판 변경 이벤트를 처리하는 함수
UIReputationReview:HandleEarningLevelChangedEvent -- 수익 레벨 변경 이벤트를 처리하는 함수
UIReputationReview:HandlePlayerManagementChangedEvent -- 플레이어 관리 데이터 변경 이벤트를 처리하는 함수
UIReputationStat:Init -- UI 엘리먼트들을 초기화하는 함수
UIReputationStat:Refresh -- 평판 통계 데이터를 UI에 표시하는 함수
UISettlementRecord:Init -- UI 엘리먼트들을 초기화하는 함수
UISettlementRecord:Refresh -- 정산 데이터를 기반으로 UI를 새로고침하는 함수
UISettlementRecord:DrawGraph -- 정산 데이터 그래프를 그리는 함수
UISettlementRecord:OnBeginPlay -- 게임 시작 시 초기화를 수행하는 함수
UISettlementRecord:Open -- 정산 기록 UI를 열고 데이터를 로드하는 함수
UISettlementRecord:RefreshTooltip -- 보너스 정보 툴팁을 새로고침하는 함수
UIStoreInfo:Open -- 상점 정보 UI를 열고 탭을 설정하는 함수
UIStoreInfo:Close -- 상점 정보 UI를 닫는 함수
UIStoreInfo:OnBeginPlay -- 게임 시작 시 UI 엘리먼트들을 초기화하는 함수
UIStoreInfo:SetSelectTab -- 선택된 탭을 설정하는 함수
UIStoreInfo:OnSelectTab -- 선택된 탭에 따라 UI를 변경하는 함수
UIStoreInfo:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 함수
UIStoreInfo:HandleButtonClickEvent2 -- 정산 버튼 클릭 이벤트를 처리하는 함수
UIStoreInfo:HandleButtonClickEvent3 -- 정산 버튼 2 클릭 이벤트를 처리하는 함수
UIStoreInfo:HandleButtonClickEvent4 -- 평판 버튼 클릭 이벤트를 처리하는 함수
UIStoreInfoPageTabButton:OnBeginPlay -- 게임 시작 시 UI 엘리먼트들을 초기화하는 함수
UIStoreInfoPageTabButton:IsButtonSelected -- 버튼 선택 상태에 따라 UI 애니메이션을 설정하는 함수
PlayerStoreManage:OnMapEnter -- 플레이어가 로비 맵에 입장했을 때 상점 관리 UI 초기화 및 쿨타임 리셋
PlayerStoreManage:Promotion -- 홍보 기능을 실행하여 고객을 유치하는 함수
PlayerStoreManage:BurgerSupplyment -- 버거 진열대에 버거를 보충하는 함수
PlayerStoreManage:CoolDown -- 홍보와 보충 기능의 쿨타임을 1씩 증가시키는 함수
PlayerStoreManage:ResetCool -- 모든 쿨타임을 초기화하고 타이머를 정리하는 함수
PlayerStoreManage:UpdateCoolTimeUI -- 상점 관리 UI의 쿨타임 표시를 업데이트하는 함수
PlayerStoreManage:RequestModifyClover -- 상점 관리 기능 사용 시 비용을 차감하고 기능을 실행하는 서버 함수
PlayerStoreManage:CanSupply -- 보충 기능이 성공적으로 실행되었을 때 호출되는 함수
PlayerStoreManage:CheckBurgerIsFull -- 현재 메뉴의 모든 진열대가 가득 찼는지 확인하는 함수
PlayerStoreManage:ModifyDisplayBurger -- 진열대에 버거를 실제로 추가하고 보고서 메시지를 생성하는 함수
PlayerStoreManage:CanPromotion -- 홍보 기능이 성공적으로 실행되었을 때 호출되는 함수
PlayerStoreManage:StartPromotion -- 홍보 효과로 일정 시간 동안 고객을 연속으로 스폰시키는 서버 함수
PlayerStoreManage:FailToManageStore -- 상점 관리 기능 사용 실패 시 토스트 메시지를 표시하는 함수
PlayerStoreManage:SetData -- 상점 관리 데이터를 스테이지별로 로드하고 쿨타임을 설정하는 함수
StoreManageData:Load -- CSV 데이터셋에서 상점 관리 데이터를 로드하여 구조체에 저장하는 함수
StoreManageStageData:Load -- 특정 스테이지의 모든 관리 레벨별 상점 관리 데이터를 로드하는 함수
UIStoreManage:UpdateSupplymentCoolTimeUI -- 버거 보충 쿨타임 UI의 진행도와 남은 시간을 업데이트하는 함수
UIStoreManage:UpdatePromotionCoolTimeUI -- 홍보 쿨타임 UI의 진행도와 남은 시간을 업데이트하는 함수
UIStoreManage:OnClickBtn -- 상점 관리 버튼 클릭 시 해당하는 기능을 실행하는 함수
UIStoreManage:SetCost -- 현재 관리 레벨과 스테이지에 따른 상점 관리 기능의 비용을 UI에 표시하는 함수
UIStoreManage:HandleButtonClickEvent2 -- 버거 보충 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreManage:HandleButtonClickEvent3 -- 홍보 버튼 클릭 이벤트를 처리하는 핸들러
UIStoreManageBtn:OnBeginPlay -- 상점 관리 UI의 슬라이드 애니메이션을 위한 초기 설정을 하는 함수
UIStoreManageBtn:SetEnable -- 상점 관리 UI를 슬라이드 애니메이션으로 열고 닫는 함수
UIStoreManageBtn:HandleButtonClickEvent -- 상점 관리 버튼 클릭 시 UI의 열기/닫기를 처리하는 핸들러
ToDoData:Load -- CSV 데이터 테이블에서 ToDo 정보를 읽어와 객체에 로드하는 함수
ToDoManager:OnBeginPlay -- 게임 시작 시 ToDo 관련 데이터셋을 로드하는 함수
ToDoManager:LoadDataSet -- EventToDoData와 ToDoSecretaryData 테이블을 로드하여 캐시하는 함수
ToDoManager:RefreshToDoList -- 현재 스테이지에 따라 적절한 ToDo 리스트를 새로고침하는 함수
ToDoManager:GetData -- 주어진 ID에 해당하는 ToDo 데이터를 반환하는 함수
ToDoManager:SetEnableRedDot -- ToDo 알림 빨간 점의 표시 여부를 설정하는 함수
ToDoManager:OpenRelatedUI -- ToDo 항목과 연결된 UI를 여는 함수
ToDoManager:SetNowToDo -- 현재 진행해야 할 ToDo를 찾아 설정하는 함수
ToDoManager:RefreshToDoInfos -- ToDo 정보 UI를 새로고침하는 함수
ToDoManager:CanToDoAchieved -- 현재 ToDo를 달성할 수 있는지 확인하는 함수
ToDoManager:RefreshSecretaryToDoList -- 비서 ToDo 리스트를 새로고침하는 함수
ToDoManager:RefreshTutorialToDoList -- 튜토리얼 단계의 ToDo 리스트를 새로고침하는 함수
ToDoManager:GetToDoSecretaryData -- 주어진 ID에 해당하는 비서 ToDo 데이터를 반환하는 함수
ToDoManager:IsToDoSecretaryOccured -- 비서 ToDo 조건이 만족되었는지 확인하는 함수
ToDoManager:HandlePlayerManagementChangedEvent -- 플레이어 경영 상태 변경 시 ToDo 정보를 업데이트하는 이벤트 핸들러
UIToDoItemRenderer:OnBeginPlay -- UI 구성 요소들을 초기화하는 함수
UIToDoItemRenderer:Refresh -- 일반 ToDo 데이터로 UI를 새로고침하는 함수
UIToDoItemRenderer:RefreshSecretary -- 비서 ToDo 데이터로 UI를 새로고침하는 함수
ToDoSecretaryData:Load -- CSV 데이터 테이블에서 할일 비서 데이터를 로드하여 객체 속성에 설정하는 함수
UIDiaInfo:OnBeginPlay -- 다이아 획득 방법 정보를 초기화하고 상점 상품 데이터를 로드하는 함수
UIDiaInfo:OpenUI -- 다이아 정보 UI를 열고 현재 보유 다이아를 표시하는 함수
UIDiaInfo:SetContents -- 플레이어 상태에 따라 다이아 획득 방법 목록을 설정하는 함수
UIDiaInfo:SetScrollView -- 리사이클 스크롤뷰를 설정하고 아이템을 표시하는 함수
UIDiaInfo:RegisterRecycleScrollLayoutCallback -- 리사이클 스크롤뷰의 셀 업데이트 콜백을 등록하는 함수
UIDiaInfo:RecycleScrollOnUpdateByIndex -- 스크롤뷰의 특정 인덱스 아이템을 업데이트하는 함수
UIDiaInfo:MoveUI -- 선택된 다이아 획득 방법에 따라 해당 UI로 이동하는 함수
UIDiaInfo:Close -- 다이아 정보 UI를 닫는 함수
UIDiaInfo:PurchaseCountCheck -- 각 상품의 구매 여부를 확인하여 보너스 표시를 설정하는 함수
UIDiaInfo:SortContents -- 보너스가 있는 항목을 상단으로 정렬하는 함수
UIDiaInfo:HandleButtonClickEvent -- 다이아 정보 버튼 클릭 시 UI를 여는 이벤트 핸들러
UIDiaInfo:HandleButtonClickEvent2 -- 닫기 버튼 클릭 시 UI를 닫는 이벤트 핸들러
UIDiaInfo:HandleButtonClickEvent3 -- 직원 장비 상점 버튼 클릭 시 해당 상점을 여는 이벤트 핸들러
UIDiaInfo:HandleButtonClickEvent4 -- 재료 컬렉션 버튼 클릭 시 컬렉션 UI를 여는 이벤트 핸들러
UIDiaInfo:HandleButtonClickEvent5 -- 추가 닫기 버튼 클릭 시 UI를 닫는 이벤트 핸들러
UIDiaInfoSlot:OnBeginPlay -- 슬롯 UI 요소들을 초기화하는 함수
UIDiaInfoSlot:Init -- 다이아 획득 방법 슬롯을 초기화하고 보너스 정보를 설정하는 함수
UIDiaInfoSlotMoveBtn:HandleButtonClickEvent -- 다이아 획득 방법 슬롯의 이동 버튼 클릭 시 해당 UI로 이동하는 이벤트 핸들러
CookEmployeeAIScript:OnBeginPlay -- 게임 시작 시 요리사 AI 초기화를 처리하는 함수
CookEmployeeAIScript:StateManager -- 요리사 AI 상태를 관리하는 메인 함수
CookEmployeeAIScript:WAIT -- 요리사가 대기 상태일 때의 처리 함수
CookEmployeeAIScript:WORK -- 요리사가 요리 작업 중일 때의 처리 함수
CookEmployeeAIScript:DISPLAY -- 요리사가 완성된 음식을 진열대에 진열하는 함수
CookEmployeeAIScript:DESTROY -- 요리사 엔티티를 제거할 때의 처리 함수
CookEmployeeAIScript:SelectMenu -- 요리할 메뉴를 선택하는 함수 (최소 재고 기준)
CookEmployeeAIScript:GetSpawnBurgerCount -- 직원의 능력에 따라 생성할 버거 개수를 계산하는 함수
CookEmployeeAIScript:HandleEmployeeMoveChangedEvent -- 직원 이동 상태 변경 이벤트를 처리하는 핸들러
CookEmployeeAIScript:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 핸들러
CookEmployeeAIScript:HandleExpansionLobbyEvent -- 로비 확장 이벤트를 처리하는 핸들러
EmployeeData:Load -- 직원 ID로 데이터셋에서 직원 정보를 로드하는 함수
EmployeeData:ConvertToTable -- 직원 데이터를 테이블 형태로 변환하는 함수
EmployeeData:ReturnSpecializedStat -- 직원의 전문 능력 타입을 반환하는 함수
EmployeeDetailChangeEvent:Init -- 직원 상세 정보 변경 이벤트를 초기화하는 함수
EmployeeDetailData:Load -- 직원 ID로 상세 데이터를 초기화하는 함수
EmployeeDetailData:ConvertToTable -- 직원 데이터를 테이블 형태로 변환하는 함수
EmployeeDetailData:ConvertToDBTable -- 직원 데이터를 DB 저장용 테이블로 변환하는 함수
EmployeeDetailData:SetFromTable -- 테이블 데이터로부터 직원 정보를 설정하는 함수
EmployeeDetailData:SetFromTable_Ver2 -- 버전 2 테이블 데이터로부터 직원 정보를 설정하는 함수
EmployeeDetailData:ReturnChuchuTotalLevel -- 츄츄의 전체 레벨을 반환하는 함수
EmployeeDetailData:ReturnStatLevelByStatType -- 능력 타입에 따른 레벨을 반환하는 함수
EmployeeDetailData:ReturnTypeLevel -- 직원 타입에 따른 레벨을 반환하는 함수
EmployeeDetailData:ReturnMaxLevelFromOverLimitLevel -- 한계돌파 레벨에 따른 최대 레벨을 반환하는 함수
EmployeeDetailData:ReturnOverLimitLevelFromGrade -- 등급에 따른 한계돌파 레벨을 반환하는 함수
EmployeeDetailData:ReturnMoveSpeedText -- 이동 속도 레벨을 텍스트로 변환하는 함수
EmployeeDetailData:ReturnTypeExp -- 직원 타입에 따른 경험치를 반환하는 함수
EmployeeDetailData:InitEmploymentLevel -- 고용 레벨을 초기화하는 함수
EmployeeInfoScript:OnBeginPlay -- 게임 시작 시 직원 정보 스크립트 초기화를 처리하는 함수
EmployeeInfoScript:Init -- 직원 UI 요소들을 초기화하는 함수
EmployeeInfoScript:Create -- 직원 엔티티를 생성하고 초기 설정을 하는 함수
EmployeeLocationData:ConvertToDBTable -- 직원 위치 데이터를 DB 저장용 테이블로 변환하는 함수
EmployeeLocationData:SetFromTable -- 테이블 데이터로부터 직원 위치 정보를 설정하는 함수
EmployeeLocationData:SetFromTable_Ver2 -- 버전 2 테이블 데이터로부터 직원 위치 정보를 설정하는 함수
EmployeeManager:SaveToDB -- 직원 데이터를 DB에 저장하는 함수
EmployeeManager:OnLoadedDataFromDB -- DB에서 로드된 직원 데이터를 처리하는 함수
EmployeeManager:InitComponent -- 직원 관리자 컴포넌트를 초기화하는 함수
EmployeeManager:SaveToOutDB -- 직원 외부 데이터를 DB에 저장하는 함수
EmployeeManager:OnLoadedDataFromOutDB -- 외부 DB에서 로드된 직원 데이터를 처리하는 함수
EmployeeManager:OnMapLeave -- 맵을 떠날 때 직원 데이터를 처리하는 함수
EmployeeManager:MapLeaveClient -- 클라이언트에서 맵 떠날 때 처리하는 함수
EmployeeManager:Init -- 직원 관리자를 초기화하는 함수
EmployeeManager:InitOfDB -- DB 데이터로 직원 관리자를 초기화하는 함수
EmployeeManager:InitChuchuOutgameDetailData -- 츄츄 외부 상세 데이터를 초기화하는 함수
EmployeeManager:SyncData -- 직원 데이터를 클라이언트에 동기화하는 함수
EmployeeManager:GetEmployeeDetail -- 직원 ID로 상세 데이터를 반환하는 함수
EmployeeManager:GetEmployeeLocation -- 직원 ID로 위치 데이터를 반환하는 함수
EmployeeManager:GetEmployeeOutgameDetail -- 직원 ID로 외부 상세 데이터를 반환하는 함수
EmployeeManager:GetEmployeeDetailIndex -- 직원 ID로 상세 데이터 인덱스를 반환하는 함수
EmployeeManager:GetEmployeeLocationIndex -- 직원 ID로 위치 데이터 인덱스를 반환하는 함수
EmployeeManager:ConvertEmpOutgameDetailToTable -- 직원 외부 상세 데이터를 테이블로 변환하는 함수
EmployeeManager:ConvertTableToEmpOutgameDetail -- 테이블 데이터를 직원 외부 상세 데이터로 변환하는 함수
EmployeeManager:ConvertEmpLocationToTable -- 직원 위치 데이터를 테이블로 변환하는 함수
EmployeeManager:ConvertEmpDetailToTable -- 직원 상세 데이터를 테이블로 변환하는 함수
EmployeeManager:ConvertTableToEmployeeLocation -- 테이블 데이터를 직원 위치 데이터로 변환하는 함수
EmployeeManager:UpdateDetailData -- 직원 상세 데이터를 업데이트하는 함수
EmployeeManager:ConvertTableToEmpDetail -- 테이블 데이터를 직원 상세 데이터로 변환하는 함수
EmployeeManager:UpdateLocationData -- 직원 위치 데이터를 업데이트하는 함수
EmployeeManager:ReturnEmployeeMoveSpeed -- 직원의 이동 속도를 계산하여 반환하는 함수
EmployeeManager:RemoveSingleData -- 단일 데이터를 제거하는 함수
EmployeeManager:ChangeLocationToWaiting -- 직원의 위치를 대기 상태로 변경하는 함수
EmployeeManager:ChangeLocationToStore -- 직원의 위치를 상점으로 변경하는 함수
EmployeeManager:RequestChangeLocationToWaiting -- 직원을 대기 위치로 이동 요청하는 함수
EmployeeManager:RequestChangeLocationToStore -- 직원을 상점 위치로 이동 요청하는 함수
EmployeeManager:CreateEmployee -- 직원을 생성하는 함수
EmployeeManager:AddEmployee -- 직원을 추가하는 함수
EmployeeManager:DestroyEmployee -- 직원을 제거하는 함수
EmployeeManager:CheckEmployeeAlreadyHave -- 이미 보유한 직원인지 확인하는 함수
EmployeeManager:CheckHasAllEmployee -- 모든 직원을 보유했는지 확인하는 함수
EmployeeManager:EmployeeStateStop -- 직원 상태를 정지시키는 함수
EmployeeManager:EmployeeStateStart -- 직원 상태를 시작시키는 함수
EmployeeManager:OnButtonClickTransfer -- 전송 버튼 클릭 시 처리하는 함수
EmployeeManager:TransferEmployee -- 직원을 전송하는 함수
EmployeeManager:RequestTransferEmployee -- 직원 전송을 요청하는 함수
EmployeeManager:RewardTransfer -- 전송 보상을 처리하는 함수
EmployeeManager:FinishTransfer -- 전송을 완료하는 함수
EmployeeManager:FailTransfer -- 전송 실패를 처리하는 함수
EmployeeManager:ShowTransferRewardUI -- 전송 보상 UI를 표시하는 함수
EmployeeManager:ReturnTotalSalary -- 총 급여를 반환하는 함수
EmployeeManager:ReturnDailySalary -- 일일 급여를 반환하는 함수
EmployeeManager:ReturnEmployeeDailySalary -- 직원의 일일 급여를 반환하는 함수
EmployeeManager:ReturnEmployeeWage -- 직원의 기본 급여를 반환하는 함수
EmployeeManager:ReturnEmployeeSalary -- 특정 직원의 급여를 반환하는 함수
EmployeeManager:ReturnEmployeeNextOverLimitWage -- 직원의 다음 한계돌파 급여를 반환하는 함수
EmployeeManager:ReturnTransferRefundJemCost -- 전송 시 환불될 보석 비용을 반환하는 함수
EmployeeManager:SyncLocationData -- 직원 위치 데이터를 동기화하는 함수
EmployeeManager:SyncDetailData -- 직원 상세 데이터를 동기화하는 함수
EmployeeManager:SyncInsertLocationData -- 직원 위치 데이터를 삽입하여 동기화하는 함수
EmployeeManager:SyncInsertDetailData -- 직원 상세 데이터를 삽입하여 동기화하는 함수
EmployeeManager:CallbackAfterSyncDetailTable -- 상세 테이블 동기화 후 콜백 함수
EmployeeManager:loggingEmployeeTable -- 직원 테이블을 로깅하는 함수
EmployeeManager:SetKitchenAppId -- 주방 앱 ID를 설정하는 함수
EmployeeManager:AddEmployeeEquipLevel -- 직원 장비 레벨을 추가하는 함수
EmployeeManager:SetEmployeeEquipLevel_ToClient -- 클라이언트에 직원 장비 레벨을 설정하는 함수
EmployeeManager:SetEmployeeEquipLevel_ForCheat -- 치트용 직원 장비 레벨을 설정하는 함수
EmployeeManager:ReturnSkillGrade -- 직원의 스킬 등급을 반환하는 함수
EmployeeManager:ReturnHasEquip -- 직원이 장비를 보유했는지 반환하는 함수
EmployeeManager:ChuchuAddedInCollection -- 츄츄를 컬렉션에 추가하는 함수
EmployeeManager:SyncChuchuInCollection -- 츄츄 컬렉션 상태를 동기화하는 함수
EmployeeManager:ChuchuSubedInCollection -- 츄츄를 컬렉션에서 제거하는 함수
EmployeeManager:LogEmployeeTrasfer -- 직원 전송을 로그에 기록하는 함수
EmployeeManager:ClearEmployeeDetailTable -- 직원 상세 테이블을 초기화하는 함수
EmployeeManager:InsertEmployeeDetailTable -- 직원 상세 테이블에 데이터를 삽입하는 함수
EmployeeManager:RemoveEmployeeDetailTable -- 직원 상세 테이블에서 데이터를 제거하는 함수
EmployeeManager:ChangeEmployeeDetailTable -- 직원 상세 테이블의 데이터를 변경하는 함수
EmployeeManager:SyncEmployeeDetailTable -- 직원 상세 테이블을 동기화하는 함수
EmployeeManager:UpdateServingEmployeeLocationTable -- 서빙 직원 위치 테이블을 업데이트하는 함수
EmployeeManager:SetChuchuMoveSpeed -- 츄츄의 이동 속도를 설정하는 함수
EmployeeMoveChangedEvent:Init -- 직원 이동 이벤트를 초기화하는 함수
EmployeeMoveChangedEvent:InitExcpetType -- 타입 제외하고 직원 이동 이벤트를 초기화하는 함수
EmployeeMoveStatLevelExpData:Load -- 레벨에 따른 직원 이동 능력 경험치 데이터를 로드하는 함수
EmployeeOutgameDetailData:Load -- 직원 ID로 외부 상세 데이터를 초기화하는 함수
EmployeeOutgameDetailData:ConvertToDBTable_ExceptId -- ID 제외하고 외부 데이터를 DB 테이블로 변환하는 함수
EmployeeOutgameDetailData:SetFromTable -- 테이블 데이터로부터 외부 상세 정보를 설정하는 함수
EmployeeOutgameDetailData:SetFromTable_Ver2 -- 버전 2 테이블 데이터로부터 외부 상세 정보를 설정하는 함수
EmployeeRUID:ReturnIconRUIDByStatType -- 직원 타입에 따라 아이콘 RUID를 반환하는 함수
EmployeeService:OnBeginPlay -- 게임 시작 시 직원 서비스를 초기화하는 함수
EmployeeService:LoadData -- 직원 관련 데이터를 로드하는 함수
EmployeeService:LoadConfigData -- 게임 설정 데이터를 로드하는 함수
EmployeeService:GetData -- 직원 ID로 직원 데이터를 반환하는 함수
EmployeeService:GetStatLevelData -- 레벨에 따른 직원 능력 데이터를 반환하는 함수
EmployeeService:ReturnWorkDuration -- 직원의 작업 소요 시간을 계산하는 함수
EmployeeService:IsStatLevelLow -- 직원의 능력 레벨이 낮은지 확인하는 함수
EmployeeService:IsStatLowByEarningLevelData -- 수익 레벨 데이터를 기준으로 직원 능력이 낮은지 확인하는 함수
EmployeeService:ReturnTransferHeart -- 직원 전송 시 필요한 하트 비용을 계산하는 함수
EmployeeService:UpdateAnim -- 직원 애니메이션을 업데이트하는 함수
EmployeeService:ReturnHasBurgerEntities -- 직원이 보유한 버거 엔티티 목록을 반환하는 함수
EmployeeService:ReturnCanStackByDisplayID -- 디스플레이 ID로 스택 가능한 수량을 반환하는 함수
EmployeeService:ReturnRemainBurgerByDisplayID -- 디스플레이 ID로 남은 버거 수량을 반환하는 함수
EmployeeService:ReturnChuchuLevel -- 츄츄의 레벨을 반환하는 함수
EmployeeService:ReturnOverLimitLevelByMaxLevel -- 최대 레벨로 한계돌파 레벨을 반환하는 함수
EmployeeService:ReturnDeposit -- 고용 보증금을 반환하는 함수
EmployeeService:ReturnMaxLevelByOverLimitLevel -- 한계돌파 레벨로 최대 레벨을 반환하는 함수
EmployeeService:ReturnRandomCharId -- 랜덤 캐릭터 ID를 반환하는 함수
EmployeeService:ReturnBestLevelOfType -- 특정 타입의 최고 레벨을 반환하는 함수
EmployeeService:ReturnChuchuIdListByGroupId -- 그룹 ID로 츄츄 ID 목록을 반환하는 함수
EmployeeService:ReturnStageEmpIdList -- 스테이지 ID로 직원 ID 목록을 반환하는 함수
EmployeeService:GetNearestDisplayId -- 가장 가까운 디스플레이 ID를 반환하는 함수
EmployeeService:GetCloserDisplayId -- 두 디스플레이 ID 중 더 가까운 것을 반환하는 함수
EmployeeStatByLevelData:Load -- 레벨 ID로 직원 능력 데이터를 로드하는 함수
EmployeeStatByLevelData:ConvertToTable -- 직원 능력 데이터를 테이블로 변환하는 함수
EmployeeStatLevelExpData:Load -- 레벨에 따른 경험치 데이터를 로드하는 함수
EmployeeStatLevelExpData:GetExpSum -- 플레이어 보너스를 고려한 누적 경험치를 반환하는 함수
EmployeeStatLevelExpData:GetExp -- 플레이어 보너스를 고려한 경험치를 반환하는 함수
EmployeeUIService:ProgressUICreate -- 직원 작업 진행 UI를 생성하는 함수
EmployeeUIService:ProgressUIInit -- 직원 작업 진행 UI를 초기화하는 함수
EmployeeUIService:ProgressUIOn -- 직원 작업 진행 UI를 활성화하는 함수
EmployeeUIService:PreogressUIOff -- 직원 작업 진행 UI를 비활성화하는 함수
EmployeeUIService:ProgressUIUpdate -- 직원 작업 진행 UI를 업데이트하는 함수
EmployeeUIService:PeedbackUICreate -- 직원 피드백 UI를 생성하는 함수
EmployeeUIService:PeedbackUIClose -- 직원 피드백 UI를 닫는 함수
EmployeeUIService:PeedbackUIUpdate -- 직원 피드백 UI를 업데이트하는 함수
EmployeeUIService:DrawPortraitWithEquip -- 직원 초상화와 장비를 그리는 함수
ServingEmployeeAIScript:OnBeginPlay -- 게임 시작 시 서빙 직원 AI 초기화를 처리하는 함수
ServingEmployeeAIScript:StateManager -- 서빙 직원 AI 상태를 관리하는 메인 함수
ServingEmployeeAIScript:WAIT -- 서빙 직원이 대기 상태일 때의 처리 함수
ServingEmployeeAIScript:ORDER -- 서빙 직원이 주문을 받는 상태일 때의 처리 함수
ServingEmployeeAIScript:SALES -- 서빙 직원이 음식을 판매하는 상태일 때의 처리 함수
ServingEmployeeAIScript:DESTROY -- 서빙 직원 엔티티를 제거할 때의 처리 함수
ServingEmployeeAIScript:PICKUP -- 서빙 직원이 음식을 픽업하는 상태일 때의 처리 함수
ServingEmployeeAIScript:SetStateManagerTimer -- 상태 관리 타이머를 설정하는 함수
ServingEmployeeAIScript:HandleEmployeeMoveChangedEvent -- 직원 이동 상태 변경 이벤트를 처리하는 핸들러
ServingEmployeeAIScript:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 핸들러
ServingEmployeeAIScript:HandleExpansionLobbyEvent -- 로비 확장 이벤트를 처리하는 핸들러
UIEmployeeListService:Set -- 직원 리스트 UI를 설정하는 함수
UIEmployeeListService:SpecializedStat -- 직원의 특화 스탯을 표시하는 함수
UIEmployeeSkillSlotSmall:OnBeginPlay -- 게임 시작 시 스킬 슬롯 UI를 초기화하는 함수
UIEmployeeSkillSlotSmall:Refresh -- 직원의 스킬 슬롯을 새로고침하는 함수
UIEmployeeSkillSlotSmall:ToggleSkillDescText -- 스킬 설명 텍스트를 토글하는 함수
UIEmployeeSkillSlotSmallNew:Init -- 새로운 스킬 슬롯 UI를 초기화하는 함수
UIEmployeeSkillSlotSmallNew:Refresh -- 직원의 스킬 슬롯을 새로고침하는 함수
ChuchuCollectionDB:SaveToDB -- 츄츄 컬렉션 데이터를 DB에 저장하는 함수
ChuchuCollectionDB:OnLoadedDataFromDB -- DB에서 로드된 데이터를 컬렉션에 적용하는 함수
ChuchuCollectionDB:ChangeChuchuCollectionState -- 츄츄 컬렉션 상태를 변경하는 함수 (수집/해제)
ChuchuCollectionDB:CountStageCollectionPercent -- 스테이지별 컬렉션 진행률을 계산하는 함수
ChuchuCollectionDB:OnSyncProperty -- 프로퍼티 동기화 시 UI 업데이트를 처리하는 함수
ChuchuCollectionDB:CountCollectionPercent -- 전체 컬렉션 달성률과 클로버 보너스를 계산하는 함수
ChuchuCollectionDB:UpdateCollectionPercent -- 클라이언트에서 컬렉션 퍼센트 UI를 업데이트하는 함수
ChuchuCollectionDB:GroupLevelReward -- 그룹 레벨 달성 보상을 지급하는 함수
ChuchuCollectionDB:SyncStageCollectionProgress -- 스테이지 컬렉션 진행률을 클라이언트에 동기화하는 함수
ChuchuCollectionDB:CalcGroupLevel -- 그룹의 현재 레벨을 계산하는 함수 (장비 레벨 기준)
ChuchuCollectionDB:AfterRewardGroupLevel -- 그룹 레벨 보상 지급 후 UI 업데이트를 처리하는 함수
ChuchuCollectionDB:LogChuchuCollection -- 츄츄 컬렉션 관련 로그를 기록하는 함수
ChuchuCollectionDB:LogChuchuEquipPurchase -- 츄츄 장비 구매 로그를 기록하는 함수
ChuchuCollectionDB:LogChuchuEquipUpgrade -- 츄츄 장비 업그레이드 로그를 기록하는 함수
ChuchuCollectionDB:GiveChuchuCollectionReward -- 츄츄 컬렉션 달성 보상을 지급하는 함수
ChuchuCollectionDB:AfterChuchuCollectionReward -- 츄츄 컬렉션 보상 지급 후 UI를 업데이트하는 함수
ChuchuCollectionDB:StageReward -- 스테이지별 컬렉션 달성 보상을 지급하는 함수
ChuchuCollectionDB:AfterCollectionLvReward -- 컬렉션 레벨 보상 지급 후 UI를 업데이트하는 함수
ChuchuCollectionDB:UpdateCollectionRedDot -- 컬렉션 관련 빨간점 표시를 업데이트하는 함수
ChuchuCollectionDB:CheckIsRewardGroupLevelReward -- 그룹 레벨 보상을 이미 받았는지 확인하는 함수
ChuchuCollectionDB:UpdateOnGroupLevelReward -- 그룹 레벨 보상 수령 상태를 업데이트하는 함수
ChuchuCollectionDB:ToastItemOverMaxCount -- 아이템 최대 보유량 초과 시 팝업을 표시하는 함수
ChuchuGroupData:Load -- 데이터 테이블에서 그룹 정보를 로드하는 함수
ChuchuGroupLogic:OnBeginPlay -- 게임 시작 시 초기화를 처리하는 함수
ChuchuGroupLogic:LoadDataSet -- 츄츄 그룹 데이터셋을 로드하는 함수
ChuchuGroupLogic:GetChuchuGroupData -- 그룹 ID로 츄츄 그룹 데이터를 반환하는 함수
ChuchuGroupLogic:ReturnStageIdFromGroupId -- 그룹 ID로 해당 스테이지 ID를 반환하는 함수
ChuchuGroupLogic:RetrunGroupIdsFromStageId -- 스테이지 ID로 해당 그룹 ID 목록을 반환하는 함수
GroupCollectionRewardData:Load -- 데이터 테이블에서 그룹 컬렉션 보상 데이터를 로드하는 함수
GroupCollectionRewardData:ReturnRewardIdFromType -- 보상 타입에 따라 적절한 보상 아이템 ID를 반환하는 함수
GroupCollectionRewardDataSetLogic:OnBeginPlay -- 게임 시작 시 데이터셋을 로드하는 함수
GroupCollectionRewardDataSetLogic:LoadDataSet -- 그룹 컬렉션 보상 데이터셋을 로드하는 함수
GroupCollectionRewardDataSetLogic:GetGroupCollectionRewardData -- 레벨에 따른 그룹 컬렉션 보상 데이터를 반환하는 함수
InfoPopupLogic:CloseUI -- 정보 팝업 UI를 닫는 함수
InfoPopupLogic:OpenUI -- 정보 팝업 UI를 여는 함수
InfoPopupLogic:Set -- 정보 팝업 내용을 설정하는 함수
InfoPopupLogic:OnBeginPlay -- 게임 시작 시 초기화를 처리하는 함수
InfoPopupLogic:HandleButtonClickEvent -- 정보 팝업 닫기 버튼 클릭 이벤트를 처리하는 핸들러
InfoPopupLogic:HandleButtonClickEvent2 -- 정보 팝업 닫기 버튼 클릭 이벤트를 처리하는 핸들러
InfoPopupLogic:HandleButtonClickEvent3 -- 정보 팝업 열기 버튼 클릭 이벤트를 처리하는 핸들러
InfoPopupLogic:HandleButtonClickEvent4 -- 정보 팝업 열기 버튼 클릭 이벤트를 처리하는 핸들러
InfoPopupLogic:HandleButtonClickEvent5 -- 정보 팝업 열기 버튼 클릭 이벤트를 처리하는 핸들러
InfoPopupLogic:HandleButtonClickEvent6 -- 정보 팝업 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:OnBeginPlay -- 게임 시작 시 UI 초기화를 처리하는 함수
UIChuchuCollection:OpenUI -- 츄츄 컬렉션 UI를 여는 함수
UIChuchuCollection:CloseUI -- 츄츄 컬렉션 UI를 닫는 함수
UIChuchuCollection:SetStgIcons -- 스테이지 아이콘들을 설정하는 함수
UIChuchuCollection:SetScrollView -- 스테이지에 따른 스크롤 뷰를 설정하는 함수
UIChuchuCollection:UpdateChuchuGroupSlot -- 츄츄 그룹 슬롯을 업데이트하는 함수
UIChuchuCollection:OnClickStgIcon -- 스테이지 아이콘 클릭 시 처리하는 함수
UIChuchuCollection:UpdateChuchuSlot -- 츄츄 슬롯을 업데이트하는 함수
UIChuchuCollection:OnClickChuchuSlot -- 츄츄 슬롯 클릭 시 상세 정보를 표시하는 함수
UIChuchuCollection:OnClickGroupSlot -- 그룹 슬롯 클릭 시 그룹 정보를 표시하는 함수
UIChuchuCollection:OnClickChuchuInfoGroupBtn -- 츄츄 정보에서 그룹 버튼 클릭 시 처리하는 함수
UIChuchuCollection:OpenBuyEquipPopup -- 장비 구매 팝업을 여는 함수
UIChuchuCollection:CloseBuyEquipPopup -- 장비 구매 팝업을 닫는 함수
UIChuchuCollection:OpenUpgradeEquipPopup -- 장비 업그레이드 팝업을 여는 함수
UIChuchuCollection:CloseUpgradeEquipPopup -- 장비 업그레이드 팝업을 닫는 함수
UIChuchuCollection:OnPurchaseEquipCompleted -- 장비 구매 완료 후 UI를 업데이트하는 함수
UIChuchuCollection:ResetEquipStarsUI -- 장비 별 UI를 리셋하는 함수
UIChuchuCollection:ResetEmployeeEquipUpgradePopup -- 직원 장비 업그레이드 팝업을 리셋하는 함수
UIChuchuCollection:OnUpgradeEquipCompleted -- 장비 업그레이드 완료 후 UI를 업데이트하는 함수
UIChuchuCollection:ResetEquipDesc -- 장비 레벨에 따른 설명 텍스트를 리셋하는 함수
UIChuchuCollection:HandleEventToPopup -- 팝업 이벤트 핸들링을 처리하는 함수
UIChuchuCollection:ResetEmployeeEquipBuyPopup -- 직원 장비 구매 팝업을 리셋하는 함수
UIChuchuCollection:UpdateCollectionPercent -- 컬렉션 달성률을 업데이트하는 함수
UIChuchuCollection:UpdateStageCollectionGauge -- 스테이지 컬렉션 게이지를 업데이트하는 함수
UIChuchuCollection:UpdateGroupLevelUI -- 그룹 레벨 UI를 업데이트하는 함수
UIChuchuCollection:OnClickGroupLevelRewardIcon -- 그룹 레벨 보상 아이콘 클릭 시 처리하는 함수
UIChuchuCollection:AfterRewardGroupLevel -- 그룹 레벨 보상 지급 후 이팩트를 처리하는 함수
UIChuchuCollection:UpdateGroupLevelRewardList -- 그룹 레벨 보상 목록을 업데이트하는 함수
UIChuchuCollection:UpdateStageCollectionReward -- 스테이지 컬렉션 보상을 업데이트하는 함수
UIChuchuCollection:OnClickStageGaugeDiaIcon -- 스테이지 게이지 다이아 아이콘 클릭 시 처리하는 함수
UIChuchuCollection:ChuchuCollectionReward -- 츄츄 컬렉션 보상을 요청하는 함수
UIChuchuCollection:AfterChuchuCollectionReward -- 츄츄 컬렉션 보상 지급 후 이팩트를 처리하는 함수
UIChuchuCollection:SkillUpgradePopup -- 스킬 업그레이드 팝업을 표시하는 함수
UIChuchuCollection:CheckCollectionRedDot -- 컬렉션 빨간점 표시 상태를 확인하는 함수
UIChuchuCollection:CheckStageIconRedDot -- 스테이지 아이콘 빨간점 표시 상태를 확인하는 함수
UIChuchuCollection:CheckGroupRedDot -- 그룹 빨간점 표시 상태를 확인하는 함수
UIChuchuCollection:RegisterRecycleScrollLayoutCallback -- 리사이클 스크롤 레이아웃 콜백을 등록하는 함수
UIChuchuCollection:CalcIndexFromGroupId -- 그룹 ID로 인덱스를 계산하는 함수
UIChuchuCollection:CalcGroupIdFromIndex -- 인덱스로 그룹 ID를 계산하는 함수
UIChuchuCollection:ReturnEntityByGroupId -- 그룹 ID로 엔티티를 반환하는 함수
UIChuchuCollection:RecycleScrollOnUpdateByIndex -- 리사이클 스크롤의 인덱스 업데이트를 처리하는 함수
UIChuchuCollection:RecycleScrollOnUpdateByGroupId -- 리사이클 스크롤의 그룹 ID 업데이트를 처리하는 함수
UIChuchuCollection:ReturnEntityByEmpId -- 직원 ID로 엔티티를 반환하는 함수
UIChuchuCollection:ScrollToGroup -- 특정 그룹으로 스크롤하는 함수
UIChuchuCollection:SetRedDotOnBegin -- 초기 빨간점 표시 상태를 설정하는 함수
UIChuchuCollection:HandleButtonClickEvent -- 컴렉션 UI 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent2 -- 컴렉션 UI 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent3 -- 장비 구매 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent4 -- 장비 구매 팝업 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent5 -- 장비 업그레이드 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent6 -- 장비 업그레이드 팝업 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent7 -- 직원 컴렉션 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent8 -- 컴렉션 그룹 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent9 -- 업그레이드 팝업 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent10 -- 구매 팝업 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent11 -- 선택된 직원 컴렉션 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent12 -- 스테이지 게이지 다이아 아이콘1 클릭 이벤트를 처리하는 핸들러
UIChuchuCollection:HandleButtonClickEvent13 -- 스테이지 게이지 다이아 아이콘2 클릭 이벤트를 처리하는 핸들러
UIChuchuCollectionSlot:OnBeginPlay -- 게임 시작 시 UI 초기화를 처리하는 함수
UIChuchuCollectionSlot:Init -- 츄츄 컬렉션 슬롯을 초기화하는 함수
UIChuchuCollectionSlot:UpdateGroupLevelUI -- 그룹 레벨 UI를 업데이트하는 함수
UIChuchuCollectionSlot:UpdateChuchuSlot -- 츄츄 슬롯을 업데이트하고 빨간점 상태를 반환하는 함수
UIChuchuCollectionSlot:UpdateGroupLevel -- 그룹 레벨을 업데이트하는 함수
UISelectChuchuInCollection:OnBeginPlay -- 게임 시작 시 UI 초기화를 처리하는 함수
UISelectChuchuInCollection:UpdateChuchuList -- 필터에 따라 츄츄 목록을 업데이트하는 함수
UISelectChuchuInCollection:OnClickChuchuSlot -- 츄츄 슬롯 클릭 시 상세 정보를 표시하는 함수
UISelectChuchuInCollection:OpenUI -- 츄츄 선택 UI를 여는 함수
UISelectChuchuInCollection:CloseUI -- 츄츄 선택 UI를 닫는 함수
UISelectChuchuInCollection:OnClickSelectBtn -- 선택 버튼 클릭 시 처리하는 함수
UISelectChuchuInCollection:OnClickFilterBtn -- 필터 버튼 클릭 시 처리하는 함수
UISelectChuchuInCollection:OnClickFilterCategory -- 필터 카테고리 선택 시 처리하는 함수
UISelectChuchuInCollection:RegisterRecycleScrollLayoutCallback -- 리사이클 스크롤 레이아웃 콜백을 등록하는 함수
UISelectChuchuInCollection:RecycleScrollOnUpdateByIndex -- 리사이클 스크롤의 인덱스 업데이트를 처리하는 함수
UISelectChuchuInCollection:CalcEmpIdFromIndex -- 인덱스로 직원 ID를 계산하는 함수
UISelectChuchuInCollection:UpdateSlotOutline -- 선택된 슬롯의 외곽선을 업데이트하는 함수
UISelectChuchuInCollection:HandleButtonClickEvent -- 선택 버튼 클릭 이벤트를 처리하는 핸들러
UISelectChuchuInCollection:HandleButtonClickEvent2 -- UI 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UISelectChuchuInCollection:HandleButtonClickEvent3 -- UI 열기 버튼 클릭 이벤트를 처리하는 핸들러
UISelectChuchuInCollection:HandleButtonClickEvent4 -- 전체 버튼 클릭 이벤트를 처리하는 핸들러
UISelectChuchuInCollection:HandleButtonClickEvent5 -- 서빙 직원 필터 버튼 클릭 이벤트를 처리하는 핸들러
UISelectChuchuInCollection:HandleButtonClickEvent6 -- 필터 버튼 클릭 이벤트를 처리하는 핸들러
UISelectChuchuInCollection:HandleButtonClickEvent7 -- 전체 필터 버튼 클릭 이벤트를 처리하는 핸들러
UISelectChuchuInCollection:HandleButtonClickEvent8 -- 장비 구매 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageDeployList:OnBeginPlay -- 게임 시작 시 직원 배치 리스트 UI를 초기화하는 함수
UIEmployeeManageDeployList:Init -- 직원 배치 슬롯을 초기화하고 잠금 상태를 설정하는 함수
UIEmployeeManageDeployList:RefreshList -- 배치된 직원 리스트를 새로고침하는 함수
UIEmployeeManageDeployList:RefreshDeployeCount -- 배치된 직원 수를 새로고침하는 함수
UIEmployeeManageDeployList:UpdateSlotOutline -- 선택된 직원의 슬롯 아웃라인을 업데이트하는 함수
UIEmployeeManageDeployList:ReturnRemainSlotIdx -- 남은 빈 슬롯의 인덱스를 반환하는 함수
UIEmployeeManageDeployList:CheckEmptySlotForRedDot -- 빈 슬롯이 있는지 확인하고 빨간점을 표시하는 함수
UIEmployeeManageDeployListRenderer:OnBeginPlay -- 게임 시작 시 배치 리스트 렌더러를 초기화하는 함수
UIEmployeeManageDeployListRenderer:Init -- 배치 리스트 렌더러를 초기화하는 함수
UIEmployeeManageDeployListRenderer:Set -- 직원 ID로 배치 리스트 렌더러를 설정하는 함수
UIEmployeeManageDeployListRenderer:OnClick -- 슬롯 클릭 시 처리하는 함수
UIEmployeeManageDeployListRenderer:EnableOutline -- 슬롯 아웃라인을 활성화하는 함수
UIEmployeeManageDeployListRenderer:DisableOutline -- 슬롯 아웃라인을 비활성화하는 함수
UIEmployeeManageDeployListRenderer:HandleButtonClickEvent -- 배치 리스트 슬롯 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageDeployListRenderer:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 핸들러
UIEmployeeManageDetailRenderer:OnBeginPlay -- 게임 시작 시 직원 상세 정보 렌더러를 초기화하는 함수
UIEmployeeManageDetailRenderer:Set -- 직원 ID로 상세 정보를 설정하는 함수
UIEmployeeManageDetailRenderer:SpecializedStat -- 직원의 특화 스탯을 표시하는 함수
UIEmployeeManageDetailRenderer:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 핸들러
UIEmployeeManageList:OnBeginPlay -- 게임 시작 시 직원 관리 리스트 UI를 초기화하는 함수
UIEmployeeManageList:Init -- 직원 관리 리스트를 초기화하는 함수
UIEmployeeManageList:OnClickFilterCategoryBtn -- 필터 카테고리 버튼 클릭 시 필터 타입을 설정하고 리스트를 새로고침하는 함수
UIEmployeeManageList:OnClickSortTypeBtn -- 정렬 타입 버튼 클릭 시 정렬 방식을 설정하고 리스트를 새로고침하는 함수
UIEmployeeManageList:RefreshList -- 직원 리스트를 새로고침하고 스크롤 위치를 재설정하는 함수
UIEmployeeManageList:UpdateSlotOutline -- 선택된 직원의 슬롯 아웃라인을 업데이트하는 함수
UIEmployeeManageList:RegisterRecycleScrollLayoutCallback -- 재활용 스크롤 레이아웃 콜백을 등록하는 함수
UIEmployeeManageList:RecycleScrollOnUpdateByIndex -- 인덱스에 따라 재활용 스크롤의 셀을 업데이트하는 함수
UIEmployeeManageList:CalcEmpIdFromIndex -- 인덱스로부터 직원 ID를 계산하여 반환하는 함수
UIEmployeeManageList:FindEntityFromEmpId -- 직원 ID로부터 해당하는 엔티티를 찾아 반환하는 함수
UIEmployeeManageList:UpdateEmpSlotFromEmpId -- 직원 ID로부터 해당 슬롯을 업데이트하는 함수
UIEmployeeManageListRenderer:Set -- 직원 ID로 렌더러의 상태를 설정하는 함수
UIEmployeeManageListRenderer:EnableOutline -- 선택 외곽선을 활성화하는 함수
UIEmployeeManageListRenderer:DisableOutline -- 선택 외곽선을 비활성화하는 함수
UIEmployeeManageListRenderer:OnClick -- 직원 슬롯 클릭 시 처리하는 함수
UIEmployeeManageListRenderer:SwitchOutline -- 선택된 슬롯의 외곽선을 전환하는 함수
UIEmployeeManageListRenderer:Init_EmployeeManage -- 직원 관리용 렌더러를 초기화하는 함수
UIEmployeeManageListRenderer:OnChangeLocation -- 직원 위치 변경 시 UI를 업데이트하는 함수
UIEmployeeManageListRenderer:Init_SelectChuchuInCollection -- 츄츄 컴렉션 선택용 렌더러를 초기화하는 함수
UIEmployeeManageListRenderer:Init_Training -- 훈련용 렌더러를 초기화하는 함수
UIEmployeeManageListRenderer:CheckEmployeeTrainingSetting -- 직원이 훈련 설정에 포함되어 있는지 확인하는 함수
UIEmployeeManageListRenderer:ChangeChuchuListSlotState_Auto -- 자동 훈련 상태에 따라 츄츄 리스트 슬롯 상태를 변경하는 함수
UIEmployeeManageListRenderer:ChangeChuchuListSlotState_Auto_Fixed -- 고정된 상태로 자동 훈련 슬롯 상태를 변경하는 함수
UIEmployeeManageListRenderer:CheckEmployeeIsAutoTraining -- 직원이 자동 훈련 중인지 확인하고 슬롯 번호를 반환하는 함수
UIEmployeeManageListRenderer:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageListRenderer:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 핸들러
UIEmployeeManageScript:Init -- 직원 관리 스크립트를 초기화하는 함수
UIEmployeeManageScript:ChangeLocationToClient -- 클라이언트에서 직원의 위치를 변경하는 함수
UIEmployeeManageScript:ChangeLocationToServer -- 서버로 직원의 위치 변경을 요청하는 함수
UIEmployeeManageScript:OnClickDeployBtn -- 배치 버튼 클릭 시 처리하는 함수
UIEmployeeManageScript:HandleButtonClickEvent1 -- 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:OnBeginPlay -- 게임 시작 시 직원 관리 UI 서비스를 초기화하는 함수
UIEmployeeManageService:UIOpen -- 직원 관리 UI를 여는 함수
UIEmployeeManageService:UIClose -- 직원 관리 UI를 닫는 함수
UIEmployeeManageService:UIRefresh -- 직원 관리 UI를 새로고침하는 함수
UIEmployeeManageService:RefreshTotalSalary -- 총 급여를 새로고침하는 함수
UIEmployeeManageService:RefreshLocation -- 직원의 위치 정보를 새로고침하는 함수
UIEmployeeManageService:SelectEmp -- 직원을 선택하는 함수
UIEmployeeManageService:StatSort -- 직원 목록을 필터와 정렬 기준에 따라 정렬하는 함수
UIEmployeeManageService:OnClickFilterBtn -- 필터 버튼 클릭 시 처리하는 함수
UIEmployeeManageService:OnClickTransferBtn -- 전송 버튼 클릭 시 처리하는 함수
UIEmployeeManageService:UpdateDeployBtn -- 배치 버튼을 업데이트하는 함수
UIEmployeeManageService:OnClickUpgradeBtn -- 업그레이드 버튼 클릭 시 처리하는 함수
UIEmployeeManageService:RequestStoreMangeRedDot -- 상점 관리 빨간 점 표시를 요청하는 함수
UIEmployeeManageService:OnClickSortBtn -- 정렬 버튼 클릭 시 처리하는 함수
UIEmployeeManageService:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent2 -- 필터 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent3 -- 전체 필터 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent4 -- 요리 필터 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent5 -- 서빙 필터 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent6 -- 정렬 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent7 -- 업그레이드 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent8 -- 전송 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent9 -- 오름차순 정렬 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeManageService:HandleButtonClickEvent10 -- 내림차순 정렬 버튼 클릭 이벤트를 처리하는 핸들러
EmployeeMoveStatByLevelData:Load -- 레벨별 직원 이동 스탯 데이터를 로드하는 함수
EmployeeMoveStatByLevelData:ConvertToTable -- 데이터를 테이블로 변환하는 함수
EmployeeSkillService:OnBeginPlay -- 게임 시작 시 직원 스킬 서비스를 초기화하는 함수
EmployeeSkillService:LoadData -- 직원 스킬 데이터를 로드하는 함수
EmployeeSkillService:GetData -- 스킬 ID로 스킬 데이터를 반환하는 함수
EmployeeSkillService:HasSkill -- 직원이 특정 스킬을 보유했는지 확인하는 함수
EmployeeSkillService:CanUseSkill -- 직원이 스킬을 사용할 수 있는지 확인하는 함수
EmployeeSkillService:ReturnSkillGradeValue -- 스킬 등급에 따른 값을 반환하는 함수
EmployeeSkillService:HasSkillOfType -- 직원이 특정 타입의 스킬을 보유했는지 확인하는 함수
EmployeeSkillService:ReturnSkillGrade -- 스킬 등급을 반환하는 함수
EmployeeSkillService:ReturnSkillName -- 스킬 이름을 반환하는 함수
EmployeeSkillService:ReturnSkillIcon -- 스킬 아이콘을 반환하는 함수
EmployeeSkillService:ReturnSkillDesc -- 스킬 설명을 반환하는 함수
EmployeeSkillService:ReturnSkillSlotBg_Mini -- 미니 스킬 슬롯 배경을 반환하는 함수
EmployeeSkillService:ReturnSkillGradeColor -- 스킬 등급에 따른 색상을 반환하는 함수
EmployeeSkillService:ReturnSkillSlotBg -- 스킬 슬롯 배경을 반환하는 함수
EmployeeSkillService:DisplaySkillSlot -- 스킬 슬롯을 화면에 표시하는 함수
EmployeeSkillService:ReturnUpgradeSkillNumByEquipLevel -- 장비 레벨에 따른 업그레이드 스킬 번호를 반환하는 함수
EmployeeSkillTypeData:Load -- 직원 스킬 타입 데이터를 로드하는 함수
EmployeeSkillTypeData:ConvertToTable -- 데이터를 테이블로 변환하는 함수
EmployeeUpgradeItemRenderer:OnBeginPlay -- 게임 시작 시 업그레이드 아이템 렌더러를 초기화하는 함수
EmployeeUpgradeItemRenderer:Init -- 아이템 ID로 업그레이드 아이템 슬롯을 초기화하는 함수
EmployeeUpgradeItemRenderer:OnClickItemAddBtn -- 아이템 추가 버튼 클릭 시 선택된 아이템 수를 증가시키는 함수
EmployeeUpgradeItemRenderer:OnClickItemSubBtn -- 아이템 제거 버튼 클릭 시 선택된 아이템 수를 감소시키는 함수
EmployeeUpgradeItemRenderer:RefreshSlectedCountText -- 선택된 아이템 수 텍스트를 새로고침하는 함수
EmployeeUpgradeItemRenderer:Init0 -- 선택된 아이템 슬롯을 초기화하는 함수 (수량 0으로 설정)
EmployeeUpgradeItemRenderer:SetPotionCount -- 포션 수량을 설정하는 함수
EmployeeUpgradeItemRenderer:HandleButtonClickEvent -- 아이템 슬롯 클릭 이벤트를 처리하는 핸들러
EmployeeUpgradeManager:OnBeginPlay -- 게임 시작 시 직원 업그레이드 관리자를 초기화하는 함수
EmployeeUpgradeManager:OnMapLeave -- 맵을 떠날 때 업그레이드 관련 데이터를 정리하는 함수
EmployeeUpgradeManager:SelectEmployee -- 업그레이드할 직원을 선택하는 함수
EmployeeUpgradeManager:RequestUpgrade -- 직원 업그레이드를 요청하는 함수
EmployeeUpgradeManager:Upgrade -- 직원의 능력을 업그레이드하는 함수
EmployeeUpgradeManager:UpgradeClient -- 클라이언트에서 직원 업그레이드 결과를 처리하는 함수
EmployeeUpgradeManager:ChangeWorkExpStatus -- 직원의 작업 경험치 상태를 변경하는 함수
EmployeeUpgradeManager:SetTimerForEmployeeWorkExp -- 직원 작업 경험치 타이머를 설정하는 함수
EmployeeUpgradeManager:RemoveTimerOfEmployeeWorkExp -- 직원 작업 경험치 타이머를 제거하는 함수
EmployeeUpgradeManager:UpgradeEffectProduction -- 업그레이드 효과를 생성하는 함수
EmployeeUpgradeManager:CheckCanOverLimit -- 한계돌파 가능 여부를 확인하는 함수
EmployeeUpgradeManager:CheckOverLimitCost -- 한계돌파 비용을 확인하는 함수
EmployeeUpgradeManager:SendClientOverLimitCostCheck -- 클라이언트에 한계돌파 비용 확인 결과를 전송하는 함수
EmployeeUpgradeManager:OverLimit -- 직원의 한계돌파를 실행하는 함수
EmployeeUpgradeManager:SendTryOverLimitResultToClient -- 한계돌파 시도 결과를 클라이언트에 전송하는 함수
EmployeeUpgradeManager:RefundExtraExp -- 초과 경험치를 환불하는 함수
EmployeeUpgradeManager:SendTutorialEventTriggerAfterUpgrade -- 업그레이드 후 튜토리얼 이벤트를 트리거하는 함수
EmployeeUpgradeManager:ToastMsg -- 토스트 메시지를 표시하는 함수
EmployeeUpgradeManager:HandlePlayerMoneyChangedEvent -- 플레이어 돈 변경 이벤트를 처리하는 핸들러
EmployeeUpgradeManager:HandlePlayerArcaneSymbolChangedEvent -- 플레이어 아케인 심볼 변경 이벤트를 처리하는 핸들러
EmployeeUpgradeService:OnBeginPlay -- 직원 업그레이드 서비스 초기화 시 실행되는 함수
EmployeeUpgradeService:LoadData -- 직원 업그레이드 관련 데이터를 로드하는 함수
EmployeeUpgradeService:GetExpData -- 레벨에 따른 경험치 데이터를 반환하는 함수
EmployeeUpgradeService:ReturnLevelExpOfExpSum -- 총 경험치로 레벨을 계산하여 반환하는 함수
EmployeeUpgradeService:ReturnNextLevelOfExpSum -- 총 경험치로 다음 레벨을 계산하여 반환하는 함수
EmployeeUpgradeService:CalcNextUpgradeData -- 다음 업그레이드 데이터를 계산하는 함수
EmployeeUpgradeService:CalculateAutoLevel -- 자동 레벨 업그레이드를 계산하는 함수
EmployeeUpgradeService:HasRequiredExp -- 필요한 경험치를 보유했는지 확인하는 함수
EmployeeUpgradeService:HasRequiredExpAdd -- 경험치 추가 시 필요한 경험치를 확인하는 함수
EmployeeUpgradeService:HasRequiredExpSub -- 경험치 차감 시 필요한 경험치를 확인하는 함수
EmployeeUpgradeService:ReturnOverLimitCost -- 한계돌파 비용을 반환하는 함수
EmployeeUpgradeService:ReturnOverLimitJemItemId -- 한계돌파 보석 아이템 ID를 반환하는 함수
EmployeeUpgradeService:ReturnExpFromPotionLevel -- 포션 레벨로 경험치를 반환하는 함수
EmployeeUpgradeService:RetrunExpItemCountTable -- 경험치 아이템 개수 테이블을 반환하는 함수
EmployeeUpgradeService:ReturnTransferRefundJemCost -- 전송 시 환불되는 보석 비용을 반환하는 함수
EmployeeUpgradeService:MaxBtn -- 최대 레벨까지 업그레이드 시 필요한 아이템을 계산하는 함수
EmployeeUpgradeService:ReturnSkillNumByOverLimitLevel -- 한계돌파 레벨에 따른 스킬 번호를 반환하는 함수
EmployeeUpgradeUIServcie:UIOpen -- 직원 업그레이드 UI를 여는 함수
EmployeeUpgradeUIServcie:UIClose -- 직원 업그레이드 UI를 닫는 함수
EmployeeUpgradeUIServcie:ReturnStatOptionDescByStatLevel -- 스탯 레벨에 따른 옵션 설명을 반환하는 함수
EmployeeUpgradeUIServcie:ReturnItemCountByID -- 아이템 ID로 플레이어가 보유한 아이템 개수를 반환하는 함수
EmployeeUpgradeUIServcie:CanRemoveSelectItem -- 선택된 아이템을 제거할 수 있는지 확인하는 함수
EmployeeUpgradeUIServcie:ReturnSelecteItemTotalExp -- 선택된 아이템들의 총 경험치를 반환하는 함수
EmployeeUpgradeUIServcie:ReturnSelectedItemLv -- 선택된 아이템들로 달성할 수 있는 레벨을 반환하는 함수
EmployeeUpgradeUIServcie:ReturnSelectedCountByItemID -- 특정 아이템 ID의 선택된 개수를 반환하는 함수
EmployeeUpgradeUIServcie:CanSelectItem -- 아이템을 선택할 수 있는지 확인하는 함수
EmployeeUpgradeUIServcie:RequestSelectItems -- 아이템 선택을 요청하고 레벨을 업데이트하는 함수
EmployeeUpgradeUIServcie:RequestClearAllSelectItems -- 모든 선택된 아이템을 초기화하는 함수
UIEmployeeUpgrade:OnBeginPlay -- 게임 시작 시 직원 업그레이드 UI를 초기화하는 함수
UIEmployeeUpgrade:Upgrade -- 직원 업그레이드를 실행하는 함수
UIEmployeeUpgrade:SetStatCategory -- 직원의 능력 카테고리를 설정하는 함수
UIEmployeeUpgrade:SetUIDetail -- 직원의 상세 정보 UI를 설정하는 함수
UIEmployeeUpgrade:SetUICurPreview -- 현재 능력치 미리보기 UI를 설정하는 함수
UIEmployeeUpgrade:SetUINextPreview -- 다음 능력치 미리보기 UI를 설정하는 함수
UIEmployeeUpgrade:SetUIExpSlider -- 경험치 슬라이더 UI를 설정하는 함수
UIEmployeeUpgrade:SetUIItem -- 업그레이드 아이템 UI를 설정하는 함수
UIEmployeeUpgrade:SetUICategory -- UI 카테고리를 설정하는 함수 (레벨업/한계돌파)
UIEmployeeUpgrade:PlayLevelUpEffect -- 레벨업 이팩트를 재생하는 함수
UIEmployeeUpgrade:SetSkillProduce -- 츄츄 레벨에 따라 스킬 UI를 설정하는 함수
UIEmployeeUpgrade:RefreshAfterLevelUp -- 레벨업 후 UI를 새로고침하는 함수
UIEmployeeUpgrade:OnClickLevelUpBtn -- 레벨업 버튼 클릭 시 처리하는 함수
UIEmployeeUpgrade:RefreshLevelUpBtn -- 레벨업 버튼 상태를 새로고침하는 함수
UIEmployeeUpgrade:OnClickResetBtn -- 리셋 버튼 클릭 시 처리하는 함수
UIEmployeeUpgrade:RefreshResetBtn -- 리셋 버튼 상태를 새로고침하는 함수
UIEmployeeUpgrade:ModifySelectItems -- 선택된 아이템 수량을 수정하는 함수
UIEmployeeUpgrade:SetSelcetItems -- 선택된 아이템 목록을 설정하는 함수
UIEmployeeUpgrade:AllClearSelectItems -- 선택된 모든 아이템을 초기화하는 함수
UIEmployeeUpgrade:SetSelectedItemSlot -- 선택된 아이템 슬롯 UI를 설정하는 함수
UIEmployeeUpgrade:OnClickOverLimitBtn -- 한계돌파 버튼 클릭 시 처리하는 함수
UIEmployeeUpgrade:OverLimit -- 한계돌파 가능 여부에 따라 처리하는 함수
UIEmployeeUpgrade:DisplayOverLimitPanel -- 한계돌파 패널 UI를 표시하는 함수
UIEmployeeUpgrade:DisplayOverLimitCost -- 한계돌파 비용을 표시하는 함수
UIEmployeeUpgrade:UpdateOverLimitCostFontColor -- 한계돌파 비용 폰트 색상을 업데이트하는 함수
UIEmployeeUpgrade:OverLimitDone -- 한계돌파 완료 후 처리하는 함수
UIEmployeeUpgrade:OpenToolTipJemCostPanel -- 보석 비용 툴팁 패널을 여는 함수
UIEmployeeUpgrade:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeUpgrade:HandleButtonClickEvent2 -- 스탯 카테고리 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeUpgrade:HandleButtonClickEvent3 -- 한계돌파 카테고리 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeUpgrade:HandleButtonClickEvent5 -- 레벨업 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeUpgrade:HandleButtonClickEvent6 -- 리셋 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeUpgrade:HandlePlayerInventoryItemChangedEvent -- 플레이어 인벤토리 아이템 변경 이벤트를 처리하는 핸들러
UIEmployeeUpgrade:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 핸들러
UIEmployeeUpgrade:HandleButtonClickEvent4 -- 한계돌파 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeUpgrade:HandleButtonClickEvent7 -- 보석 비용 툴팁 버튼 클릭 이벤트를 처리하는 핸들러
UIEmployeeUPgradeAuto:OnBeginPlay -- 게임 시작 시 UI 컴포넌트들을 초기화하는 함수
UIEmployeeUPgradeAuto:UIEnable -- UI 활성화/비활성화를 설정하는 함수
UIEmployeeUPgradeAuto:OnClickAutoLevelMaxBtn -- 자동 레벨 최대 버튼 클릭 시 처리하는 함수
UIEmployeeUPgradeAuto:OnClickAutoLevelAddBtn -- 자동 레벨 증가 버튼 클릭 시 처리하는 함수
UIEmployeeUPgradeAuto:OnClickAutoLevelSubBtn -- 자동 레벨 감소 버튼 클릭 시 처리하는 함수
UIEmployeeUPgradeAuto:RefreshLevel -- 레벨을 새로고침하는 함수
UIEmployeeUPgradeAuto:RefreshAutoPannel -- 자동 패널을 새로고침하는 함수
UIEmployeeUPgradeAuto:RefreshAutoBtn -- 자동 버튼을 새로고침하는 함수
UISkillOpenPopup:OnBeginPlay -- 게임 시작 시 스킬 오픈 팝업의 UI 컴포넌트들을 초기화하는 함수
UISkillOpenPopup:Open -- 스킬 오픈 팝업을 열고 애니메이션을 재생하는 함수
UISkillOpenPopup:Refresh -- 스킬 정보를 새로고침하여 UI에 표시하는 함수
UISkillOpenPopup:Close -- 스킬 오픈 팝업을 닫고 큐에 있는 다음 팝업을 여는 함수
UISkillOpenPopup:OpenAnim -- 일반 스킬 오픈 애니메이션을 재생하는 함수
UISkillOpenPopup:Refresh_Overlimit -- 한계돌파 팝업의 직원 정보를 새로고침하는 함수
UISkillOpenPopup:OpenAnim_OverLimit -- 한계돌파 스킬 오픈 애니메이션을 재생하는 함수
UISkillOpenPopup:HandleButtonClickEvent -- 팝업 닫기 버튼 클릭 이벤트를 처리하는 핸들러
KitchenAppData:Load -- 주방기기 데이터를 ID로 조회하여 속성값들을 로드하는 함수
KitchenAppManager:Init -- 주방기기 매니저의 초기화를 수행하는 함수
KitchenAppManager:OnMapEnter -- 플레이어가 로비 맵에 입장할 때 초기화하는 함수
KitchenAppManager:OnMapLeave -- 플레이어가 로비 맵에서 나갈 때 초기화하는 함수
KitchenAppManager:InitUseApp -- 주방기기 사용자 정보를 초기화하는 함수
KitchenAppManager:ReleaseApp -- 특정 주방기기의 사용자 할당을 해제하는 함수
KitchenAppManager:AssignApp -- 특정 주방기기에 사용자를 할당하는 함수
KitchenAppManager:ReturnAvailableApp -- 사용 가능한 주방기기의 인덱스를 순차적으로 반환하는 함수
KitchenAppManager:ReturnRandomAvailableApp -- 사용 가능한 주방기기 중 랜덤한 인덱스를 반환하는 함수
KitchenAppService:OnBeginPlay -- 게임 시작 시 주방기기 데이터를 로드하고 초기화하는 함수
KitchenAppService:InsertKitAppOffsetDataSet -- 주방기기 위치 데이터를 데이터셋에 삽입하는 에디터용 함수
KitchenAppService:LoadData -- 주방기기 데이터셋에서 데이터를 로드하여 내부 테이블에 저장하는 함수
KitchenAppService:GetData -- ID로 주방기기 데이터를 조회하여 반환하는 함수
KitchenAppService:ReturnDisplayNum -- 플레이어가 사용 가능한 디스플레이 개수를 계산하여 반환하는 함수
KitchenAppService:ReturnDisplayRUID -- 디스플레이에 표시할 버거 스프라이트 RUID를 반환하는 함수
KitchenAppService:ReturnKitchenAppRUID -- 주방기기의 사용 상태에 따른 스프라이트 RUID를 반환하는 함수
KitchenAppService:UpdateDisplaySpriteByID -- 특정 디스플레이 슬롯의 스프라이트를 업데이트하는 함수
KitchenAppService:UpdateAllDisplaySprite -- 모든 디스플레이의 스프라이트를 업데이트하는 함수
KitchenAppService:UpdateKitchenAppSpriteByID -- 특정 주방기기의 스프라이트를 ID로 업데이트하는 함수
KitchenAppService:UpdateAllKitchenAppSprite -- 모든 주방기기의 스프라이트를 업데이트하는 함수
KitchenAppService:UpdateKitchenAppPosByID -- 특정 주방기기의 위치를 ID로 업데이트하는 함수
KitchenAppService:UpdateAllEmployeeUseKitchenAppPos -- 모든 직원이 사용할 주방기기 위치를 업데이트하는 함수
KitchenAppService:VisibleKitAppsEntity -- 주방기기 엔티티들을 확장 단계에 맞게 생성하고 설정하는 함수
KitchenAppService:KitchenAppProductionByID -- 특정 주방기기의 작동 상태를 변경하는 함수
KitchenAppService:UpdateEmployeeUseKitchenAppPos -- 직원이 사용할 주방기기 위치를 업데이트하는 함수
KitchenAppService:HandleButtonClickEditorEvent -- 에디터에서 버튼 클릭 이벤트를 처리하여 데이터셋을 삽입하는 함수
ChangedSelectedIngreCardsEvent:Init -- 선택된 재료 카드 변경 이벤트를 초기화하는 함수
DrawBurgerUIService:DrawBurgerUI -- 버거 UI를 그리고 재료들을 배치하는 함수
DrawBurgerUIService:ReturnIngreData -- 재료 데이터를 기반으로 UI 배치 정보를 계산하는 함수
DrawBurgerUIService:TweenIngredientUI -- 재료 UI를 트윈 애니메이션과 함께 생성하는 함수
DrawBurgerUIService:DrawIngredientUI -- 재료 UI를 즉시 그리는 함수
DrawBurgerUIService:HandleTextInputEndEditEvent -- 번 스킨 ID 입력을 처리하여 버거 UI를 업데이트하는 핸들러
DrawBurgerUIService:HandleTextInputEndEditEvent2 -- 재료 ID 입력을 처리하여 재료를 추가하는 핸들러
DrawBurgerUIService:HandleButtonClickEvent -- 재료 목록을 초기화하는 버튼 클릭 핸들러
IngreCardSetLogic:SetIngreCard -- 재료 카드를 선택 목록에 추가하는 함수
IngreCardSetLogic:UnsetIngreCard -- 재료 카드를 선택 목록에서 제거하는 함수
IngreCardSetLogic:GetCurrentSelectedTotalCount -- 현재 선택된 재료 카드의 총 개수를 반환하는 함수
IngreCardSetLogic:UnsetIngreCardAll -- 선택된 모든 재료 카드를 초기화하는 함수
IngreCardSetLogic:GetIndexById -- 테이블에서 특정 ID의 인덱스를 찾는 함수
UIEntityLogic_RecipeGroup:InitializeRecipeUI -- 레시피 UI를 초기화하고 레시피북을 열어주는 함수
BunData:Load -- 번 데이터를 로드하고 상단/하단 부분을 초기화하는 함수
BunDetailData:Load -- CSV 데이터로부터 번 상세 정보를 로드하는 함수
BunSkinData:Load -- 번 스킨 데이터를 로드하고 획득 조건을 설정하는 함수
BunSkinDetailData:Load -- CSV 데이터로부터 번 스킨 상세 정보를 로드하는 함수
IngredientData:Load -- CSV 데이터로부터 재료 정보를 로드하는 함수
IngredientData:GetTasteScore -- 현재 스테이지와 플레이어 상태에 따른 재료의 맛 점수를 계산하는 함수
IngredientData:GetCost -- 현재 스테이지와 플레이어 상태에 따른 재료의 비용을 계산하는 함수
IngredientData:IsIngreBuffed -- 재료가 현재 스테이지나 플레이어 효과로 버프를 받고 있는지 확인하는 함수
IngredientData:IsIngreStageBuffed -- 재료가 현재 스테이지에서 버프를 받고 있는지 확인하는 함수
IngredientDataSetLogic:OnBeginPlay -- 게임 시작 시 데이터셋을 로드하는 함수
IngredientDataSetLogic:LoadDataSet -- 재료, 번, 번 스킨 데이터를 CSV에서 로드하는 함수
IngredientDataSetLogic:ReturnPropertyIconRUIDByType -- 재료 속성 타입에 따른 아이콘 RUID를 반환하는 함수
IngredientDataSetLogic:ReturnDishRUIDByGrade -- 등급에 따른 접시 RUID를 반환하는 함수
IngredientDataSetLogic:ReturnRandomIngredientOfGrade -- 특정 등급과 태그 조건에 맞는 랜덤 재료를 반환하는 함수
IngredientDataSetLogic:ReturnRandomBunOfGrade -- 특정 등급의 랜덤 번을 반환하는 함수
IngredientDataSetLogic:ReturnIsTagMatch -- 재료가 요구되는 태그와 일치하는지 확인하는 함수
IngredientDataSetLogic:ReturnExclusiveIngredientOfTag -- 특정 태그에만 해당하는 재료를 랜덤으로 반환하는 함수
IngredientDataSetLogic:ReturnIsTagExclusive -- 재료가 특정 태그에만 배타적으로 해당하는지 확인하는 함수
IngredientDataSetLogic:GetIngredientData -- ID로 재료 데이터를 가져오는 함수
IngredientDataSetLogic:GetBunData -- ID로 번 데이터를 가져오는 함수
IngredientDataSetLogic:GetBunDetailData -- ID와 부위 키로 번 상세 데이터를 가져오는 함수
IngredientDataSetLogic:GetBunSkinData -- ID로 번 스킨 데이터를 가져오는 함수
IngredientDataSetLogic:GetBunSkinDetailData -- ID와 부위 키로 번 스킨 상세 데이터를 가져오는 함수
IngredientDataSetLogic:GetBunSkinBonusRate -- 플레이어가 수집한 번 스킨 개수에 따른 보너스 비율을 계산하는 함수
IngredientDataSetLogic:GetBalanceThreshold -- 플레이어의 밸런스 임계값을 계산하는 함수
IngredientDataSetLogic:GetSpicyThreshold -- 플레이어의 매운맛 임계값을 계산하는 함수
IngredientDataSetLogic:RequestSetIngreNameKeywords -- 재료 이름 키워드를 설정하도록 서버에 요청하는 함수
IngredientDataSetLogic:SetIngreNameKeywords -- 플레이어의 재료 이름 키워드를 설정하는 함수
RecipeComboData:Load -- 레시피 콤보 데이터를 CSV에서 로드하고 태그별 필요 개수를 설정하는 함수
RecipeData:ConvertToTable -- 레시피 데이터를 테이블로 변환하는 함수
RecipeData:SetFromTable -- 테이블 데이터로부터 레시피 데이터를 설정하는 함수
RecipeData:GetIsBunSkinned -- 번에 스킨이 적용되었는지 확인하는 함수
RecipeData:ConvertToDBTable -- 데이터베이스 테이블로 변환하는 함수
RecipeData:SerFromDBTable_Ver1 -- 데이터베이스 테이블 버전 1에서 데이터를 역직렬화하는 함수
RecipeDataSetLogic:OnBeginPlay -- 게임 시작 시 레시피 데이터셋을 초기화하는 함수
RecipeDataSetLogic:LoadDataSet -- 트렌드 데이터를 로드하는 함수
RecipeDataSetLogic:IsRecipeTrend -- 레시피가 현재 트렌드인지 확인하는 함수
RecipeDataSetLogic:IsRecipeIncludeIngredient -- 레시피에 특정 재료가 포함되어 있는지 확인하는 함수
RecipeDataSetLogic:GetTrendData -- 트렌드 ID로 트렌드 데이터를 반환하는 함수
RecipeDataSetLogic:ReturnRerollCost -- 리롤 횟수에 따른 비용을 반환하는 함수
RecipeDataSetLogic:ReturnBestTasteScore -- 특정 태그의 레시피 중 최고 맛 점수를 반환하는 함수
RecipeDataSetLogic:GetRecipeCost -- 레시피의 비용을 계산하여 반환하는 함수
RecipeDataSetLogic:ReturnRandomRecipeNameCheckProhibited -- 금지어를 확인하여 랜덤 레시피 이름을 반환하는 함수
RecipeDataSetLogic:RequestSetRandomRecipeName -- 랜덤 레시피 이름 설정을 요청하는 함수
RecipeDataSetLogic:RequestSetBurgerNameInputText -- 버거 이름 입력 텍스트를 설정하는 함수
RecipeIngreDrawData:DataToTable -- 레시피 재료 그리기 데이터를 테이블 형태로 변환하는 함수
RecipeIngreDrawData:TableToData -- 테이블 데이터를 레시피 재료 그리기 데이터로 변환하는 함수
RecipeIngreDrawData:Init -- 레시피 재료 그리기 데이터를 초기화하는 함수
RecipeIngreDrawEnum:EncodeIngreList -- 재료 리스트를 JSON 문자열로 인코딩하는 함수
RecipeIngreDrawEnum:DecodeIngreList -- JSON 문자열을 재료 리스트로 디코딩하는 함수
RecipeTagData:Load -- 레시피 태그 데이터를 CSV에서 로드하고 색상 정보를 설정하는 함수
RecipeTagDataSetLogic:OnBeginPlay -- 게임 시작 시 데이터셋을 로드하는 함수
RecipeTagDataSetLogic:LoadDataSet -- 레시피 태그 데이터셋을 로드하는 함수
RecipeTagDataSetLogic:ReturnMainTypeOfIngres -- 재료들의 주요 타입을 반환하는 함수
RecipeTagDataSetLogic:PopRecipeTypeIcon -- 레시피 타입 아이콘을 팝업으로 표시하는 함수
RecipeTagDataSetLogic:ReturnRecipeTagSortIndex -- 레시피 태그의 정렬 인덱스를 반환하는 함수
RecipeTagDataSetLogic:IsRecipeComboActiveForRecipe -- 레시피에 대해 레시피 콤보가 활성화되어 있는지 확인하는 함수
RecipeTagDataSetLogic:IsRecipeComboActiveForTag -- 태그에 대해 레시피 콤보가 활성화되어 있는지 확인하는 함수
RecipeTagDataSetLogic:GetRecipeTagData -- 태그로 레시피 태그 데이터를 가져오는 함수
TasteGradeData:Load -- 맛 등급 데이터를 CSV에서 로드하는 함수
TasteGradeDataSetLogic:OnBeginPlay -- 게임 시작 시 데이터셋을 로드하는 함수
TasteGradeDataSetLogic:LoadDataSet -- 맛 등급 데이터셋을 로드하는 함수
TasteGradeDataSetLogic:ReturnGradeDataByScore -- 점수에 따른 등급 데이터를 반환하는 함수
TasteGradeDataSetLogic:ReturnAttractiveScoreByScore -- 점수에 따른 매력도 점수를 반환하는 함수
TasteGradeDataSetLogic:GetTasteGradeData -- 등급 인덱스로 맛 등급 데이터를 가져오는 함수
TasteGradeDataSetLogic:GetFinalComboBonus -- 플레이어의 최종 콤보 보너스를 계산하는 함수
TasteGradeDataSetLogic:GetFinalBalanceBonus -- 플레이어의 최종 밸런스 보너스를 계산하는 함수
TrendData:Load -- 트렌드 데이터를 CSV에서 로드하는 함수
UIIngreDishIcon:SetItem -- 재료 아이템 정보를 설정하는 함수
UIIngreDishIcon:OnBeginPlay -- 게임 시작 시 UI 요소들을 초기화하는 함수
UIIngreDishIcon:OnClickItem -- 아이템 클릭 시 호출되는 함수
UIRecipeBook:Open -- 레시피북 UI를 여는 함수
UIRecipeBook:Close -- 레시피북 UI를 닫는 함수
UIRecipeBook:Refresh -- 레시피북 UI를 새로고침하는 함수
UIRecipeBook:OpenUIIngreCardSetting -- 재료 카드 설정 UI를 여는 함수
UIRecipeBook:OnClickAutoSetBtn -- 자동 설정 버튼 클릭 시 호출되는 함수
UIRecipeBook:ClearFunction -- 레시피 설정을 초기화하는 함수
UIRecipeBook:RefreshComboInfo -- 레시피 콤보 정보를 새로고침하는 함수
UIRecipeBook:OnClickResetBtn -- 리셋 버튼 클릭 시 호출되는 함수
UIRecipeBook:OnBeginPlay -- 게임 시작 시 버튼 이벤트를 연결하는 함수
UIRecipeBook:RefreshReplaceBtns -- 교체 버튼들을 새로고침하는 함수
UIRecipeBook:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent2 -- 레시피 그룹 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent3 -- 재료 카드 설정 이동 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent4 -- 전체 삭제 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent5 -- 자동 설정 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent6 -- 레시피 그룹 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent7 -- 레시피 콤보 정보 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent8 -- 메뉴 콤보 오픈 조건 툴팁 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent9 -- 리셋 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBook:HandleButtonClickEvent10 -- 레시피 목록 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBurgerSlot:Init -- 레시피 버거 슬롯 UI 요소들을 초기화하는 함수
UIRecipeBurgerSlot:Refresh -- 레시피 버거 슬롯을 새로고침하는 함수
UIRecipeBurgerSlot:OnClickSlotRecipeBook -- 레시피북에서 슬롯 클릭 시 호출되는 함수
UIRecipeBurgerSlot:OnClickSlotRecipeList -- 레시피 리스트에서 슬롯 클릭 시 호출되는 함수
UIRecipeBurgerSlot:OnClickLockedSlot -- 잠긴 슬롯 클릭 시 호출되는 함수
UIRecipeBurgerSlot:SetSelected -- 슬롯의 선택 상태를 설정하는 함수
UIRecipeCountBar:OnBeginPlay -- 게임 시작 시 레시피 카운트 바를 초기화하는 함수
UIRecipeCountBar:Refresh -- 레시피 카운트 바를 새로고침하는 함수
UIRecipeSortButton:HandleButtonClickEvent -- 레시피 정렬 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeTag:Init -- 레시피 태그 UI 요소들을 초기화하는 함수
UIRecipeTag:Refresh -- 레시피 태그 정보를 새로고침하는 함수
UIRecipeTag:Clear -- 레시피 태그를 초기화하는 함수
UIBunDetail:Init -- 번 상세정보 UI 요소들을 초기화하는 함수
UIBunDetail:Refresh -- 번 데이터를 기반으로 상세정보를 새로고침하는 함수
UIBunList:Open -- 번 선택 UI를 여는 함수
UIBunList:Close -- 번 선택 UI를 닫는 함수
UIBunList:RefreshList -- 번 목록을 새로고침하는 함수
UIBunList:RefreshDetail -- 선택된 번의 상세 정보를 새로고침하는 함수
UIBunList:OnSetFunction -- 선택된 번을 설정하는 함수
UIBunList:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIBunList:HandleButtonClickEvent2 -- 번 설정 버튼 클릭 이벤트를 처리하는 핸들러
UIBunList:HandleButtonClickEvent3 -- 배경 클릭으로 닫기 이벤트를 처리하는 핸들러
UIBunSelectBtn:Init -- 번 선택 버튼 UI 요소들을 초기화하는 함수
UIBunSelectBtn:Refresh -- 번 선택 버튼의 상태와 정보를 새로고침하는 함수
UIBunSelectBtn:OnSelectFunction -- 번 선택 시 호출되는 함수
UIBunSelectBtn:HandleButtonClickEvent -- 번 선택 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreAutoSetSelectArea:Open -- 재료 자동 설정 선택 영역을 여는 함수
UIIngreAutoSetSelectArea:Close -- 재료 자동 설정 선택 영역을 닫는 함수
UIIngreAutoSetSelectBtn:OnBeginPlay -- 재료 자동 설정 버튼을 초기화하고 클릭 이벤트를 연결하는 함수
UIIngreCard:Init -- 재료 카드 UI 요소들을 초기화하고 클릭 이벤트를 연결하는 함수
UIIngreCard:Refresh -- 재료 카드의 정보를 새로고침하는 함수
UIIngreCard:HandleChangedSelectedIngreCardsEvent -- 선택된 재료 카드 변경 이벤트를 처리하는 핸들러
UIIngreCardSetting:OnBeginPlay -- 재료 카드 설정 UI 초기화 및 이벤트 연결하는 함수
UIIngreCardSetting:Open -- 재료 카드 설정 UI를 열고 초기 설정을 하는 함수
UIIngreCardSetting:Close -- 재료 카드 설정 UI를 닫는 함수
UIIngreCardSetting:RequestMoveToRecipeMaking -- 레시피 제작으로 이동을 요청하는 함수
UIIngreCardSetting:RefreshIngreCardList -- 필터에 따라 재료 카드 리스트를 새로고침하는 함수
UIIngreCardSetting:RefreshIngreSlotList -- 선택된 재료 슬롯 리스트를 새로고침하는 함수
UIIngreCardSetting:DeselectCardAll -- 모든 카드 선택을 해제하는 함수
UIIngreCardSetting:RefreshBunSetSlot -- 번 설정 슬롯을 새로고침하는 함수
UIIngreCardSetting:RefreshBalanceBar -- 밸런스 바를 새로고침하는 함수
UIIngreCardSetting:SetIngreGachaRedDot -- 재료 가차 버튼의 빨간점 표시를 설정하는 함수
UIIngreCardSetting:OnClickFilterBtn -- 필터 버튼 클릭 시 호출되는 함수
UIIngreCardSetting:OnClickAutoSetBtn -- 자동 설정 버튼 클릭 시 호출되는 함수
UIIngreCardSetting:ReturnAutoSetIngreCardList -- 태그에 따라 자동 설정할 재료 카드 리스트를 반환하는 함수
UIIngreCardSetting:IsNeedToExclusive -- 배타적 재료가 필요한지 판단하는 함수
UIIngreCardSetting:SetBunRedDot -- 번 선택 버튼의 빨간점 표시를 설정하는 함수
UIIngreCardSetting:AutoSetIngreCard -- 태그에 따라 재료 카드를 자동으로 설정하는 함수
UIIngreCardSetting:CheckTutorial -- 튜토리얼 조건을 체크하는 함수
UIIngreCardSetting:SetSort -- 정렬 방식을 설정하는 함수
UIIngreCardSetting:SetFilter -- 필터를 설정하는 함수
UIIngreCardSetting:RefreshSideMenuInfo -- 사이드 메뉴 정보를 새로고침하는 함수
UIIngreCardSetting:HandleButtonClickEvent -- 레시피 제작 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleButtonClickEvent2 -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleButtonClickEvent3 -- 모든 선택 해제 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleButtonClickEvent4 -- 자동 설정 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleButtonClickEvent5 -- 번 선택 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleButtonClickEvent6 -- 재료 가차 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleButtonClickEvent7 -- 필터 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleButtonClickEvent8 -- 정렬 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleButtonClickEvent9 -- 사이드 메뉴 정보 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreCardSetting:HandleChangedSelectedIngreCardsEvent -- 선택된 재료 카드 변경 이벤트를 처리하는 핸들러
UIIngredientProperty:Refresh -- 재료 속성 정보를 새로고침하는 함수
UIIngredientProperty:Init -- 재료 속성 UI 요소들을 초기화하는 함수
UIIngreFilterSelectArea:Open -- 재료 필터 선택 영역을 여는 함수
UIIngreFilterSelectArea:Close -- 재료 필터 선택 영역을 닫는 함수
UIIngreFilterSelectBtn:OnBeginPlay -- 재료 필터 선택 버튼을 초기화하고 클릭 이벤트를 연결하는 함수
UIIngreSetSlot:Init -- 재료 설정 슬롯 UI 요소들을 초기화하는 함수
UIIngreSetSlot:Refresh -- 재료 설정 슬롯의 상태와 정보를 새로고침하는 함수
UIIngreSetSlot:EmptyButtonFunction -- 빈 슬롯을 클릭했을 때 호출되는 함수
UIIngreSetSlot:FilledButtonFunction -- 재료가 있는 슬롯을 클릭했을 때 호출되는 함수
UIIngreSetSlot:LockedButtonFunction -- 잠긴 슬롯을 클릭했을 때 호출되는 함수
UIIngreSetSlot:HandleChangedSelectedIngreCardsEvent -- 선택된 재료 카드 변경 이벤트를 처리하는 핸들러
UIRecipeComboInfo:Open -- 레시피 콤보 정보 창을 여는 함수
UIRecipeComboInfo:Close -- 레시피 콤보 정보 창을 닫는 함수
UIRecipeComboInfo:Refresh -- 레시피 콤보 정보 목록을 새로고침하는 함수
UIRecipeComboInfo:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeComboInfo:HandleButtonClickEvent2 -- 배경 클릭으로 닫기 이벤트를 처리하는 핸들러
UIRecipeComboInfoSlot:Init -- 레시피 콤보 정보 슬롯 UI 요소들을 초기화하는 함수
UIRecipeComboInfoSlot:Refresh -- 레시피 콤보 정보 슬롯을 새로고침하는 함수
UIRecipeComboTagSlot:Refresh -- 레시피 콤보 태그 슬롯을 새로고침하는 함수
UIRecipeList:OnBeginPlay -- 게임 시작 시 레시피 리스트를 초기화하는 함수
UIRecipeList:RefreshDetail -- 레시피 상세 정보를 새로고침하는 함수
UIRecipeList:RefreshListByKey -- 키에 따라 레시피 리스트를 새로고침하는 함수
UIRecipeList:FilterRecipes -- 필터 조건에 따라 레시피를 필터링하는 함수
UIRecipeList:SortRecipes -- 정렬 키에 따라 레시피를 정렬하는 함수
UIRecipeListDetail:Init -- 레시피 리스트 상세 정보 UI 요소들을 초기화하는 함수
UIRecipeListDetail:Refresh -- 레시피 상세 정보를 새로고침하는 함수
UIRecipeListDetail:InitEntitiesForEmpty -- 빈 상태에 따라 엔티티들을 초기화하는 함수
UIRecipeListDetail:RefreshPriceInfoText -- 가격 정보 텍스트를 새로고침하는 함수
UIRecipeListHolder:OnBeginPlay -- 게임 시작 시 레시피 리스트 홀더를 초기화하는 함수
UIRecipeListHolder:Open -- 레시피 리스트 홀더를 여는 함수
UIRecipeListHolder:Close -- 레시피 리스트 홀더를 닫는 함수
UIRecipeListHolder:RefreshListAndDetail -- 레시피 리스트와 상세 정보를 새로고침하는 함수
UIRecipeListHolder:RefreshRecipeCountBar -- 레시피 카운트 바를 새로고침하는 함수
UIRecipeListHolder:SetEntitiesEnableByKey -- 키에 따라 엔티티들의 활성화 상태를 설정하는 함수
UIRecipeListHolder:RefreshSetButton -- 설정 버튼을 새로고침하는 함수
UIRecipeListHolder:SetButtonDim -- 버튼의 비활성화 상태를 설정하는 함수
UIRecipeSetButtonArea:OnBeginPlay -- 게임 시작 시 레시피 설정 버튼 영역을 초기화하는 함수
UIRecipeSetButtonArea:OnClickSetButton -- 레시피 설정 버튼 클릭 시 호출되는 함수
UIRecipeSetButtonArea:OnClickClearButton -- 레시피 해제 버튼 클릭 시 호출되는 함수
UIRecipeSetButtonArea:MoveToSetIngrePage -- 재료 설정 페이지로 이동하는 함수
UIRecipeSetButtonArea:OnClickSetVIPOrderButton -- VIP 주문 설정 버튼 클릭 시 호출되는 함수
UIRecipeSetButtonArea:OnClickSetTrialButton -- 트라이얼 설정 버튼 클릭 시 호출되는 함수
UIRecipeSetButtonArea:RefreshSetButton -- 레시피 설정/해제 버튼의 상태를 새로고침하는 함수
UIRecipeSetButtonArea:RefreshMoveToMakeBtnDim -- 제작 페이지로 이동 버튼의 비활성화 상태를 새로고침하는 함수
UIRecipeSetButtonArea:RefreshVIPOrderSelectBtnDim -- VIP 주문 선택 버튼의 비활성화 상태를 새로고침하는 함수
UIRecipeSetButtonArea:OnClickDeleteButton -- 레시피 삭제 버튼 클릭 시 호출되는 함수
UIRecipeSetButtonArea:RefreshDeleteBtnDim -- 삭제 버튼의 비활성화 상태를 새로고침하는 함수
UIRecipeSetTopBar:Refresh -- 매개변수에 따라 레시피 설정 상단 바를 새로고침하는 함수
UIRecipeSetTopBar:SetTrialResultGuess -- 트라이얼 결과 예상을 설정하는 함수
UIRecipeSetTopBar:OnBeginPlay -- 게임 시작 시 레시피 설정 상단 바를 초기화하는 함수
UIRecipeSetTopBar:SetEnableSortList -- 정렬 목록의 활성화 상태를 설정하는 함수
UIRecipeSetTopBar:RefreshVIPOrderRequirements -- VIP 주문 요구사항을 새로고침하는 함수
UIBunSkinListSlot:Init -- 번 스킨 리스트 슬롯 UI 요소들을 초기화하는 함수
UIBunSkinListSlot:Refresh -- 번 스킨 슬롯을 새로고침하는 함수
UIBunSkinListSlot:EnableSelected -- 선택 상태를 설정하는 함수
UIBunSkinListSlot:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeBunSkinDetail:Init -- 번 스킨 상세 정보 UI 요소들을 초기화하는 함수
UIRecipeBunSkinDetail:Refresh -- 번 스킨 상세 정보를 새로고침하는 함수
UIRecipeBunSkinList:OnBeginPlay -- 게임 시작 시 번 스킨 리스트를 초기화하는 함수
UIRecipeBunSkinList:Open -- 번 스킨 리스트를 여는 함수
UIRecipeBunSkinList:Close -- 번 스킨 리스트를 닫는 함수
UIRecipeBunSkinList:StartTween -- 열기/닫기 트위 애니메이션을 시작하는 함수
UIRecipeBunSkinList:Refresh -- 번 스킨 리스트를 새로고침하는 함수
UIRecipeBunSkinList:RefreshList -- 번 스킨 리스트 아이템들을 새로고침하는 함수
UIRecipeBunSkinList:OnClickSlot -- 번 스킨 슬롯 클릭 시 호출되는 함수
UIRecipeBunSkinList:OnClickSkipBtn -- 건너뛰기 버튼 클릭 시 호출되는 함수
UIRecipeBunSkinList:OnClickUseBtn -- 사용 버튼 클릭 시 호출되는 함수
UIRecipeBunSkinList:BurgerMoveOut -- 버거를 바깥으로 이동시키는 함수
UIRecipeBunSkinList:BurgerMoveIn -- 버거를 안쪽으로 이동시키는 함수
UIRecipeBunSkinList:OnSelectBunSkinId -- 번 스킨 ID를 선택할 때 호출되는 함수
UIRecipeBunSkinList:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeChoiceBtn:Init -- 레시피 선택 버튼 UI 요소들을 초기화하는 함수
UIRecipeChoiceBtn:Refresh -- 재료 정보를 기반으로 선택 버튼을 새로고침하는 함수
UIRecipeChoiceBtn:Choice -- 재료를 선택하는 함수
UIRecipeEmployeeDetail:Init -- 직원 상세 정보 UI 요소들을 초기화하는 함수
UIRecipeEmployeeDetail:Refresh -- 직원 상세 정보를 새로고침하는 함수
UIRecipeEmployeeList:OnBeginPlay -- 게임 시작 시 직원 목록 UI를 초기화하는 함수
UIRecipeEmployeeList:Close -- 직원 목록 UI를 닫는 함수
UIRecipeEmployeeList:StartTween -- 직원 목록 UI의 트윈 애니메이션을 시작하는 함수
UIRecipeEmployeeList:Refresh -- 직원 목록을 새로고침하는 함수
UIRecipeEmployeeList:Open -- 직원 목록 UI를 여는 함수
UIRecipeEmployeeList:RefreshList -- 직원 목록을 새로고침하고 정렬하는 함수
UIRecipeEmployeeList:RefreshDetail -- 선택된 직원의 상세 정보를 새로고침하는 함수
UIRecipeEmployeeList:OnClickSkipBtn -- 직원 선택을 건너뛰는 함수
UIRecipeEmployeeList:OnClickUseSkillBtn -- 직원 스킬 사용 버튼을 클릭하는 함수
UIRecipeEmployeeList:ReturnChatBalloonType -- 직원의 채팅 벌룬 타입을 반환하는 함수
UIRecipeEmployeeList:SetEmployeeSlot -- 직원 슬롯의 상태를 설정하는 함수
UIRecipeEmployeeList:OnClickChatBalloon -- 채팅 벌룬을 클릭하는 함수
UIRecipeEmployeeList:HandleButtonClickEvent -- 스킵 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeEmployeeList:HandleButtonClickEvent2 -- 스킬 사용 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeEmployeeList:HandleButtonClickEvent3 -- 다른 스킵 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeEmployeeList:HandleButtonClickEvent4 -- 채팅 벌룬 클릭 이벤트를 처리하는 핸들러
UIRecipeMaking:Open -- 레시피 만들기 UI를 여는 함수
UIRecipeMaking:Close -- 레시피 만들기 UI를 닫는 함수
UIRecipeMaking:RequestEndRecipeMaking -- 레시피 만들기 종료를 요청하는 함수
UIRecipeMaking:SetChoicePairs -- 선택 가능한 재료 쌍들을 설정하는 함수
UIRecipeMaking:SetChoiceButtons -- 선택 버튼들을 설정하는 함수
UIRecipeMaking:ChoiceFunction -- 재료를 선택하는 함수
UIRecipeMaking:CompleteMakingFunction -- 레시피 만들기를 완료하는 함수
UIRecipeMaking:SpawnIngredient -- 재료를 생성하고 버거에 추가하는 함수
UIRecipeMaking:RefreshCountText -- 남은 선택 횟수 텍스트를 새로고침하는 함수
UIRecipeMaking:RefreshBalanceBar -- 밸런스 바를 새로고침하는 함수
UIRecipeMaking:RefreshSpicinessBar -- 매운맛 바를 새로고침하는 함수
UIRecipeMaking:CheckBalanceCombo -- 밸런스 콤보를 확인하고 처리하는 함수
UIRecipeMaking:RefreshScoreBar -- 점수 바를 새로고침하는 함수
UIRecipeMaking:RerollChoicePairs -- 선택지 쌍들을 다시 뒤섭는 함수
UIRecipeMaking:StartRecipeMaking -- 레시피 만들기를 시작하는 함수
UIRecipeMaking:RefreshRerollButton -- 리롤 버튼을 새로고침하는 함수
UIRecipeMaking:SetBalanceZone -- 밸런스 영역을 설정하는 함수
UIRecipeMaking:RefreshSideMenuInfo -- 사이드 메뉴 정보를 새로고침하는 함수
UIRecipeMaking:HandleButtonClickEvent -- 레시피 만들기 종료 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeMaking:HandleButtonClickEvent2 -- 레시피 만들기 완료 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeMaking:HandleButtonClickEvent3 -- 리롤 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeMaking:HandlePlayerArcaneSymbolChangedEvent -- 플레이어의 아카네 심볼 변경 이벤트를 처리하는 핸들러
UIRecipeMaking:HandleButtonClickEvent4 -- 사이드 메뉴 정보 버튼 클릭 이벤트를 처리하는 핸들러
UIRecipeResult:OnBeginPlay -- 게임 시작 시 버거 완성 효과 리소스를 최적화하여 로드하는 함수
UIRecipeResult:Init -- 레시피 결과 UI의 모든 요소를 초기화하는 함수
UIRecipeResult:Open -- 레시피 결과 UI를 여는 함수
UIRecipeResult:MakeTweenNumTextRising -- 숫자 텍스트가 상승하는 트윈 애니메이션을 만드는 함수
UIRecipeResult:RequestRefreshTasteScoreBar -- 맛 점수 바를 새로고침 요청하는 함수
UIRecipeResult:RequestRefreshBalanceScoreBar -- 밸런스 점수 바를 새로고침 요청하는 함수
UIRecipeResult:SetBalanceResult -- 밸런스 결과를 설정하고 성공 여부를 반환하는 함수
UIRecipeResult:RequestRefreshBalanceBonus -- 밸런스 보너스를 새로고침 요청하는 함수
UIRecipeResult:RequestRefreshSpicinessScoreBar -- 매운맛 점수 바를 새로고침 요청하는 함수
UIRecipeResult:SetSpicyResult -- 매운맛 결과를 설정하는 함수
UIRecipeResult:RequestRefreshPriceBar -- 가격 바를 새로고침 요청하는 함수
UIRecipeResult:RequestTagIconPopped -- 태그 아이콘이 팝업되도록 요청하는 함수
UIRecipeResult:ChangeRenderIndex -- 렌더링 인덱스를 변경하는 함수
UIRecipeResult:RenderFunction -- 렌더링 단계에 따라 결과를 표시하는 함수
UIRecipeResult:SetInfoText -- 정보 텍스트를 설정하고 표시하는 함수
UIRecipeResult:SetSelectedEmployeeInfo -- 선택된 직원의 정보를 설정하는 함수
UIRecipeResult:SetSkillInfo -- 스킬 정보를 설정하고 표시하는 함수
UIRecipeResult:UseSkill -- 직원의 스킬을 사용하는 함수
UIRecipeResult:SkipResultRender -- 결과 렌더링을 스킵하는 함수
UIRecipeResult:SetFinalScore -- 최종 점수를 설정하는 함수
UIRecipeResult:ReturnValueCapApplied -- 값에 상한선을 적용하여 반환하는 함수
UIRecipeResult:HandleButtonClickEvent -- 스킵 버튼 클릭 이벤트를 처리하는 핸들러
UITrendInfo:Init -- 트렌드 정보 UI 요소들을 초기화하는 함수
UITrendInfo:Refresh -- 트렌드 정보를 새로고침하는 함수
UITrendInfo:RefreshForRecipeList -- 레시피 리스트용 트렌드 정보를 새로고침하는 함수
UITrendInfoBar:Refresh -- 트렌드 정보 바를 새로고침하는 함수
UIVIPOrderNewSeasonPopup:Open -- 새 시즌 팝업을 열어서 시즌 정보를 표시
UIVIPOrderNewSeasonPopup:Init -- UI 컴포넌트들을 초기화하고 참조를 설정
UIVIPOrderNewSeasonPopup:Refresh -- 현재 시즌의 메인 태그와 기간 정보를 새로고침
UIVIPOrderNewSeasonPopup:Close -- 새 시즌 팝업을 닫고 관련 UI 상태를 복원
UIVIPOrderNewSeasonPopup:HandleButtonClickEvent -- 팝업 닫기 버튼 클릭 시 팝업을 닫는 핸들러
UIVIPOrderPanel:Open -- VIP 주문 패널을 열고 튜토리얼 및 상태를 업데이트
UIVIPOrderPanel:Refresh -- 패널의 시즌 정보와 주문 목록을 새로고침
UIVIPOrderPanel:RefreshOrderList -- 각 주문 슬롯의 데이터를 업데이트하고 애니메이션 적용
UIVIPOrderPanel:OnBeginPlay -- 게임 시작 시 VIP 주문 슬롯들을 생성하고 초기화
UIVIPOrderPanel:Close -- VIP 주문 패널을 닫고 슬롯들을 정리
UIVIPOrderPanel:RefreshCountBar -- 완료된 주문 수와 최대 주문 수를 표시하고 상태 업데이트
UIVIPOrderPanel:CheckOpenSeasonPopup -- 처음 UI 진입 시 새 시즌 팝업을 표시할지 확인
UIVIPOrderPanel:CheckOpenAfterCloseSeason -- 시즌 종료 후 UI 진입 상태를 확인하고 설정
UIVIPOrderPanel:EndWaitRefresh -- 대기 상태를 종료하고 슬롯들의 상태를 업데이트
UIVIPOrderPanel:StartWaitRefresh -- 대기 상태를 시작하고 슬롯들에 대기 상태를 알림
UIVIPOrderPanel:ClearAllTweenerAndTimer -- 모든 슬롯의 애니메이션과 타이머를 정리
UIVIPOrderPanel:HandleButtonClickEvent -- VIP 주문 패널 열기 버튼 클릭을 처리
UIVIPOrderPanel:HandleButtonClickEvent2 -- VIP 주문 패널 닫기 버튼 클릭을 처리
UIVIPOrderPanel:HandleButtonClickEvent3 -- VIP 주문 업그레이드 패널 열기 버튼 클릭을 처리
UIVIPOrderPanel:HandleButtonClickEvent4 -- VIP 주문 패널 다시 열기 버튼 클릭을 처리
UIVIPOrderPreview:Init -- VIP 주문 미리보기 UI 컴포넌트들을 초기화하고 이벤트 연결
UIVIPOrderPreview:Refresh -- 주문 목록을 새로고침하고 선택된 슬롯 정보를 업데이트
UIVIPOrderPreview:OpenOrderList -- 주문 목록을 열거나 이미 열려있으면 닫기
UIVIPOrderPreview:CloseOrderList -- 주문 목록을 닫기
UIVIPOrderPreview:RefreshOrderList -- 각 주문 슬롯의 데이터를 새로고침하고 선택 상태 표시
UIVIPOrderPreview:RefreshNowRequirements -- 현재 선택된 주문의 요구사항을 새로고침하고 조건 충족 여부 확인
UIVIPOrderPreview:OnPinOrder -- 특정 주문을 고정하고 미리보기 상태를 업데이트
UIVIPOrderPreviewSlot:Init -- 미리보기 슬롯의 UI 컴포넌트들을 초기화
UIVIPOrderPreviewSlot:Refresh -- 주문 인덱스와 고정 상태에 따라 슬롯을 새로고침
UIVIPOrderRecipeRequirement:Init -- 레시피 요구사항 UI 컴포넌트들을 초기화
UIVIPOrderRecipeRequirement:Refresh -- 요구사항 타입에 따라 적절한 UI를 표시하고 데이터 설정
UIVIPOrderScoreExtraReward:Open -- 추가 보상 팝업을 열고 보상 등급에 따른 애니메이션 시작
UIVIPOrderScoreExtraReward:StartRender -- 보상 팝업의 페이드 인 애니메이션과 점수 드롭 효과 시작
UIVIPOrderScoreExtraReward:EndRender -- 보상 팝업의 페이드 아웃 애니메이션과 정리 작업
UIVIPOrderScoreExtraReward:OnBeginPlay -- 게임 시작 시 팝업을 비활성화 상태로 초기화
UIVIPOrderSeasonInfo:OnBeginPlay -- 시즌 정보 UI의 초기화 상태와 보상 상태를 설정
UIVIPOrderSeasonInfo:Refresh -- 시즌 정보, 메인 태그, 보상 슬라이더를 새로고침
UIVIPOrderSeasonInfo:RefreshLeftDayText -- 시즌 남은 날짜 텍스트를 업데이트
UIVIPOrderSeasonInfo:RefreshRewardSlider -- 시즌 점수에 따른 보상 슬라이더와 보상 버튼 상태를 업데이트
UIVIPOrderSeasonInfo:OnClickRewardBtn -- 보상 버튼 클릭 시 보상 획득 또는 툴팁 표시 처리
UIVIPOrderSeasonInfo:Init -- 보상 버튼들과 툴팁을 생성하고 이벤트를 연결
UIVIPOrderSeasonInfo:RefreshRewardTooltip -- 보상 툴팁의 아이템과 수량을 보너스 적용하여 새로고침
UIVIPOrderSeasonInfo:TweenRewardSlider -- 시즌 점수 증가에 따른 보상 슬라이더 애니메이션 실행
UIVIPOrderSeasonInfo:SetRewardEntity -- 보상 엔티티의 상태에 따라 버튼 활성화와 이미지를 설정
UIVIPOrderSeasonInfo:SetNotToRefreshSlider -- 슬라이더 새로고침 금지 상태를 설정
UIVIPOrderSeasonInfo:RefreshRewardInfoTooltip -- 보상 정보 툴팁의 컬렉션과 전략 보너스 정보를 새로고침
UIVIPOrderSlot:Init -- VIP 주문 슬롯의 모든 UI 컴포넌트를 초기화하고 이벤트 연결
UIVIPOrderSlot:Refresh -- 슬롯 데이터에 따라 주문 타입별로 UI를 새로고침
UIVIPOrderSlot:RefreshComplete -- 완료된 주문 상태의 UI를 설정
UIVIPOrderSlot:RefreshRecipe -- 레시피 주문의 요구사항들을 UI에 표시
UIVIPOrderSlot:RefreshIngre -- 재료 주문의 정보와 보유 수량을 표시하고 충족 여부 확인
UIVIPOrderSlot:RefreshRerollBtn -- 리롤 버튼의 비용과 활성화 상태를 업데이트
UIVIPOrderSlot:RefreshWaiting -- 대기 상태 주문의 리셋 비용과 남은 날짜를 표시
UIVIPOrderSlot:RefreshReward -- 주문 완료 시 받을 보상 아이템들을 UI에 표시
UIVIPOrderSlot:MoveOut -- 슬롯이 사라지는 애니메이션을 실행하고 새 데이터로 교체 준비
UIVIPOrderSlot:MoveIn -- 새로운 주문 데이터로 슬롯이 나타나는 애니메이션을 실행
UIVIPOrderSlot:SetSlotData -- 슬롯 데이터를 설정하고 대기 상태에 따라 적절한 처리 수행
UIVIPOrderSlot:ClearEntities -- 슬롯 엔티티들의 시각적 상태를 초기화
UIVIPOrderSlot:IsSameData -- 두 슬롯 데이터가 같은 주문인지 UniqueId로 비교
UIVIPOrderSlot:OnChangedIsWaiting -- 대기 상태 변경 시 임시 저장된 데이터로 슬롯을 새로고침
UIVIPOrderSlot:RequestRefresh -- 슬롯 상태에 따라 적절한 새로고침 방식을 선택
UIVIPOrderSlot:PopAfterWait -- 대기 후 점수 팝업을 위해 임시 점수를 저장
UIVIPOrderSlot:ClearSlotMovement -- 진행 중인 모든 애니메이션과 타이머를 정리하고 상태 초기화
UIVIPOrderSlot:HandlePlayerArcaneSymbolChangedEvent -- 플레이어의 아케인 심볼 변경 시 슬롯 데이터를 새로고침
VIPOrderDataSetLogic:OnBeginPlay -- 게임 시작 시 VIP 주문 관련 데이터셋을 초기화
VIPOrderDataSetLogic:LoadDataSet -- CSV 파일에서 시즌 보상 데이터를 읽어와 테이블에 저장
VIPOrderDataSetLogic:ReturnIngreType -- 시즌 메인 태그를 기준으로 가중치를 적용한 재료 타입을 반환
VIPOrderDataSetLogic:ReturnRecipeOrderData -- 플레이어 상태에 맞는 레시피 주문 데이터를 생성하고 반환
VIPOrderDataSetLogic:ReturnIngreOrderData -- 플레이어 상태에 맞는 재료 주문 데이터를 생성하고 반환
VIPOrderDataSetLogic:IsRecipeCorrectForOrder -- 제출한 레시피가 VIP 주문의 모든 요구사항을 충족하는지 검증
VIPOrderDataSetLogic:ReturnSeasonEndElapsedByStartElapsed -- 시즌 시작 시점을 기준으로 해당 시즌의 종료 시점을 계산
VIPOrderDataSetLogic:RefreshSeasonInfoLeftDayText -- 현재 시간을 기준으로 시즌 종료까지 남은 날짜를 계산하고 UI 업데이트
VIPOrderDataSetLogic:ReturnResetOrderCost -- 남은 날짜에 비례하여 주문 리셋에 필요한 아케인 심볼 비용을 계산
VIPOrderDataSetLogic:RefreshRequirementSlotIcon -- 요구사항 타입에 따라 적절한 아이콘과 상태 표시를 설정
VIPOrderDataSetLogic:ReturnRequirementDatasTableForUI -- 슬롯 데이터에서 UI 표시용 요구사항 목록을 추출하여 반환
VIPOrderDataSetLogic:IsIngreRelatedToOrder -- 특정 재료가 해당 슬롯의 레시피 주문 요구사항에 포함되는지 확인
VIPOrderDataSetLogic:ReturnVIPOrderReward -- 주문 데이터와 플레이어 상태를 기반으로 보상 아이템과 수량을 계산
VIPOrderDataSetLogic:ReturnVIPOrderRerollCost -- 플레이어의 리롤 횟수에 따라 증가하는 리롤 비용을 계산
VIPOrderDataSetLogic:ReturnFixedStartMonthByStartElapsed -- 시작 시점을 기준으로 해당 시즌의 고정된 시작 월을 반환
VIPOrderRecipeRewardData:Load -- CSV 데이터에서 레시피 보상 정보를 로드하고 파싱
VIPOrderRecipeRewardData:ReturnRewardGradeByTasteGrade -- 맛 등급에 해당하는 보상 등급을 찾아서 반환
VIPOrderRequirementData:Load -- CSV 데이터에서 VIP 주문 요구사항 정보를 로드하고 파싱
VIPOrderRequirementData:ReturnRandomIngreGrade -- 사용 가능한 재료 등급 중에서 랜덤하게 하나를 선택하여 반환
VIPOrderResultRenderLogic:DropSeasonScores -- 시즌 점수를 시각적으로 드롭하는 애니메이션을 실행
VIPOrderResultRenderLogic:ClearScoreEntities -- 생성된 모든 점수 엔티티들을 제거하고 카운터 초기화
VIPOrderResultRenderLogic:OnBeginPlay -- 점수 렌더링 로직 초기화
VIPOrderResultRenderLogic:RequestStartPopAfterWaiting -- 대기 후 점수 팝업을 시작하도록 요청
VIPOrderResultRenderLogic:RequestStartExtraRewardAfterWaiting -- 대기 후 추가 보상을 시작하도록 요청
VIPOrderResultRenderLogic:RequestOpenExtraReward -- 저장된 추가 보상이 있으면 팝업을 열어서 표시
VIPOrderSeasonRewardData:Load -- 관리 레벨과 CSV 행 데이터를 기반으로 시즌 보상 데이터를 로드
CustomerAIScript:Create -- 고객 AI를 초기화하고 이동 스크립트를 설정하는 함수
CustomerAIScript:StateManager -- 고객의 상태를 관리하고 각 상태에 따른 행동을 처리하는 함수
CustomerAIScript:BEFOREENTER -- 고객이 매장 입장 전 대기 상태를 처리하는 함수
CustomerAIScript:ENTER -- 고객이 매장에 입장하여 대기 좌석으로 이동하는 상태를 처리하는 함수
CustomerAIScript:ORDER -- 고객이 주문을 대기하고 주문 UI를 생성하는 상태를 처리하는 함수
CustomerAIScript:CHECKOUT -- 고객이 결제를 완료하고 매장을 나가기 전 처리하는 상태 함수
CustomerAIScript:EXITTEMP -- 고객이 임시 출구 지점으로 이동하는 상태를 처리하는 함수
CustomerAIScript:EXIT -- 고객이 최종 출구로 이동하여 매장을 완전히 나가는 상태를 처리하는 함수
CustomerAIScript:DESTROY -- 고객 엔티티를 정리하고 제거하는 상태를 처리하는 함수
CustomerAIScript:SetOrder -- 고객이 주문을 완료했음을 설정하는 함수
CustomerAIScript:SetPurchase -- 고객이 결제를 완료했음을 설정하고 대기열에서 제거하는 함수
CustomerAIScript:Report -- 고객이 매장을 떠나는 이유를 분석하고 보고서를 생성하는 함수
CustomerAIScript:ResetEntity -- 고객 엔티티를 초기화하고 오브젝트 풀로 반환하는 함수
CustomerAIScript:OnBeginPlay -- 고객 엔티티가 생성될 때 버거 컴포넌트를 초기화하는 함수
CustomerAIScript:UpdateWaitSpotId -- 고객의 대기 좌석 위치 정보를 업데이트하는 함수
CustomerAIScript:ChangeStateToORDERByEmployeeDestroyed -- 직원이 파괴되었을 때 고객 상태를 주문 대기로 변경하는 함수
CustomerAIScript:HandleEmployeeMoveChangedEvent -- 직원 이동 상태 변경 이벤트를 처리하는 핸들러
CustomerAvatarData:Load -- CSV 데이터에서 고객 아바타 정보를 로드하고 리소스 ID를 수집하는 함수
CustomerAvatarService:OnBeginPlay -- 서비스 시작 시 고객 아바타 데이터셋을 로드하는 함수
CustomerAvatarService:LoadDataSet -- CSV에서 고객 아바타 데이터를 로드하여 메모리에 저장하는 함수
CustomerAvatarService:SetRandomCostume -- 현재 스테이지에 맞는 랜덤 고객 의상을 설정하는 함수
CustomerAvatarService:GetCostumerAvatarData -- 인덱스에 해당하는 고객 아바타 데이터를 반환하는 함수
CustomerAvatarService:SetRandomEmotion -- 고객에게 랜덤한 감정 표현을 설정하는 함수
CustomerAvatarService:ResetCustomerAvatarResources -- 현재 스테이지에 맞는 고객 아바타 리소스를 미리 로드하는 함수
CustomerAvatarService:GetIndex -- 현재 스테이지에 해당하는 아바타 인덱스 범위를 계산하는 함수
CustomerAvatarService:InsertRUIDToPreloadData -- 유효한 리소스 ID를 프리로드 목록에 추가하는 함수
CustomerManager:OnBeginPlay -- 서버에서 고객 매니저를 초기화하는 함수
CustomerManager:Init -- 클라이언트에서 고객 매니저를 초기화하고 고객 풀을 생성하는 함수
CustomerManager:SetCustomerSpawnDelay -- 고객 스폰 딜레이를 계산하고 설정하는 함수
CustomerManager:CreateCustomer -- 고객 엔티티를 풀에서 가져와서 생성하는 함수
CustomerManager:RefreshSpawnTable -- 고객 스폰 테이블을 새로고침하고 각 고객의 정보를 설정하는 함수
CustomerManager:SyncCustomerInfoTable -- 서버에서 전송된 고객 스폰 정보를 클라이언트에 동기화하는 함수
CustomerManager:SetRandomOrderTag -- 트렌드와 메뉴 상황에 따라 고객의 주문 태그를 결정하는 함수
CustomerManager:SetOrderRecipeId -- 타겟 태그에 맞는 레시피 ID를 선택하여 반환하는 함수
CustomerManager:CalcMyAttractive -- 가게의 총 매력도를 계산하는 함수
CustomerManager:ResetLeaveCustomerAttractive -- 떠난 고객 매력도 통계를 초기화하는 함수
CustomerManager:CalcAttractiveRecipe -- 설정된 레시피들의 총 매력도를 계산하는 함수
CustomerManager:CalcAttractiveExpension -- 매장 확장 단계에 따른 매력도를 계산하는 함수
CustomerManager:CalcAttractiveInterior -- 매장 인테리어 레벨에 따른 매력도를 계산하는 함수
CustomerManager:CalacAttractiveDeco -- 매장 장식에 따른 매력도를 계산하는 함수
CustomerManager:CalcRecipeAttractive -- 특정 레시피의 매력도를 계산하는 함수
CustomerManager:RequestPayPurchase -- 고객의 결제 요청을 처리하고 매출을 계산하는 함수
CustomerManager:RequestAddStorageTip -- 고객이 주는 팁을 저장소에 추가하거나 드롭으로 생성하는 함수
CustomerManager:RequestAddDropTip -- 드롭된 팁을 플레이어 인벤토리에 추가하는 함수
CustomerManager:CalcAppliacneBonus -- 주방 기기 레벨에 따른 보너스를 계산하는 함수
CustomerManager:CalcRecipeComboBonus -- 레시피 콤보 보너스를 계산하는 함수
CustomerManager:HasWaitingCustomer -- 대기 중인 고객이 있는지 확인하는 함수
CustomerManager:AddWaitCustomer -- 대기열에 고객을 추가하는 함수
CustomerManager:RemoveWaitCustomer -- 대기열에서 고객을 제거하는 함수
CustomerManager:ExitWaitCustomer -- 대기 중인 고객들을 상황에 따라 퇴장시키는 함수
CustomerManager:ReturnWaitSeat -- 사용 가능한 대기 좌석을 찾아 반환하는 함수
CustomerManager:MoveAllCustomerForward -- 모든 대기 고객들을 앞으로 이동시키는 함수
CustomerManager:MoveCustomerForwardByCounterID -- 특정 카운터의 대기 고객들을 앞으로 이동시키는 함수
CustomerManager:UpdateAllWaitCustomerPos -- 확장 레벨 변경 시 모든 대기 고객의 위치를 업데이트하는 함수
CustomerManager:OnMapLeave -- 맵을 떠날 때 고객 매니저를 정리하는 함수
CustomerManager:InitCustomerSpawner -- 고객 스폰너를 초기화하는 함수
CustomerManager:SpawnCustomer -- 실제로 고객을 스폰하는 함수
CustomerManager:OnUpdate -- 매 프레임 고객 스폰 타이밍을 처리하는 함수
CustomerManager:UpdateCustomerSpawnPos -- 확장 레벨에 따라 고객 스폰 위치를 업데이트하는 함수
CustomerManager:SetTurialTagByOrderByNowStage -- 현재 스테이지에 따라 튜토리얼 태그 순서를 설정하는 함수
CustomerManager:CustomerOrderChange -- 고객의 주문 내용을 변경하는 함수
CustomerManager:HandlePlayerReputationChangedEvent -- 플레이어 평판 변경 이벤트를 처리하는 핸들러
CustomerService:OnBeginPlay -- 고객 서비스 시작 시 초기화하는 함수
CustomerService:LoadDataOnServer -- 서버에서 고객 그룹 비율 설정 데이터를 로드하는 함수
CustomerService:SpawnDropItem -- 고객이 주는 팁을 드롭 아이템으로 생성하는 함수
CustomerService:RequestGainDropTip -- 플레이어가 드롭된 팁을 획득하는 요청을 처리하는 함수
CustomerService:SetEmotion -- 고객의 감정 상태를 설정하는 함수
CustomerService:SetBodyAction -- 고객의 몸짓 애니메이션을 설정하는 함수
CustomerService:EnableAngryMark -- 고객의 화난 표시를 활성화/비활성화하는 함수
CustomerUIService:CreateOrderUI -- 고객의 주문 UI를 생성하는 함수
CustomerUIService:OrderUIOff -- 고객의 주문 UI를 비활성화하는 함수
CustomerUIService:CreatePreferUI -- 고객의 선호 태그 UI를 생성하는 함수
CustomerUIService:PreferUIOfff -- 고객의 선호 UI를 비활성화하는 함수
CustomerUIService:UpdatePeedbackUI -- 고객의 피드백 UI를 업데이트하는 함수
CustomerUIService:CreatePayProductionUI -- 고객 결제 시 돈 표시 UI를 생성하는 함수
CustomerUIService:CreateTipProductionUI -- 팁 획득 시 표시 UI를 생성하는 함수
PeedbackRUID:OnBeginPlay -- 피드백 UI에 사용할 리소스 ID들을 초기화하는 함수
AutoTrainingSlotData:FindSlotNumFromId -- ID로부터 슬롯 번호를 찾는 함수
AutoTrainingSlotData:FindSlotNumFromEntity -- 엔티티로부터 슬롯 번호를 찾는 함수
AutoTrainingSlotData:ConvertToTable -- 슬롯 데이터를 테이블 형태로 변환하는 함수
AutoTrainingSlotData:SetFromTable -- 테이블 데이터로부터 슬롯 정보를 설정하는 함수
AutoTrainingSlotData:DefaultDataTable -- 기본 데이터 테이블을 생성하는 함수
AutoTrainingTruckSlot:SetLock -- 슬롯을 잠금 상태로 설정하는 함수
AutoTrainingTruckSlot:SetUnlock -- 슬롯을 잠금 해제 상태로 설정하는 함수
AutoTrainingTruckSlot:SwitchLockPanel -- 잠금 상태에 따라 UI 패널을 전환하는 함수
AutoTrainingTruckSlot:ChangeUIOnState -- 상태에 따라 UI를 변경하는 함수
AutoTrainingTruckSlot:UpdateTimeText -- 시간 텍스트를 업데이트하는 함수
AutoTrainingTruckSlot:EnableOkButtonDim -- OK 버튼의 딤 상태를 설정하는 함수
AutoTrainingTruckSlot:SetOkBtnLunchBoxNum -- OK 버튼에 도시락 개수를 설정하는 함수
AutoTrainingTruckSlot:UpdateTimeText_ParkingArea -- 주차장 영역의 시간 텍스트를 업데이트하는 함수
AutoTrainingTruckSlot:ChangeUIOnState_ParkingArea -- 주차장 영역의 UI 상태를 변경하는 함수
HintItemData:Load -- 데이터 테이블에서 힌트 아이템 정보를 로드하는 함수
HintItemDataSetLogic:OnBeginPlay -- 게임 시작 시 데이터셋을 로드하는 함수
HintItemDataSetLogic:LoadDataSet -- 힌트 아이템 데이터셋을 로드하는 함수
HintItemDataSetLogic:GetHintItemData -- ID로 힌트 아이템 데이터를 가져오는 함수
HintItemDataSetLogic:ReturnItemListByColor -- 특정 색상의 아이템 목록을 반환하는 함수
HintItemDataSetLogic:ReturnItemIdByCategoryAndColor -- 카테고리와 색상으로 아이템 ID를 반환하는 함수
HintItemDataSetLogic:ReturnRowByColor -- 특정 색상의 데이터 행을 반환하는 함수
HintItemDataSetLogic:ReturnRandomPlaceItems -- 랜덤 장소 아이템들을 반환하는 함수
HintItemDataSetLogic:ReturnIconRuidById -- ID로 아이콘 RUID를 반환하는 함수
HintItemDataSetLogic:ReturnItemName -- ID로 아이템 이름을 반환하는 함수
PaperHintComponent:SetPaperHint -- 종이 힌트의 타입을 설정하는 함수
PaperHintComponent:HandleButtonClickEvent -- 버튼 클릭 시 종이 힌트 아이콘을 여는 이벤트 핸들러
PlayerAutoTrainingManager:SaveToDB -- 자동 훈련 데이터를 데이터베이스에 저장하는 함수
PlayerAutoTrainingManager:OnLoadedDataFromDB -- 데이터베이스에서 로드된 데이터를 처리하는 함수
PlayerAutoTrainingManager:InitComponent -- 컴포넌트를 초기화하는 함수
PlayerAutoTrainingManager:ConvertToTable -- 구조체 데이터를 테이블로 변환하는 함수
PlayerAutoTrainingManager:ConvertTableToInfo -- 테이블 데이터를 슬롯 정보로 변환하는 함수
PlayerAutoTrainingManager:UpdateUnlockCondition -- 슬롯 잠금 해제 조건을 업데이트하는 함수
PlayerAutoTrainingManager:SetLockSlots -- 슬롯의 잠금 상태를 설정하는 함수
PlayerAutoTrainingManager:SetLockSlotsUI -- 클라이언트에서 슬롯 잠금 UI를 설정하는 함수
PlayerAutoTrainingManager:TruckSlotOkButton -- 트럭 슬롯의 OK 버튼 클릭 시 처리하는 함수
PlayerAutoTrainingManager:OnClickRewardAllButton -- 모든 보상 버튼 클릭 시 처리하는 함수
PlayerAutoTrainingManager:TrainingShortCut -- 훈련 단축키 처리하는 함수
PlayerAutoTrainingManager:StartTrainingShortCut -- 훈련 단축 시작하는 함수
PlayerAutoTrainingManager:FailStartTrainingShortCut -- 훈련 단축 시작 실패 시 처리하는 함수
PlayerAutoTrainingManager:CheckGoTraining -- 훈련 시작 조건을 확인하는 함수
PlayerAutoTrainingManager:StartTraining -- 훈련을 시작하는 함수
PlayerAutoTrainingManager:FailStartTraining -- 훈련 시작 실패 시 처리하는 함수
PlayerAutoTrainingManager:OpenResultPopup -- 결과 팝업을 여는 함수
PlayerAutoTrainingManager:CalcResult -- 훈련 결과를 계산하는 함수
PlayerAutoTrainingManager:DisplayResultSlot -- 결과 슬롯을 표시하는 함수
PlayerAutoTrainingManager:GiveReward -- 플레이어에게 보상을 지급하는 함수
PlayerAutoTrainingManager:OnRewardPopupOkButton -- 보상 팝업의 OK 버튼 클릭 시 처리하는 함수
PlayerAutoTrainingManager:ChangeTruckState -- 트럭의 상태를 변경하는 함수
PlayerAutoTrainingManager:ChangeTruckStateClient -- 클라이언트에서 트럭 상태를 변경하는 함수
PlayerAutoTrainingManager:StartTimer -- 타이머를 시작하는 함수
PlayerAutoTrainingManager:UpdateTimer -- 타이머를 업데이트하는 함수
PlayerAutoTrainingManager:InitTruckSlot -- 트럭 슬롯을 초기화하는 함수
PlayerAutoTrainingManager:UpdateTimerUI -- 타이머 UI를 업데이트하는 함수
PlayerAutoTrainingManager:UpdateHudTimerUI -- HUD 타이머 UI를 업데이트하는 함수
PlayerAutoTrainingManager:UpdateParkingAreaInfo -- 주차장 영역 정보를 업데이트하는 함수
PlayerAutoTrainingManager:SetChuhuInTruck -- 츄츄를 트럭에 설정하는 함수
PlayerAutoTrainingManager:SyncData -- 데이터를 동기화하는 함수
PlayerAutoTrainingManager:ChangeStateChuchuListSlot -- 츄츄 리스트 슬롯의 상태를 변경하는 함수
PlayerAutoTrainingManager:UpdateChuchuSlot -- 츄츄 슬롯을 업데이트하는 함수
PlayerAutoTrainingManager:SetEmpScroll -- 직원 스크롤을 설정하는 함수
PlayerAutoTrainingManager:UpdateTrainingSelectedList -- 훈련 선택 목록을 업데이트하는 함수
PlayerAutoTrainingManager:UpdateLunchBoxTruckSlotOkButtons -- 도시락 트럭 슬롯 OK 버튼을 업데이트하는 함수
PlayerAutoTrainingManager:OnOpenUI -- UI가 열릴 때 처리하는 함수
PlayerAutoTrainingManager:CheckCanRewardForRedDot -- 빨간 점 표시를 위한 보상 가능 여부를 확인하는 함수
PlayerAutoTrainingManager:CanRewardAutoTraining -- 자동 훈련 보상 가능 상태를 설정하는 함수
PlayerAutoTrainingManager:OnTransferAutoTrainingChuchu -- 자동 훈련 츄츄를 이송할 때 처리하는 함수
PlayerAutoTrainingManager:CheckChuchuAutoTraining -- 츄츄의 자동 훈련 상태를 확인하는 함수
PlayerAutoTrainingManager:OnClickScooterArea -- 스쿠터 영역 클릭 시 처리하는 함수
PlayerAutoTrainingManager:AutoTrainingToastMsg -- 자동 훈련 토스트 메시지를 표시하는 함수
PlayerTrainingManager:LoadConfigData -- 버거 가격 보너스 설정 데이터를 로드하는 함수
PlayerTrainingManager:OnClickTrainingButton -- 훈련 시작 버튼 클릭 시 처리하는 함수
PlayerTrainingManager:RequestEnterTraining -- 훈련 입장 요청을 처리하는 함수
PlayerTrainingManager:FadeInTraining -- 훈련 시작 시 페이드인 효과를 처리하는 함수
PlayerTrainingManager:OnStartTraining -- 훈련을 시작할 때 초기화하는 함수
PlayerTrainingManager:ResetValues -- 훈련 관련 값들을 초기화하는 함수
PlayerTrainingManager:ResetValuesClient -- 클라이언트에서 훈련 관련 값들을 초기화하는 함수
PlayerTrainingManager:InitUI -- 훈련 UI를 초기화하는 함수
PlayerTrainingManager:ChangeBurgerPrice -- 버거 가격을 변경하는 함수
PlayerTrainingManager:CreateCharModels -- 훈련에 참여할 캐릭터 모델들을 생성하는 함수
PlayerTrainingManager:CreateHints_Fix -- 고정된 형태로 힌트들을 생성하는 함수
PlayerTrainingManager:CreateHints -- 랜덤하게 힌트들을 생성하는 함수
PlayerTrainingManager:CreateHotPlace -- 핫플레이스를 생성하고 고객 수를 설정하는 함수
PlayerTrainingManager:CreateIngreBoxList -- 재료 상자 목록을 생성하는 함수
PlayerTrainingManager:ChoiceHint -- 특정 스팟에서 힌트를 선택하는 함수
PlayerTrainingManager:OpenHintPopup -- 힌트 팝업을 여는 함수
PlayerTrainingManager:SelectLunchBoxButton -- 도시락 버튼을 선택하는 함수
PlayerTrainingManager:SwitchSelectedTCharToNext -- 선택된 캐릭터를 다음 캐릭터로 전환하는 함수
PlayerTrainingManager:SwitchNextChuchu -- 다음 캐릭터로 전환하는 함수
PlayerTrainingManager:SendChuChu -- 캐릭터를 특정 스팟에 보내는 함수
PlayerTrainingManager:FindIngredientBox -- 재료 상자를 찾았을 때 처리하는 함수
PlayerTrainingManager:NextTurn -- 다음 턴으로 넘어가는 함수
PlayerTrainingManager:OnSelectLastSpot -- 마지막 스팟을 선택할 때 처리하는 함수
PlayerTrainingManager:OnGoToPlaceButton -- 장소로 가기 버튼을 클릭할 때 처리하는 함수
PlayerTrainingManager:SwitchPanel -- UI 패널을 상태에 따라 전환하는 함수
PlayerTrainingManager:ClearHintScroll -- 힌트 스크롤을 지우는 함수
PlayerTrainingManager:GiveReward -- 훈련 완료 후 보상을 지급하는 함수
PlayerTrainingManager:SetResultUI -- 훈련 결과 UI를 설정하는 함수
PlayerTrainingManager:OpenResultUI -- 훈련 결과 UI를 여는 함수
PlayerTrainingManager:OnEndTraining -- 훈련이 끝났을 때 처리하는 함수
PlayerTrainingManager:LogEndTrainingServer -- 훈련 종료 로그를 서버에 기록하는 함수
PlayerTrainingManager:SetPlaceBg -- 선택된 장소에 따라 배경을 설정하는 함수
PlayerTrainingManager:ChangeBurgerPriceUI -- 버거 가격 UI를 변경하는 함수
PlayerTrainingManager:SetSelectedChuchuIdList -- 선택된 캐릭터 ID 목록을 설정하는 함수
PlayerTrainingManager:CheatStateChange -- 치트로 상태를 변경하는 함수
PlayerTrainingManager:ModifyLunchBoxNum -- 도시락 개수를 수정하는 함수
PlayerTrainingManager:RouletteStart -- 룰렛을 시작하는 함수
PlayerTrainingManager:OpenMap -- 지도를 열거나 닫는 함수
PlayerTrainingManager:AddPaperHintInScroll -- 스크롤에 종이 힌트를 추가하는 함수
PlayerTrainingManager:OnClickPaperHintIcon -- 종이 힌트 아이콘을 클릭할 때 처리하는 함수
PlayerTrainingManager:AddRewardBox -- 보상 상자를 추가하는 함수
PlayerTrainingManager:GetSpotNameFromKey -- 스팟 키로부터 스팟 이름을 가져오는 함수
PlayerTrainingManager:GetSpotFoodholdFromKey -- 스팟 키로부터 지형 RUID를 가져오는 함수
PlayerTrainingManager:GetSpotBgFromKey -- 스팟 키로부터 배경 RUID를 가져오는 함수
PlayerTrainingManager:SetProgressBar -- 진행 바를 설정하는 함수
PlayerTrainingManager:CheckTodoList -- 할 일 목록을 체크하는 함수
PlayerTrainingManager:ShowLastSpot -- 마지막 스팟을 보여주는 함수
PlayerTrainingManager:ShowLastSpot_HotPlace -- 핫플레이스 마지막 스팟을 보여주는 함수
PlayerTrainingManager:EnterTrainingToast -- 훈련 입장 토스트 메시지를 보여주는 함수
PlayerTrainingManager:SetHotPlaceName -- 핫플레이스 이름을 설정하는 함수
PlayerTrainingManager:ChangeMonth_HalfYear -- 월에 따라 반기 정보를 변경하는 함수
PlayerTrainingManager:AddExpReward -- 경험치 보상을 추가하는 함수
PlayerTrainingManager:OnLastSpotSelect -- 마지막 스팟을 선택할 때 처리하는 함수
PlayerTrainingManager:OnClickHintSkipButton -- 힌트 건너뛰기 버튼을 클릭할 때 처리하는 함수
PlayerTrainingManager:UpdateTrainingTicket -- 훈련 티켓 UI를 업데이트하는 함수
PlayerTrainingManager:OnClickTruckArea -- 트럭 영역을 클릭할 때 처리하는 함수
SpotComponent:OnSelectLastSpot -- 마지막 스팟을 선택할 때 처리하는 함수
SpotComponent:OnBeginPlay -- 게임 시작 시 스팟 초기화하는 함수
SpotComponent:ClearSpotHintScroll -- 스팟 힌트 스크롤을 초기화하는 함수
SpotComponent:AddHintIcon -- 힌트 아이콘을 추가하는 함수
SpotComponent:ClearEnteredTChar -- 입장한 캐릭터 정보를 초기화하는 함수
SpotComponent:OnClickHintIcon -- 힌트 아이콘 클릭 시 처리하는 함수
SpotComponent:GoLastSpot -- 마지막 스팟으로 이동할 때 처리하는 함수
SpotComponent:BounceSpot -- 스팟을 바운스 효과로 표시하는 함수
SpotComponent:ChangeMaterial -- 엔티티의 머티리얼을 변경하는 함수
SpotComponent:BigBounceSpot -- 스팟을 큰 바운스 효과로 표시하는 함수
SpotComponent:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
TrainingChar:OnBeginPlay -- 게임 시작 시 캐릭터를 초기화하는 함수
TrainingChar:OnEnterSpot -- 스팟에 입장할 때 처리하는 함수
TrainingChar:Emotion -- 캐릭터의 감정 표현을 설정하는 함수
TrainingChar:FindHint -- 힌트를 찾는 처리를 하는 함수
TrainingChar:FindPaperHint -- 종이 힌트를 찾는 처리를 하는 함수
TrainingChar:GotoOriginPos -- 원래 위치로 이동하는 함수
TrainingChar:Init -- 캐릭터를 초기화하는 함수
TrainingChar:SetCharId -- 캐릭터 ID를 설정하는 함수
TrainingCustomerComponent:OnInitialize -- 컴포넌트를 초기화하는 함수
TrainingCustomerComponent:StartWalking -- 고객이 걷기 시작하는 함수
TrainingCustomerComponent:Set -- 핫플레이스 여부에 따라 고객 설정을 변경하는 함수
TrainingExpRewardData:SetData -- 데이터 행에서 훈련 경험치 보상 데이터를 설정하는 함수
TrainingRewardLogic:OnBeginPlay -- 게임 시작 시 훈련 보상 데이터를 설정하는 함수
TrainingRewardLogic:SetData -- 훈련 경험치 보상 데이터를 로드하고 설정하는 함수
TrainingRewardLogic:GetData -- 스테이지 ID와 경영 레벨로 훈련 경험치 보상 데이터를 가져오는 함수
UITraining:OnClickExitButton -- 나가기 버튼을 클릭할 때 처리하는 함수
UITraining:OnClickGiveupButton -- 포기 버튼을 클릭할 때 처리하는 함수
UITraining:SetGuidePopup -- 가이드 팝업을 설정하는 함수
UITraining:EnableGuidePopup -- 가이드 팝업을 활성화/비활성화하는 함수
UITraining:ChuchuChat -- 상태에 따라 캐릭터 채팅 메시지를 설정하는 함수
UITraining:UpdateTitleText -- 상태에 따라 제목 텍스트를 업데이트하는 함수
UITraining:OpenCloverInfoToolTip -- 클로버 정보 툴팁을 여는 함수
UITraining:SetCloverInfo -- 클로버 정보를 설정하는 함수
UITraining:DestroyCloverInfoToolTip -- 클로버 정보 툴팁을 제거하는 함수
UITraining:HandleButtonClickEvent5 -- 지도 시작 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent6 -- 결과 UI 열기 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent7 -- 나가기 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent13 -- 힌트 팝업 닫기 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent15 -- 힌트 팝업 닫기 버튼 클릭 이벤트 핸들러 2
UITraining:HandleButtonClickEvent11 -- 포기 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent9 -- 버거 판매 시작 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent -- 지도 열기 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent10 -- 룰렛 시작 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent12 -- 지도 닫기 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent16 -- 가이드 팝업 닫기 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent17 -- 힌트 건너뛰기 버튼 클릭 이벤트 핸들러
UITraining:HandleButtonClickEvent18 -- 클로버 정보 버튼 클릭 이벤트 핸들러
UITrainingAuto:OnBeginPlay -- 게임 시작 시 자동 훈련 UI를 초기화하는 함수
UITrainingAuto:InitUI -- 자동 훈련 UI를 초기화하는 함수
UITrainingAuto:OpenUI -- 자동 훈련 UI를 여는 함수
UITrainingAuto:CloseUI -- 자동 훈련 UI를 닫는 함수
UITrainingAuto:OnClickRewardAll -- 모든 보상 버튼 클릭 시 처리하는 함수
UITrainingAuto:SetLockSlots -- 슬롯의 잠금 상태를 설정하는 함수
UITrainingAuto:OnClickOkButton -- OK 버튼 클릭 시 처리하는 함수
UITrainingAuto:OnResultOkButton -- 결과 팝업 OK 버튼 클릭 시 처리하는 함수
UITrainingAuto:CloseResultPopup -- 결과 팝업을 닫는 함수
UITrainingAuto:OpenResultPopup -- 결과 팝업을 여는 함수
UITrainingAuto:DisplayEmployeeScroll -- 직원 스크롤을 표시하는 함수
UITrainingAuto:RefreshDetail -- 직원 상세 정보를 새로고침하는 함수
UITrainingAuto:OnClickSelectButton -- 선택 버튼 클릭 시 처리하는 함수
UITrainingAuto:AddSelectedScroll -- 선택된 직원을 스크롤에 추가하는 함수
UITrainingAuto:OpenChuchuListPopup -- 캐릭터 목록 팝업을 여는 함수
UITrainingAuto:CloseChuchuListPopup -- 캐릭터 목록 팝업을 닫는 함수
UITrainingAuto:ChangeStateChuchuListSlot -- 캐릭터 목록 슬롯의 상태를 변경하는 함수
UITrainingAuto:EmptySelectedSlot -- 선택된 슬롯을 비우는 함수
UITrainingAuto:SetTruckSlot -- 트럭 슬롯을 설정하는 함수
UITrainingAuto:UpdateTruckChuchuSlot -- 트럭 캐릭터 슬롯을 업데이트하는 함수
UITrainingAuto:UpdateHudSlot -- HUD 슬롯을 업데이트하는 함수
UITrainingAuto:EmptyHudSlot -- HUD 슬롯을 비우는 함수
UITrainingAuto:LockHudSlot -- HUD 슬롯을 잠그는 함수
UITrainingAuto:LockParkingAreaEntity -- 주차장 영역 엔티티를 잠그는 함수
UITrainingAuto:UpdateTruckSlotOkButtonDim -- 트럭 슬롯 OK 버튼 딩 상태를 업데이트하는 함수
UITrainingAuto:UpdateUpgradeInfo -- 업그레이드 정보를 업데이트하는 함수
UITrainingAuto:OnClickUpgradeBtn -- 업그레이드 버튼 클릭 시 처리하는 함수
UITrainingAuto:EnableDimRewardAllBtn -- 모든 보상 버튼의 딩 상태를 설정하는 함수
UITrainingAuto:OnClickScooterArea -- 스쿠터 영역 클릭 시 처리하는 함수
UITrainingAuto:OpenCloverInfoToolTip -- 클로버 정보 툴팁을 여는 함수
UITrainingAuto:SetCloverInfoToolTip -- 클로버 정보 툴팁을 설정하는 함수
UITrainingAuto:DestroyCloverInfoToolTip -- 클로버 정보 툴팁을 제거하는 함수
UITrainingAuto:RegisterRecycleScrollLayoutCallback -- 리사이클 스크롤 콜백을 등록하는 함수
UITrainingAuto:RecycleScrollOnUpdateByIndex -- 인덱스로 리사이클 스크롤을 업데이트하는 함수
UITrainingAuto:CalcEmpIdFromIndex -- 인덱스로부터 직원 ID를 계산하는 함수
UITrainingAuto:ReturnEntityFromEmpId -- 직원 ID로부터 엔티티를 반환하는 함수
UITrainingAuto:HandleButtonClickEvent -- HUD 슬롯 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent2 -- UI 닫기 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent3 -- 1번 슬롯 OK 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent4 -- 2번 슬롯 OK 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent5 -- 3번 슬롯 OK 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent6 -- 결과 OK 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent7 -- 결과 팝업 닫기 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent8 -- 모든 보상 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent9 -- 직원 선택 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent10 -- 캐릭터 목록 닫기 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent11 -- 직원 업그레이드 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent12 -- 상점 열기 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent13 -- 1번 업그레이드 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent14 -- 2번 업그레이드 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent15 -- 3번 업그레이드 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent16 -- 캐릭터 목록 팝업 닫기 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent17 -- 상점 열기 버튼 클릭 이벤트 핸들러 2
UITrainingAuto:HandleButtonClickEvent19 -- 1번 클로버 정보 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent20 -- 2번 클로버 정보 버튼 클릭 이벤트 핸들러
UITrainingAuto:HandleButtonClickEvent21 -- 3번 클로버 정보 버튼 클릭 이벤트 핸들러
UITrainingSetting:OnBeginPlay -- 게임 시작 시 훈련 설정 UI를 초기화하는 함수
UITrainingSetting:OpenTrainingSettingUI -- 훈련 설정 UI를 여는 함수
UITrainingSetting:OnClickStartButton -- 시작 버튼 클릭 시 처리하는 함수
UITrainingSetting:CloseTrainingSettingUI -- 훈련 설정 UI를 닫는 함수
UITrainingSetting:RefreshDetail -- 직원 상세 정보를 새로고침하는 함수
UITrainingSetting:DisplayEmployeeScroll -- 직원 스크롤을 표시하는 함수
UITrainingSetting:AddSelectedScroll -- 선택된 직원을 스크롤에 추가하는 함수
UITrainingSetting:OnClickSelectButton -- 선택 버튼 클릭 시 처리하는 함수
UITrainingSetting:OnClickSelectedSlot -- 선택된 슬롯 클릭 시 처리하는 함수
UITrainingSetting:EmptySelectedSlot -- 선택된 슬롯을 비우는 함수
UITrainingSetting:GetSelectedChuchuNum -- 선택된 캐릭터 수를 반환하는 함수
UITrainingSetting:GetSelectedChuchuList -- 선택된 캐릭터 목록을 반환하는 함수
UITrainingSetting:UpdateSelectedScroll -- 선택된 스크롤을 업데이트하는 함수
UITrainingSetting:UpdateSelectedList -- 선택된 목록을 업데이트하는 함수
UITrainingSetting:UpdateStartButtonDim -- 시작 버튼의 딩 상태를 업데이트하는 함수
UITrainingSetting:UpdateTrainingTicketUI -- 훈련 티켓 UI를 업데이트하는 함수
UITrainingSetting:SetSelectedSlot -- 선택된 슬롯을 설정하는 함수
UITrainingSetting:OnClickUpgradeBtn -- 업그레이드 버튼 클릭 시 처리하는 함수
UITrainingSetting:UpdateUpgradeInfo -- 업그레이드 정보를 업데이트하는 함수
UITrainingSetting:UpdateParkingAreaInfo -- 주차장 영역 정보를 업데이트하는 함수
UITrainingSetting:OnClickTruckArea -- 트럭 영역 클릭 시 처리하는 함수
UITrainingSetting:RegisterRecycleScrollLayoutCallback -- 리사이클 스크롤 콜백을 등록하는 함수
UITrainingSetting:RecycleScrollOnUpdateByIndex -- 인덱스로 리사이클 스크롤을 업데이트하는 함수
UITrainingSetting:CalcEmpIdFromIndex -- 인덱스로부터 직원 ID를 계산하는 함수
UITrainingSetting:ReturnEntityByEmpId -- 직원 ID로부터 엔티티를 반환하는 함수
UITrainingSetting:RecycleScrollOnUpdateByEmpId -- 직원 ID로 리사이클 스크롤을 업데이트하는 함수
UITrainingSetting:HandleButtonClickEvent -- 훈련 설정 UI 열기 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent2 -- OK 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent3 -- 닫기 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent4 -- 선택 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent5 -- 직원 업그레이드 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent6 -- 상점 열기 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent7 -- 1번 업그레이드 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent8 -- 2번 업그레이드 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent9 -- 3번 업그레이드 버튼 클릭 이벤트 핸들러
UITrainingSetting:HandleButtonClickEvent10 -- 상점 열기 버튼 클릭 이벤트 핸들러 2
UITrainingSetting:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 이벤트를 처리하는 핸들러
BurgerComponent:OnBurgerEntity -- 버거 엔티티를 활성화하고 스프라이트와 크기를 설정하는 함수
BurgerComponent:OnBeginPlay -- 컴포넌트 초기화 시 SpriteRendererComponent 참조를 설정하는 함수
BurgerComponent:OffBurgerEntity -- 버거 엔티티를 비활성화하고 요리 중인 버거 수를 감소시키는 함수
BurgerComponent:SubstractBurgerEntity -- 버거 개수를 차감하고 스프라이트 크기를 업데이트하는 함수
BurgerComponent:AddBurgerEntity -- 버거 개수를 증가시키고 스프라이트 크기를 업데이트하는 함수
MenuManager:Init -- 메뉴 매니저의 모든 데이터를 초기화하는 함수
MenuManager:OnMapEnter -- 로비 맵 진입 시 메뉴 매니저를 초기화하는 함수
MenuManager:OnMapLeave -- 로비 맵 이탈 시 메뉴 매니저를 초기화하는 함수
MenuManager:ReturnSlotIdxByUniqueID -- 고유 ID로 레시피 슬롯 인덱스를 찾아 반환하는 함수
MenuManager:ReturnRecipeUniqueID -- 레시피 ID로 고유 ID를 찾아 반환하는 함수
MenuManager:ReturnRecipeDataByUniqueID -- 고유 ID로 레시피 데이터를 찾아 반환하는 함수
MenuManager:SetMenu -- 메뉴 설정을 업데이트하고 변경사항이 있으면 처리하는 함수
MenuManager:HasChangedMenuSlot -- 메뉴 슬롯 위치가 변경되었는지 확인하는 함수
MenuManager:HasChangedMenuRecipe -- 메뉴 레시피가 변경되었는지 확인하는 함수
MenuManager:HasDiplayBurger -- 특정 슬롯에 표시할 버거가 있는지 확인하는 함수
MenuManager:ModifyDisplayBurger -- 표시 버거 수량을 수정하고 UI를 업데이트하는 함수
MenuManager:RefreshDisplayBurger -- 표시 버거 데이터를 새로고침하고 메뉴 변경사항을 반영하는 함수
MenuManager:AddSaleBurgerCount -- 판매된 버거 수량을 누적하여 기록하는 함수
MenuManager:ReturnSalesBurgerByRecipeID -- 레시피 ID로 판매된 버거 수량을 조회하는 함수
MenuManager:AllClearSalesBurger -- 모든 판매 버거 기록을 초기화하는 함수
MenuManager:ClearSaleBurgerByRecipeID -- 특정 레시피의 판매 기록을 삭제하는 함수
MenuManager:OnSyncProperty -- 동기화 프로퍼티 변경 시 UI를 업데이트하는 함수
MenuManager:GetDisplayedBurgerCount -- 특정 슬롯의 표시된 버거 개수를 반환하는 함수
MenuManager:GetDisplayedBurgerCountByUniqueId -- 고유 ID로 모든 슬롯의 표시된 버거 총 개수를 반환하는 함수
MenuManager:ClearLastRecipes -- 이전 레시피 설정 기록을 초기화하는 함수
MenuManager:AddCookingBurgers -- 요리 중인 버거 개수를 추가하는 함수
MenuManager:SubCookingBurgers -- 요리 중인 버거 개수를 차감하는 함수
MenuManager:GetCookingBurgers -- 요리 중인 버거 개수를 조회하는 함수
MenuManager:ResetCookingBurgers -- 요리 중인 버거 개수를 초기화하는 함수
MenuService:BurgerInit -- 버거 엔티티의 스프라이트와 렌더링 순서를 초기화하는 함수
MenuService:CreateBurgerEntity -- 버거 엔티티를 생성하거나 풀에서 재사용하여 반환하는 함수
MenuService:ResetBurgerEntity -- 버거 엔티티를 초기화하고 풀로 반환하는 함수
MenuService:ResetChildBurgerEntities -- 부모 엔티티의 모든 자식 버거 엔티티를 초기화하는 함수
MenuService:UpdateBurgerStackPos -- 직원이 들고 있는 버거들의 스택 위치를 업데이트하는 함수
MenuService:ChangeMenuRecipe -- 메뉴 레시피 변경 시 고객과 직원 상태를 처리하는 함수
MenuService:ChangeMenuSlot -- 메뉴 슬롯 변경 시 표시 버거와 UI를 업데이트하는 함수
MenuService:GetBurgerRUID -- 버거 태그로 스프라이트 RUID를 조회하여 반환하는 함수
EventDialogManager:ParseDialog -- 리치 텍스트를 파싱하여 일반 텍스트와 포맷 정보를 분리하는 함수
EventDialogManager:TypeWriter -- 텍스트를 타이핑 효과로 출력하는 함수
EventDialogManager:PlayTypeWriter -- 타이핑 애니메이션을 시작하는 함수
EventDialogManager:SkipTypeWriter -- 타이핑 애니메이션을 스킵하는 함수
EventDialogManager:EndTypeWriter -- 타이핑 애니메이션을 종료하고 정리 작업을 수행하는 함수
EventManager:CallEvent -- 이벤트를 시작하고 시간 흐름을 정지시키는 함수
EventManager:EndEvent -- 이벤트를 종료하고 후속 처리를 수행하는 함수
EventManager:CallDialog -- 특정 인덱스의 이벤트 다이얼로그를 호출하는 함수
EventManager:MoveNextDialog -- 다음 다이얼로그로 넘어가거나 타이핑을 스킵하는 함수
EventManager:SetEventOccurByAchiId -- 업적 ID에 따라 발생할 이벤트를 설정하는 함수
EventManager:ReturnOccuredEventGroupId -- 업적 ID에 해당하는 이벤트 그룹 ID들을 반환하는 함수
EventManager:CallEventOnDayChanged -- 하루가 지날 때 대기 중인 이벤트를 호출하는 함수
EventManager:SetEventReferKeyData -- 이벤트의 참조키 데이터를 설정하는 함수
EventManager:SetCanMoveNext -- 다음 다이얼로그로 넘어갈 수 있는지 설정하고 자동 진행 타이머를 관리하는 함수
EventManager:SetCallbackFunction -- 이벤트 종료 후 실행할 콜백 함수를 설정하는 함수
EventManager:SetReferKeyForEmployment -- 고용 이벤트에서 직원 ID를 참조키로 설정하는 함수
EventManager:HandleButtonClickEvent -- 이벤트 UI의 버튼 클릭을 처리하는 핸들러
EventManager:HandleTutorialTriggerEvent -- 튜토리얼 트리거 이벤트를 처리하여 해당 튜토리얼 이벤트를 호출하는 핸들러
EventUIManager:Open -- 이벤트 UI를 열고 현재 HUD 상태를 저장하는 함수
EventUIManager:Close -- 이벤트 UI를 닫고 이전 상태로 복원하는 함수
EventUIManager:SetDialogUI -- 이벤트 다이얼로그 타입에 따라 적절한 UI를 설정하는 함수
EventUIManager:CloseAllEventEntities -- 모든 이벤트 UI 엔티티들을 비활성화하는 함수
EventUIManager:SetCanMoveNextText -- 다음 단계 이동 버튼과 텍스트 표시 상태를 설정하는 함수
EventUIManager:ResetEntitiesRUID -- 이벤트 UI 엔티티들의 RUID를 초기화하는 함수
EventUIManager:OnBeginPlay -- 게임 시작 시 이벤트 UI 엔티티들을 등록하는 함수
EventUIManager:IsAnyEventUIOpened -- 어떤 이벤트 UI가 열려있는지 확인하는 함수
UIButtonUnlockLogic:OnBeginPlay -- 게임 시작 시 버튼 잠금 해제 데이터를 로드하는 함수
UIButtonUnlockLogic:LoadDataSet -- CSV에서 버튼 잠금 해제 데이터를 로드하는 함수
UIButtonUnlockLogic:GetButtonUnlockData -- ID로 버튼 잠금 해제 데이터를 가져오는 함수
UIButtonUnlockLogic:IsButtonUnlocked -- 지정된 버튼이 잠금 해제되었는지 확인하는 함수
UIButtonUnlockLogic:SetButtonsUnlock -- 모든 버튼들의 잠금 해제 상태를 업데이트하는 함수
UIButtonUnlockLogic:SetEnableEveryButtons -- 모든 버튼을 강제로 잠금 해제하는 함수
UIButtonUnlockLogic:HandlePlayerManagementChangedEvent -- 플레이어 경영 데이터 변경 시 버튼 상태를 업데이트하는 핸들러
UIEventConfettiSpawner:OnBeginPlay -- 콘페티 스포너를 초기화하는 함수
UIEventConfettiSpawner:SpawnRandomConfetti -- 랜덤 콘페티를 생성하고 애니메이션을 시작하는 함수
UIEventConfettiSpawner:StartSpawnConfetties -- 콘페티 스폰 애니메이션을 시작하는 함수
UIEventConfettiSpawner:EndSpawnConfetties -- 콘페티 스폰을 종료하고 정리하는 함수
UIEventConfettiSpawner:ReturnRandomConfettiRUID -- 랜덤 콘페티 RUID를 반환하는 함수
ButtonUnlockData:Load -- CSV 데이터에서 버튼 잠금 해제 정보를 로드하는 함수
EventDataSetLogic:OnBeginPlay -- 게임 시작 시 이벤트 관련 데이터를 초기화하는 함수
EventDataSetLogic:LoadDataSet -- CSV에서 이벤트 그룹 데이터와 NPC 데이터를 로드하는 함수
EventDataSetLogic:SetOpenFunctionRUIDs -- 기능 열기 이벤트에 사용할 아이콘 RUID들을 설정하는 함수
EventDataSetLogic:GetNPCData -- NPC ID로 NPC 데이터를 반환하는 함수
EventDataSetLogic:ReturnDialogText -- 이벤트 다이얼로그의 텍스트를 참조키와 인수로 포맷팅하여 반환하는 함수
EventDataSetLogic:GetEventGroupData -- 이벤트 그룹 ID로 이벤트 그룹 데이터를 반환하는 함수
EventDialogData:Load -- CSV 데이터에서 이벤트 다이얼로그 정보를 로드하는 함수
EventGroupData:Load -- CSV 데이터에서 이벤트 그룹 정보를 로드하고 다이얼로그 데이터를 연결하는 함수
EventGroupData:ReturnBooleanByString -- 문자열을 불린값으로 변환하는 함수
NPCData:Load -- CSV 데이터에서 NPC 정보를 로드하고 기본값을 설정하는 함수
UIEventCongrats:Init -- 축하 이벤트 UI 요소들을 초기화하는 함수
UIEventCongrats:Refresh -- 축하 이벤트 UI를 새로고침하고 축하 효과를 표시하는 함수
UIEventDecoUpgrade:StartRender -- 인테리어 업그레이드 애니메이션 렌더링을 시작하는 함수
UIEventDecoUpgrade:EndRender -- 렌더링을 종료하고 다음 단계로 이동을 허용하는 함수
UIEventDecoUpgrade:ChangePhase -- 지정된 단계로 변경하는 함수
UIEventDecoUpgrade:PhaseFunction -- 단계별 인테리어 업그레이드 애니메이션을 실행하는 함수
UIEventDecoUpgrade:GetTargetEntity -- 엔티티 이름으로 해당 엔티티를 찾아 반환하는 함수
UIEventDecoUpgrade:StartCameraTween -- 카메라 전환 애니메이션을 시작하는 함수
UIEventDecoUpgrade:StartToastTween -- 완료 토스트 메시지 애니메이션을 시작하는 함수
UIEventDecoUpgrade:SetParticlesPos -- 카메라 레벨별 파티클 이팩트 위치를 설정하는 함수
UIEventDecoUpgrade:ChangeCameraTo -- 지정된 카메라로 전환하는 함수
UIEventDecoUpgrade:Lerp -- 두 값 사이를 선형 보간하는 함수
UIEventEndTrend:Init -- 트렌드 종료 이벤트 UI 요소들을 초기화하는 함수
UIEventEndTrend:Refresh -- 트렌드 종료 이벤트 정보를 화면에 표시하고 보고서를 생성하는 함수
UIEventEndTrend:Reset -- UI 요소들을 초기 상태로 되돌리는 함수
UIEventExpansion:Init -- 확장 이벤트 UI 요소들과 카메라 경계를 초기화하는 함수
UIEventExpansion:StartRender -- 확장 이벤트 렌더링을 시작하고 초기 설정을 진행하는 함수
UIEventExpansion:EndRender -- 렌더링을 종료하고 다음 단계로 이동을 허용하는 함수
UIEventExpansion:ChangePhase -- 지정된 단계로 변경하는 함수
UIEventExpansion:PhaseFunction -- 단계별 확장 애니메이션을 실행하는 함수
UIEventExpansion:StartCameraTween -- 카메라 전환 애니메이션을 시작하는 함수
UIEventExpansion:StartToastTween -- 완료 토스트 메시지 애니메이션을 시작하는 함수
UIEventExpansion:SetParticlesPos -- 확장 레벨에 맞는 파티클 이팩트 위치를 설정하는 함수
UIEventExpansion:SetToastInfo -- 토스트 아이콘과 텍스트를 설정하는 함수
UIEventExpansion:MakeReport -- 확장/인테리어 업그레이드 보고서를 생성하는 함수
UIEventExpansion:Lerp -- 두 값 사이를 선형 보간하는 함수
UIEventFail:Init -- 실패 이벤트 UI 요소들을 초기화하는 함수
UIEventFail:Refresh -- 실패 이벤트 UI를 새로고침하고 실패 효과를 표시하는 함수
UIEventGetItem:Init -- 아이템 획득 이벤트 UI 요소들을 초기화하는 함수
UIEventGetItem:Refresh -- 아이템 획득 이벤트 UI를 새로고침하고 획득한 아이템을 표시하는 함수
UIEventGetItem:Reset -- 아이템 획득 이벤트 UI를 초기 상태로 리셋하는 함수
UIEventInfoDialog:Init -- 정보 다이얼로그 UI 요소들을 초기화하는 함수
UIEventInfoDialog:Refresh -- 정보 다이얼로그 UI를 새로고침하고 내용을 표시하는 함수
UIEventNewEmployee:Init -- 신입 직원 이벤트 UI 요소들을 초기화하는 함수
UIEventNewEmployee:Refresh -- 신입 직원 이벤트 UI를 새로고침하고 직원 정보를 표시하는 함수
UIEventNewEmployee:Reset -- 신입 직원 이벤트 UI를 초기 상태로 리셋하는 함수
UIEventOpenFunction:Init -- 기능 열기 이벤트 UI 요소들을 초기화하는 함수
UIEventOpenFunction:Refresh -- 기능 열기 이벤트 UI를 새로고침하고 아이콘을 표시하는 함수
UIEventOpenFunction:Reset -- 기능 열기 이벤트 UI를 초기 상태로 리셋하는 함수
UIEventRankingAnnounce:Init -- 랭킹 발표 이벤트 UI 요소들을 초기화하는 함수
UIEventRankingAnnounce:StartRender -- 랭킹 발표 렌더링을 시작하고 데이터를 준비하는 함수
UIEventRankingAnnounce:EndRender -- 렌더링을 종료하고 다음 단계로 이동을 허용하는 함수
UIEventRankingAnnounce:SetInitialInformations -- 이전 랭킹 기록 정보를 초기 설정하는 함수
UIEventRankingAnnounce:SetListEntities -- 랭킹 리스트 엔티티들을 생성하고 배치하는 함수
UIEventRankingAnnounce:SetNoise -- 랭킹 슬롯에 노이즈 효과를 설정하는 함수
UIEventRankingAnnounce:AnnounceResult -- 랭킹 결과를 발표하고 현재 순위를 표시하는 함수
UIEventRankingAnnounce:ClearDatas -- 랭킹 데이터와 타이머를 초기화하는 함수
UIEventRankingAnnounce:ChangePhase -- 랭킹 발표 단계를 변경하는 함수
UIEventRankingAnnounce:PhaseFunction -- 단계별 랭킹 발표 로직을 실행하는 함수
UIEventResignEmployee:Init -- 직원 퇴사 이벤트 UI 요소들을 초기화하는 함수
UIEventResignEmployee:Refresh -- 직원 퇴사 이벤트 UI를 새로고침하고 직원 정보를 표시하는 함수
UIEventResignEmployee:Reset -- 직원 퇴사 이벤트 UI를 초기 상태로 리셋하는 함수
UIEventStartTrend:Init -- 트렌드 시작 이벤트 UI 요소들을 초기화하는 함수
UIEventStartTrend:Refresh -- 트렌드 시작 이벤트 UI를 새로고침하고 긍정/부정 트렌드를 표시하는 함수
UIEventStartTrend:Reset -- 트렌드 시작 이벤트 UI를 초기 상태로 리셋하는 함수
UIEventStoreName:OnBeginPlay -- 상점명 변경 UI를 초기화하고 이벤트를 연결하는 함수
UIEventStoreName:Refresh -- 상점명 입력 필드와 비용 정보를 업데이트하는 함수
UIEventStoreName:OnClickConfirmBtn -- 상점명 설정/변경 확인 버튼 클릭 이벤트를 처리하는 함수
UIEventTalkDialog:Init -- 대화 이벤트 UI 요소들을 초기화하는 함수
UIEventTalkDialog:Refresh -- 대화 데이터를 바탕으로 UI를 업데이트하는 함수
UIEventTalkDialog:PlaySFX -- 지정된 키에 따라 사운드 이팩트를 재생하는 함수
UIEventTalkDialog:PlayPlayerEmotion -- 플레이어 아바타에 감정 애니메이션을 재생하는 함수
TutorialData:Load -- CSV 데이터에서 튜토리얼 설정을 로드하는 함수
TutorialDataSetLogic:OnBeginPlay -- 게임 시작 시 튜토리얼 데이터를 로드하는 함수
TutorialDataSetLogic:LoadDataSet -- CSV에서 튜토리얼 데이터를 로드하여 테이블에 저장하는 함수
TutorialDataSetLogic:GetTutorialData -- ID로 튜토리얼 데이터를 반환하는 함수
TutorialManager:IsEnableOpenPopUp -- 팝업을 열 수 있는지 시간 간격을 체크하는 함수
TutorialManager:GetTargetEntity -- 튜토리얼 데이터에 따라 타겟 엔티티를 찾아 반환하는 함수
TutorialManager:SetTargetPosition -- 타겟 엔티티의 위치를 부모에 맞춰 설정하는 함수
TutorialManager:MirroringUIParent -- 타겟 UI의 부모 구조를 미러링하여 튜토리얼 오버레이를 생성하는 함수
TutorialManager:ShowMask -- 튜토리얼 마스크를 표시하고 가이드 텍스트를 배치하는 함수
TutorialManager:HideMask -- 튜토리얼 마스크를 숨기고 정리 작업을 수행하는 함수
TutorialManager:PlayTutorial -- 튜토리얼을 실행하고 설정에 따라 UI를 표시하는 함수
TutorialManager:OnEndPlay -- 게임 종료 시 타이머를 정리하는 함수
TutorialManager:SendTutorialTriggerEvent -- 튜토리얼 트리거 이벤트를 전송하는 함수
TutorialManager:CheckForceTo -- 강제 조건을 체크하는 함수
TutorialManager:RegisterFunction -- 튜토리얼에서 사용할 함수들을 등록하는 함수
TutorialManager:RegisterForceTo -- 튜토리얼 강제 조건들을 등록하는 함수
TutorialManager:OnBeginPlay -- 게임 시작 시 함수를 등록하는 함수
TutorialManager:SetCallbackHideMask -- 마스크 숨김 콜백을 설정하는 함수
TutorialManager:SetGuideTextPosition -- 가이드 텍스트의 위치를 설정하는 함수
TutorialManager:SetGuideTextScreenPosition -- 화면 기준으로 가이드 텍스트의 위치를 설정하는 함수
TutorialManager:HandleButtonClickEvent -- 튜토리얼 버튼 클릭을 처리하고 타겟 엔티티의 이벤트를 전달하는 핸들러
ManagementDataSetLogic:OnBeginPlay -- 게임 시작 시 관리 관련 데이터셋을 로드하는 함수
ManagementDataSetLogic:LoadDataSet -- 관리 레벨 데이터와 유지비 데이터를 CSV에서 로드하는 함수
ManagementDataSetLogic:LoadConfigData -- 기구 관련 설정 데이터를 컨피그에서 로드하는 함수
ManagementDataSetLogic:ReturnMaintenance -- 플레이어의 총 유지비(매장 임대료 + 기구 비용)를 계산하여 반환하는 함수
ManagementDataSetLogic:ReturnStoreRent -- 플레이어의 매장 확장, 인테리어, 데코 레벨에 따른 임대료를 계산하는 함수
ManagementDataSetLogic:ReturnApplianceCost -- 플레이어의 기구 개수와 레벨에 따른 유지비를 계산하는 함수
ManagementDataSetLogic:MakeGoalCompleteReport -- 관리 목표 달성 메시지를 리포트 대기열에 추가하는 클라이언트 함수
ManagementDataSetLogic:GetManagementLevelData -- 지정된 레벨의 관리 레벨 데이터를 반환하는 함수
ManagementDataSetLogic:RequestStartMLevelUpRewardRender -- 관리 레벨 업 보상 UI 렌더링을 시작하는 클라이언트 함수
ManagementDataSetLogic:GetManagementGoalData -- 지정된 스테이지와 레벨의 관리 목표 데이터를 반환하는 함수
ManagementGoalData:Load -- 특정 레벨의 관리 목표 데이터를 CSV 행들로부터 로드하는 함수
ManagementGoalIndexData:Load -- CSV 데이터에서 업적 타입과 목표값을 로드하는 함수
ManagementLevelData:Load -- 데이터 테이블에서 관리 레벨의 UI 표시 정보를 로드하는 함수
UIHUDManagement:OnBeginPlay -- HUD 관리 UI의 하위 엔티티들을 초기화하는 함수
UIHUDManagement:Refresh -- 플레이어의 관리 레벨 상태에 따라 HUD를 업데이트하는 함수
UIManagement:Open -- 관리 UI를 열고 오픈 애니메이션을 재생하는 함수
UIManagement:Close -- 관리 UI를 닫는 함수
UIManagement:Refresh -- 플레이어의 관리 레벨과 목표 상태에 따라 UI를 갱신하는 함수
UIManagement:OnClickLevelUpBtn -- 관리 레벨 업 버튼 클릭 시 조건을 확인하고 레벨업을 요청하는 함수
UIManagement:HandleButtonClickEvent -- 관리 UI 열기 버튼 클릭 이벤트 처리
UIManagement:HandleButtonClickEvent2 -- 관리 UI 닫기 버튼 클릭 이벤트 처리
UIManagement:HandleButtonClickEvent3 -- 레벨업 버튼 클릭 이벤트 처리
UIManagement:HandlePlayerManagementChangedEvent -- 플레이어 관리 상태 변경 이벤트 처리
UIManagement:HandleButtonClickEvent4 -- 추가 관리 UI 열기 버튼 클릭 이벤트 처리
UIManagement:HandleButtonClickEvent5 -- 랭킹 보기 버튼 클릭 이벤트 처리
UIManagement:HandleButtonClickEvent6 -- 스테이지 선택 버튼 클릭 이벤트 처리
UIManagement:HandleplayerStageProgressChangedEvent -- 플레이어 스테이지 진행도 변경 이벤트 처리
UIManagementGoalSlotRenderer:OnBeginPlay -- 관리 목표 슬롯의 하위 UI 요소들을 초기화하고 클릭 이벤트를 연결하는 함수
UIManagementGoalSlotRenderer:Refresh -- 관리 목표 슬롯의 데이터와 완료 상태에 따라 UI를 갱신하는 함수
UIManagementGoalSlotRenderer:RefreshGaugeBar -- 목표 진행도에 따라 게이지 바를 업데이트하는 함수
UIManagementLevelUpReward:OnBeginPlay -- 게임 시작 시 레벨업 보상 UI를 비활성화하는 함수
UIManagementLevelUpReward:Open -- 지정된 관리 레벨에 대한 레벨업 보상 UI를 여는 함수
UIManagementLevelUpReward:Close -- 레벨업 보상 UI를 닫고 정리 작업을 수행하는 함수
UIManagementLevelUpReward:SetCanClose -- UI의 닫기 가능 상태를 설정하는 함수
UIManagementLevelUpReward:StartRender -- 관리 레벨업 보상 UI의 렌더링을 시작하는 함수
UIManagementLevelUpReward:ReturnLogList -- 관리 레벨업 시 표시할 혜택 목록을 생성하여 반환하는 함수
UIManagementLevelUpReward:HandleButtonClickEvent -- 레벨업 보상 UI 닫기 버튼 클릭 이벤트 처리
TrialLogic:ReturnRandomRivalId -- 플레이어가 선택한 직원과 중복되지 않는 랜덤한 라이벌 직원 ID를 반환하는 함수
TrialLogic:ReturnRandomBurgerIngreList -- Trial용 랜덤 버거 재료 리스트를 생성하여 반환하는 함수
TrialLogic:ReturnUserStatByTrialInfo -- Trial 정보와 플레이어 데이터를 기반으로 사용자의 스탯 값을 계산하여 반환하는 함수
TrialLogic:ReturnIngreGradeByGrade -- Trial 등급에 따라 사용할 재료의 등급을 랜덤하게 선택하여 반환하는 함수
TrialLogic:ReturnUserRank -- 사용자 스탯과 요구 스탯을 비교하여 Trial에서의 순위를 계산하는 함수
TrialLogic:ReturnTrialScore -- 순위와 플레이어 가중치를 기반으로 Trial 점수를 계산하여 반환하는 함수
TrialLogic:ReturnStackPositionByGrid -- 그리드 좌표를 실제 UI 위치로 변환하여 스택 아이템의 배치 위치를 반환하는 함수
TrialLogic:ReturnTrialName -- Trial ID를 기반으로 현지화된 Trial 이름을 반환하는 클라이언트 전용 함수
TrialLogic:ReturnUnofficialTrialProgress -- 플레이어의 능력치를 기반으로 비공식 Trial에서 도전 가능한 진행도를 계산하는 함수
TrialLogic:ReturnNextProgress -- 현재 진행도에서 다음 단계 진행도를 계산하여 반환하는 함수
TrialLogic:IsTrialRecommended -- 플레이어의 능력치를 기반으로 해당 Trial이 추천되는지 판단하는 클라이언트 전용 함수
TrialLogic:GetChallengingOfficialTrialProgress -- 공식 Trial에서 플레이어가 도전할 수 있는 다음 진행도를 반환하는 함수
TrialLogic:GetChallengingTrialData -- Trial 타입에 따라 플레이어가 도전할 수 있는 난이도 데이터를 반환하는 함수
TrialLogic:GetExEmployeeIdOfType -- 특정 직원 타입에 대해 제외된 직원 ID를 반환하는 함수
TrialLogic:PlayUIEmployeeAnim -- UI에서 직원의 애니메이션과 장비를 표시하는 함수
TrialLogic:ReturnPreviousProgress -- 현재 진행도에서 이전 단계 진행도를 계산하여 반환하는 함수
TrialResultUILogic:EnableTrialResultUI -- Trial 결과 UI의 활성화/비활성화를 제어하는 클라이언트 전용 함수
TrialResultUILogic:UpdateTrialResultInfo -- Trial 결과 정보를 업데이트하고 UI 요소들을 설정하는 클라이언트 전용 함수
TrialResultUILogic:ChangePhase -- Trial 결과 UI의 페이즈를 변경하고 해당 페이즈에 맞는 초기화를 수행하는 클라이언트 전용 함수
TrialResultUILogic:InitEntitiesForPhase -- 특정 페이즈에 필요한 UI 엔티티들의 상태를 초기화하는 클라이언트 전용 함수
TrialResultUILogic:PhaseFunction -- 각 페이즈에서 실행할 애니메이션과 로직을 처리하는 클라이언트 전용 함수
TrialResultUILogic:HandleButtonClickEvent -- Trial 결과 화면에서 버튼 클릭을 처리하는 이벤트 핸들러
TrialSimpleRenderLogic:OnBeginPlay -- 게임 시작 시 Trial 렌더링에 필요한 애니메이션 리소스를 로드하는 클라이언트 전용 함수
TrialSimpleRenderLogic:EnterTrialRender -- Trial 렌더링을 시작하고 레이아웃과 화면 정보를 설정하는 클라이언트 함수
TrialSimpleRenderLogic:EndTrialRender -- Trial 렌더링을 종료하고 결과 UI로 전환하는 클라이언트 전용 함수
TrialSimpleRenderLogic:SkipTrialRender -- Trial 렌더링을 건너뛰고 바로 결과 화면으로 이동하는 클라이언트 함수
TrialSimpleRenderLogic:FadeInFunction -- Trial 화면 페이드인 시 UI 그룹들을 설정하고 BGM을 적용하는 클라이언트 함수
TrialSimpleRenderLogic:ChangePhase -- Trial 렌더링 페이즈를 변경하고 해당 페이즈의 UI와 로직을 초기화하는 클라이언트 전용 함수
TrialSimpleRenderLogic:InitEntitiesForPhase -- 특정 페이즈에서 필요한 엔티티들을 초기화하고 설정하는 클라이언트 전용 함수
TrialSimpleRenderLogic:PhaseFunction -- 각 페이즈에서 실행할 타이머 기반 로직과 애니메이션을 처리하는 클라이언트 전용 함수
TrialSimpleRenderLogic:HandleButtonClickEvent2 -- Trial 렌더링 중 스킵 버튼 클릭을 처리하는 이벤트 핸들러
TrialUILogic:OpenSelectTrialUI -- Trial 선택 UI를 열고 다른 관련 UI들을 비활성화하는 클라이언트 전용 함수
TrialUILogic:ReturnIconRUIDByTargetStat -- 대상 스탯 타입에 따라 해당하는 아이콘 RUID를 반환하는 함수
TrialUILogic:DrawDifficultyStars -- Trial 난이도를 별 아이콘으로 표시하는 클라이언트 전용 함수
TrialUILogic:GradeColorCode -- Trial 등급에 따른 색상 코드를 반환하는 함수
TrialUILogic:CheckTrialRedDotEnable -- 플레이어의 능력치를 확인하여 Trial 탭에 빨간 점 표시 여부를 결정하는 클라이언트 함수
TrialUILogic:HandleButtonClickEvent -- Trial 버튼 클릭 이벤트를 처리하여 Trial 선택 UI를 여는 이벤트 핸들러
TrialData:Load -- CSV 데이터에서 Trial 정보를 로드하여 객체의 속성들을 초기화하는 함수
TrialData:GetGradeData -- 지정된 등급에 해당하는 TrialGradeData 객체를 반환하는 함수
TrialData:GetMaxDifficultyData -- 최고 등급의 최고 난이도 데이터를 반환하는 함수
TrialDataSetLogic:OnBeginPlay -- 게임 시작 시 Trial 데이터셋을 로드하는 초기화 함수
TrialDataSetLogic:LoadDataSet -- CSV에서 Trial 데이터와 승리 가중치 데이터를 로드하여 메모리에 저장하는 함수
TrialDataSetLogic:GetTrialData -- 특정 Trial ID에 해당하는 TrialData 객체를 반환하는 함수
TrialDifficultyData:Load -- CSV 데이터에서 Trial 난이도 정보를 로드하여 보상 및 비용 데이터를 설정하는 함수
TrialDifficultyData:GetTrialCost -- 플레이어의 현재 스테이지와 Trial 타입에 따라 참가 비용을 계산하여 반환하는 함수
TrialGradeData:Load -- Trial 등급 데이터를 로드하고 해당 등급의 모든 난이도 데이터를 초기화하는 함수
TrialGradeData:ReturnGradeBGRUID -- 등급에 따른 배경 이미지 RUID를 반환하는 함수
TrialGradeData:GetDifficultyData -- 지정된 난이도에 해당하는 TrialDifficultyData 객체를 반환하는 함수
TrialGradeData:ReturnMaxDifficulty -- 현재 등급에서 사용 가능한 최대 난이도 값을 반환하는 함수
UITrialCustomer:ChangeAvatarActionState -- Trial 고객 아바타의 액션 상태를 변경하는 클라이언트 전용 함수
UITrialCustomer:SpawnAndGetIn -- Trial 고객을 생성하고 지정된 위치로 이동시키는 클라이언트 전용 함수
UITrialCustomer:BuyAndGoOut -- Trial 고객이 구매 후 퇴장하는 애니메이션을 처리하는 클라이언트 전용 함수
UITrialCustomer:RequestBuyState -- Trial 고객에게 구매 상태를 요청하는 클라이언트 전용 함수
UITrialCustomer:OnBeginPlay -- 컴포넌트 초기화 시 아이템 엔티티를 찾아 저장하는 클라이언트 전용 함수
UITrialCustomer:SetItem -- Trial 고객이 들고 있을 아이템을 태그에 따라 설정하는 클라이언트 전용 함수
UITrialCustomers:OnBeginPlay -- 컴포넌트 초기화 시 자식 레이아웃들을 찾아 저장하는 클라이언트 전용 함수
UITrialCustomers:Spawn -- Trial 고객들을 생성하고 애니메이션과 함께 나타나게 하는 클라이언트 전용 함수
UITrialCustomers:Despawn -- Trial 고객들을 사라지게 하는 애니메이션을 처리하는 클라이언트 전용 함수
UITrialCustomers:SetStatIconEntities -- 점수에 따라 스탯 아이콘 엔티티들을 생성하고 설정하는 클라이언트 전용 함수
UITrialCustomers:TweenLog -- 스탯 로그를 애니메이션과 함께 표시하는 클라이언트 전용 함수
UITrialEmployeeDetail:OnBeginPlay -- 컴포넌트 초기화 시 UI 요소들을 찾아 연결하는 클라이언트 전용 함수
UITrialEmployeeDetail:Refresh -- 직원 정보와 Trial 결과 예측을 표시하도록 UI를 새로고침하는 클라이언트 전용 함수
UITrialEmployeeSlot:Init -- 직원 슬롯 UI 요소들을 초기화하고 클릭 이벤트를 연결하는 함수
UITrialEmployeeSlot:Refresh -- 직원 슬롯을 주어진 직원 ID로 새로고침하는 함수
UITrialEmployeeSlot:SelectEmp -- 직원을 선택하여 상세 정보를 업데이트하는 함수
UITrialEmployeeSlot:OnBeginPlay -- 컴포넌트 시작 시 초기화를 수행하는 클라이언트 전용 함수
UITrialGradeUpRenderer:StartRender -- Trial 등급 상승 렌더링을 시작하는 클라이언트 전용 함수
UITrialGradeUpRenderer:EndRender -- Trial 등급 상승 렌더링을 종료하는 클라이언트 전용 함수
UITrialGradeUpRenderer:RenderGradeUp -- Trial 등급 상승 애니메이션을 단계별로 렌더링하는 클라이언트 전용 함수
UITrialGradeUpRenderer:RenderGradeMax -- Trial 최대 등급 달성 애니메이션을 단계별로 렌더링하는 클라이언트 전용 함수
UITrialGradeUpRenderer:Init -- UI 요소들을 초기화하고 원본 크기를 저장하는 클라이언트 전용 함수
UITrialGradeUpRenderer:SetGradeEntity -- 등급에 따라 등급 엔티티의 색상과 이미지를 설정하는 클라이언트 전용 함수
UITrialLayout:SetLayouts -- Trial 레이아웃들을 초기화하고 트윈 데이터를 준비하는 클라이언트 전용 함수
UITrialLayout:ClearChildEntities -- Trial 종료 시 모든 자식 엔티티들을 정리하고 데이터를 초기화하는 클라이언트 전용 함수
UITrialLayout:SpawnBurger -- 지정된 레이아웃에 버거들을 생성하는 클라이언트 전용 함수
UITrialLayout:SpawnIngredient -- 개별 재료를 생성하고 애니메이션 여부를 결정하는 클라이언트 전용 함수
UITrialLayout:RemoveBurger -- 버거를 제거하고 나머지 버거들을 아래로 이동시키는 클라이언트 전용 함수
UITrialLayout:SuccessFunction -- Trial 성공 이벤트를 처리하고 해당 애니메이션을 실행하는 클라이언트 전용 함수
UITrialLayout:SetStackEntities -- 직원 스탯에 따라 스택 아이템들을 생성하고 배치하는 클라이언트 전용 함수
UITrialLayoutSlot:OnBeginPlay -- 컴포넌트 초기화 시 모든 UI 요소들을 찾아 연결하는 클라이언트 전용 함수
UITrialLayoutSlot:SetBoxSlider -- 박스 슬라이더의 값을 설정하는 클라이언트 전용 함수
UITrialLayoutSlot:SetScoreboard -- 점수판에 순위와 점수를 표시하는 클라이언트 전용 함수
UITrialLayoutSlot:SetNametag -- 이름표를 설정하고 표시 모드를 결정하는 클라이언트 전용 함수
UITrialLayoutSlot:SetStatLogData -- 통계 로그 데이터를 설정하는 클라이언트 전용 함수
UITrialLayoutSlot:SetNotifyEnable -- 알림을 활성화하고 텍스트와 지속시간을 설정하는 클라이언트 전용 함수
UITrialLayoutSlot:SetVoteEntities -- 투표 엔티티들을 점수에 따라 설정하는 클라이언트 전용 함수
UITrialLayoutSlot:SetLayoutCustomerEntities -- 레이아웃에 고객 엔티티들을 설정하는 클라이언트 전용 함수
UITrialProgress:Init -- Trial 진행도 UI의 등급과 난이도 엔티티를 초기화하는 클라이언트 전용 함수
UITrialProgress:Refresh -- Trial 진행도 UI를 주어진 등급과 난이도로 새로고침하는 클라이언트 전용 함수
UITrialRewardPopup:Init -- Trial 보상 팝업 UI 요소들을 초기화하고 버튼 이벤트를 연결하는 클라이언트 전용 함수
UITrialRewardPopup:Open -- Trial 보상 팝업을 열고 애니메이션을 재생하는 클라이언트 전용 함수
UITrialRewardPopup:Close -- Trial 보상 팝업을 닫는 클라이언트 전용 함수
UITrialRewardPopup:Refresh -- Trial 정보와 보상 데이터를 기반으로 팝업 UI를 업데이트하는 클라이언트 전용 함수
UITrialScreen:OnBeginPlay -- 컴포넌트 초기화 시 Trial 화면의 모든 UI 요소들을 찾아 연결하는 클라이언트 전용 함수
UITrialScreen:SetTrialInformation -- Trial 정보를 화면에 표시하고 이름표, 설명, 진행도를 업데이트하는 클라이언트 전용 함수
UITrialScreen:SetCommentEnable -- Trial 진행 중 코멘트 메시지를 표시하고 타이머를 관리하는 클라이언트 전용 함수
UITrialScreen:SetScreenUI -- Trial 화면의 페이즈에 따라 UI 요소들의 표시 상태를 설정하는 클라이언트 전용 함수
UITrialScreen:SetTimeSlider -- 시간 진행도 슬라이더의 채우기 정도를 설정하는 클라이언트 전용 함수
UITrialSelect:OnBeginPlay -- 컴포넌트 초기화 시 탭 버튼들을 설정하고 이벤트를 연결하는 클라이언트 전용 함수
UITrialSelect:Open -- Trial 선택 UI를 열고 지정된 탭으로 전환하는 클라이언트 전용 함수
UITrialSelect:Close -- Trial 선택 UI를 닫고 시간 흐름을 정상화하는 클라이언트 전용 함수
UITrialSelect:SetSelectTab -- 선택된 탭을 설정하고 해당 탭의 콘텐츠를 로드하는 클라이언트 전용 함수
UITrialSelect:OnSelectTab -- 탭 선택 시 탭 버튼들의 비주얼 상태를 업데이트하는 클라이언트 전용 함수
UITrialSelect:Apply -- 선택된 탭에 따라 Trial 목록을 로드하고 표시하는 클라이언트 전용 함수
UITrialSelect:SetTabRedDot -- 탭에 빨간 점 표시를 설정하고 메인 메뉴 알림도 업데이트하는 클라이언트 전용 함수
UITrialSelect:HandleButtonClickEvent -- 닫기 버튼 클릭 시 Trial 선택 UI를 닫는 이벤트 핸들러
UITrialSelect:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 시 Trial 빨간 점 표시를 업데이트하는 이벤트 핸들러
UITrialSelectSlot:Init -- Trial 선택 슬롯 UI 요소들을 초기화하고 버튼 이벤트를 연결하는 함수
UITrialSelectSlot:Refresh -- Trial 슬롯을 주어진 데이터로 업데이트하고 비용, 상태 등을 표시하는 함수
UITrialSetEmployee:Open -- Trial에 참여할 직원 선택 UI를 열고 초기화하는 클라이언트 전용 함수
UITrialSetEmployee:Close -- 직원 선택 UI를 닫고 매니저 상태를 리셋하는 클라이언트 전용 함수
UITrialSetEmployee:RefreshList -- 직원 목록을 정렬 기준에 따라 업데이트하고 스크롤 뷰에 표시하는 함수
UITrialSetEmployee:RefreshDetail -- 선택된 직원의 상세 정보를 업데이트하고 선택 상태를 반영하는 함수
UITrialSetEmployee:OnClickSelectButton -- 직원 선택 버튼 클릭 시 선택된 직원으로 Trial을 시작하는 함수
UITrialSetEmployee:OnClickGrowthButton -- 직원 성장 버튼 클릭 시 선택된 직원의 업그레이드 UI를 여는 함수
UITrialSetEmployee:SetSortCriteria -- 직원 목록의 정렬 기준을 설정하고 목록을 새로고침하는 함수
UITrialSetEmployee:ReturnSortedEmployeeDetailTable -- 직원 상세 정보 테이블을 정렬 기준에 따라 정렬하여 반환하는 함수
UITrialSetEmployee:OnBeginPlay -- 컴포넌트 초기화 시 스크롤 뷰의 셀 업데이트 콜백을 설정하는 클라이언트 전용 함수
UITrialSetEmployee:OnListEmpty -- 직원 목록이 비어있을 때 UI 요소들의 표시 상태를 설정하는 함수
UITrialSetEmployee:HandleButtonClickEvent -- 닫기 버튼 클릭 시 직원 선택 UI를 닫는 이벤트 핸들러
UITrialSetEmployee:HandleButtonClickEvent2 -- 직원 선택 버튼 클릭 시 선택 로직을 실행하는 이벤트 핸들러
UITrialSetEmployee:HandleButtonClickEvent3 -- 직원 성장 버튼 클릭 시 업그레이드 UI를 여는 이벤트 핸들러
UITrialSetEmployee:HandleEmployeeDetailChangeEvent -- 직원 상세 정보 변경 시 선택된 직원의 정보를 업데이트하는 이벤트 핸들러
UITrialSetTopBar:OnBeginPlay -- 컴포넌트 초기화 시 상단바 UI 요소들을 연결하고 이벤트를 설정하는 클라이언트 전용 함수
UITrialSetTopBar:Refresh -- Trial 정보로 상단바 UI를 업데이트하고 추천 레벨을 표시하는 함수
UITrialSetTopBar:ToggleTrialDescText -- Trial 설명 톨틁을 열고 닫는 토글 함수
EmploymentDetail:SetUI -- 직원 상세 정보 UI를 설정하는 함수
EmploymentDetail:HandleButtonClickEvent -- 직원 상세 정보 버튼 클릭 이벤트를 처리하는 함수
EmploymentLevelButton:SetUI -- 고용 레벨 버튼 UI를 설정하는 함수
EmploymentLevelButton:SetStageImage -- 현재 스테이지에 맞는 이미지를 설정하는 함수
EmploymentLevelButton:HandleButtonClickEvent -- 고용 레벨 버튼 클릭 이벤트를 처리하는 함수
PlayerEmployment:SaveToDB -- 고용 관련 데이터를 데이터베이스에 저장하는 함수
PlayerEmployment:OnLoadedDataFromDB -- 데이터베이스에서 고용 관련 데이터를 로드하는 함수
PlayerEmployment:InitComponent -- 고용 컴포넌트를 초기화하는 함수
PlayerEmployment:OnBeginPlay -- 게임 시작 시 고용 관련 데이터를 초기화하는 함수
PlayerEmployment:SetEmploymentTypeInfo -- 고용 타입 정보를 설정하는 함수
PlayerEmployment:SetEmploymentTypeList -- 클라이언트에서 고용 타입 목록을 설정하는 함수
PlayerEmployment:SuccessToStartRecruit -- 고용 시작이 성공했을 때 처리하는 함수
PlayerEmployment:CheckCanStartRecruit -- 고용을 시작할 수 있는지 확인하는 함수
PlayerEmployment:FailToStartRecruit -- 고용 시작이 실패했을 때 처리하는 함수
PlayerEmployment:OnProcessingRecruit -- 고용 처리를 시작하는 함수
PlayerEmployment:OnFinishRecruiting -- 고용 처리가 완료되었을 때 처리하는 함수
PlayerEmployment:Recruit_Fix -- 튜토리얼용 고정 직원 목록을 생성하는 함수
PlayerEmployment:ChangeState -- 고용 상태를 변경하는 함수
PlayerEmployment:CheckCanEmployChuchu -- 선택한 직원을 고용할 수 있는지 확인하는 함수
PlayerEmployment:SuccessToEmployChuchu -- 직원 고용이 성공했을 때 처리하는 함수
PlayerEmployment:FailToEmployChuchu -- 직원 고용이 실패했을 때 처리하는 함수
PlayerEmployment:OnCancelEmployment -- 고용을 취소할 때 처리하는 함수
PlayerEmployment:CancelEmploymentServer -- 서버에서 고용 취소를 처리하는 함수
PlayerEmployment:CancelEmploymentClient -- 클라이언트에서 고용 취소를 처리하는 함수
PlayerEmployment:OnSyncProperty -- 서버에서 동기화된 속성을 처리하는 함수
PlayerEmployment:UpdateEmploymentList -- 고용 직원 목록을 업데이트하는 함수
PlayerEmployment:UpdateHasClover -- 고용 비용에 따른 UI 색상 업데이트 함수
PlayerEmployment:WaitForRecruit -- 고용 대기 시간을 처리하는 함수
PlayerEmployment:AddScoutLv -- 스카웃 레벨을 1 증가시키는 함수
PlayerEmployment:ModifyScoutLv -- 스카웃 레벨을 수정하는 함수
PlayerEmployment:SyncScoutLv -- 스카웃 레벨을 클라이언트에 동기화하는 함수
PlayerEmployment:OnSelectChuchuInCollection -- 컶렉션에서 선택한 츄츄를 처리하는 함수
PlayerEmployment:AddEmploymentLv -- 고용 레벨을 1 증가시키는 함수
PlayerEmployment:ModifyEmploymentLv -- 고용 레벨을 수정하는 함수
PlayerEmployment:SyncEmploymentLv -- 고용 레벨을 클라이언트에 동기화하는 함수
PlayerEmployment:ReturnCostByEmploymentLv -- 고용 레벨에 따른 비용을 계산하여 반환하는 함수
PlayerEmployment:ReturnCostByScoutLv -- 스카웃 레벨에 따른 비용을 계산하여 반환하는 함수
PlayerEmployment:FailToScout -- 스카웃이 실패했을 때 처리하는 함수
PlayerEmployment:SuccessToScout -- 스카웃이 성공했을 때 처리하는 함수
PlayerEmployment:OpenScoutUI -- 스카웃 UI를 여는 함수
PlayerEmployment:LogEmployment -- 고용 관련 로그를 기록하는 함수
PlayerEmployment:ReturnEmploymentChuchuPool -- 고용 가능한 츄츄 풀을 반환하는 함수
PlayerEmployment:RerollList -- 고용 목록을 다시 뽑는 함수
PlayerEmployment:AddRerollCount -- 리롤 횟수를 증가시키는 함수
PlayerEmployment:SyncRerollCount -- 리롤 횟수를 클라이언트에 동기화하는 함수
PlayerEmployment:CalcRerollCost -- 리롤 비용을 계산하는 함수
PlayerEmployment:CalcEmploymentStartLv -- 고용 시작 레벨을 계산하는 함수
PlayerEmployment:HandlePlayerArcaneSymbolChangedEvent -- 플레이어 아케인심볼 변경 이벤트를 처리하는 함수
UIEmployment:OnBeginPlay -- 게임 시작 시 고용 UI 초기화를 처리하는 함수
UIEmployment:SetEmploymentTypeList -- 고용 타입 목록을 UI에 설정하는 함수
UIEmployment:OpenUI -- 고용 UI를 여는 함수
UIEmployment:CloseUI -- 고용 UI를 닫는 함수
UIEmployment:ChangeState -- 고용 UI 상태를 변경하는 함수
UIEmployment:OnCilckLevelButton -- 고용 레벨 버튼 클릭 시 처리하는 함수
UIEmployment:SwitchButtonOutline -- 버튼 선택 상태를 변경하는 함수
UIEmployment:OnClickOkButton -- 확인 버튼 클릭 시 처리하는 함수
UIEmployment:FailRecruiting -- 고용이 실패했을 때 처리하는 함수
UIEmployment:ShowEmployeeList -- 고용 가능한 직원 목록을 보여주는 함수
UIEmployment:OnCilckEmpListButton -- 직원 목록에서 직원을 선택했을 때 처리하는 함수
UIEmployment:SuccessEmploy -- 직원 고용이 성공했을 때 처리하는 함수
UIEmployment:FailEmploy -- 직원 고용이 실패했을 때 처리하는 함수
UIEmployment:CancelEmployment -- 고용을 취소했을 때 처리하는 함수
UIEmployment:DisplayDetail -- 선택된 직원의 상세 정보를 보여주는 함수
UIEmployment:OnClickCancelEmployment -- 고용 취소 버튼을 클릭했을 때 처리하는 함수
UIEmployment:UpdateEmploymentLvText -- 고용 레벨 텍스트를 업데이트하는 함수
UIEmployment:UpdateEmploymentStageImg -- 고용 스테이지 이미지를 업데이트하는 함수
UIEmployment:UpdateRerollText -- 리롤 비용 텍스트를 업데이트하는 함수
UIEmployment:OnClickRerollBtn -- 리롤 버튼을 클릭했을 때 처리하는 함수
UIEmployment:UpdateDepositUI -- 고용 보증금 UI를 업데이트하는 함수
UIEmployment:UpdateScountLvText -- 스카웃 레벨 텍스트를 업데이트하는 함수
UIEmployment:UpdateChuchuLevelInfoText -- 츄츄 레벨 정보 텍스트를 업데이트하는 함수
UIEmployment:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 함수
UIEmployment:HandleButtonClickEvent2 -- 확인 버튼 클릭 이벤트를 처리하는 함수
UIEmployment:HandleButtonClickEvent3 -- 고용 UI 열기 버튼 클릭 이벤트를 처리하는 함수
UIEmployment:HandleButtonClickEvent5 -- 고용 취소 버튼 클릭 이벤트를 처리하는 함수
UIEmployment:HandleButtonClickEvent4 -- 직원 목록 확인 버튼 클릭 이벤트를 처리하는 함수
UIEmployment:HandleButtonClickEvent6 -- 직원 관리 버튼 클릭 이벤트를 처리하는 함수
UIEmployment:HandleButtonClickEvent7 -- 리롤 버튼 클릭 이벤트를 처리하는 함수
UITransfer:CloseUI -- 이적 UI를 닫는 함수
UITransfer:OnClickOkButton -- 이적 확인 버튼 클릭 시 처리하는 함수
UITransfer:TransferChuChu -- 츄츄 이적을 실행하는 함수
UITransfer:OpenTransferUI -- 이적 UI를 열고 직원 정보를 설정하는 함수
UITransfer:SetInfo -- 이적 시 환급받을 하트와 젬 정보를 설정하는 함수
UITransfer:NotifyFinishTransfer -- 이적 완료 알림을 처리하는 함수
UITransfer:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 함수
UITransfer:HandleButtonClickEvent2 -- 확인 버튼 클릭 이벤트를 처리하는 함수
StoreRankingDataSetLogic:OnBeginPlay -- 게임 시작 시 상점 랭킹 데이터셋을 로드하는 함수
StoreRankingDataSetLogic:LoadDataSet -- CSV에서 상점 이름 데이터를 읽어와 메모리에 로드하는 함수
StoreRankingDataSetLogic:ReturnRandomStoreNameOfGrade -- 특정 등급에 맞는 랜덤 상점 이름을 반환하는 함수 (중복 제외)
StoreRankingDataSetLogic:ReturnIndexsByRanking -- 랭킹을 기준으로 표시할 랭킹 범위의 시작과 끝 인덱스를 반환하는 함수
StoreRankingDataSetLogic:ReturnPlayerUserRankingScore -- 플레이어의 랭킹 점수(최고 수익)를 반환하는 함수
StoreRankingDataSetLogic:ReturnPlayerUserRankingByScore -- 점수를 기준으로 플레이어의 예상 랭킹을 계산하여 반환하는 함수
StoreRankingDataSetLogic:ReturnRewardDataByRanking -- 랭킹에 따른 보상 데이터를 반환하는 함수
StoreRankingDataSetLogic:ReturnScoreByRanking -- 랭킹을 기준으로 해당 랭킹에 필요한 점수를 계산하여 반환하는 함수
StoreRankingDataSetLogic:ResetRankingSpeechText -- 플레이어의 랭킹 코멘트 텍스트를 UI에 재설정하는 함수
StoreRankingDataSetLogic:GetRankFlowType -- 랭킹 변화 유형을 문자열로 반환하는 함수 (1위, 상승, 동일, 하락)
StoreRankingDataSetLogic:RefreshRankingRedDot -- 랭킹 재심사 가능 여부에 따라 레드닷을 표시하는 함수
StoreRankingDataSetLogic:GetRankingReexamCost -- 플레이어의 현재 랭킹에 따른 재심사 비용을 반환하는 함수
StoreRankingDataSetLogic:HandleBestEarningRecordChangedEvent -- 최고 수익 기록이 변경될 때 랭킹 레드닷을 갱신하는 이벤트 핸들러
StoreRankingRewardData:Load -- CSV 데이터 행에서 랭킹 보상 정보를 로드하는 함수
StoreRankingRewardData:GetAdjustedReward -- 플레이어의 정확한 랭킹에 따라 조정된 보상을 계산하여 반환하는 함수
UIStoreRanking:Open -- 상점 랭킹 UI를 열고 모든 관련 데이터를 갱신하는 함수
UIStoreRanking:Close -- 상점 랭킹 UI를 닫는 함수
UIStoreRanking:RefreshRankingStatus -- 플레이어의 랭킹 상태를 갱신하고 랭킹 리스트를 표시하는 함수
UIStoreRanking:RefreshRank1Data -- 1위 랭커의 정보를 갱신하여 표시하는 함수 (플레이어가 1위인지 라이벌인지에 따라 다르게 표시)
UIStoreRanking:ClearAvatarCostume -- 아바타의 모든 커스텀 코스튬을 초기화하는 함수
UIStoreRanking:RefreshReexamButton -- 재심사 버튼의 상태와 비용 정보를 갱신하는 함수
UIStoreRanking:HandleButtonClickEvent -- 랭킹 UI 열기 버튼 클릭 이벤트 핸들러
UIStoreRanking:HandleButtonClickEvent2 -- 랭킹 UI 닫기 버튼 클릭 이벤트 핸들러
UIStoreRanking:HandleTextInputEndEditEvent -- 랭킹 코멘트 텍스트 입력 완료 이벤트 핸들러
UIStoreRanking:HandleButtonClickEvent3 -- 랭킹 재심사 버튼 클릭 이벤트 핸들러
UIStoreRankingSlotRenderer:Init -- UI 엘리먼트들을 초기화하는 함수
UIStoreRankingSlotRenderer:RefreshInfo -- 랭킹 슬롯의 정보를 갱신하고 스타일을 적용하는 함수
GuideContentListData:Load -- 데이터 테이블에서 가이드 컨텐츠 정보를 로드하여 속성에 저장하는 함수
GuidePageController:OnBeginPlay -- 가이드 페이지 컨트롤러 초기화 및 닫기 버튼 이벤트 연결하는 함수
GuidePageController:ContentDataSet -- 페이지 ID에 해당하는 가이드 컨텐츠 데이터를 로드하고 UI 엔티티를 생성하는 함수
GuidePageController:SetButton -- 가이드 페이지를 열기 위한 버튼 엔티티를 설정하고 클릭 이벤트를 연결하는 함수
GuidePageController:Open -- 가이드 페이지를 열고 사운드 재생 및 UI 상태를 변경하는 함수
GuidePageController:Close -- 가이드 페이지를 닫고 사운드 재생 및 UI 상태를 복원하는 함수
GuidePageController:OnUpdate -- 스크롤 위치에 따라 화살표 표시 여부를 결정하는 업데이트 함수
GuidePageController:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하여 가이드 페이지를 닫는 핸들러 함수
GuidePageListData:Load -- 데이터 테이블에서 가이드 페이지 정보를 로드하여 속성에 저장하는 함수
GuidePageManager:OnBeginPlay -- 가이드 페이지 매니저 초기화 및 모든 가이드 버튼들을 설정하는 함수
GuidePageManager:LoadDataSet -- 가이드 페이지 목록 데이터셋을 로드하여 내부 테이블에 저장하는 함수
GuidePageManager:GuideUIGroupEnable -- 가이드 UI 그룹의 활성화 상태를 설정하는 함수
GuidePageManager:SetGuidePage -- 특정 가이드 페이지를 설정하고 열기 버튼을 연결하는 함수
GuidePageManager:SetGuidePageButton -- 가이드 페이지 버튼에 클릭 이벤트를 연결하는 함수
GuidePageManager:OpenGuidePage -- 지정된 페이지 ID의 가이드 페이지를 열고 컨텐츠를 로드하는 함수
CustomAvatarData:Load -- 데이터 테이블에서 커스텀 아바타 정보를 로드하여 속성들을 설정하는 함수
CustomAvatarData:SetAvatarCostume -- 커스텀 아바타의 코스튬 정보를 CostumeManagerComponent에 적용하는 함수
DialogLineData:Init -- 다이얼로그 라인 데이터를 초기화하고 CSV 데이터로부터 속성들을 설정하는 함수
AvatarEmotionLogic:GetEmotionType -- 문자열 감정 타입을 EmotionalType 열거형으로 변환하는 함수
DialogDataLogic:Load -- 다이얼로그 데이터와 커스텀 아바타 데이터를 CSV에서 로드하여 테이블에 저장하는 함수
DialogDataLogic:GetDialogTable -- 다이얼로그 ID에 해당하는 다이얼로그 테이블을 반환하는 함수
DialogDataLogic:GetFirstLineId -- 다이얼로그 ID의 첫 번째 라인 ID를 반환하는 함수
DialogDataLogic:ChangeDefinitionWord -- 메시지 텍스트에서 특수 키워드를 실제 값으로 치환하고 하이라이트 정보를 추출하는 함수
DialogDataLogic:SetHighlight -- 텍스트에 하이라이트 색상 태그를 적용하는 함수
DialogDataLogic:OnBeginPlay -- 게임 시작 시 다이얼로그 데이터를 로드하는 함수
IntroDialogLogic:EnableUIDialogGroup -- 다이얼로그 UI 그룹의 활성화 상태를 설정하는 함수
IntroDialogLogic:ResetActor -- 인트로 관련 액터들을 초기 상태로 리셋하는 함수
IntroDialogLogic:StartIntro -- 인트로 시퀀스를 시작하고 카메라, 페이드, 캡션을 설정하는 함수
IntroDialogLogic:StartCutSceneIntro -- 컷신 인트로를 시작하고 유튜브 비디오를 재생하는 함수
IntroDialogLogic:StopYoutubeVideo -- 유튜브 비디오 재생을 중단하고 플레이어를 비활성화하는 함수
IntroDialogLogic:EndCutSceneIntro -- 컷신 인트로를 종료하고 다음 단계로 전환하는 함수
IntroDialogLogic:StartIntro2 -- 두 번째 인트로 다이얼로그를 시작하는 함수
IntroDialogLogic:StartPlayPopup -- 게임 시작 팝업을 생성하고 표시하는 함수
IntroDialogLogic:SkipIntroDialog1 -- 첫 번째 인트로 다이얼로그를 스킵하는 함수
IntroDialogLogic:SkipCutScene -- 컷신을 스킵하고 다음 단계로 이동하는 함수
IntroDialogLogic:SkipIntroDialog2 -- 두 번째 인트로 다이얼로그를 스킵하는 함수
IntroDialogLogic:EndIntro -- 인트로를 완전히 종료하고 게임으로 전환하는 함수
IntroDialogLogic:StartOutro -- 아웃트로 시퀀스를 시작하는 함수
IntroDialogLogic:EndOutro -- 아웃트로를 종료하고 게임 상태를 복원하는 함수
IntroDialogLogic:SetOutroYear -- 아웃트로에서 사용할 연도를 설정하는 함수
IntroDialogLogic:ShowFade1 -- 페이드 인/아웃 효과를 실행하는 함수 (타입 1)
IntroDialogLogic:ShowFade2 -- 페이드 인 효과만 실행하는 함수 (타입 2)
IntroDialogLogic:SetIntroCamera -- 인트로용 카메라로 전환하고 줌 비율을 설정하는 함수
IntroDialogLogic:PlayCameraWalk1 -- 첫 번째 카메라 워킹 애니메이션을 재생하는 함수
IntroDialogLogic:PlayCameraWalk2 -- 두 번째 카메라 워킹 애니메이션을 재생하는 함수
IntroDialogLogic:SkipPictureShow -- 그림 표시를 스킵하고 배경을 리셋하는 함수
IntroDialogLogic:ShowPickture -- 인트로 그림을 화면에 표시하고 애니메이션을 재생하는 함수
IntroDialogLogic:StartIntroOpeningCaption -- 인트로 오프닝 캡션을 시작하는 함수
IntroDialogLogic:EndIntroOpeningCaption -- 인트로 오프닝 캡션을 종료하고 다이얼로그를 시작하는 함수
IntroDialogLogic:OnBeginPlay -- 게임 시작 시 인트로 관련 초기화를 수행하는 함수
IntroDialogLogic:DialogDimFade -- 다이얼로그 딤 효과를 페이드 인/아웃하는 함수
IntroDialogLogic:DialogDimShow -- 다이얼로그 딤을 즉시 표시하는 함수
IntroDialogSkipButton:HandleButtonClickEvent -- 스킵 버튼 클릭 시 현재 다이얼로그 상태에 따라 적절한 스킵 동작을 수행하는 핸들러
IntroOpeningCaption:Init -- 인트로 오프닝 캡션을 초기화하고 텍스트 엔티티들을 생성하는 함수
IntroOpeningCaption:SetData -- 다음 캡션 텍스트 데이터를 설정하고 타이핑 효과를 시작하는 함수
IntroOpeningCaption:OnPrintEnd -- 현재 캡션의 타이핑 효과를 종료하고 다음 캡션으로 넘어가는 함수
IntroOpeningCaption:Close -- 캡션을 닫고 모든 텍스트 엔티티들을 초기화하는 함수
IntroOpeningCaption:OnUpdate -- 매 프레임마다 타이핑 효과를 업데이트하는 함수
IntroOpeningCaption:OnBeginPlay -- 게임 시작 시 캡션 엔티티를 비활성화하는 함수
IntroStartPlayBtnComponent:HandleButtonClickEvent -- 게임 시작 버튼 클릭 시 인트로를 종료하고 게임을 시작하는 핸들러
PortraitTypeEnum:ToInt -- 문자열 포트레이트 타입을 정수 값으로 변환하는 함수
UIDialogLogic:MakeDialog -- 다이얼로그를 생성하고 시작하는 함수
UIDialogLogic:Init -- 다이얼로그 시스템을 초기화하는 함수
UIDialogLogic:GetNextLine -- 다음 다이얼로그 라인으로 진행하거나 다이얼로그를 종료하는 함수
UIDialogLogic:EndDialog -- 다이얼로그를 종료하고 콜백 함수를 호출하는 함수
UIDialogLogic:SetHUDOnDialog -- 다이얼로그 상태에 따라 HUD와 UI 요소들의 표시 상태를 설정하는 함수
UIDialogPanel:Open -- 다이얼로그 패널을 열고 데이터를 설정하는 함수
UIDialogPanel:SetData -- 다이얼로그 데이터를 설정하고 포트레이트, 텍스트, 선택지를 업데이트하는 함수
UIDialogPanel:OnClickNext -- 다음 버튼 클릭 시 처리하는 함수 (타이핑 완료 또는 다음 라인으로 진행)
UIDialogPanel:Close -- 다이얼로그 패널을 닫고 관련 상태를 초기화하는 함수
UIDialogPanel:OnSelect -- 선택지를 선택했을 때 처리하는 함수
UIDialogPanel:OnUpdate -- 매 프레임마다 타이핑 효과를 업데이트하는 함수
UIDialogPanel:SetSelect -- 선택지 UI를 설정하고 표시하는 함수
UIDialogPanel:Init -- UI 요소들을 초기화하고 이벤트를 연결하는 함수
UIDialogPanel:OnPrintEnd -- 타이핑 효과를 종료하고 선택지를 활성화하는 함수
UIDialogPanel:StopTween -- 선택지 관련 트윈과 타이머를 정리하는 함수
UIDialogPanel:ChangeCurSelect -- 현재 선택된 선택지를 위/아래로 변경하는 함수
UIDialogPanel:SetSelected -- 특정 선택지 아이템의 선택 상태를 설정하는 함수
UIDialogPanel:HandleKeyDownEvent -- 키보드 입력을 처리하는 핸들러 (스페이스바, 방향키)
PlayerDiamondChangedEvent:Init -- 플레이어 다이아몬드 변경 이벤트를 초기화하는 함수
SideMenuData:Load -- CSV 데이터를 읽어서 사이드메뉴 데이터를 로드하는 함수
StageConfigData:Load -- CSV 데이터를 읽어서 스테이지 설정 데이터를 로드하는 함수
StageData:Load -- CSV 데이터를 읽어서 스테이지 데이터를 로드하고 관련 데이터들을 초기화하는 함수
StageData:GetStageEarningLevelData -- 수익 레벨에 해당하는 스테이지 수익 데이터를 반환하는 함수
StageData:GetStageRankingData -- 인덱스에 해당하는 스테이지 랭킹 데이터를 반환하는 함수
StageData:GetReputationManagementData -- 경영 레벨에 해당하는 평판 관리 데이터를 반환하는 함수
StageData:GetVIPOrderRequirementData -- 경영 레벨과 버거 스택에 해당하는 VIP 주문 요구사항 데이터를 반환하는 함수
StageData:GetVIPOrderRecipeRewardData -- 경영 레벨에 해당하는 VIP 주문 레시피 보상 데이터를 반환하는 함수
StageDataSetLogic:OnBeginPlay -- 게임 시작 시 스테이지 데이터를 로드하는 함수
StageDataSetLogic:LoadDataSet -- CSV에서 스테이지 데이터를 읽어와 초기화하는 함수
StageDataSetLogic:GetStageData -- 스테이지 ID에 해당하는 스테이지 데이터를 반환하는 함수
StageDataSetLogic:GetStageOnlyIngredient -- 해당 스테이지에서만 얻을 수 있는 재료 목록을 반환하는 함수
StageDataSetLogic:GetStageTotalIngredient -- 해당 스테이지에서 사용 가능한 모든 재료 목록을 반환하는 함수
StageDataSetLogic:GetStageCollectionRate -- 스테이지 컬렉션 수집률을 계산하여 반환하는 함수
StageDataSetLogic:GetLastStageId -- 현재 열려있는 마지막 스테이지 ID를 반환하는 함수
StageDataSetLogic:GetStageClearProgress -- 스테이지 클리어에 필요한 진행도를 반환하는 함수
StageDataSetLogic:OpenStageClearRewardUI -- 스테이지 클리어 보상 UI를 여는 함수
StageSettingEnum:OnBeginPlay -- 스테이지 설정 메뉴 열거형을 초기화하는 함수
StageSettingEnum:GetIndexByKey -- 키 문자열로 해당하는 열거형 인덱스를 찾아 반환하는 함수
StrategyData:Load -- CSV 데이터를 읽어서 전략 데이터를 로드하는 함수
StrategyData:GetLevelEffect -- 전략의 레벨과 스테이지에 따른 효과 수치를 계산하여 반환하는 함수
StrategyDataSetLogic:OnBeginPlay -- 게임 시작 시 전략 및 사이드메뉴 데이터를 로드하는 함수
StrategyDataSetLogic:LoadDataSet -- CSV에서 전략 및 사이드메뉴 데이터를 읽어와 초기화하는 함수
StrategyDataSetLogic:GetStrategyData -- ID에 해당하는 전략 데이터를 반환하는 함수
StrategyDataSetLogic:GetSideMenuData -- ID에 해당하는 사이드메뉴 데이터를 반환하는 함수
StrategyDataSetLogic:GetStrategyDescText -- 전략의 설명 텍스트를 포맷팅하여 반환하는 함수
StrategyDataSetLogic:GetSideMenuDescText -- 사이드메뉴의 설명 텍스트를 포맷팅하여 반환하는 함수
StrategyDataSetLogic:GetStrategyEffectDescText -- 전략의 효과 설명 텍스트를 포맷팅하여 반환하는 함수
StrategyDataSetLogic:SetSideMenuIconPos -- 사이드메뉴 아이콘의 위치를 설정하는 함수
StrategyEnum:GetPlayerStrategyEffect -- 플레이어가 설정한 전략의 효과를 계산하여 반환하는 함수
StrategyEnum:GetSideMenuEffect -- 사이드메뉴의 효과를 계산하여 반환하는 함수
SideMenuSettingChangedEvent:Init -- 사이드메뉴 설정 변경 이벤트를 초기화하는 함수
StrategySettingChangedEvent:Init -- 전략 설정 변경 이벤트를 초기화하는 함수
UICurrentSideMenuSlot:Init -- UI 컴포넌트들을 초기화하고 이벤트를 연결하는 함수
UICurrentSideMenuSlot:Refresh -- 사이드메뉴 슬롯 UI를 새로고침하는 함수
UICurrentStrategySlot:Init -- UI 컴포넌트들을 초기화하고 이벤트를 연결하는 함수
UICurrentStrategySlot:Refresh -- 현재 전략 슬롯 UI를 새로고침하는 함수
UICurrentStrategySlot:GetGoodsIcon -- 관련 아이템에 따른 아이콘 RUID를 반환하는 함수
UISideMenuReward:Open -- 사이드메뉴 보상 UI를 여는 함수
UISideMenuReward:MoveNext -- 다음 보상 단계로 이동하는 함수
UISideMenuReward:Close -- 사이드메뉴 보상 UI를 닫는 함수
UISideMenuReward:Refresh -- 보상 UI를 새로고침하는 함수
UISideMenuReward:HandleButtonClickEvent -- 보상 구매 버튼 클릭 이벤트를 처리하는 핸들러
UIStageClearRewardGroup:OnBeginPlay -- 컴포넌트 초기화 시 배경 원본 크기를 저장하는 함수
UIStageClearRewardGroup:Open -- 스테이지 클리어 보상 그룹을 여는 함수
UIStageClearRewardGroup:Close -- 스테이지 클리어 보상 그룹을 닫는 함수
UIStageClearRewardGroup:Refresh -- UI를 새로고침하고 현재 인덱스에 맞는 보상을 표시하는 함수
UIStageClearRewardGroup:ClearUI -- UI 요소들을 초기화하고 숨기는 함수
UIStageClearRewardGroup:ChangeTitleText -- 인덱스에 맞는 제목 텍스트로 변경하고 페이드인 효과를 적용하는 함수
UIStageClearRewardGroup:MoveToIndex -- 지정된 인덱스로 이동하고 UI를 새로고침하는 함수
UIStageClearRewardGroup:SetCanMoveNext -- 다음 단계로 이동할 수 있도록 설정하는 함수
UIStageClearRewardGroup:OpenAnim -- 열기 애니메이션을 실행하고 지속시간을 반환하는 함수
UIStageClearRewardGroup:ClearAnim -- UI를 지우는 애니메이션을 실행하고 지속시간을 반환하는 함수
UIStageClearRewardGroup:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하여 다음 단계로 이동하는 핸들러
UIStageClearRewardGroup:HandleKeyDownEvent -- 키 다운 이벤트를 처리하는 핸들러
UIStageInfo:OnBeginPlay -- 컴포넌트 초기화 시 탭과 페이지를 설정하는 함수
UIStageInfo:Open -- 스테이지 정보 UI를 여는 함수
UIStageInfo:Close -- 스테이지 정보 UI를 닫는 함수
UIStageInfo:SetSelectTab -- 선택된 탭을 설정하는 함수
UIStageInfo:OnSelectTab -- 탭 선택 시 UI 상태를 변경하는 함수
UIStageInfo:Apply -- 선택된 탭에 따라 페이지를 적용하는 함수
UIStageInfo:SetStageTitle -- 스테이지 제목을 설정하는 함수
UIStageInfo:HandleButtonClickEvent -- 첫 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageInfo:HandleButtonClickEvent2 -- 두 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageInfo:HandleButtonClickEvent3 -- 세 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageInfo:HandleButtonClickEvent4 -- 네 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageInfoEmployee:Init -- UI 컴포넌트들을 초기화하는 함수
UIStageInfoEmployee:Refresh -- 직원 정보를 새로고침하는 함수
UIStageInfoIngredient:Init -- UI 컴포넌트들을 초기화하는 함수
UIStageInfoIngredient:Refresh -- 재료 정보를 새로고침하는 함수
UIStageInfoStage:Init -- UI 컴포넌트들을 초기화하고 이벤트를 연결하는 함수
UIStageInfoStage:Refresh -- 스테이지 정보를 새로고침하는 함수
UIStageInfoStrategy:Init -- UI 컴포넌트들을 초기화하는 함수
UIStageInfoStrategy:Refresh -- 전략 정보를 새로고침하는 함수
UIStageInfoStrategy:GetGoodsIcon -- 관련 상품에 따른 아이콘을 반환하는 함수
UIStageRewardClear:StartRender -- 스테이지 클리어 보상 렌더링을 시작하는 함수
UIStageRewardClear:PlayAnim -- 보상 애니메이션을 재생하는 함수
UIStageRewardClear:SetInfo -- 스테이지 정보를 설정하는 함수
UIStageRewardClear:ClearUI -- UI를 초기화하는 함수
UIStageRewardSideMenu:StartRender -- 사이드메뉴 보상 렌더링을 시작하는 함수
UIStageRewardSideMenu:PlayAnim -- 사이드메뉴 보상 애니메이션을 재생하는 함수
UIStageRewardSideMenu:SetInfo -- 사이드메뉴 정보를 설정하는 함수
UIStageRewardSideMenu:ClearUI -- UI를 초기화하는 함수
UIStageRewardSideMenu:OnBeginPlay -- 게임 시작 시 트레이 원점 위치를 저장하는 함수
UIStageRewardStrategy:StartRender -- 전략 보상 렌더링을 시작하는 함수
UIStageRewardStrategy:PlayAnim -- 전략 보상 애니메이션을 재생하는 함수
UIStageRewardStrategy:SetInfo -- 전략 정보를 설정하는 함수
UIStageRewardStrategy:ClearUI -- UI를 초기화하는 함수
UIStageSelect:OnBeginPlay -- 컴포넌트 초기화 시 UI를 비활성화하는 함수
UIStageSelect:Open -- 스테이지 선택 UI를 여는 함수
UIStageSelect:Close -- 스테이지 선택 UI를 닫는 함수
UIStageSelect:Refresh -- 스테이지 목록을 새로고침하는 함수
UIStageSelect:OnSelectSlot -- 스테이지 슬롯을 선택했을 때 처리하는 함수
UIStageSelect:RefreshChustarLevel -- 츄스타 레벨을 새로고침하는 함수
UIStageSelect:HandleButtonClickEvent -- 첫 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSelect:HandleButtonClickEvent2 -- 두 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSelect:HandleButtonClickEvent3 -- 세 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSelect:HandleButtonClickEvent4 -- 네 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSelect:HandleButtonClickEvent5 -- 다섯 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSelect:HandleButtonClickEvent6 -- 여섯 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSelect:HandleButtonClickEvent7 -- 일곱 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSelect:HandleButtonClickEvent8 -- 여덟 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSelectSlot:Init -- UI 컴포넌트들을 초기화하는 함수
UIStageSelectSlot:Refresh -- 스테이지 슬롯을 새로고침하는 함수
UIStageSelectSlot:IsComplete -- 스테이지가 완료되었는지 확인하는 함수
UIStageSelectSlot:IsLocked -- 스테이지가 잠겨있는지 확인하는 함수
UIStageSelectSlot:SetStageComingSoon -- 스테이지 출시 예정 상태를 설정하는 함수
UIStageSetting:OnBeginPlay -- 컴포넌트 초기화 시 페이지와 네비게이터를 설정하는 함수
UIStageSetting:Open -- 스테이지 설정 UI를 열고 초기화하는 함수
UIStageSetting:Close -- 스테이지 설정 UI를 닫고 정리하는 함수
UIStageSetting:RefreshSetting -- 설정 페이지를 새로고침하고 표시하는 함수
UIStageSetting:OnMoveNext -- 다음 페이지로 이동하는 함수
UIStageSetting:OnMovePrevious -- 이전 페이지로 이동하는 함수
UIStageSetting:OnDone -- 설정 완료 시 처리하는 함수
UIStageSetting:GetDataFromClient -- 클라이언트에서 설정 데이터를 가져오는 함수
UIStageSetting:RefreshStageInfoBar -- 스테이지 정보 바를 새로고침하는 함수
UIStageSetting:ResetSetting -- 설정을 초기화하는 함수
UIStageSetting:MoveNavigator -- 네비게이터를 이동시키는 함수
UIStageSetting:MoveIndicatorTo -- 인디케이터를 특정 위치로 이동시키는 함수
UIStageSetting:HandleButtonClickEvent -- 다음 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSetting:HandleButtonClickEvent2 -- 이전 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSetting:HandleButtonClickEvent3 -- 완료 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSetting:HandleButtonClickEvent4 -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSettingEmployee:Init -- UI 컴포넌트들을 초기화하고 이벤트를 연결하는 함수
UIStageSettingEmployee:Refresh -- 직원 선택 UI를 새로고침하는 함수
UIStageSettingEmployee:RefreshCookSlot -- 요리사 슬롯을 새로고침하는 함수
UIStageSettingEmployee:RefreshServingSlot -- 서빙 직원 슬롯을 새로고침하는 함수
UIStageSettingEmployee:SetSlot -- 직원 슬롯을 설정하는 함수
UIStageSettingIngredient:Init -- UI 컴포넌트들을 초기화하는 함수
UIStageSettingIngredient:Refresh -- 스테이지 설정 재료 정보를 새로고침하는 함수
UIStageSettingIngredient:RefreshPromotedIngres -- 추천 재료 목록을 새로고침하는 함수
UIStageSettingIngredient:SetPromotedIngres -- 추천 재료를 설정하는 함수
UIStageSettingIngredient:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSettingStageInfo:Init -- UI 컴포넌트들을 초기화하는 함수
UIStageSettingStageInfo:Refresh -- 스테이지 정보를 새로고침하는 함수
UIStageSettingStageInfo:OpenAnim -- 열기 애니메이션을 실행하는 함수
UIStageSettingStrategy:OnBeginPlay -- 컴포넌트 초기화 시 탭과 리사이클 뷰를 설정하는 함수
UIStageSettingStrategy:Open -- 전략 설정 UI를 여는 함수
UIStageSettingStrategy:SetSelectTab -- 선택된 탭을 설정하는 함수
UIStageSettingStrategy:OnSelectTab -- 탭 선택 시 UI 상태를 변경하는 함수
UIStageSettingStrategy:Apply -- 선택된 탭에 따라 데이터를 적용하는 함수
UIStageSettingStrategy:Refresh -- 전략 설정 UI를 새로고침하는 함수
UIStageSettingStrategy:RefreshSPBar -- SP 바를 새로고침하는 함수
UIStageSettingStrategy:RefreshCurrentSideMenuSlot -- 현재 사이드메뉴 슬롯을 새로고침하는 함수
UIStageSettingStrategy:RequestSetStrategy -- 전략 설정을 요청하는 함수
UIStageSettingStrategy:RequestSetSideMenu -- 사이드메뉴 설정을 요청하는 함수
UIStageSettingStrategy:ResetData -- 설정 데이터를 초기화하는 함수
UIStageSettingStrategy:RequestUnsetSideMenu -- 사이드메뉴 설정 해제를 요청하는 함수
UIStageSettingStrategy:RequestUnsetStrategy -- 전략 설정 해제를 요청하는 함수
UIStageSettingStrategy:SetUsedSP -- 사용된 SP를 계산하여 설정하는 함수
UIStageSettingStrategy:SetPassBtnRedDot -- 패스 버튼의 빨간 점을 설정하는 함수
UIStageSettingStrategy:RefreshSideMenuTabRedDot -- 사이드메뉴 탭의 빨간 점을 새로고침하는 함수
UIStageSettingStrategy:HandleButtonClickEvent -- 첫 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSettingStrategy:HandleButtonClickEvent2 -- 두 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIStageSettingStrategy:HandleStrategySettingChangedEvent -- 전략 설정 변경 이벤트를 처리하는 핸들러
UIStageSettingStrategy:HandleSideMenuSettingChangedEvent -- 사이드메뉴 설정 변경 이벤트를 처리하는 핸들러
UIStageSettingStrategy:HandlePlayerSPChangedEvent -- 플레이어 SP 변경 이벤트를 처리하는 핸들러
UIStartStageToast:OnBeginPlay -- 컴포넌트 초기화 시 UI를 비활성화하는 함수
UIStartStageToast:Init -- UI 컴포넌트들을 초기화하는 함수
UIStartStageToast:Open -- 스테이지 시작 토스트 UI를 여는 함수
UIStartStageToast:StartRender -- 토스트 애니메이션을 시작하는 함수
UIStartStageToast:OnEndPlay -- 컴포넌트 종료 시 타이머를 정리하는 함수
UIStartStageToast:HandleKeyDownEvent -- 키 입력 이벤트를 처리하는 핸들러
UIStrategySlot:Init -- UI 컴포넌트들을 초기화하고 이벤트를 연결하는 함수
UIStrategySlot:Refresh -- 전략 또는 사이드메뉴 슬롯을 새로고침하는 함수
UIStrategySlot:RefreshStrategy -- 전략 슬롯을 새로고침하는 함수
UIStrategySlot:RefreshSideMenu -- 사이드메뉴 슬롯을 새로고침하는 함수
UIStrategySlot:GetGoodsIcon -- 관련 아이템에 따른 아이콘 RUID를 반환하는 함수
UIStrategySlot:GetSideMenuOpened -- 사이드메뉴가 열려있는지 확인하는 함수
UIStrategySlot:HandleStrategySettingChangedEvent -- 전략 설정 변경 이벤트를 처리하는 핸들러
UIStrategySlot:HandleSideMenuSettingChangedEvent -- 사이드메뉴 설정 변경 이벤트를 처리하는 핸들러
UICollectionLogic:EnableIngreBunCollectionSlotRewardDot -- 재료/번 컬렉션 슬롯의 보상 점을 활성화/비활성화하고 트윈 애니메이션을 처리하는 함수
UICollectionLogic:DropDiamondAndMoveToMoneyBar -- 다이아몬드 아이콘을 생성하여 머니바로 이동시키는 트윈 애니메이션을 실행하는 함수
UICollectionLogic:SetIngreBunCollectionMenuBtnRedDot -- 메인 메뉴의 재료/번 컬렉션 버튼에 빨간 점 표시 여부를 설정하는 함수
UICollectionLogic:DropDiamondAndMoveToMoneyBar_ChuchuCollection -- 츄츄 컬렉션용 다이아몬드 아이콘을 생성하여 머니바로 이동시키는 트윈 애니메이션 함수
UICollectionLogic:RequestPlayGetAllRewardBtnAnim -- 모든 보상 받기 버튼 애니메이션을 실행하는 함수
UIIngreBunCollection:OnBeginPlay -- 컴포넌트 초기화 시 탭, 필터, 정렬 옵션들을 설정하는 함수
UIIngreBunCollection:Open -- 재료/번 컬렉션 UI를 열고 지정된 탭으로 설정하는 함수
UIIngreBunCollection:Close -- 재료/번 컬렉션 UI를 닫는 함수
UIIngreBunCollection:SetSelectTab -- 선택된 탭을 변경하고 관련 UI를 갱신하는 함수
UIIngreBunCollection:OnSelectTab -- 탭 선택 시 탭 UI의 시각적 상태를 업데이트하는 함수
UIIngreBunCollection:Apply -- 선택된 탭에 맞는 데이터를 적용하고 UI를 갱신하는 함수
UIIngreBunCollection:RefreshList -- 선택된 탭에 맞는 아이템 리스트를 생성하고 정렬하여 화면에 표시하는 함수
UIIngreBunCollection:SetFilter -- 필터 조건을 설정하고 필요시 리스트를 갱신하는 함수
UIIngreBunCollection:SetSort -- 정렬 조건을 설정하고 필요시 리스트를 갱신하는 함수
UIIngreBunCollection:SetEnableFilterArea -- 필터 선택 영역의 활성화 상태를 설정하는 함수
UIIngreBunCollection:SetEnableSortArea -- 정렬 선택 영역의 활성화 상태를 설정하는 함수
UIIngreBunCollection:GetDrawList -- 선택된 탭에 따라 필터링된 아이템 리스트를 반환하는 함수
UIIngreBunCollection:OnClickSlot -- 컬렉션 슬롯 클릭 시 보상 수령 처리 및 선택 상태 업데이트 함수
UIIngreBunCollection:RefreshDetail -- 선택된 아이템의 상세 정보를 표시하는 함수
UIIngreBunCollection:CheckCanGetReward -- 보상 받기 버튼 상태와 탭별 빨간 점 표시를 확인하고 설정하는 함수
UIIngreBunCollection:OnGetAllRewardButtonClicked -- 모든 보상 받기 버튼 클릭 시 해당 탭의 모든 수령 가능한 보상을 처리하는 함수
UIIngreBunCollection:ReturnCanGetReward -- 지정된 탭에서 수령 가능한 보상이 있는지 확인하여 반환하는 함수
UIIngreBunCollection:RefreshSubBar -- 선택된 탭에 맞는 서브 바 UI를 갱신하는 함수
UIIngreBunCollection:RefreshCollectionProgress -- 선택된 탭의 컬렉션 진행률을 계산하고 표시하는 함수
UIIngreBunCollection:GetTabIcon -- 선택된 탭에 맞는 아이콘 RUID를 반환하는 함수
UIIngreBunCollection:GetTabName -- 선택된 탭에 맞는 탭 이름을 반환하는 함수
UIIngreBunCollection:HandleButtonClickEvent -- 컬렉션 열기 버튼 클릭 이벤트 핸들러
UIIngreBunCollection:HandleButtonClickEvent2 -- 컬렉션 닫기 버튼 클릭 이벤트 핸들러
UIIngreBunCollection:HandleButtonClickEvent3 -- 모든 보상 받기 버튼 클릭 이벤트 핸들러
UIIngreBunCollection:HandleButtonClickEvent4 -- 필터 버튼 클릭 이벤트 핸들러
UIIngreBunCollection:HandleButtonClickEvent5 -- 정렬 버튼 클릭 이벤트 핸들러
UIIngreBunCollectionDetailBun:Init -- 번 상세 정보 UI 컴포넌트들을 초기화하는 함수
UIIngreBunCollectionDetailBun:Refresh -- 지정된 번 ID의 상세 정보를 화면에 표시하는 함수
UIIngreBunCollectionDetailBunSkin:Init -- 번 스킨 상세 정보 UI 컴포넌트들을 초기화하는 함수
UIIngreBunCollectionDetailBunSkin:Refresh -- 지정된 번 스킨 ID의 상세 정보를 화면에 표시하는 함수
UIIngreBunCollectionDetailIngre:Init -- 재료 상세 정보 UI 컴포넌트들을 초기화하는 함수
UIIngreBunCollectionDetailIngre:Refresh -- 지정된 재료 ID의 상세 정보를 화면에 표시하는 함수
UIIngreBunCollectionSlot:OnBeginPlay -- 컴포넌트 초기화 시 UI 요소들을 참조하는 함수
UIIngreBunCollectionSlot:RefreshIngre -- 재료 컴렉션 슬롯의 데이터를 갱신하는 함수
UIIngreBunCollectionSlot:RefreshBun -- 번 컴렉션 슬롯의 데이터를 갱신하는 함수
UIIngreBunCollectionSlot:RefreshBunSkin -- 번 스킨 컴렉션 슬롯의 데이터를 갱신하는 함수
UIIngreBunCollectionSlot:EnableSelected -- 슬롯의 선택 상태를 설정하는 함수
UIIngreBunCollectionSlot:HandleButtonClickEvent -- 슬롯 클릭 이벤트 핸들러
BadgeData:Load -- CSV 데이터 테이블에서 배지 정보를 로드하고 초기화하는 함수
BadgeDataSetLogic:OnBeginPlay -- 게임 시작 시 배지 데이터를 로드하는 초기화 함수
BadgeDataSetLogic:LoadDataSet -- CSV에서 배지 데이터를 읽어와 메모리에 저장하는 함수
BadgeDataSetLogic:GetBadgeData -- 배지 ID로 해당 배지 데이터를 반환하는 함수
BadgeDataSetLogic:GetBadgeListByTypeId -- 특정 타입 ID에 해당하는 배지 목록을 필터링해서 반환하는 함수
BadgeEnum:SetStageEmployeeCollectProgress -- 스테이지별 직원 수집 진행도를 업데이트하는 함수
BadgeEnum:SetRecipeTagGradeProgress -- 레시피 태그별 등급 진행도를 업데이트하는 함수
UIBadgeList:OnBeginPlay -- UI 컴포넌트 초기화 및 이벤트 연결을 수행하는 함수
UIBadgeList:Open -- 배지 UI를 열고 초기 상태를 설정하는 함수
UIBadgeList:Close -- 배지 UI를 닫는 함수
UIBadgeList:SetSelectTab -- 선택된 탭을 변경하고 UI를 업데이트하는 함수
UIBadgeList:OnSelectTab -- 탭 선택 시 탭 UI 스타일을 업데이트하는 함수
UIBadgeList:SetFilter -- 필터를 설정하고 UI를 업데이트하는 함수
UIBadgeList:Refresh -- 현재 필터와 탭에 따라 배지 목록을 새로고침하는 함수
UIBadgeList:RefreshProgressBar -- 배지 수집 진행도 바를 업데이트하는 함수
UIBadgeList:HandleButtonClickEvent -- 배지 UI 열기 버튼 클릭 이벤트 핸들러
UIBadgeList:HandleButtonClickEvent2 -- 배지 UI 닫기 버튼 클릭 이벤트 핸들러
UIBadgeList:HandleButtonClickEvent3 -- 배지 UI 배경 클릭으로 닫기 이벤트 핸들러
UIBadgeSlot:Init -- UI 컴포넌트 참조를 초기화하는 함수
UIBadgeSlot:Refresh -- 배지 슬롯 UI를 배지 데이터로 업데이트하는 함수
ExchangeChuChuAnim:Load -- 교환 시스템에서 사용할 츄츄 애니메이션 데이터를 CSV에서 로드하는 함수
ExchangeDataSetLogic:OnBeginPlay -- 게임 시작 시 교환 관련 데이터셋을 로드하는 함수
ExchangeDataSetLogic:LoadDataSet -- 교환 재료와 츄츄 애니메이션 데이터를 CSV에서 로드하여 테이블에 저장하는 함수
ExchangeDataSetLogic:GetExchangeIngredientData -- 경영 레벨과 인덱스를 기반으로 교환 재료 데이터를 반환하는 함수
ExchangeDataSetLogic:GetExchangeChuChuData -- 스테이지와 인덱스를 기반으로 츄츄 애니메이션 데이터를 반환하는 함수
ExchangeIngredient:Load -- 교환 시스템에서 사용할 재료 데이터를 CSV에서 로드하고 인덱스를 계산하는 함수
ExchangeManager:GiveReward -- 교환 결과에 따라 플레이어에게 보상을 지급하고 비용을 차감하는 함수
ExchangeManager:CalculateReward -- 카드 결과에 따라 보너스 비율을 적용하여 최종 보상을 계산하는 함수
ExchangeManager:ExchangePlayFlow -- 교환 시스템 진입 로그를 기록하는 함수
MenuCardLogic:GetMenuImgRUID -- 메뉴 타입에 따라 적절한 이미지 RUID를 반환하는 함수
MenuCardLogic:GetEffectWord -- 카드 타입에 따라 효과 텍스트 이미지 RUID를 반환하는 함수
MenuCardLogic:GetImgOffset -- 메뉴 타입에 따라 이미지 오프셋 위치를 반환하는 함수
MenuCardLogic:GetBGRUID -- 메뉴 타입에 따라 배경 이미지 RUID를 반환하는 함수
MenuCardLogic:PlayEffectSound -- 카드 타입에 따라 적절한 효과 사운드를 재생하는 함수
MenuCardLogic:RandomChuChuRUID -- 현재 스테이지에 따라 랜덤한 츄츄 인덱스를 반환하는 함수
MenuCardLogic:GetMutoImgRUID -- 메뉴 타입에 따라 무토 캐릭터 이미지 RUID를 반환하는 함수
UIExchange:OnBeginPlay -- 교환 UI 초기화 시 메뉴 카드 타입 배열을 설정하는 함수
UIExchange:OpenExchangeUI -- 교환 UI를 열고 초기 설정을 수행하는 함수
UIExchange:CloseExchangeUI -- 교환 UI를 닫는 함수
UIExchange:InitMenuCard -- 메뉴 카드를 초기화하고 설정하는 함수
UIExchange:ShuffleMenuCard -- 메뉴 카드 타입을 랜덤하게 섮는 함수
UIExchange:OnClickMenuCard -- 메뉴 카드 클릭 시 처리하는 함수
UIExchange:ShowTray -- 선택된 메뉴를 트레이에 표시하는 함수
UIExchange:InitTray -- 트레이를 초기화하는 함수
UIExchange:ShowWordEffect -- 카드 선택 시 단어 효과를 보여주는 함수
UIExchange:ShowResult -- 교환 결과를 보여주는 함수
UIExchange:ShowRewardEffect -- 보상 효과를 보여주고 계산을 수행하는 함수
UIExchange:CalculateReward -- 카드 결과에 따라 최종 보상을 계산하는 클라이언트 함수
UIExchange:OnClickSkipBtn -- 스킵 버튼 클릭 시 효과를 건너뛰고 결과를 즈시 보여주는 함수
UIExchange:RequestReward -- 서버에 보상 지급을 요청하는 함수
UIExchange:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIExchange:HandleButtonClickEvent2 -- 두 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:OnBeginPlay -- 교환 설정 UI 초기화 시 재료 오브젝트를 로드하고 설정값을 설정하는 함수
UIExchangeSetting:OnClickHeartBtn -- 하트 보상 타입을 선택하고 UI를 업데이트하는 함수
UIExchangeSetting:OnClickCloverBtn -- 클로버 보상 타입을 선택하고 UI를 업데이트하는 함수
UIExchangeSetting:OnClickResetBtn -- 재료 개수를 1로 초기화하는 함수
UIExchangeSetting:OnClickMinusBtn -- 재료 개수를 1 감소시키는 함수
UIExchangeSetting:OnClickAddBtn -- 재료 개수를 1 증가시키는 함수
UIExchangeSetting:OnClickMaxBtn -- 재료 개수를 최대값인 10으로 설정하는 함수
UIExchangeSetting:SetExchangeType -- 교환 타입을 설정하는 함수
UIExchangeSetting:SetIngredients -- 재료 개수를 설정하고 UI를 업데이트하는 함수
UIExchangeSetting:SetReward -- 카드 보너스를 고려하여 보상 범위를 계산하고 UI에 표시하는 함수
UIExchangeSetting:SetIngredientCost -- 재료 비용을 계산하고 UI에 표시하는 함수
UIExchangeSetting:CalculateGold -- 재료 개수와 기본 금액을 기반으로 필요한 금액을 계산하는 함수
UIExchangeSetting:CloseExchangeSettingUI -- 교환 설정 UI를 닫고 초기화하는 함수
UIExchangeSetting:OpenExchangeSettingUI -- 교환 설정 UI를 열고 초기 설정을 수행하는 함수
UIExchangeSetting:OnClickStartBtn -- 교환 시작 버튼 클릭 시 유효성 검사 후 교환 UI를 여는 함수
UIExchangeSetting:GetDefaultGold -- 현재 스테이지와 경영 레벨에 따라 기본 금액을 가져오는 함수
UIExchangeSetting:CalculateReward -- 교환 타입과 재료 개수에 따라 보상을 계산하는 함수
UIExchangeSetting:HandleButtonClickEvent -- 첫 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:HandleButtonClickEvent2 -- 두 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:HandleButtonClickEvent3 -- 세 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:HandleButtonClickEvent4 -- 네 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:HandleButtonClickEvent5 -- 다섯 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:HandleButtonClickEvent6 -- 여섯 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:HandleButtonClickEvent7 -- 일곱 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:HandleButtonClickEvent8 -- 여덟 번째 버튼 클릭 이벤트를 처리하는 핸들러
UIExchangeSetting:HandleButtonClickEvent9 -- 아홉 번째 버튼 클릭 이벤트를 처리하는 핸들러
IngreSynthLogic:DrawIngreList -- 플레이어의 재료 카드를 필터링하여 재료 목록을 그리고 UI를 갱신하는 함수
IngreSynthLogic:RegisterRecycleScrollLayoutCallback -- 재료 목록의 리사이클 스크롤뷰 콜백을 등록하는 함수
IngreSynthLogic:RecycleScrollOnUpdateByIndex -- 리사이클 스크롤뷰에서 특정 인덱스의 슬롯을 갱신하는 함수
IngreSynthLogic:ReturnIngreGradeFromFilterType -- 필터 타입에 따라 재료 등급을 반환하는 함수
IngreSynthLogic:OnSelectIngreSlot -- 재료 슬롯을 선택했을 때 선택 목록에 추가하는 함수
IngreSynthLogic:OnDeselectIngreSlot -- 선택된 재료 슬롯을 해제하고 목록을 정리하는 함수
IngreSynthLogic:ResetAllSelectedIngreSlot -- 선택된 모든 재료 슬롯을 초기화하는 함수
IngreSynthLogic:SetMaxSlotCount -- 필터 타입에 따라 최대 슬롯 개수를 설정하는 함수
IngreSynthLogic:RefreshSelectedIngreListSlot -- 선택된 재료 목록 슬롯들을 갱신하는 함수
IngreSynthLogic:SetFilterType -- 재료 필터 타입을 설정하고 슬롯 개수를 조정하는 함수
IngreSynthLogic:CheckNoticePanelState -- 선택된 재료 개수에 따라 알림 패널과 합성 버튼 상태를 조정하는 함수
IngreSynthLogic:SetTagType -- 태그 번호에 따라 태그 타입을 설정하고 알림 패널 상태를 확인하는 함수
IngreSynthLogic:OnClickSynthBtn -- 합성 버튼 클릭 시 조건을 확인하고 합성을 요청하는 함수
IngreSynthLogic:RequestSynth -- 클라이언트에서 합성 요청을 받아 서버에서 합성을 실행하는 함수
IngreSynthLogic:IsChance -- 합성 대성공 확률을 계산하여 성공 여부를 반환하는 함수
IngreSynthLogic:Synth -- 실제 재료 합성을 수행하여 보상을 지급하는 함수
IngreSynthLogic:ReturnGrade -- 필터 타입에 따라 합성 결과물의 등급을 반환하는 함수
IngreSynthLogic:FinishSynth -- 합성 완료 후 보상 UI를 표시하고 초기 화면으로 돌아가는 함수
IngreSynthLogic:PlaySynthEffect -- 합성 효과를 재생하고 선택 목록을 비활성화하는 함수
IngreSynthLogic:AutoSet -- 재료를 자동으로 선택하여 슬롯을 채우는 함수
IngreSynthLogic:SetStateSynthBtn -- 합성 버튼의 활성화 상태와 디밍 상태를 설정하는 함수
IngreSynthLogic:LogIngreSynthResult -- 재료 합성 결과를 로그로 기록하는 함수
IngreSynthLogic:ReturnSelectedListEntityAndOffAnother -- 슬롯 개수에 따라 적절한 선택 목록 엔티티를 반환하는 함수
IngreSynthLogic:MakeIngrePool -- 필터와 태그에 따라 합성 가능한 재료 풀을 생성하는 함수
IngreSynthLogic:IngreSynthSimul -- 재료 합성을 여러 번 시뮬레이션하여 결과를 확인하는 함수
IngreSynthLogic:ReturnTagTypeString -- 태그 번호에 따라 해당하는 태그 타입 문자열을 반환하는 함수
IngreSynthLogic:CheatLog -- 디버그용 합성 결과 로그를 출력하는 함수
IngreSynthLogic:CountSelectedIngre -- 선택된 재료 목록에서 특정 재료의 선택 개수를 세는 함수
UIIngreSynthComponent:OnBeginPlay -- UI 컴포넌트 초기화 및 버튼 이벤트 등록을 수행하는 함수
UIIngreSynthComponent:OpenUI -- 재료 합성 UI를 열고 게임 시간을 정지하는 함수
UIIngreSynthComponent:CloseUI -- 재료 합성 UI를 닫고 게임 시간을 재개하는 함수
UIIngreSynthComponent:EnableNoticePanel -- 알림 패널을 활성화하고 상황에 따른 텍스트를 설정하는 함수
UIIngreSynthComponent:EnableFilterList -- 필터 목록을 활성화하고 첫 페이지 애니메이션을 재생하는 함수
UIIngreSynthComponent:EnableIngreList -- 재료 목록을 활성화하고 선택된 필터에 따라 내용을 갱신하는 함수
UIIngreSynthComponent:SelectFilterType -- 필터 타입을 선택하고 해당 화면으로 전환하는 함수
UIIngreSynthComponent:OnClickFilterBackBtn -- 필터 뒤로가기 버튼 클릭 시 초기 화면으로 돌아가는 함수
UIIngreSynthComponent:InitUIFirstPage -- UI를 초기 상태로 리셋하고 필터 선택 화면을 표시하는 함수
UIIngreSynthComponent:OnClickClearBtn -- 클리어 버튼 클릭 시 선택된 모든 재료를 초기화하는 함수
UIIngreSynthComponent:OnClickAutoSetBtn -- 자동 설정 버튼 클릭 시 재료를 자동으로 선택하는 함수
UIIngreSynthComponent:SelectTagBtn -- 태그 버튼을 선택하고 체크 상태를 업데이트하는 함수
UIIngreSynthComponent:OnClickSynthBtn -- 합성 버튼 클릭 시 로직에 합성 요청을 전달하는 함수
UIIngreSynthComponent:PlayEffect -- 합성 효과를 재생하고 대성공 여부에 따라 다른 연출을 하는 함수
UIIngreSynthComponent:SetStateSynthBtn -- 합성 버튼의 활성화 상태와 디밍 상태를 설정하는 함수
UIIngreSynthComponent:FirstPageAnim -- 초기 페이지 진입 시 필터 버튼들의 애니메이션을 재생하는 함수
UIIngreSynthComponent:SetSynthRecipeIcon -- 필터 타입에 따라 합성 레시피 아이콘을 설정하는 함수
UIIngreSynthComponent:EnableBtnOnEffectPlaying -- 효과 재생 중에 버튼들의 활성화 상태를 제어하는 함수
UIIngreSynthComponent:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreSynthComponent:HandleButtonClickEvent2 -- 필터 뒤로가기 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreSynthComponent:HandleButtonClickEvent3 -- 클리어 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreSynthComponent:HandleButtonClickEvent4 -- 자동 설정 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreSynthComponent:HandleButtonClickEvent5 -- 합성 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreSynthComponent:HandleButtonClickEvent6 -- UI 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreSynthListSlot:Init -- 슬롯 UI 컴포넌트들을 초기화하는 함수
UIIngreSynthListSlot:Refresh -- 재료 데이터에 따라 슬롯의 아이콘과 정보를 갱신하는 함수
UIIngreSynthListSlot:OnClickSlot -- 슬롯 클릭 시 재료를 선택 목록에 추가하는 함수
UIIngreSynthListSlot:OnClickSelectedSlot -- 선택된 슬롯에서 해제 시 카운트를 갱신하는 함수
UIIngreSynthListSlot:SetCount -- 재료 수량과 선택 상태에 따라 카운트 텍스트를 설정하는 함수
UIIngreSynthListSlot:ResetCount -- 슬롯의 카운트를 리셋하는 함수
UIIngreSynthListSlot:HandleButtonClickEvent -- 슬롯 버튼 클릭 이벤트를 처리하는 핸들러
UIIngreSynthSelectedSlot:Refresh -- 선택된 재료 데이터에 따라 슬롯의 아이콘과 정보를 갱신하는 함수
UIIngreSynthSelectedSlot:OnClickSlot -- 선택된 슬롯 클릭 시 해당 재료를 선택 목록에서 제거하는 함수
UIIngreSynthSelectedSlot:InitEmpty -- 슬롯을 빈 상태로 초기화하는 함수
UIIngreSynthSelectedSlot:InitEntity -- 슬롯의 UI 컴포넌트들을 초기화하는 함수
UIIngreSynthSelectedSlot:HandleButtonClickEvent -- 선택된 슬롯 버튼 클릭 이벤트를 처리하는 핸들러
CheatButtonMacroLogic:AutoClick -- 매크로가 활성화되었을 때 자동으로 버튼을 여러 번 클릭
CheatButtonMacroLogic:HandleButtonClickEvent -- UI 버튼 클릭 이벤트를 처리하고 자동 클릭 실행
CheatButtonMacroLogic:HandleButtonClickEvent2 -- UI 텍스트 클릭 이벤트를 처리하고 자동 클릭 실행
CheatButtonMacroLogic:HandleButtonClickEvent3 -- UI 스프라이트 클릭 이벤트를 처리하고 마지막 클릭 버튼 저장
CheatButtonMacroLogic:HandleButtonClickEvent4 -- UI 빈 요소 클릭 이벤트를 처리하고 자동 클릭 실행
CheatButtonMacroLogic:HandleKeyDownEvent -- F10 키를 눌러 매크로 기능을 토글하는 키보드 이벤트 처리
PacketDelayCheckComponent:OnMapEnter -- 맵 진입 시 패킷 지연 체크를 위한 타이머 설정 및 초기화
PacketDelayCheckComponent:PacketTimeCheck_Client -- 클라이언트에서 패킷 시간을 체크하고 서버로 응답 전송
PacketDelayCheckComponent:PacketTimeCheck_Server -- 서버에서 클라이언트 패킷 지연 시간을 체크하고 일시정지 상태 판단
PacketDelayCheckComponent:CheckClientDelayed -- 클라이언트 지연 상태를 체크하고 서버-클라이언트 간 동기화 상태 관리
PacketDelayCheckComponent:PacketDelayCheckLogging -- 패킷 지연 발생 시 로그를 기록하고 시간 흐름 상태를 체크
PacketDelayCheckComponent:CheckClientPaused -- 클라이언트의 일시정지 상태를 반환
PacketDelayCheckComponent:UpdateReceivedClientPacketTime -- 클라이언트로부터 패킷을 받은 시간을 업데이트
PlayerAdmin:OnBeginPlay -- 플레이어가 게임에 입장할 때 관리자 권한을 확인하고 설정
PlayerAdmin:RequestMobileCheatBtnEnable -- 모바일 플랫폼에서 치트 버튼들의 활성화 상태를 설정
PlayerAdmin:RequestAdminCheatBtnEnable -- 관리자 권한에 따라 디버그 UI 그룹과 치트 버튼들을 활성화
PlayerAdmin:VersionTextInit -- 버전 텍스트를 초기화하고 현재 버전 정보를 표시
PlayerAdmin:HandleButtonClickEvent -- 인트로 맵 패스 버튼 클릭 시 월드 입장 준비 완료 처리
PlayerAdmin:HandleButtonClickEvent2 -- 모바일 모니터 버튼 클릭 시 모니터 버튼 세트 패널 토글
CheatPresetDataLogic:Load -- 치트 프리셋 데이터를 로드하는 함수
CheatPresetDataLogic:GetCheatPresetData -- 테스트 키로 치트 프리셋 데이터를 가져오는 함수
CheatPresetDataLogic:GetCheatPresetUpgrade -- 테스트 키로 치트 프리셋 업그레이드 데이터를 가져오는 함수
CheatPresetDataLogic:GetCheatPresetEmployees -- 테스트 키로 치트 프리셋 직원 데이터를 가져오는 함수
CheatPresetDataLogic:GetManagementLv -- 테스트 키로 관리 레벨을 가져오는 함수
CheatPresetDataLogic:GetUpgradeTypeId -- 타입 열거형으로 업그레이드 타입 ID를 가져오는 함수
PlayerCheatComponent:OnBeginPlay -- 치트 컴포넌트 초기화 시 사용자 ID 설정 및 모든 치트 명령어 등록
PlayerCheatComponent:GoCheat -- 치트 명령어를 실행하는 함수
PlayerCheatComponent:SendCheat -- 치트 메시지를 전송하는 함수
PlayerCheatComponent:HasAuthority -- 치트 권한이 있는지 확인하는 함수
PlayerCheatComponent:RegisterCheat -- 치트 명령어를 등록하는 함수
PlayerCheatComponent:GainMeso -- 메소를 획득하는 치트 함수
PlayerCheatComponent:GainClover -- 클로버를 획득하는 치트 함수
PlayerCheatComponent:GainHeart -- 하트를 획득하는 치트 함수
PlayerCheatComponent:GainTip -- 팁을 획득하는 치트 함수
PlayerCheatComponent:GainItem -- 아이템을 획득하는 치트 함수
PlayerCheatComponent:GainDropBox -- 드롭박스를 획득하는 치트 함수
PlayerCheatComponent:ClearAllDB -- 모든 데이터베이스를 초기화하는 치트 함수
PlayerCheatComponent:ClearIngameDB -- 인게임 데이터베이스를 초기화하는 치트 함수
PlayerCheatComponent:ClearInventory -- 인벤토리를 초기화하는 치트 함수
PlayerCheatComponent:AddTimeSecond -- 시간을 초 단위로 추가하는 치트 함수
PlayerCheatComponent:AddTimeMinute -- 시간을 분 단위로 추가하는 치트 함수
PlayerCheatComponent:OpenWorldShopStorageOperation -- 월드샵 스토리지 작업을 여는 치트 함수
PlayerCheatComponent:SetTrialProgress -- 트라이얼 진행도를 설정하는 치트 함수
PlayerCheatComponent:SetEveryButtonsUnlock -- 모든 버튼을 해금하는 치트 함수
PlayerCheatComponent:ChangeAchievementProgress -- 업적 진행도를 변경하는 치트 함수
PlayerCheatComponent:ChangeTimeFlowDelay -- 시간 흐름 딜레이를 변경하는 치트 함수
PlayerCheatComponent:AddIngredientCard -- 재료 카드를 추가하는 치트 함수
PlayerCheatComponent:ChangePlayerStoreRanking -- 플레이어 상점 랭킹을 변경하는 치트 함수
PlayerCheatComponent:AddEmployee -- 직원을 추가하는 치트 함수
PlayerCheatComponent:AddAllEmployee -- 모든 직원을 추가하는 치트 함수
PlayerCheatComponent:RemoveEmployee -- 직원을 제거하는 치트 함수
PlayerCheatComponent:ChangeEmployeeLevel -- 직원 레벨을 변경하는 치트 함수
PlayerCheatComponent:CallEvent -- 이벤트를 호출하는 치트 함수
PlayerCheatComponent:ChangeManagementLevel -- 경영 레벨을 변경하는 치트 함수
PlayerCheatComponent:ChangeManagementInprogress -- 경영 진행도를 변경하는 치트 함수
PlayerCheatComponent:SubMesoUnderZero -- 메소를 0 이하로 차감하는 치트 함수
PlayerCheatComponent:ChangeTrend -- 트렌드를 변경하는 치트 함수
PlayerCheatComponent:TrainingSkip -- 훈련을 스킵하는 치트 함수
PlayerCheatComponent:CallRankingEvent -- 랭킹 이벤트를 호출하는 치트 함수
PlayerCheatComponent:MakeStoreInfoReport -- 상점 정보 리포트를 생성하는 치트 함수
PlayerCheatComponent:GainTrainingTicket -- 훈련 티켓을 획득하는 치트 함수
PlayerCheatComponent:ChangeCustomerSpawnDelay -- 고객 스폰 딜레이를 변경하는 치트 함수
PlayerCheatComponent:FindHotPlace -- 핫플레이스를 찾는 치트 함수
PlayerCheatComponent:StopTimeFlow -- 시간 흐름을 정지/재개하는 치트 함수
PlayerCheatComponent:SetEnableLobbyHUD -- 로비 HUD 활성화 상태를 설정하는 치트 함수
PlayerCheatComponent:SetEnableMoneyBar -- 머니 바 활성화 상태를 설정하는 치트 함수
PlayerCheatComponent:StartIntroDialog -- 인트로 다이얼로그를 시작하는 치트 함수
PlayerCheatComponent:StartOutroDialog -- 아웃트로 다이얼로그를 시작하는 치트 함수
PlayerCheatComponent:AutoTrainingSkip -- 자동 훈련을 스킵하는 치트 함수
PlayerCheatComponent:SetAttractiveScore -- 매력도 점수를 설정하는 치트 함수
PlayerCheatComponent:ResetAttractiveScore -- 매력도 점수를 리셋하는 치트 함수
PlayerCheatComponent:AllShopCountReset -- 모든 상점 카운트를 리셋하는 치트 함수
PlayerCheatComponent:AddMonthlyEarning -- 월 수익을 추가하는 치트 함수
PlayerCheatComponent:SetUpgradeLevel -- 업그레이드 레벨을 설정하는 치트 함수
PlayerCheatComponent:ChangeReputation -- 평판을 변경하는 치트 함수
PlayerCheatComponent:OpenVIPOrder -- VIP 주문을 열기 위한 조건을 설정하는 치트 함수
PlayerCheatComponent:StartNewVIPOrderSeason -- 새로운 VIP 주문 시즌을 시작하는 치트 함수
PlayerCheatComponent:CreateVIPOrderSlotData -- VIP 주문 슬롯 데이터를 생성하는 치트 함수
PlayerCheatComponent:SetVIPOrderCompleteCount -- VIP 주문 완료 횟수를 설정하는 치트 함수
PlayerCheatComponent:SetVIPOrderCount -- VIP 주문 가능 횟수를 설정하는 치트 함수
PlayerCheatComponent:SetSkipTutorial -- 튜토리얼을 스킵하는 치트 함수
PlayerCheatComponent:ClearEventCompleteStatus -- 이벤트 완료 상태를 초기화하는 치트 함수
PlayerCheatComponent:GetExpPotionItemByExpValue -- 경험치 값에 따른 경험치 포션 아이템을 획득하는 치트 함수
PlayerCheatComponent:TestPresetStart -- 테스트 프리셋을 시작하는 치트 함수
PlayerCheatComponent:IsValidTestKey -- 테스트 키가 유효한지 확인하는 함수
PlayerCheatComponent:TestPresetMapSetting -- 테스트 프리셋 맵 설정을 적용하는 치트 함수
PlayerCheatComponent:TestPresetStep1Management -- 테스트 프리셋 1단계 경영 설정을 적용하는 치트 함수
PlayerCheatComponent:TestPresetStep2Upgrade -- 테스트 프리셋 2단계 업그레이드 설정을 적용하는 치트 함수
PlayerCheatComponent:TestPresetStep3Employee -- 테스트 프리셋 3단계 직원 설정을 적용하는 치트 함수
PlayerCheatComponent:TestPresetStep4Recipe -- 테스트 프리셋 4단계 레시피 설정을 적용하는 치트 함수
PlayerCheatComponent:TestPresetStep5Earning -- 테스트 프리셋 5단계 수익 설정을 적용하는 치트 함수
PlayerCheatComponent:TestPresetAll -- 모든 테스트 프리셋을 적용하는 치트 함수
PlayerCheatComponent:EndEventNow -- 현재 진행 중인 이벤트를 즉시 종료하는 치트 함수
PlayerCheatComponent:ForceSetEventOccured -- 이벤트 발생을 강제로 설정하는 치트 함수
PlayerCheatComponent:UnlockEveryUpgrades -- 모든 업그레이드를 잠금 해제하는 치트 함수
PlayerCheatComponent:ChangeEmployeeLevelAll -- 모든 직원의 레벨을 변경하는 치트 함수
PlayerCheatComponent:SetUnofficialTrials -- 비공식 트라이얼을 설정하는 치트 함수
PlayerCheatComponent:SetIsCheatMode -- 치트 모드 상태를 설정하는 함수
PlayerCheatComponent:GainDiamondFree -- 무료 다이아몬드를 획득하는 치트 함수
PlayerCheatComponent:GainDiamondPaid -- 유료 다이아몬드를 획득하는 치트 함수
PlayerCheatComponent:SetStageProgress -- 스테이지 진행도를 설정하는 치트 함수
PlayerCheatComponent:SetBunSkinCollection -- 번 스킨 컬렉션을 설정하는 치트 함수
PlayerCheatComponent:AddAllIngredientCards -- 모든 재료 카드를 추가하는 치트 함수
PlayerCheatComponent:GainStrategyPointSP -- 전략 포인트 SP를 획득하는 치트 함수
PlayerCheatComponent:SetSideMenuCollection -- 사이드 메뉴 컬렉션을 설정하는 치트 함수
PlayerCheatComponent:ForceSaveDB -- 데이터베이스를 강제로 저장하는 치트 함수
PlayerCheatComponent:GainPackage -- 패키지를 획득하는 치트 함수
PlayerCheatComponent:ResetShopItemCount -- 상점 아이템 구매 횟수를 리셋하는 치트 함수
PlayerCheatComponent:StartTrend -- 트렌드를 시작하는 치트 함수
PlayerCheatComponent:EndTrend -- 트렌드를 종료하는 치트 함수
PlayerCheatComponent:SetVIPOrderSeasonCompleteScore -- VIP 주문 시즌 완료 점수를 설정하는 치트 함수
PlayerCheatComponent:ResetEmployeeEquipCurrency -- 직원 장비 화폐를 리셋하는 치트 함수
PlayerCheatComponent:ChangeChuchuEquipUgradeLevel -- 츄츄 장비 업그레이드 레벨을 변경하는 치트 함수
PlayerCheatComponent:EmployeeEquipUpgradeSimulator1 -- 직원 장비 업그레이드 시뮬레이터 1을 실행하는 치트 함수
PlayerCheatComponent:EmployeeEquipUpgradeSimulator2 -- 직원 장비 업그레이드 시뮬레이터 2를 실행하는 치트 함수
PlayerCheatComponent:ChangeChuchuCollectionState -- 츄츄 컬렉션 상태를 변경하는 치트 함수
PlayerCheatComponent:ChangeEmploymentCount -- 고용 횟수를 변경하는 치트 함수
PlayerCheatComponent:ChangeBadgeProgress -- 배지 진행도를 변경하는 치트 함수
PlayerCheatComponent:GetBadge -- 배지를 획득하는 치트 함수
PlayerCheatComponent:ResetPassPurchaseRecord -- 패스 구매 기록을 리셋하는 치트 함수
PlayerCheatComponent:ResetPassLevelReward -- 패스 레벨 보상을 리셋하는 치트 함수
PlayerCheatComponent:BuyChuchuEquip -- 츄츄 장비를 구매하는 치트 함수
PlayerCheatComponent:BuyChuchuEquipAll -- 모든 츄츄 장비를 구매하는 치트 함수
PlayerCheatComponent:HUDOnOff -- HUD 표시를 토글하는 치트 함수
PlayerCheatComponent:HUDOnOffClient -- 클라이언트에서 HUD 표시를 제어하는 함수
PlayerCheatComponent:AddPiggyBankPoint -- 돼지 저금통 포인트를 추가하는 치트 함수
PlayerCheatComponent:SetPiggyBankLevel -- 돼지 저금통 레벨을 설정하는 치트 함수
PlayerCheatComponent:PlayDialog -- 다이얼로그를 재생하는 치트 함수
PlayerCheatComponent:ResetBoosterPackPurchase -- 부스터 팩 구매를 리셋하는 치트 함수
PlayerCheatComponent:AddRecipe -- 레시피를 추가하는 치트 함수
PlayerCheatComponent:ClearStoreInfoReport -- 상점 정보 리포트를 초기화하는 치트 함수
PlayerCheatComponent:LaunchingEventChangeDay -- 런칭 이벤트 날짜를 변경하는 치트 함수
PlayerCheatComponent:LaunchingEventReset -- 런칭 이벤트를 리셋하는 치트 함수
PlayerCheatComponent:ChangeOfflineRewardTime -- 오프라인 보상 시간을 변경하는 치트 함수
PlayerCheatComponent:SetDropdownTestTimer -- 드롭다운 테스트 타이머를 설정하는 치트 함수
PlayerCheatComponent:AddRecipeGrade -- 레시피 등급을 추가하는 치트 함수
PlayerCheatComponent:SetFreeDiamondForceMinus -- 무료 다이아몬드를 강제로 음수로 설정하는 치트 함수
PlayerCheatComponent:EnableForceDelayFlag -- 강제 딜레이 플래그를 활성화하는 치트 함수
PlayerCheatComponent:SetIngreSynthGreatSuccessProb -- 재료 합성 대성공 확률을 설정하는 치트 함수
PlayerCheatComponent:RemoveAllIngredientCards -- 모든 재료 카드를 제거하는 치트 함수
PlayerCheatComponent:Achievement_ProgressFull -- 모든 업적의 진행도를 완료로 설정하는 치트 함수
PlayerCheatComponent:Achievement_AchieveFull -- 모든 업적을 달성 상태로 설정하는 치트 함수
PlayerCheatComponent:Achievement_CompleteFull -- 모든 업적을 완료 상태로 설정하는 치트 함수
PlayerCheatComponent:SetStoreUpgradeLevel -- 상점 업그레이드 레벨을 설정하는 치트 함수
PlayerCheatComponent:IngreSynthSimulator -- 재료 합성 시뮬레이터를 실행하는 치트 함수
PlayerCheatComponent:HandleChatBalloonEvent -- 채팅 말풍선 이벤트를 처리하는 핸들러
UICheat:FindCommand -- 입력된 명령어와 매칭되는 치트 명령어들을 찾아 표시
UICheat:OnBeginPlay -- 치트 UI 초기화 및 이벤트 연결
UICheat:OnTextInputValueChanged -- 텍스트 입력이 변경될 때 명령어 검색 수행
UICheat:OnTextInputSumit -- 엔터 키를 눌렀을 때 치트 명령어 전송
UICheat:SetCommand -- 명령어를 입력 필드에 설정하고 활성화
UICheat:GetOrCreateCommandRenderer -- 명령어 렌더러 엔티티를 가져오거나 새로 생성
UICheat:ClearCommandRenderer -- 모든 명령어 렌더러를 비활성화
UICheat:ToggleUI -- 치트 UI를 토글하여 보이거나 숨김
UICheat:HandleKeyDownEvent -- 키 입력 이벤트를 처리하는 핸들러
UICheat:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UICheatCommandRenderer:OnBeginPlay -- 치트 명령어 렌더러 UI 요소들을 초기화
UICheatCommandRenderer:Set -- 명령어와 설명을 UI에 설정
UICheatCommandRenderer:HandleButtonClickEvent -- 명령어 렌더러 버튼 클릭 시 명령어를 입력 필드에 설정
DebugMonitorSpawnPool:OnBeginPlay -- 스폰 풀 모니터 UI 요소들을 초기화
DebugMonitorSpawnPool:UpdateMonitor -- 고객 스폰 풀 데이터를 읽어서 모니터 UI에 표시
DebugMonitorSpawnPool:PageChange -- 스폰 풀 데이터 페이지를 변경하여 다음/이전 페이지로 이동
DebugMonitorSpawnPool:ResetButtonHilight -- 새로고침 버튼의 색상을 노란색으로 변경하여 업데이트 필요 상태 표시
DebugMonitorUICustomer:OnBeginPlay -- 고객 디버그 모니터 UI를 초기화하고 데이터 설정
DebugMonitorUICustomer:SetSelectedCustomer -- 선택된 고객 엔티티를 설정하고 모니터 정보를 업데이트
DebugMonitorUICustomer:SetUiSpawnTableInfo -- 고객의 스폰 테이블 정보를 UI에 설정
DebugMonitorUICustomer:SetUiMapInfo -- 고객의 맵 관련 정보를 UI에 설정
DebugMonitorUICustomer:SetUiAiScriptInfo -- 고객의 AI 스크립트 정보를 UI에 설정
DebugMonitorUICustomer:UpdateWaitingTime -- 고객의 대기 시간을 실시간으로 업데이트
DebugMonitorUIEmployee:UpdateEmpDebugInfo -- 직원들의 디버그 정보를 업데이트하고 UI에 표시
DebugMonitorUIEmployee:ChangeLocation -- 직원 위치를 변경하고 레이아웃을 업데이트하는 함수
DebugMonitorUIEmployee:TotalDurationSet -- 직원의 총 작업 시간을 설정하는 함수
DebugMonitorUIEmployee:WorkDurationSet -- 직원의 작업 시간을 설정하는 함수
DebugMonitorUIEmployee:LevelSet -- 레벨을 설정하는 함수
DebugMonitorUIEmployee:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
DebugMonitorUIMaintain:Calcost -- 유지보수 비용을 계산하고 각 항목별로 분류하여 표시
DebugMonitorUIMaintain:UpdateUI -- UI를 업데이트하는 함수
DebugMonitorUIStore:OnBeginPlay -- 디버그 모니터 상점 정보 UI를 초기화하고 데이터 설정
DebugMonitorUIStore:SetUiManagementInfo -- 경영 정보를 UI에 설정 (경영 레벨, 수익 레벨, 매력도 요구사항 등)
DebugMonitorUIStore:SetAttractiveInfo -- 상점 매력도 정보를 UI에 설정 (확장, 인테리어, 데코, 레시피)
DebugMonitorUIStore:SetReputationInfo -- 평판 정보를 UI에 설정 (평판 점수, 스폰 지연 시간)
DebugMonitorUIStore:SetReputationChangeByReview -- 리뷰에 의한 평판 변화량을 월간 누적치로 설정
DebugMonitorUIStore:SetReputationChangeByContents -- 콘텐츠에 의한 평판 변화량을 월간 누적치로 설정
DebugMonitorUIStore:ResetReputationChangeByReview -- 월간 평판 변화량 누적치를 모두 리셋
DebugMonitorUIStore:SetPiggyBankInfo -- 저금통 정보를 UI에 설정 (다음 레벨까지 수익, 추가 포인트)
DebugMonitorUIStore:HandlePlayerManagementChangedEvent -- 플레이어 경영 레벨 변경 이벤트 처리
DebugMonitorUIStore:HandleEarningLevelChangedEvent -- 수익 레벨 변경 이벤트 처리
DebugMonitorUIStore:HandlePlayerReputationChangedEvent -- 플레이어 평판 변경 이벤트 처리
PlayerDebugMonitor:OnBeginPlay -- 디버그 모니터 그룹을 활성화하고 초기 상태 설정
PlayerDebugMonitor:SpawnUIMonitorEntity -- 모든 디버그 모니터 UI 엔티티들을 생성하고 위치 설정
PlayerDebugMonitor:EnableStoreInfoMonitor -- 상점 정보 모니터를 활성화/비활성화하고 관련 정보를 업데이트
PlayerDebugMonitor:EnableCustomerInfoMonitor -- 고객 정보 모니터를 활성화/비활성화하고 정보를 업데이트
PlayerDebugMonitor:UpdateCustomerInfoMonitor -- 고객 정보 모니터의 표시 상태를 고객 ID에 따라 업데이트
PlayerDebugMonitor:EnableRecipeInfoMonitor -- 레시피 정보 모니터들을 활성화/비활성화
PlayerDebugMonitor:UpdateDebugMonitorAttractive -- 상점의 매력도 정보를 업데이트
PlayerDebugMonitor:ResetDebugMonitorMonthlyReputation -- 월간 평판 변화량을 리셋
PlayerDebugMonitor:UpdateDebugMonitorReputationChangeByContents -- 콘텐츠에 의한 평판 변화량을 업데이트
PlayerDebugMonitor:UpdateDebugMonitorRecipeMaking -- 레시피 제작 모니터의 정보를 키에 따라 업데이트
PlayerDebugMonitor:EnableEmployeeInfoMonitor -- 직원 정보 모니터를 활성화/비활성화하고 정보를 업데이트
PlayerDebugMonitor:EnableMaintainInfoMonitor -- 유지보수 정보 모니터를 활성화하고 비용 계산
PlayerDebugMonitor:UpdateMonitor -- 모든 모니터 정보를 업데이트
PlayerDebugMonitor:UpdatePiggyBankInfo -- 저금통 정보를 업데이트
PlayerDebugMonitor:EnableSpawnPoolMonitor -- 스폰 풀 모니터를 활성화하고 데이터를 업데이트
PlayerDebugMonitor:HandleKeyDownEvent -- 키보드 입력으로 각종 디버그 모니터들을 토글하는 이벤트 처리
SpawnPoolBtn:HandleButtonClickEvent -- 스폰 풀 모니터의 버튼 클릭 이벤트를 타입에 따라 처리
UIRecipeDebug:OnBeginPlay -- 레시피 디버그 UI 초기화 및 버튼 이벤트 연결
UIRecipeDebug:OpenTab -- 지정된 탭을 열고 해당 정보를 새로고침
UIRecipeDebug:RefreshMakingText -- 레시피 제작 중 정보를 새로고침 (밸런스, 맵기, 맛 점수, 가격)
UIRecipeDebug:RefreshResultText -- 레시피 결과 정보를 새로고침 (태그, 콤보, 빵 보너스, 밸런스 보너스)
DebugTimer:OnUpdate -- 매 프레임마다 타이머가 실행 중일 때 경과 시간을 업데이트
DebugTimer:UpdateUI -- 타이머 UI를 업데이트하고 예약된 시간에 도달하면 자동 정지
DebugTimer:ToggleStartPuase -- 타이머 시작/정지 상태를 토글하고 게임 내 시간 흐름을 제어
DebugTimer:TimerReset -- 타이머를 초기화하고 모든 기록과 예약을 리셋
DebugTimer:TimeRecord -- 현재 시간을 기록하고 UI에 새로운 기록 항목을 추가
DebugTimer:Reserve -- 지정된 기간에 따라 타이머 자동 정지를 예약 설정
DebugTimer:Init -- 디버그 타이머 UI와 예약 버튼들을 초기화
DebugTimer:TimeFlow -- 게임 내 시간 흐름을 제어
DebugTimer:UpdateTime -- 게임 내 날짜 정보를 업데이트
DebugTimer:OnBeginPlay -- 컴포넌트 초기화 시 UI 요소들을 찾아서 연결하고 31일 달 정보를 설정
DebugTimer:HandleButtonClickEvent -- 메인 타이머의 시작/정지 버튼 클릭 이벤트 처리
DebugTimer:HandleButtonClickEvent2 -- 간단한 타이머의 시작/정지 버튼 클릭 이벤트 처리
DebugTimer:HandleButtonClickEvent4 -- 타이머 리셋 버튼 클릭 이벤트 처리
DebugTimer:HandleButtonClickEvent3 -- 메인 타이머의 시간 기록 버튼 클릭 이벤트 처리
DebugTimer:HandleButtonClickEvent9 -- 간단한 타이머의 시간 기록 버튼 클릭 이벤트 처리
DebugTimer:HandleButtonClickEvent5 -- 간단한 타이머 모드로 전환하는 버튼 클릭 이벤트 처리
DebugTimer:HandleButtonClickEvent6 -- 메인 타이머 모드로 전환하는 버튼 클릭 이벤트 처리
DebugTimer:HandleButtonClickEvent7 -- 예약 UI 패널을 토글하는 버튼 클릭 이벤트 처리
DebugTimer:HandleButtonClickEvent8 -- 예약 기간 선택 버튼들의 클릭 이벤트 처리
BGMService:ApplyBGM -- 지정된 BGM을 현재 맵에 적용하고 재생
BGMService:ApplySpotBGM -- 스팟 데이터에서 해당 스팟의 BGM을 찾아서 적용
BGMService:StopBGM -- 현재 재생 중인 BGM을 정지
BGMService:ResumeBGM -- 정지된 BGM을 다시 재생
BGMService:ApplyLobbyBGM -- 현재 스테이지에 맞는 로비 BGM을 적용
CheckProhibitedWordLogic:IsProhibitedWordUsingAPI -- API를 사용하여 금지어 여부를 확인하고 특수문자 검사
CheckProhibitedWordLogic:ContainsSpecialCharacter -- 텍스트에 허용되지 않는 특수문자가 포함되어 있는지 확인
CheckProhibitedWordLogic:HandleTextInputEndEditEditorEvent -- 텍스트 입력 완료 에디터 이벤트 처리
ColorCodeEnum:OnBeginPlay -- 게임 시작 시 색상 코드 테이블을 초기화
ColorCodeEnum:GetColor -- 헥스 코드로 색상 객체를 반환하고 캐시에 저장
DateTimeLogic:GetUtcNow -- 현재 UTC 시간에 경과 시간을 더한 값을 반환
DateTimeLogic:AddTime -- 디버그용 시간을 추가하고 변경 이벤트를 발송
DateTimeLogic:ClearAddTime -- 추가된 디버그 시간을 초기화
DateTimeLogic:GetUtcNowElapsed -- 현재 UTC 시간의 경과 시간을 밀리초로 반환
DateTimeLogic:ChangeElapsedToString -- 경과 시간을 시:분:초 형태의 문자열로 변환
DateTimeLogic:GetUtc9Elapsed -- UTC+9 시간대의 경과 시간을 반환
DateTimeLogic:GetUtcNowText -- 현재 UTC 시간을 RFC3339 형식의 문자열로 반환
DBUtilLogic:GetNumberByTable -- 테이블에서 키에 해당하는 숫자 값을 가져오고 없으면 기본값 반환
DBUtilLogic:GetStringByTable -- 테이블에서 키에 해당하는 문자열 값을 가져오고 없으면 기본값 반환
DBUtilLogic:IsEmpty -- 테이블이 비어있거나 nil인지 확인
DBUtilLogic:SerializeAttendTable -- 출석 정보 테이블을 문자열로 직렬화 (미구현)
DBUtilLogic:DeserializeAttendTable -- 문자열에서 출석 정보 테이블로 역직렬화 (미구현)
EditorLogic:HandleButtonClickEditorEvent -- 에디터 버튼 클릭 시 UI 그룹의 모든 텍스트 폰트를 기본값으로 설정
EditorLogic:HandleButtonClickEditorEvent2 -- 두 번째 에디터 버튼 클릭 시 특정 엔티티를 제거
FadeService:ShowFade -- 페이드 인 효과를 표시하고 지정된 서브 기능을 실행
FadeService:HideFade -- 페이드 아웃 효과를 실행하여 화면을 원래대로 복원
GetConfigDataLogic:GetConfigNumDataByKey -- 설정 키에 해당하는 숫자 데이터를 반환
GetConfigDataLogic:OnBeginPlay -- 게임 시작 시 설정 데이터를 로드하고 각종 매니저에 값을 설정
IconRuidEnum:GetSkillTypeIcon -- 스킬 타입에 따른 아이콘 RUID를 반환
IconRuidEnum:GetComboCountRUID -- 콤보 카운트에 해당하는 숫자 아이콘 RUID를 반환
IconRuidEnum:GetEffectRUIDByGrade -- 등급에 따른 이펙트 RUID를 반환
IconRuidEnum:GetOverLimitJemIcon -- 직원 타입에 따른 오버리밋 젬 아이콘 RUID를 반환
IconRuidEnum:GetAutoTrainingIcon -- 인덱스에 따른 자동 훈련 아이콘 RUID를 반환
IconRuidEnum:GetMaterialEntryId -- 머터리얼 ID에 해당하는 엔트리 ID를 반환
MathUtilLogic:Vector3AlmostEquals -- 두 Vector3 좌표가 거의 같은지 비교하여 불린 값 반환
NickNameLogic:IsValid -- 닉네임 텍스트가 유효한지 검증하고 결과 메시지를 반환
NickNameLogic:CodePointToLen -- 유니코드 코드포인트를 문자 길이로 변환
NickNameLogic:IsWhitespaceOnly -- 텍스트가 공백 문자로만 구성되어 있는지 확인
NickNameLogic:IsWhitespaceCodepoint -- 코드포인트가 공백 문자인지 확인
NickNameLogic:HandleTextInputEndEditEditorEvent -- 텍스트 입력 완료 에디터 이벤트 처리
RandomLogic:RandomInteger -- 시드를 기반으로 랜덤 정수를 생성
RandomLogic:RandomDouble -- 0과 1 사이의 랜덤 실수를 생성
RandomLogic:RandomIntegerRange -- 지정된 범위 내의 랜덤 정수를 생성
RandomLogic:NextSeed -- 시드 테이블에서 다음 시드 값을 설정
RandomLogic:GetRandomDouble -- 시드를 사용하여 랜덤 실수를 반환
RandomLogic:GetRandomDoubles -- 지정된 개수만큼의 랜덤 실수 배열을 반환
RandomLogic:GetRandomRange -- 시드를 사용하여 범위 내 랜덤 정수를 반환
RandomLogic:ReturnRandomPickWeight -- 가중치 테이블을 기반으로 랜덤 선택된 인덱스를 반환
RandomLogic:ReturnIsDropProb100 -- 확률 값에 따른 드롭 성공 여부를 판단
RandomLogic:RandomIntegersInRange -- 지정된 범위의 정수들을 무작위로 섞은 배열을 반환
ResourceManager:OnBeginPlay -- 게임 시작 시 SFX 테이블을 로드하고 리소스를 프리로드
ResourceManager:ChangeMaterial -- 엔티티의 머터리얼을 변경하고 지정된 시간 후 원래대로 복원
StringUtilLogic:ReturnThousandsSeparatedString -- 정수를 천 단위로 구분된 문자열로 변환
StringUtilLogic:ReturnOriginString -- 문자열에서 쉼표를 제거하여 원본 숫자 문자열로 복원
StringUtilLogic:ParseItemsStringToItemTable -- 아이템 문자열을 파싱하여 아이템 테이블로 변환
StringUtilLogic:ConvertIntToStringWithBigNumber -- 큰 숫자를 축약된 형태의 문자열로 변환
StringUtilLogic:GetDurationTimeString -- 기간을 시:분:초 형태의 지역화된 문자열로 변환
StringUtilLogic:ParseTimeStringToDateTimeElpased -- 시간 문자열을 DateTime 경과 시간으로 파싱
StringUtilLogic:ShuffleStringTable -- 문자열 테이블의 순서를 무작위로 섞어서 반환
StringUtilLogic:FormatNumber -- 숫자를 K, M, B 단위로 축약하여 포맷팅
StringUtilLogic:NumToString -- 숫자를 정수로 변환한 후 문자열로 반환
StringUtilLogic:StringToInt -- 문자열을 정수로 변환하여 반환
StringUtilLogic:GetBoolByString -- 문자열을 불린 값으로 변환하고 실패 시 기본값 반환
StringUtilLogic:GetSyncTableVStr -- 동기화 테이블의 값들을 쉼표로 구분된 문자열로 변환
StringUtilLogic:get_utc_time_rfc3339_format -- UTC 시간을 RFC3339 형식의 문자열로 변환
StringUtilLogic:IntBoolToString -- 정수-불린 테이블을 쉼표로 구분된 문자열로 변환
StringUtilLogic:IntIntToString -- 정수-정수 테이블을 쉼표로 구분된 문자열로 변환
StringUtilLogic:IntBoolToTable -- 쉼표로 구분된 문자열을 정수-불린 테이블로 변환
StringUtilLogic:IntIntToTable -- 쉼표로 구분된 문자열을 정수-정수 테이블로 변환
StringUtilLogic:StringBoolToString -- 문자열-불린 테이블을 쉼표로 구분된 문자열로 변환
StringUtilLogic:StringBoolToTable -- 쉼표로 구분된 문자열을 문자열-불린 테이블로 변환
StringUtilLogic:OrdinalFormatter -- 숫자에 서수 접미사(st, nd, rd, th)를 추가하여 문자열 포맷팅
StringUtilLogic:HandleKeyDownEvent -- 키 입력 이벤트 처리
UIMoneyBarLogic:OnBeginPlay -- 게임 시작 시 UI 아이콘들을 데이터 테이블에서 가져와 설정
UIMoneyBarLogic:UpdateCloverUI -- 클로버 UI의 값을 업데이트
UIMoneyBarLogic:UpdateMoneyUI -- 돈 UI의 값을 업데이트
UIMoneyBarLogic:UpdateHeartUI -- 하트 UI의 값을 업데이트
UIMoneyBarLogic:UpdateDiamondUI -- 다이아몬드 UI의 값을 업데이트
UIMoneyBarLogic:EnableOnlyDiamondUI -- 다이아몬드 UI만 활성화하고 다른 UI들은 비활성화
UIMoneyBarLogic:EnableDiamondInfoButton -- 다이아몬드 정보 버튼의 활성화 상태를 설정
UIMoneyBarLogic:HandlePlayerMoneyChangedEvent -- 플레이어 돈 변경 이벤트 처리
UIMoneyBarLogic:HandlePlayerArcaneSymbolChangedEvent -- 플레이어 아케인 심볼(클로버) 변경 이벤트 처리
UIMoneyBarLogic:HandlePlayerHeartChangedEvent -- 플레이어 하트 변경 이벤트 처리
UIMoneyBarLogic:HandlePlayerDiamondChangedEvent -- 플레이어 다이아몬드 변경 이벤트 처리
UIMoneyBarLogic:HandleButtonClickEvent -- 다이아몬드 UI 클릭 시 다이아몬드 정보 팝업 열기
UIMoneyBarLogic:HandleButtonClickEvent2 -- 다이아몬드 정보 버튼 클릭 시 툴팁 표시
AchievementDataSetLogic:OnBeginPlay -- 게임 시작 시 업적 데이터셋을 로드
AchievementDataSetLogic:LoadDataSet -- CSV 파일에서 업적 타입 및 ID 데이터를 로드하여 테이블에 저장
AchievementDataSetLogic:GetAchievementTypeData -- 업적 타입 ID로 해당 업적 타입 데이터 반환
AchievementDataSetLogic:GetAchievementIdData -- 업적 ID로 해당 업적 ID 데이터 반환
AchievementIdData:Load -- CSV 데이터테이블에서 업적 ID 데이터를 로드하여 속성에 저장
AchievementLogic:CheckAchievementAchieved -- 플레이어의 업적 달성 상태를 확인하고 업데이트
AchievementLogic:ReturnInitialTypeValue -- 업적 타입의 초기값을 반환
AchievementLogic:ReturnAchievementNameText -- 업적 이름 텍스트를 현지화하여 반환
AchievementLogic:ReturnAchievementDescText -- 업적 설명 텍스트를 현지화하여 반환
AchievementLogic:ReturnConvertedTypeValue -- 업적 타입에 따라 값을 적절한 형식으로 변환하여 반환
AchievementLogic:GetFixedTypeValue -- 스테이지별 보정값을 적용한 업적 목표값 계산
AchievementTypeData:Load -- CSV 데이터테이블에서 업적 타입 데이터를 로드하여 속성에 저장
UIAchievement:OnBeginPlay -- UI 초기화 및 탭 버튼, 닫기 버튼 이벤트 설정
UIAchievement:Open -- 업적 UI를 열고 달성된 업적이 있는 탭을 기본으로 선택
UIAchievement:Close -- 업적 UI를 닫기
UIAchievement:OnGetAllRewardButtonClicked -- 모든 보상 받기 버튼 클릭 시 처리
UIAchievement:GetAchiTypesByTab -- 선택된 탭에 해당하는 업적 타입 목록을 정렬하여 반환
UIAchievement:SetSelectTab -- 탭 선택 시 UI 상태 업데이트 및 업적 목록 표시
UIAchievement:OnSelectTab -- 탭 선택 상태에 따른 UI 시각적 효과 적용
UIAchievement:Apply -- 선택된 탭의 업적들을 달성 상태별로 분류하고 정렬하여 UI에 표시
UIAchievement:ClearSlots -- 업적 슬롯들을 모두 클리어
UIAchievement:GetTabTitle -- 탭 인덱스에 해당하는 현지화된 탭 제목 반환
UIAchievement:HandleButtonClickEvent -- 업적 버튼 클릭 이벤트 처리
UIAchievementSlotRenderer:OnBeginPlay -- UI 컴포넌트들을 초기화하고 보상 버튼 이벤트 설정
UIAchievementSlotRenderer:Init -- 업적 슬롯을 특정 업적 타입으로 초기화하고 보상 정보 설정
UIAchievementSlotRenderer:Clear -- 업적 슬롯을 초기화하고 비활성화
UIAchievementSlotRenderer:RefreshGauge -- 업적 진행도 게이지와 텍스트를 현재 상태로 갱신
UIAchievementSlotRenderer:RefreshComplete -- 업적 완료 상태에 따른 UI 표시 갱신
BalanceDataSetLogic:OnBeginPlay -- 게임 시작 시 밸런스 데이터셋을 로드
BalanceDataSetLogic:LoadDataSet -- 스테이지 설정 데이터와 매장 매력도 레벨 데이터를 로드
BalanceDataSetLogic:SetEarningLevelByEarningRecord -- 플레이어의 수익 기록에 따라 수익 레벨을 설정
BalanceDataSetLogic:GetStageConfigData -- 스테이지 ID에 해당하는 설정 데이터를 반환
BalanceDataSetLogic:GetStoreAttractiveLevelData -- 매력도 레벨에 해당하는 매장 매력도 데이터를 반환
BalanceDataSetLogic:HandlePlayerManagementChangedEvent -- 플레이어 경영 정보 변경 시 수익 레벨을 재계산
StageEarningLevelData:Load -- 데이터 테이블에서 스테이지 수익 레벨 정보를 로드
StoreAttractiveLevelData:Load -- 데이터 테이블에서 매장 매력도 레벨 정보를 로드
ChatMessageComponent:SetIndex -- 채팅 메시지의 인덱스를 설정
ChatMessageComponent:InitChatInfo -- 채팅 정보를 초기화하고 인덱스를 설정
CustomChatLogic:OnBeginPlay -- 서버 시작 시 채팅 큐를 초기화하고 메시지 브로드캐스트 타이머를 설정
CustomChatLogic:RequestChat -- 클라이언트로부터 채팅 메시지 요청을 처리하고 적절한 채팅 타입에 따라 메시지를 배포
CustomChatLogic:OnGetMessage -- 서버로부터 받은 채팅 메시지 데이터를 파싱하여 이벤트로 전송
CustomChatLogic:ReplaceNonSpaceWithAsterisk -- 금지어를 별표(*)로 치환하여 반환 (공백은 유지)
CustomChatLogic:AddSystemMessage -- 클라이언트에서 시스템 메시지를 생성하여 채팅창에 표시
CustomChatLogic:GetTypeByMessage -- 메시지 내용을 분석하여 채팅 타입을 결정 (일반, 귓속말, 파티, 확성기)
CustomChatLogic:StartsWith -- 문자열이 특정 접두사로 시작하는지 확인
CustomChatLogic:SendMegaphone -- 확성기 메시지를 모든 월드 인스턴스에 브로드캐스트
CustomChatLogic:RefreshMsg -- 채팅 메시지를 UI 엔터티에 표시하기 위해 텍스트와 아이콘을 업데이트
CustomChatLogic:OnEndPlay -- 서버 종료 시 채팅 타이머를 정리
CustomChatLogic:AddToChatData -- 신고용 채팅 데이터를 저장하고 최대 개수를 유지
CustomChatLogic:ReportChatMessage -- 특정 인덱스의 채팅 메시지를 신고 처리
CustomChatLogic:ReportChatToClient -- 클라이언트에서 신고된 채팅 메시지를 처리 (자기 자신은 제외)
CustomChatLogic:RefreshChatBannedStatusClient -- 채팅 금지 상태에 따라 입력 필드의 활성화 상태를 변경
CustomChatLogic:HandleUserEnterEvent -- 유저가 입장할 때 캐시된 채팅 메시지를 전송
CustomChatLogic:HandleOnGetChatMessage -- 다른 월드 인스턴스에서 받은 채팅 메시지를 큐에 추가
OnGetChatMessage:Init -- 채팅 메시지 데이터를 초기화하는 함수
OnReportedCustomChat:Init -- 신고된 채팅 데이터를 초기화하는 함수
ReportChatType:Init -- 신고용 채팅 데이터를 초기화
UICustomChat:OnBeginPlay -- 채팅 UI 초기화 및 이벤트 연결 설정
UICustomChat:OnSumitMessage -- 입력된 채팅 메시지를 처리하고 적절한 채팅 타입으로 전송
UICustomChat:SetWhisper -- 귓속말 모드로 입력 필드를 설정
UICustomChat:Refresh -- 채팅 목록을 새로고침하고 스크롤 위치를 유지
UICustomChat:ActivateInputField -- 채팅 입력 필드를 활성화하고 채팅창을 열기
UICustomChat:OnTextInputEndEdit -- 입력 종료 시 선택 상태를 해제
UICustomChat:OnActivateInputField -- 입력 필드 활성화 시 선택 상태를 설정
UICustomChat:RefreshFoldMsg -- 접힌 채팅창에 표시될 마지막 메시지를 업데이트
UICustomChat:ClearChatTextMaterial -- 채팅 텍스트의 마테리얼 효과를 정리
UICustomChat:HandleOnGetChatMessage -- 채팅 메시지를 받아 UI에 추가하고 채팅 벌룬을 표시
UICustomChat:HandleKeyUpEvent -- 엔터 키 입력 시 채팅 입력 필드를 활성화
UICustomChatHolder:OnBeginPlay -- 초기화 시 채팅창을 숨김 상태로 설정
UICustomChatHolder:ToggleCustomChat -- 채팅창의 펼치기/접기 상태를 전환
UICustomChatHolder:HandleButtonClickEvent -- 채팅창 열기 버튼 클릭 이벤트 처리
UICustomChatHolder:HandleButtonClickEvent2 -- 채팅창 닫기 버튼 클릭 이벤트 처리
RandomBox:AddItem -- 가중치와 값을 가진 아이템을 랜덤박스에 추가
RandomBox:Pick -- 가중치 기반으로 랜덤하게 아이템을 선택하여 반환
RandomBox:FindMaxValueLessThanOrEqual -- 이진 탐색으로 타겟보다 작거나 같은 최대값을 찾아 반환
RandomBox:RemoveItem -- 지정된 값을 가진 아이템들을 제거하고 제거된 가중치 반환
WeightRandomBox:Add -- 아이템과 가중치를 추가하고 더티 플래그 설정
WeightRandomBox:Remove -- 지정된 아이템을 제거하고 더티 플래그 설정
WeightRandomBox:Pick -- 가중치 기반으로 랜덤하게 아이템을 선택하여 반환
WeightRandomBox:CalculateSum -- 더티 플래그가 설정되어 있을 때만 전체 가중치 합계 재계산
WeightRandomBox:GetPickItem -- 랜덤 값에 따라 선택될 아이템을 찾아 반환
WeightRandomBox:GetTotalWeight -- 전체 가중치 합계를 계산하고 반환
IngredientGachaDataLogic:OnBeginPlay -- 게임 시작 시 재료 가챠 데이터셋을 로드
IngredientGachaDataLogic:LoadDataSet -- CSV 파일에서 재료 가챠 랜덤박스 데이터를 로드하여 메모리에 저장
IngredientGachaDataLogic:ReturnMultiCountByGachaId -- 가챠 ID에 따른 멀티 뽑기 개수를 반환 (BN: 3개, IN: 5개)
IngredientGachaDataLogic:GetIngreGachaRandomBoxData -- ID로 재료 가챠 랜덤박스 데이터를 조회하여 반환
IngreGachaRandomBoxData:Load -- CSV 데이터 테이블에서 가챠 박스 데이터를 로드하여 등급별 가중치 설정
IngreGachaRandomBoxData:Pick -- 플레이어와 개수를 받아 가중치 기반으로 재료/빵 아이템을 랜덤 선택하여 반환
IngreGachaRandomBoxData:GetGachaPool -- 원본 풀에서 지정된 등급에 해당하는 아이템들만 필터링하여 가챠 풀 생성
UIIngreGacha:Open -- 재료 가챠 UI를 열고 필요시 레시피 그룹도 함께 활성화
UIIngreGacha:Close -- 재료 가챠 UI를 닫고 관련 UI 상태를 정리
UIIngreGacha:Refresh -- 가챠 슬롯들을 새로고침하여 아이템 데이터로 UI 업데이트
UIIngreGacha:OnBeginPlay -- 컴포넌트 시작 시 UI 새로고침
UIIngreGacha:HandleButtonClickEvent -- 닫기 버튼 클릭 시 재료 가챠 UI를 닫는 핸들러
UIIngreGacha:HandleButtonClickEvent2 -- 재료 가챠 전체 보기 버튼 클릭 시 UI를 완전히 여는 핸들러
UIIngreGacha:HandleButtonClickEvent3 -- 배경 클릭 시 재료 가챠 UI를 닫는 핸들러
UIIngreGacha:HandleButtonClickEvent4 -- 재료번 컶렉션 버튼 클릭 시 컶렉션 UI를 여는 핸들러
UIIngreGachaItemRenderer:Init -- UI 요소들을 초기화하고 버튼 텍스트 설정
UIIngreGachaItemRenderer:Refresh -- 아이템 ID로 가챠 아이템 UI를 새로고침하고 이벤트 연결
UIIngreGachaItemRenderer:RefreshCountText -- 아이템 수량에 따라 버튼 활성화 상태와 텍스트 색상 업데이트
UIIngreGachaItemRenderer:OnBeginPlay -- 컴포넌트 시작 시 재료 가챠 빨간점 비활성화
UIIngreGachaItemRenderer:HandlePlayerInventoryItemChangedEvent -- 플레이어 인벤토리 아이템 변경 시 수량 텍스트 업데이트
DropBoxLogic:OpenDropBox -- 드롭박스 ID에 따라 확률적으로 아이템을 지급하는 메서드
DropBoxLogic:AddItem -- 플레이어 인벤토리에 아이템을 추가하는 메서드
DropBoxLogic:CheckLogic -- 드롭박스 확률 로직을 테스트하는 디버그용 메서드
ItemData:Load -- 데이터 테이블에서 아이템 정보를 로드하는 메서드
ItemData:GetUseItems_List -- 사용 아이템 정보를 리스트 형태로 반환하는 메서드
ItemData:GetUseItems_Dictinary -- 사용 아이템 정보를 딕셔너리 형태로 반환하는 메서드
ItemData:GetUseItems_ItemId_Pair -- 사용 아이템 정보를 아이템 ID와 함께 쌍으로 반환하는 메서드
ItemDataSetLogic:OnBeginPlay -- 게임 시작 시 아이템 데이터셋을 로드하는 메서드
ItemDataSetLogic:LoadDataSet -- CSV 파일에서 아이템 데이터를 로드하고 아이콘을 프리로드하는 메서드
ItemDataSetLogic:GetItemData -- 아이템 ID로 아이템 데이터를 조회하는 메서드
ItemDataSetLogic:ReturnPotionIdsByStatType -- 스탯 타입에 따른 포션 아이템 ID 목록을 반환하는 메서드
ItemDataSetLogic:ReturnPotionStatTypeDataIndex -- 스탯 타입을 데이터 인덱스로 변환하는 메서드
ItemDataSetLogic:ReturnItemRuidFromId -- 아이템 ID로 아이콘 RUID를 조회하는 메서드
PlayerArcaneSymbolChangedEvent:Init -- 플레이어 비밀기호 변경 이벤트를 초기화하는 메서드
PlayerHeartChangedEvent:Init -- 플레이어 하트 변경 이벤트를 초기화하는 메서드
PlayerMoneyChangedEvent:Init -- 플레이어 돈 변경 이벤트를 초기화하는 메서드
PlayerReputationChangedEvent:Init -- 플레이어 평판 변경 이벤트를 초기화하는 메서드
PlayerTipChangedEvent:Init -- 플레이어 팁 변경 이벤트를 초기화하는 메서드
PlayerTrainingTokenChangedEvent:Init -- 플레이어 훈련 토큰 변경 이벤트를 초기화하는 메서드
BtnEnableControllerByLocale:OnBeginPlay -- 현재 로케일이 한국어인지 확인하여 버튼 활성화 상태를 설정
GetLocalizationTextLogic:OnBeginPlay -- 게임 시작 시 현지화 참조 키 테이블을 로드하여 ReferKeys 배열에 저장
GetLocalizationTextLogic:GetText -- 현재 로케일에 해당하는 번역된 텍스트를 반환
GetLocalizationTextLogic:MakeLocalizeDataText -- 텍스트 키를 기반으로 현지화된 데이터 텍스트를 생성하고 포맷팅 처리
GetLocalizationTextLogic:IsReferKey -- 주어진 문자열이 참조 키인지 확인하여 boolean 값을 반환
GetLocalizationTextLogic:GetReferKeyText -- 참조 키에 해당하는 실제 텍스트 값을 반환 (플레이어명, 상점명 등)
GetLocalizationTextLogic:CallToastByLocalizationKey -- 현지화 키를 사용하여 토스트 메시지를 표시
GetLocalizationTextLogic:RequestSetLocalizedTextServer -- 서버에 현지화된 텍스트 설정을 요청하고 지원하는 로케일 목록을 구성
GetLocalizationTextLogic:SetLocalizedTextServer -- 서버에서 현지화된 텍스트 데이터와 플레이어의 현재 로케일 ID를 설정
GetLocalizationTextLogic:GetLocalizedTextServer -- 서버에서 특정 로케일 ID와 키에 해당하는 현지화된 텍스트를 반환
LocalizedTextServer:GetText -- 지정된 로케일 ID에 해당하는 현지화된 텍스트를 반환
TextManager:GetText -- 입력받은 문자열을 그대로 반환
TextManager:GetSmartText -- 하나의 인자를 사용하여 스마트 포맷팅된 텍스트를 반환
TextManager:GetSmartText2 -- 두 개의 인자를 사용하여 스마트 포맷팅된 텍스트를 반환
TextManager:GetSmartText3 -- 세 개의 인자를 사용하여 스마트 포맷팅된 텍스트를 반환
TextManager:GetSmartText4 -- 네 개의 인자를 사용하여 스마트 포맷팅된 텍스트를 반환
TextManager:GetHexCode -- 색상 이름에 해당하는 헥스 컬러 코드를 반환
LocalizedTextComponent:OnBeginPlay -- 컴포넌트 시작 시 자동 설정이 활성화되어 있으면 폰트 크기를 설정
LocalizedTextComponent:SetFontSize -- 현재 로케일에 따라 텍스트 컴포넌트의 폰트 크기를 조정
LocalizedTextInputComponent:OnBeginPlay -- 컴포넌트 시작 시 자동 설정이 활성화되어 있으면 문자 제한을 설정
LocalizedTextInputComponent:SetCharacterLimit -- 현재 로케일에 따라 텍스트 입력 컴포넌트의 문자 제한을 조정
MainMenuBtnData:Load -- 데이터 테이블에서 메뉴 버튼 정보를 로드하여 프로퍼티에 설정
MainMenuBtnData:ReturnCategoryRUID -- 카테고리 번호에 따라 해당하는 카테고리 아이콘 RUID를 반환
MainMenuDataSetLogic:OnBeginPlay -- 로직 시작 시 메인 메뉴 데이터셋을 로드
MainMenuDataSetLogic:LoadDataSet -- 메인 메뉴 버튼 데이터를 CSV에서 읽어와 테이블에 저장
MainMenuDataSetLogic:GetMenuBtnData -- ID로 메인 메뉴 버튼 데이터를 조회하여 반환
MainMenuDataSetLogic:ClearMenuBtnChild -- 모든 메뉴 버튼의 클릭 유도 UI를 비활성화
MainMenuDataSetLogic:SetClickHereOnMenuBtn -- 특정 메뉴 버튼에 클릭 유도 화살표 UI를 생성하고 설정
MainMenuRedDotManager:OnBeginPlay -- 로직 시작 시 모든 메뉴 버튼의 빨간점 UI들을 찾아서 배열에 저장
MainMenuRedDotManager:SetMenuBtnRedDot -- 모든 메뉴 버튼의 빨간점 상태를 확인하여 메인 메뉴 버튼의 빨간점 표시 여부를 결정
MainMenuRedDotManager:EnableTrialRedDot -- 시험 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableShopRedDot -- 상점 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableUpgradeRedDot -- 업그레이드 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableAchievementRedDot -- 업적 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableIngreGachaRedDot -- 재료 뽑기 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableEmploymentRedDot -- 고용 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableTrainingRedDot -- 훈련 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableAutoTrainingRedDot -- 자동 훈련 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableEmployeeManageRedDot -- 직원 관리 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableRecipeRedDot -- 레시피 메뉴 버튼의 빨간점을 플레이어의 업그레이드 슬롯 개수와 설정된 레시피 개수를 비교하여 설정
MainMenuRedDotManager:EnableVIPOrderRedDot -- VIP 주문 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableIngreBunCollectionRedDot -- 재료 번 컬렉션 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableChuchuCollectionRedDot -- 츄츄 컬렉션 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
MainMenuRedDotManager:EnableRankingRedDot -- 랭킹 메뉴 버튼의 빨간점 표시 상태를 설정하고 메인 메뉴 빨간점을 업데이트
SelectDropDownLogic:SetSelected -- 드롭다운 아이템의 선택 상태에 따른 비주얼 스타일을 설정
SelectDropDownLogic:SetIconInfo -- 드롭다운 아이템의 아이콘 이미지를 설정
SelectDropDownLogic:SetTextInfo -- 드롭다운 아이템의 텍스트를 설정
SelectDropDownLogic:RefreshSelected -- 드롭다운 아이템들 중 지정된 키에 해당하는 아이템만 선택 상태로 설정
TooltipService:OpenTooltip -- 기본 툴팅을 열고 텍스트를 설정한 후 현재 툴팅으로 설정
TooltipService:CloseTooltip -- 툴팅을 닫고 관련 상태를 초기화
TooltipService:OpenTooltipWithPadding -- 아이템 설명용 툴팅을 위치에 맞촰 열고 패딩과 함께 표시
TooltipService:ShowHUDMoneyBarToolTip -- HUD 머니바 전용 툴팅을 표시
TooltipService:HandleScreenTouchEvent -- 화면 터치 이벤트 발생 시 열린 툴팅을 닫기
TooltipService:HandleMouseScrollEvent -- 마우스 스크롤 이벤트 발생 시 스크롤 사용 중이면 툴팅을 닫기
UIButtonTypeA:SetText -- 버튼에 표시될 텍스트를 설정
UIButtonTypeA:SetEnable -- 버튼의 활성화 상태를 설정하여 Disabled 오버레이 제어
UIButtonTypeA:OnBeginPlay -- 컴포넌트 초기화 시 버튼 엔티티들을 참조하고 이벤트를 연결
UIButtonTypeA:OnClickButton -- 버튼 클릭 이벤트 처리 및 외부 콜백 함수 호출
UIButtonTypeA:OnButtonStateChange -- 버튼 상태 변경 이벤트 처리 및 외부 콜백 함수 호출
UICurrencyToolTipComponent:OnBeginPlay -- 컴포넌트 초기화 시 툴팁 엔티티를 찾고 데이터를 설정
UICurrencyToolTipComponent:SetData -- 아이템 ID에 따른 툴팁 데이터를 설정하고 텍스트를 업데이트
UICurrencyToolTipComponent:HandleButtonClickEvent -- 버튼 클릭 시 툴팅 데이터를 확인하고 툴팅을 표시
UIEntityService:PlayUISpriteAnim -- UI 스프라이트 애니메이션을 지정된 시간 동안 재생하고 자동으로 비활성화
UIEntityService:GetOrCreateEntityOfModel -- 모델명과 인덱스로 엔티티를 찾거나 새로 생성하여 반환
UIEntityService:PlayMoveBounceTween -- 엔티티에 랜덤 위치로 이동하는 바운스 트위닝 애니메이션을 재생
UIEntityService:MakeStarIconForTasteScore -- 맛 점수에 따라 별 아이콘들을 생성하고 트위닝 효과를 적용
UIEntityService:TweenAndFade -- 엔티티를 지정된 위치로 이동시키면서 동시에 페이드 인/아웃 효과 적용
UIEntityService:GetOrCreateClonedEntityByName -- 이름으로 엔티티를 찾거나 원본을 복제하여 새로 생성하여 반환
UIEntityService:PlayPopFadeTween -- 엔티티에 랜덤 위치로 팝업하며 페이드아웃되는 트위닝 애니메이션을 재생
UIEntityService:SetDimWithIcon -- 엔티티의 Dim 효과와 아이콘 Dim, 텍스트 색상을 설정
UIEntityService:PlayMoneyPopFade -- 금액에 따라 코인 아이콘들을 생성하고 팝페이드 효과를 적용
UIEntityService:PlayUIOpenAnim -- UI 엔티티의 오픈 애니메이션을 지연 시간과 함께 재생
UIEntityService:ClearUIOpenAnim -- 엔티티의 UI 오픈 애니메이션을 중단하고 관련 데이터를 정리
UIGaugeBar:SetGauge -- 게이지의 현재 값을 설정하고 UI를 새로고침
UIGaugeBar:OnBeginPlay -- 컴포넌트 초기화 시 게이지 관련 엔티티들을 찾고 참조를 설정
UIGaugeBar:SetMaxValue -- 게이지의 최대값을 설정
UIGaugeBar:SetTextFormat -- 게이지 텍스트에 사용될 포맷 문자열을 설정
UIGaugeBar:Refresh -- 게이지의 시각적 표시와 텍스트를 현재 값에 따라 업데이트
UIGaugeBar:SetText -- 게이지 텍스트를 직접 설정
UIGroupManager:IsOnUI -- 어떤 UI 그룹이라도 활성화되어 있는지 확인하여 반환
UIGroupManager:IsOnLobby -- 로비 상태인지 확인 (이벤트 체크 옵션 포함)
UIGroupManager:ClearAllUI -- 열려있는 모든 UI를 순차적으로 닫고 정리
UIGroupManager:EnableMoneyBarGroup -- 머니 바 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableBackToLobbyBtn -- 로비로 돌아가기 버튼의 활성화 상태를 설정하는 함수
UIGroupManager:OnBeginPlay -- UI 그룹 매니저 초기화 시 실행되는 함수
UIGroupManager:IsEnableOpenPopUp -- 팝업을 열 수 있는 상태인지 확인하는 함수
UIGroupManager:EnableRecipeGroup -- 레시피 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableRewardGroup -- 보상 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableAchievementGroup -- 업적 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableEventGroup -- 이벤트 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableManagementGroup -- 경영 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableTrialGroup -- 트라이얼 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableRecipeSetGroup -- 레시피 세트 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableUpgradeGroup -- 업그레이드 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableVIPOrderGroup -- VIP 주문 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableStoreRankingGroup -- 상점 랭킹 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableStoreInfoGroup -- 상점 정보 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableTutorialGroup -- 튜토리얼 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:SetEnableMainMenuPanel -- 메인 메뉴 패널의 활성화 상태를 설정하는 함수
UIGroupManager:EnableReputationRewardGroup -- 평판 보상 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableStageInfoGroup -- 스테이지 정보 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableToastLobbyGroup -- 토스트 로비 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableIngreBunCollectionGroup -- 재료 번 컬렉션 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableChuchuCollectionGroup -- 츄츄 컬렉션 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableStageClearRewardGroup -- 스테이지 클리어 보상 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableSpecialShopGroup -- 특별 상점 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableStagePassGroup -- 스테이지 패스 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableSelectChuchuInCollection -- 컬렉션에서 츄츄 선택 UI의 활성화 상태를 설정하는 함수
UIGroupManager:EnableBadgeGroup -- 배지 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnablePiggyBankGroup -- 돼지 저금통 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableBoosterPackGroup -- 부스터 팩 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableStageLoadingGroup -- 스테이지 로딩 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableLobbyHUDGroup -- 로비 HUD 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableExchangeSettingGroup -- 환전 설정 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableExchangeGroup -- 환전 그룹의 활성화 상태를 설정하는 함수
UIGroupManager:EnableDiaInfoGroup -- 다이아 정보 그룹의 활성화 상태를 설정하는 함수
UIImageAlign:OnBeginPlay -- 컴포넌트 초기화 시 스프라이트와 트랜스폼 컴포넌트 참조 설정
UIImageAlign:SetCharId -- 캐릭터 ID에 따라 이미지 크기를 설정 (S: 400x400, T: 180x180, N: 400x400)
UIImageAlign:UpdateCanvas -- RUID 문자열을 파싱하여 이미지 설정 및 애니메이션 타입에 따라 스케일과 위치 조정
UIImageSizeFit:Apply -- 텍스트의 높이에 맞촰 이미지 사이즈를 조정하고 텍스트를 설정
UIImageSizeFit:OnBeginPlay -- 컴포넌트 초기화 시 원본 패딩 값들을 저장
UIImageSizeFit:Show -- 이미지를 1초간 표시한 후 자동으로 비활성화
UIItemRewardService:OnBeginPlay -- 로직 시작 시 배경 원본 크기를 저장하고 보상 리스트를 초기화
UIItemRewardService:SetItemRewardUI -- 아이템 보상 UI를 설정하고 애니메이션과 함께 표시
UIItemRewardService:AddItemToRewardQueue -- 아이템을 보상 대기열에 추가하여 나중에 일괄 표시할 수 있도록 준비
UIItemRewardService:RequestSetQueueToUI -- 대기열에 저장된 보상 아이템들을 UI로 표시하고 대기열을 초기화
UIItemRewardService:CloseUI -- 보상 UI를 닫고 관련 데이터를 정리한 후 평판 보상이 있으면 표시
UIItemRewardService:SetReputationRewardUI -- 평판 보상 UI를 설정하고 표시
UIItemRewardService:CloseReputationRewardUI -- 평판 보상 UI를 닫고 관련 데이터를 정리하는 함수
UIItemRewardService:SetCloseUICallback -- UI 닫기 콜백 함수를 설정하는 함수
UIItemRewardService:SetSideMenuRewardUI -- 사이드 메뉴 보상 UI를 설정하는 함수
UIItemRewardService:EndAnim -- 보상 애니메이션을 종료하고 UI를 활성화하는 함수
UIItemRewardService:OpenAnim -- 보상 UI 열기 애니메이션을 재생하고 지속 시간을 반환하는 함수
UIItemRewardService:DrawSeperatedList -- 보상 아이템 목록을 분리된 리스트로 그리는 함수
UIItemRewardService:ClearSeperatedList -- 분리된 보상 리스트를 초기화하는 함수
UIItemRewardService:HandleButtonClickEvent -- 보상 UI 터치 또는 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIItemRewardService:HandleButtonClickEvent2 -- 평판 보상 UI 터치 또는 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIItemRewardSlot:SetItem -- 아이템 ID와 개수로 슬롯을 설정하는 함수
UIItemRewardSlot:OnBeginPlay -- 게임 시작 시 UI 컴포넌트들을 초기화하는 함수
UIItemRewardSlot:OnClickItem -- 아이템 클릭 시 처리하는 함수
UIItemRewardSlot:SetIngredient -- 재료 ID와 개수로 슬롯을 설정하는 함수
UIItemRewardSlot:SetEmptySlot -- 슬롯을 비어있는 상태로 설정하는 함수
UIItemRewardSlot:ResetItemRUID -- 아이템 RUID를 초기화하는 함수
UIItemSlot:SetItem -- 아이템 ID와 개수를 받아 슬롯의 아이콘과 텍스트를 설정
UIItemSlot:OnBeginPlay -- 컴포넌트 초기화 시 아이콘, 개수 텍스트, 설명 엔티티들을 찾고 클릭 이벤트 연결
UIItemSlot:OnClickItem -- 아이템 클릭 시 설명을 표시할지 확인하고 설명 UI를 표시
UIPopup:Open -- 확인/취소 팝업을 열고 메시지와 콜백 함수들을 설정한 후 애니메이션 시작
UIPopup:OnClickOk -- 확인 버튼 클릭 시 팝업을 닫고 설정된 OK 콜백 함수를 실행
UIPopup:OnClickCancel -- 취소 버튼 클릭 시 팝업을 닫고 설정된 취소 콜백 함수를 실행
UIPopup:Close -- 팝업을 닫는 함수
UIPopup:StartTween -- 팝업 열기/닫기 트윈 애니메이션을 시작하는 함수
UIPopup:ResetPopup -- 팝업의 내용과 콜백 함수들을 재설정하는 함수
UIPopup:DisconnectButtonClickEvents -- 버튼 클릭 이벤트 연결을 해제하는 함수
UIPopupOK:Open -- 확인 팝업을 열고 메시지와 콜백 함수를 설정하는 함수
UIPopupOK:OnClickOk -- 확인 버튼 클릭 시 팝업을 닫고 콜백 함수를 실행하는 함수
UIPopupOK:Close -- 팝업을 닫고 이벤트 연결을 해제하는 함수
UIPopupOK:StartTween -- 팝업 열기/닫기 트윈 애니메이션을 시작하는 함수
UIPopupPurchase:Open -- 구매 팝업을 열고 가격과 콜백 함수를 설정하는 함수
UIPopupPurchase:OnClickOk -- 확인 버튼 클릭 시 팝업을 닫고 콜백 함수를 실행하는 함수
UIPopupPurchase:Close -- 팝업을 닫고 이벤트 연결을 해제하는 함수
UIPopupPurchase:StartTween -- 팝업 열기/닫기 트윈 애니메이션을 시작하는 함수
UIPopupPurchase:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIRewardLogText:Init -- 아이콘 엔티티를 찾아서 참조를 설정
UIRewardLogText:RefreshAndStartTween -- 보상 로그 텍스트와 아이콘을 설정하고 트위닝 애니메이션 시작
UIScreenLogic:GetWidth -- 화면의 너비를 계산하여 반환
UIScreenLogic:GetHeight -- 화면의 높이를 계산하여 반환
UIScreenLogic:GetResolution -- 현재 화면의 해상도를 Vector2로 반환
UIScreenLogic:GetRatioX -- 기준 해상도 대비 X축 비율을 계산하여 실제 화면 너비로 변환
UIScreenLogic:GetRatioY -- 기준 해상도 대비 Y축 비율을 계산하여 실제 화면 높이로 변환
UIScreenLogic:GetPosition -- 절대 좌표를 상대 좌표(0~1)로 변환
UIScreenLogic:GetPositionFromTouchPoint -- 터치 포인트를 UI 좌표계로 변환하여 Vector3로 반환
UIToast:ShowMessage -- 토스트 메시지를 표시하고 트위닝 애니메이션 시작
UIToast:StartTween -- 토스트 메시지의 페이드 인/아웃 트위닝 애니메이션을 시작
UIToast:OnEndPlay -- 로직 종료 시 실행 중인 타이머를 정리
UIToastLobby:OnBeginPlay -- 로직 시작 시 메시지 엔티티의 원본 위치를 저장
UIToastLobby:ShowMessage -- 로비 토스트 메시지를 표시하고 트위닝 애니메이션 시작
UIToastLobby:StartTween -- 로비 토스트의 위치 이동과 함께 페이드 인/아웃 트위닝 시작
UIToastLobby:OnEndPlay -- 로직 종료 시 실행 중인 타이머를 정리
UIToggleTypeA:SetText -- 토글 버튼의 텍스트를 설정
UIToggleTypeA:SetSelect -- 토글 버튼의 선택 상태에 따라 이미지를 변경
UIToggleTypeA:OnBeginPlay -- 컴포넌트 초기화 시 UI 엘리먼트들을 찾고 버튼 이벤트를 연결
UIToggleTypeA:OnClickButton -- 버튼 클릭 시 인덱스 확인 후 외부 콜백 함수 호출
UIToggleTypeA:SetIndex -- 토글 버튼의 인덱스 번호를 설정
UIToggleTypeA:SetTextColor -- 토글 버튼의 텍스트 색상을 설정
UIToggleTypeA:SetTextOutLine -- 토글 버튼의 텍스트 외곽선 설정
SubscriptionData:Load -- CSV 테이블에서 구독 서비스 데이터를 로드
SubscriptionService:IngreBoxService -- 플레이어의 재료 상자 구독 서비스 상태를 업데이트
SubscriptionService:UpdateHUDSubscriptionInfo -- HUD에 구독 서비스 정보를 업데이트하여 표시
SubscriptionService:RefreshSlot -- 구독 서비스 슬롯의 아이템 정보와 남은 횟수를 갱신
SubscriptionService:OnBeginPlay -- 게임 시작 시 구독 정보 툴팁을 비활성화
UISubscriptionProgressSlot:OnBeginPlay -- UI 컴포넌트 초기화
UISubscriptionProgressSlot:Refresh -- 구독 아이템의 진행 상태를 UI에 표시
UISubscriptionProgressSlot:Disable -- 구독 서비스가 만료되었을 때 비활성화 표시
UIUpgradeDetail:Init -- 업그레이드 세부 정보 UI 컴포넌트들을 초기화
UIUpgradeDetail:Refresh -- 선택된 업그레이드 타입의 세부 정보를 UI에 갱신
UIUpgradeDetail:SetDescEntity -- 업그레이드 도움말 데이터를 UI 엔티티에 설정
UIUpgradeDetail:RefreshEmpty -- 선택된 업그레이드가 없을 때 빈 상태로 UI를 갱신
UIUpgradeDetail:RefreshCostTooltip -- 업그레이드 비용 툴팁에 원래 비용과 할인 효과를 표시
UIUpgradeListSlot:Init -- 업그레이드 목록 슬롯의 UI 컴포넌트 초기화
UIUpgradeListSlot:Refresh -- 업그레이드 슬롯 UI를 현재 상태에 맞게 갱신
UIUpgradeListSlot:HandleButtonClickEvent -- 업그레이드 슬롯 클릭 시 해당 업그레이드 선택
UIUpgradePanel:OnBeginPlay -- 업그레이드 패널 초기화 및 탭 버튼 이벤트 연결
UIUpgradePanel:Open -- 업그레이드 패널을 열고 특정 업그레이드를 선택
UIUpgradePanel:Close -- 업그레이드 패널을 닫기
UIUpgradePanel:Refresh -- 선택된 탭의 업그레이드 목록을 갱신
UIUpgradePanel:SetSelectTab -- 선택된 탭을 설정하고 UI를 갱신
UIUpgradePanel:OnSelectTab -- 탭 선택 시 UI 스타일을 변경하고 가이드 버튼 설정
UIUpgradePanel:ReturnTabName -- 탭 인덱스에 해당하는 로컬라이즈된 탭 이름을 반환
UIUpgradePanel:OnSelectSlot -- 업그레이드 슬롯을 선택하고 세부 정보를 갱신
UIUpgradePanel:ReturnTabIconRUID -- 탭 인덱스에 해당하는 아이콘 RUID를 반환
UIUpgradePanel:SetGuidePageBtn -- 선택된 탭에 따라 가이드 페이지 버튼을 설정
UIUpgradePanel:SetTabRedDot -- 탭에 업그레이드 가능한 항목이 있을 때 빨간 점 표시
UIUpgradePanel:ResetScroll -- 선택된 업그레이드 항목으로 스크롤 위치를 초기화
UIUpgradePanel:HandleButtonClickEvent2 -- 닫기 버튼 클릭 시 업그레이드 패널을 닫기
UIUpgradePanel:HandleButtonClickEvent3 -- 업그레이드 패널 열기 버튼 클릭 처리
UpgradeDataSetLogic:OnBeginPlay -- 게임 시작 시 업그레이드 데이터셋을 로드
UpgradeDataSetLogic:LoadDataSet -- 업그레이드 타입 데이터와 구독 데이터를 CSV에서 로드
UpgradeDataSetLogic:ReturnValueOfTypeLevel -- 특정 업그레이드 타입과 레벨에 대한 효과 값을 반환
UpgradeDataSetLogic:ReturnMaxLevelValueOfType -- 업그레이드 타입의 최대 레벨에서의 효과 값을 반환
UpgradeDataSetLogic:ReturnCurrentPlayerValue -- 플레이어의 현재 업그레이드 레벨에서의 효과 값을 반환
UpgradeDataSetLogic:ReturnTabDatas -- 탭 ID에 따른 업그레이드 목록 데이터를 반환
UpgradeDataSetLogic:CanUpgrade -- 플레이어가 해당 업그레이드를 할 수 있는지 확인
UpgradeDataSetLogic:IsConditionSatisfied -- 업그레이드 조건이 만족되었는지 확인
UpgradeDataSetLogic:ReturnMaxUpgradeLevelAvailable -- 플레이어가 업그레이드 가능한 최대 레벨의 효과 값을 반환
UpgradeDataSetLogic:GetData -- 업그레이드 타입 ID로 업그레이드 타입 데이터를 반환
UpgradeDataSetLogic:GetLevelData -- 업그레이드 타입과 레벨로 레벨 데이터를 반환
UpgradeDataSetLogic:ReturnConditionText -- 업그레이드 조건을 로컬라이즈된 텍스트로 반환
UpgradeDataSetLogic:ReturnCurrentPlayerLevel -- 플레이어의 현재 업그레이드 레벨을 반환
UpgradeDataSetLogic:RequestCloseUpgradeUI -- 업그레이드 UI를 닫고 관련 UI도 함께 닫기
UpgradeDataSetLogic:ReturnGuidePageIdByTabIndex -- 탭 인덱스에 따른 가이드 페이지 ID를 반환
UpgradeDataSetLogic:MakeUpgradeReport -- 업그레이드 완료 시 보고서 메시지를 생성
UpgradeDataSetLogic:ReturnReportParamValue -- 보고서 파라미터 문자열을 실제 값으로 변환
UpgradeDataSetLogic:MakeSubscriptionExpireReport -- 구독 서비스 만료 시 보고서 메시지를 생성
UpgradeDataSetLogic:GetSubscriptionData -- 구독 ID로 구독 데이터를 반환
UpgradeDataSetLogic:CalcBurgerPriceFromTrainingUpgradeLevel -- 트레이닝 업그레이드 레벨에 따른 버거 가격을 계산
UpgradeHelpData:Load -- CSV 데이터로부터 업그레이드 도움말 정보를 로드
UpgradeLevelData:Load -- CSV 행 데이터에서 업그레이드 레벨 정보를 로드
UpgradeLevelData:GetHelpData -- 업그레이드 도움말 데이터를 반환
UpgradeLevelData:GetUpgradeCost -- 플레이어의 스테이지와 전략 효과를 반영한 업그레이드 비용 계산
UpgradeLevelData:GetConditionValue -- 업그레이드 조건 값을 스테이지에 따라 반환
UpgradeLevelData:GetUpgradeValue -- 전략 효과를 반영한 업그레이드 효과 값을 반환
UpgradeTypeData:Load -- CSV 데이터테이블에서 업그레이드 타입 정보를 로드
UpgradeTypeData:GetMaxLevel -- 플레이어의 스테이지에 따른 최대 업그레이드 레벨을 반환
UpgradeTypeData:IsUpgradeConditionSatisfied -- 업그레이드 해금 조건이 만족되었는지 확인
UpgradeTypeData:SetUpgradeConditionSatisfied -- 업그레이드 해금 조건을 강제로 만족시킴
CustomAnimation:OnBeginPlay -- 게임 시작 시 애니메이션 초기화 및 자동 재생 수행
CustomAnimation:OnUpdate -- 매 프레임마다 애니메이션 시간 및 상태 업데이트
CustomAnimation:Play -- 애니메이션 재생 시작
CustomAnimation:PingPong -- 핑폰 애니메이션 시간 계산 (앞뒤로 반복)
CustomAnimation:Repeat -- 루프 애니메이션 시간 계산 (루프 딩레이 고려)
CustomAnimation:ChangeAnimationClip -- 애니메이션 클립을 변경하고 새로 재생
CustomAnimation:InitClipData -- 애니메이션 클립 데이터를 초기화하고 콜백 함수 설정
CustomAnimation:Stop -- 애니메이션 정지
CustomAnimationLogic:OnBeginPlay -- 게임 시작 시 초기화 작업 수행
CustomAnimationLogic:InterpolateKeyframes -- 키프레임 데이터를 기반으로 주어진 시간의 보간된 값을 계산
CustomAnimationLogic:ApplyAnimation -- 애니메이션 데이터를 현재 시간에 맞게 적용
CustomAnimationLogic:GetClip -- 애니메이션 클립 데이터를 가져오거나 캐시에서 로드
NaviNodeEditorLogic:Function1 -- 선택된 스테이지의 네비게이션 노드 정보를 데이터셋에 저장
NaviNodeEditorLogic:HandleButtonClickEditorEvent -- 데이터 저장 버튼 클릭 이벤트 처리
NaviNodeEditorLogic:HandleButtonClickEditorEvent2 -- 그리드 형태로 네비게이션 노드를 자동 생성
LobbySpawnPositionLogic:OnBeginPlay -- 게임 시작 시 모든 스폰 위치 데이터를 로드
LobbySpawnPositionLogic:LoadRowColDataSet -- 행과 열 구조를 가진 데이터셋을 테이블에 로드
LobbySpawnPositionLogic:LoadRowDataSet -- 행 구조만 가진 데이터셋을 테이블에 로드
LobbySpawnPositionLogic:LoadKitchenAppDataSet -- 주방기기 타입과 인덱스를 기준으로 데이터셋을 테이블에 로드
LobbySpawnPositionLogic:LoadExpansionTileGroupDataSet -- 확장 타일 그룹 데이터를 3차원 구조로 로드
LobbySpawnPositionLogic:ResetCustomerWaitSeatGroup -- 고객 대기석 그룹의 특정 위치를 업데이트
LobbySpawnPositionLogic:ResetEmployeeUseKitchenAppPosGroup -- 직원이 주방기기를 사용할 위치를 업데이트
LobbySpawnPositionLogic:ResetDisplayOffset -- 디스플레이 오프셋 위치를 업데이트
SpawnPosEditorLogic:CustomerWaitSeatGroup -- 고객 대기석 그룹의 위치 정보를 데이터셋에 저장
SpawnPosEditorLogic:CustomerExitTempGroup -- 고객 임시 퇴장 그룹의 위치 정보를 데이터셋에 저장
SpawnPosEditorLogic:CustomerEnterGroup -- 고객 입장 그룹의 위치 정보를 데이터셋에 저장
SpawnPosEditorLogic:CustomerBeforeEnterGroup -- 고객 입장 전 대기 그룹의 위치 정보를 데이터셋에 저장
SpawnPosEditorLogic:EmployeeUseKitchenAppPosGroup -- 직원이 주방기기를 사용할 위치 정보를 데이터셋에 저장
SpawnPosEditorLogic:DisplayOffset -- 디스플레이 오프셋 위치 정보를 데이터셋에 저장
SpawnPosEditorLogic:ExpansionTileGroup -- 확장 타일 그룹의 위치 정보를 데이터셋에 저장
SpawnPosEditorLogic:HandleButtonClickEditorEvent -- 에디터 버튼 클릭 이벤트 처리
LogStorageLogic:LogValue -- 플레이어의 특정 값을 로그로 저장하는 서버 전용 메서드
EmployeeMoveScript:InitForAstar -- A* 알고리즘을 위한 초기화 및 경로 갱신 함수 설정
EmployeeMoveScript:OnUpdate -- 매 프레임마다 직원의 이동 로직 처리
EmployeeMoveScript:ChangeTarget -- 타겟 위치를 변경하고 직원 타입에 따라 목적지 설정
EmployeeMoveScript:InitGraph -- 네비게이션 그래프를 초기화하고 경로 찾기용 노드 데이터 구성
EmployeeMoveScript:MoveByAstar -- A* 알고리즘을 사용한 경로 기반 이동 처리
EmployeeMoveScript:MoveByLinear -- 직선 경로로 목표 지점까지 이동 처리
EmployeeMoveScript:MoveByDir -- 방향 벡터에 따른 실제 이동 및 캐릭터 방향 설정
EmployeeMoveScript:CheckArrival -- 목표 지점 도착 여부를 거리 계산으로 확인
EmployeeMoveScript:MoveFinished -- 이동 완료 시 최종 위치 설정 및 이동 완료 이벤트 발송
EmployeeMoveScript:ChangeRendererLookDirection -- 캐릭터의 좌우 방향에 따른 스프라이트 플립 처리
EmployeeMoveScript:HandleKeyDownEvent -- 디버그용 키보드 입력으로 네비게이션 링크 시각화 처리
EmployeeMoveScript:HandleEmployeeMoveChangedEvent -- 직원 이동 상태 변경 이벤트 처리 및 타겟 위치 업데이트
EmployeeMoveScript:HandleRefreshPathEvent -- 패스파인더에서 경로 갱신 요청 시 그래프 재초기화 처리
PathFinder:OnBeginPlay -- 패스파인더 초기화 및 A* 알고리즘 함수들 설정
PathFinder:distance -- 두 점 사이의 거리를 계산하여 반환
PathFinder:path -- A* 알고리즘을 사용하여 시작점에서 목표점까지의 경로를 계산
PathFinder:InitNodes -- 특정 레벨의 네비게이션 노드 데이터를 초기화하고 맵 데이터 로드
RecycleScrollView:OnBeginPlay -- 스크롤뷰 초기화: 마스크와 터치 컴포넌트 추가, 아이템 설정
RecycleScrollView:Initialize -- 스크롤뷰 초기 설정: 뷰 바운드 설정 및 리프레시
RecycleScrollView:GetOrCreateItem -- 지정된 인덱스의 아이템을 가져오거나 새로 생성
RecycleScrollView:SetTotalCount -- 전체 아이템 개수를 설정하고 리프레시
RecycleScrollView:OnScroll -- 스크롤 방향에 따라 수직 또는 수평 이동 처리
RecycleScrollView:MoveVertical -- 수직 스크롤 이동: 셀들의 위치를 업데이트하고 재사용 처리
RecycleScrollView:MoveHorizontal -- 수평 스크롤 이동: 셀들의 위치를 업데이트하고 재사용 처리
RecycleScrollView:Refresh -- 스크롤뷰 전체를 리프레시: 아이템 위치 재계산 및 화면에 표시
RecycleScrollView:CalculateOffset -- 스크롤 이동 시 경계를 벗어나지 않도록 오프셋 계산
RecycleScrollView:CanScroll -- 컨텐츠 크기에 따라 스크롤 가능 여부 판단
RecycleScrollView:SetItem -- 스크롤뷰에서 사용할 아이템 프리팩을 설정
RecycleScrollView:SetViewBounds -- 스크롤뷰의 보이는 영역 바운드 설정
RecycleScrollView:UpdateCell -- 스크롤 셀의 데이터를 업데이트하고 콜백 함수 호출
RecycleScrollView:OnMapLeave -- 맵을 떠날 때 스크롤뷰 상태 정리
RecycleScrollView:Clear -- 스크롤뷰의 모든 상태 변수들을 초기화
RecycleScrollView:SetContentRectSize -- 컨텐츠 영역의 크기를 설정하고 스크롤 상태 업데이트
RecycleScrollView:OnDrag -- 드래그 입력에 따라 스크롤 이동 처리 및 스크롤바 업데이트
RecycleScrollView:ChangedScroll -- 스크롤 상태 변경 시 스크롤바들을 업데이트
RecycleScrollView:GetStartOffset -- 정렬 타입에 따른 시작 오프셋 계산
RecycleScrollView:ScrollToIndex_Horizontal -- 수평 스크롤에서 지정된 인덱스로 스크롤 이동
RecycleScrollView:HandleUITouchBeginDragEvent -- 터치 드래그 시작 이벤트 처리
RecycleScrollView:HandleUITouchEndDragEvent -- 터치 드래그 종료 이벤트 처리
RecycleScrollView:HandleUITouchDragEvent -- 터치 드래그 중 이벤트 처리
RecycleScrollView:HandleUITouchEnterEvent -- 터치 영역 진입 이벤트 처리
RecycleScrollView:HandleUITouchExitEvent -- 터치 영역 이탈 이벤트 처리
RecycleScrollView:HandleMouseScrollEvent -- 마우스 스크롤 이벤트 처리
RecycleTest:Function1 -- 스크롤뷰 셀 아이템의 텍스트를 현재 인덱스로 업데이트
RecycleTest:OnBeginPlay -- 스크롤뷰 초기화 및 테스트 데이터 설정
RecycleTest:HandleKeyDownEvent -- 키보드 입력으로 스크롤뷰 테스트 기능 실행
ScrollBar:SetScrollNormalizedPosition -- 스크롤바의 정규화된 위치를 설정하고 스크롤뷰에 반영
ScrollBar:CalcNormalizedPosition -- 현재 스크롤바 핸들 위치를 기반으로 정규화된 위치값 계산
ScrollBar:SetScrollBar -- 스크롤뷰와 연결하여 스크롤바 크기와 위치 설정
ScrollBar:SetScrollPosition -- 스크롤 방향에 따라 스크롤바 핸들 위치 업데이트
ScrollBar:Clear -- 스크롤바 상태 초기화
ScrollBar:OnMapLeave -- 맵 떠날 때 스크롤바 상태 정리
ScrollBar:HandleUITouchBeginDragEvent -- 스크롤바 드래그 시작 시 초기 터치 위치 저장
ScrollBar:HandleUITouchDragEvent -- 스크롤바 드래그 중 위치 업데이트 처리
ScrollBar:HandleUITouchEndDragEvent -- 스크롤바 드래그 종료 시 드래그 상태 해제
ScrollItem:Reset -- 스크롤 아이템의 인덱스 값들을 초기화
ScrollItem:Init -- 스크롤 아이템을 실제 인덱스, 현재 인덱스, 엔티티로 초기화
ScrollMathLogic:GetTouchPoint -- 터치 포인트를 기준 해상도에 맞게 변환하여 정규화된 좌표 반환
OptimizeMobileMapResource:OnBeginPlay -- 모바일 최적화된 맵 리소스로 스프라이트 설정 및 크기 조정
OptimizeMobileResource:OnBeginPlay -- 모바일 최적화된 이미지 리소스로 스프라이트 GUI 렌더러 설정
ResourceLoadLogic:PreLoadResources -- 리소스 ID 배열을 받아 비동기로 사전 로드 수행
ResourceLoadLogic:UnloadResources -- 지정된 리소스들의 캐시를 제거하고 미사용 리소스 언로드
ResourceLoadLogic:AvatarResourcesLoad -- 현재 스테이지의 아바타 리소스들을 로드
ResourceLoadLogic:AvatarResourcesUnload -- 현재 스테이지의 아바타 리소스들을 언로드
ResourceLoadLogic:OnBeginPlay -- 게임 시작 시 모바일 리소스 테이블 초기화 및 기본 리소스 로드
ResourceLoadLogic:OptimizeMobileResource -- 모바일 플랫폼에서 최적화된 리소스 ID로 변환
ResourceLoadLogic:OptimizeMobileSize -- 모바일 플랫폼에서 크기 배수값을 반환, PC에서는 1 반환
ResourceLoadLogic:DialogAvatarRuids -- 지정된 스테이지의 아바타 리소스 ID들을 수집하여 반환
BMShopResourcePreloadLogic:OnBeginPlay -- 상점 리소스 사전 로드 로직 초기화
PlayerPrivateShop:OpenShopGroup -- 상점 그룹을 열고 필요시 시스템 리셋 요청
PlayerPrivateShop:CloseShopGroup -- 열려있는 상점 그룹을 닫기
PlayerPrivateShop:IsNeccesarySystemReset -- 상점에 시스템 리셋이 필요한지 시간 기준으로 확인
PlayerPrivateShop:RequestSystemResetShop -- 시스템 상점 리셋 요청 처리
PlayerPrivateShop:UpdateShop -- 상점 상품 목록을 업데이트하고 리셋 시간 설정
PlayerPrivateShop:RequestResetShopByMoney -- 돈으로 상점 리셋 요청 처리
PlayerPrivateShop:BuyProduct -- 상품 구매 처리 및 유효성 검사
PlayerPrivateShop:CanBuyProduct -- 상품 구매 가능 여부를 다양한 조건으로 검사
PlayerPrivateShop:OnSyncProperty -- 동기화 속성 변경 시 UI 새로고침 처리
PlayerPrivateShop:SaveToDB -- 개인 상점 데이터를 DB에 저장
PlayerPrivateShop:LoadFromDB -- DB에서 로드할 키 목록에 개인 상점 추가
PlayerPrivateShop:OnLoadedDataFromDB -- DB에서 로드된 개인 상점 데이터를 파싱하여 적용
PlayerPrivateShop:GetBuyMaxCountFromQuantity -- 상품의 최대 구매 가능 수량을 계산하여 반환
PlayerPrivateShop:GetNextSystemResetTime -- 다음 시스템 리셋 시간을 계산하여 반환
PlayerPrivateShop:BuyProductLog -- 상품 구매 성공 로그를 기록
PlayerPrivateShop:CancelBuyProductLog -- 상품 구매 실패 로그를 기록
PlayerPrivateShop:CanBuyFromCondition -- 상품 구매 조건을 만족하는지 확인
PlayerPrivateShop:FailMessageToServer -- 실패 메시지를 서버로 전송하여 로그 기록
ShopData:LoadFrom -- 데이터셋에서 상점 기본 정보를 로드
ShopDataLogic:LoadProductData -- 상점 상품 데이터셋을 로드하고 상점별로 분류
ShopDataLogic:LoadShopData -- 상점 기본 데이터셋을 로드하고 그룹별로 분류
ShopDataLogic:GetShopProductData -- 상품 ID로 상점 상품 데이터 반환
ShopDataLogic:GetShopData -- 상점 ID로 상점 데이터 반환
ShopDataLogic:OnBeginPlay -- 게임 시작 시 상점 관련 데이터들을 로드
ShopDataLogic:PickProductsByShopId -- 상점 ID에 따라 랜덤 확률로 상품들을 선택
ShopDataLogic:GetShopIdsByShopGroup -- 상점 그룹에 속한 상점 ID 목록 반환
ShopDataLogic:GetProductIdsByShopId -- 상점 ID에 속한 상품 ID 목록 반환
ShopDataLogic:CheckCanOpenShop -- 플레이어가 해당 상점을 열 수 있는지 조건 확인
ShopDataLogic:CheckProductUnlock -- 플레이어가 해당 상품을 해금했는지 조건 확인
ShopProductData:LoadFrom -- 데이터셋에서 상점 상품 정보를 로드
UIShop:OnBeginPlay -- UI 컴포넌트 초기화 및 이벤트 연결 설정
UIShop:Open -- 상점 그룹을 열고 접근 가능한 상점들을 표시
UIShop:Close -- 상점 UI를 닫고 관련 팝업들도 정리
UIShop:ClearData -- 상점 메뉴와 상품 데이터를 초기화
UIShop:GetOrCreateMenuRenderer -- 상점 메뉴 렌더러를 가져오거나 새로 생성
UIShop:GetOrCreateProductRenderer -- 상품 렌더러를 가져오거나 새로 생성
UIShop:ClearProductRenderer -- 상품 렌더러들을 비활성화하여 숨김
UIShop:OnShopSelected -- 선택된 상점의 상품들을 로드하고 UI 업데이트
UIShop:RefreshShop -- 상점 UI를 새로고침하여 최신 상태 반영
UIShop:OnResetedShop -- 상점이 리셋되었을 때 UI 새로고침 처리
UIShop:RefreshProducts -- 선택된 상점의 상품 목록을 새로고침하여 표시
UIShop:RefreshResetPrice -- 상점 리셋 가격을 계산하고 UI에 표시
UIShop:DisplayRemainResetTime -- 남은 리셋 시간을 계산하고 표시
UIShop:OnUpdate -- 매 프레임 리셋 시간을 확인하고 필요시 자동 리셋 요청
UIShop:OnResetButtonClicked -- 리셋 버튼 클릭 시 돈으로 상점 리셋 요청
UIShop:RefreshSubscriptionInfo -- 구독 상품 정보를 새로고침하여 UI에 표시
UIShop:HandleButtonClickEvent -- 일반 상점 열기 버튼 클릭 이벤트 처리
UIShop:HandleButtonClickEvent2 -- 직원 업그레이드 상점 열기 버튼 클릭 이벤트 처리
UIShop:HandleButtonClickEvent3 -- 구독 상점 열기 버튼 클릭 이벤트 처리
UIShop:HandleButtonClickEvent4 -- 네 번째 일반 상점 열기 버튼 클릭 이벤트 처리
UIShopMenuRenderer:Init -- 상점 ID로 메뉴 렌더러 초기화
UIShopMenuRenderer:OnBeginPlay -- UI 컴포넌트 초기화 및 자식 엔티티 참조 설정
UIShopMenuRenderer:OnUpdateBallonSprite -- 선택 상태에 따라 메뉴 배경 스프라이트 업데이트
UIShopMenuRenderer:OnUpdateTextColor -- 선택 상태에 따라 메뉴 텍스트 색상 업데이트
UIShopMenuRenderer:OnUpdateIconSprite -- 선택 상태에 따라 메뉴 아이콘 투명도 업데이트
UIShopMenuRenderer:InitUI -- 상점 메뉴 UI 요소들을 초기화
UIShopMenuRenderer:SetColorAndRuidForSpecialShop -- 특별 상점용 색상과 리소스 ID 설정
UIShopMenuRenderer:HandleButtonClickEvent -- 메뉴 버튼 클릭 시 상점 선택 이벤트 처리
UIShopProductRenderer:Init -- 상품 ID로 상품 렌더러 UI를 초기화
UIShopProductRenderer:RefreshUI -- 상품 UI 요소들을 새로고침하여 최신 상태 반영
UIShopProductRenderer:OnBeginPlay -- UI 컴포넌트 초기화 및 자식 엔티티 참조 설정
UIShopProductRenderer:RefreshPriceText -- 상품 가격 텍스트와 통화 아이콘을 업데이트
UIShopProductRenderer:InitSpecialShopItem -- 특별 상점 상품으로 UI를 초기화
UIShopProductRenderer:SetBlockComponent -- 상품 구매 차단 컴포넌트 활성화/비활성화 설정
UIShopProductRenderer:UpdatePriceTextColor -- 소유 자금과 비교하여 가격 텍스트 색상 업데이트
UIShopProductRenderer:HandleButtonClickEvent -- 상품 클릭 시 구매 팝업 열기 이벤트 처리
UIShopPurchasePopup:OnBeginPlay -- UI 컴포넌트 초기화 및 이벤트 연결 설정
UIShopPurchasePopup:Popup -- 일반 상점 상품 구매 팝업을 열고 상품 정보 표시
UIShopPurchasePopup:PopDown -- 구매 팝업을 닫고 애니메이션 처리
UIShopPurchasePopup:OnClickBuyButton -- 구매 버튼 클릭 시 일반/특별 상점에 따라 처리 분기
UIShopPurchasePopup:OnClickCancelButton -- 취소 버튼 클릭 시 팝업 닫기
UIShopPurchasePopup:UpdateText -- 일반 상점 구매 팝업의 텍스트와 가격 업데이트
UIShopPurchasePopup:OnModifyButtonClicked -- 수량 조절 버튼 클릭 시 구매 수량 변경 및 UI 업데이트
UIShopPurchasePopup:PurchaseProcess -- 일반 상점 상품 구매 처리 실행
UIShopPurchasePopup:Popup_SpecialShop -- 특별 상점 상품 구매 팝업을 열고 상품 정보 표시
UIShopPurchasePopup:UpdateText_SpecialShop -- 특별 상점 구매 팝업의 텍스트와 가격 업데이트
UIShopPurchasePopup:PurchaseProcess_SpecialShop -- 특별 상점 상품 구매 처리 실행
UIShopPurchasePopup:SpecialShopPurchasePriceCheck -- 특별 상점 상품 구매 가격 및 재화 제한 확인
UIStagePassBackgroundRenderer:ResetResourcesBackgroundByGroupId -- 그룹 ID에 따라 스테이지 패스 배경 리소스를 설정
UIStagePassBackgroundRenderer:OnBeginPlay -- 스테이지 패스 배경 리소스 데이터 초기화
BMDropDownLogic:HandleButtonClickEvent2 -- 스페셜 샵 열기 버튼 클릭 이벤트 처리
BMDropDownLogic:HandleButtonClickEvent3 -- 스테이지 패스 열기 버튼 클릭 이벤트 처리
BMDropDownLogic:HandleButtonClickEvent -- 부스터 팩 열기 버튼 클릭 이벤트 처리
PaidLogic:OnBeginPlay -- 서버에서 결제 콜백 설정
PaidLogic:PurchaseCallback -- 월드샵 구매 콜백 처리 및 검증
PaidLogic:NotifyPurchaseToClient -- 클라이언트에 구매 완료 알림 및 UI 업데이트
PaidLogic:OnPurchaseCountChanged -- 구매 횟수 변경 시 클라이언트 알림
PaidLogic:RequestPurchaseWorldShopProduct_SpecialShop -- 스페셜 샵 월드샵 상품 구매 요청 처리
PaidLogic:RequestPurchaseDiamondProduct_SpecialShop -- 스페셜 샵 다이아몬드 상품 구매 요청 처리
PaidLogic:PromptPurchase -- 월드샵 구매 프롬프트 표시
PaidLogic:GivePurchaseItem -- 구매한 아이템을 플레이어에게 지급
PaidLogic:SendPurchaseResult -- 구매 결과를 보상 UI로 표시
PaidLogic:RequestPurchaseEmployeeEquip -- 직원 장비 구매 요청 처리 및 지급
PaidLogic:RequestUpgradeEmployeeEquip -- 직원 장비 업그레이드 요청 처리 및 확률 계산
PaidLogic:NotifyPurchaseEmployeeEquipToClient -- 직원 장비 구매 완료를 클라이언트에 알리고 UI 업데이트
PaidLogic:NotifyUpgradeEmployeeEquipToClient -- 직원 장비 업그레이드 결과를 클라이언트에 알림
PaidLogic:UpgradeProcess -- 업그레이드 확률 계산 및 랜덤 시드 설정
PaidLogic:CommonLog -- 공통 로그 출력 (비어있음)
PaidLogic:EmployeeEquipUpgradeSimulator1 -- 직원 장비 업그레이드 시뮬레이터 1 (지정 레벨 획수 테스트)
PaidLogic:EmployeeEquipUpgradeSimulator2 -- 직원 장비 업그레이드 시뮬레이터 2 (전체 레벨 비용 계산)
PaidLogic:RequestPurchaseWorldShopProduct_StagePass -- 스테이지 패스 월드샵 상품 구매 요청 처리
PaidLogic:PurchaseCallback_SpecialShop -- 스페셜 샵 구매 콜백 처리 및 검증
PaidLogic:PurchaseCallback_StagePass -- 스테이지 패스 구매 콜백 처리 및 데이터 업데이트
PaidLogic:PurchaseProcessByShopType -- 샵 타입에 따른 구매 처리 분기 및 실행
PaidLogic:RequestGetReward_StagePass -- 스테이지 패스 보상 수령 요청 처리
PaidLogic:RequestGetPurchaseReward_StagePass -- 스테이지 패스 구매 보상 수령 요청 처리
PaidLogic:SendItemOverMaxCountPopup -- 아이템 최대 수량 초과 알림 팝업 표시
PaidLogic:AddEarnings_PiggyBank -- 피기뱅크 수익 추가 및 데이터 저장
PaidLogic:RequestReceiveReward_PiggyBank -- 피기뱅크 보상 수령 요청 처리
PaidLogic:RequestPurchaseWorldShopProduct_PiggyBank -- 피기뱅크 월드샵 상품 구매 요청 처리
PaidLogic:PurchaseCallback_PiggyBank -- 피기뱅크 구매 콜백 처리 및 레벨 검증
PaidLogic:RequestPurchase_BoosterPack -- 부스터 팩 구매 요청 처리 및 검증
PurchaseLogLogic:PurchaseSuccessLog -- 구매 성공 로그 기록
PurchaseLogLogic:PurchaseSuccessLog_SpecialShop_WorldCoin -- 스페셜 샵 월드코인 구매 성공 로그 기록
PurchaseLogLogic:PurchaseSuccessLog_SpecialShop_Diamond -- 스페셜 샵 다이아몬드 구매 성공 로그 기록
PurchaseLogLogic:PurchaseSuccessLog_StagePass -- 스테이지 패스 구매 성공 로그 기록
PurchaseLogLogic:PurchaseSuccessLog_PiggyBank -- 피기뱅크 구매 성공 로그 기록
PurchaseLogLogic:PurchaseSuccessLog_BoosterPack -- 부스터 팩 구매 성공 로그 기록
PurchaseLogLogic:PurchaseFailLog -- 구매 실패 로그 기록
PurchaseLogLogic:PurchaseFailLog_InvalidEntity -- 잘못된 엔티티로 인한 구매 실패 로그 기록
PurchaseLogLogic:PurchaseFailLog_FailOnPrompt -- 구매 프롬프트 실패 로그 기록
PurchaseLogLogic:PurchaseFailLog_InvalidProductId -- 잘못된 상품 ID로 인한 구매 실패 로그 기록
PurchaseLogLogic:PurchaseFailLog_UnauthorizedPiggyBank -- 피기뱅크 무단 구매 시도 실패 로그 기록
PurchaseLogLogic:PurchaseFailLog_UnauthorizedBoosterPack -- 부스터 팩 무단 구매 시도 실패 로그 기록
PurchaseLogLogic:PurchaseFailLog_DiamondLack -- 다이아몬드 부족으로 인한 구매 실패 로그 기록
PurchaseLogLogic:PurchaseFailLog_SpecialShop_AddStorageFail -- 스페셜 샵 인벤토리 추가 실패 로그 기록
PurchaseLogLogic:StagePassCompleteLog -- 스테이지 패스 보상 수령 완료 로그 기록
PurchaseLogLogic:PiggyBankLevelUpRewardLog -- 피기뱅크 레벨업 보상 로그 기록
PurchaseLogLogic:PiggyBankFlowLog -- 피기뱅크 포인트 흐름 로그 기록
PurchaseLogLogic:StorageFlowLog -- 인벤토리 흐름 로그 기록
PurchaseLogLogic:AllLoggingForTest -- 테스트용 전체 로깅
PurchaseLogLogic:CheckCanTimeFlowsLog -- 클라이언트 시간 흐름 검증 로그 기록
UIPurchasePopupLogic:OpenPurchaseConfirmPopup_Immediately -- 구매 확인 팝업을 즉시 열기
UIPurchasePopupLogic:OpenWithdrawalNoticePopup -- 취소 알림 팝업 열기
UIPurchasePopupLogic:OpenOverMaxCountPopup -- 최대 수량 초과 알림 팝업 열기
UIPurchasePopupLogic:OpenNoRefunablePurchasePopup -- 환불 불가 구매 팝업 열기
UIPurchasePopupLogic:OnClose -- 팝업 닫기 이벤트 처리
UIPurchasePopupLogic:OnOk -- 팝업 확인 이벤트 처리
BoosterPackData:LoadFrom -- 데이터셋에서 부스터 팩 데이터를 로드
BoosterPackDataLogic:OnBeginPlay -- 게임 시작 시 부스터 팩 데이터 로드
BoosterPackDataLogic:LoadBoosterPackDataSet -- 부스터 팩 데이터셋을 로드하여 테이블에 저장
BoosterPackDataLogic:GetBoosterPackData -- 스테이지 ID로 부스터 팩 데이터 조회
UIBoosterPack:Open -- 부스터 팩 UI를 열고 초기화
UIBoosterPack:Close -- 부스터 팩 UI를 닫고 콜백 실행
UIBoosterPack:OnUpdateBoosterPackButtonExpose -- 부스터 팩 버튼 노출 상태 업데이트
UIBoosterPack:TitleAnimation -- 제목 애니메이션 실행
UIBoosterPack:OpenAndRegisterPiggyBankOpenCallback -- 부스터 팩을 열고 닫을 때 피기뱅크를 열도록 콜백 등록
UIBoosterPack:HandleButtonClickEvent2 -- 샵에서 부스터 팩 버튼 클릭 이벤트 처리
UIBoosterPack:HandleButtonClickEvent -- 부스터 팩 닫기 버튼 클릭 이벤트 처리
UIBoosterPack:HandlePlayerManagementChangedEvent -- 플레이어 경영 상태 변경 시 부스터 팩 버튼 업데이트
UIBoosterPack:HandlePlayerBoosterPackPurchaseChangedEvent -- 플레이어 부스터 팩 구매 상태 변경 시 버튼 업데이트
UIBoosterPack:HandlePlayerPurchaseCountChangedEvent -- 플레이어 구매 카운트 변경 시 버튼 업데이트
UIBoosterPackRenderer:OnBeginPlay -- 부스터 팩 렌더러 UI 컴포넌트 초기화
UIBoosterPackRenderer:Init -- 부스터 팩 슬롯 초기화 및 데이터 설정
UIBoosterPackRenderer:OnClickPurchaseButton -- 부스터 팩 구매 버튼 클릭 이벤트 처리
UIBoosterPackRenderer:ResetPurchaseButton -- 구매 버튼 상태 및 표시 업데이트
UIBoosterPackRenderer:GetBoosterPackPurchased -- 해당 스테이지의 부스터 팩 구매 여부 확인
UIBoosterPackRenderer:HandlePlayerBoosterPackPurchaseChangedEvent -- 플레이어 부스터 팩 구매 상태 변경 시 버튼 업데이트
UIBoosterPackRenderer:HandlePlayerPurchaseCountChangedEvent -- 플레이어 구매 카운트 변경 시 프리미엄 부스터 팩 버튼 업데이트
EmployeeEquipUpgradeDataLogic:OnBeginPlay -- 게임 시작 시 직원 장비 업그레이드 데이터 로드
EmployeeEquipUpgradeDataLogic:LoadEmployeeEquipUpgradeDataSet -- 직원 장비 업그레이드 데이터셋을 로드하여 테이블에 저장
EmployeeEquipUpgradeDataLogic:GetEmployeeEquipUpgrageData -- 장비 레벨에 따른 업그레이드 데이터 조회
UIEmployeeEquipShop:OnPurchaseEquipCompleted -- 직원 장비 구매 완료 시 처리
UIEmployeeEquipShop:OnClickBuyEqiup -- 직원 장비 구매 버튼 클릭 이벤트 처리
UIEmployeeEquipShop:OnClickGotoShop -- 샵으로 이동하여 아이템 구매 팝업 열기
UIEmployeeEquipShop:OpenGotoShopPopup -- 샵 이동 확인 팝업 열기
UIEmployeeEquipShop:OnClickUpgradeEquip -- 직원 장비 업그레이드 버튼 클릭 이벤트 처리
UIEmployeeEquipShop:OnUpgradeEquipCompleted -- 직원 장비 업그레이드 완료 시 처리 및 이팩트 표시
UIEmployeeEquipShop:HandleButtonClickEvent -- 직원 장비 구매 버튼 클릭 이벤트 처리
UIEmployeeEquipShop:HandleButtonClickEvent2 -- 직원 장비 업그레이드 버튼 클릭 이벤트 처리
EmployeeEquipUpgradeData:LoadFrom -- 데이터셋에서 직원 장비 업그레이드 데이터를 로드
PiggyBankBtn:OnBeginPlay -- 저금통 버튼의 게이지와 텍스트 컴포넌트를 초기화
PiggyBankBtn:HandlePlayerPiggyBankPointChangedEvent -- 플레이어의 저금통 포인트 변경 시 게이지와 텍스트를 업데이트
PiggyBankDataLogic:OnBeginPlay -- 저금통 데이터 로직 초기화 시 레벨 데이터와 보상 데이터를 로드
PiggyBankDataLogic:LoadPiggyBankLevelDataSet -- CSV 파일에서 저금통 레벨별 데이터를 로드하여 테이블에 저장
PiggyBankDataLogic:LoadPiggyBankLevelUpRewardDataSet -- CSV 파일에서 저금통 레벨업 보상 데이터를 로드하여 테이블에 저장
PiggyBankDataLogic:GetPiggyBankLevelData -- 레벨에 해당하는 저금통 레벨 데이터를 반환
PiggyBankDataLogic:GetPiggyBankLevelDataByProductId -- 상품 ID에 해당하는 저금통 레벨 데이터를 반환
PiggyBankDataLogic:GetPiggyBankRewardData -- 슬롯 ID에 해당하는 저금통 보상 데이터를 반환
PiggyBankLevelData:LoadFrom -- CSV 데이터 행에서 저금통 레벨 데이터의 모든 속성을 로드
PiggyBankLevelUpRewardData:LoadFrom -- CSV 데이터 행에서 저금통 레벨업 보상 데이터의 모든 속성을 로드
UIPiggyBank:OnBeginPlay -- 저금통 UI 초기화 및 스크롤뷰와 버튼 엔티티 설정
UIPiggyBank:Init -- 저금통 UI의 모든 요소를 플레이어 데이터에 맞게 초기화
UIPiggyBank:Close -- 저금통 UI 그룹을 비활성화하여 닫기
UIPiggyBank:Open -- 저금통 UI 그룹을 활성화하고 초기화하여 열기
UIPiggyBank:InitBottomSection -- 저금통 레벨업 보상 섹션을 동적으로 생성하고 초기화
UIPiggyBank:ResetGaugeFillSprite -- 현재 포인트에 따라 게이지 채우기 스프라이트 크기를 조정
UIPiggyBank:OnUpdatePoint -- 포인트 변경 시 배경 이미지와 텍스트, 게이지를 업데이트
UIPiggyBank:OnUpdateLevel -- 레벨 변경 시 UI의 모든 레벨 관련 요소들을 업데이트
UIPiggyBank:ResetMidSectionUI -- 현재 레벨에 따라 중간 섹션 UI를 최대 레벨 도달 여부에 따라 설정
UIPiggyBank:ResetRedDot -- 수령 가능한 보상이 있는지 확인하여 빨간 점 표시 상태를 설정
UIPiggyBank:ResetMaxPointTextPositionByGauge -- 게이지 너비에 따라 최대 포인트 텍스트의 위치를 조정
UIPiggyBank:ResetDiscountRate -- 레벨에 따라 할인율 텍스트 표시 여부와 내용을 설정
UIPiggyBank:ResetPolicyText -- 레벨에 따라 정책 설명 텍스트 표시 여부와 내용을 설정
UIPiggyBank:HandleButtonClickEvent -- 닫기 버튼 클릭 시 닫기 사운드 재생 후 UI 닫기
UIPiggyBank:HandleButtonClickEvent2 -- 저금통 열기 버튼 클릭 시 UI 열기
UIPiggyBank:HandleButtonClickEvent3 -- 저금통 열기 버튼 클릭 시 UI 열기
UIPiggyBank:HandleButtonClickEvent4 -- 저금통 구매 버튼 클릭 시 포인트 가득참 여부 확인 후 구매 처리
UIPiggyBank:HandlePlayerPiggyBankPointChangedEvent -- 플레이어 저금통 포인트 변경 시 UI 업데이트
UIPiggyBank:HandlePlayerPiggyBankLevelChangedEvent -- 플레이어 저금통 레벨 변경 시 UI 업데이트 또는 빨간 점만 업데이트
UIPiggyBank:HandlePlayerPiggyBankRewardReceivedChangedEvent -- 플레이어 저금통 보상 수령 상태 변경 시 빨간 점 상태 업데이트
UIPiggyBank:HandleButtonClickEvent5 -- 환불 관련 버튼 클릭 시 철회 안내 팝업 열기
UIPiggyBank:HandlePlayerNowStageChangedEvent -- 플레이어 현재 스테이지 변경 시 저금통 버튼 활성화 여부 설정
UIPiggyBankLevelUpRewardSlot:OnBeginPlay -- 저금통 레벨업 보상 슬롯의 UI 컴포넌트들을 초기화하고 클릭 이벤트 연결
UIPiggyBankLevelUpRewardSlot:Init -- 슬롯 ID에 해당하는 보상 데이터로 UI를 초기화
UIPiggyBankLevelUpRewardSlot:ResetUIChangedByPlayerData -- 플레이어 데이터에 따라 슬롯의 상태와 UI를 업데이트
UIPiggyBankLevelUpRewardSlot:HandlePlayerPiggyBankLevelChangedEvent -- 플레이어 저금통 레벨 변경 시 슬롯 UI를 업데이트
UIPiggyBankLevelUpRewardSlot:HandlePlayerPiggyBankRewardReceivedChangedEvent -- 플레이어 저금통 보상 수령 상태 변경 시 슬롯 UI를 업데이트
SpecialShopDataLogic:OnBeginPlay -- 게임 시작 시 특별 상점 데이터셋을 로드
SpecialShopDataLogic:LoadAllDataSet -- 클라이언트에서 모든 특별 상점 관련 데이터셋을 로드
SpecialShopDataLogic:LoadSpecialShopDataSet -- 특별 상점 기본 정보 데이터셋을 로드
SpecialShopDataLogic:LoadSpecialShopProductDataSet -- 특별 상점 상품 데이터셋을 로드하고 상점별로 분류
SpecialShopDataLogic:LoadSpecialShopProductModelDataSet -- 클라이언트에서 특별 상점 상품 UI 모델 데이터셋을 로드
SpecialShopDataLogic:HasRemainingStock -- 상품의 구매 가능 재고가 남아있는지 확인
SpecialShopDataLogic:FilterSpecialProductDataByCondition -- 조건에 맞는 특별 상점 상품 데이터를 필터링하여 반환
SpecialShopDataLogic:IsCurrenyWorldCoin -- 상품이 월드 코인으로 구매하는 상품인지 확인
SpecialShopDataLogic:AbnormalLog -- 비정상 상황에 대한 로그 기록
SpecialShopDataLogic:CommonLog -- 일반적인 로그 메시지 기록
UIItemDetailSlot:OnBeginPlay -- UI 컴포넌트 초기화 및 자식 엔티티 참조 설정
UIItemDetailSlot:Init -- 아이템 상세 슬롯을 초기화하고 아이콘과 개수 표시
UIItemDetailSlot:HandleButtonClickEvent -- 슬롯 클릭 시 아이템 설명 툴팁 표시
UISpecialShop:Open -- 특별 상점 UI를 열고 상점 메뉴와 상품들을 정렬하여 표시
UISpecialShop:Close -- 특별 상점 UI를 닫고 관련 팝업들도 닫기
UISpecialShop:ClearData -- 상점 메뉴와 상품 데이터를 초기화
UISpecialShop:ClearProductRenderer -- 상품 렌더러들을 비활성화하여 화면에서 숨김
UISpecialShop:GetOrCreateMenuRenderer -- 상점 메뉴 렌더러를 가져오거나 새로 생성
UISpecialShop:OnShopSelected -- 선택된 상점의 상품들을 로드하고 UI 업데이트
UISpecialShop:GetProductsByUserPurchaseCount -- 사용자 구매 횟수에 따라 표시할 상품들을 필터링
UISpecialShop:HasRemainingProduct -- 해당 상점에 구매 가능한 상품이 남아있는지 확인
UISpecialShop:OpenPurchasePopup -- 특정 아이템 ID에 대한 구매 팝업을 열기
UISpecialShop:OnUpdateCallback -- 상품 렌더러를 업데이트하여 상품 정보 표시
UISpecialShop:HandleButtonClickEvent -- 특별 상점 열기 버튼 클릭 이벤트 처리
UISpecialShop:HandleButtonClickEvent2 -- 특별 상점 닫기 버튼 클릭 이벤트 처리
UISpecialShop:HandleButtonClickEvent3 -- 출금 안내 팝업 열기 버튼 클릭 이벤트 처리
UISpecialShop:HandleButtonClickEvent4 -- 두 번째 특별 상점 열기 버튼 클릭 이벤트 처리
UISpecialShop:HandleButtonClickEvent5 -- 두 번째 출금 안내 팝업 열기 버튼 클릭 이벤트 처리
UISpecialShopProduct:OnBeginPlay -- UI 컴포넌트 초기화 및 자식 엔티티들 참조 설정
UISpecialShopProduct:Init -- 특별 상점 상품 UI를 초기화하고 데이터에 따라 설정
UISpecialShopProduct:SetUINextLevelProduct -- 다음 레벨 상품으로 UI를 업데이트
UISpecialShopProduct:SetUIBlock -- 상품 UI를 차단하거나 활성화 상태로 설정
UISpecialShopProduct:ResetProductPurhaseState -- 상품 구매 상태에 따라 UI 상태를 리셋
UISpecialShopProduct:OpenPurchaseCheckPopup -- 구매 확인 팝업을 열고 상품 타입에 따라 처리
UISpecialShopProduct:OnClickPurchaseButton -- 구매 버튼 클릭 시 사운드 재생 및 팝업 열기
UISpecialShopProduct:ResetEntitiesByBlockUI -- 차단 UI 상태에 따라 관련 UI 요소들을 리셋
UISpecialShopProduct:HandleButtonClickEvent -- 상품 클릭 시 패키지 또는 일반 상품에 따라 처리 분기
UISpecialShopProduct:HandlePlayerDiamondChangedEvent -- 플레이어 다이아몬드 변경 시 가격 텍스트 색상 업데이트
SpecialShopData:LoadFrom -- 데이터셋에서 특별 상점 데이터를 로드하여 속성에 설정
SpecialShopProductData:LoadFrom -- 데이터셋에서 특별 상점 상품 데이터를 로드하여 속성에 설정
SpecialShopProductModelData:LoadFrom -- 데이터셋에서 특별 상점 상품 모델 UI 표시 정보를 로드
StagePassDataLogic:OnBeginPlay -- 게임 시작 시 모든 스테이지 패스 데이터셋을 로드하는 함수
StagePassDataLogic:LoadStagePassGroupDataSet -- 스테이지 패스 그룹 데이터를 CSV에서 로드하여 초기화하는 함수
StagePassDataLogic:LoadStagePassProductDataSet -- 스테이지 패스 상품 데이터를 CSV에서 로드하여 초기화하는 함수
StagePassDataLogic:LoadStagePassLevelDataSet -- 스테이지 패스 레벨 데이터를 CSV에서 로드하여 초기화하는 함수
StagePassDataLogic:LoadStagePassRewardDataSet -- 스테이지 패스 보상 데이터를 CSV에서 로드하여 초기화하는 함수
StagePassDataLogic:IsWorldCoinProduct -- 해당 상품이 월드 코인 상품인지 확인하는 함수
StagePassDataLogic:IsPassProductPurchased -- 사용자가 해당 패스 상품을 구매했는지 확인하는 함수
StagePassDataLogic:CanReceiveReward -- 사용자가 해당 보상을 받을 수 있는지 확인하는 함수
StagePassDataLogic:GetStagePassProductData -- 상품 ID로 스테이지 패스 상품 데이터를 반환하는 함수
UIStagePass:OnBeginPlay -- 스테이지 패스 UI 초기화 시 실행되는 함수
UIStagePass:Open -- 스테이지 패스 UI를 열고 초기화하는 함수
UIStagePass:Close -- 스테이지 패스 UI를 닫는 함수
UIStagePass:ResetPassGroupTab -- 패스 그룹 탭을 리셋하는 함수
UIStagePass:ResetUIsByGroupTab -- 그룹 탭에 따라 UI를 리셋하는 함수
UIStagePass:ResetPassLevelBar -- 패스 레벨 바를 리셋하는 함수
UIStagePass:GetOrCreatGroupTabRenderer -- 그룹 탭 렌더러를 가져오거나 생성하는 함수
UIStagePass:HandlePurchaseCountChangedEvent -- 구매 횟수 변경 이벤트를 처리하는 함수
UIStagePass:GetOrCreatePassLevelRenderer -- 패스 레벨 렌더러를 가져오거나 생성하는 함수
UIStagePass:OnChangedSelectedGroup -- 선택된 그룹이 변경될 때 처리하는 함수
UIStagePass:DisableGroupEntity -- 그룹 엔티티를 비활성화하는 함수
UIStagePass:DisableLevelEntity -- 레벨 엔티티를 비활성화하는 함수
UIStagePass:AddEnableReward -- 보상 활성화를 추가하는 함수
UIStagePass:RemoveEnableReward -- 보상 활성화를 제거하는 함수
UIStagePass:ResetPassProductButton -- 패스 상품 버튼을 리셋하는 함수
UIStagePass:RegisterRecycleScrollLayoutCallback -- 리사이클 스크롤 레이아웃 콜백을 등록하는 함수
UIStagePass:OnClickPurchasePassProductButton -- 패스 상품 구매 버튼 클릭 시 처리하는 함수
UIStagePass:SetScrollToRewardSlotId -- 보상 슬롯 ID로 스크롤을 설정하는 함수
UIStagePass:GetEnableRewards -- 활성화된 보상 목록을 가져오는 함수
UIStagePass:ResetRedDot -- 빨간 점 표시를 리셋하는 함수
UIStagePass:HasTotalRewards -- 총 보상이 있는지 확인하는 함수
UIStagePass:ResetGroupTabRedDot -- 그룹 탭의 빨간 점을 리셋하는 함수
UIStagePass:HasReward -- 보상이 있는지 확인하는 함수
UIStagePass:HasPurchaseReward -- 구매 보상이 있는지 확인하는 함수
UIStagePass:HandleButtonClickEvent -- 닫기 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePass:HandleButtonClickEvent2 -- 스테이지 패스 열기 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePass:HandleButtonClickEvent3 -- 모든 보상 받기 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePass:HandleButtonClickEvent4 -- 첫 번째 상품 구매 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePass:HandleButtonClickEvent5 -- 두 번째 상품 구매 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePass:HandlePlayerStagePassRewardReceivedChangedEvent -- 플레이어 스테이지 패스 보상 수령 상태 변경 이벤트를 처리하는 핸들러
UIStagePass:HandlePlayerStagePassPurchaseRewardReceivedChangedEvent -- 플레이어 스테이지 패스 구매 보상 수령 상태 변경 이벤트를 처리하는 핸들러
UIStagePass:HandleplayerStageProgressChangedEvent -- 플레이어 스테이지 진행도 변경 이벤트를 처리하는 핸들러
UIStagePassGroup:ResetUIActivated -- UI를 활성화 상태로 재설정하는 함수
UIStagePassGroup:ResetUIDeactivated -- UI를 비활성화 상태로 재설정하는 함수
UIStagePassGroup:OnBeginPlay -- 게임 시작 시 빨간 점 UI 컴포넌트를 초기화하는 함수
UIStagePassGroup:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePassLevel:OnBeginPlay -- 게임 시작 시 UI 컴포넌트들을 초기화하는 함수
UIStagePassLevel:Init -- 스테이지 패스 레벨 데이터로 UI를 초기화하는 함수
UIStagePassLevel:SetUILevelByRewardStatus -- 보상 상태에 따라 레벨 UI를 설정하는 함수
UIStagePassLevel:SetUIRewards -- 보상 UI를 설정하는 함수
UIStagePassLevel:SetUILevelByProgress -- 진행도에 따라 레벨 UI를 설정하는 함수
UIStagePassPageButton:OnBeginPlay -- 게임 시작 시 UI 컴포넌트를 초기화하는 함수
UIStagePassPageButton:Init -- 보상 슬롯 ID로 페이지 버튼을 초기화하는 함수
UIStagePassPageButton:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePassProduct:OnBeginPlay -- 게임 시작 시 UI 컴포넌트들을 초기화하는 함수
UIStagePassProduct:Init -- 스테이지 패스 상품 데이터로 UI를 초기화하는 함수
UIStagePassProduct:OnRewardInfoButtonClick -- 보상 정보 버튼 클릭 시 처리하는 함수
UIStagePassProduct:OnClickPurchaseButton -- 구매 버튼 클릭 시 처리하는 함수
UIStagePassProduct:OnOkCallback -- 구매 확인 콜백 함수
UIStagePassProduct:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePassPurchaseReward:OnBeginPlay -- 게임 시작 시 UI 컴포넌트를 초기화하는 함수
UIStagePassPurchaseReward:Init -- 상품 ID로 구매 보상을 초기화하는 함수
UIStagePassPurchaseReward:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UIStagePassPurchaseReward:HandlePlayerStagePassPurchaseRewardReceivedChangedEvent -- 플레이어 스테이지 패스 구매 보상 수령 변경 이벤트를 처리하는 핸들러
StagePassGroupData:LoadFrom -- 데이터셋에서 스테이지 패스 그룹 데이터를 로드
StagePassLevelData:LoadFrom -- 데이터셋에서 스테이지 패스 레벨 데이터를 로드
StagePassProductData:LoadFrom -- 데이터셋에서 스테이지 패스 상품 데이터를 로드
StagePassRewardData:LoadFrom -- 데이터셋에서 스테이지 패스 보상 데이터를 로드
Extend_UIRewardInfoSpecialShop:Init -- 특별 상점 상품의 보상 정보 UI를 초기화
Extend_UIRewardInfoSpecialShop:SetPolicyText -- 상품 타입에 따라 정책 안내 텍스트를 설정
Extend_UIRewardInfoStagePass:Init -- 스테이지 패스 상품의 보상 정보 UI를 초기화
UIRewardInfo:ConnectEntities -- UI 엔티티들을 연결하고 참조 설정
UIRewardInfo:OnBeginPlay -- UI 초기화 및 이벤트 연결 설정
UIRewardInfo:OnClickCloseButton -- 보상 정보 팝업 닫기 버튼 처리
UIRewardInfo:OnClickPurchaseButton -- 보상 정보에서 구매 버튼 클릭 처리
UIRewardItem:OnBeginPlay -- UI 컴포넌트 초기화 및 자식 엔티티 참조 설정
UIRewardItem:Init -- 스테이지 패스 보상 아이템 UI를 초기화
UIRewardItem:SetUIByRewardStatus -- 보상 상태에 따라 UI 모양을 업데이트
UIRewardItem:HandleButtonClickEvent -- 보상 아이템 클릭 시 보상 수령 또는 툴팁 표시
UIRewardItem:HandlePlayerStagePassRewardReceivedChangedEvent -- 플레이어 스테이지 패스 보상 수령 상태 변경 시 UI 업데이트
UIRewardSumSlot:OnBeginPlay -- UI 컴포넌트 초기화 및 이벤트 연결
UIRewardSumSlot:Init -- 보상 요약 슬롯을 초기화하고 아이템 정보 표시
TitleEmployee:OnBeginPlay -- 타이틀 화면에 표시할 랜덤 직원과 버거 스택을 설정
TitleEmployee:MoveStart -- 직원이 화면을 가로질러 이동하는 애니메이션 시작
TitleManager:OnMapEnter -- 타이틀 맵 진입 시 초기화 및 UI 활성화
TitleManager:ReadyForEnterToWorld -- 월드 진입 준비 및 다음 맵 결정
TitleManager:PassCheckServer -- 인트로 시청 여부를 확인하여 버튼 상태 설정
TitleManager:SetButtonAfterCheckPass -- 패스 체크 결과에 따른 버튼 상태 설정
TitleManager:OpenTitleUI -- 타이틀 UI 활성화 및 리소스 프리로드
TitleManager:ResetData -- 플레이어 데이터 초기화 및 추방 처리
TitleManager:RequestResetDataFromClient -- 클라이언트에서 데이터 초기화 요청 처리
TitleManager:ShowFade -- 페이드 효과와 함께 다음 맵으로 이동
TitleManager:MoveToNextMap -- 맵 이름에 따른 목적지 경로 설정 및 텔레포트
TitleManager:SetDataFixButton -- 데이터 수정 버튼 활성화/비활성화
TitleManager:SetDataResetButton -- 데이터 리셋 버튼 활성화/비활성화
TitleManager:HandleKeyDownEvent -- 키 입력 이벤트를 처리하는 핸들러
UITitle:TitleUIOn -- 타이틀 UI 활성화 및 데코 애니메이션 시작
UITitle:TitleUIOff -- 타이틀 UI 비활성화 및 타이머 정리
UITitle:ToggleResetPopup -- 데이터 리셋 팝업 표시/숨기기 및 입력 필드 초기화
UITitle:SetButtonScroll -- 패스 체크 결과에 따른 게임 시작 버튼 설정
UITitle:OnGameStartButton -- 게임 시작 버튼 클릭 시 인트로/로비 진입 처리
UITitle:OnClickDataReset -- 데이터 리셋 버튼 클릭 시 입력 확인 및 처리
UITitle:OnClickGoToTitleButton -- 타이틀로 돌아가기 버튼 클릭 처리
UITitle:OnClickInfoButton -- 정보 버튼 클릭 시 정보 팝업 표시
UITitle:ToggleInfoPopup -- 정보 팝업 표시/숨기기
UITitle:CloseAllPopup -- 모든 팝업 닫기
UITitle:EnableFixDataButton -- 데이터 수정 버튼 활성화 상태 설정
UITitle:SpawnDeco -- 타이틀 화면에 데코용 직원 스폰 및 이동 애니메이션
UITitle:ToggelToastAlpha -- 그래픽 설정 토스트 알파 깜박임 애니메이션
UITitle:TweenDecoCharacter -- 타이틀 캐릭터 좌우 이동 애니메이션
UITitle:HandleButtonClickEvent3 -- 게임 시작 버튼 클릭 이벤트 처리
UITitle:HandleButtonClickEvent4 -- 데이터 리셋 버튼 클릭 이벤트 처리
UITitle:HandleButtonClickEvent5 -- 리셋 팝업 닫기 버튼 클릭 이벤트 처리
UITitle:HandleButtonClickEvent8 -- 타이틀로 돌아가기 확인 버튼 클릭 이벤트 처리
UITitle:HandleButtonClickEvent9 -- 정보 버튼 클릭 이벤트 처리
UITitle:HandleButtonClickEvent10 -- 정보 팝업 닫기 버튼 클릭 이벤트 처리
TweenCurveLogic:GetTweenValue -- 키프레임 기반 트윈 값 계산 (베지어 곡선 지원)
TweenCurveLogic:BezierInterpolation -- 베지어 곡선 보간 계산
TweenCurveLogic:GetTweenEnumByString -- 문자열로 EaseType 열거형 값 반환
UIAnimation:OnBeginPlay -- CSV 데이터를 기반으로 UI 애니메이션 클립 초기화
UIAnimation:OnUpdate -- 매 프레임 애니메이션 업데이트 및 트윈 처리
UIAnimation:Play -- 애니메이션 재생 시작
UIAnimation:UpdateNextFrame -- 다음 프레임 데이터로 UI 속성 업데이트
UIAnimation:TweenNextFrame -- 이전 프레임과 다음 프레임 사이의 트윈 처리
UITweenAlpha:OnBeginPlay -- 알파 트윈 초기화 및 자동 재생 설정
UITweenAlpha:OnUpdate -- 매 프레임 알파 값 계산 및 적용
UITweenAlpha:Play -- 알파 트윈 재생 시작
UITweenAlpha:PoingPonng -- 핑폰 루프 계산 (앞뒤로 반복)
UITweenAlpha:Repeat -- 일반 루프 계산 (반복)
UITweenAlpha:Stop -- 알파 트윈 정지
UITweenCansvasGroupAlpha:OnBeginPlay -- 캔버스 그룹 알파 트윈 초기화
UITweenCansvasGroupAlpha:OnUpdate -- 매 프레임 캔버스 그룹 알파 값 업데이트
UITweenCansvasGroupAlpha:Play -- 캔버스 그룹 알파 트윈 재생 시작
UITweenCansvasGroupAlpha:PoingPonng -- 핑폰 루프 계산
UITweenCansvasGroupAlpha:Repeat -- 일반 루프 계산
UITweenCansvasGroupAlpha:Stop -- 캔버스 그룹 알파 트윈 정지
UITweenClick:OnBeginPlay -- 버튼 클릭 트윈 초기화 및 특수 케이스 처리
UITweenClick:Pressed -- 버튼 눌렸을 때 크기 축소 애니메이션
UITweenClick:Released -- 버튼 떼었을 때 원래 크기로 복구 애니메이션
UITweenClick:HandleButtonClickEvent -- 버튼 클릭 이벤트를 처리하는 핸들러
UITweenClick:HandleButtonStateChangeEvent -- 버튼 상태 변경 이벤트를 처리하는 핸들러
UITweenConfetti:OnBeginPlay -- 콘페티 효과 트윈 초기화
UITweenConfetti:OnUpdate -- 매 프레임 콘페티 위치 및 알파 업데이트
UITweenConfetti:Play -- 콘페티 애니메이션 재생 시작
UITweenConfetti:PoingPonng -- 핑폰 루프 계산
UITweenConfetti:Repeat -- 일반 루프 계산
UITweenConfetti:Stop -- 콘페티 애니메이션 정지 및 풀로 반환
UITweenMoveBounce:StartTween -- 타겟 위치로 바운스 효과와 함께 이동하는 트윈 시작
UITweenMoveBounce:OnUpdate -- 매 프레임 위치 업데이트
UITweenMoveFade:StartTween -- 방향에 따른 이동과 페이드 효과 트윈 시작
UITweenMoveFade:OnUpdate -- 매 프레임 위치와 알파 업데이트
UITweenPop:StartPop -- 팝업 효과와 함께 등장하는 트윈 시작
UITweenPop:OnUpdate -- 매 프레임 월드 위치 업데이트
UITweenPop:StartMoveToTarget -- 타겟 위치로 이동 후 페이드 아웃 처리
UITweenPopFade:StartTween -- 팝업 효과와 페이드 결합 트윈 시작
UITweenPopFade:OnUpdate -- 매 프레임 위치 업데이트
UITweenPopFade:StartFade -- 페이드 아웃 효과 시작
UITweenPosition:OnBeginPlay -- 위치 트윈 초기화 및 자동 재생 설정
UITweenPosition:OnUpdate -- 매 프레임 위치 값 계산 및 적용
UITweenPosition:Play -- 위치 트윈 재생 시작
UITweenPosition:PoingPonng -- 핑폰 루프 계산
UITweenPosition:Repeat -- 일반 루프 계산
UITweenPosition:Stop -- 위치 트윈 정지
UITweenRotate:OnBeginPlay -- 회전 트윈 초기화 및 자동 재생 설정
UITweenRotate:OnUpdate -- 매 프레임 회전 값 계산 및 적용
UITweenRotate:Play -- 회전 트윈 재생 시작
UITweenRotate:PoingPonng -- 핑폰 루프 계산
UITweenRotate:Repeat -- 일반 루프 계산
UITweenRotate:Stop -- 회전 트윈 정지
UITweenScale:OnBeginPlay -- 크기 트윈 초기화 및 자동 재생 설정
UITweenScale:OnUpdate -- 매 프레임 크기 값 계산 및 적용
UITweenScale:Play -- 크기 트윈 재생 시작
UITweenScale:PoingPonng -- 핑폰 루프 계산
UITweenScale:Repeat -- 일반 루프 계산
UITweenScale:Stop -- 크기 트윈 정지
UITweenTextColor:OnBeginPlay -- 텍스트 색상 트윈 초기화 및 자동 재생 설정
UITweenTextColor:OnUpdate -- 매 프레임 텍스트 색상 및 외곽선 업데이트
UITweenTextColor:Play -- 텍스트 색상 트윈 재생 시작
UITweenTextColor:PoingPonng -- 핑폰 루프 계산
UITweenTextColor:Repeat -- 일반 루프 계산
UITweenTextColor:Stop -- 텍스트 색상 트윈 정지 및 초기 색상로 복구
UITweenTextScale:OnBeginPlay -- 텍스트 크기 트윈 초기화 및 자동 재생 설정
UITweenTextScale:OnUpdate -- 매 프레임 텍스트 크기 값 계산 및 적용
UITweenTextScale:Play -- 텍스트 크기 트윈 재생 시작
UITweenTextScale:PoingPonng -- 핑폰 루프 계산
UITweenTextScale:Repeat -- 일반 루프 계산
UITweenTextScale:Stop -- 텍스트 크기 트윈 정지