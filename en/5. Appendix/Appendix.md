PlayerAccount:SaveToDB -- Saves player account information to the database
PlayerAccount:OnLoadedDataFromDB -- Processes account data loaded from the database
PlayerAccount:OnCreated -- Sets creation timestamp when account is created
PlayerAccount:OnLogin -- Records login time when player logs in
PlayerAccount:OnLogout -- Records logout time when player logs out
PlayerAchievement:SaveToDB -- Saves achievement data to the database
PlayerAchievement:OnLoadedDataFromDB -- Loads achievement data from database and initializes
PlayerAchievement:InitComponent -- Initializes the achievement component
PlayerAchievement:ChangeProgress -- Changes achievement progress
PlayerAchievement:RequestChangeProgress -- Requests achievement progress change from client
PlayerAchievement:SetComplete -- Sets achievement completion status and grants rewards
PlayerAchievement:RequestSetComplete -- Processes achievement completion request and checks conditions
PlayerAchievement:SetAchieved -- Sets achievement completion status and handles related events
PlayerAchievement:OnSyncProperty -- Handles UI updates when synchronized properties change
PlayerAchievement:ReturnAchievementIdByType -- Returns corresponding achievement ID based on achievement type
PlayerAchievement:RequestUpdateUIAchievement -- Requests achievement UI update
PlayerAchievement:SetAchievementRedDot -- Sets red dot indicator for achievement menu
PlayerAchievement:IsAnyAchievementAchievedInTab -- Checks if any achievement is completed in specific tab
PlayerAchievement:RequestGainAllReward -- Claims rewards for all completed achievements at once
PlayerAchievement:IsAchievementComplete -- Checks if achievement is completed
PlayerAchievement:IsAchievementAchieved -- Checks if achievement is achieved
PlayerAchievement:ReturnAchievementProgress -- Returns current progress of achievement type
PlayerAchievement:RequestSetMultipleComplete -- Processes multiple achievements completion simultaneously
PlayerAchievement:CheckCanEventCompleted -- Checks if event can be triggered based on achievement completion
PlayerAchievement:SetInitialTypeValue -- Sets initial values for achievement types
PlayerAchievement:ChangeAllAchieveCompleteForCheat -- Changes all achievements to completed state for cheat
PlayerBadge:SaveToDB -- Saves badge data to the database
PlayerBadge:OnLoadedDataFromDB -- Loads badge data from the database
PlayerBadge:ChangeProgress -- Changes badge progress and checks completion
PlayerBadge:CheckBadgeAchieved -- Checks badge completion based on progress
PlayerBadge:SetBadgeAchieved -- Sets badge achievement status
PlayerBadge:GetBadgeAchievedFromPlatform -- Gets badge achievement information from platform
PlayerBadge:BadgeLog -- Records badge achievement logs
PlayerCollection:SaveToDB -- Saves collection data to the database
PlayerCollection:OnLoadedDataFromDB -- Loads collection data from the database
PlayerCollection:AddIngredientCollection -- Adds new ingredients to ingredient collection
PlayerCollection:AddBunCollection -- Adds new buns to bun collection
PlayerCollection:RequestGetIngredientCollectionReward -- Requests ingredient collection reward
PlayerCollection:GetIngredientCollectionReward -- Grants ingredient collection reward
PlayerCollection:RequestGetBunCollectionReward -- Requests bun collection reward
PlayerCollection:GetBunCollectionReward -- Grants bun collection reward
PlayerCollection:RequestAddBunSkinCollection -- Requests addition to bun skin collection
PlayerCollection:AddBunSkinCollection -- Adds new skin to bun skin collection
PlayerCollection:CheckCanGetBunSkin -- Checks if bun skin can be obtained
PlayerCollection:OnSyncProperty -- Handles UI updates when synchronized properties change
PlayerCollection:AddSideMenuCollection -- Adds new menu to side menu collection
PlayerCollection:RequestAddSideMenuCollection -- Requests addition to side menu collection
PlayerCollection:CheckCanGetSideMenu -- Checks if side menu can be obtained
PlayerCollection:RequestSetSideMenuChecked -- Sets side menu check status
PlayerCollection:IngreCollectionFlowLog -- Records ingredient collection flow logs
PlayerCollection:GetCollectionRate -- Calculates and returns completion rate for selected tab
PlayerCollection:AddStrategyCollection -- Adds new strategy to strategy collection
PlayerCollection:RequestAddStrategyCollection -- Requests addition to strategy collection and checks conditions
PlayerDBManager:OnBeginPlay -- Performs database initialization and loading at game start
PlayerDBManager:OnMapEnter -- Performs lobby-related initialization when entering map
PlayerDBManager:SaveToDB -- Saves player data to the database
PlayerDBManager:ClearStageDB -- Deletes stage database
PlayerDBManager:LoadFromDB -- Loads player data from the database
PlayerDBManager:OnLoadedDataFromStageDB -- Loads data from stage database
PlayerDBManager:CallAfterEveryDataLoaded -- Performs initialization tasks after all data is loaded
PlayerDBManager:ConnetLog -- Records connection logs
PlayerDBManager:DBErrorLog -- Records database error logs
PlayerDBManager:InitComponents -- Initializes all player components
PlayerDBManager:HandleUserLeaveEvent -- Handles user leave event
PlayerDialog:OnMapEnter -- Starts intro dialog when entering intro map
PlayerEvent:SaveToDB -- Saves event data to the database
PlayerEvent:OnLoadedDataFromDB -- Loads event data from the database
PlayerEvent:InitComponent -- Initializes the event component
PlayerEvent:OnSyncProperty -- Handles UI updates when synchronized properties change
PlayerEvent:IsEventOccured -- Checks if specific event has occurred
PlayerEvent:SetEventOccured -- Sets event to occurred status
PlayerEvent:AddToEventQueue -- Adds event to event queue
PlayerEvent:RequestAddToEventQueue -- Requests addition to event queue
PlayerEvent:RemoveFromEventQueue -- Removes event from event queue
PlayerEvent:RequestRemoveFromEventQueue -- Requests removal from event queue
PlayerEvent:AddToDayEventQueue -- Adds event to daily event queue
PlayerEvent:RequestAddToDayEventQueue -- Requests addition to daily event queue
PlayerEvent:RemoveAndCallEventFromEventQueue -- Removes event from queue and calls the event
PlayerEvent:RequestRemoveAndCallEventFromEventQueue -- Requests removal and calling of event from queue
PlayerEvent:RequestSetEventReferKey -- Requests setting of event reference key
PlayerEvent:SetEventReferKey -- Sets event reference key
PlayerEvent:RequestClearEventData -- Processes request to clear event data
PlayerEvent:ForceSetEventOccured -- Forces event to occurred status
PlayerEvent:CheckEventCallbackOccured -- Checks if event callback has occurred
PlayerEvent:SetToDoSecretaryChecked -- Sets todo secretary check status
PlayerEvent:RequestSetToDoSecretaryChecked -- Requests setting of todo secretary check status
PlayerEvent:RefreshToDoSecretaryInfo -- Refreshes todo secretary information
PlayerEvent:RequestSetAllToDoSecretaryChecked -- Sets all todo secretaries to checked status
PlayerEvent:RefreshAllToDoSecretaryInfo -- Refreshes all todo secretary information
PlayerEvent:TutorialStartLog -- Records tutorial start log
PlayerEvent:TutorialEndLog -- Records tutorial end log
PlayerEvent:CheckTutorialEndLog -- Checks tutorial end log
PlayerEvent:RemoveFromDayEventQueue -- Removes event from daily event queue
PlayerEvent:RequestCallEvent -- Requests event calling
PlayerEvent:HandlePlayerTrainingTokenChangedEvent -- Handles player training token change event
PlayerEvent:HandlePlayerMoneyChangedEvent -- Handles player money change event
PlayerEventFunction:OnBeginPlay -- Initializes and registers event functions
PlayerEventFunction:RegisterFunc -- Registers function to command table
PlayerEventFunction:CommandFunc -- Executes corresponding function based on event group ID
PlayerEventFunction:GetItem -- Grants items through events
PlayerEventFunction:AddSubscription -- Adds subscription through events
PlayerEventFunction:OpenTrial -- Opens unofficial trial
PlayerEventFunction:GetStoreRankingReward -- Grants store ranking reward
PlayerEventFunction:SetRedDot -- Sets menu red dot indicator
PlayerEventFunction:OpenVIPOrder -- Opens VIP order
PlayerEventFunction:ModifyReputation -- Modifies reputation
PlayerEventFunction:ClearAllUI -- Clears all UI
PlayerIngameManager:SaveToDB -- Saves ingame manager data to the database
PlayerIngameManager:OnLoadedDataFromDB -- Loads ingame data from the database
PlayerIngameManager:InitComponent -- Initializes ingame manager component
PlayerIngredient:SaveToDB -- Saves ingredient data to the database
PlayerIngredient:OnLoadedDataFromDB -- Loads ingredient data from the database
PlayerIngredient:InitComponent -- Initializes all ingredient data during component initialization
PlayerIngredient:AddIngredientCard -- Adds ingredient card
PlayerIngredient:RemoveIngredientCard -- Removes ingredient card
PlayerIngredient:CanUseIngredientCard -- Checks if ingredient card can be used
PlayerIngredient:AddBun -- Adds bun (bread)
PlayerIngredient:RemoveBun -- Removes bun
PlayerIngredient:CanUseBun -- Checks if bun can be used
PlayerIngredient:SetBunFunction -- Sets bun function
PlayerIngredient:RequestSetBun -- Requests bun setting
PlayerIngredient:RequestOpenIngredientGacha -- Requests ingredient gacha opening
PlayerIngredient:ProcessOpenIngredientGacha -- Opens ingredient gacha and processes results
PlayerIngredient:ProcessIngredientGacha -- Processes ingredient gacha results
PlayerIngredient:SendGachaResult -- Sends gacha results to client
PlayerIngredient:OnSyncProperty -- Handles UI updates when synchronized properties change
PlayerIngredient:ChangeConnectingStatus -- Changes connection status
PlayerIngredient:AddToIngreSubscriptionBox -- Adds items to ingredient subscription box
PlayerIngredient:GetIngreSubscriptionBox -- Collects ingredient subscription box
PlayerIngredient:RequestGetIngreSubscriptionBox -- Requests ingredient subscription box collection
PlayerIngredient:InitIngreCards -- Grants initial ingredient cards
PlayerIngredient:IngreFlowLog -- Records ingredient flow logs
PlayerInventory:SaveToDB -- Saves inventory data to the database
PlayerInventory:OnLoadedDataFromDB -- Loads inventory data from the database
PlayerInventory:InitComponent -- Initializes inventory component
PlayerInventory:AddItem -- Adds item to inventory
PlayerInventory:AddItems -- Adds multiple items to inventory
PlayerInventory:RemoveItem -- Removes item from inventory
PlayerInventory:CanUseItem -- Checks if item can be used
PlayerInventory:RemoveItems -- Removes multiple items from inventory
PlayerInventory:ClearItems -- Clears all items
PlayerInventory:RequestUseItem -- Requests item usage
PlayerInventory:RequestAddItem -- Requests item addition
PlayerInventory:ModifyMoney -- Increases or decreases money
PlayerInventory:AddMoney -- Adds money
PlayerInventory:SubMoney -- Deducts money
PlayerInventory:OnSyncProperty -- Handles UI updates when synchronized properties change
PlayerInventory:AddLunchBox -- Adds lunch box
PlayerInventory:SubLunchBox -- Deducts lunch box
PlayerInventory:ModifyLunchBox -- Increases or decreases lunch box quantity
PlayerInventory:ModifyArcaneSymbol -- Increases or decreases arcane symbols
PlayerInventory:AddArcaneSymbol -- Adds arcane symbols
PlayerInventory:SubArcaneSymbol -- Deducts arcane symbols
PlayerInventory:ModifyHeart -- Increases or decreases hearts
PlayerInventory:AddHeart -- Adds hearts
PlayerInventory:SubHeart -- Deducts hearts
PlayerInventory:ModifyTip -- Increases or decreases tips
PlayerInventory:AddTip -- Adds tips
PlayerInventory:SubTip -- Deducts tips
PlayerInventory:RequestUseTip -- Requests tip usage to convert to hearts
PlayerInventory:SubMoneyUnderZero -- Deducts money allowing negative balance
PlayerInventory:AddLunchBoxGaugePerDay -- Adds daily lunch box gauge
PlayerInventory:CalcLunchBoxRemainDay -- Calculates remaining days for lunch box
PlayerInventory:RefreshLunchBoxRemainDay -- Refreshes lunch box remaining days UI
PlayerInventory:UpdateLunchBoxUpgradeInfo -- Updates lunch box upgrade information
PlayerInventory:ModifyTrainingTicket -- Modifies training ticket quantity
PlayerInventory:CheckTrainingRedDot -- Checks if training menu red dot should be displayed
PlayerInventory:ModifyReputation -- Increases or decreases reputation
PlayerInventory:AddReputation -- Adds reputation
PlayerInventory:SubReputation -- Deducts reputation
PlayerInventory:UseItem -- Uses item
PlayerInventory:GetItemCount -- Returns quantity of specific item owned
PlayerInventory:IsItemOverMaxCount -- Checks if item exceeds maximum stack count
PlayerItemFunction:OnBeginPlay -- Initializes and registers item functions
PlayerItemFunction:RegisterFunc -- Registers function to command table
PlayerItemFunction:CommandFunc -- Executes corresponding function based on item ID
PlayerItemFunction:OpenPackage -- Opens package item and grants contents
PlayerItemFunction:OpenIngreBox -- Opens ingredient box and conducts gacha
PlayerItemFunction:UsePotionCook -- Uses cook potion to grant experience
PlayerItemFunction:UsePotionServing -- Uses serving potion to grant experience
PlayerItemFunction:UseOverLimitCook -- Uses cook over-limit item
PlayerItemFunction:UseOverLimitServing -- Uses serving over-limit item
PlayerItemFunction:AddSubscription -- Adds subscription
PlayerItemFunction:AddBunSkin -- Adds bun skin
PlayerLog:OnBeginPlay -- Initializes log category flow types
PlayerLog:PlayflowLog -- Records play flow log
PlayerLog:ResourceFlow -- Records resource flow log
PlayerLog:ItemFlow -- Records item flow log
PlayerLog:ConnectFlow -- Records connection flow log
PlayerLog:AutoTrainingFlow -- Records auto training flow log
PlayerLog:RecipeFlow -- Records recipe flow log
PlayerLog:UpgradeFlow -- Records upgrade flow log
PlayerLog:EmployeeUpgradeFlow -- Records employee upgrade flow log
PlayerLog:EmployeeOvelimitFlow -- Records employee overlimit flow log
PlayerLog:RankFlow -- Records ranking flow log
PlayerLog:AchievementFlow -- Records achievement flow log
PlayerLog:TrialEmployee -- Records employee trial flow log
PlayerLog:TrialRecipe -- Records recipe trial flow log
PlayerLog:RequestMenuLog -- Requests menu log recording
PlayerLog:MenuFlow -- Records menu flow log
PlayerLog:EmployeeLocation -- Records employee location change log
PlayerLog:EmployeeFlow -- Records employee flow log
PlayerLog:GetRewardStr -- Converts reward table to string
PlayerLog:ExchangeFlow -- Records exchange flow log
PlayerLog:VerificationRecipe -- Records recipe verification log
PlayerLog:GetArrayStr -- Converts table to array string
PlayerManagement:SaveToDB -- Saves management data to the database
PlayerManagement:OnLoadedDataFromDB -- Loads management data from the database
PlayerManagement:InitComponent -- Initializes management component
PlayerManagement:SetCurrentGoalsProgress -- Sets progress for current goals
PlayerManagement:ManagementLevelUp -- Increases management level
PlayerManagement:OnSyncProperty -- Handles UI updates when synchronized properties change
PlayerManagement:RequestManagementLevelUp -- Processes management level up request
PlayerManagement:ChangeConnectingStatus -- Changes connection status
PlayerManagement:SetStoreRanking -- Sets store ranking and grants rewards
PlayerManagement:RequestSetStoreRanking -- Requests store ranking setting
PlayerManagement:CheckRankingAnnounceDay -- Checks ranking announcement day
PlayerManagement:ReturnSurroundingsData -- Returns surrounding ranking data
PlayerManagement:CheckRankingExplainDay -- Checks ranking explanation day
PlayerManagement:RequestSetRankingSpeech -- Requests ranking speech setting
PlayerManagement:SetRankingSpeech -- Sets ranking speech
PlayerManagement:GetGoalCount -- Returns number of achieved goals
PlayerManagement:CheckGoalsAchieved -- Checks and processes goal achievement
PlayerManagement:RequestSetIsEndingEventSeen -- Sets ending event viewed status
PlayerManagement:GetIsEndingEventSeen -- Returns ending event viewed status
PlayerManagement:AddReputationLog -- Adds reputation log
PlayerManagement:UpdateReputationLogOnDayChanged -- Updates reputation log when day changes
PlayerManagement:RequestSyncReputationLogs -- Requests reputation log synchronization
PlayerManagement:SyncReputationLogs -- Synchronizes reputation logs
PlayerManagement:SetManagementLevel -- Sets management level
PlayerManagement:UpdateReputationDailyLogs -- Updates daily reputation logs
PlayerManagement:InitBoosterPackPurchase -- Initializes booster pack purchase information
PlayerManagement:OnBoosterPackPurchased -- Processes booster pack purchase
PlayerManagement:IsPreminumBoosterPackPurchased -- Checks if premium booster pack is purchased
PlayerManagement:RequestReexamRanking -- Requests ranking re-examination
PlayerManagement:ReexamRanking -- Re-examines ranking
PlayerManagement:ExamStoreRanking -- Examines store ranking and calculates new ranking
PlayerOutgameManager:SaveToDB -- Saves outgame player data to database
PlayerOutgameManager:OnLoadedDataFromDB -- Loads and initializes outgame player data from database
PlayerOutgameManager:OnSyncProperty -- Triggers related events and UI updates based on synchronized properties
PlayerOutgameManager:RequestSetStoreName -- Processes store name setting request from client
PlayerOutgameManager:SetStoreName -- Sets store name after profanity check and logs the action
PlayerOutgameManager:GetDiamondCount -- Returns total diamond count by combining free and paid diamonds
PlayerOutgameManager:ModifyDiamond -- Increases or decreases diamond amount with logging
PlayerOutgameManager:AddDiamond -- Adds diamonds with maximum stack check and logging
PlayerOutgameManager:SubDiamond -- Deducts diamonds prioritizing free diamonds before paid diamonds
PlayerOutgameManager:SubDiamondPaidOnly -- Deducts only paid diamonds for special cases
PlayerOutgameManager:GetPurchaseCount -- Calculates and returns purchase count for specific product (applies additional purchase count deduction)
PlayerOutgameManager:AddPurchaseCount -- Increases purchase count for specific product by 1 and returns result
PlayerOutgameManager:SubPurchaseCount -- Decreases purchase count for specific product by 1 or resets and returns result
PlayerOutgameManager:ModifyStrategyPoint -- Increases or decreases strategy points with logging
PlayerOutgameManager:AddStrategyPoint -- Adds strategy points with maximum stack check
PlayerOutgameManager:SubStrategyPoint -- Deducts strategy points with balance check
PlayerOutgameManager:HasRemainStagePassRewardBySlotId -- Checks if there are unclaimed stage pass rewards for specific slot
PlayerOutgameManager:GetStagePassRewardReceived -- Checks if specific stage pass reward has been received
PlayerOutgameManager:ReceiveStagePassReward -- Receives stage pass reward and adds to inventory
PlayerOutgameManager:ReceiveStagePassPurchaseReward -- Receives stage pass purchase reward and adds to inventory
PlayerOutgameManager:GetStagePassPurchaseRewardReceived -- Checks if stage pass purchase reward has been received
PlayerOutgameManager:ResetPurchseCount -- Resets purchase count for specific product and returns previous value
PlayerOutgameManager:ResetStagePassRewardReceived -- Resets stage pass reward received status and returns number of changes
PlayerOutgameManager:GetStagePassRecentRewardId -- Returns recent stage pass reward ID for specific group
PlayerOutgameManager:GetPiggyBankRewardReceived -- Checks piggy bank reward received status for specific slot
PlayerOutgameManager:AddPiggyBankLevel -- Increases piggy bank level and converts saved points to diamonds for grant
PlayerOutgameManager:AddPiggyBankPoint -- Adds piggy bank points and resets settlement earnings when full
PlayerOutgameManager:IsPiggyBankFull -- Checks if piggy bank is full and adjusts to maximum value if needed
PlayerOutgameManager:ResetPiggyBankPoint -- Resets piggy bank points and settlement earnings
PlayerOutgameManager:ForceAddPiggyBankPoint_ForCheat -- Cheat function to force add piggy bank points
PlayerOutgameManager:ReceivePiggyBankReward -- Receives piggy bank level up reward and adds to inventory
PlayerOutgameManager:ForceSetPiggyBankLevelAndPoint_ForCheat -- Cheat function to force set piggy bank level and points
PlayerOutgameManager:StoreNameFlowLog -- Records store name change related logs
PlayerOutgameManager:AddItem -- Adds item to outgame inventory with maximum stack check
PlayerOutgameManager:RemoveItem -- Removes item from outgame inventory
PlayerOutgameManager:RequestSetHasSeenIntro -- Sets intro video viewed status
PlayerOutgameManager:SetLogoutTimeElapsed -- Sets logout time for offline reward calculation
PlayerOutgameManager:InitPiggyBankPoint -- Initializes piggy bank points to 0 with logging
PlayerOutgameManager:AddMaxStackCountMailCount -- Increases maximum stack count mail count by 1
PlayerOutgameManager:SetRecentOpenedStagePassGroup -- Sets recently opened stage pass group ID
PlayerOutgameManager:SetBoosterPack1Purchased -- Sets booster pack 1 purchase status for specific stage
PlayerRecipe:SaveToDB -- Saves recipe-related data to database
PlayerRecipe:OnLoadedDataFromDB -- Loads and initializes recipe data from database
PlayerRecipe:InitComponent -- Initializes all recipe component data
PlayerRecipe:CheckCanStartRecipeMaking -- Checks if recipe creation can start and consumes required ingredients
PlayerRecipe:StartRecipeMaking -- Starts recipe creation UI from client
PlayerRecipe:EndRecipeMakingServer -- Completes recipe creation on server and processes achievements and rewards
PlayerRecipe:EndRecipeMakingClient -- Handles UI cleanup and next screen transition after client recipe creation completion
PlayerRecipe:ConvertRecipeDataToTable -- Converts recipe struct data to table format for DB storage
PlayerRecipe:ConvertTableToRecipeData -- Converts table data to recipe struct for loading
PlayerRecipe:AddNewRecipe -- Adds new recipe and handles related achievements and logs
PlayerRecipe:RequestSyncAllRecipe -- Synchronizes all recipe data to client and refreshes UI
PlayerRecipe:OnSyncProperty -- Updates related UI and menu settings based on synchronized properties
PlayerRecipe:RequestDeleteRecipe -- Processes recipe deletion request from client
PlayerRecipe:DeleteRecipe -- Deletes recipe and removes from set menus with logging
PlayerRecipe:ChangeConnectingStatus -- Changes server processing status from client
PlayerRecipe:SetInitialDatas -- Creates and sets initial basic recipe data
PlayerRecipe:SetRecipe -- Sets recipe to specific slot and calculates menu combinations and attractiveness updates
PlayerRecipe:ClearSetRecipes -- Initializes all set recipes and calculates combinations
PlayerRecipe:UnsetRecipe -- Removes recipe setting for specific slot or resets all
PlayerRecipe:RequestSetRecipe -- Processes recipe setting request from client
PlayerRecipe:RequestUnsetRecipe -- Processes recipe removal request from client
PlayerRecipe:RequestRefreshRecipeUI -- Refreshes all recipe-related UI
PlayerRecipe:SetRecipeTrialBuff -- Applies trial buff to recipe and sets expiration date
PlayerRecipe:EndRecipeTrialBuff -- Ends recipe trial buff and initializes related data
PlayerRecipe:ChangeTrialBuffProgress -- Increases progress by 1 for all recipes with trial buff applied
PlayerRecipe:CheckTrialProgressExpiry -- Checks expiration dates for trial buff applied recipes and ends expired buffs
PlayerRecipe:AutoSetRecipe -- Automatically sets owned recipes to menu slots sorted by price
PlayerRecipe:RequestAutoSetRecipe -- Processes automatic recipe setting request from client
PlayerRecipe:MakeNewTrend -- Creates new trend setting positive and negative trends and triggering related events
PlayerRecipe:RequestMakeNewTrend -- Processes new trend creation request from client
PlayerRecipe:ChangeTrendProgress -- Increases progress by 1 for all currently active trends
PlayerRecipe:CheckTrendExpiry -- Checks trend expiration dates and ends expired trends
PlayerRecipe:EndTrend -- Ends specified trends and triggers related events and refreshes customer spawn table
PlayerRecipe:SetYearlyPlan -- Sets yearly trend plan determining trend dates for first and second half of year
PlayerRecipe:CheckYearlyPlan -- Checks if trends should occur on specific dates according to yearly plan and executes them
PlayerRecipe:CalculateActiveRecipeCombo -- Analyzes tag combinations of currently set recipes to calculate active combos
PlayerRecipe:RequestEndRecipeMaking -- Processes recipe creation completion request from client after profanity check and storage limit verification
PlayerRecipe:ChangeRecipeSetCompleteProgress -- Changes recipe setting completion status
PlayerRecipe:ReturnRecipeIndexByUniqueId -- Finds and returns recipe index using unique ID
PlayerRecipe:ForceSyncSetRecipes -- Force synchronizes set recipes from server and updates related UI and menus
PlayerRecipe:RequestForceSyncSetRecipes -- Processes forced recipe setting synchronization request from client
PlayerRecipe:SetTempUsingCards -- Sets temporary card data to be used during recipe creation
PlayerRecipe:verificationBurgerData -- Verifies that burger data taste score and price do not exceed maximum limits
PlayerSettlement:SaveToDB -- Saves settlement data to database
PlayerSettlement:OnLoadedDataFromDB -- Loads and initializes settlement data from database
PlayerSettlement:InitComponent -- Initializes all settlement component data
PlayerSettlement:Settlement -- Executes monthly settlement calculating income and expenses and processing results
PlayerSettlement:RequestSyncSettlementDatas -- Synchronizes settlement data from server to client and updates UI
PlayerSettlement:ConvertSettlementDataToTable -- Converts settlement data struct to table format for DB storage
PlayerSettlement:ConvertTableToSettlementData -- Converts table data to settlement data struct for loading
PlayerSettlement:CreateNewMonthSettlementData -- Creates new month settlement data maintaining maximum 7 months record
PlayerSettlement:AddValueForSettlement -- Adds value to specific settlement data item and performs related processing
PlayerSettlement:ReplaceValueForSettlement -- Replaces value for specific settlement data item
PlayerSettlement:RequestAddValueForSettlement -- Processes settlement data value addition request from client
PlayerSettlement:AddTableValueForSettlement -- Adds data to table-type settlement data item as key-value pair
PlayerSettlement:RequestAddTableValueForSettlement -- Processes settlement data table value addition request from client
PlayerSettlement:CheckForResignEvent -- Checks resignation warning conditions and processes automatic resignation and warnings based on employee count
PlayerSettlement:ResignWarningAlert -- Displays resignation warning feedback UI to all employees
PlayerSettlement:RequestSyncSettlementDataFromServer -- Processes settlement data synchronization request from server to client
PlayerSettlement:OnSyncProperty -- Triggers related events and UI updates based on synchronized properties
PlayerSettlement:RequestRefreshStoreInfoRecordPage -- Refreshes store information record page
PlayerSettlement:ChangeRecipeEarningRecord -- Changes recipe highest earning record and processes related achievements and events
PlayerSettlement:AddPiggyBankEarnings -- Adds piggy bank earnings and increases piggy bank points when conditions are met
PlayerSettlement:ResetPiggyBankEarings -- Resets piggy bank earnings and updates debug monitor
PlayerSettlement:MonthlySnapLog -- Records monthly snapshot log for game data analysis
PlayerSettlement:MonthlyResourceLog -- Records monthly resource log to track resource acquisition and consumption
PlayerSettlement:UpdateEarningLevel -- Updates earning level
PlayerSettlement:RequestOpenUIOfflineReward -- Calculates logout time and reward amount to open offline reward UI
PlayerSettlement:RequestGetOfflineReward -- Processes offline reward collection request from client
PlayerStage:SaveToDB -- Saves stage-related data to database
PlayerStage:OnLoadedDataFromDB -- Loads and initializes stage data from database
PlayerStage:OnLoadedStage -- Performs initial settings and UI updates when stage loading is complete
PlayerStage:OnStartNewStage -- Prepares setting data for starting new stage and initializes DB
PlayerStage:OnContinueStage -- Performs preparation work to continue existing stage
PlayerStage:SetStageProgress -- Sets stage progress and grants rewards when clear conditions are met
PlayerStage:MoveToLoadingMap -- Moves to loading map to prepare for stage transition
PlayerStage:OnMapEnter -- Handles stage transition processing and log recording when entering map
PlayerStage:ClearUI -- Clears all UI and deactivates lobby-related elements
PlayerStage:OnSyncProperty -- Triggers related events and UI updates based on synchronized properties
PlayerStage:GetChustarLevel -- Calculates and returns Chustar level based on number of cleared stages
PlayerStage:GetStageClearReward -- Grants stage clear rewards and unlocks collection items and adds to reward queue
PlayerStage:IsAchieveStageProgress -- Checks if specified stage progress has reached required level
PlayerStage:GetNextStageProgress -- Calculates next stage progress and returns stage ID and progress
PlayerStage:ReturnMapName -- Generates and returns map name based on stage ID
PlayerStage:IsStageOpened -- Checks if specified stage is unlocked and accessible
PlayerStage:RequestDrawStageClearRewardQueue -- Displays reward UI from stage clear reward queue and clears queue
PlayerStage:RequestClearStageRewardQueue -- Initializes stage reward queue and clear data
PlayerStage:RequestMakeDialog -- Creates dialog during stage progression and conditionally opens booster pack UI
PlayerStage:GetPlayerLastStageProgress -- Returns player's latest stage progress as string
PlayerStage:StageEnterLog -- Records stage entry log for user behavior analysis data collection
PlayerStage:StageSettingLog -- Records stage setting log to track strategies and setting data used
PlayerStage:SetStageSettingData -- Saves stage setting data in JSON format
PlayerStage:DrawStageClearRewardQueue -- Processes stage clear reward queue to display reward UI
PlayerTrial:SaveToDB -- Saves trial-related data to database
PlayerTrial:OnLoadedDataFromDB -- Loads and initializes trial data from database
PlayerTrial:InitComponent -- Initializes all trial component data
PlayerTrial:OnSyncProperty -- Updates related UI and handles events based on synchronized properties
PlayerTrial:SetTrialData -- Sets trial data and prepares rendering and client synchronization
PlayerTrial:SetCharacterData -- Creates trial participants' character data and places them in layout
PlayerTrial:ReturnPlayData -- Generates play data based on trial weights and returns as time array
PlayerTrial:SetRankData -- Sets ranking data based on user stats and requirements and determines trial order
PlayerTrial:ReturnCharacterData -- Creates user or rival character data and returns with layout index
PlayerTrial:ClearDatas -- Initializes all trial-related data and resets selection status
PlayerTrial:SyncTableData -- Synchronizes table data sent from server to client
PlayerTrial:ChangeConnectingStatus -- Changes server processing status for loading state management
PlayerTrial:SelectTrial -- Selects trial and moves to trial setting UI after cost and condition checks
PlayerTrial:RequestSelectTrial -- Processes trial selection request from client
PlayerTrial:EndTrial -- Ends trial and grants rewards and handles achievements based on results
PlayerTrial:RequestEndTrial -- Processes trial end request from client
PlayerTrial:RequestSetSelectedRecipe -- Processes selected recipe setting request from client
PlayerTrial:SetSelectedRecipe -- Sets selected recipe in recipe trial and deducts trial cost to start trial
PlayerTrial:RequestSetTarget -- Opens recipe or employee selection UI based on trial target
PlayerTrial:RequestSetSelectedEmployee -- Processes selected employee setting request from client
PlayerTrial:SetSelectedEmployee -- Sets selected employee in employee trial and deducts trial cost to start trial
PlayerTrial:SetIngredientData -- Sets ingredient data for each participant based on trial type for visual display
PlayerTrial:UpdateTrialProgress -- Updates official/unofficial trial progress when trial is won and handles related events
PlayerTrial:SetTrialGradeDifficulty -- Sets trial grade and difficulty and refreshes related secretary information
PlayerTrial:SetOfficialTrials -- Sets official trial list based on current stage
PlayerTrial:SetUnofficialTrials -- Randomly generates unofficial trial list categorized into employee and recipe trials
PlayerTrial:RequestSetTrialTab2RedDotChecked -- Sets trial tab2 red dot check status
PlayerTutorialEvent:SaveToDB -- Saves tutorial event data to database
PlayerTutorialEvent:OnLoadedDataFromDB -- Loads and initializes tutorial event data from database
PlayerTutorialEvent:SetIsSkipTutorial -- Changes tutorial skip setting and completes all tutorial events if necessary
PlayerTutorialEvent:SetEventOccured -- Sets specific tutorial event to occurred status and processes related rewards
PlayerTutorialEvent:IsEventOccured -- Checks if specific tutorial event has occurred and returns status
PlayerTutorialEvent:ForceSetTutorialEventsOccured -- Forces all tutorial events to occurred status
PlayerTutorialEvent:OnSyncProperty -- Unlocks UI buttons and refreshes related UI when tutorial events are synchronized
PlayerUpgrade:SaveToDB -- Saves upgrade data to database
PlayerUpgrade:OnLoadedDataFromDB -- Loads and initializes upgrade data from database
PlayerUpgrade:InitComponent -- Initializes all upgrade component data
PlayerUpgrade:UpgradeFunction -- Performs upgrade logic checking conditions then deducting cost and processing level up
PlayerUpgrade:RequestUpgrade -- Processes upgrade request from client
PlayerUpgrade:RequestApplyUpgradeDataServer -- Performs various facility and function updates based on upgrade type and handles achievements
PlayerUpgrade:ReturnPlayerUpgradeLevelOfType -- Returns current level of specified upgrade type
PlayerUpgrade:ChangeConnectingStatus -- Changes server processing status for loading state management
PlayerUpgrade:OnSyncProperty -- Updates related UI and handles button unlock processing based on synchronized properties
PlayerUpgrade:UpdateIngreBoxSubscriptionStatus -- Updates ingredient box subscription status and adds ingredients to subscription box at beginning of month
PlayerUpgrade:AddNewSubscription -- Adds new subscription combining with existing subscription period
PlayerUpgrade:ForceSetUpgradeLevel -- Cheat function to force set upgrade level and update related facilities
PlayerUpgrade:SyncToClientUpgrades -- Synchronizes upgrade data to client
PlayerVIPOrder:SaveToDB -- Saves VIP order-related data to database
PlayerVIPOrder:OnLoadedDataFromDB -- Loads and initializes VIP order data from database
PlayerVIPOrder:InitComponent -- Initializes all VIP order component data
PlayerVIPOrder:OnSyncProperty -- Updates VIP order-related UI and changes status based on synchronized properties
PlayerVIPOrder:StartNewSeason -- Starts new VIP order season setting main tag and creating order slots
PlayerVIPOrder:CreateVIPOrderSlotData -- Creates VIP order data for specified slot setting as recipe or ingredient order
PlayerVIPOrder:AddVIPOrderUniqueId -- Increases VIP order unique ID by 1
PlayerVIPOrder:RequestSyncVIPOrderSlotData -- Synchronizes VIP order slot data from server to client and updates UI
PlayerVIPOrder:RequestRerollOrderSlot -- Processes VIP order reroll request from client deducting cost and creating new order
PlayerVIPOrder:RequestSubmitVIPOrder -- Processes VIP order submission request from client checking conditions and completing order
PlayerVIPOrder:CompleteVIPOrder -- Completes VIP order granting rewards and adding season score with logging
PlayerVIPOrder:CheckVIPOrderResetCool -- Decreases VIP order waiting time daily and resets to new order when it reaches 0
PlayerVIPOrder:RequestSyncVIPOrderSlotDataToServer -- Processes VIP order slot data server synchronization request from client
PlayerVIPOrder:RefreshCompleteStatus -- Refreshes VIP order completion status creating new orders for additional orders gained through upgrades
PlayerVIPOrder:CheckStartNewSeason -- Checks if VIP order season end notice or new season start should occur based on current month
PlayerVIPOrder:RequestGetSeasonReward -- Processes VIP order season reward collection request from client checking score conditions and granting rewards
PlayerVIPOrder:RequestSetFirstEnterUI -- Sets VIP order UI first entry status from client
PlayerVIPOrder:RequestResetVIPOrderSlot -- Processes VIP order slot reset request from client deducting cost and creating new order
PlayerVIPOrder:ResetVIPOrderSlot -- Resets specified VIP order slot replacing with new order data
PlayerVIPOrder:RequestSetCloseEnterUI -- Sets VIP order UI close notice entry status from client
PlayerVIPOrder:AddVIPOrderSeasonRewardScore -- Adds specified amount to VIP order season reward score
PlayerVIPOrder:VIPOrderRecipeLog -- Records VIP order recipe-related logs for game data analysis
PlayerVIPOrder:VIPOrderIngreLog -- Records VIP order ingredient-related logs for game data analysis
StorageCount:OnBeginPlay -- Loads storage count for all products in special shop at game start
StorageCount:LoadStorageCount -- Gets and returns storage count for specific product from world shop service
InteriorEntityCameraData:Load -- Loads camera data based on upgrade level
InteriorEntityCameraData:GetEntitiesOfTargetCamera -- Returns entity list corresponding to specific camera key
LobbyEntityLogic:SetEntities -- Sets main entities in lobby map
LobbyEntityLogic:SpawnDisplayCountText -- Creates display count text based on expansion level
LobbyEntityLogic:SetKitchenAppInfo -- Sets kitchen appliance information
LobbyEntityLogic:SetModelAfterSpawn -- Handles model setting after spawn
LobbyEntityLogic:GetEmployeeSpawnPostion -- Returns spawn position based on employee type
LobbyHUDService:OnBeginPlay -- Sets menu button icon animation at game start
LobbyHUDService:OnEndPlay -- Cleans up timers at game end
LobbyHUDService:OpenHUD -- Opens and initializes lobby HUD
LobbyHUDService:UpdateTrainingTokenUI -- Updates training token UI
LobbyHUDService:UpdateStoreInfoReportUI -- Updates store information report UI
LobbyHUDService:UpdateStoreInfoTrendUI -- Updates store information trend UI
LobbyHUDService:RefreshRemainText -- Refreshes remaining time text
LobbyHUDService:EnableTipUI -- Enables/disables tip UI
LobbyHUDService:UpdateTipUI -- Updates tip UI
LobbyHUDService:GainTip -- Gains tip
LobbyHUDService:UpdateTipMaxText -- Updates tip maximum text
LobbyHUDService:RefreshSubscriptionBoxButton -- Refreshes subscription box button
LobbyHUDService:UpdateBestEarningRecord -- Updates best earning record
LobbyHUDService:UpdateStoreNameUI -- Updates store name UI
LobbyHUDService:UpdateVIPOrderBtn -- Updates VIP order button
LobbyHUDService:ClearLobbyHUD -- Clears lobby HUD
LobbyHUDService:PlayGainTipEffectOnTipButton -- Plays tip gain effect on tip button
LobbyHUDService:RequestChangeStoreName -- Requests store name change
LobbyHUDService:ClearStoreInfoReportUI -- Clears store information report UI
LobbyHUDService:UpdateMoveNextStageBtn -- Updates move to next stage button
LobbyHUDService:OpenStartStageToast -- Opens stage start toast
LobbyHUDService:OpenStartDayToast -- Opens day start toast
LobbyHUDService:SetDropdownTestTimer -- Sets dropdown test timer
LobbyHUDService:HandlePlayerManagementChangedEvent -- Handles player management status change event
LobbyHUDService:HandlePlayerTrainingTokenChangedEvent -- Handles player training token change event
LobbyHUDService:HandlePlayerTipChangedEvent -- Handles player tip change event
LobbyHUDService:HandleButtonClickEvent -- Handles tip storage button click event
LobbyHUDService:HandleButtonClickEvent2 -- Handles ingredient subscription box button click event
LobbyHUDService:HandleBestEarningRecordChangedEvent -- Handles best earning record change event
LobbyHUDService:HandleButtonClickEvent6 -- Handles store information button click event
LobbyHUDService:HandleButtonClickEvent7 -- Handles store name change button click event
LobbyHUDService:HandleButtonClickEvent8 -- Handles move to next stage button click event
LobbyManager:RequestInit -- Requests lobby initialization from server
LobbyManager:InitClient -- Initializes lobby on client
LobbyManager:OnMapLeave -- Processes when leaving map
LobbyManager:OnBeginPlay -- Sets first entry flag at game start
LobbyRenovationService:SetEntities -- Sets entities needed for lobby renovation
LobbyRenovationService:RedesignInterior -- Redesigns interior
LobbyRenovationService:ExpandLobby -- Expands lobby
LobbyRenovationService:UpdateLobbyTileMap -- Updates lobby tile map
LobbyRenovationService:UpdatePostBox -- Updates post box position
LobbyRenovationService:UpdateWaitSeatPos -- Updates waiting seat position
LobbyRenovationService:UpdateAllInnerWall -- Updates all inner walls
LobbyRenovationService:UpdateInnerWallByAppIdx -- Updates inner wall by app index
LobbyRenovationService:AddBoxTile -- Adds box tile
LobbyRenovationService:RemoveTile -- Removes tile
LobbyRenovationService:UpdateInteriorObject -- Updates interior object
LobbyRenovationService:UpdateExteriorObject -- Updates exterior object
LobbyRenovationService:UpdateKitchenInterior -- Updates kitchen interior
LobbyRenovationService:GetParkingAreaEntity -- Gets parking area entity
LobbyRenovationService:GetHiddenAreaEntity -- Gets hidden area entity
LobbyRenovationService:SetInteriorEntityLayer -- Sets interior entity layer
OfflineRewardLogic:OpenUI -- Opens offline reward UI
OfflineRewardLogic:GetOfflineRewardAmount -- Calculates offline reward amount
OfflineRewardLogic:GetRewardTimeSec -- Calculates reward time in seconds
OfflineRewardLogic:GetMaxRewardTime -- Gets maximum reward time
OfflineRewardLogic:PlayAnimOnClickGetRewardButton -- Plays animation when reward button is clicked
OfflineRewardLogic:GetMoneyRUIDByRewardAmount -- Gets money RUID based on reward amount
OfflineRewardLogic:OfflineRewardLog -- Records offline reward log
OfflineRewardLogic:IsOfflinePopupOpened -- Checks if offline popup is opened
ReportMessageMaker:MakeReport -- Creates report message
ReportMessageMaker:CheckParamIsNilOrNot -- Checks if parameter is nil
ReportMessageMaker:RequestAddToReportQueue -- Requests addition to report queue
ReportMessageMaker:ReserveReport -- Reserves report
ReportMessageMaker:RequestRemoveToReportQueue -- Requests removal from report queue
ReportMessageMaker:OnEndPlay -- Cleans up timers at game end
ReportMessageMaker:Init -- Initializes report message maker
ReportMessageMaker:ClearReportQueue -- Clears report queue
TimeManager:SaveToDB -- Saves time data to DB
TimeManager:OnLoadedDataFromDB -- Processes data loaded from DB
TimeManager:InitComponent -- Initializes component
TimeManager:OnBeginPlay -- Sets first entry flag at game start
TimeManager:OnUpdate -- Updates time every frame
TimeManager:OnMapEnter -- Processes when entering map
TimeManager:OnMapLeave -- Processes when leaving map
TimeManager:UpdateTime -- Updates time
TimeManager:OnMonthChanged -- Processes when month changes
TimeManager:OnYearChanged -- Processes when year changes
TimeManager:OnDayChanged -- Processes when day changes
TimeManager:TimeFlowsChange -- Changes time flow status
TimeManager:RequestTimeFlowClient -- Requests time flow from client
TimeManager:GetTimeText -- Converts time to text
TimeManager:CheckCanTimeFlows -- Checks if time can flow
TimeManager:debugTimeFlow -- Sets debug time flow
TimeUIService:UpdateUI -- Updates time UI
UIGetOfflineRewardPopup:OnBeginPlay -- Disables popup at game start
UIGetOfflineRewardPopup:Init -- Initializes UI components
UIGetOfflineRewardPopup:Open -- Opens offline reward popup
UIGetOfflineRewardPopup:Refresh -- Refreshes UI
UIGetOfflineRewardPopup:Close -- Closes popup
UIGetOfflineRewardPopup:GetRandomEmployeeTable -- Gets random employee table
UIHUDDropDown:OnBeginPlay -- Initializes dropdown at game start
UIHUDDropDown:SetDropdownSize -- Sets dropdown size
UIHUDDropDown:SetDrawOfName -- Sets display status for specific item
UIHUDDropDown:ClearTweenerAndTimer -- Clears tweener and timer
UIHUDDropDown:CheckDropdownRedDotEnable -- Checks dropdown red dot activation
UIHUDDropDown:SetItemRedDot -- Sets red dot for specific item
UIHUDDropDown:SetTestTimer -- Sets test timer
UILobbyManager:OnBeginPlay -- Initializes UI at game start
UILobbyManager:HideStoreInfoArea -- Hides store information area
UILobbyManager:ShowStoreInfoArea -- Shows store information area
UILobbyManager:RequestUpdateSettlementRecordUI -- Requests settlement record UI update
UILobbyManager:RefreshMenuInfo -- Refreshes menu information
UILobbyManager:OpenMainMenu -- Opens main menu
UILobbyManager:CloseMainMenu -- Closes main menu
UILobbyManager:HandleButtonClickEvent -- Handles main menu button click event
UILobbyManager:HandleButtonClickEvent2 -- Handles main menu close button click event
UILobbyManager:HandleButtonClickEvent3 -- Handles main menu close button click event
UIMenuInfoComponent:OnBeginPlay -- Initializes UI components at game start
UIMenuInfoComponent:Refresh -- Refreshes menu information
UIMenuInfoComponent:UpdateDebugMonitorUIRecipe -- Updates debug monitor UI recipe
UIStartDayToast:OnBeginPlay -- Disables toast at game start
UIStartDayToast:Init -- Initializes UI components
UIStartDayToast:Open -- Opens day start toast
UIStartDayToast:StartRender -- Starts rendering
UIStartDayToast:OnEndPlay -- Cleans up timers at game end
UIStartDayToast:TypeWriter -- Executes typewriter effect
UIStartDayToast:PlayTypeWriter -- Plays typewriter effect
UIStartDayToast:EndTypeWriter -- Ends typewriter effect
UIStartDayToast:HandleKeyDownEvent -- Handles key down event
UIStoreInfoPageManager:OnBeginPlay -- Initializes pages at game start
UIStoreInfoPageManager:SetTabPage -- Sets tab page
UIStoreInfoPageManager:TabOffAll -- Turns off all tabs
UIStoreInfoPageManager:HandleButtonClickEvent -- Handles tab1 button click event
UIStoreInfoPageManager:HandleButtonClickEvent2 -- Handles tab2 button click event
UIStoreInfoPageManager:HandleButtonClickEvent3 -- Handles tab3 button click event
UIStoreInfoPageManager:HandleButtonClickEvent4 -- Handles tab4 button click event
UIStoreInfoPageManager:HandleButtonClickEvent5 -- Handles tab1 close button click event
UIStoreInfoPageManager:HandleButtonClickEvent6 -- Handles tab2 close button click event
UIStoreInfoPageManager:HandleButtonClickEvent7 -- Handles tab3 close button click event
UIStoreInfoPageManager:HandleButtonClickEvent8 -- Handles tab4 close button click event
CameraDataSetLogic:OnBeginPlay -- Loads camera dataset at logic start
CameraDataSetLogic:LoadDataSet -- Loads lobby camera data and interior camera data
CameraDataSetLogic:GetInteriorEntityCameraData -- Returns interior entity camera data for corresponding level
CameraDataSetLogic:GetLobbyCameraData -- Returns lobby camera data for corresponding expansion level
LobbyCameraData:Load -- Loads level-specific camera data from data table
LobbyCameraData:GetCameraTypeDataByKey -- Returns camera type data corresponding to key
LobbyCameraService:ChangeCameraTo -- Switches to camera corresponding to specified key
LobbyCameraService:SetCameraSetting -- Sets camera position and zoom ratio
LobbyCameraService:SetCamerasForExpansion -- Applies camera settings based on expansion level
LobbyCameraService:MoveMovingCamera -- Moves moving camera based on keyboard input
LobbyCameraService:OnUpdate -- Handles camera updates every frame
LobbyCameraService:MoveMovingCameraByTouchPoint -- Moves moving camera based on touch input
LobbyCameraService:InitCameras -- Initializes camera settings
LobbyCameraService:ToggleCameraSetOptions -- Toggles camera option UI
LobbyCameraService:StartCameraSetOptionsTween -- Starts camera option UI animation
LobbyCameraService:OnBeginPlay -- Performs initialization tasks at logic start
LobbyCameraService:OnClickCameraSetOptionBtn -- Processes camera option button click
LobbyCameraService:ForceCorrectPos -- Force corrects moving camera position within boundaries
LobbyCameraService:SwitchCamera -- Switches camera sequentially
LobbyCameraService:SetEnableCameraZoom -- Sets camera zoom function enable/disable
LobbyCameraService:SetMovingCameraByKey -- Sets moving camera position and zoom based on key
LobbyCameraService:ClearCameraSettingOnMap -- Clears camera settings on map
LobbyCameraService:GetZoomRatio -- Returns platform-adjusted zoom ratio
LobbyCameraService:HandleKeyDownEvent -- Handles key press event to set camera movement input
LobbyCameraService:HandleKeyUpEvent -- Handles key release event to release camera movement input
LobbyCameraService:HandleScreenTouchHoldEvent -- Handles screen touch hold event
LobbyCameraService:HandleScreenTouchReleaseEvent -- Handles screen touch release event
LobbyCameraService:HandleButtonClickEvent3 -- Handles cooking view camera button click event
LobbyCameraService:HandleButtonClickEvent4 -- Handles serving view camera button click event
LobbyCameraService:HandleButtonClickEvent5 -- Handles entrance view camera button click event
LobbyCameraService:HandleButtonClickEvent6 -- Handles camera option toggle button click event
LobbyCameraService:HandleButtonClickEvent -- Handles overall view camera button click event
LobbyCameraTypeData:Load -- Loads camera type data from row data
InteractionPeedbackScript:OnTouch -- Opens corresponding UI when customer or employee entity is touched
InteractionPeedbackScript:HandleUITouchDownEvent -- Handles UI touch down event to execute touch interaction
InteractionScript:OnBeginPlay -- Initialization that determines interaction type based on entity name
InteractionScript:OnTouch -- Touch processing that opens or closes appropriate UI based on interaction type
InteractionScript:HandleTouchEvent -- Handles touch event to execute touch interaction after UI overlay check
InteractionTipScript:Create -- Creates tip item and auto-removes after set time
InteractionTipScript:GetItem -- Obtains tip item updates UI and deletes entity
InteractionTipScript:HandleTouchEvent -- Handles tip item touch event to execute item obtaining after UI overlay check
InteractionUIService:OnBeginPlay -- Sets up interaction UI initialization and button event connections
InteractionUIService:OpenUIKitchenAppNone -- Opens kitchen appliance UI that requires upgrade
InteractionUIService:CloseUIKitchenAppNone -- Closes kitchen appliance upgrade required UI and resets selection state
InteractionUIService:OpenUIKitchenAppInfo -- Opens kitchen appliance information UI and displays current level and effects
InteractionUIService:CloseUIUIKitchenAppInfo -- Closes kitchen appliance information UI and resets selection state
InteractionUIService:ClickKitchenAppType -- Highlights corresponding appliances based on kitchen appliance type
InteractionUIService:UnClickKitchenAppType -- Removes highlighting for kitchen appliance type
InteractionUIService:UnClickAllKitchenAppType -- Removes highlighting for all kitchen appliances
InteractionUIService:ClickEmployee -- Selects and highlights employee
InteractionUIService:UnClickEmployee -- Removes employee highlighting
InteractionUIService:UpdateUIEmployeeInfo -- Updates employee information UI
InteractionUIService:OpenUIEmployeeInfo -- Opens employee information UI and makes employee selected
InteractionUIService:CloseUIEmployeeInfo -- Closes employee information UI and resets selection state
InteractionUIService:OpenDisplayBurgerCount -- Displays burger count text for display
InteractionUIService:CloseDisplayBurgerCount -- Hides burger count text for display
InteractionUIService:RefreshDisplayTextAll -- Refreshes burger count text for all displays
InteractionUIService:RefreshDisplayTextBySlotID -- Updates burger count text for specific display slot
InteractionUIService:CanNotFindDecokitchenApps -- Retries when display entity cannot be found
InteractionUIService:HandleScreenTouchReleaseEvent -- Handles screen touch release event to process UI closing
InteractionUIService:HandleEmployeeDetailChangeEvent -- Handles employee detail change event to update UI
SubscriptionPostBox:Refresh -- Refreshes subscription box status and updates notification display
SubscriptionPostBox:OnBeginPlay -- Initializes subscription box and sets up touch events
SubscriptionPostBox:OnTouch -- Requests item collection after UI overlay check when subscription box is touched
SubscriptionPostBox:HandleTouchEvent -- Handles touch event to execute subscription box touch interaction
ReputationDataSetLogic:OnBeginPlay -- Initializes effect index on client
ReputationDataSetLogic:ReturnSpawnDelay -- Calculates customer spawn delay based on player reputation and management level
ReputationDataSetLogic:ReturnReputationChangeByServingTime -- Calculates reputation change based on serving time
ReputationDataSetLogic:RequestReputationChange -- Requests reputation change and records log
ReputationDataSetLogic:PlayReputationChangeEffectHUD -- Plays reputation change effect on HUD
ReputationDataSetLogic:PlayReputationChangeEffectMap -- Plays reputation change effect on map
ReputationDataSetLogic:ReturnReputationReviewScore -- Calculates review score (0-5 points) based on player reputation
ReputationDataSetLogic:ReturnReviewStarCountByReputationAmount -- Returns star count based on reputation change amount
ReputationDataSetLogic:SetReputationDownServingTimeMin -- Sets minimum serving time where reputation decreases
ReputationManagementData:Load -- Loads reputation management data from CSV data table and stores in properties
UIReputation:Init -- Initializes star rating and score text components for reputation UI
UIReputation:Refresh -- Updates star rating UI and score text based on current reputation score
UIReputation:HandlePlayerReputationChangedEvent -- Refreshes UI when player reputation changes
UIReputation:HandleEarningLevelChangedEvent -- Refreshes UI when earning level changes
UIReputation:HandlePlayerManagementChangedEvent -- Refreshes UI when player management level changes
BestEarningRecordChangedEvent:Init -- Initializes best earning record change event data
EarningLevelChangedEvent:Init -- Initializes earning level change event data
SettlementData:ConvertToTable -- Converts settlement data to table format
SettlementData:SetFromTable -- Sets settlement data from table data
SettlementData:ReturnEarnings -- Calculates and returns total earnings
SettlementData:ReturnExpense -- Calculates and returns total expenses
SettlementData:ReturnNetIncome -- Calculates and returns net income (earnings - expenses)
SettlementPropertyEnum:ReadMe -- Settlement property enum class description
SettlementUIService:OpenUISettlement -- Opens settlement UI panel
SettlementUIService:ForceCloseUISettlement -- Force closes settlement UI panel
UISettlementItem:Init -- Initializes settlement item UI component
UISettlementItem:Refresh -- Refreshes UI based on settlement data
UISettlementItem:ReturnTitleValueTableOfEnum -- Returns title and value table based on enum
UISettlementPanel:Open -- Opens settlement panel and displays data
UISettlementPanel:Close -- Closes settlement panel
UISettlementPanel:OnBeginPlay -- Initializes UI elements at component start
UISettlementPanel:Refresh -- Updates UI based on settlement data
UISettlementPanel:OpenShopInfo -- Opens store information window
UISettlementPanel:StartTween -- Starts panel open/close tween animation
UISettlementPanel:DrawGraph -- Draws settlement graph
UISettlementPanel:ForceClose -- Force closes panel immediately
UISettlementPanel:HandleButtonClickEvent -- Handles close button click event
UISettlementPanel:HandleButtonClickEvent2 -- Handles store information button click event
UISettlementProgressGraphLine:Init -- Initializes graph line UI component
UISettlementProgressGraphLine:Refresh -- Updates graph line based on settlement data
UIStoreInfoRecordPage:OnBeginPlay -- Initializes UI elements at component start
UIStoreInfoRecordPage:RefreshData -- Updates store record page based on settlement data
UIStoreInfoRecordPage:HandleEmployeeDetailChangeEvent -- Handles employee detail change event
CustomerReviewData:Load -- Loads customer review data from data table
EmployeeReveiwStatusEnum:OnBeginPlay -- Initializes priority scores by employee status
EmployeeReveiwStatusEnum:ReturnReviewStatusIconRUID -- Returns icon RUID based on employee status
EmployeeReveiwStatusEnum:ReturnEmployeeStatus -- Determines and returns current employee status based on player and employee ID
EmployeeReveiwStatusEnum:ReturnRandomStatusComment -- Returns random comment based on employee status
StoreInfoDataSetLogic:OnBeginPlay -- Loads dataset at game start
StoreInfoDataSetLogic:LoadDataSet -- Loads customer review data and store information report data
StoreInfoDataSetLogic:ReturnPlayerScoreByCustomerReviewId -- Calculates and returns player score based on customer review ID
StoreInfoDataSetLogic:ReturnTutorialMainTags -- Returns player tutorial main tags
StoreInfoDataSetLogic:ReturnLackRecipeId -- Returns recipe ID that player lacks
StoreInfoReportData:Load -- Loads store information report data from data table
UICustomerReview:Open -- Opens customer review UI and refreshes data
UICustomerReview:Refresh -- Refreshes customer review list
UICustomerReview:OnBeginPlay -- Initializes UI elements at game start
UICustomerReview:ReturnCustomerReviewPool -- Returns customer review data pool sorted by score
UICustomerReviewSlotRenderer:OnBeginPlay -- Initializes UI elements at game start
UICustomerReviewSlotRenderer:Refresh -- Refreshes customer review slot data
UIEmployeeReview:OnBeginPlay -- Initializes UI elements and events at game start
UIEmployeeReview:Open -- Opens employee review UI and sets data
UIEmployeeReview:Refresh -- Refreshes employee review list
UIEmployeeReview:SetStatusData -- Sets status data for all employees
UIEmployeeReview:SetTitleBar -- Sets title bar UI and sort buttons
UIEmployeeReview:SetSortCriteria -- Sets sort criteria and refreshes UI
UIEmployeeReview:ReturnSortedEmployeeDetailTable -- Returns employee data sorted by sort criteria
UIEmployeeReview:SetUserDetailTable -- Sets employee detail table
UIEmployeeReview:HandleButtonClickEvent -- Handles employee management button click event
UIEmployeeReviewSlotRenderer:Init -- Initializes UI elements
UIEmployeeReviewSlotRenderer:Refresh -- Refreshes employee review slot data
UIEmployeeReviewSlotRenderer:HandleEmployeeDetailChangeEvent -- Handles employee detail change event
UIEmployeeReviewSortButton:OnBeginPlay -- Initializes sort key and UI elements at game start
UIEmployeeReviewSortButton:SetSortValue -- Sets sort value for general sort button
UIEmployeeReviewSortButton:SetSortValueSkill -- Sets sort value for skill sort button
UIEmployeeReviewSortButton:HandleButtonClickEvent -- Handles sort button click event
UIReputationFeedback:OnBeginPlay -- Initializes UI elements at game start
UIReputationFeedback:Refresh -- Refreshes UI based on feedback type
UIReputationFeedback:ReturnRandomEmployeeDataInStore -- Returns random employee data from serving employees in store
UIReputationFeedback:ReturnIconRUIDByFeedbackType -- Returns icon RUID based on feedback type
UIReputationRecentLog:OnBeginPlay -- Initializes UI elements at game start
UIReputationRecentLog:Refresh -- Refreshes UI based on reputation log information
UIReputationReview:Init -- Initializes UI elements
UIReputationReview:Open -- Opens reputation review UI and refreshes data
UIReputationReview:Refresh -- Refreshes reputation review data
UIReputationReview:RefreshRecentLogList -- Refreshes recent reputation log list
UIReputationReview:RefreshFeedbackList -- Refreshes feedback list
UIReputationReview:ReturnFeedbackTable -- Analyzes reputation logs to create feedback table
UIReputationReview:RefreshReputationStats -- Refreshes reputation statistics data
UIReputationReview:OnBeginPlay -- Performs initialization at game start
UIReputationReview:HandlePlayerReputationChangedEvent -- Handles player reputation change event
UIReputationReview:HandleEarningLevelChangedEvent -- Handles earning level change event
UIReputationReview:HandlePlayerManagementChangedEvent -- Handles player management data change event
UIReputationStat:Init -- Initializes UI elements
UIReputationStat:Refresh -- Displays reputation statistics data on UI
UISettlementRecord:Init -- Initializes UI elements
UISettlementRecord:Refresh -- Refreshes UI based on settlement data
UISettlementRecord:DrawGraph -- Draws settlement data graph
UISettlementRecord:OnBeginPlay -- Performs initialization at game start
UISettlementRecord:Open -- Opens settlement record UI and loads data
UISettlementRecord:RefreshTooltip -- Refreshes bonus information tooltip
UIStoreInfo:Open -- Opens store information UI and sets tab
UIStoreInfo:Close -- Closes store information UI
UIStoreInfo:OnBeginPlay -- Initializes UI elements at game start
UIStoreInfo:SetSelectTab -- Sets selected tab
UIStoreInfo:OnSelectTab -- Changes UI based on selected tab
UIStoreInfo:HandleButtonClickEvent -- Handles close button click event
UIStoreInfo:HandleButtonClickEvent2 -- Handles settlement button click event
UIStoreInfo:HandleButtonClickEvent3 -- Handles settlement button 2 click event
UIStoreInfo:HandleButtonClickEvent4 -- Handles reputation button click event
UIStoreInfoPageTabButton:OnBeginPlay -- Initializes UI elements at game start
UIStoreInfoPageTabButton:IsButtonSelected -- Sets UI animation based on button selection status
PlayerStoreManage:OnMapEnter -- Initializes store management UI and resets cooltime when player enters lobby map
PlayerStoreManage:Promotion -- Executes promotion function to attract customers
PlayerStoreManage:BurgerSupplyment -- Supplies burgers to burger display
PlayerStoreManage:CoolDown -- Increases cooltime for promotion and supply functions by 1
PlayerStoreManage:ResetCool -- Resets all cooltime and clears timers
PlayerStoreManage:UpdateCoolTimeUI -- Updates cooltime display in store management UI
PlayerStoreManage:RequestModifyClover -- Server function that deducts cost and executes function when using store management features
PlayerStoreManage:CanSupply -- Function called when supply function executes successfully
PlayerStoreManage:CheckBurgerIsFull -- Checks if all displays for current menu are full
PlayerStoreManage:ModifyDisplayBurger -- Actually adds burgers to display and creates report message
PlayerStoreManage:CanPromotion -- Function called when promotion function executes successfully
PlayerStoreManage:StartPromotion -- Server function that continuously spawns customers for set duration as promotion effect
PlayerStoreManage:FailToManageStore -- Displays toast message when store management function usage fails
PlayerStoreManage:SetData -- Loads store management data by stage and sets cooltime
StoreManageData:Load -- Loads store management data from CSV dataset and stores in struct
StoreManageStageData:Load -- Loads all management level store management data for specific stage
UIStoreManage:UpdateSupplymentCoolTimeUI -- Updates progress and remaining time for burger supply cooltime UI
UIStoreManage:UpdatePromotionCoolTimeUI -- Updates progress and remaining time for promotion cooltime UI
UIStoreManage:OnClickBtn -- Executes corresponding function when store management button is clicked
UIStoreManage:SetCost -- Displays cost of store management functions based on current management level and stage on UI
UIStoreManage:HandleButtonClickEvent2 -- Handles burger supply button click event
UIStoreManage:HandleButtonClickEvent3 -- Handles promotion button click event
UIStoreManageBtn:OnBeginPlay -- Performs initial setup for store management UI slide animation
UIStoreManageBtn:SetEnable -- Opens and closes store management UI with slide animation
UIStoreManageBtn:HandleButtonClickEvent -- Handles store management button click to process UI open/close
ToDoData:Load -- Reads ToDo information from CSV data table and loads into object
ToDoManager:OnBeginPlay -- Loads ToDo related datasets at game start
ToDoManager:LoadDataSet -- Loads EventToDoData and ToDoSecretaryData tables and caches them
ToDoManager:RefreshToDoList -- Refreshes appropriate ToDo list based on current stage
ToDoManager:GetData -- Returns ToDo data corresponding to given ID
ToDoManager:SetEnableRedDot -- Sets whether to display ToDo notification red dot
ToDoManager:OpenRelatedUI -- Opens UI linked to ToDo item
ToDoManager:SetNowToDo -- Finds and sets current ToDo to be progressed
ToDoManager:RefreshToDoInfos -- Refreshes ToDo information UI
ToDoManager:CanToDoAchieved -- Checks if current ToDo can be achieved
ToDoManager:RefreshSecretaryToDoList -- Refreshes secretary ToDo list
ToDoManager:RefreshTutorialToDoList -- Refreshes tutorial stage ToDo list
ToDoManager:GetToDoSecretaryData -- Returns secretary ToDo data corresponding to given ID
ToDoManager:IsToDoSecretaryOccured -- Checks if secretary ToDo condition is satisfied
ToDoManager:HandlePlayerManagementChangedEvent -- Event handler that updates ToDo information when player management status changes
UIToDoItemRenderer:OnBeginPlay -- Initializes UI components
UIToDoItemRenderer:Refresh -- Refreshes UI with general ToDo data
UIToDoItemRenderer:RefreshSecretary -- Refreshes UI with secretary ToDo data
ToDoSecretaryData:Load -- Loads todo secretary data from CSV data table and sets object properties
UIDiaInfo:OnBeginPlay -- Initializes diamond acquisition method information and loads shop product data
UIDiaInfo:OpenUI -- Opens diamond information UI and displays currently owned diamonds
UIDiaInfo:SetContents -- Sets diamond acquisition method list based on player status
UIDiaInfo:SetScrollView -- Sets up recycle scroll view and displays items
UIDiaInfo:RegisterRecycleScrollLayoutCallback -- Registers cell update callback for recycle scroll view
UIDiaInfo:RecycleScrollOnUpdateByIndex -- Updates specific index item in scroll view
UIDiaInfo:MoveUI -- Moves to corresponding UI based on selected diamond acquisition method
UIDiaInfo:Close -- Closes diamond information UI
UIDiaInfo:PurchaseCountCheck -- Checks purchase status for each product to set bonus display
UIDiaInfo:SortContents -- Sorts items with bonuses to top
UIDiaInfo:HandleButtonClickEvent -- Event handler that opens UI when diamond information button is clicked
UIDiaInfo:HandleButtonClickEvent2 -- Event handler that closes UI when close button is clicked
UIDiaInfo:HandleButtonClickEvent3 -- Event handler that opens corresponding shop when employee equipment shop button is clicked
UIDiaInfo:HandleButtonClickEvent4 -- Event handler that opens collection UI when ingredient collection button is clicked
UIDiaInfo:HandleButtonClickEvent5 -- Event handler that closes UI when additional close button is clicked
UIDiaInfoSlot:OnBeginPlay -- Initializes slot UI elements
UIDiaInfoSlot:Init -- Initializes diamond acquisition method slot and sets bonus information
UIDiaInfoSlotMoveBtn:HandleButtonClickEvent -- Event handler that moves to corresponding UI when diamond acquisition method slot move button is clicked
CookEmployeeAIScript:OnBeginPlay -- Handles cook employee AI initialization at game start
CookEmployeeAIScript:StateManager -- Main function that manages cook employee AI state
CookEmployeeAIScript:WAIT -- Processing function when cook employee is in waiting state
CookEmployeeAIScript:WORK -- Processing function when cook employee is cooking
CookEmployeeAIScript:DISPLAY -- Function for cook employee to display completed food on display stand
CookEmployeeAIScript:DESTROY -- Processing function when cook employee entity is removed
CookEmployeeAIScript:SelectMenu -- Function to select menu to cook (based on minimum stock)
CookEmployeeAIScript:GetSpawnBurgerCount -- Calculates number of burgers to create based on employee capability
CookEmployeeAIScript:HandleEmployeeMoveChangedEvent -- Handler for employee movement state change event
CookEmployeeAIScript:HandleEmployeeDetailChangeEvent -- Handler for employee detail information change event
CookEmployeeAIScript:HandleExpansionLobbyEvent -- Handler for lobby expansion event
EmployeeData:Load -- Loads employee information from dataset by employee ID
EmployeeData:ConvertToTable -- Converts employee data to table format
EmployeeData:ReturnSpecializedStat -- Returns employee's specialized stat type
EmployeeDetailChangeEvent:Init -- Initializes employee detail information change event
EmployeeDetailData:Load -- Initializes employee detail data by employee ID
EmployeeDetailData:ConvertToTable -- Converts employee data to table format
EmployeeDetailData:ConvertToDBTable -- Converts employee data to DB storage table
EmployeeDetailData:SetFromTable -- Sets employee information from table data
EmployeeDetailData:SetFromTable_Ver2 -- Sets employee information from version 2 table data
EmployeeDetailData:ReturnChuchuTotalLevel -- Returns ChuChu's total level
EmployeeDetailData:ReturnStatLevelByStatType -- Returns level based on stat type
EmployeeDetailData:ReturnTypeLevel -- Returns level based on employee type
EmployeeDetailData:ReturnMaxLevelFromOverLimitLevel -- Returns maximum level based on over-limit level
EmployeeDetailData:ReturnOverLimitLevelFromGrade -- Returns over-limit level based on grade
EmployeeDetailData:ReturnMoveSpeedText -- Converts movement speed level to text
EmployeeDetailData:ReturnTypeExp -- Returns experience based on employee type
EmployeeDetailData:InitEmploymentLevel -- Initializes employment level
EmployeeInfoScript:OnBeginPlay -- Handles employee information script initialization at game start
EmployeeInfoScript:Init -- Initializes employee UI elements
EmployeeInfoScript:Create -- Creates employee entity and performs initial setup
EmployeeLocationData:ConvertToDBTable -- Converts employee location data to DB storage table
EmployeeLocationData:SetFromTable -- Sets employee location information from table data
EmployeeLocationData:SetFromTable_Ver2 -- Sets employee location information from version 2 table data
EmployeeManager:SaveToDB -- Saves employee data to DB
EmployeeManager:OnLoadedDataFromDB -- Processes employee data loaded from DB
EmployeeManager:InitComponent -- Initializes employee manager component
EmployeeManager:SaveToOutDB -- Saves employee external data to DB
EmployeeManager:OnLoadedDataFromOutDB -- Processes employee data loaded from external DB
EmployeeManager:OnMapLeave -- Processes employee data when leaving map
EmployeeManager:MapLeaveClient -- Processes on client when leaving map
EmployeeManager:Init -- Initializes employee manager
EmployeeManager:InitOfDB -- Initializes employee manager with DB data
EmployeeManager:InitChuchuOutgameDetailData -- Initializes ChuChu outgame detail data
EmployeeManager:SyncData -- Synchronizes employee data to client
EmployeeManager:GetEmployeeDetail -- Returns employee detail data by employee ID
EmployeeManager:GetEmployeeLocation -- Returns employee location data by employee ID
EmployeeManager:GetEmployeeOutgameDetail -- Returns employee outgame detail data by employee ID
EmployeeManager:GetEmployeeDetailIndex -- Returns employee detail data index by employee ID
EmployeeManager:GetEmployeeLocationIndex -- Returns employee location data index by employee ID
EmployeeManager:ConvertEmpOutgameDetailToTable -- Converts employee outgame detail data to table
EmployeeManager:ConvertTableToEmpOutgameDetail -- Converts table data to employee outgame detail data
EmployeeManager:ConvertEmpLocationToTable -- Converts employee location data to table
EmployeeManager:ConvertEmpDetailToTable -- Converts employee detail data to table
EmployeeManager:ConvertTableToEmployeeLocation -- Converts table data to employee location data
EmployeeManager:UpdateDetailData -- Updates employee detail data
EmployeeManager:ConvertTableToEmpDetail -- Converts table data to employee detail data
EmployeeManager:UpdateLocationData -- Updates employee location data
EmployeeManager:ReturnEmployeeMoveSpeed -- Calculates and returns employee movement speed
EmployeeManager:RemoveSingleData -- Removes single data
EmployeeManager:ChangeLocationToWaiting -- Changes employee location to waiting state
EmployeeManager:ChangeLocationToStore -- Changes employee location to store
EmployeeManager:RequestChangeLocationToWaiting -- Requests moving employee to waiting location
EmployeeManager:RequestChangeLocationToStore -- Requests moving employee to store location
EmployeeManager:CreateEmployee -- Creates employee
EmployeeManager:AddEmployee -- Adds employee
EmployeeManager:DestroyEmployee -- Removes employee
EmployeeManager:CheckEmployeeAlreadyHave -- Checks if employee is already owned
EmployeeManager:CheckHasAllEmployee -- Checks if all employees are owned
EmployeeManager:EmployeeStateStop -- Stops employee state
EmployeeManager:EmployeeStateStart -- Starts employee state
EmployeeManager:OnButtonClickTransfer -- Processes transfer button click
EmployeeManager:TransferEmployee -- Transfers employee
EmployeeManager:RequestTransferEmployee -- Requests employee transfer
EmployeeManager:RewardTransfer -- Processes transfer reward
EmployeeManager:FinishTransfer -- Completes transfer
EmployeeManager:FailTransfer -- Processes transfer failure
EmployeeManager:ShowTransferRewardUI -- Displays transfer reward UI
EmployeeManager:ReturnTotalSalary -- Returns total salary
EmployeeManager:ReturnDailySalary -- Returns daily salary
EmployeeManager:ReturnEmployeeDailySalary -- Returns employee's daily salary
EmployeeManager:ReturnEmployeeWage -- Returns employee's base wage
EmployeeManager:ReturnEmployeeSalary -- Returns specific employee's salary
EmployeeManager:ReturnEmployeeNextOverLimitWage -- Returns employee's next over-limit wage
EmployeeManager:ReturnTransferRefundJemCost -- Returns gem cost to be refunded during transfer
EmployeeManager:SyncLocationData -- Synchronizes employee location data
EmployeeManager:SyncDetailData -- Synchronizes employee detail data
EmployeeManager:SyncInsertLocationData -- Synchronizes by inserting employee location data
EmployeeManager:SyncInsertDetailData -- Synchronizes by inserting employee detail data
EmployeeManager:CallbackAfterSyncDetailTable -- Callback function after detail table synchronization
EmployeeManager:loggingEmployeeTable -- Logs employee table
EmployeeManager:SetKitchenAppId -- Sets kitchen app ID
EmployeeManager:AddEmployeeEquipLevel -- Adds employee equipment level
EmployeeManager:SetEmployeeEquipLevel_ToClient -- Sets employee equipment level to client
EmployeeManager:SetEmployeeEquipLevel_ForCheat -- Cheat function to set employee equipment level
EmployeeManager:ReturnSkillGrade -- Returns employee's skill grade
EmployeeManager:ReturnHasEquip -- Returns whether employee has equipment
EmployeeManager:ChuchuAddedInCollection -- Adds ChuChu to collection
EmployeeManager:SyncChuchuInCollection -- Synchronizes ChuChu collection status
EmployeeManager:ChuchuSubedInCollection -- Removes ChuChu from collection
EmployeeManager:LogEmployeeTrasfer -- Records employee transfer to log
EmployeeManager:ClearEmployeeDetailTable -- Clears employee detail table
EmployeeManager:InsertEmployeeDetailTable -- Inserts data into employee detail table
EmployeeManager:RemoveEmployeeDetailTable -- Removes data from employee detail table
EmployeeManager:ChangeEmployeeDetailTable -- Changes data in employee detail table
EmployeeManager:SyncEmployeeDetailTable -- Synchronizes employee detail table
EmployeeManager:UpdateServingEmployeeLocationTable -- Updates serving employee location table
EmployeeManager:SetChuchuMoveSpeed -- Sets ChuChu's movement speed
EmployeeMoveChangedEvent:Init -- Initializes employee movement event
EmployeeMoveChangedEvent:InitExcpetType -- Initializes employee movement event excluding type
EmployeeMoveStatLevelExpData:Load -- Loads employee movement stat experience data by level
EmployeeOutgameDetailData:Load -- Initializes employee outgame detail data by employee ID
EmployeeOutgameDetailData:ConvertToDBTable_ExceptId -- Converts outgame data to DB table excluding ID
EmployeeOutgameDetailData:SetFromTable -- Sets outgame detail information from table data
EmployeeOutgameDetailData:SetFromTable_Ver2 -- Sets outgame detail information from version 2 table data
EmployeeRUID:ReturnIconRUIDByStatType -- Returns icon RUID based on employee type
EmployeeService:OnBeginPlay -- Initializes employee service at game start
EmployeeService:LoadData -- Loads employee-related data
EmployeeService:LoadConfigData -- Loads game configuration data
EmployeeService:GetData -- Returns employee data by employee ID
EmployeeService:GetStatLevelData -- Returns employee stat data by level
EmployeeService:ReturnWorkDuration -- Calculates employee work duration
EmployeeService:IsStatLevelLow -- Checks if employee stat level is low
EmployeeService:IsStatLowByEarningLevelData -- Checks if employee stat is low based on earning level data
EmployeeService:ReturnTransferHeart -- Calculates heart cost required for employee transfer
EmployeeService:UpdateAnim -- Updates employee animation
EmployeeService:ReturnHasBurgerEntities -- Returns list of burger entities owned by employee
EmployeeService:ReturnCanStackByDisplayID -- Returns stackable quantity by display ID
EmployeeService:ReturnRemainBurgerByDisplayID -- Returns remaining burger quantity by display ID
EmployeeService:ReturnChuchuLevel -- Returns ChuChu's level
EmployeeService:ReturnOverLimitLevelByMaxLevel -- Returns over-limit level by maximum level
EmployeeService:ReturnDeposit -- Returns employment deposit
EmployeeService:ReturnMaxLevelByOverLimitLevel -- Returns maximum level by over-limit level
EmployeeService:ReturnRandomCharId -- Returns random character ID
EmployeeService:ReturnBestLevelOfType -- Returns highest level of specific type
EmployeeService:ReturnChuchuIdListByGroupId -- Returns ChuChu ID list by group ID
EmployeeService:ReturnStageEmpIdList -- Returns employee ID list by stage ID
EmployeeService:GetNearestDisplayId -- Returns nearest display ID
EmployeeService:GetCloserDisplayId -- Returns closer display ID between two
EmployeeStatByLevelData:Load -- Loads employee stat data by level ID
EmployeeStatByLevelData:ConvertToTable -- Converts employee stat data to table
EmployeeStatLevelExpData:Load -- Loads experience data by level
EmployeeStatLevelExpData:GetExpSum -- Returns cumulative experience considering player bonus
EmployeeStatLevelExpData:GetExp -- Returns experience considering player bonus
EmployeeUIService:ProgressUICreate -- Creates employee work progress UI
EmployeeUIService:ProgressUIInit -- Initializes employee work progress UI
EmployeeUIService:ProgressUIOn -- Activates employee work progress UI
EmployeeUIService:PreogressUIOff -- Deactivates employee work progress UI
EmployeeUIService:ProgressUIUpdate -- Updates employee work progress UI
EmployeeUIService:PeedbackUICreate -- Creates employee feedback UI
EmployeeUIService:PeedbackUIClose -- Closes employee feedback UI
EmployeeUIService:PeedbackUIUpdate -- Updates employee feedback UI
EmployeeUIService:DrawPortraitWithEquip -- Draws employee portrait with equipment
ServingEmployeeAIScript:OnBeginPlay -- Handles serving employee AI initialization at game start
ServingEmployeeAIScript:StateManager -- Main function that manages serving employee AI state
ServingEmployeeAIScript:WAIT -- Processing function when serving employee is in waiting state
ServingEmployeeAIScript:ORDER -- Processing function when serving employee is taking orders
ServingEmployeeAIScript:SALES -- Processing function when serving employee is selling food
ServingEmployeeAIScript:DESTROY -- Processing function when serving employee entity is removed
ServingEmployeeAIScript:PICKUP -- Processing function when serving employee is picking up food
ServingEmployeeAIScript:SetStateManagerTimer -- Sets state management timer
ServingEmployeeAIScript:HandleEmployeeMoveChangedEvent -- Handles employee movement state change event
ServingEmployeeAIScript:HandleEmployeeDetailChangeEvent -- Handles employee detail information change event
ServingEmployeeAIScript:HandleExpansionLobbyEvent -- Handles lobby expansion event
UIEmployeeListService:Set -- Sets employee list UI
UIEmployeeListService:SpecializedStat -- Displays employee's specialized stat
UIEmployeeSkillSlotSmall:OnBeginPlay -- Initializes skill slot UI at game start
UIEmployeeSkillSlotSmall:Refresh -- Refreshes employee skill slot
UIEmployeeSkillSlotSmall:ToggleSkillDescText -- Toggles skill description text
UIEmployeeSkillSlotSmallNew:Init -- Initializes new skill slot UI
UIEmployeeSkillSlotSmallNew:Refresh -- Refreshes employee skill slot
ChuchuCollectionDB:SaveToDB -- Saves ChuChu collection data to DB
ChuchuCollectionDB:OnLoadedDataFromDB -- Applies data loaded from DB to collection
ChuchuCollectionDB:ChangeChuchuCollectionState -- Changes ChuChu collection state (collect/release)
ChuchuCollectionDB:CountStageCollectionPercent -- Calculates collection progress by stage
ChuchuCollectionDB:OnSyncProperty -- Handles UI update during property synchronization
ChuchuCollectionDB:CountCollectionPercent -- Calculates total collection achievement rate and clover bonus
ChuchuCollectionDB:UpdateCollectionPercent -- Updates collection percent UI on client
ChuchuCollectionDB:GroupLevelReward -- Grants group level achievement reward
ChuchuCollectionDB:SyncStageCollectionProgress -- Synchronizes stage collection progress to client
ChuchuCollectionDB:CalcGroupLevel -- Calculates current level of group based on equipment level
ChuchuCollectionDB:AfterRewardGroupLevel -- Handles UI updates after granting group level reward
ChuchuCollectionDB:LogChuchuCollection -- Records ChuChu collection related logs
ChuchuCollectionDB:LogChuchuEquipPurchase -- Records ChuChu equipment purchase logs
ChuchuCollectionDB:LogChuchuEquipUpgrade -- Records ChuChu equipment upgrade logs
ChuchuCollectionDB:GiveChuchuCollectionReward -- Grants ChuChu collection achievement reward
ChuchuCollectionDB:AfterChuchuCollectionReward -- Updates UI after granting ChuChu collection reward
ChuchuCollectionDB:StageReward -- Grants stage collection achievement reward
ChuchuCollectionDB:AfterCollectionLvReward -- Updates UI after granting collection level reward
ChuchuCollectionDB:UpdateCollectionRedDot -- Updates collection related red dot indicator
ChuchuCollectionDB:CheckIsRewardGroupLevelReward -- Checks if group level reward has already been received
ChuchuCollectionDB:UpdateOnGroupLevelReward -- Updates group level reward received status
ChuchuCollectionDB:ToastItemOverMaxCount -- Displays popup when item exceeds maximum holding capacity
ChuchuGroupData:Load -- Loads group information from data table
ChuchuGroupLogic:OnBeginPlay -- Handles initialization at game start
ChuchuGroupLogic:LoadDataSet -- Loads ChuChu group dataset
ChuchuGroupLogic:GetChuchuGroupData -- Returns ChuChu group data by group ID
ChuchuGroupLogic:ReturnStageIdFromGroupId -- Returns corresponding stage ID by group ID
ChuchuGroupLogic:RetrunGroupIdsFromStageId -- Returns corresponding group ID list by stage ID
GroupCollectionRewardData:Load -- Loads group collection reward data from data table
GroupCollectionRewardData:ReturnRewardIdFromType -- Returns appropriate reward item ID based on reward type
GroupCollectionRewardDataSetLogic:OnBeginPlay -- Loads dataset at game start
GroupCollectionRewardDataSetLogic:LoadDataSet -- Loads group collection reward dataset
GroupCollectionRewardDataSetLogic:GetGroupCollectionRewardData -- Returns group collection reward data based on level
InfoPopupLogic:CloseUI -- Closes information popup UI
InfoPopupLogic:OpenUI -- Opens information popup UI
InfoPopupLogic:Set -- Sets information popup content
InfoPopupLogic:OnBeginPlay -- Handles initialization at game start
InfoPopupLogic:HandleButtonClickEvent -- Handles information popup close button click event
InfoPopupLogic:HandleButtonClickEvent2 -- Handles information popup close button click event
InfoPopupLogic:HandleButtonClickEvent3 -- Handles information popup open button click event
InfoPopupLogic:HandleButtonClickEvent4 -- Handles information popup open button click event
InfoPopupLogic:HandleButtonClickEvent5 -- Handles information popup open button click event
InfoPopupLogic:HandleButtonClickEvent6 -- Handles information popup open button click event
UIChuchuCollection:OnBeginPlay -- Handles UI initialization at game start
UIChuchuCollection:OpenUI -- Opens ChuChu collection UI
UIChuchuCollection:CloseUI -- Closes ChuChu collection UI
UIChuchuCollection:SetStgIcons -- Sets stage icons
UIChuchuCollection:SetScrollView -- Sets scroll view according to stage
UIChuchuCollection:UpdateChuchuGroupSlot -- Updates ChuChu group slot
UIChuchuCollection:OnClickStgIcon -- Processes stage icon click
UIChuchuCollection:UpdateChuchuSlot -- Updates ChuChu slot
UIChuchuCollection:OnClickChuchuSlot -- Displays detailed information when ChuChu slot is clicked
UIChuchuCollection:OnClickGroupSlot -- Displays group information when group slot is clicked
UIChuchuCollection:OnClickChuchuInfoGroupBtn -- Processes group button click in ChuChu information
UIChuchuCollection:OpenBuyEquipPopup -- Opens equipment purchase popup
UIChuchuCollection:CloseBuyEquipPopup -- Closes equipment purchase popup
UIChuchuCollection:OpenUpgradeEquipPopup -- Opens equipment upgrade popup
UIChuchuCollection:CloseUpgradeEquipPopup -- Closes equipment upgrade popup
UIChuchuCollection:OnPurchaseEquipCompleted -- Updates UI after equipment purchase completion
UIChuchuCollection:ResetEquipStarsUI -- Resets equipment star UI
UIChuchuCollection:ResetEmployeeEquipUpgradePopup -- Resets employee equipment upgrade popup
UIChuchuCollection:OnUpgradeEquipCompleted -- Updates UI after equipment upgrade completion
UIChuchuCollection:ResetEquipDesc -- Resets description text based on equipment level
UIChuchuCollection:HandleEventToPopup -- Processes popup event handling
UIChuchuCollection:ResetEmployeeEquipBuyPopup -- Resets employee equipment purchase popup
UIChuchuCollection:UpdateCollectionPercent -- Updates collection achievement rate
UIChuchuCollection:UpdateStageCollectionGauge -- Updates stage collection gauge
UIChuchuCollection:UpdateGroupLevelUI -- Updates group level UI
UIChuchuCollection:OnClickGroupLevelRewardIcon -- Processes group level reward icon click
UIChuchuCollection:AfterRewardGroupLevel -- Processes effect after granting group level reward
UIChuchuCollection:UpdateGroupLevelRewardList -- Updates group level reward list
UIChuchuCollection:UpdateStageCollectionReward -- Updates stage collection reward
UIChuchuCollection:OnClickStageGaugeDiaIcon -- Processes stage gauge diamond icon click
UIChuchuCollection:ChuchuCollectionReward -- Requests ChuChu collection reward
UIChuchuCollection:AfterChuchuCollectionReward -- Processes effect after granting ChuChu collection reward
UIChuchuCollection:SkillUpgradePopup -- Displays skill upgrade popup
UIChuchuCollection:CheckCollectionRedDot -- Checks collection red dot display status
UIChuchuCollection:CheckStageIconRedDot -- Checks stage icon red dot display status
UIChuchuCollection:CheckGroupRedDot -- Checks group red dot display status
UIChuchuCollection:RegisterRecycleScrollLayoutCallback -- Registers recycle scroll layout callback
UIChuchuCollection:CalcIndexFromGroupId -- Calculates index from group ID
UIChuchuCollection:CalcGroupIdFromIndex -- Calculates group ID from index
UIChuchuCollection:ReturnEntityByGroupId -- Returns entity by group ID
UIChuchuCollection:RecycleScrollOnUpdateByIndex -- Handles recycle scroll index update
UIChuchuCollection:RecycleScrollOnUpdateByGroupId -- Handles recycle scroll group ID update
UIChuchuCollection:ReturnEntityByEmpId -- Returns entity by employee ID
UIChuchuCollection:ScrollToGroup -- Scrolls to specific group
UIChuchuCollection:SetRedDotOnBegin -- Sets initial red dot display status
UIChuchuCollection:HandleButtonClickEvent -- Handles collection UI open button click event
UIChuchuCollection:HandleButtonClickEvent2 -- Handles collection UI close button click event
UIChuchuCollection:HandleButtonClickEvent3 -- Handles equipment purchase button click event
UIChuchuCollection:HandleButtonClickEvent4 -- Handles equipment purchase popup close button click event
UIChuchuCollection:HandleButtonClickEvent5 -- Handles equipment upgrade button click event
UIChuchuCollection:HandleButtonClickEvent6 -- Handles equipment upgrade popup close button click event
UIChuchuCollection:HandleButtonClickEvent7 -- Handles employee collection open button click event
UIChuchuCollection:HandleButtonClickEvent8 -- Handles collection group button click event
UIChuchuCollection:HandleButtonClickEvent9 -- Handles upgrade popup close button click event
UIChuchuCollection:HandleButtonClickEvent10 -- Handles purchase popup close button click event
UIChuchuCollection:HandleButtonClickEvent11 -- Handles selected employee collection open button click event
UIChuchuCollection:HandleButtonClickEvent12 -- Handles stage gauge diamond icon1 click event
UIChuchuCollection:HandleButtonClickEvent13 -- Handles stage gauge diamond icon2 click event
UIChuchuCollectionSlot:OnBeginPlay -- Handles UI initialization at game start
UIChuchuCollectionSlot:Init -- Initializes ChuChu collection slot
UIChuchuCollectionSlot:UpdateGroupLevelUI -- Updates group level UI
UIChuchuCollectionSlot:UpdateChuchuSlot -- Updates ChuChu slot and returns red dot status
UIChuchuCollectionSlot:UpdateGroupLevel -- Updates group level
UISelectChuchuInCollection:OnBeginPlay -- Handles UI initialization at game start
UISelectChuchuInCollection:UpdateChuchuList -- Updates ChuChu list according to filter
UISelectChuchuInCollection:OnClickChuchuSlot -- Displays detailed information when ChuChu slot is clicked
UISelectChuchuInCollection:OpenUI -- Opens ChuChu selection UI
UISelectChuchuInCollection:CloseUI -- Closes ChuChu selection UI
UISelectChuchuInCollection:OnClickSelectBtn -- Processes select button click
UISelectChuchuInCollection:OnClickFilterBtn -- Processes filter button click
UISelectChuchuInCollection:OnClickFilterCategory -- Processes filter category selection
UISelectChuchuInCollection:RegisterRecycleScrollLayoutCallback -- Registers recycle scroll layout callback
UISelectChuchuInCollection:RecycleScrollOnUpdateByIndex -- Handles recycle scroll index update
UISelectChuchuInCollection:CalcEmpIdFromIndex -- Calculates employee ID from index
UISelectChuchuInCollection:UpdateSlotOutline -- Updates outline for selected slot
UISelectChuchuInCollection:HandleButtonClickEvent -- Handles select button click event
UISelectChuchuInCollection:HandleButtonClickEvent2 -- Handles UI close button click event
UISelectChuchuInCollection:HandleButtonClickEvent3 -- Handles UI open button click event
UISelectChuchuInCollection:HandleButtonClickEvent4 -- Handles all button click event
UISelectChuchuInCollection:HandleButtonClickEvent5 -- Handles serving employee filter button click event
UISelectChuchuInCollection:HandleButtonClickEvent6 -- Handles filter button click event
UISelectChuchuInCollection:HandleButtonClickEvent7 -- Handles all filter button click event
UISelectChuchuInCollection:HandleButtonClickEvent8 -- Handles equipment purchase button click event
UIEmployeeManageDeployList:OnBeginPlay -- Initializes employee deployment list UI at game start
UIEmployeeManageDeployList:Init -- Initializes employee deployment slots and sets lock status
UIEmployeeManageDeployList:RefreshList -- Refreshes deployed employee list
UIEmployeeManageDeployList:RefreshDeployeCount -- Refreshes deployed employee count
UIEmployeeManageDeployList:UpdateSlotOutline -- Updates slot outline for selected employee
UIEmployeeManageDeployList:ReturnRemainSlotIdx -- Returns index of remaining empty slot
UIEmployeeManageDeployList:CheckEmptySlotForRedDot -- Checks if empty slot exists and displays red dot
UIEmployeeManageDeployListRenderer:OnBeginPlay -- Initializes deployment list renderer at game start
UIEmployeeManageDeployListRenderer:Init -- Initializes deployment list renderer
UIEmployeeManageDeployListRenderer:Set -- Sets deployment list renderer with employee ID
UIEmployeeManageDeployListRenderer:OnClick -- Processes slot click
UIEmployeeManageDeployListRenderer:EnableOutline -- Enables slot outline
UIEmployeeManageDeployListRenderer:DisableOutline -- Disables slot outline
UIEmployeeManageDeployListRenderer:HandleButtonClickEvent -- Handles deployment list slot click event
UIEmployeeManageDeployListRenderer:HandleEmployeeDetailChangeEvent -- Handles employee detail change event
UIEmployeeManageDetailRenderer:OnBeginPlay -- Initializes employee detail renderer at game start
UIEmployeeManageDetailRenderer:Set -- Sets detail information with employee ID
UIEmployeeManageDetailRenderer:SpecializedStat -- Displays employee's specialized stat
UIEmployeeManageDetailRenderer:HandleEmployeeDetailChangeEvent -- Handles employee detail change event
UIEmployeeManageList:OnBeginPlay -- Initializes employee management list UI at game start
UIEmployeeManageList:Init -- Initializes employee management list
UIEmployeeManageList:OnClickFilterCategoryBtn -- Sets filter type and refreshes list when filter category button is clicked
UIEmployeeManageList:OnClickSortTypeBtn -- Sets sort method and refreshes list when sort type button is clicked
UIEmployeeManageList:RefreshList -- Refreshes employee list and resets scroll position
UIEmployeeManageList:UpdateSlotOutline -- Updates slot outline for selected employee
UIEmployeeManageList:RegisterRecycleScrollLayoutCallback -- Registers recycle scroll layout callback
UIEmployeeManageList:RecycleScrollOnUpdateByIndex -- Updates recycle scroll cell according to index
UIEmployeeManageList:CalcEmpIdFromIndex -- Calculates and returns employee ID from index
UIEmployeeManageList:FindEntityFromEmpId -- Finds and returns corresponding entity from employee ID
UIEmployeeManageList:UpdateEmpSlotFromEmpId -- Updates corresponding slot from employee ID
UIEmployeeManageListRenderer:Set -- Sets renderer state with employee ID
UIEmployeeManageListRenderer:EnableOutline -- Enables selection outline
UIEmployeeManageListRenderer:DisableOutline -- Disables selection outline
UIEmployeeManageListRenderer:OnClick -- Processes employee slot click
UIEmployeeManageListRenderer:SwitchOutline -- Toggles outline for selected slot
UIEmployeeManageListRenderer:Init_EmployeeManage -- Initializes renderer for employee management
UIEmployeeManageListRenderer:OnChangeLocation -- Updates UI when employee location changes
UIEmployeeManageListRenderer:Init_SelectChuchuInCollection -- Initializes renderer for ChuChu collection selection
UIEmployeeManageListRenderer:Init_Training -- Initializes renderer for training
UIEmployeeManageListRenderer:CheckEmployeeTrainingSetting -- Checks if employee is included in training setting
UIEmployeeManageListRenderer:ChangeChuchuListSlotState_Auto -- Changes ChuChu list slot state according to auto training status
UIEmployeeManageListRenderer:ChangeChuchuListSlotState_Auto_Fixed -- Changes auto training slot state to fixed state
UIEmployeeManageListRenderer:CheckEmployeeIsAutoTraining -- Checks if employee is in auto training and returns slot number
UIEmployeeManageListRenderer:HandleButtonClickEvent -- Handles button click event
UIEmployeeManageListRenderer:HandleEmployeeDetailChangeEvent -- Handles employee detail change event
UIEmployeeManageScript:Init -- Initializes employee management script
UIEmployeeManageScript:ChangeLocationToClient -- Changes employee location on client
UIEmployeeManageScript:ChangeLocationToServer -- Requests employee location change to server
UIEmployeeManageScript:OnClickDeployBtn -- Processes deployment button click
UIEmployeeManageScript:HandleButtonClickEvent1 -- Handles button click event
UIEmployeeManageService:OnBeginPlay -- Initializes employee management UI service at game start
UIEmployeeManageService:UIOpen -- Opens employee management UI
UIEmployeeManageService:UIClose -- Closes employee management UI
UIEmployeeManageService:UIRefresh -- Refreshes employee management UI
UIEmployeeManageService:RefreshTotalSalary -- Refreshes total salary
UIEmployeeManageService:RefreshLocation -- Refreshes employee location information
UIEmployeeManageService:SelectEmp -- Selects employee
UIEmployeeManageService:StatSort -- Sorts employee list according to filter and sort criteria
UIEmployeeManageService:OnClickFilterBtn -- Processes filter button click
UIEmployeeManageService:OnClickTransferBtn -- Processes transfer button click
UIEmployeeManageService:UpdateDeployBtn -- Updates deployment button
UIEmployeeManageService:OnClickUpgradeBtn -- Processes upgrade button click
UIEmployeeManageService:RequestStoreMangeRedDot -- Requests store management red dot display
UIEmployeeManageService:OnClickSortBtn -- Processes sort button click
UIEmployeeManageService:HandleButtonClickEvent -- Handles close button click event
UIEmployeeManageService:HandleButtonClickEvent2 -- Handles filter button click event
UIEmployeeManageService:HandleButtonClickEvent3 -- Handles all filter button click event
UIEmployeeManageService:HandleButtonClickEvent4 -- Handles cook filter button click event
UIEmployeeManageService:HandleButtonClickEvent5 -- Handles serving filter button click event
UIEmployeeManageService:HandleButtonClickEvent6 -- Handles sort button click event
UIEmployeeManageService:HandleButtonClickEvent7 -- Handles upgrade button click event
UIEmployeeManageService:HandleButtonClickEvent8 -- Handles transfer button click event
UIEmployeeManageService:HandleButtonClickEvent9 -- Handles ascending sort button click event
UIEmployeeManageService:HandleButtonClickEvent10 -- Handles descending sort button click event
EmployeeMoveStatByLevelData:Load -- Loads employee movement stat data by level
EmployeeMoveStatByLevelData:ConvertToTable -- Converts data to table
EmployeeSkillService:OnBeginPlay -- Initializes employee skill service at game start
EmployeeSkillService:LoadData -- Loads employee skill data
EmployeeSkillService:GetData -- Returns skill data by skill ID
EmployeeSkillService:HasSkill -- Checks if employee has specific skill
EmployeeSkillService:CanUseSkill -- Checks if employee can use skill
EmployeeSkillService:ReturnSkillGradeValue -- Returns value according to skill grade
EmployeeSkillService:HasSkillOfType -- Checks if employee has skill of specific type
EmployeeSkillService:ReturnSkillGrade -- Returns skill grade
EmployeeSkillService:ReturnSkillName -- Returns skill name
EmployeeSkillService:ReturnSkillIcon -- Returns skill icon
EmployeeSkillService:ReturnSkillDesc -- Returns skill description
EmployeeSkillService:ReturnSkillSlotBg_Mini -- Returns mini skill slot background
EmployeeSkillService:ReturnSkillGradeColor -- Returns color according to skill grade
EmployeeSkillService:ReturnSkillSlotBg -- Returns skill slot background
EmployeeSkillService:DisplaySkillSlot -- Displays skill slot on screen
EmployeeSkillService:ReturnUpgradeSkillNumByEquipLevel -- Returns upgrade skill number according to equipment level
EmployeeSkillTypeData:Load -- Loads employee skill type data
EmployeeSkillTypeData:ConvertToTable -- Converts data to table
EmployeeUpgradeItemRenderer:OnBeginPlay -- Initializes upgrade item renderer at game start
EmployeeUpgradeItemRenderer:Init -- Initializes upgrade item slot with item ID
EmployeeUpgradeItemRenderer:OnClickItemAddBtn -- Increases selected item count when item add button is clicked
EmployeeUpgradeItemRenderer:OnClickItemSubBtn -- Decreases selected item count when item sub button is clicked
EmployeeUpgradeItemRenderer:RefreshSlectedCountText -- Refreshes selected item count text
EmployeeUpgradeItemRenderer:Init0 -- Initializes selected item slot (sets quantity to 0)
EmployeeUpgradeItemRenderer:SetPotionCount -- Sets potion quantity
EmployeeUpgradeItemRenderer:HandleButtonClickEvent -- Handles item slot click event
EmployeeUpgradeManager:OnBeginPlay -- Initializes employee upgrade manager at game start
EmployeeUpgradeManager:OnMapLeave -- Clears upgrade related data when leaving map
EmployeeUpgradeManager:SelectEmployee -- Selects employee to upgrade
EmployeeUpgradeManager:RequestUpgrade -- Requests employee upgrade
EmployeeUpgradeManager:Upgrade -- Upgrades employee abilities
EmployeeUpgradeManager:UpgradeClient -- Processes employee upgrade result on client
EmployeeUpgradeManager:ChangeWorkExpStatus -- Changes employee work experience status
EmployeeUpgradeManager:SetTimerForEmployeeWorkExp -- Sets employee work experience timer
EmployeeUpgradeManager:RemoveTimerOfEmployeeWorkExp -- Removes employee work experience timer
EmployeeUpgradeManager:UpgradeEffectProduction -- Generates upgrade effect
EmployeeUpgradeManager:CheckCanOverLimit -- Checks if over-limit is possible
EmployeeUpgradeManager:CheckOverLimitCost -- Checks over-limit cost
EmployeeUpgradeManager:SendClientOverLimitCostCheck -- Sends over-limit cost check result to client
EmployeeUpgradeManager:OverLimit -- Executes employee over-limit
EmployeeUpgradeManager:SendTryOverLimitResultToClient -- Sends over-limit attempt result to client
EmployeeUpgradeManager:RefundExtraExp -- Refunds excess experience
EmployeeUpgradeManager:SendTutorialEventTriggerAfterUpgrade -- Triggers tutorial event after upgrade
EmployeeUpgradeManager:ToastMsg -- Displays toast message
EmployeeUpgradeManager:HandlePlayerMoneyChangedEvent -- Handles player money change event
EmployeeUpgradeManager:HandlePlayerArcaneSymbolChangedEvent -- Handles player arcane symbol change event
EmployeeUpgradeService:OnBeginPlay -- Executed when employee upgrade service initializes
EmployeeUpgradeService:LoadData -- Loads employee upgrade related data
EmployeeUpgradeService:GetExpData -- Returns experience data according to level
EmployeeUpgradeService:ReturnLevelExpOfExpSum -- Calculates and returns level from total experience
EmployeeUpgradeService:ReturnNextLevelOfExpSum -- Calculates and returns next level from total experience
EmployeeUpgradeService:CalcNextUpgradeData -- Calculates next upgrade data
EmployeeUpgradeService:CalculateAutoLevel -- Calculates automatic level upgrade
EmployeeUpgradeService:HasRequiredExp -- Checks if required experience is owned
EmployeeUpgradeService:HasRequiredExpAdd -- Checks required experience when adding experience
EmployeeUpgradeService:HasRequiredExpSub -- Checks required experience when subtracting experience
EmployeeUpgradeService:ReturnOverLimitCost -- Returns over-limit cost
EmployeeUpgradeService:ReturnOverLimitJemItemId -- Returns over-limit gem item ID
EmployeeUpgradeService:ReturnExpFromPotionLevel -- Returns experience from potion level
EmployeeUpgradeService:RetrunExpItemCountTable -- Returns experience item count table
EmployeeUpgradeService:ReturnTransferRefundJemCost -- Returns gem cost to be refunded during transfer
EmployeeUpgradeService:MaxBtn -- Calculates items needed for max level upgrade
EmployeeUpgradeService:ReturnSkillNumByOverLimitLevel -- Returns skill number according to over-limit level
EmployeeUpgradeUIServcie:UIOpen -- Opens employee upgrade UI
EmployeeUpgradeUIServcie:UIClose -- Closes employee upgrade UI
EmployeeUpgradeUIServcie:ReturnStatOptionDescByStatLevel -- Returns option description according to stat level
EmployeeUpgradeUIServcie:ReturnItemCountByID -- Returns item count owned by player by item ID
EmployeeUpgradeUIServcie:CanRemoveSelectItem -- Checks if selected item can be removed
EmployeeUpgradeUIServcie:ReturnSelecteItemTotalExp -- Returns total experience of selected items
EmployeeUpgradeUIServcie:ReturnSelectedItemLv -- Returns level achievable with selected items
EmployeeUpgradeUIServcie:ReturnSelectedCountByItemID -- Returns selected count for specific item ID
EmployeeUpgradeUIServcie:CanSelectItem -- Checks if item can be selected
EmployeeUpgradeUIServcie:RequestSelectItems -- Requests item selection and updates level
EmployeeUpgradeUIServcie:RequestClearAllSelectItems -- Clears all selected items
UIEmployeeUpgrade:OnBeginPlay -- Initializes employee upgrade UI at game start
UIEmployeeUpgrade:Upgrade -- Executes employee upgrade
UIEmployeeUpgrade:SetStatCategory -- Sets employee stat category
UIEmployeeUpgrade:SetUIDetail -- Sets employee detail information UI
UIEmployeeUpgrade:SetUICurPreview -- Sets current stat preview UI
UIEmployeeUpgrade:SetUINextPreview -- Sets next stat preview UI
UIEmployeeUpgrade:SetUIExpSlider -- Sets experience slider UI
UIEmployeeUpgrade:SetUIItem -- Sets upgrade item UI
UIEmployeeUpgrade:SetUICategory -- Sets UI category (level up/over-limit)
UIEmployeeUpgrade:PlayLevelUpEffect -- Plays level up effect
UIEmployeeUpgrade:SetSkillProduce -- Sets skill UI according to ChuChu level
UIEmployeeUpgrade:RefreshAfterLevelUp -- Refreshes UI after level up
UIEmployeeUpgrade:OnClickLevelUpBtn -- Processes level up button click
UIEmployeeUpgrade:RefreshLevelUpBtn -- Refreshes level up button status
UIEmployeeUpgrade:OnClickResetBtn -- Processes reset button click
UIEmployeeUpgrade:RefreshResetBtn -- Refreshes reset button status
UIEmployeeUpgrade:ModifySelectItems -- Modifies selected item quantity
UIEmployeeUpgrade:SetSelcetItems -- Sets selected item list
UIEmployeeUpgrade:AllClearSelectItems -- Clears all selected items
UIEmployeeUpgrade:SetSelectedItemSlot -- Sets selected item slot UI
UIEmployeeUpgrade:OnClickOverLimitBtn -- Processes over-limit button click
UIEmployeeUpgrade:OverLimit -- Processes according to over-limit possibility
UIEmployeeUpgrade:DisplayOverLimitPanel -- Displays over-limit panel UI
UIEmployeeUpgrade:DisplayOverLimitCost -- Displays over-limit cost
UIEmployeeUpgrade:UpdateOverLimitCostFontColor -- Updates over-limit cost font color
UIEmployeeUpgrade:OverLimitDone -- Processes after over-limit completion
UIEmployeeUpgrade:OpenToolTipJemCostPanel -- Opens gem cost tooltip panel
UIEmployeeUpgrade:HandleButtonClickEvent -- Handles close button click event
UIEmployeeUpgrade:HandleButtonClickEvent2 -- Handles stat category button click event
UIEmployeeUpgrade:HandleButtonClickEvent3 -- Handles over-limit category button click event
UIEmployeeUpgrade:HandleButtonClickEvent5 -- Handles level up button click event
UIEmployeeUpgrade:HandleButtonClickEvent6 -- Handles reset button click event
UIEmployeeUpgrade:HandlePlayerInventoryItemChangedEvent -- Handles player inventory item change event
UIEmployeeUpgrade:HandleEmployeeDetailChangeEvent -- Handles employee detail change event
UIEmployeeUpgrade:HandleButtonClickEvent4 -- Handles over-limit button click event
UIEmployeeUpgrade:HandleButtonClickEvent7 -- Handles gem cost tooltip button click event
UIEmployeeUPgradeAuto:OnBeginPlay -- Initializes UI components at game start
UIEmployeeUPgradeAuto:UIEnable -- Sets UI enable/disable
UIEmployeeUPgradeAuto:OnClickAutoLevelMaxBtn -- Processes auto level max button click
UIEmployeeUPgradeAuto:OnClickAutoLevelAddBtn -- Processes auto level add button click
UIEmployeeUPgradeAuto:OnClickAutoLevelSubBtn -- Processes auto level sub button click
UIEmployeeUPgradeAuto:RefreshLevel -- Refreshes level
UIEmployeeUPgradeAuto:RefreshAutoPannel -- Refreshes auto panel
UIEmployeeUPgradeAuto:RefreshAutoBtn -- Refreshes auto button
UISkillOpenPopup:OnBeginPlay -- Initializes skill open popup UI components at game start
UISkillOpenPopup:Open -- Opens skill open popup and plays animation
UISkillOpenPopup:Refresh -- Refreshes skill information and displays on UI
UISkillOpenPopup:Close -- Closes skill open popup and opens next popup in queue
UISkillOpenPopup:OpenAnim -- Plays normal skill open animation
UISkillOpenPopup:Refresh_Overlimit -- Refreshes employee information for over-limit popup
UISkillOpenPopup:OpenAnim_OverLimit -- Plays over-limit skill open animation
UISkillOpenPopup:HandleButtonClickEvent -- Handles popup close button click event
KitchenAppData:Load -- Loads kitchen appliance data by ID and loads property values
KitchenAppManager:Init -- Performs initialization of kitchen appliance manager
KitchenAppManager:OnMapEnter -- Initializes when player enters lobby map
KitchenAppManager:OnMapLeave -- Initializes when player leaves lobby map
KitchenAppManager:InitUseApp -- Initializes kitchen appliance user information
KitchenAppManager:ReleaseApp -- Releases user assignment from specific kitchen appliance
KitchenAppManager:AssignApp -- Assigns user to specific kitchen appliance
KitchenAppManager:ReturnAvailableApp -- Returns index of available kitchen appliance sequentially
KitchenAppManager:ReturnRandomAvailableApp -- Returns random index among available kitchen appliances
KitchenAppService:OnBeginPlay -- Loads and initializes kitchen appliance data at game start
KitchenAppService:InsertKitAppOffsetDataSet -- Editor function to insert kitchen appliance position data into dataset
KitchenAppService:LoadData -- Loads data from kitchen appliance dataset and stores in internal table
KitchenAppService:GetData -- Queries and returns kitchen appliance data by ID
KitchenAppService:ReturnDisplayNum -- Calculates and returns number of displays available to player
KitchenAppService:ReturnDisplayRUID -- Returns burger sprite RUID to display on display
KitchenAppService:ReturnKitchenAppRUID -- Returns sprite RUID according to kitchen appliance usage status
KitchenAppService:UpdateDisplaySpriteByID -- Updates sprite of specific display slot
KitchenAppService:UpdateAllDisplaySprite -- Updates sprites of all displays
KitchenAppService:UpdateKitchenAppSpriteByID -- Updates sprite of specific kitchen appliance by ID
KitchenAppService:UpdateAllKitchenAppSprite -- Updates sprites of all kitchen appliances
KitchenAppService:UpdateKitchenAppPosByID -- Updates position of specific kitchen appliance by ID
KitchenAppService:UpdateAllEmployeeUseKitchenAppPos -- Updates kitchen appliance positions for all employees to use
KitchenAppService:VisibleKitAppsEntity -- Creates and sets kitchen appliance entities according to expansion stage
KitchenAppService:KitchenAppProductionByID -- Changes operation status of specific kitchen appliance
KitchenAppService:UpdateEmployeeUseKitchenAppPos -- Updates kitchen appliance positions for employee use
KitchenAppService:HandleButtonClickEditorEvent -- Handles button click event in editor to insert dataset
ChangedSelectedIngreCardsEvent:Init -- Initializes selected ingredient card change event
DrawBurgerUIService:DrawBurgerUI -- Draws burger UI and arranges ingredients
DrawBurgerUIService:ReturnIngreData -- Calculates UI layout information based on ingredient data
DrawBurgerUIService:TweenIngredientUI -- Creates ingredient UI with tween animation
DrawBurgerUIService:DrawIngredientUI -- Immediately draws ingredient UI
DrawBurgerUIService:HandleTextInputEndEditEvent -- Handles bun skin ID input to update burger UI
DrawBurgerUIService:HandleTextInputEndEditEvent2 -- Handles ingredient ID input to add ingredient
DrawBurgerUIService:HandleButtonClickEvent -- Button click handler that clears ingredient list
IngreCardSetLogic:SetIngreCard -- Adds ingredient card to selection list
IngreCardSetLogic:UnsetIngreCard -- Removes ingredient card from selection list
IngreCardSetLogic:GetCurrentSelectedTotalCount -- Returns total count of currently selected ingredient cards
IngreCardSetLogic:UnsetIngreCardAll -- Clears all selected ingredient cards
IngreCardSetLogic:GetIndexById -- Finds index of specific ID in table
UIEntityLogic_RecipeGroup:InitializeRecipeUI -- Initializes recipe UI and opens recipe book
BunData:Load -- Loads bun data and initializes top/bottom parts
BunDetailData:Load -- Loads bun detail information from CSV data
BunSkinData:Load -- Loads bun skin data and sets acquisition conditions
BunSkinDetailData:Load -- Loads bun skin detail information from CSV data
IngredientData:Load -- Loads ingredient information from CSV data
IngredientData:GetTasteScore -- Calculates ingredient taste score according to current stage and player status
IngredientData:GetCost -- Calculates ingredient cost according to current stage and player status
IngredientData:IsIngreBuffed -- Checks if ingredient is buffed by current stage or player effects
IngredientData:IsIngreStageBuffed -- Checks if ingredient is buffed by current stage
IngredientDataSetLogic:OnBeginPlay -- Loads dataset at game start
IngredientDataSetLogic:LoadDataSet -- Loads ingredient, bun, and bun skin data from CSV
IngredientDataSetLogic:ReturnPropertyIconRUIDByType -- Returns icon RUID according to ingredient property type
IngredientDataSetLogic:ReturnDishRUIDByGrade -- Returns dish RUID according to grade
IngredientDataSetLogic:ReturnRandomIngredientOfGrade -- Returns random ingredient matching specific grade and tag conditions
IngredientDataSetLogic:ReturnRandomBunOfGrade -- Returns random bun of specific grade
IngredientDataSetLogic:ReturnIsTagMatch -- Checks if ingredient matches required tag
IngredientDataSetLogic:ReturnExclusiveIngredientOfTag -- Randomly returns ingredient that belongs exclusively to specific tag
IngredientDataSetLogic:ReturnIsTagExclusive -- Checks if ingredient belongs exclusively to specific tag
IngredientDataSetLogic:GetIngredientData -- Gets ingredient data by ID
IngredientDataSetLogic:GetBunData -- Gets bun data by ID
IngredientDataSetLogic:GetBunDetailData -- Gets bun detail data by ID and part key
IngredientDataSetLogic:GetBunSkinData -- Gets bun skin data by ID
IngredientDataSetLogic:GetBunSkinDetailData -- Gets bun skin detail data by ID and part key
IngredientDataSetLogic:GetBunSkinBonusRate -- Calculates bonus rate according to number of bun skins collected by player
IngredientDataSetLogic:GetBalanceThreshold -- Calculates player's balance threshold
IngredientDataSetLogic:GetSpicyThreshold -- Calculates player's spicy threshold
IngredientDataSetLogic:RequestSetIngreNameKeywords -- Requests server to set ingredient name keywords
IngredientDataSetLogic:SetIngreNameKeywords -- Sets player's ingredient name keywords
RecipeComboData:Load -- Loads recipe combo data from CSV and sets required count by tag
RecipeData:ConvertToTable -- Converts recipe data to table
RecipeData:SetFromTable -- Sets recipe data from table data
RecipeData:GetIsBunSkinned -- Checks if bun has skin applied
RecipeData:ConvertToDBTable -- Converts to database table
RecipeData:SerFromDBTable_Ver1 -- Deserializes data from database table version 1
RecipeDataSetLogic:OnBeginPlay -- Initializes recipe dataset at game start
RecipeDataSetLogic:LoadDataSet -- Loads trend data
RecipeDataSetLogic:IsRecipeTrend -- Checks if recipe is current trend
RecipeDataSetLogic:IsRecipeIncludeIngredient -- Checks if recipe includes specific ingredient
RecipeDataSetLogic:GetTrendData -- Returns trend data by trend ID
RecipeDataSetLogic:ReturnRerollCost -- Returns cost according to reroll count
RecipeDataSetLogic:ReturnBestTasteScore -- Returns highest taste score among recipes of specific tag
RecipeDataSetLogic:GetRecipeCost -- Calculates and returns recipe cost
RecipeDataSetLogic:ReturnRandomRecipeNameCheckProhibited -- Returns random recipe name after checking prohibited words
RecipeDataSetLogic:RequestSetRandomRecipeName -- Requests random recipe name setting
RecipeDataSetLogic:RequestSetBurgerNameInputText -- Sets burger name input text
RecipeIngreDrawData:DataToTable -- Converts recipe ingredient draw data to table format
RecipeIngreDrawData:TableToData -- Converts table data to recipe ingredient draw data
RecipeIngreDrawData:Init -- Initializes recipe ingredient draw data
RecipeIngreDrawEnum:EncodeIngreList -- Encodes ingredient list to JSON string
RecipeIngreDrawEnum:DecodeIngreList -- Decodes JSON string to ingredient list
RecipeTagData:Load -- Loads recipe tag data from CSV and sets color information
RecipeTagDataSetLogic:OnBeginPlay -- Loads dataset at game start
RecipeTagDataSetLogic:LoadDataSet -- Loads recipe tag dataset
RecipeTagDataSetLogic:ReturnMainTypeOfIngres -- Returns main type of ingredients
RecipeTagDataSetLogic:PopRecipeTypeIcon -- Displays recipe type icon as popup
RecipeTagDataSetLogic:ReturnRecipeTagSortIndex -- Returns sort index of recipe tag
RecipeTagDataSetLogic:IsRecipeComboActiveForRecipe -- Checks if recipe combo is active for recipe
RecipeTagDataSetLogic:IsRecipeComboActiveForTag -- Checks if recipe combo is active for tag
RecipeTagDataSetLogic:GetRecipeTagData -- Gets recipe tag data by tag
TasteGradeData:Load -- Loads taste grade data from CSV
TasteGradeDataSetLogic:OnBeginPlay -- Loads dataset at game start
TasteGradeDataSetLogic:LoadDataSet -- Loads taste grade dataset
TasteGradeDataSetLogic:ReturnGradeDataByScore -- Returns grade data according to score
TasteGradeDataSetLogic:ReturnAttractiveScoreByScore -- Returns attractiveness score according to score
TasteGradeDataSetLogic:GetTasteGradeData -- Gets taste grade data by grade index
TasteGradeDataSetLogic:GetFinalComboBonus -- Calculates player's final combo bonus
TasteGradeDataSetLogic:GetFinalBalanceBonus -- Calculates player's final balance bonus
TrendData:Load -- Loads trend data from CSV
UIIngreDishIcon:SetItem -- Sets ingredient item information
UIIngreDishIcon:OnBeginPlay -- Initializes UI elements at game start
UIIngreDishIcon:OnClickItem -- Called when item is clicked
UIRecipeBook:Open -- Opens recipe book UI
UIRecipeBook:Close -- Closes recipe book UI
UIRecipeBook:Refresh -- Refreshes recipe book UI
UIRecipeBook:OpenUIIngreCardSetting -- Opens ingredient card setting UI
UIRecipeBook:OnClickAutoSetBtn -- Called when auto set button is clicked
UIRecipeBook:ClearFunction -- Clears recipe setting
UIRecipeBook:RefreshComboInfo -- Refreshes recipe combo information
UIRecipeBook:OnClickResetBtn -- Called when reset button is clicked
UIRecipeBook:OnBeginPlay -- Connects button events at game start
UIRecipeBook:RefreshReplaceBtns -- Refreshes replace buttons
UIRecipeBook:HandleButtonClickEvent -- Handles close button click event
UIRecipeBook:HandleButtonClickEvent2 -- Handles recipe group open button click event
UIRecipeBook:HandleButtonClickEvent3 -- Handles ingredient card setting move button click event
UIRecipeBook:HandleButtonClickEvent4 -- Handles delete all button click event
UIRecipeBook:HandleButtonClickEvent5 -- Handles auto set button click event
UIRecipeBook:HandleButtonClickEvent6 -- Handles recipe group open button click event
UIRecipeBook:HandleButtonClickEvent7 -- Handles recipe combo info open button click event
UIRecipeBook:HandleButtonClickEvent8 -- Handles menu combo open condition tooltip button click event
UIRecipeBook:HandleButtonClickEvent9 -- Handles reset button click event
UIRecipeBook:HandleButtonClickEvent10 -- Handles recipe list open button click event
UIRecipeBurgerSlot:Init -- Initializes recipe burger slot UI elements
UIRecipeBurgerSlot:Refresh -- Refreshes recipe burger slot
UIRecipeBurgerSlot:OnClickSlotRecipeBook -- Called when slot is clicked in recipe book
UIRecipeBurgerSlot:OnClickSlotRecipeList -- Called when slot is clicked in recipe list
UIRecipeBurgerSlot:OnClickLockedSlot -- Called when locked slot is clicked
UIRecipeBurgerSlot:SetSelected -- Sets slot selection state
UIRecipeCountBar:OnBeginPlay -- Initializes recipe count bar at game start
UIRecipeCountBar:Refresh -- Refreshes recipe count bar
UIRecipeSortButton:HandleButtonClickEvent -- Handles recipe sort button click event
UIRecipeTag:Init -- Initializes recipe tag UI elements
UIRecipeTag:Refresh -- Refreshes recipe tag information
UIRecipeTag:Clear -- Clears recipe tag
UIBunDetail:Init -- Initializes bun detail UI elements
UIBunDetail:Refresh -- Refreshes detail information based on bun data
UIBunList:Open -- Opens bun selection UI
UIBunList:Close -- Closes bun selection UI
UIBunList:RefreshList -- Refreshes bun list
UIBunList:RefreshDetail -- Refreshes detailed information of selected bun
UIBunList:OnSetFunction -- Sets selected bun
UIBunList:HandleButtonClickEvent -- Handles close button click event
UIBunList:HandleButtonClickEvent2 -- Handles bun set button click event
UIBunList:HandleButtonClickEvent3 -- Handles close by background click event
UIBunSelectBtn:Init -- Initializes bun select button UI elements
UIBunSelectBtn:Refresh -- Refreshes bun select button state and information
UIBunSelectBtn:OnSelectFunction -- Called when bun is selected
UIBunSelectBtn:HandleButtonClickEvent -- Handles bun select button click event
UIIngreAutoSetSelectArea:Open -- Opens ingredient auto set select area
UIIngreAutoSetSelectArea:Close -- Closes ingredient auto set select area
UIIngreAutoSetSelectBtn:OnBeginPlay -- Initializes ingredient auto set button and connects click event
UIIngreCard:Init -- Initializes ingredient card UI elements and connects click event
UIIngreCard:Refresh -- Refreshes ingredient card information
UIIngreCard:HandleChangedSelectedIngreCardsEvent -- Handles selected ingredient card change event
UIIngreCardSetting:OnBeginPlay -- Initializes ingredient card setting UI and connects events
UIIngreCardSetting:Open -- Opens ingredient card setting UI and performs initial setup
UIIngreCardSetting:Close -- Closes ingredient card setting UI
UIIngreCardSetting:RequestMoveToRecipeMaking -- Requests move to recipe making
UIIngreCardSetting:RefreshIngreCardList -- Refreshes ingredient card list according to filter
UIIngreCardSetting:RefreshIngreSlotList -- Refreshes selected ingredient slot list
UIIngreCardSetting:DeselectCardAll -- Deselects all cards
UIIngreCardSetting:RefreshBunSetSlot -- Refreshes bun setting slot
UIIngreCardSetting:RefreshBalanceBar -- Refreshes balance bar
UIIngreCardSetting:SetIngreGachaRedDot -- Sets red dot indicator for ingredient gacha button
UIIngreCardSetting:OnClickFilterBtn -- Called when filter button is clicked
UIIngreCardSetting:OnClickAutoSetBtn -- Called when auto set button is clicked
UIIngreCardSetting:ReturnAutoSetIngreCardList -- Returns ingredient card list to auto set according to tag
UIIngreCardSetting:IsNeedToExclusive -- Determines if exclusive ingredient is needed
UIIngreCardSetting:SetBunRedDot -- Sets red dot indicator for bun select button
UIIngreCardSetting:AutoSetIngreCard -- Automatically sets ingredient cards according to tag
UIIngreCardSetting:CheckTutorial -- Checks tutorial conditions
UIIngreCardSetting:SetSort -- Sets sort method
UIIngreCardSetting:SetFilter -- Sets filter
UIIngreCardSetting:RefreshSideMenuInfo -- Refreshes side menu information
UIIngreCardSetting:HandleButtonClickEvent -- Handles recipe making button click event
UIIngreCardSetting:HandleButtonClickEvent2 -- Handles close button click event
UIIngreCardSetting:HandleButtonClickEvent3 -- Handles deselect all button click event
UIIngreCardSetting:HandleButtonClickEvent4 -- Handles auto set button click event
UIIngreCardSetting:HandleButtonClickEvent5 -- Handles bun select button click event
UIIngreCardSetting:HandleButtonClickEvent6 -- Handles ingredient gacha button click event
UIIngreCardSetting:HandleButtonClickEvent7 -- Handles filter button click event
UIIngreCardSetting:HandleButtonClickEvent8 -- Handles sort button click event
UIIngreCardSetting:HandleButtonClickEvent9 -- Handles side menu info button click event
UIIngreCardSetting:HandleChangedSelectedIngreCardsEvent -- Handles selected ingredient card change event
UIIngredientProperty:Refresh -- Refreshes ingredient property information
UIIngredientProperty:Init -- Initializes ingredient property UI elements
UIIngreFilterSelectArea:Open -- Opens ingredient filter select area
UIIngreFilterSelectArea:Close -- Closes ingredient filter select area
UIIngreFilterSelectBtn:OnBeginPlay -- Initializes ingredient filter select button and connects click event
UIIngreSetSlot:Init -- Initializes ingredient setting slot UI elements
UIIngreSetSlot:Refresh -- Refreshes ingredient setting slot state and information
UIIngreSetSlot:EmptyButtonFunction -- Called when empty slot is clicked
UIIngreSetSlot:FilledButtonFunction -- Called when slot with ingredient is clicked
UIIngreSetSlot:LockedButtonFunction -- Called when locked slot is clicked
UIIngreSetSlot:HandleChangedSelectedIngreCardsEvent -- Handles selected ingredient card change event
UIRecipeComboInfo:Open -- Opens recipe combo information window
UIRecipeComboInfo:Close -- Closes recipe combo information window
UIRecipeComboInfo:Refresh -- Refreshes recipe combo information list
UIRecipeComboInfo:HandleButtonClickEvent -- Handles close button click event
UIRecipeComboInfo:HandleButtonClickEvent2 -- Handles close by background click event
UIRecipeComboInfoSlot:Init -- Initializes recipe combo information slot UI elements
UIRecipeComboInfoSlot:Refresh -- Refreshes recipe combo information slot
UIRecipeComboTagSlot:Refresh -- Refreshes recipe combo tag slot
UIRecipeList:OnBeginPlay -- Initializes recipe list at game start
UIRecipeList:RefreshDetail -- Refreshes recipe detail information
UIRecipeList:RefreshListByKey -- Refreshes recipe list according to key
UIRecipeList:FilterRecipes -- Filters recipes according to filter conditions
UIRecipeList:SortRecipes -- Sorts recipes according to sort key
UIRecipeListDetail:Init -- Initializes recipe list detail information UI elements
UIRecipeListDetail:Refresh -- Refreshes recipe detail information
UIRecipeListDetail:InitEntitiesForEmpty -- Initializes entities according to empty state
UIRecipeListDetail:RefreshPriceInfoText -- Refreshes price information text
UIRecipeListHolder:OnBeginPlay -- Initializes recipe list holder at game start
UIRecipeListHolder:Open -- Opens recipe list holder
UIRecipeListHolder:Close -- Closes recipe list holder
UIRecipeListHolder:RefreshListAndDetail -- Refreshes recipe list and detail information
UIRecipeListHolder:RefreshRecipeCountBar -- Refreshes recipe count bar
UIRecipeListHolder:SetEntitiesEnableByKey -- Sets entity enable state according to key
UIRecipeListHolder:RefreshSetButton -- Refreshes set button
UIRecipeListHolder:SetButtonDim -- Sets button dim state
UIRecipeSetButtonArea:OnBeginPlay -- Initializes recipe set button area at game start
UIRecipeSetButtonArea:OnClickSetButton -- Called when recipe set button is clicked
UIRecipeSetButtonArea:OnClickClearButton -- Called when recipe clear button is clicked
UIRecipeSetButtonArea:MoveToSetIngrePage -- Moves to ingredient setting page
UIRecipeSetButtonArea:OnClickSetVIPOrderButton -- Called when VIP order set button is clicked
UIRecipeSetButtonArea:OnClickSetTrialButton -- Called when trial set button is clicked
UIRecipeSetButtonArea:RefreshSetButton -- Refreshes recipe set/clear button state
UIRecipeSetButtonArea:RefreshMoveToMakeBtnDim -- Refreshes move to making page button dim state
UIRecipeSetButtonArea:RefreshVIPOrderSelectBtnDim -- Refreshes VIP order select button dim state
UIRecipeSetButtonArea:OnClickDeleteButton -- Called when recipe delete button is clicked
UIRecipeSetButtonArea:RefreshDeleteBtnDim -- Refreshes delete button dim state
UIRecipeSetTopBar:Refresh -- Refreshes recipe set top bar according to parameters
UIRecipeSetTopBar:SetTrialResultGuess -- Sets trial result guess
UIRecipeSetTopBar:OnBeginPlay -- Initializes recipe set top bar at game start
UIRecipeSetTopBar:SetEnableSortList -- Sets enable state of sort list
UIRecipeSetTopBar:RefreshVIPOrderRequirements -- Refreshes VIP order requirements
UIBunSkinListSlot:Init -- Initializes bun skin list slot UI elements
UIBunSkinListSlot:Refresh -- Refreshes bun skin slot
UIBunSkinListSlot:EnableSelected -- Sets selection state
UIBunSkinListSlot:HandleButtonClickEvent -- Handles button click event
UIRecipeBunSkinDetail:Init -- Initializes bun skin detail information UI elements
UIRecipeBunSkinDetail:Refresh -- Refreshes bun skin detail information
UIRecipeBunSkinList:OnBeginPlay -- Initializes bun skin list at game start
UIRecipeBunSkinList:Open -- Opens bun skin list
UIRecipeBunSkinList:Close -- Closes bun skin list
UIRecipeBunSkinList:StartTween -- Starts open/close tween animation
UIRecipeBunSkinList:Refresh -- Refreshes bun skin list
UIRecipeBunSkinList:RefreshList -- Refreshes bun skin list items
UIRecipeBunSkinList:OnClickSlot -- Called when bun skin slot is clicked
UIRecipeBunSkinList:OnClickSkipBtn -- Called when skip button is clicked
UIRecipeBunSkinList:OnClickUseBtn -- Called when use button is clicked
UIRecipeBunSkinList:BurgerMoveOut -- Moves burger outward
UIRecipeBunSkinList:BurgerMoveIn -- Moves burger inward
UIRecipeBunSkinList:OnSelectBunSkinId -- Called when bun skin ID is selected
UIRecipeBunSkinList:HandleButtonClickEvent -- Handles button click event
UIRecipeChoiceBtn:Init -- Initializes recipe choice button UI elements
UIRecipeChoiceBtn:Refresh -- Refreshes choice button based on ingredient information
UIRecipeChoiceBtn:Choice -- Selects ingredient
UIRecipeEmployeeDetail:Init -- Initializes employee detail information UI elements
UIRecipeEmployeeDetail:Refresh -- Refreshes employee detail information
UIRecipeEmployeeList:OnBeginPlay -- Initializes employee list UI at game start
UIRecipeEmployeeList:Close -- Closes employee list UI
UIRecipeEmployeeList:StartTween -- Starts employee list UI tween animation
UIRecipeEmployeeList:Refresh -- Refreshes employee list
UIRecipeEmployeeList:Open -- Opens employee list UI
UIRecipeEmployeeList:RefreshList -- Refreshes and sorts employee list
UIRecipeEmployeeList:RefreshDetail -- Refreshes detailed information of selected employee
UIRecipeEmployeeList:OnClickSkipBtn -- Skips employee selection
UIRecipeEmployeeList:OnClickUseSkillBtn -- Clicks employee skill use button
UIRecipeEmployeeList:ReturnChatBalloonType -- Returns employee's chat balloon type
UIRecipeEmployeeList:SetEmployeeSlot -- Sets employee slot state
UIRecipeEmployeeList:OnClickChatBalloon -- Clicks chat balloon
UIRecipeEmployeeList:HandleButtonClickEvent -- Handles skip button click event
UIRecipeEmployeeList:HandleButtonClickEvent2 -- Handles skill use button click event
UIRecipeEmployeeList:HandleButtonClickEvent3 -- Handles another skip button click event
UIRecipeEmployeeList:HandleButtonClickEvent4 -- Handles chat balloon click event
UIRecipeMaking:Open -- Opens recipe making UI
UIRecipeMaking:Close -- Closes recipe making UI
UIRecipeMaking:RequestEndRecipeMaking -- Requests recipe making end
UIRecipeMaking:SetChoicePairs -- Sets selectable ingredient pairs
UIRecipeMaking:SetChoiceButtons -- Sets choice buttons
UIRecipeMaking:ChoiceFunction -- Selects ingredient
UIRecipeMaking:CompleteMakingFunction -- Completes recipe making
UIRecipeMaking:SpawnIngredient -- Spawns ingredient and adds to burger
UIRecipeMaking:RefreshCountText -- Refreshes remaining choice count text
UIRecipeMaking:RefreshBalanceBar -- Refreshes balance bar
UIRecipeMaking:RefreshSpicinessBar -- Refreshes spiciness bar
UIRecipeMaking:CheckBalanceCombo -- Checks and processes balance combo
UIRecipeMaking:RefreshScoreBar -- Refreshes score bar
UIRecipeMaking:RerollChoicePairs -- Rerolls choice pairs
UIRecipeMaking:StartRecipeMaking -- Starts recipe making
UIRecipeMaking:RefreshRerollButton -- Refreshes reroll button
UIRecipeMaking:SetBalanceZone -- Sets balance zone
UIRecipeMaking:RefreshSideMenuInfo -- Refreshes side menu information
UIRecipeMaking:HandleButtonClickEvent -- Handles recipe making end button click event
UIRecipeMaking:HandleButtonClickEvent2 -- Handles recipe making complete button click event
UIRecipeMaking:HandleButtonClickEvent3 -- Handles reroll button click event
UIRecipeMaking:HandlePlayerArcaneSymbolChangedEvent -- Handles player arcane symbol change event
UIRecipeMaking:HandleButtonClickEvent4 -- Handles side menu info button click event
UIRecipeResult:OnBeginPlay -- Optimizes and loads burger completion effect resources at game start
UIRecipeResult:Init -- Initializes all elements of recipe result UI
UIRecipeResult:Open -- Opens recipe result UI
UIRecipeResult:MakeTweenNumTextRising -- Creates tween animation for rising number text
UIRecipeResult:RequestRefreshTasteScoreBar -- Requests taste score bar refresh
UIRecipeResult:RequestRefreshBalanceScoreBar -- Requests balance score bar refresh
UIRecipeResult:SetBalanceResult -- Sets balance result and returns success status
UIRecipeResult:RequestRefreshBalanceBonus -- Requests balance bonus refresh
UIRecipeResult:RequestRefreshSpicinessScoreBar -- Requests spiciness score bar refresh
UIRecipeResult:SetSpicyResult -- Sets spicy result
UIRecipeResult:RequestRefreshPriceBar -- Requests price bar refresh
UIRecipeResult:RequestTagIconPopped -- Requests tag icon popup
UIRecipeResult:ChangeRenderIndex -- Changes render index
UIRecipeResult:RenderFunction -- Displays results according to render step
UIRecipeResult:SetInfoText -- Sets and displays info text
UIRecipeResult:SetSelectedEmployeeInfo -- Sets selected employee information
UIRecipeResult:SetSkillInfo -- Sets and displays skill information
UIRecipeResult:UseSkill -- Uses employee skill
UIRecipeResult:SkipResultRender -- Skips result rendering
UIRecipeResult:SetFinalScore -- Sets final score
UIRecipeResult:ReturnValueCapApplied -- Returns value with cap applied
UIRecipeResult:HandleButtonClickEvent -- Handles skip button click event
UITrendInfo:Init -- Initializes trend information UI elements
UITrendInfo:Refresh -- Refreshes trend information
UITrendInfo:RefreshForRecipeList -- Refreshes trend information for recipe list
UITrendInfoBar:Refresh -- Refreshes trend information bar
UIVIPOrderNewSeasonPopup:Open -- Opens new season popup and displays season information
UIVIPOrderNewSeasonPopup:Init -- Initializes UI components and sets references
UIVIPOrderNewSeasonPopup:Refresh -- Refreshes current season's main tag and period information
UIVIPOrderNewSeasonPopup:Close -- Closes new season popup and restores related UI state
UIVIPOrderNewSeasonPopup:HandleButtonClickEvent -- Handler that closes popup when popup close button is clicked
UIVIPOrderPanel:Open -- Opens VIP order panel and updates tutorial and status
UIVIPOrderPanel:Refresh -- Refreshes panel's season information and order list
UIVIPOrderPanel:RefreshOrderList -- Updates each order slot's data and applies animation
UIVIPOrderPanel:OnBeginPlay -- Creates and initializes VIP order slots at game start
UIVIPOrderPanel:Close -- Closes VIP order panel and cleans up slots
UIVIPOrderPanel:RefreshCountBar -- Displays completed and maximum order count and updates status
UIVIPOrderPanel:CheckOpenSeasonPopup -- Checks if new season popup should be displayed on first UI entry
UIVIPOrderPanel:CheckOpenAfterCloseSeason -- Checks and sets UI entry status after season end
UIVIPOrderPanel:EndWaitRefresh -- Ends wait state and updates slots status
UIVIPOrderPanel:StartWaitRefresh -- Starts wait state and notifies slots of wait state
UIVIPOrderPanel:ClearAllTweenerAndTimer -- Clears all slot animations and timers
UIVIPOrderPanel:HandleButtonClickEvent -- Handles VIP order panel open button click
UIVIPOrderPanel:HandleButtonClickEvent2 -- Handles VIP order panel close button click
UIVIPOrderPanel:HandleButtonClickEvent3 -- Handles VIP order upgrade panel open button click
UIVIPOrderPanel:HandleButtonClickEvent4 -- Handles VIP order panel reopen button click
UIVIPOrderPreview:Init -- Initializes VIP order preview UI components and connects events
UIVIPOrderPreview:Refresh -- Refreshes order list and updates selected slot information
UIVIPOrderPreview:OpenOrderList -- Opens order list or closes if already open
UIVIPOrderPreview:CloseOrderList -- Closes order list
UIVIPOrderPreview:RefreshOrderList -- Refreshes each order slot's data and displays selection state
UIVIPOrderPreview:RefreshNowRequirements -- Refreshes current selected order requirements and checks condition fulfillment
UIVIPOrderPreview:OnPinOrder -- Pins specific order and updates preview state
UIVIPOrderPreviewSlot:Init -- Initializes preview slot UI components
UIVIPOrderPreviewSlot:Refresh -- Refreshes slot according to order index and pin state
UIVIPOrderRecipeRequirement:Init -- Initializes recipe requirement UI components
UIVIPOrderRecipeRequirement:Refresh -- Displays appropriate UI according to requirement type and sets data
UIVIPOrderScoreExtraReward:Open -- Opens extra reward popup and starts animation according to reward grade
UIVIPOrderScoreExtraReward:StartRender -- Starts reward popup fade in animation and score drop effect
UIVIPOrderScoreExtraReward:EndRender -- Performs reward popup fade out animation and cleanup
UIVIPOrderScoreExtraReward:OnBeginPlay -- Initializes popup to inactive state at game start
UIVIPOrderSeasonInfo:OnBeginPlay -- Sets season information UI initialization state and reward status
UIVIPOrderSeasonInfo:Refresh -- Refreshes season information, main tag, and reward slider
UIVIPOrderSeasonInfo:RefreshLeftDayText -- Updates season remaining days text
UIVIPOrderSeasonInfo:RefreshRewardSlider -- Updates reward slider and reward button status according to season score
UIVIPOrderSeasonInfo:OnClickRewardBtn -- Handles reward acquisition or tooltip display when reward button is clicked
UIVIPOrderSeasonInfo:Init -- Creates reward buttons and tooltips and connects events
UIVIPOrderSeasonInfo:RefreshRewardTooltip -- Refreshes reward tooltip items and quantities with bonus applied
UIVIPOrderSeasonInfo:TweenRewardSlider -- Executes reward slider animation according to season score increase
UIVIPOrderSeasonInfo:SetRewardEntity -- Sets button activation and image according to reward entity state
UIVIPOrderSeasonInfo:SetNotToRefreshSlider -- Sets slider refresh prohibition state
UIVIPOrderSeasonInfo:RefreshRewardInfoTooltip -- Refreshes reward info tooltip collection and strategy bonus information
UIVIPOrderSlot:Init -- Initializes all UI components of VIP order slot and connects events
UIVIPOrderSlot:Refresh -- Refreshes UI by order type according to slot data
UIVIPOrderSlot:RefreshComplete -- Sets UI for completed order state
UIVIPOrderSlot:RefreshRecipe -- Displays recipe order requirements on UI
UIVIPOrderSlot:RefreshIngre -- Displays ingredient order information and owned quantity and checks fulfillment
UIVIPOrderSlot:RefreshRerollBtn -- Updates reroll button cost and activation status
UIVIPOrderSlot:RefreshWaiting -- Displays reset cost and remaining days for waiting status order
UIVIPOrderSlot:RefreshReward -- Displays reward items to receive upon order completion on UI
UIVIPOrderSlot:MoveOut -- Executes slot disappearing animation and prepares for replacement with new data
UIVIPOrderSlot:MoveIn -- Executes slot appearing animation with new order data
UIVIPOrderSlot:SetSlotData -- Sets slot data and performs appropriate processing according to wait state
UIVIPOrderSlot:ClearEntities -- Initializes slot entities visual state
UIVIPOrderSlot:IsSameData -- Compares two slot data to check if they are the same order by UniqueId
UIVIPOrderSlot:OnChangedIsWaiting -- Refreshes slot with temporarily saved data when wait state changes
UIVIPOrderSlot:RequestRefresh -- Selects appropriate refresh method according to slot state
UIVIPOrderSlot:PopAfterWait -- Saves temporary score for score popup after waiting
UIVIPOrderSlot:ClearSlotMovement -- Clears all ongoing animations and timers and initializes state
UIVIPOrderSlot:HandlePlayerArcaneSymbolChangedEvent -- Refreshes slot data when player arcane symbol changes
VIPOrderDataSetLogic:OnBeginPlay -- Initializes VIP order related datasets at game start
VIPOrderDataSetLogic:LoadDataSet -- Reads season reward data from CSV files and stores in table
VIPOrderDataSetLogic:ReturnIngreType -- Returns ingredient type with weight applied based on season main tag
VIPOrderDataSetLogic:ReturnRecipeOrderData -- Creates and returns recipe order data suitable for player status
VIPOrderDataSetLogic:ReturnIngreOrderData -- Creates and returns ingredient order data suitable for player status
VIPOrderDataSetLogic:IsRecipeCorrectForOrder -- Verifies if submitted recipe meets all VIP order requirements
VIPOrderDataSetLogic:ReturnSeasonEndElapsedByStartElapsed -- Calculates season end time based on season start time
VIPOrderDataSetLogic:RefreshSeasonInfoLeftDayText -- Calculates remaining days until season end based on current time and updates UI
VIPOrderDataSetLogic:ReturnResetOrderCost -- Calculates arcane symbol cost required for order reset proportional to remaining days
VIPOrderDataSetLogic:RefreshRequirementSlotIcon -- Sets appropriate icon and status display according to requirement type
VIPOrderDataSetLogic:ReturnRequirementDatasTableForUI -- Extracts and returns UI display requirement list from slot data
VIPOrderDataSetLogic:IsIngreRelatedToOrder -- Checks if specific ingredient is included in recipe order requirements for that slot
VIPOrderDataSetLogic:ReturnVIPOrderReward -- Calculates reward items and quantities based on order data and player status
VIPOrderDataSetLogic:ReturnVIPOrderRerollCost -- Calculates reroll cost that increases according to player's reroll count
VIPOrderDataSetLogic:ReturnFixedStartMonthByStartElapsed -- Returns fixed start month for corresponding season based on start time
VIPOrderRecipeRewardData:Load -- Loads and parses recipe reward information from CSV data
VIPOrderRecipeRewardData:ReturnRewardGradeByTasteGrade -- Finds and returns reward grade corresponding to taste grade
VIPOrderRequirementData:Load -- Loads and parses VIP order requirement information from CSV data
VIPOrderRequirementData:ReturnRandomIngreGrade -- Randomly selects and returns one from available ingredient grades
VIPOrderResultRenderLogic:DropSeasonScores -- Executes visual score dropping animation
VIPOrderResultRenderLogic:ClearScoreEntities -- Removes all created score entities and initializes counter
VIPOrderResultRenderLogic:OnBeginPlay -- Initializes score rendering logic
VIPOrderResultRenderLogic:RequestStartPopAfterWaiting -- Requests to start score popup after waiting
VIPOrderResultRenderLogic:RequestStartExtraRewardAfterWaiting -- Requests to start extra reward after waiting
VIPOrderResultRenderLogic:RequestOpenExtraReward -- Opens popup to display if there are saved extra rewards
VIPOrderSeasonRewardData:Load -- Loads season reward data based on management level and CSV row data
CustomerAIScript:Create -- Initializes customer AI and sets movement script
CustomerAIScript:StateManager -- Manages customer state and handles actions according to each state
CustomerAIScript:BEFOREENTER -- Handles customer waiting state before entering store
CustomerAIScript:ENTER -- Handles customer entering store and moving to waiting seat state
CustomerAIScript:ORDER -- Handles customer waiting for order and creating order UI state
CustomerAIScript:CHECKOUT -- Handles customer completing payment and processing before leaving store state
CustomerAIScript:EXITTEMP -- Handles customer moving to temporary exit point state
CustomerAIScript:EXIT -- Handles customer moving to final exit and completely leaving store state
CustomerAIScript:DESTROY -- Handles cleaning up and removing customer entity state
CustomerAIScript:SetOrder -- Sets that customer has completed order
CustomerAIScript:SetPurchase -- Sets that customer has completed payment and removes from waiting queue
CustomerAIScript:Report -- Analyzes reason for customer leaving store and generates report
CustomerAIScript:ResetEntity -- Initializes customer entity and returns to object pool
CustomerAIScript:OnBeginPlay -- Initializes burger component when customer entity is created
CustomerAIScript:UpdateWaitSpotId -- Updates customer waiting seat position information
CustomerAIScript:ChangeStateToORDERByEmployeeDestroyed -- Changes customer state to order waiting when employee is destroyed
CustomerAIScript:HandleEmployeeMoveChangedEvent -- Handles employee movement state change event
CustomerAvatarData:Load -- Loads customer avatar information from CSV data and collects resource IDs
CustomerAvatarService:OnBeginPlay -- Loads customer avatar dataset at service start
CustomerAvatarService:LoadDataSet -- Loads customer avatar data from CSV and stores in memory
CustomerAvatarService:SetRandomCostume -- Sets random customer costume suitable for current stage
CustomerAvatarService:GetCostumerAvatarData -- Returns customer avatar data corresponding to index
CustomerAvatarService:SetRandomEmotion -- Sets random emotion expression to customer
CustomerAvatarService:ResetCustomerAvatarResources -- Preloads customer avatar resources suitable for current stage
CustomerAvatarService:GetIndex -- Calculates avatar index range corresponding to current stage
CustomerAvatarService:InsertRUIDToPreloadData -- Adds valid resource ID to preload list
CustomerManager:OnBeginPlay -- Initializes customer manager on server
CustomerManager:Init -- Initializes customer manager on client and creates customer pool
CustomerManager:SetCustomerSpawnDelay -- Calculates and sets customer spawn delay
CustomerManager:CreateCustomer -- Gets customer entity from pool and creates
CustomerManager:RefreshSpawnTable -- Refreshes customer spawn table and sets each customer information
CustomerManager:SyncCustomerInfoTable -- Synchronizes customer spawn information sent from server to client
CustomerManager:SetRandomOrderTag -- Determines customer order tag according to trends and menu situation
CustomerManager:SetOrderRecipeId -- Selects and returns recipe ID matching target tag
CustomerManager:CalcMyAttractive -- Calculates store's total attractiveness
CustomerManager:ResetLeaveCustomerAttractive -- Initializes left customer attractiveness statistics
CustomerManager:CalcAttractiveRecipe -- Calculates total attractiveness of set recipes
CustomerManager:CalcAttractiveExpension -- Calculates attractiveness according to store expansion stage
CustomerManager:CalcAttractiveInterior -- Calculates attractiveness according to store interior level
CustomerManager:CalacAttractiveDeco -- Calculates attractiveness according to store decoration
CustomerManager:CalcRecipeAttractive -- Calculates attractiveness of specific recipe
CustomerManager:RequestPayPurchase -- Processes customer payment request and calculates sales
CustomerManager:RequestAddStorageTip -- Adds customer tip to storage or creates as drop
CustomerManager:RequestAddDropTip -- Adds dropped tip to player inventory
CustomerManager:CalcAppliacneBonus -- Calculates bonus according to kitchen appliance level
CustomerManager:CalcRecipeComboBonus -- Calculates recipe combo bonus
CustomerManager:HasWaitingCustomer -- Checks if there are waiting customers
CustomerManager:AddWaitCustomer -- Adds customer to waiting queue
CustomerManager:RemoveWaitCustomer -- Removes customer from waiting queue
CustomerManager:ExitWaitCustomer -- Makes waiting customers exit according to situation
CustomerManager:ReturnWaitSeat -- Finds and returns available waiting seat
CustomerManager:MoveAllCustomerForward -- Moves all waiting customers forward
CustomerManager:MoveCustomerForwardByCounterID -- Moves waiting customers of specific counter forward
CustomerManager:UpdateAllWaitCustomerPos -- Updates all waiting customer positions when expansion level changes
CustomerManager:OnMapLeave -- Cleans up customer manager when leaving map
CustomerManager:InitCustomerSpawner -- Initializes customer spawner
CustomerManager:SpawnCustomer -- Actually spawns customer
CustomerManager:OnUpdate -- Handles customer spawn timing every frame
CustomerManager:UpdateCustomerSpawnPos -- Updates customer spawn position according to expansion level
CustomerManager:SetTurialTagByOrderByNowStage -- Sets tutorial tag order according to current stage
CustomerManager:CustomerOrderChange -- Changes customer order content
CustomerManager:HandlePlayerReputationChangedEvent -- Handles player reputation change event
CustomerService:OnBeginPlay -- Initializes at customer service start
CustomerService:LoadDataOnServer -- Loads customer group ratio setting data on server
CustomerService:SpawnDropItem -- Creates customer tip as drop item
CustomerService:RequestGainDropTip -- Processes player's request to obtain dropped tip
CustomerService:SetEmotion -- Sets customer emotion state
CustomerService:SetBodyAction -- Sets customer body animation
CustomerService:EnableAngryMark -- Enables/disables customer angry mark
CustomerUIService:CreateOrderUI -- Creates customer order UI
CustomerUIService:OrderUIOff -- Deactivates customer order UI
CustomerUIService:CreatePreferUI -- Creates customer preference tag UI
CustomerUIService:PreferUIOfff -- Deactivates customer preference UI
CustomerUIService:UpdatePeedbackUI -- Updates customer feedback UI
CustomerUIService:CreatePayProductionUI -- Creates money display UI when customer pays
CustomerUIService:CreateTipProductionUI -- Creates display UI when tip is obtained
PeedbackRUID:OnBeginPlay -- Initializes resource IDs to use for feedback UI
AutoTrainingSlotData:FindSlotNumFromId -- Finds slot number from ID
AutoTrainingSlotData:FindSlotNumFromEntity -- Finds slot number from entity
AutoTrainingSlotData:ConvertToTable -- Converts slot data to table format
AutoTrainingSlotData:SetFromTable -- Sets slot information from table data
AutoTrainingSlotData:DefaultDataTable -- Creates default data table
AutoTrainingTruckSlot:SetLock -- Sets slot to locked state
AutoTrainingTruckSlot:SetUnlock -- Sets slot to unlocked state
AutoTrainingTruckSlot:SwitchLockPanel -- Switches UI panel according to lock state
AutoTrainingTruckSlot:ChangeUIOnState -- Changes UI according to state
AutoTrainingTruckSlot:UpdateTimeText -- Updates time text
AutoTrainingTruckSlot:EnableOkButtonDim -- Sets OK button dim state
AutoTrainingTruckSlot:SetOkBtnLunchBoxNum -- Sets lunch box count on OK button
AutoTrainingTruckSlot:UpdateTimeText_ParkingArea -- Updates parking area time text
AutoTrainingTruckSlot:ChangeUIOnState_ParkingArea -- Changes parking area UI state
HintItemData:Load -- Loads hint item information from data table
HintItemDataSetLogic:OnBeginPlay -- Loads dataset at game start
HintItemDataSetLogic:LoadDataSet -- Loads hint item dataset
HintItemDataSetLogic:GetHintItemData -- Gets hint item data by ID
HintItemDataSetLogic:ReturnItemListByColor -- Returns item list of specific color
HintItemDataSetLogic:ReturnItemIdByCategoryAndColor -- Returns item ID by category and color
HintItemDataSetLogic:ReturnRowByColor -- Returns data row of specific color
HintItemDataSetLogic:ReturnRandomPlaceItems -- Returns random place items
HintItemDataSetLogic:ReturnIconRuidById -- Returns icon RUID by ID
HintItemDataSetLogic:ReturnItemName -- Returns item name by ID
PaperHintComponent:SetPaperHint -- Sets paper hint type
PaperHintComponent:HandleButtonClickEvent -- Event handler that opens paper hint icon when button is clicked
PlayerAutoTrainingManager:SaveToDB -- Saves auto training data to database
PlayerAutoTrainingManager:OnLoadedDataFromDB -- Processes data loaded from database
PlayerAutoTrainingManager:InitComponent -- Initializes component
PlayerAutoTrainingManager:ConvertToTable -- Converts struct data to table
PlayerAutoTrainingManager:ConvertTableToInfo -- Converts table data to slot information
PlayerAutoTrainingManager:UpdateUnlockCondition -- Updates slot unlock conditions
PlayerAutoTrainingManager:SetLockSlots -- Sets slot lock state
PlayerAutoTrainingManager:SetLockSlotsUI -- Sets slot lock UI on client
PlayerAutoTrainingManager:TruckSlotOkButton -- Processes truck slot OK button click
PlayerAutoTrainingManager:OnClickRewardAllButton -- Processes all reward button click
PlayerAutoTrainingManager:TrainingShortCut -- Processes training shortcut
PlayerAutoTrainingManager:StartTrainingShortCut -- Starts training shortcut
PlayerAutoTrainingManager:FailStartTrainingShortCut -- Processes training shortcut start failure
PlayerAutoTrainingManager:CheckGoTraining -- Checks training start conditions
PlayerAutoTrainingManager:StartTraining -- Starts training
PlayerAutoTrainingManager:FailStartTraining -- Processes training start failure
PlayerAutoTrainingManager:OpenResultPopup -- Opens result popup
PlayerAutoTrainingManager:CalcResult -- Calculates training result
PlayerAutoTrainingManager:DisplayResultSlot -- Displays result slot
PlayerAutoTrainingManager:GiveReward -- Grants reward to player
PlayerAutoTrainingManager:OnRewardPopupOkButton -- Processes reward popup OK button click
PlayerAutoTrainingManager:ChangeTruckState -- Changes truck state
PlayerAutoTrainingManager:ChangeTruckStateClient -- Changes truck state on client
PlayerAutoTrainingManager:StartTimer -- Starts timer
PlayerAutoTrainingManager:UpdateTimer -- Updates timer
PlayerAutoTrainingManager:InitTruckSlot -- Initializes truck slot
PlayerAutoTrainingManager:UpdateTimerUI -- Updates timer UI
PlayerAutoTrainingManager:UpdateHudTimerUI -- Updates HUD timer UI
PlayerAutoTrainingManager:UpdateParkingAreaInfo -- Updates parking area information
PlayerAutoTrainingManager:SetChuhuInTruck -- Sets ChuChu in truck
PlayerAutoTrainingManager:SyncData -- Synchronizes data
PlayerAutoTrainingManager:ChangeStateChuchuListSlot -- Changes ChuChu list slot state
PlayerAutoTrainingManager:UpdateChuchuSlot -- Updates ChuChu slot
PlayerAutoTrainingManager:SetEmpScroll -- Sets employee scroll
PlayerAutoTrainingManager:UpdateTrainingSelectedList -- Updates training selected list
PlayerAutoTrainingManager:UpdateLunchBoxTruckSlotOkButtons -- Updates lunch box truck slot OK buttons
PlayerAutoTrainingManager:OnOpenUI -- Processes when UI opens
PlayerAutoTrainingManager:CheckCanRewardForRedDot -- Checks if reward is possible for red dot display
PlayerAutoTrainingManager:CanRewardAutoTraining -- Sets auto training reward possible state
PlayerAutoTrainingManager:OnTransferAutoTrainingChuchu -- Processes when transferring auto training ChuChu
PlayerAutoTrainingManager:CheckChuchuAutoTraining -- Checks ChuChu's auto training state
PlayerAutoTrainingManager:OnClickScooterArea -- Processes scooter area click
PlayerAutoTrainingManager:AutoTrainingToastMsg -- Displays auto training toast message
PlayerTrainingManager:LoadConfigData -- Loads burger price bonus configuration data
PlayerTrainingManager:OnClickTrainingButton -- Processes training start button click
PlayerTrainingManager:RequestEnterTraining -- Processes training entry request
PlayerTrainingManager:FadeInTraining -- Processes fade in effect at training start
PlayerTrainingManager:OnStartTraining -- Initializes when starting training
PlayerTrainingManager:ResetValues -- Initializes training related values
PlayerTrainingManager:ResetValuesClient -- Initializes training related values on client
PlayerTrainingManager:InitUI -- Initializes training UI
PlayerTrainingManager:ChangeBurgerPrice -- Changes burger price
PlayerTrainingManager:CreateCharModels -- Creates character models to participate in training
PlayerTrainingManager:CreateHints_Fix -- Creates hints in fixed form
PlayerTrainingManager:CreateHints -- Creates hints randomly
PlayerTrainingManager:CreateHotPlace -- Creates hot place and sets customer count
PlayerTrainingManager:CreateIngreBoxList -- Creates ingredient box list
PlayerTrainingManager:ChoiceHint -- Selects hint at specific spot
PlayerTrainingManager:OpenHintPopup -- Opens hint popup
PlayerTrainingManager:SelectLunchBoxButton -- Selects lunch box button
PlayerTrainingManager:SwitchSelectedTCharToNext -- Switches selected character to next character
PlayerTrainingManager:SwitchNextChuchu -- Switches to next character
PlayerTrainingManager:SendChuChu -- Sends character to specific spot
PlayerTrainingManager:FindIngredientBox -- Processes when ingredient box is found
PlayerTrainingManager:NextTurn -- Advances to next turn
PlayerTrainingManager:OnSelectLastSpot -- Processes when last spot is selected
PlayerTrainingManager:OnGoToPlaceButton -- Processes when go to place button is clicked
PlayerTrainingManager:SwitchPanel -- Switches UI panel according to state
PlayerTrainingManager:ClearHintScroll -- Clears hint scroll
PlayerTrainingManager:GiveReward -- Grants reward after training completion
PlayerTrainingManager:SetResultUI -- Sets training result UI
PlayerTrainingManager:OpenResultUI -- Opens training result UI
PlayerTrainingManager:OnEndTraining -- Processes when training ends
PlayerTrainingManager:LogEndTrainingServer -- Records training end log to server
PlayerTrainingManager:SetPlaceBg -- Sets background according to selected place
PlayerTrainingManager:ChangeBurgerPriceUI -- Changes burger price UI
PlayerTrainingManager:SetSelectedChuchuIdList -- Sets selected character ID list
PlayerTrainingManager:CheatStateChange -- Changes state with cheat
PlayerTrainingManager:ModifyLunchBoxNum -- Modifies lunch box count
PlayerTrainingManager:RouletteStart -- Starts roulette
PlayerTrainingManager:OpenMap -- Opens or closes map
PlayerTrainingManager:AddPaperHintInScroll -- Adds paper hint to scroll
PlayerTrainingManager:OnClickPaperHintIcon -- Processes when paper hint icon is clicked
PlayerTrainingManager:AddRewardBox -- Adds reward box
PlayerTrainingManager:GetSpotNameFromKey -- Gets spot name from spot key
PlayerTrainingManager:GetSpotFoodholdFromKey -- Gets terrain RUID from spot key
PlayerTrainingManager:GetSpotBgFromKey -- Gets background RUID from spot key
PlayerTrainingManager:SetProgressBar -- Sets progress bar
PlayerTrainingManager:CheckTodoList -- Checks todo list
PlayerTrainingManager:ShowLastSpot -- Shows last spot
PlayerTrainingManager:ShowLastSpot_HotPlace -- Shows hot place last spot
PlayerTrainingManager:EnterTrainingToast -- Shows training entry toast message
PlayerTrainingManager:SetHotPlaceName -- Sets hot place name
PlayerTrainingManager:ChangeMonth_HalfYear -- Changes half year information according to month
PlayerTrainingManager:AddExpReward -- Adds experience reward
PlayerTrainingManager:OnLastSpotSelect -- Processes when last spot is selected
PlayerTrainingManager:OnClickHintSkipButton -- Processes when hint skip button is clicked
PlayerTrainingManager:UpdateTrainingTicket -- Updates training ticket UI
PlayerTrainingManager:OnClickTruckArea -- Processes when truck area is clicked
SpotComponent:OnSelectLastSpot -- Processes when last spot is selected
SpotComponent:OnBeginPlay -- Initializes spot at game start
SpotComponent:ClearSpotHintScroll -- Clears spot hint scroll
SpotComponent:AddHintIcon -- Adds hint icon
SpotComponent:ClearEnteredTChar -- Clears entered character information
SpotComponent:OnClickHintIcon -- Processes hint icon click
SpotComponent:GoLastSpot -- Processes when moving to last spot
SpotComponent:BounceSpot -- Displays spot with bounce effect
SpotComponent:ChangeMaterial -- Changes entity material
SpotComponent:BigBounceSpot -- Displays spot with big bounce effect
SpotComponent:HandleButtonClickEvent -- Handles button click event
TrainingChar:OnBeginPlay -- Initializes character at game start
TrainingChar:OnEnterSpot -- Processes when entering spot
TrainingChar:Emotion -- Sets character emotion expression
TrainingChar:FindHint -- Processes finding hint
TrainingChar:FindPaperHint -- Processes finding paper hint
TrainingChar:GotoOriginPos -- Moves to original position
TrainingChar:Init -- Initializes character
TrainingChar:SetCharId -- Sets character ID
TrainingCustomerComponent:OnInitialize -- Initializes component
TrainingCustomerComponent:StartWalking -- Customer starts walking
TrainingCustomerComponent:Set -- Changes customer setting according to hot place status
TrainingExpRewardData:SetData -- Sets training experience reward data from data row
TrainingRewardLogic:OnBeginPlay -- Sets training reward data at game start
TrainingRewardLogic:SetData -- Loads and sets training experience reward data
TrainingRewardLogic:GetData -- Gets training experience reward data by stage ID and management level
UITraining:OnClickExitButton -- Processes exit button click
UITraining:OnClickGiveupButton -- Processes give up button click
UITraining:SetGuidePopup -- Sets guide popup
UITraining:EnableGuidePopup -- Enables/disables guide popup
UITraining:ChuchuChat -- Sets character chat message according to state
UITraining:UpdateTitleText -- Updates title text according to state
UITraining:OpenCloverInfoToolTip -- Opens clover information tooltip
UITraining:SetCloverInfo -- Sets clover information
UITraining:DestroyCloverInfoToolTip -- Destroys clover information tooltip
UITraining:HandleButtonClickEvent5 -- Map start button click event handler
UITraining:HandleButtonClickEvent6 -- Result UI open button click event handler
UITraining:HandleButtonClickEvent7 -- Exit button click event handler
UITraining:HandleButtonClickEvent13 -- Hint popup close button click event handler
UITraining:HandleButtonClickEvent15 -- Hint popup close button click event handler 2
UITraining:HandleButtonClickEvent11 -- Give up button click event handler
UITraining:HandleButtonClickEvent9 -- Burger sale start button click event handler
UITraining:HandleButtonClickEvent -- Map open button click event handler
UITraining:HandleButtonClickEvent10 -- Roulette start button click event handler
UITraining:HandleButtonClickEvent12 -- Map close button click event handler
UITraining:HandleButtonClickEvent16 -- Guide popup close button click event handler
UITraining:HandleButtonClickEvent17 -- Hint skip button click event handler
UITraining:HandleButtonClickEvent18 -- Clover info button click event handler
UITrainingAuto:OnBeginPlay -- Initializes auto training UI at game start
UITrainingAuto:InitUI -- Initializes auto training UI
UITrainingAuto:OpenUI -- Opens auto training UI
UITrainingAuto:CloseUI -- Closes auto training UI
UITrainingAuto:OnClickRewardAll -- Processes all reward button click
UITrainingAuto:SetLockSlots -- Sets slot lock state
UITrainingAuto:OnClickOkButton -- Processes OK button click
UITrainingAuto:OnResultOkButton -- Processes OK button click when result popup appears
UITrainingAuto:CloseResultPopup -- Closes result popup
UITrainingAuto:OpenResultPopup -- Opens result popup
UITrainingAuto:DisplayEmployeeScroll -- Displays employee scroll
UITrainingAuto:RefreshDetail -- Refreshes employee detail information
UITrainingAuto:OnClickSelectButton -- Processes select button click
UITrainingAuto:AddSelectedScroll -- Adds selected employee to scroll
UITrainingAuto:OpenChuchuListPopup -- Opens character list popup
UITrainingAuto:CloseChuchuListPopup -- Closes character list popup
UITrainingAuto:ChangeStateChuchuListSlot -- Changes character list slot state
UITrainingAuto:EmptySelectedSlot -- Empties selected slot
UITrainingAuto:SetTruckSlot -- Sets truck slot
UITrainingAuto:UpdateTruckChuchuSlot -- Updates truck character slot
UITrainingAuto:UpdateHudSlot -- Updates HUD slot
UITrainingAuto:EmptyHudSlot -- Empties HUD slot
UITrainingAuto:LockHudSlot -- Locks HUD slot
UITrainingAuto:LockParkingAreaEntity -- Locks parking area entity
UITrainingAuto:UpdateTruckSlotOkButtonDim -- Updates truck slot OK button dim state
UITrainingAuto:UpdateUpgradeInfo -- Updates upgrade information
UITrainingAuto:OnClickUpgradeBtn -- Processes upgrade button click
UITrainingAuto:EnableDimRewardAllBtn -- Sets dim state of all reward button
UITrainingAuto:OnClickScooterArea -- Processes scooter area click
UITrainingAuto:OpenCloverInfoToolTip -- Opens clover information tooltip
UITrainingAuto:SetCloverInfoToolTip -- Sets clover information tooltip
UITrainingAuto:DestroyCloverInfoToolTip -- Destroys clover information tooltip
UITrainingAuto:RegisterRecycleScrollLayoutCallback -- Registers recycle scroll layout callback
UITrainingAuto:RecycleScrollOnUpdateByIndex -- Updates recycle scroll by index
UITrainingAuto:CalcEmpIdFromIndex -- Calculates employee ID from index
UITrainingAuto:ReturnEntityFromEmpId -- Returns entity from employee ID
UITrainingAuto:HandleButtonClickEvent -- HUD slot click event handler
UITrainingAuto:HandleButtonClickEvent2 -- UI close button click event handler
UITrainingAuto:HandleButtonClickEvent3 -- Slot 1 OK button click event handler
UITrainingAuto:HandleButtonClickEvent4 -- Slot 2 OK button click event handler
UITrainingAuto:HandleButtonClickEvent5 -- Slot 3 OK button click event handler
UITrainingAuto:HandleButtonClickEvent6 -- Result OK button click event handler
UITrainingAuto:HandleButtonClickEvent7 -- Result popup close button click event handler
UITrainingAuto:HandleButtonClickEvent8 -- All reward button click event handler
UITrainingAuto:HandleButtonClickEvent9 -- Employee select button click event handler
UITrainingAuto:HandleButtonClickEvent10 -- Character list close button click event handler
UITrainingAuto:HandleButtonClickEvent11 -- Employee upgrade button click event handler
UITrainingAuto:HandleButtonClickEvent12 -- Shop open button click event handler
UITrainingAuto:HandleButtonClickEvent13 -- Upgrade button 1 click event handler
UITrainingAuto:HandleButtonClickEvent14 -- Upgrade button 2 click event handler
UITrainingAuto:HandleButtonClickEvent15 -- Upgrade button 3 click event handler
UITrainingAuto:HandleButtonClickEvent16 -- Character list popup close button click event handler
UITrainingAuto:HandleButtonClickEvent17 -- Shop open button 2 click event handler
UITrainingAuto:HandleButtonClickEvent19 -- Clover info button 1 click event handler
UITrainingAuto:HandleButtonClickEvent20 -- Clover info button 2 click event handler
UITrainingAuto:HandleButtonClickEvent21 -- Clover info button 3 click event handler
UITrainingSetting:OnBeginPlay -- Initializes training setting UI at game start
UITrainingSetting:OpenTrainingSettingUI -- Opens training setting UI
UITrainingSetting:OnClickStartButton -- Processes start button click
UITrainingSetting:CloseTrainingSettingUI -- Closes training setting UI
UITrainingSetting:RefreshDetail -- Refreshes employee detail information
UITrainingSetting:DisplayEmployeeScroll -- Displays employee scroll
UITrainingSetting:AddSelectedScroll -- Adds selected employee to scroll
UITrainingSetting:OnClickSelectButton -- Processes select button click
UITrainingSetting:OnClickSelectedSlot -- Processes selected slot click
UITrainingSetting:EmptySelectedSlot -- Empties selected slot
UITrainingSetting:GetSelectedChuchuNum -- Returns number of selected characters
UITrainingSetting:GetSelectedChuchuList -- Returns list of selected characters
UITrainingSetting:UpdateSelectedScroll -- Updates selected scroll
UITrainingSetting:UpdateSelectedList -- Updates selected list
UITrainingSetting:UpdateStartButtonDim -- Updates start button dim state
UITrainingSetting:UpdateTrainingTicketUI -- Updates training ticket UI
UITrainingSetting:SetSelectedSlot -- Sets selected slot
UITrainingSetting:OnClickUpgradeBtn -- Processes upgrade button click
UITrainingSetting:UpdateUpgradeInfo -- Updates upgrade information
UITrainingSetting:UpdateParkingAreaInfo -- Updates parking area information
UITrainingSetting:OnClickTruckArea -- Processes truck area click
UITrainingSetting:RegisterRecycleScrollLayoutCallback -- Registers recycle scroll layout callback
UITrainingSetting:RecycleScrollOnUpdateByIndex -- Updates recycle scroll by index
UITrainingSetting:CalcEmpIdFromIndex -- Calculates employee ID from index
UITrainingSetting:ReturnEntityByEmpId -- Returns entity from employee ID
UITrainingSetting:RecycleScrollOnUpdateByEmpId -- Updates recycle scroll by employee ID
UITrainingSetting:HandleButtonClickEvent -- Training setting UI open button click event handler
UITrainingSetting:HandleButtonClickEvent2 -- OK button click event handler
UITrainingSetting:HandleButtonClickEvent3 -- Close button click event handler
UITrainingSetting:HandleButtonClickEvent4 -- Select button click event handler
UITrainingSetting:HandleButtonClickEvent5 -- Employee upgrade button click event handler
UITrainingSetting:HandleButtonClickEvent6 -- Shop open button click event handler
UITrainingSetting:HandleButtonClickEvent7 -- Upgrade button 1 click event handler
UITrainingSetting:HandleButtonClickEvent8 -- Upgrade button 2 click event handler
UITrainingSetting:HandleButtonClickEvent9 -- Upgrade button 3 click event handler
UITrainingSetting:HandleButtonClickEvent10 -- Shop open button 2 click event handler
UITrainingSetting:HandleEmployeeDetailChangeEvent -- Employee detail change event handler
BurgerComponent:OnBurgerEntity -- Activates burger entity and sets sprite and size
BurgerComponent:OnBeginPlay -- Sets SpriteRendererComponent reference during component initialization
BurgerComponent:OffBurgerEntity -- Deactivates burger entity and decreases cooking burger count
BurgerComponent:SubstractBurgerEntity -- Decreases burger count and updates sprite size
BurgerComponent:AddBurgerEntity -- Increases burger count and updates sprite size
MenuManager:Init -- Initializes all data in menu manager
MenuManager:OnMapEnter -- Initializes menu manager when entering lobby map
MenuManager:OnMapLeave -- Initializes menu manager when leaving lobby map
MenuManager:ReturnSlotIdxByUniqueID -- Finds and returns recipe slot index by unique ID
MenuManager:ReturnRecipeUniqueID -- Finds and returns unique ID by recipe ID
MenuManager:ReturnRecipeDataByUniqueID -- Finds and returns recipe data by unique ID
MenuManager:SetMenu -- Updates menu settings and processes changes if any
MenuManager:HasChangedMenuSlot -- Checks if menu slot position has changed
MenuManager:HasChangedMenuRecipe -- Checks if menu recipe has changed
MenuManager:HasDiplayBurger -- Checks if there are burgers to display in specific slot
MenuManager:ModifyDisplayBurger -- Modifies display burger quantity and updates UI
MenuManager:RefreshDisplayBurger -- Refreshes display burger data and reflects menu changes
MenuManager:AddSaleBurgerCount -- Records accumulated sold burger quantity
MenuManager:ReturnSalesBurgerByRecipeID -- Queries sold burger quantity by recipe ID
MenuManager:AllClearSalesBurger -- Clears all sold burger records
MenuManager:ClearSaleBurgerByRecipeID -- Deletes sales record for specific recipe
MenuManager:OnSyncProperty -- Updates UI when synchronization property changes
MenuManager:GetDisplayedBurgerCount -- Returns displayed burger count in specific slot
MenuManager:GetDisplayedBurgerCountByUniqueId -- Returns total displayed burger count for all slots by unique ID
MenuManager:ClearLastRecipes -- Clears previous recipe setting records
MenuManager:AddCookingBurgers -- Adds cooking burger count
MenuManager:SubCookingBurgers -- Subtracts cooking burger count
MenuManager:GetCookingBurgers -- Queries cooking burger count
MenuManager:ResetCookingBurgers -- Resets cooking burger count
MenuService:BurgerInit -- Initializes burger entity sprite and rendering order
MenuService:CreateBurgerEntity -- Creates burger entity or reuses from pool and returns it
MenuService:ResetBurgerEntity -- Initializes burger entity and returns to pool
MenuService:ResetChildBurgerEntities -- Initializes all child burger entities under parent entity
MenuService:UpdateBurgerStackPos -- Updates stack positions of burgers held by employee
MenuService:ChangeMenuRecipe -- Handles customer and employee states when menu recipe changes
MenuService:ChangeMenuSlot -- Updates display burger and UI when menu slot changes
MenuService:GetBurgerRUID -- Queries and returns sprite RUID by burger tag
EventDialogManager:ParseDialog -- Parses rich text to separate plain text and format information
EventDialogManager:TypeWriter -- Outputs text with typing effect
EventDialogManager:PlayTypeWriter -- Starts typing animation
EventDialogManager:SkipTypeWriter -- Skips typing animation
EventDialogManager:EndTypeWriter -- Ends typing animation and performs cleanup
EventManager:CallEvent -- Starts event and stops time flow
EventManager:EndEvent -- Ends event and performs follow-up processing
EventManager:CallDialog -- Calls event dialog at specific index
EventManager:MoveNextDialog -- Moves to next dialog or skips typing
EventManager:SetEventOccurByAchiId -- Sets events to occur based on achievement ID
EventManager:ReturnOccuredEventGroupId -- Returns event group IDs corresponding to achievement ID
EventManager:CallEventOnDayChanged -- Calls pending events when day changes
EventManager:SetEventReferKeyData -- Sets reference key data for event
EventManager:SetCanMoveNext -- Sets whether can move to next dialog and manages auto-progress timer
EventManager:SetCallbackFunction -- Sets callback function to execute after event ends
EventManager:SetReferKeyForEmployment -- Sets employee ID as reference key in employment event
EventManager:HandleButtonClickEvent -- Handles event UI button click
EventManager:HandleTutorialTriggerEvent -- Handles tutorial trigger event and calls corresponding tutorial event
EventUIManager:Open -- Opens event UI and saves current HUD state
EventUIManager:Close -- Closes event UI and restores previous state
EventUIManager:SetDialogUI -- Sets appropriate UI according to event dialog type
EventUIManager:CloseAllEventEntities -- Deactivates all event UI entities
EventUIManager:SetCanMoveNextText -- Sets display state of next step move button and text
EventUIManager:ResetEntitiesRUID -- Initializes RUID of event UI entities
EventUIManager:OnBeginPlay -- Registers event UI entities at game start
EventUIManager:IsAnyEventUIOpened -- Checks if any event UI is open
UIButtonUnlockLogic:OnBeginPlay -- Loads button unlock data at game start
UIButtonUnlockLogic:LoadDataSet -- Loads button unlock data from CSV
UIButtonUnlockLogic:GetButtonUnlockData -- Gets button unlock data by ID
UIButtonUnlockLogic:IsButtonUnlocked -- Checks if specified button is unlocked
UIButtonUnlockLogic:SetButtonsUnlock -- Updates unlock status of all buttons
UIButtonUnlockLogic:SetEnableEveryButtons -- Forcibly unlocks all buttons
UIButtonUnlockLogic:HandlePlayerManagementChangedEvent -- Updates button status when player management data changes
UIEventConfettiSpawner:OnBeginPlay -- Initializes confetti spawner
UIEventConfettiSpawner:SpawnRandomConfetti -- Spawns random confetti and starts animation
UIEventConfettiSpawner:StartSpawnConfetties -- Starts confetti spawn animation
UIEventConfettiSpawner:EndSpawnConfetties -- Ends confetti spawn and cleans up
UIEventConfettiSpawner:ReturnRandomConfettiRUID -- Returns random confetti RUID
ButtonUnlockData:Load -- Loads button unlock information from CSV data
EventDataSetLogic:OnBeginPlay -- Initializes event-related data at game start
EventDataSetLogic:LoadDataSet -- Loads event group data and NPC data from CSV
EventDataSetLogic:SetOpenFunctionRUIDs -- Sets icon RUIDs to use for function open events
EventDataSetLogic:GetNPCData -- Returns NPC data by NPC ID
EventDataSetLogic:ReturnDialogText -- Formats and returns event dialog text with reference keys and arguments
EventDataSetLogic:GetEventGroupData -- Returns event group data by event group ID
EventDialogData:Load -- Loads event dialog information from CSV data
EventGroupData:Load -- Loads event group information from CSV data and connects dialog data
EventGroupData:ReturnBooleanByString -- Converts string to boolean value
NPCData:Load -- Loads NPC information from CSV data and sets default values
UIEventCongrats:Init -- Initializes congratulation event UI elements
UIEventCongrats:Refresh -- Refreshes congratulation event UI and displays congratulation effect
UIEventDecoUpgrade:StartRender -- Starts interior upgrade animation rendering
UIEventDecoUpgrade:EndRender -- Ends rendering and allows move to next step
UIEventDecoUpgrade:ChangePhase -- Changes to specified phase
UIEventDecoUpgrade:PhaseFunction -- Executes interior upgrade animation by phase
UIEventDecoUpgrade:GetTargetEntity -- Finds and returns entity by entity name
UIEventDecoUpgrade:StartCameraTween -- Starts camera transition animation
UIEventDecoUpgrade:StartToastTween -- Starts completion toast message animation
UIEventDecoUpgrade:SetParticlesPos -- Sets particle effect positions by camera level
UIEventDecoUpgrade:ChangeCameraTo -- Switches to specified camera
UIEventDecoUpgrade:Lerp -- Linearly interpolates between two values
UIEventEndTrend:Init -- Initializes trend end event UI elements
UIEventEndTrend:Refresh -- Displays trend end event information and generates report
UIEventEndTrend:Reset -- Resets UI elements to initial state
UIEventExpansion:Init -- Initializes expansion event UI elements and camera boundaries
UIEventExpansion:StartRender -- Starts expansion event rendering and proceeds with initial setup
UIEventExpansion:EndRender -- Ends rendering and allows move to next step
UIEventExpansion:ChangePhase -- Changes to specified phase
UIEventExpansion:PhaseFunction -- Executes expansion animation by phase
UIEventExpansion:StartCameraTween -- Starts camera transition animation
UIEventExpansion:StartToastTween -- Starts completion toast message animation
UIEventExpansion:SetParticlesPos -- Sets particle effect positions suitable for expansion level
UIEventExpansion:SetToastInfo -- Sets toast icon and text
UIEventExpansion:MakeReport -- Generates expansion/interior upgrade report
UIEventExpansion:Lerp -- Linearly interpolates between two values
UIEventFail:Init -- Initializes failure event UI elements
UIEventFail:Refresh -- Refreshes failure event UI and displays failure effect
UIEventGetItem:Init -- Initializes item acquisition event UI elements
UIEventGetItem:Refresh -- Refreshes item acquisition event UI and displays acquired items
UIEventGetItem:Reset -- Resets item acquisition event UI to initial state
UIEventInfoDialog:Init -- Initializes information dialog UI elements
UIEventInfoDialog:Refresh -- Refreshes information dialog UI and displays content
UIEventNewEmployee:Init -- Initializes new employee event UI elements
UIEventNewEmployee:Refresh -- Refreshes new employee event UI and displays employee information
UIEventNewEmployee:Reset -- Resets new employee event UI to initial state
UIEventOpenFunction:Init -- Initializes function open event UI elements
UIEventOpenFunction:Refresh -- Refreshes function open event UI and displays icon
UIEventOpenFunction:Reset -- Resets function open event UI to initial state
UIEventRankingAnnounce:Init -- Initializes ranking announcement event UI elements
UIEventRankingAnnounce:StartRender -- Starts ranking announcement rendering and prepares data
UIEventRankingAnnounce:EndRender -- Ends rendering and allows move to next step
UIEventRankingAnnounce:SetInitialInformations -- Sets initial information for previous ranking records
UIEventRankingAnnounce:SetListEntities -- Creates and arranges ranking list entities
UIEventRankingAnnounce:SetNoise -- Sets noise effect on ranking slots
UIEventRankingAnnounce:AnnounceResult -- Announces ranking results and displays current ranking
UIEventRankingAnnounce:ClearDatas -- Initializes ranking data and timers
UIEventRankingAnnounce:ChangePhase -- Changes ranking announcement phase
UIEventRankingAnnounce:PhaseFunction -- Executes ranking announcement logic by phase
UIEventResignEmployee:Init -- Initializes employee resignation event UI elements
UIEventResignEmployee:Refresh -- Refreshes employee resignation event UI and displays employee information
UIEventResignEmployee:Reset -- Resets employee resignation event UI to initial state
UIEventStartTrend:Init -- Initializes trend start event UI elements
UIEventStartTrend:Refresh -- Refreshes trend start event UI and displays positive/negative trends
UIEventStartTrend:Reset -- Resets trend start event UI to initial state
UIEventStoreName:OnBeginPlay -- Initializes store name change UI and connects events
UIEventStoreName:Refresh -- Updates store name input field and cost information
UIEventStoreName:OnClickConfirmBtn -- Handles store name set/change confirm button click event
UIEventTalkDialog:Init -- Initializes talk event UI elements
UIEventTalkDialog:Refresh -- Updates UI based on dialog data
UIEventTalkDialog:PlaySFX -- Plays sound effects according to specified key
UIEventTalkDialog:PlayPlayerEmotion -- Plays emotion animation on player avatar
TutorialData:Load -- Loads tutorial settings from CSV data
TutorialDataSetLogic:OnBeginPlay -- Loads tutorial data at game start
TutorialDataSetLogic:LoadDataSet -- Loads tutorial data from CSV and stores in table
TutorialDataSetLogic:GetTutorialData -- Returns tutorial data by ID
TutorialManager:IsEnableOpenPopUp -- Checks if popup can be opened based on time interval
TutorialManager:GetTargetEntity -- Finds and returns target entity according to tutorial data
TutorialManager:SetTargetPosition -- Sets target entity position according to parent
TutorialManager:MirroringUIParent -- Mirrors parent structure of target UI to create tutorial overlay
TutorialManager:ShowMask -- Displays tutorial mask and arranges guide text
TutorialManager:HideMask -- Hides tutorial mask and performs cleanup
TutorialManager:PlayTutorial -- Executes tutorial and displays UI according to settings
TutorialManager:OnEndPlay -- Cleans up timers when game ends
TutorialManager:SendTutorialTriggerEvent -- Sends tutorial trigger event
TutorialManager:CheckForceTo -- Checks forced conditions
TutorialManager:RegisterFunction -- Registers functions to use in tutorial
TutorialManager:RegisterForceTo -- Registers tutorial forced conditions
TutorialManager:OnBeginPlay -- Registers functions at game start
TutorialManager:SetCallbackHideMask -- Sets mask hide callback
TutorialManager:SetGuideTextPosition -- Sets guide text position
TutorialManager:SetGuideTextScreenPosition -- Sets guide text position based on screen coordinates
TutorialManager:HandleButtonClickEvent -- Handles tutorial button click and forwards target entity event
ManagementDataSetLogic:OnBeginPlay -- Loads management-related datasets at game start
ManagementDataSetLogic:LoadDataSet -- Loads management level data and maintenance cost data from CSV
ManagementDataSetLogic:LoadConfigData -- Loads equipment-related configuration data from config
ManagementDataSetLogic:ReturnMaintenance -- Calculates and returns player's total maintenance cost (store rent + equipment cost)
ManagementDataSetLogic:ReturnStoreRent -- Calculates rent based on player's store expansion, interior, and decoration levels
ManagementDataSetLogic:ReturnApplianceCost -- Calculates maintenance cost based on player's equipment count and level
ManagementDataSetLogic:MakeGoalCompleteReport -- Adds management goal completion message to report queue (client function)
ManagementDataSetLogic:GetManagementLevelData -- Returns management level data for specified level
ManagementDataSetLogic:RequestStartMLevelUpRewardRender -- Starts management level up reward UI rendering (client function)
ManagementDataSetLogic:GetManagementGoalData -- Returns management goal data for specified stage and level
ManagementGoalData:Load -- Loads management goal data for specific level from CSV rows
ManagementGoalIndexData:Load -- Loads achievement type and goal value from CSV data
ManagementLevelData:Load -- Loads UI display information for management level from data table
UIHUDManagement:OnBeginPlay -- Initializes sub-entities of HUD management UI
UIHUDManagement:Refresh -- Updates HUD according to player's management level status
UIManagement:Open -- Opens management UI and plays opening animation
UIManagement:Close -- Closes management UI
UIManagement:Refresh -- Refreshes UI according to player's management level and goal status
UIManagement:OnClickLevelUpBtn -- Checks conditions and requests level up when management level up button is clicked
UIManagement:HandleButtonClickEvent -- Management UI open button click event handler
UIManagement:HandleButtonClickEvent2 -- Management UI close button click event handler
UIManagement:HandleButtonClickEvent3 -- Level up button click event handler
UIManagement:HandlePlayerManagementChangedEvent -- Player management status change event handler
UIManagement:HandleButtonClickEvent4 -- Additional management UI open button click event handler
UIManagement:HandleButtonClickEvent5 -- Ranking view button click event handler
UIManagement:HandleButtonClickEvent6 -- Stage select button click event handler
UIManagement:HandleplayerStageProgressChangedEvent -- Player stage progress change event handler
UIManagementGoalSlotRenderer:OnBeginPlay -- Initializes sub-UI elements of management goal slot and connects click events
UIManagementGoalSlotRenderer:Refresh -- Refreshes UI according to management goal slot data and completion status
UIManagementGoalSlotRenderer:RefreshGaugeBar -- Updates gauge bar according to goal progress
UIManagementLevelUpReward:OnBeginPlay -- Deactivates level up reward UI at game start
UIManagementLevelUpReward:Open -- Opens level up reward UI for specified management level
UIManagementLevelUpReward:Close -- Closes level up reward UI and performs cleanup
UIManagementLevelUpReward:SetCanClose -- Sets UI closable state
UIManagementLevelUpReward:StartRender -- Starts rendering of management level up reward UI
UIManagementLevelUpReward:ReturnLogList -- Creates and returns benefit list to display during management level up
UIManagementLevelUpReward:HandleButtonClickEvent -- Level up reward UI close button click event handler
TrialLogic:ReturnRandomRivalId -- Returns random rival employee ID that doesn't overlap with player's selected employee
TrialLogic:ReturnRandomBurgerIngreList -- Creates and returns random burger ingredient list for Trial
TrialLogic:ReturnUserStatByTrialInfo -- Calculates and returns user's stat value based on Trial information and player data
TrialLogic:ReturnIngreGradeByGrade -- Randomly selects and returns ingredient grade to use according to Trial grade
TrialLogic:ReturnUserRank -- Compares user stats with required stats to calculate Trial ranking
TrialLogic:ReturnTrialScore -- Calculates and returns Trial score based on ranking and player weight
TrialLogic:ReturnStackPositionByGrid -- Converts grid coordinates to actual UI positions and returns stack item placement position
TrialLogic:ReturnTrialName -- Returns localized Trial name based on Trial ID (client-only function)
TrialLogic:ReturnUnofficialTrialProgress -- Calculates challengeable progress in unofficial Trials based on player abilities
TrialLogic:ReturnNextProgress -- Calculates and returns next step progress from current progress
TrialLogic:IsTrialRecommended -- Determines if Trial is recommended based on player abilities (client-only function)
TrialLogic:GetChallengingOfficialTrialProgress -- Returns next progress player can challenge in official Trials
TrialLogic:GetChallengingTrialData -- Returns difficulty data player can challenge according to Trial type
TrialLogic:GetExEmployeeIdOfType -- Returns excluded employee ID for specific employee type
TrialLogic:PlayUIEmployeeAnim -- Displays employee animation and equipment in UI
TrialLogic:ReturnPreviousProgress -- Calculates and returns previous step progress from current progress
TrialResultUILogic:EnableTrialResultUI -- Controls Trial result UI activation/deactivation (client-only function)
TrialResultUILogic:UpdateTrialResultInfo -- Updates Trial result information and sets UI elements (client-only function)
TrialResultUILogic:ChangePhase -- Changes Trial result UI phase and performs initialization for that phase (client-only function)
TrialResultUILogic:InitEntitiesForPhase -- Initializes UI entity states needed for specific phase (client-only function)
TrialResultUILogic:PhaseFunction -- Handles animations and logic to execute in each phase (client-only function)
TrialResultUILogic:HandleButtonClickEvent -- Handles button clicks in Trial result screen
TrialSimpleRenderLogic:OnBeginPlay -- Loads animation resources needed for Trial rendering at game start (client-only function)
TrialSimpleRenderLogic:EnterTrialRender -- Starts Trial rendering and sets layout and screen information (client function)
TrialSimpleRenderLogic:EndTrialRender -- Ends Trial rendering and transitions to result UI (client-only function)
TrialSimpleRenderLogic:SkipTrialRender -- Skips Trial rendering and immediately moves to result screen (client function)
TrialSimpleRenderLogic:FadeInFunction -- Sets UI groups and applies BGM during Trial screen fade in (client function)
TrialSimpleRenderLogic:ChangePhase -- Changes Trial rendering phase and initializes UI and logic for that phase (client-only function)
TrialSimpleRenderLogic:InitEntitiesForPhase -- Initializes and sets entities needed for specific phase (client-only function)
TrialSimpleRenderLogic:PhaseFunction -- Handles timer-based logic and animations to execute in each phase (client-only function)
TrialSimpleRenderLogic:HandleButtonClickEvent2 -- Handles skip button click during Trial rendering
TrialUILogic:OpenSelectTrialUI -- Opens Trial selection UI and deactivates other related UIs (client-only function)
TrialUILogic:ReturnIconRUIDByTargetStat -- Returns corresponding icon RUID according to target stat type
TrialUILogic:DrawDifficultyStars -- Displays Trial difficulty as star icons (client-only function)
TrialUILogic:GradeColorCode -- Returns color code according to Trial grade
TrialUILogic:CheckTrialRedDotEnable -- Checks player abilities to determine Trial tab red dot display (client function)
TrialUILogic:HandleButtonClickEvent -- Handles Trial button click event to open Trial selection UI
TrialData:Load -- Loads Trial information from CSV data and initializes object properties
TrialData:GetGradeData -- Returns TrialGradeData object corresponding to specified grade
TrialData:GetMaxDifficultyData -- Returns highest grade's highest difficulty data
TrialDataSetLogic:OnBeginPlay -- Loads Trial dataset at game start
TrialDataSetLogic:LoadDataSet -- Loads Trial data and victory weight data from CSV and stores in memory
TrialDataSetLogic:GetTrialData -- Returns TrialData object corresponding to specific Trial ID
TrialDifficultyData:Load -- Loads Trial difficulty information from CSV data and sets reward and cost data
TrialDifficultyData:GetTrialCost -- Calculates and returns entry cost based on player's current stage and Trial type
TrialGradeData:Load -- Loads Trial grade data and initializes all difficulty data for that grade
TrialGradeData:ReturnGradeBGRUID -- Returns background image RUID according to grade
TrialGradeData:GetDifficultyData -- Returns TrialDifficultyData object corresponding to specified difficulty
TrialGradeData:ReturnMaxDifficulty -- Returns maximum difficulty value available in current grade
UITrialCustomer:ChangeAvatarActionState -- Changes Trial customer avatar action state (client-only function)
UITrialCustomer:SpawnAndGetIn -- Creates Trial customer and moves to specified position (client-only function)
UITrialCustomer:BuyAndGoOut -- Handles animation of Trial customer purchasing and leaving (client-only function)
UITrialCustomer:RequestBuyState -- Requests purchase state from Trial customer (client-only function)
UITrialCustomer:OnBeginPlay -- Finds and stores item entity during component initialization (client-only function)
UITrialCustomer:SetItem -- Sets item for Trial customer to hold according to tag (client-only function)
UITrialCustomers:OnBeginPlay -- Finds and stores child layouts during component initialization (client-only function)
UITrialCustomers:Spawn -- Creates Trial customers and makes them appear with animation (client-only function)
UITrialCustomers:Despawn -- Handles disappearing animation of Trial customers (client-only function)
UITrialCustomers:SetStatIconEntities -- Creates and sets stat icon entities according to score (client-only function)
UITrialCustomers:TweenLog -- Displays stat log with animation (client-only function)
UITrialEmployeeDetail:OnBeginPlay -- Finds and connects UI elements during component initialization (client-only function)
UITrialEmployeeDetail:Refresh -- Refreshes UI to display employee information and Trial result prediction (client-only function)
UITrialEmployeeSlot:Init -- Initializes employee slot UI elements and connects click events
UITrialEmployeeSlot:Refresh -- Refreshes employee slot with given employee ID
UITrialEmployeeSlot:SelectEmp -- Selects employee and updates detailed information
UITrialEmployeeSlot:OnBeginPlay -- Performs initialization when component starts (client-only function)
UITrialGradeUpRenderer:StartRender -- Starts Trial grade up rendering (client-only function)
UITrialGradeUpRenderer:EndRender -- Ends Trial grade up rendering (client-only function)
UITrialGradeUpRenderer:RenderGradeUp -- Renders Trial grade up animation by steps (client-only function)
UITrialGradeUpRenderer:RenderGradeMax -- Renders Trial max grade achievement animation by steps (client-only function)
UITrialGradeUpRenderer:Init -- Initializes UI elements and saves original sizes (client-only function)
UITrialGradeUpRenderer:SetGradeEntity -- Sets grade entity color and image according to grade (client-only function)
UITrialLayout:SetLayouts -- Initializes Trial layouts and prepares tween data (client-only function)
UITrialLayout:ClearChildEntities -- Cleans up all child entities and initializes data when Trial ends (client-only function)
UITrialLayout:SpawnBurger -- Creates burgers in specified layout (client-only function)
UITrialLayout:SpawnIngredient -- Creates individual ingredients and determines animation (client-only function)
UITrialLayout:RemoveBurger -- Removes burger and moves remaining burgers downward (client-only function)
UITrialLayout:SuccessFunction -- Handles Trial success event and executes corresponding animation (client-only function)
UITrialLayout:SetStackEntities -- Creates and arranges stack items according to employee stats (client-only function)
UITrialLayoutSlot:OnBeginPlay -- Finds and connects all UI elements during component initialization (client-only function)
UITrialLayoutSlot:SetBoxSlider -- Sets box slider value (client-only function)
UITrialLayoutSlot:SetScoreboard -- Displays ranking and score on scoreboard (client-only function)
UITrialLayoutSlot:SetNametag -- Sets nametag and determines display mode (client-only function)
UITrialLayoutSlot:SetStatLogData -- Sets statistics log data (client-only function)
UITrialLayoutSlot:SetNotifyEnable -- Activates notifications and sets text and duration (client-only function)
UITrialLayoutSlot:SetVoteEntities -- Sets vote entities according to score (client-only function)
UITrialLayoutSlot:SetLayoutCustomerEntities -- Sets customer entities in layout (client-only function)
UITrialProgress:Init -- Initializes grade and difficulty entities of Trial progress UI (client-only function)
UITrialProgress:Refresh -- Refreshes Trial progress UI with given grade and difficulty (client-only function)
UITrialRewardPopup:Init -- Initializes Trial reward popup UI elements and connects button events (client-only function)
UITrialRewardPopup:Open -- Opens Trial reward popup and plays animation (client-only function)
UITrialRewardPopup:Close -- Closes Trial reward popup (client-only function)
UITrialRewardPopup:Refresh -- Updates popup UI based on Trial information and reward data (client-only function)
UITrialScreen:OnBeginPlay -- Finds and connects all UI elements of Trial screen during component initialization (client-only function)
UITrialScreen:SetTrialInformation -- Displays Trial information on screen and updates nametag, description, and progress (client-only function)
UITrialScreen:SetCommentEnable -- Displays comment messages during Trial and manages timer (client-only function)
UITrialScreen:SetScreenUI -- Sets display state of UI elements according to Trial screen phase (client-only function)
UITrialScreen:SetTimeSlider -- Sets time progress slider fill amount (client-only function)
UITrialSelect:OnBeginPlay -- Sets tab buttons and connects events during component initialization (client-only function)
UITrialSelect:Open -- Opens Trial selection UI and switches to specified tab (client-only function)
UITrialSelect:Close -- Closes Trial selection UI and normalizes time flow (client-only function)
UITrialSelect:SetSelectTab -- Sets selected tab and loads content for that tab (client-only function)
UITrialSelect:OnSelectTab -- Updates visual state of tab buttons when tab is selected (client-only function)
UITrialSelect:Apply -- Loads and displays Trial list according to selected tab (client-only function)
UITrialSelect:SetTabRedDot -- Sets red dot display on tab and updates main menu notification (client-only function)
UITrialSelect:HandleButtonClickEvent -- Handles close button click to close Trial selection UI
UITrialSelect:HandleEmployeeDetailChangeEvent -- Updates Trial red dot display when employee detail information changes
UITrialSelectSlot:Init -- Initializes Trial selection slot UI elements and connects button events
UITrialSelectSlot:Refresh -- Updates Trial slot with given data and displays cost, status, etc.
UITrialSetEmployee:Open -- Opens employee selection UI for Trial participation and initializes (client-only function)
UITrialSetEmployee:Close -- Closes employee selection UI and resets manager state (client-only function)
UITrialSetEmployee:RefreshList -- Updates employee list according to sorting criteria and displays in scroll view
UITrialSetEmployee:RefreshDetail -- Updates detailed information of selected employee and reflects selection state
UITrialSetEmployee:OnClickSelectButton -- Starts Trial with selected employee when employee select button is clicked
UITrialSetEmployee:OnClickGrowthButton -- Opens upgrade UI for selected employee when employee growth button is clicked
UITrialSetEmployee:SetSortCriteria -- Sets sorting criteria for employee list and refreshes list
UITrialSetEmployee:ReturnSortedEmployeeDetailTable -- Sorts and returns employee detail table according to sorting criteria
UITrialSetEmployee:OnBeginPlay -- Sets scroll view cell update callback during component initialization (client-only function)
UITrialSetEmployee:OnListEmpty -- Sets display state of UI elements when employee list is empty
UITrialSetEmployee:HandleButtonClickEvent -- Handles close button click to close employee selection UI
UITrialSetEmployee:HandleButtonClickEvent2 -- Handles employee select button click to execute selection logic
UITrialSetEmployee:HandleButtonClickEvent3 -- Handles employee growth button click to open upgrade UI
UITrialSetEmployee:HandleEmployeeDetailChangeEvent -- Updates selected employee information when employee detail changes
UITrialSetTopBar:OnBeginPlay -- Connects top bar UI elements and sets events during component initialization (client-only function)
UITrialSetTopBar:Refresh -- Updates top bar UI with Trial information and displays recommended level
UITrialSetTopBar:ToggleTrialDescText -- Toggles Trial description tooltip open/close
EmploymentDetail:SetUI -- Sets employee detail information UI
EmploymentDetail:HandleButtonClickEvent -- Handles employee detail information button click event
EmploymentLevelButton:SetUI -- Sets employment level button UI
EmploymentLevelButton:SetStageImage -- Sets image matching current stage
EmploymentLevelButton:HandleButtonClickEvent -- Handles employment level button click event
PlayerEmployment:SaveToDB -- Saves employment-related data to database
PlayerEmployment:OnLoadedDataFromDB -- Loads employment-related data from database
PlayerEmployment:InitComponent -- Initializes employment component
PlayerEmployment:OnBeginPlay -- Initializes employment-related data at game start
PlayerEmployment:SetEmploymentTypeInfo -- Sets employment type information
PlayerEmployment:SetEmploymentTypeList -- Sets employment type list on client
PlayerEmployment:SuccessToStartRecruit -- Handles when employment start succeeds
PlayerEmployment:CheckCanStartRecruit -- Checks if employment can start
PlayerEmployment:FailToStartRecruit -- Handles when employment start fails
PlayerEmployment:OnProcessingRecruit -- Starts employment processing
PlayerEmployment:OnFinishRecruiting -- Handles when employment processing completes
PlayerEmployment:Recruit_Fix -- Creates fixed employee list for tutorial
PlayerEmployment:ChangeState -- Changes employment state
PlayerEmployment:CheckCanEmployChuchu -- Checks if selected employee can be employed
PlayerEmployment:SuccessToEmployChuchu -- Handles when employee employment succeeds
PlayerEmployment:FailToEmployChuchu -- Handles when employee employment fails
PlayerEmployment:OnCancelEmployment -- Handles when employment is canceled
PlayerEmployment:CancelEmploymentServer -- Handles employment cancellation on server
PlayerEmployment:CancelEmploymentClient -- Handles employment cancellation on client
PlayerEmployment:OnSyncProperty -- Handles properties synchronized from server
PlayerEmployment:UpdateEmploymentList -- Updates employment employee list
PlayerEmployment:UpdateHasClover -- Updates UI color according to employment cost
PlayerEmployment:WaitForRecruit -- Handles employment waiting time
PlayerEmployment:AddScoutLv -- Increases scout level by 1
PlayerEmployment:ModifyScoutLv -- Modifies scout level
PlayerEmployment:SyncScoutLv -- Synchronizes scout level to client
PlayerEmployment:OnSelectChuchuInCollection -- Handles ChuChu selected from collection
PlayerEmployment:AddEmploymentLv -- Increases employment level by 1
PlayerEmployment:ModifyEmploymentLv -- Modifies employment level
PlayerEmployment:SyncEmploymentLv -- Synchronizes employment level to client
PlayerEmployment:ReturnCostByEmploymentLv -- Calculates and returns cost according to employment level
PlayerEmployment:ReturnCostByScoutLv -- Calculates and returns cost according to scout level
PlayerEmployment:FailToScout -- Handles when scouting fails
PlayerEmployment:SuccessToScout -- Handles when scouting succeeds
PlayerEmployment:OpenScoutUI -- Opens scout UI
PlayerEmployment:LogEmployment -- Records employment-related log
PlayerEmployment:ReturnEmploymentChuchuPool -- Returns employable ChuChu pool
PlayerEmployment:RerollList -- Rerolls employment list
PlayerEmployment:AddRerollCount -- Increases reroll count
PlayerEmployment:SyncRerollCount -- Synchronizes reroll count to client
PlayerEmployment:CalcRerollCost -- Calculates reroll cost
PlayerEmployment:CalcEmploymentStartLv -- Calculates employment start level
PlayerEmployment:HandlePlayerArcaneSymbolChangedEvent -- Handles player arcane symbol change event
UIEmployment:OnBeginPlay -- Handles employment UI initialization at game start
UIEmployment:SetEmploymentTypeList -- Sets employment type list to UI
UIEmployment:OpenUI -- Opens employment UI
UIEmployment:CloseUI -- Closes employment UI
UIEmployment:ChangeState -- Changes employment UI state
UIEmployment:OnCilckLevelButton -- Handles employment level button click
UIEmployment:SwitchButtonOutline -- Changes button selection state
UIEmployment:OnClickOkButton -- Handles OK button click
UIEmployment:FailRecruiting -- Handles when employment fails
UIEmployment:ShowEmployeeList -- Shows employable employee list
UIEmployment:OnCilckEmpListButton -- Handles when employee is selected from employee list
UIEmployment:SuccessEmploy -- Handles when employee employment succeeds
UIEmployment:FailEmploy -- Handles when employee employment fails
UIEmployment:CancelEmployment -- Handles when employment is canceled
UIEmployment:DisplayDetail -- Shows detailed information of selected employee
UIEmployment:OnClickCancelEmployment -- Handles when employment cancel button is clicked
UIEmployment:UpdateEmploymentLvText -- Updates employment level text
UIEmployment:UpdateEmploymentStageImg -- Updates employment stage image
UIEmployment:UpdateRerollText -- Updates reroll cost text
UIEmployment:OnClickRerollBtn -- Handles when reroll button is clicked
UIEmployment:UpdateDepositUI -- Updates employment deposit UI
UIEmployment:UpdateScountLvText -- Updates scout level text
UIEmployment:UpdateChuchuLevelInfoText -- Updates ChuChu level information text
UIEmployment:HandleButtonClickEvent -- Handles close button click event
UIEmployment:HandleButtonClickEvent2 -- Handles OK button click event
UIEmployment:HandleButtonClickEvent3 -- Handles employment UI open button click event
UIEmployment:HandleButtonClickEvent5 -- Handles employment cancel button click event
UIEmployment:HandleButtonClickEvent4 -- Handles employee list confirm button click event
UIEmployment:HandleButtonClickEvent6 -- Handles employee management button click event
UIEmployment:HandleButtonClickEvent7 -- Handles reroll button click event
UITransfer:CloseUI -- Closes transfer UI
UITransfer:OnClickOkButton -- Handles transfer confirm button click
UITransfer:TransferChuChu -- Executes ChuChu transfer
UITransfer:OpenTransferUI -- Opens transfer UI and sets employee information
UITransfer:SetInfo -- Sets heart and gem information to be refunded during transfer
UITransfer:NotifyFinishTransfer -- Handles transfer completion notification
UITransfer:HandleButtonClickEvent -- Handles close button click event
UITransfer:HandleButtonClickEvent2 -- Handles confirm button click event
StoreRankingDataSetLogic:OnBeginPlay -- Loads store ranking dataset at game start
StoreRankingDataSetLogic:LoadDataSet -- Reads store name data from CSV and loads into memory
StoreRankingDataSetLogic:ReturnRandomStoreNameOfGrade -- Returns random store name matching specific grade (excluding duplicates)
StoreRankingDataSetLogic:ReturnIndexsByRanking -- Returns start and end indices of ranking range to display based on ranking
StoreRankingDataSetLogic:ReturnPlayerUserRankingScore -- Returns player's ranking score (highest earnings)
StoreRankingDataSetLogic:ReturnPlayerUserRankingByScore -- Calculates and returns player's expected ranking based on score
StoreRankingDataSetLogic:ReturnRewardDataByRanking -- Returns reward data according to ranking
StoreRankingDataSetLogic:ReturnScoreByRanking -- Calculates and returns required score for ranking
StoreRankingDataSetLogic:ResetRankingSpeechText -- Resets player's ranking comment text to UI
StoreRankingDataSetLogic:GetRankFlowType -- Returns ranking change type as string (1st place, rising, same, falling)
StoreRankingDataSetLogic:RefreshRankingRedDot -- Displays red dot according to ranking re-examination availability
StoreRankingDataSetLogic:GetRankingReexamCost -- Returns re-examination cost according to player's current ranking
StoreRankingDataSetLogic:HandleBestEarningRecordChangedEvent -- Refreshes ranking red dot when best earning record changes
StoreRankingRewardData:Load -- Loads ranking reward information from CSV data row
StoreRankingRewardData:GetAdjustedReward -- Calculates and returns adjusted reward according to player's exact ranking
UIStoreRanking:Open -- Opens store ranking UI and refreshes all related data
UIStoreRanking:Close -- Closes store ranking UI
UIStoreRanking:RefreshRankingStatus -- Refreshes player's ranking status and displays ranking list
UIStoreRanking:RefreshRank1Data -- Refreshes and displays 1st place ranker information (displays differently if player is 1st or rival)
UIStoreRanking:ClearAvatarCostume -- Clears all custom costumes from avatar
UIStoreRanking:RefreshReexamButton -- Refreshes re-examination button status and cost information
UIStoreRanking:HandleButtonClickEvent -- Ranking UI open button click event handler
UIStoreRanking:HandleButtonClickEvent2 -- Ranking UI close button click event handler
UIStoreRanking:HandleTextInputEndEditEvent -- Ranking comment text input completion event handler
UIStoreRanking:HandleButtonClickEvent3 -- Ranking re-examination button click event handler
UIStoreRankingSlotRenderer:Init -- Initializes UI elements
UIStoreRankingSlotRenderer:RefreshInfo -- Refreshes ranking slot information and applies styles
GuideContentListData:Load -- Loads guide content information from data table and stores in properties
GuidePageController:OnBeginPlay -- Initializes guide page controller and connects close button event
GuidePageController:ContentDataSet -- Loads guide content data for page ID and creates UI entities
GuidePageController:SetButton -- Sets button entity to open guide page and connects click event
GuidePageController:Open -- Opens guide page and plays sound and changes UI state
GuidePageController:Close -- Closes guide page and plays sound and restores UI state
GuidePageController:OnUpdate -- Updates arrow display based on scroll position
GuidePageController:HandleButtonClickEvent -- Handles button click event to close guide page
GuidePageListData:Load -- Loads guide page information from data table and stores in properties
GuidePageManager:OnBeginPlay -- Initializes guide page manager and sets up all guide buttons
GuidePageManager:LoadDataSet -- Loads guide page list dataset and stores in internal table
GuidePageManager:GuideUIGroupEnable -- Sets activation state of guide UI group
GuidePageManager:SetGuidePage -- Sets specific guide page and connects open button
GuidePageManager:SetGuidePageButton -- Connects click event to guide page button
GuidePageManager:OpenGuidePage -- Opens guide page with specified page ID and loads content
CustomAvatarData:Load -- Loads custom avatar information from data table and sets properties
CustomAvatarData:SetAvatarCostume -- Applies custom avatar costume information to CostumeManagerComponent
DialogLineData:Init -- Initializes dialog line data and sets properties from CSV data
AvatarEmotionLogic:GetEmotionType -- Converts string emotion type to EmotionalType enum
DialogDataLogic:Load -- Loads dialog data and custom avatar data from CSV and stores in table
DialogDataLogic:GetDialogTable -- Returns dialog table corresponding to dialog ID
DialogDataLogic:GetFirstLineId -- Returns first line ID of dialog ID
DialogDataLogic:ChangeDefinitionWord -- Replaces special keywords in message text with actual values and extracts highlight information
DialogDataLogic:SetHighlight -- Applies highlight color tags to text
DialogDataLogic:OnBeginPlay -- Loads dialog data at game start
IntroDialogLogic:EnableUIDialogGroup -- Sets activation state of dialog UI group
IntroDialogLogic:ResetActor -- Resets intro-related actors to initial state
IntroDialogLogic:StartIntro -- Starts intro sequence and sets camera, fade, and caption
IntroDialogLogic:StartCutSceneIntro -- Starts cutscene intro and plays YouTube video
IntroDialogLogic:StopYoutubeVideo -- Stops YouTube video playback and deactivates player
IntroDialogLogic:EndCutSceneIntro -- Ends cutscene intro and transitions to next step
IntroDialogLogic:StartIntro2 -- Starts second intro dialog
IntroDialogLogic:StartPlayPopup -- Creates and displays game start popup
IntroDialogLogic:SkipIntroDialog1 -- Skips first intro dialog
IntroDialogLogic:SkipCutScene -- Skips cutscene and moves to next step
IntroDialogLogic:SkipIntroDialog2 -- Skips second intro dialog
IntroDialogLogic:EndIntro -- Completely ends intro and transitions to game
IntroDialogLogic:StartOutro -- Starts outro sequence
IntroDialogLogic:EndOutro -- Ends outro and restores game state
IntroDialogLogic:SetOutroYear -- Sets year to use in outro
IntroDialogLogic:ShowFade1 -- Executes fade in/out effect (type 1)
IntroDialogLogic:ShowFade2 -- Executes fade in effect only (type 2)
IntroDialogLogic:SetIntroCamera -- Switches to intro camera and sets zoom ratio
IntroDialogLogic:PlayCameraWalk1 -- Plays first camera walking animation
IntroDialogLogic:PlayCameraWalk2 -- Plays second camera walking animation
IntroDialogLogic:SkipPictureShow -- Skips picture display and resets background
IntroDialogLogic:ShowPickture -- Displays intro picture on screen and plays animation
IntroDialogLogic:StartIntroOpeningCaption -- Starts intro opening caption
IntroDialogLogic:EndIntroOpeningCaption -- Ends intro opening caption and starts dialog
IntroDialogLogic:OnBeginPlay -- Performs intro-related initialization at game start
IntroDialogLogic:DialogDimFade -- Fades dialog dim effect in/out
IntroDialogLogic:DialogDimShow -- Immediately displays dialog dim
IntroDialogSkipButton:HandleButtonClickEvent -- Performs appropriate skip action according to current dialog state when skip button is clicked
IntroOpeningCaption:Init -- Initializes intro opening caption and creates text entities
IntroOpeningCaption:SetData -- Sets next caption text data and starts typing effect
IntroOpeningCaption:OnPrintEnd -- Ends current caption typing effect and moves to next caption
IntroOpeningCaption:Close -- Closes caption and initializes all text entities
IntroOpeningCaption:OnUpdate -- Updates typing effect every frame
IntroOpeningCaption:OnBeginPlay -- Deactivates caption entity at game start
IntroStartPlayBtnComponent:HandleButtonClickEvent -- Ends intro and starts game when game start button is clicked
PortraitTypeEnum:ToInt -- Converts string portrait type to integer value
UIDialogLogic:MakeDialog -- Creates and starts dialog
UIDialogLogic:Init -- Initializes dialog system
UIDialogLogic:GetNextLine -- Proceeds to next dialog line or ends dialog
UIDialogLogic:EndDialog -- Ends dialog and calls callback function
UIDialogLogic:SetHUDOnDialog -- Sets display state of HUD and UI elements according to dialog status
UIDialogPanel:Open -- Opens dialog panel and sets data
UIDialogPanel:SetData -- Sets dialog data and updates portrait, text, and choices
UIDialogPanel:OnClickNext -- Handles next button click (completes typing or proceeds to next line)
UIDialogPanel:Close -- Closes dialog panel and initializes related state
UIDialogPanel:OnSelect -- Handles choice selection
UIDialogPanel:OnUpdate -- Updates typing effect every frame
UIDialogPanel:SetSelect -- Sets and displays choice UI
UIDialogPanel:Init -- Initializes UI elements and connects events
UIDialogPanel:OnPrintEnd -- Ends typing effect and activates choices
UIDialogPanel:StopTween -- Cleans up choice-related tweens and timers
UIDialogPanel:ChangeCurSelect -- Changes currently selected choice up/down
UIDialogPanel:SetSelected -- Sets selection state of specific choice item
UIDialogPanel:HandleKeyDownEvent -- Handles keyboard input (spacebar, arrow keys)
PlayerDiamondChangedEvent:Init -- Initializes player diamond change event
SideMenuData:Load -- Loads side menu data from CSV data
StageConfigData:Load -- Loads stage configuration data from CSV data
StageData:Load -- Loads stage data from CSV data and initializes related data
StageData:GetStageEarningLevelData -- Returns stage earnings data corresponding to earning level
StageData:GetStageRankingData -- Returns stage ranking data corresponding to index
StageData:GetReputationManagementData -- Returns reputation management data corresponding to management level
StageData:GetVIPOrderRequirementData -- Returns VIP order requirement data corresponding to management level and burger stack
StageData:GetVIPOrderRecipeRewardData -- Returns VIP order recipe reward data corresponding to management level
StageDataSetLogic:OnBeginPlay -- Loads stage data at game start
StageDataSetLogic:LoadDataSet -- Reads and initializes stage data from CSV
StageDataSetLogic:GetStageData -- Returns stage data corresponding to stage ID
StageDataSetLogic:GetStageOnlyIngredient -- Returns ingredient list obtainable only in that stage
StageDataSetLogic:GetStageTotalIngredient -- Returns all ingredient list available in that stage
StageDataSetLogic:GetStageCollectionRate -- Calculates and returns stage collection completion rate
StageDataSetLogic:GetLastStageId -- Returns last opened stage ID
StageDataSetLogic:GetStageClearProgress -- Returns progress required to clear stage
StageDataSetLogic:OpenStageClearRewardUI -- Opens stage clear reward UI
StageSettingEnum:OnBeginPlay -- Initializes stage setting menu enum
StageSettingEnum:GetIndexByKey -- Finds and returns enum index corresponding to key string
StrategyData:Load -- Loads strategy data from CSV data
StrategyData:GetLevelEffect -- Calculates and returns effect value according to strategy level and stage
StrategyDataSetLogic:OnBeginPlay -- Loads strategy and side menu data at game start
StrategyDataSetLogic:LoadDataSet -- Reads and initializes strategy and side menu data from CSV
StrategyDataSetLogic:GetStrategyData -- Returns strategy data corresponding to ID
StrategyDataSetLogic:GetSideMenuData -- Returns side menu data corresponding to ID
StrategyDataSetLogic:GetStrategyDescText -- Formats and returns strategy description text
StrategyDataSetLogic:GetSideMenuDescText -- Formats and returns side menu description text
StrategyDataSetLogic:GetStrategyEffectDescText -- Formats and returns strategy effect description text
StrategyDataSetLogic:SetSideMenuIconPos -- Sets side menu icon position
StrategyEnum:GetPlayerStrategyEffect -- Calculates and returns effect of player's set strategy
StrategyEnum:GetSideMenuEffect -- Calculates and returns side menu effect
SideMenuSettingChangedEvent:Init -- Initializes side menu setting change event
StrategySettingChangedEvent:Init -- Initializes strategy setting change event
UICurrentSideMenuSlot:Init -- Initializes UI components and connects events
UICurrentSideMenuSlot:Refresh -- Refreshes side menu slot UI
UICurrentStrategySlot:Init -- Initializes UI components and connects events
UICurrentStrategySlot:Refresh -- Refreshes current strategy slot UI
UICurrentStrategySlot:GetGoodsIcon -- Returns icon RUID according to related item
UISideMenuReward:Open -- Opens side menu reward UI
UISideMenuReward:MoveNext -- Moves to next reward step
UISideMenuReward:Close -- Closes side menu reward UI
UISideMenuReward:Refresh -- Refreshes reward UI
UISideMenuReward:HandleButtonClickEvent -- Handles reward purchase button click event
UIStageClearRewardGroup:OnBeginPlay -- Saves background original size during component initialization
UIStageClearRewardGroup:Open -- Opens stage clear reward group
UIStageClearRewardGroup:Close -- Closes stage clear reward group
UIStageClearRewardGroup:Refresh -- Refreshes UI and displays reward matching current index
UIStageClearRewardGroup:ClearUI -- Initializes and hides UI elements
UIStageClearRewardGroup:ChangeTitleText -- Changes to title text matching index and applies fade in effect
UIStageClearRewardGroup:MoveToIndex -- Moves to specified index and refreshes UI
UIStageClearRewardGroup:SetCanMoveNext -- Sets to allow move to next step
UIStageClearRewardGroup:OpenAnim -- Executes opening animation and returns duration
UIStageClearRewardGroup:ClearAnim -- Executes UI clearing animation and returns duration
UIStageClearRewardGroup:HandleButtonClickEvent -- Handles button click event to move to next step
UIStageClearRewardGroup:HandleKeyDownEvent -- Handles key down event
UIStageInfo:OnBeginPlay -- Sets tabs and pages during component initialization
UIStageInfo:Open -- Opens stage information UI
UIStageInfo:Close -- Closes stage information UI
UIStageInfo:SetSelectTab -- Sets selected tab
UIStageInfo:OnSelectTab -- Changes UI state when tab is selected
UIStageInfo:Apply -- Applies page according to selected tab
UIStageInfo:SetStageTitle -- Sets stage title
UIStageInfo:HandleButtonClickEvent -- Handles first button click event
UIStageInfo:HandleButtonClickEvent2 -- Handles second button click event
UIStageInfo:HandleButtonClickEvent3 -- Handles third button click event
UIStageInfo:HandleButtonClickEvent4 -- Handles fourth button click event
UIStageInfoEmployee:Init -- Initializes UI components
UIStageInfoEmployee:Refresh -- Refreshes employee information
UIStageInfoIngredient:Init -- Initializes UI components
UIStageInfoIngredient:Refresh -- Refreshes ingredient information
UIStageInfoStage:Init -- Initializes UI components and connects events
UIStageInfoStage:Refresh -- Refreshes stage information
UIStageInfoStrategy:Init -- Initializes UI components
UIStageInfoStrategy:Refresh -- Refreshes strategy information
UIStageInfoStrategy:GetGoodsIcon -- Returns icon according to related goods
UIStageRewardClear:StartRender -- Starts stage clear reward rendering
UIStageRewardClear:PlayAnim -- Plays reward animation
UIStageRewardClear:SetInfo -- Sets stage information
UIStageRewardClear:ClearUI -- Initializes UI
UIStageRewardSideMenu:StartRender -- Starts side menu reward rendering
UIStageRewardSideMenu:PlayAnim -- Plays side menu reward animation
UIStageRewardSideMenu:SetInfo -- Sets side menu information
UIStageRewardSideMenu:ClearUI -- Initializes UI
UIStageRewardSideMenu:OnBeginPlay -- Saves tray origin position at game start
UIStageRewardStrategy:StartRender -- Starts strategy reward rendering
UIStageRewardStrategy:PlayAnim -- Plays strategy reward animation
UIStageRewardStrategy:SetInfo -- Sets strategy information
UIStageRewardStrategy:ClearUI -- Initializes UI
UIStageSelect:OnBeginPlay -- Deactivates UI during component initialization
UIStageSelect:Open -- Opens stage selection UI
UIStageSelect:Close -- Closes stage selection UI
UIStageSelect:Refresh -- Refreshes stage list
UIStageSelect:OnSelectSlot -- Handles when stage slot is selected
UIStageSelect:RefreshChustarLevel -- Refreshes Chustar level
UIStageSelect:HandleButtonClickEvent -- Handles first button click event
UIStageSelect:HandleButtonClickEvent2 -- Handles second button click event
UIStageSelect:HandleButtonClickEvent3 -- Handles third button click event
UIStageSelect:HandleButtonClickEvent4 -- Handles fourth button click event
UIStageSelect:HandleButtonClickEvent5 -- Handles fifth button click event
UIStageSelect:HandleButtonClickEvent6 -- Handles sixth button click event
UIStageSelect:HandleButtonClickEvent7 -- Handles seventh button click event
UIStageSelect:HandleButtonClickEvent8 -- Handles eighth button click event
UIStageSelectSlot:Init -- Initializes UI components
UIStageSelectSlot:Refresh -- Refreshes stage slot
UIStageSelectSlot:IsComplete -- Checks if stage is complete
UIStageSelectSlot:IsLocked -- Checks if stage is locked
UIStageSelectSlot:SetStageComingSoon -- Sets stage coming soon status
UIStageSetting:OnBeginPlay -- Sets pages and navigator during component initialization
UIStageSetting:Open -- Opens stage setting UI and initializes
UIStageSetting:Close -- Closes stage setting UI and cleans up
UIStageSetting:RefreshSetting -- Refreshes setting page and displays
UIStageSetting:OnMoveNext -- Moves to next page
UIStageSetting:OnMovePrevious -- Moves to previous page
UIStageSetting:OnDone -- Handles when setting is complete
UIStageSetting:GetDataFromClient -- Gets setting data from client
UIStageSetting:RefreshStageInfoBar -- Refreshes stage info bar
UIStageSetting:ResetSetting -- Initializes settings
UIStageSetting:MoveNavigator -- Moves navigator
UIStageSetting:MoveIndicatorTo -- Moves indicator to specific position
UIStageSetting:HandleButtonClickEvent -- Handles next button click event
UIStageSetting:HandleButtonClickEvent2 -- Handles previous button click event
UIStageSetting:HandleButtonClickEvent3 -- Handles complete button click event
UIStageSetting:HandleButtonClickEvent4 -- Handles close button click event
UIStageSettingEmployee:Init -- Initializes UI components and connects events
UIStageSettingEmployee:Refresh -- Refreshes employee selection UI
UIStageSettingEmployee:RefreshCookSlot -- Refreshes cook slot
UIStageSettingEmployee:RefreshServingSlot -- Refreshes serving employee slot
UIStageSettingEmployee:SetSlot -- Sets employee slot
UIStageSettingIngredient:Init -- Initializes UI components
UIStageSettingIngredient:Refresh -- Refreshes stage setting ingredient information
UIStageSettingIngredient:RefreshPromotedIngres -- Refreshes promoted ingredient list
UIStageSettingIngredient:SetPromotedIngres -- Sets promoted ingredients
UIStageSettingIngredient:HandleButtonClickEvent -- Handles button click event
UIStageSettingStageInfo:Init -- Initializes UI components
UIStageSettingStageInfo:Refresh -- Refreshes stage information
UIStageSettingStageInfo:OpenAnim -- Executes opening animation
UIStageSettingStrategy:OnBeginPlay -- Sets tabs and recycle view during component initialization
UIStageSettingStrategy:Open -- Opens strategy setting UI
UIStageSettingStrategy:SetSelectTab -- Sets selected tab
UIStageSettingStrategy:OnSelectTab -- Changes UI state when tab is selected
UIStageSettingStrategy:Apply -- Applies data according to selected tab
UIStageSettingStrategy:Refresh -- Refreshes strategy setting UI
UIStageSettingStrategy:RefreshSPBar -- Refreshes SP bar
UIStageSettingStrategy:RefreshCurrentSideMenuSlot -- Refreshes current side menu slot
UIStageSettingStrategy:RequestSetStrategy -- Requests strategy setting
UIStageSettingStrategy:RequestSetSideMenu -- Requests side menu setting
UIStageSettingStrategy:ResetData -- Initializes setting data
UIStageSettingStrategy:RequestUnsetSideMenu -- Requests side menu setting cancellation
UIStageSettingStrategy:RequestUnsetStrategy -- Requests strategy setting cancellation
UIStageSettingStrategy:SetUsedSP -- Calculates and sets used SP
UIStageSettingStrategy:SetPassBtnRedDot -- Sets red dot on pass button
UIStageSettingStrategy:RefreshSideMenuTabRedDot -- Refreshes red dot on side menu tab
UIStageSettingStrategy:HandleButtonClickEvent -- Handles first button click event
UIStageSettingStrategy:HandleButtonClickEvent2 -- Handles second button click event
UIStageSettingStrategy:HandleStrategySettingChangedEvent -- Handles strategy setting change event
UIStageSettingStrategy:HandleSideMenuSettingChangedEvent -- Handles side menu setting change event
UIStageSettingStrategy:HandlePlayerSPChangedEvent -- Handles player SP change event
UIStartStageToast:OnBeginPlay -- Deactivates UI during component initialization
UIStartStageToast:Init -- Initializes UI components
UIStartStageToast:Open -- Opens stage start toast UI
UIStartStageToast:StartRender -- Starts toast animation
UIStartStageToast:OnEndPlay -- Cleans up timer when component ends
UIStartStageToast:HandleKeyDownEvent -- Handles key input event
UIStrategySlot:Init -- Initializes UI components and connects events
UIStrategySlot:Refresh -- Refreshes strategy or side menu slot
UIStrategySlot:RefreshStrategy -- Refreshes strategy slot
UIStrategySlot:RefreshSideMenu -- Refreshes side menu slot
UIStrategySlot:GetGoodsIcon -- Returns icon RUID according to related item
UIStrategySlot:GetSideMenuOpened -- Checks if side menu is open
UIStrategySlot:HandleStrategySettingChangedEvent -- Handles strategy setting change event
UIStrategySlot:HandleSideMenuSettingChangedEvent -- Handles side menu setting change event
UICollectionLogic:EnableIngreBunCollectionSlotRewardDot -- Activates/deactivates reward dot on ingredient/bun collection slot and handles tween animation
UICollectionLogic:DropDiamondAndMoveToMoneyBar -- Creates diamond icon and executes tween animation to move it to money bar
UICollectionLogic:SetIngreBunCollectionMenuBtnRedDot -- Sets red dot display on ingredient/bun collection button in main menu
UICollectionLogic:DropDiamondAndMoveToMoneyBar_ChuchuCollection -- Creates diamond icon for ChuChu collection and moves to money bar with tween animation
UICollectionLogic:RequestPlayGetAllRewardBtnAnim -- Executes get all reward button animation
UIIngreBunCollection:OnBeginPlay -- Sets tabs, filters, and sort options during component initialization
UIIngreBunCollection:Open -- Opens ingredient/bun collection UI and sets to specified tab
UIIngreBunCollection:Close -- Closes ingredient/bun collection UI
UIIngreBunCollection:SetSelectTab -- Changes selected tab and updates related UI
UIIngreBunCollection:OnSelectTab -- Updates visual state of tab UI when tab is selected
UIIngreBunCollection:Apply -- Applies data matching selected tab and updates UI
UIIngreBunCollection:RefreshList -- Creates item list matching selected tab, sorts and displays on screen
UIIngreBunCollection:SetFilter -- Sets filter condition and refreshes list if needed
UIIngreBunCollection:SetSort -- Sets sort condition and refreshes list if needed
UIIngreBunCollection:SetEnableFilterArea -- Sets activation state of filter selection area
UIIngreBunCollection:SetEnableSortArea -- Sets activation state of sort selection area
UIIngreBunCollection:GetDrawList -- Returns filtered item list according to selected tab
UIIngreBunCollection:OnClickSlot -- Handles reward collection and updates selection state when collection slot is clicked
UIIngreBunCollection:RefreshDetail -- Displays detailed information of selected item
UIIngreBunCollection:CheckCanGetReward -- Checks reward button status and sets red dot display by tab
UIIngreBunCollection:OnGetAllRewardButtonClicked -- Handles all collectable rewards for that tab when get all reward button is clicked
UIIngreBunCollection:ReturnCanGetReward -- Checks and returns if there are collectable rewards in specified tab
UIIngreBunCollection:RefreshSubBar -- Updates sub bar UI matching selected tab
UIIngreBunCollection:RefreshCollectionProgress -- Calculates and displays collection progress of selected tab
UIIngreBunCollection:GetTabIcon -- Returns icon RUID matching selected tab
UIIngreBunCollection:GetTabName -- Returns tab name matching selected tab
UIIngreBunCollection:HandleButtonClickEvent -- Collection open button click event handler
UIIngreBunCollection:HandleButtonClickEvent2 -- Collection close button click event handler
UIIngreBunCollection:HandleButtonClickEvent3 -- Get all reward button click event handler
UIIngreBunCollection:HandleButtonClickEvent4 -- Filter button click event handler
UIIngreBunCollection:HandleButtonClickEvent5 -- Sort button click event handler
UIIngreBunCollectionDetailBun:Init -- Initializes bun detail information UI components
UIIngreBunCollectionDetailBun:Refresh -- Displays detailed information of specified bun ID on screen
UIIngreBunCollectionDetailBunSkin:Init -- Initializes bun skin detail information UI components
UIIngreBunCollectionDetailBunSkin:Refresh -- Displays detailed information of specified bun skin ID on screen
UIIngreBunCollectionDetailIngre:Init -- Initializes ingredient detail information UI components
UIIngreBunCollectionDetailIngre:Refresh -- Displays detailed information of specified ingredient ID on screen
UIIngreBunCollectionSlot:OnBeginPlay -- References UI elements during component initialization
UIIngreBunCollectionSlot:RefreshIngre -- Updates ingredient collection slot data
UIIngreBunCollectionSlot:RefreshBun -- Updates bun collection slot data
UIIngreBunCollectionSlot:RefreshBunSkin -- Updates bun skin collection slot data
UIIngreBunCollectionSlot:EnableSelected -- Sets slot selection state
UIIngreBunCollectionSlot:HandleButtonClickEvent -- Slot click event handler
BadgeData:Load -- Loads badge information from CSV data table and initializes
BadgeDataSetLogic:OnBeginPlay -- Loads badge data at game start
BadgeDataSetLogic:LoadDataSet -- Reads badge data from CSV and stores in memory
BadgeDataSetLogic:GetBadgeData -- Returns badge data by badge ID
BadgeDataSetLogic:GetBadgeListByTypeId -- Filters and returns badge list corresponding to specific type ID
BadgeEnum:SetStageEmployeeCollectProgress -- Updates stage-specific employee collection progress
BadgeEnum:SetRecipeTagGradeProgress -- Updates recipe tag-specific grade progress
UIBadgeList:OnBeginPlay -- Performs UI component initialization and event connection
UIBadgeList:Open -- Opens badge UI and sets initial state
UIBadgeList:Close -- Closes badge UI
UIBadgeList:SetSelectTab -- Changes selected tab and updates UI
UIBadgeList:OnSelectTab -- Updates tab UI style when tab is selected
UIBadgeList:SetFilter -- Sets filter and updates UI
UIBadgeList:Refresh -- Refreshes badge list according to current filter and tab
UIBadgeList:RefreshProgressBar -- Updates badge collection progress bar
UIBadgeList:HandleButtonClickEvent -- Badge UI open button click event handler
UIBadgeList:HandleButtonClickEvent2 -- Badge UI close button click event handler
UIBadgeList:HandleButtonClickEvent3 -- Badge UI background click close event handler
UIBadgeSlot:Init -- Initializes UI component references
UIBadgeSlot:Refresh -- Updates badge slot UI with badge data
ExchangeChuChuAnim:Load -- Loads ChuChu animation data to use in exchange system from CSV
ExchangeDataSetLogic:OnBeginPlay -- Loads exchange-related datasets at game start
ExchangeDataSetLogic:LoadDataSet -- Loads exchange ingredients and ChuChu animation data from CSV and stores in table
ExchangeDataSetLogic:GetExchangeIngredientData -- Returns exchange ingredient data based on management level and index
ExchangeDataSetLogic:GetExchangeChuChuData -- Returns ChuChu animation data based on stage and index
ExchangeIngredient:Load -- Loads ingredient data to use in exchange system from CSV and calculates index
ExchangeManager:GiveReward -- Gives reward to player according to exchange result and deducts cost
ExchangeManager:CalculateReward -- Calculates final reward by applying bonus rate according to card result
ExchangeManager:ExchangePlayFlow -- Records exchange system entry log
MenuCardLogic:GetMenuImgRUID -- Returns appropriate image RUID according to menu type
MenuCardLogic:GetEffectWord -- Returns effect text image RUID according to card type
MenuCardLogic:GetImgOffset -- Returns image offset position according to menu type
MenuCardLogic:GetBGRUID -- Returns background image RUID according to menu type
MenuCardLogic:PlayEffectSound -- Plays appropriate effect sound according to card type
MenuCardLogic:RandomChuChuRUID -- Returns random ChuChu index according to current stage
MenuCardLogic:GetMutoImgRUID -- Returns Muto character image RUID according to menu type
UIExchange:OnBeginPlay -- Sets menu card type array when exchange UI initializes
UIExchange:OpenExchangeUI -- Opens exchange UI and performs initial setup
UIExchange:CloseExchangeUI -- Closes exchange UI
UIExchange:InitMenuCard -- Initializes and sets menu cards
UIExchange:ShuffleMenuCard -- Randomly shuffles menu card types
UIExchange:OnClickMenuCard -- Handles when menu card is clicked
UIExchange:ShowTray -- Displays selected menu on tray
UIExchange:InitTray -- Initializes tray
UIExchange:ShowWordEffect -- Shows word effect when card is selected
UIExchange:ShowResult -- Shows exchange result
UIExchange:ShowRewardEffect -- Shows reward effect and performs calculation
UIExchange:CalculateReward -- Calculates final reward according to card result (client function)
UIExchange:OnClickSkipBtn -- Skips effects and immediately shows result when skip button is clicked
UIExchange:RequestReward -- Requests reward payment to server
UIExchange:HandleButtonClickEvent -- Handles button click event
UIExchange:HandleButtonClickEvent2 -- Handles second button click event
UIExchangeSetting:OnBeginPlay -- Loads ingredient objects and sets default values when exchange setting UI initializes
UIExchangeSetting:OnClickHeartBtn -- Selects heart reward type and updates UI
UIExchangeSetting:OnClickCloverBtn -- Selects clover reward type and updates UI
UIExchangeSetting:OnClickResetBtn -- Resets ingredient count to 1
UIExchangeSetting:OnClickMinusBtn -- Decreases ingredient count by 1
UIExchangeSetting:OnClickAddBtn -- Increases ingredient count by 1
UIExchangeSetting:OnClickMaxBtn -- Sets ingredient count to maximum value of 10
UIExchangeSetting:SetExchangeType -- Sets exchange type
UIExchangeSetting:SetIngredients -- Sets ingredient count and updates UI
UIExchangeSetting:SetReward -- Calculates reward range considering card bonus and displays on UI
UIExchangeSetting:SetIngredientCost -- Calculates ingredient cost and displays on UI
UIExchangeSetting:CalculateGold -- Calculates required amount based on ingredient count and base amount
UIExchangeSetting:CloseExchangeSettingUI -- Closes exchange setting UI and initializes
UIExchangeSetting:OpenExchangeSettingUI -- Opens exchange setting UI and performs initial setup
UIExchangeSetting:OnClickStartBtn -- Validates and opens exchange UI when exchange start button is clicked
UIExchangeSetting:GetDefaultGold -- Gets base amount according to current stage and management level
UIExchangeSetting:CalculateReward -- Calculates reward according to exchange type and ingredient count
UIExchangeSetting:HandleButtonClickEvent -- Handles first button click event
UIExchangeSetting:HandleButtonClickEvent2 -- Handles second button click event
UIExchangeSetting:HandleButtonClickEvent3 -- Handles third button click event
UIExchangeSetting:HandleButtonClickEvent4 -- Handles fourth button click event
UIExchangeSetting:HandleButtonClickEvent5 -- Handles fifth button click event
UIExchangeSetting:HandleButtonClickEvent6 -- Handles sixth button click event
UIExchangeSetting:HandleButtonClickEvent7 -- Handles seventh button click event
UIExchangeSetting:HandleButtonClickEvent8 -- Handles eighth button click event
UIExchangeSetting:HandleButtonClickEvent9 -- Handles ninth button click event
IngreSynthLogic:DrawIngreList -- Filters player's ingredient cards and draws ingredient list, updates UI
IngreSynthLogic:RegisterRecycleScrollLayoutCallback -- Registers callback for ingredient list recycle scroll view
IngreSynthLogic:RecycleScrollOnUpdateByIndex -- Updates slot at specific index in recycle scroll view
IngreSynthLogic:ReturnIngreGradeFromFilterType -- Returns ingredient grade according to filter type
IngreSynthLogic:OnSelectIngreSlot -- Adds ingredient slot to selection list when selected
IngreSynthLogic:OnDeselectIngreSlot -- Removes selected ingredient slot and organizes list
IngreSynthLogic:ResetAllSelectedIngreSlot -- Initializes all selected ingredient slots
IngreSynthLogic:SetMaxSlotCount -- Sets maximum slot count according to filter type
IngreSynthLogic:RefreshSelectedIngreListSlot -- Refreshes selected ingredient list slots
IngreSynthLogic:SetFilterType -- Sets ingredient filter type and adjusts slot count
IngreSynthLogic:CheckNoticePanelState -- Adjusts notice panel and synthesis button state according to selected ingredient count
IngreSynthLogic:SetTagType -- Sets tag type according to tag number and checks notice panel state
IngreSynthLogic:OnClickSynthBtn -- Checks conditions and requests synthesis when synthesis button is clicked
IngreSynthLogic:RequestSynth -- Receives synthesis request from client and executes synthesis on server
IngreSynthLogic:IsChance -- Calculates synthesis great success probability and returns success status
IngreSynthLogic:Synth -- Performs actual ingredient synthesis and gives reward
IngreSynthLogic:ReturnGrade -- Returns synthesis result grade according to filter type
IngreSynthLogic:FinishSynth -- Displays reward UI and returns to initial screen after synthesis completion
IngreSynthLogic:PlaySynthEffect -- Plays synthesis effect and deactivates selection list
IngreSynthLogic:AutoSet -- Automatically selects ingredients to fill slots
IngreSynthLogic:SetStateSynthBtn -- Sets synthesis button activation state and dimming state
IngreSynthLogic:LogIngreSynthResult -- Records ingredient synthesis result as log
IngreSynthLogic:ReturnSelectedListEntityAndOffAnother -- Returns appropriate selection list entity according to slot count
IngreSynthLogic:MakeIngrePool -- Creates synthesis-capable ingredient pool according to filter and tag
IngreSynthLogic:IngreSynthSimul -- Simulates ingredient synthesis multiple times to check results
IngreSynthLogic:ReturnTagTypeString -- Returns corresponding tag type string according to tag number
IngreSynthLogic:CheatLog -- Outputs synthesis result log for debugging
IngreSynthLogic:CountSelectedIngre -- Counts selection count of specific ingredient in selected ingredient list
UIIngreSynthComponent:OnBeginPlay -- Performs UI component initialization and button event registration
UIIngreSynthComponent:OpenUI -- Opens ingredient synthesis UI and pauses game time
UIIngreSynthComponent:CloseUI -- Closes ingredient synthesis UI and resumes game time
UIIngreSynthComponent:EnableNoticePanel -- Activates notice panel and sets text according to situation
UIIngreSynthComponent:EnableFilterList -- Activates filter list and plays first page animation
UIIngreSynthComponent:EnableIngreList -- Activates ingredient list and updates content according to selected filter
UIIngreSynthComponent:SelectFilterType -- Selects filter type and transitions to corresponding screen
UIIngreSynthComponent:OnClickFilterBackBtn -- Returns to initial screen when filter back button is clicked
UIIngreSynthComponent:InitUIFirstPage -- Resets UI to initial state and displays filter selection screen
UIIngreSynthComponent:OnClickClearBtn -- Initializes all selected ingredients when clear button is clicked
UIIngreSynthComponent:OnClickAutoSetBtn -- Automatically selects ingredients when auto set button is clicked
UIIngreSynthComponent:SelectTagBtn -- Selects tag button and updates check state
UIIngreSynthComponent:OnClickSynthBtn -- Forwards synthesis request to logic when synthesis button is clicked
UIIngreSynthComponent:PlayEffect -- Plays synthesis effect and performs different presentation according to great success
UIIngreSynthComponent:SetStateSynthBtn -- Sets synthesis button activation state and dimming state
UIIngreSynthComponent:FirstPageAnim -- Plays animation of filter buttons when entering initial page
UIIngreSynthComponent:SetSynthRecipeIcon -- Sets synthesis recipe icon according to filter type
UIIngreSynthComponent:EnableBtnOnEffectPlaying -- Controls button activation state during effect playback
UIIngreSynthComponent:HandleButtonClickEvent -- Handles close button click event
UIIngreSynthComponent:HandleButtonClickEvent2 -- Handles filter back button click event
UIIngreSynthComponent:HandleButtonClickEvent3 -- Handles clear button click event
UIIngreSynthComponent:HandleButtonClickEvent4 -- Handles auto set button click event
UIIngreSynthComponent:HandleButtonClickEvent5 -- Handles synthesis button click event
UIIngreSynthComponent:HandleButtonClickEvent6 -- Handles UI open button click event
UIIngreSynthListSlot:Init -- Initializes slot UI components
UIIngreSynthListSlot:Refresh -- Updates slot icon and information according to ingredient data
UIIngreSynthListSlot:OnClickSlot -- Adds ingredient to selection list when slot is clicked
UIIngreSynthListSlot:OnClickSelectedSlot -- Updates count when removed from selected slot
UIIngreSynthListSlot:SetCount -- Sets count text according to ingredient quantity and selection state
UIIngreSynthListSlot:ResetCount -- Resets slot count
UIIngreSynthListSlot:HandleButtonClickEvent -- Handles slot button click event
UIIngreSynthSelectedSlot:Refresh -- Updates slot icon and information according to selected ingredient data
UIIngreSynthSelectedSlot:OnClickSlot -- Removes corresponding ingredient from selection list when selected slot is clicked
UIIngreSynthSelectedSlot:InitEmpty -- Initializes slot to empty state
UIIngreSynthSelectedSlot:InitEntity -- Initializes slot UI components
UIIngreSynthSelectedSlot:HandleButtonClickEvent -- Handles selected slot button click event
CheatButtonMacroLogic:AutoClick -- Automatically clicks button multiple times when macro is activated
CheatButtonMacroLogic:HandleButtonClickEvent -- Handles UI button click event and executes auto click
CheatButtonMacroLogic:HandleButtonClickEvent2 -- Handles UI text click event and executes auto click
CheatButtonMacroLogic:HandleButtonClickEvent3 -- Handles UI sprite click event and saves last clicked button
CheatButtonMacroLogic:HandleButtonClickEvent4 -- Handles UI empty element click event and executes auto click
CheatButtonMacroLogic:HandleKeyDownEvent -- Handles F10 key press to toggle macro function
PacketDelayCheckComponent:OnMapEnter -- Sets timer for packet delay check and initializes when entering map
PacketDelayCheckComponent:PacketTimeCheck_Client -- Checks packet time on client and sends response to server
PacketDelayCheckComponent:PacketTimeCheck_Server -- Checks client packet delay time on server and determines pause state
PacketDelayCheckComponent:CheckClientDelayed -- Checks client delay state and manages server-client synchronization status
PacketDelayCheckComponent:PacketDelayCheckLogging -- Records log when packet delay occurs and checks time flow status
PacketDelayCheckComponent:CheckClientPaused -- Returns client pause state
PacketDelayCheckComponent:UpdateReceivedClientPacketTime -- Updates time when packet is received from client
PlayerAdmin:OnBeginPlay -- Checks and sets admin privileges when player enters game
PlayerAdmin:RequestMobileCheatBtnEnable -- Sets activation state of cheat buttons on mobile platform
PlayerAdmin:RequestAdminCheatBtnEnable -- Activates debug UI group and cheat buttons according to admin privileges
PlayerAdmin:VersionTextInit -- Initializes version text and displays current version information
PlayerAdmin:HandleButtonClickEvent -- Handles intro map pass when intro map pass button is clicked
PlayerAdmin:HandleButtonClickEvent2 -- Toggles monitor button set panel when mobile monitor button is clicked
CheatPresetDataLogic:Load -- Loads cheat preset data
CheatPresetDataLogic:GetCheatPresetData -- Gets cheat preset data by test key
CheatPresetDataLogic:GetCheatPresetUpgrade -- Gets cheat preset upgrade data by test key
CheatPresetDataLogic:GetCheatPresetEmployees -- Gets cheat preset employee data by test key
CheatPresetDataLogic:GetManagementLv -- Gets management level by test key
CheatPresetDataLogic:GetUpgradeTypeId -- Gets upgrade type ID by type enum
PlayerCheatComponent:OnBeginPlay -- Sets user ID and registers all cheat commands during cheat component initialization
PlayerCheatComponent:GoCheat -- Executes cheat command
PlayerCheatComponent:SendCheat -- Sends cheat message
PlayerCheatComponent:HasAuthority -- Checks if has cheat authority
PlayerCheatComponent:RegisterCheat -- Registers cheat command
PlayerCheatComponent:GainMeso -- Cheat function to gain meso
PlayerCheatComponent:GainClover -- Cheat function to gain clover
PlayerCheatComponent:GainHeart -- Cheat function to gain heart
PlayerCheatComponent:GainTip -- Cheat function to gain tips
PlayerCheatComponent:GainItem -- Cheat function to gain items
PlayerCheatComponent:GainDropBox -- Cheat function to gain dropboxes
PlayerCheatComponent:ClearAllDB -- Cheat function to clear all databases
PlayerCheatComponent:ClearIngameDB -- Cheat function to clear in-game database
PlayerCheatComponent:ClearInventory -- Cheat function to clear inventory
PlayerCheatComponent:AddTimeSecond -- Cheat function to add time in seconds
PlayerCheatComponent:AddTimeMinute -- Cheat function to add time in minutes
PlayerCheatComponent:OpenWorldShopStorageOperation -- Cheat function to open world shop storage operation
PlayerCheatComponent:SetTrialProgress -- Cheat function to set trial progress
PlayerCheatComponent:SetEveryButtonsUnlock -- Cheat function to unlock all buttons
PlayerCheatComponent:ChangeAchievementProgress -- Cheat function to change achievement progress
PlayerCheatComponent:ChangeTimeFlowDelay -- Cheat function to change time flow delay
PlayerCheatComponent:AddIngredientCard -- Cheat function to add ingredient cards
PlayerCheatComponent:ChangePlayerStoreRanking -- Cheat function to change player store ranking
PlayerCheatComponent:AddEmployee -- Cheat function to add an employee
PlayerCheatComponent:AddAllEmployee -- Cheat function to add all employees
PlayerCheatComponent:RemoveEmployee -- Cheat function to remove an employee
PlayerCheatComponent:ChangeEmployeeLevel -- Cheat function to change employee level
PlayerCheatComponent:CallEvent -- Cheat function to call events
PlayerCheatComponent:ChangeManagementLevel -- Cheat function to change management level
PlayerCheatComponent:ChangeManagementInprogress -- Cheat function to change management progress
PlayerCheatComponent:SubMesoUnderZero -- Cheat function to subtract meso below zero
PlayerCheatComponent:ChangeTrend -- Cheat function to change trends
PlayerCheatComponent:TrainingSkip -- Cheat function to skip training
PlayerCheatComponent:CallRankingEvent -- Cheat function to call ranking events
PlayerCheatComponent:MakeStoreInfoReport -- Cheat function to generate store information reports
PlayerCheatComponent:GainTrainingTicket -- Cheat function to gain training tickets
PlayerCheatComponent:ChangeCustomerSpawnDelay -- Cheat function to change customer spawn delay
PlayerCheatComponent:FindHotPlace -- Cheat function to find hot places
PlayerCheatComponent:StopTimeFlow -- Cheat function to stop/resume time flow
PlayerCheatComponent:SetEnableLobbyHUD -- Cheat function to set lobby HUD enable status
PlayerCheatComponent:SetEnableMoneyBar -- Cheat function to set money bar enable status
PlayerCheatComponent:StartIntroDialog -- Cheat function to start intro dialog
PlayerCheatComponent:StartOutroDialog -- Cheat function to start outro dialog
PlayerCheatComponent:AutoTrainingSkip -- Cheat function to skip auto training
PlayerCheatComponent:SetAttractiveScore -- Cheat function to set attractiveness score
PlayerCheatComponent:ResetAttractiveScore -- Cheat function to reset attractiveness score
PlayerCheatComponent:AllShopCountReset -- Cheat function to reset all shop counts
PlayerCheatComponent:AddMonthlyEarning -- Cheat function to add monthly earnings
PlayerCheatComponent:SetUpgradeLevel -- Cheat function to set upgrade level
PlayerCheatComponent:ChangeReputation -- Cheat function to change reputation
PlayerCheatComponent:OpenVIPOrder -- Cheat function to set conditions for opening VIP orders
PlayerCheatComponent:StartNewVIPOrderSeason -- Cheat function to start a new VIP order season
PlayerCheatComponent:CreateVIPOrderSlotData -- Cheat function to create VIP order slot data
PlayerCheatComponent:SetVIPOrderCompleteCount -- Cheat function to set VIP order completion count
PlayerCheatComponent:SetVIPOrderCount -- Cheat function to set VIP order count
PlayerCheatComponent:SetSkipTutorial -- Cheat function to skip tutorial
PlayerCheatComponent:ClearEventCompleteStatus -- Cheat function to clear event completion status
PlayerCheatComponent:GetExpPotionItemByExpValue -- Cheat function to get experience potion item by experience value
PlayerCheatComponent:TestPresetStart -- Cheat function to start test preset
PlayerCheatComponent:IsValidTestKey -- Function to check if test key is valid
PlayerCheatComponent:TestPresetMapSetting -- Cheat function to apply test preset map settings
PlayerCheatComponent:TestPresetStep1Management -- Cheat function to apply test preset step 1 management settings
PlayerCheatComponent:TestPresetStep2Upgrade -- Cheat function to apply test preset step 2 upgrade settings
PlayerCheatComponent:TestPresetStep3Employee -- Cheat function to apply test preset step 3 employee settings
PlayerCheatComponent:TestPresetStep4Recipe -- Cheat function to apply test preset step 4 recipe settings
PlayerCheatComponent:TestPresetStep5Earning -- Cheat function to apply test preset step 5 earning settings
PlayerCheatComponent:TestPresetAll -- Cheat function to apply all test presets
PlayerCheatComponent:EndEventNow -- Cheat function to immediately end current running events
PlayerCheatComponent:ForceSetEventOccured -- Cheat function to force set event occurrence
PlayerCheatComponent:UnlockEveryUpgrades -- Cheat function to unlock all upgrades
PlayerCheatComponent:ChangeEmployeeLevelAll -- Cheat function to change all employees' levels
PlayerCheatComponent:SetUnofficialTrials -- Cheat function to set unofficial trials
PlayerCheatComponent:SetIsCheatMode -- Function to set cheat mode status
PlayerCheatComponent:GainDiamondFree -- Cheat function to gain free diamonds
PlayerCheatComponent:GainDiamondPaid -- Cheat function to gain paid diamonds
PlayerCheatComponent:SetStageProgress -- Cheat function to set stage progress
PlayerCheatComponent:SetBunSkinCollection -- Cheat function to set bun skin collection
PlayerCheatComponent:AddAllIngredientCards -- Cheat function to add all ingredient cards
PlayerCheatComponent:GainStrategyPointSP -- Cheat function to gain strategy points SP
PlayerCheatComponent:SetSideMenuCollection -- Cheat function to set side menu collection
PlayerCheatComponent:ForceSaveDB -- Cheat function to force save database
PlayerCheatComponent:GainPackage -- Cheat function to gain packages
PlayerCheatComponent:ResetShopItemCount -- Cheat function to reset shop item purchase count
PlayerCheatComponent:StartTrend -- Cheat function to start trends
PlayerCheatComponent:EndTrend -- Cheat function to end trends
PlayerCheatComponent:SetVIPOrderSeasonCompleteScore -- Cheat function to set VIP order season completion score
PlayerCheatComponent:ResetEmployeeEquipCurrency -- Cheat function to reset employee equipment currency
PlayerCheatComponent:ChangeChuchuEquipUgradeLevel -- Cheat function to change ChuChu equipment upgrade level
PlayerCheatComponent:EmployeeEquipUpgradeSimulator1 -- Cheat function to run employee equipment upgrade simulator 1
PlayerCheatComponent:EmployeeEquipUpgradeSimulator2 -- Cheat function to run employee equipment upgrade simulator 2
PlayerCheatComponent:ChangeChuchuCollectionState -- Cheat function to change ChuChu collection state
PlayerCheatComponent:ChangeEmploymentCount -- Cheat function to change employment count
PlayerCheatComponent:ChangeBadgeProgress -- Cheat function to change badge progress
PlayerCheatComponent:GetBadge -- Cheat function to get badges
PlayerCheatComponent:ResetPassPurchaseRecord -- Cheat function to reset pass purchase records
PlayerCheatComponent:ResetPassLevelReward -- Cheat function to reset pass level rewards
PlayerCheatComponent:BuyChuchuEquip -- Cheat function to buy ChuChu equipment
PlayerCheatComponent:BuyChuchuEquipAll -- Cheat function to buy all ChuChu equipment
PlayerCheatComponent:HUDOnOff -- Cheat function to toggle HUD display
PlayerCheatComponent:HUDOnOffClient -- Function to control HUD display from client
PlayerCheatComponent:AddPiggyBankPoint -- Cheat function to add piggy bank points
PlayerCheatComponent:SetPiggyBankLevel -- Cheat function to set piggy bank level
PlayerCheatComponent:PlayDialog -- Cheat function to play dialogs
PlayerCheatComponent:ResetBoosterPackPurchase -- Cheat function to reset booster pack purchases
PlayerCheatComponent:AddRecipe -- Cheat function to add recipes
PlayerCheatComponent:ClearStoreInfoReport -- Cheat function to clear store information reports
PlayerCheatComponent:LaunchingEventChangeDay -- Cheat function to change launching event day
PlayerCheatComponent:LaunchingEventReset -- Cheat function to reset launching events
PlayerCheatComponent:ChangeOfflineRewardTime -- Cheat function to change offline reward time
PlayerCheatComponent:SetDropdownTestTimer -- Cheat function to set dropdown test timer
PlayerCheatComponent:AddRecipeGrade -- Cheat function to add recipe grades
PlayerCheatComponent:SetFreeDiamondForceMinus -- Cheat function to force set free diamonds to negative
PlayerCheatComponent:EnableForceDelayFlag -- Cheat function to enable force delay flag
PlayerCheatComponent:SetIngreSynthGreatSuccessProb -- Cheat function to set ingredient synthesis great success probability
PlayerCheatComponent:RemoveAllIngredientCards -- Cheat function to remove all ingredient cards
PlayerCheatComponent:Achievement_ProgressFull -- Cheat function to set all achievement progress to complete
PlayerCheatComponent:Achievement_AchieveFull -- Cheat function to set all achievements to achieved status
PlayerCheatComponent:Achievement_CompleteFull -- Cheat function to set all achievements to complete status
PlayerCheatComponent:SetStoreUpgradeLevel -- Cheat function to set store upgrade level
PlayerCheatComponent:IngreSynthSimulator -- Cheat function to run ingredient synthesis simulator
PlayerCheatComponent:HandleChatBalloonEvent -- Handler to process chat balloon events
UICheat:FindCommand -- Finds and displays cheat commands that match the input
UICheat:OnBeginPlay -- Initializes cheat UI and connects events
UICheat:OnTextInputValueChanged -- Performs command search when text input changes
UICheat:OnTextInputSumit -- Sends cheat command when enter key is pressed
UICheat:SetCommand -- Sets command in input field and activates it
UICheat:GetOrCreateCommandRenderer -- Gets existing command renderer entity or creates new one
UICheat:ClearCommandRenderer -- Deactivates all command renderers
UICheat:ToggleUI -- Toggles cheat UI to show or hide
UICheat:HandleKeyDownEvent -- Handler to process key input events
UICheat:HandleButtonClickEvent -- Handler to process button click events
UICheatCommandRenderer:OnBeginPlay -- Initializes cheat command renderer UI elements
UICheatCommandRenderer:Set -- Sets command and description in UI
UICheatCommandRenderer:HandleButtonClickEvent -- Sets command in input field when command renderer button is clicked
DebugMonitorSpawnPool:OnBeginPlay -- Initializes spawn pool monitor UI elements
DebugMonitorSpawnPool:UpdateMonitor -- Reads customer spawn pool data and displays it in monitor UI
DebugMonitorSpawnPool:PageChange -- Changes spawn pool data page to move to next/previous page
DebugMonitorSpawnPool:ResetButtonHilight -- Changes refresh button color to yellow to indicate update needed status
DebugMonitorUICustomer:OnBeginPlay -- Initializes customer debug monitor UI and sets data
DebugMonitorUICustomer:SetSelectedCustomer -- Sets selected customer entity and updates monitor information
DebugMonitorUICustomer:SetUiSpawnTableInfo -- Sets customer spawn table information in UI
DebugMonitorUICustomer:SetUiMapInfo -- Sets customer map-related information in UI
DebugMonitorUICustomer:SetUiAiScriptInfo -- Sets customer AI script information in UI
DebugMonitorUICustomer:UpdateWaitingTime -- Updates customer waiting time in real-time
DebugMonitorUIEmployee:UpdateEmpDebugInfo -- Updates employee debug information and displays it in UI
DebugMonitorUIEmployee:ChangeLocation -- Changes employee location and updates layout
DebugMonitorUIEmployee:TotalDurationSet -- Function to set employee total work time
DebugMonitorUIEmployee:WorkDurationSet -- Function to set employee work time
DebugMonitorUIEmployee:LevelSet -- Function to set level
DebugMonitorUIEmployee:HandleButtonClickEvent -- Handler to process button click events
DebugMonitorUIMaintain:Calcost -- Calculates maintenance costs and displays them categorized by each item
DebugMonitorUIMaintain:UpdateUI -- Function to update UI
DebugMonitorUIStore:OnBeginPlay -- Initializes debug monitor store information UI and sets data
DebugMonitorUIStore:SetUiManagementInfo -- Sets management information in UI (management level, earning level, attractiveness requirements, etc.)
DebugMonitorUIStore:SetAttractiveInfo -- Sets store attractiveness information in UI (expansion, interior, decoration, recipes)
DebugMonitorUIStore:SetReputationInfo -- Sets reputation information in UI (reputation score, spawn delay time)
DebugMonitorUIStore:SetReputationChangeByReview -- Sets reputation change by reviews as monthly cumulative values
DebugMonitorUIStore:SetReputationChangeByContents -- Sets reputation change by contents as monthly cumulative values
DebugMonitorUIStore:ResetReputationChangeByReview -- Resets all monthly reputation change cumulative values
DebugMonitorUIStore:SetPiggyBankInfo -- Sets piggy bank information in UI (earnings to next level, additional points)
DebugMonitorUIStore:HandlePlayerManagementChangedEvent -- Processes player management level change events
DebugMonitorUIStore:HandleEarningLevelChangedEvent -- Processes earning level change events
DebugMonitorUIStore:HandlePlayerReputationChangedEvent -- Processes player reputation change events
PlayerDebugMonitor:OnBeginPlay -- Enables debug monitor group and sets initial state
PlayerDebugMonitor:SpawnUIMonitorEntity -- Creates all debug monitor UI entities and sets positions
PlayerDebugMonitor:EnableStoreInfoMonitor -- Enables/disables store information monitor and updates related information
PlayerDebugMonitor:EnableCustomerInfoMonitor -- Enables/disables customer information monitor and updates information
PlayerDebugMonitor:UpdateCustomerInfoMonitor -- Updates customer information monitor display status based on customer ID
PlayerDebugMonitor:EnableRecipeInfoMonitor -- Enables/disables recipe information monitors
PlayerDebugMonitor:UpdateDebugMonitorAttractive -- Updates store attractiveness information
PlayerDebugMonitor:ResetDebugMonitorMonthlyReputation -- Resets monthly reputation changes
PlayerDebugMonitor:UpdateDebugMonitorReputationChangeByContents -- Updates reputation changes by contents
PlayerDebugMonitor:UpdateDebugMonitorRecipeMaking -- Updates recipe making monitor information based on key
PlayerDebugMonitor:EnableEmployeeInfoMonitor -- Enables/disables employee information monitor and updates information
PlayerDebugMonitor:EnableMaintainInfoMonitor -- Enables maintenance information monitor and calculates costs
PlayerDebugMonitor:UpdateMonitor -- Updates all monitor information
PlayerDebugMonitor:UpdatePiggyBankInfo -- Updates piggy bank information
PlayerDebugMonitor:EnableSpawnPoolMonitor -- Enables spawn pool monitor and updates data
PlayerDebugMonitor:HandleKeyDownEvent -- Processes keyboard input events to toggle various debug monitors
SpawnPoolBtn:HandleButtonClickEvent -- Processes spawn pool monitor button click events by type
UIRecipeDebug:OnBeginPlay -- Initializes recipe debug UI and connects button events
UIRecipeDebug:OpenTab -- Opens specified tab and refreshes corresponding information
UIRecipeDebug:RefreshMakingText -- Refreshes recipe making information (balance, spiciness, taste score, price)
UIRecipeDebug:RefreshResultText -- Refreshes recipe result information (tags, combos, bread bonus, balance bonus)
DebugTimer:OnUpdate -- Updates elapsed time every frame when timer is running
DebugTimer:UpdateUI -- Updates timer UI and automatically stops when reserved time is reached
DebugTimer:ToggleStartPuase -- Toggles timer start/stop state and controls in-game time flow
DebugTimer:TimerReset -- Resets timer and clears all records and reservations
DebugTimer:TimeRecord -- Records current time and adds new record item to UI
DebugTimer:Reserve -- Sets timer auto-stop reservation according to specified duration
DebugTimer:Init -- Initializes debug timer UI and reservation buttons
DebugTimer:TimeFlow -- Controls in-game time flow
DebugTimer:UpdateTime -- Updates in-game date information
DebugTimer:OnBeginPlay -- Finds and connects UI elements during component initialization and sets 31-day month information
DebugTimer:HandleButtonClickEvent -- Processes main timer start/stop button click events
DebugTimer:HandleButtonClickEvent2 -- Processes simple timer start/stop button click events
DebugTimer:HandleButtonClickEvent4 -- Processes timer reset button click events
DebugTimer:HandleButtonClickEvent3 -- Processes main timer time record button click events
DebugTimer:HandleButtonClickEvent9 -- Processes simple timer time record button click events
DebugTimer:HandleButtonClickEvent5 -- Processes button click events to switch to simple timer mode
DebugTimer:HandleButtonClickEvent6 -- Processes button click events to switch to main timer mode
DebugTimer:HandleButtonClickEvent7 -- Processes button click events to toggle reservation UI panel
DebugTimer:HandleButtonClickEvent8 -- Processes click events for reservation period selection buttons
BGMService:ApplyBGM -- Applies and plays specified BGM to current map
BGMService:ApplySpotBGM -- Finds and applies BGM for the spot from spot data
BGMService:StopBGM -- Stops currently playing BGM
BGMService:ResumeBGM -- Resumes stopped BGM
BGMService:ApplyLobbyBGM -- Applies lobby BGM matching current stage
CheckProhibitedWordLogic:IsProhibitedWordUsingAPI -- Uses API to check for prohibited words and performs special character inspection
CheckProhibitedWordLogic:ContainsSpecialCharacter -- Checks if text contains disallowed special characters
CheckProhibitedWordLogic:HandleTextInputEndEditEditorEvent -- Processes text input completion editor events
ColorCodeEnum:OnBeginPlay -- Initializes color code table on game start
ColorCodeEnum:GetColor -- Returns color object from hex code and stores in cache
DateTimeLogic:GetUtcNow -- Returns current UTC time plus elapsed time
DateTimeLogic:AddTime -- Adds debug time and sends change events
DateTimeLogic:ClearAddTime -- Clears added debug time
DateTimeLogic:GetUtcNowElapsed -- Returns elapsed time of current UTC time in milliseconds
DateTimeLogic:ChangeElapsedToString -- Converts elapsed time to hour:minute:second format string
DateTimeLogic:GetUtc9Elapsed -- Returns elapsed time in UTC+9 timezone
DateTimeLogic:GetUtcNowText -- Returns current UTC time as RFC3339 format string
DBUtilLogic:GetNumberByTable -- Gets numeric value for key from table and returns default if missing
DBUtilLogic:GetStringByTable -- Gets string value for key from table and returns default if missing
DBUtilLogic:IsEmpty -- Checks if table is empty or nil
DBUtilLogic:SerializeAttendTable -- Serializes attendance information table to string (not implemented)
DBUtilLogic:DeserializeAttendTable -- Deserializes string to attendance information table (not implemented)
EditorLogic:HandleButtonClickEditorEvent -- Sets all text fonts in UI group to default when editor button is clicked
EditorLogic:HandleButtonClickEditorEvent2 -- Removes specific entity when second editor button is clicked
FadeService:ShowFade -- Displays fade in effect and executes specified sub function
FadeService:HideFade -- Executes fade out effect to restore screen to original state
GetConfigDataLogic:GetConfigNumDataByKey -- Returns numeric data corresponding to configuration key
GetConfigDataLogic:OnBeginPlay -- Loads configuration data on game start and sets values to various managers
IconRuidEnum:GetSkillTypeIcon -- Returns icon RUID based on skill type
IconRuidEnum:GetComboCountRUID -- Returns numeric icon RUID corresponding to combo count
IconRuidEnum:GetEffectRUIDByGrade -- Returns effect RUID based on grade
IconRuidEnum:GetOverLimitJemIcon -- Returns over limit gem icon RUID based on employee type
IconRuidEnum:GetAutoTrainingIcon -- Returns auto training icon RUID based on index
IconRuidEnum:GetMaterialEntryId -- Returns entry ID corresponding to material ID
MathUtilLogic:Vector3AlmostEquals -- Compares two Vector3 coordinates to check if they are almost equal and returns boolean
NickNameLogic:IsValid -- Validates nickname text and returns result message
NickNameLogic:CodePointToLen -- Converts unicode codepoint to character length
NickNameLogic:IsWhitespaceOnly -- Checks if text consists only of whitespace characters
NickNameLogic:IsWhitespaceCodepoint -- Checks if codepoint is a whitespace character
NickNameLogic:HandleTextInputEndEditEditorEvent -- Processes text input completion editor events
RandomLogic:RandomInteger -- Generates random integer based on seed
RandomLogic:RandomDouble -- Generates random real number between 0 and 1
RandomLogic:RandomIntegerRange -- Generates random integer within specified range
RandomLogic:NextSeed -- Sets next seed value from seed table
RandomLogic:GetRandomDouble -- Returns random real number using seed
RandomLogic:GetRandomDoubles -- Returns array of specified number of random real numbers
RandomLogic:GetRandomRange -- Returns random integer within range using seed
RandomLogic:ReturnRandomPickWeight -- Returns randomly selected index based on weight table
RandomLogic:ReturnIsDropProb100 -- Determines drop success based on probability value
RandomLogic:RandomIntegersInRange -- Returns randomly shuffled array of integers in specified range
ResourceManager:OnBeginPlay -- Loads SFX table and preloads resources on game start
ResourceManager:ChangeMaterial -- Changes entity material and restores to original after specified time
StringUtilLogic:ReturnThousandsSeparatedString -- Converts integer to thousands-separated string
StringUtilLogic:ReturnOriginString -- Removes commas from string to restore original number string
StringUtilLogic:ParseItemsStringToItemTable -- Parses item string to convert to item table
StringUtilLogic:ConvertIntToStringWithBigNumber -- Converts large numbers to abbreviated string format
StringUtilLogic:GetDurationTimeString -- Converts duration to localized hour:minute:second format string
StringUtilLogic:ParseTimeStringToDateTimeElpased -- Parses time string to DateTime elapsed time
StringUtilLogic:ShuffleStringTable -- Returns string table with randomly shuffled order
StringUtilLogic:FormatNumber -- Formats numbers with K, M, B unit abbreviations
StringUtilLogic:NumToString -- Converts number to integer then returns as string
StringUtilLogic:StringToInt -- Converts string to integer and returns
StringUtilLogic:GetBoolByString -- Converts string to boolean value and returns default if failed
StringUtilLogic:GetSyncTableVStr -- Converts sync table values to comma-separated string
StringUtilLogic:get_utc_time_rfc3339_format -- Converts UTC time to RFC3339 format string
StringUtilLogic:IntBoolToString -- Converts integer-boolean table to comma-separated string
StringUtilLogic:IntIntToString -- Converts integer-integer table to comma-separated string
StringUtilLogic:IntBoolToTable -- Converts comma-separated string to integer-boolean table
StringUtilLogic:IntIntToTable -- Converts comma-separated string to integer-integer table
StringUtilLogic:StringBoolToString -- Converts string-boolean table to comma-separated string
StringUtilLogic:StringBoolToTable -- Converts comma-separated string to string-boolean table
StringUtilLogic:OrdinalFormatter -- Adds ordinal suffixes (st, nd, rd, th) to numbers for string formatting
StringUtilLogic:HandleKeyDownEvent -- Processes key input events
UIMoneyBarLogic:OnBeginPlay -- Gets and sets UI icons from data table on game start
UIMoneyBarLogic:UpdateCloverUI -- Updates clover UI value
UIMoneyBarLogic:UpdateMoneyUI -- Updates money UI value
UIMoneyBarLogic:UpdateHeartUI -- Updates heart UI value
UIMoneyBarLogic:UpdateDiamondUI -- Updates diamond UI value
UIMoneyBarLogic:EnableOnlyDiamondUI -- Enables only diamond UI and disables other UIs
UIMoneyBarLogic:EnableDiamondInfoButton -- Sets enable status of diamond information button
UIMoneyBarLogic:HandlePlayerMoneyChangedEvent -- Processes player money change events
UIMoneyBarLogic:HandlePlayerArcaneSymbolChangedEvent -- Processes player arcane symbol (clover) change events
UIMoneyBarLogic:HandlePlayerHeartChangedEvent -- Processes player heart change events
UIMoneyBarLogic:HandlePlayerDiamondChangedEvent -- Processes player diamond change events
UIMoneyBarLogic:HandleButtonClickEvent -- Opens diamond information popup when diamond UI is clicked
UIMoneyBarLogic:HandleButtonClickEvent2 -- Displays tooltip when diamond information button is clicked
AchievementDataSetLogic:OnBeginPlay -- Loads achievement dataset on game start
AchievementDataSetLogic:LoadDataSet -- Loads achievement type and ID data from CSV files and stores in tables
AchievementDataSetLogic:GetAchievementTypeData -- Returns achievement type data by achievement type ID
AchievementDataSetLogic:GetAchievementIdData -- Returns achievement ID data by achievement ID
AchievementIdData:Load -- Loads achievement ID data from CSV data table and stores in properties
AchievementLogic:CheckAchievementAchieved -- Checks and updates player achievement completion status
AchievementLogic:ReturnInitialTypeValue -- Returns initial value for achievement type
AchievementLogic:ReturnAchievementNameText -- Returns localized achievement name text
AchievementLogic:ReturnAchievementDescText -- Returns localized achievement description text
AchievementLogic:ReturnConvertedTypeValue -- Converts and returns value to appropriate format based on achievement type
AchievementLogic:GetFixedTypeValue -- Calculates achievement target value with stage-specific correction values applied
AchievementTypeData:Load -- Loads achievement type data from CSV data table and stores in properties
UIAchievement:OnBeginPlay -- Initializes UI and sets up tab buttons and close button events
UIAchievement:Open -- Opens achievement UI and selects tab with completed achievements as default
UIAchievement:Close -- Closes achievement UI
UIAchievement:OnGetAllRewardButtonClicked -- Processes when get all rewards button is clicked
UIAchievement:GetAchiTypesByTab -- Returns sorted list of achievement types for selected tab
UIAchievement:SetSelectTab -- Updates UI state when tab is selected and displays achievement list
UIAchievement:OnSelectTab -- Applies visual effects based on tab selection state
UIAchievement:Apply -- Categorizes and sorts achievements in selected tab by completion status and displays in UI
UIAchievement:ClearSlots -- Clears all achievement slots
UIAchievement:GetTabTitle -- Returns localized tab title for tab index
UIAchievement:HandleButtonClickEvent -- Processes achievement button click events
UIAchievementSlotRenderer:OnBeginPlay -- Initializes UI components and sets up reward button events
UIAchievementSlotRenderer:Init -- Initializes achievement slot with specific achievement type and sets reward information
UIAchievementSlotRenderer:Clear -- Initializes and deactivates achievement slot
UIAchievementSlotRenderer:RefreshGauge -- Updates achievement progress gauge and text to current state
UIAchievementSlotRenderer:RefreshComplete -- Updates UI display based on achievement completion status
BalanceDataSetLogic:OnBeginPlay -- Loads balance dataset on game start
BalanceDataSetLogic:LoadDataSet -- Loads stage configuration data and store attractiveness level data
BalanceDataSetLogic:SetEarningLevelByEarningRecord -- Sets earning level based on player's earning records
BalanceDataSetLogic:GetStageConfigData -- Returns configuration data for stage ID
BalanceDataSetLogic:GetStoreAttractiveLevelData -- Returns store attractiveness data for attractiveness level
BalanceDataSetLogic:HandlePlayerManagementChangedEvent -- Recalculates earning level when player management information changes
StageEarningLevelData:Load -- Loads stage earning level information from data table
StoreAttractiveLevelData:Load -- Loads store attractiveness level information from data table
ChatMessageComponent:SetIndex -- Sets chat message index
ChatMessageComponent:InitChatInfo -- Initializes chat information and sets index
CustomChatLogic:OnBeginPlay -- Initializes chat queue on server start and sets message broadcast timer
CustomChatLogic:RequestChat -- Processes chat message requests from clients and distributes messages according to appropriate chat type
CustomChatLogic:OnGetMessage -- Parses chat message data received from server and sends as events
CustomChatLogic:ReplaceNonSpaceWithAsterisk -- Replaces prohibited words with asterisks (*) while preserving spaces
CustomChatLogic:AddSystemMessage -- Generates system messages on client and displays them in chat window
CustomChatLogic:GetTypeByMessage -- Analyzes message content to determine chat type (normal, whisper, party, megaphone)
CustomChatLogic:StartsWith -- Checks if string starts with specific prefix
CustomChatLogic:SendMegaphone -- Broadcasts megaphone messages to all world instances
CustomChatLogic:RefreshMsg -- Updates text and icons to display chat messages in UI entities
CustomChatLogic:OnEndPlay -- Cleans up chat timer on server shutdown
CustomChatLogic:AddToChatData -- Stores chat data for reporting and maintains maximum count
CustomChatLogic:ReportChatMessage -- Processes reporting of chat message at specific index
CustomChatLogic:ReportChatToClient -- Processes reported chat messages from client (excludes self)
CustomChatLogic:RefreshChatBannedStatusClient -- Changes input field enable status based on chat ban status
CustomChatLogic:HandleUserEnterEvent -- Sends cached chat messages when user enters
CustomChatLogic:HandleOnGetChatMessage -- Adds chat messages received from other world instances to queue
OnGetChatMessage:Init -- Function to initialize chat message data
OnReportedCustomChat:Init -- Function to initialize reported chat data
ReportChatType:Init -- Initializes chat data for reporting
UICustomChat:OnBeginPlay -- Initializes chat UI and sets up event connections
UICustomChat:OnSumitMessage -- Processes input chat messages and sends them with appropriate chat type
UICustomChat:SetWhisper -- Sets input field to whisper mode
UICustomChat:Refresh -- Refreshes chat list and maintains scroll position
UICustomChat:ActivateInputField -- Activates chat input field and opens chat window
UICustomChat:OnTextInputEndEdit -- Deselects selection state when input ends
UICustomChat:OnActivateInputField -- Sets selection state when input field is activated
UICustomChat:RefreshFoldMsg -- Updates last message to be displayed in folded chat window
UICustomChat:ClearChatTextMaterial -- Cleans up material effects from chat text
UICustomChat:HandleOnGetChatMessage -- Receives chat messages, adds them to UI, and displays chat balloons
UICustomChat:HandleKeyUpEvent -- Activates chat input field when enter key is pressed
UICustomChatHolder:OnBeginPlay -- Sets chat window to hidden state during initialization
UICustomChatHolder:ToggleCustomChat -- Toggles chat window expand/collapse state
UICustomChatHolder:HandleButtonClickEvent -- Processes chat window open button click events
UICustomChatHolder:HandleButtonClickEvent2 -- Processes chat window close button click events
RandomBox:AddItem -- Adds item with weight and value to random box
RandomBox:Pick -- Randomly selects and returns item based on weight
RandomBox:FindMaxValueLessThanOrEqual -- Uses binary search to find and return maximum value less than or equal to target
RandomBox:RemoveItem -- Removes items with specified value and returns removed weight
WeightRandomBox:Add -- Adds item and weight and sets dirty flag
WeightRandomBox:Remove -- Removes specified item and sets dirty flag
WeightRandomBox:Pick -- Randomly selects and returns item based on weight
WeightRandomBox:CalculateSum -- Recalculates total weight sum only when dirty flag is set
WeightRandomBox:GetPickItem -- Finds and returns item to be selected based on random value
WeightRandomBox:GetTotalWeight -- Calculates and returns total weight sum
IngredientGachaDataLogic:OnBeginPlay -- Loads ingredient gacha dataset on game start
IngredientGachaDataLogic:LoadDataSet -- Loads ingredient gacha random box data from CSV files and stores in memory
IngredientGachaDataLogic:ReturnMultiCountByGachaId -- Returns multi-draw count by gacha ID (BN: 3, IN: 5)
IngredientGachaDataLogic:GetIngreGachaRandomBoxData -- Queries and returns ingredient gacha random box data by ID
IngreGachaRandomBoxData:Load -- Loads gacha box data from CSV data table and sets grade-based weights
IngreGachaRandomBoxData:Pick -- Receives player and count, randomly selects ingredient/bread items based on weight and returns
IngreGachaRandomBoxData:GetGachaPool -- Creates gacha pool by filtering only items of specified grade from original pool
UIIngreGacha:Open -- Opens ingredient gacha UI and activates recipe group if needed
UIIngreGacha:Close -- Closes ingredient gacha UI and cleans up related UI state
UIIngreGacha:Refresh -- Refreshes gacha slots and updates UI with item data
UIIngreGacha:OnBeginPlay -- Refreshes UI when component starts
UIIngreGacha:HandleButtonClickEvent -- Handler to close ingredient gacha UI when close button is clicked
UIIngreGacha:HandleButtonClickEvent2 -- Handler to fully open UI when ingredient gacha view all button is clicked
UIIngreGacha:HandleButtonClickEvent3 -- Handler to close ingredient gacha UI when background is clicked
UIIngreGacha:HandleButtonClickEvent4 -- Handler to open collection UI when ingredient-bun collection button is clicked
UIIngreGachaItemRenderer:Init -- Initializes UI elements and sets button text
UIIngreGachaItemRenderer:Refresh -- Refreshes gacha item UI with item ID and connects events
UIIngreGachaItemRenderer:RefreshCountText -- Updates button enable status and text color based on item quantity
UIIngreGachaItemRenderer:OnBeginPlay -- Disables ingredient gacha red dot when component starts
UIIngreGachaItemRenderer:HandlePlayerInventoryItemChangedEvent -- Updates quantity text when player inventory item changes
DropBoxLogic:OpenDropBox -- Method to probabilistically grant items based on dropbox ID
DropBoxLogic:AddItem -- Method to add items to player inventory
DropBoxLogic:CheckLogic -- Debug method to test dropbox probability logic
ItemData:Load -- Method to load item information from data table
ItemData:GetUseItems_List -- Method to return use item information in list format
ItemData:GetUseItems_Dictinary -- Method to return use item information in dictionary format
ItemData:GetUseItems_ItemId_Pair -- Method to return use item information paired with item ID
ItemDataSetLogic:OnBeginPlay -- Method to load item dataset on game start
ItemDataSetLogic:LoadDataSet -- Method to load item data from CSV files and preload icons
ItemDataSetLogic:GetItemData -- Method to query item data by item ID
ItemDataSetLogic:ReturnPotionIdsByStatType -- Method to return potion item ID list based on stat type
ItemDataSetLogic:ReturnPotionStatTypeDataIndex -- Method to convert stat type to data index
ItemDataSetLogic:ReturnItemRuidFromId -- Method to query icon RUID by item ID
PlayerArcaneSymbolChangedEvent:Init -- Method to initialize player arcane symbol change events
PlayerHeartChangedEvent:Init -- Method to initialize player heart change events
PlayerMoneyChangedEvent:Init -- Method to initialize player money change events
PlayerReputationChangedEvent:Init -- Method to initialize player reputation change events
PlayerTipChangedEvent:Init -- Method to initialize player tip change events
PlayerTrainingTokenChangedEvent:Init -- Method to initialize player training token change events
BtnEnableControllerByLocale:OnBeginPlay -- Checks if current locale is Korean and sets button enable status
GetLocalizationTextLogic:OnBeginPlay -- Loads localization reference key table and stores in ReferKeys array on game start
GetLocalizationTextLogic:GetText -- Returns translated text for current locale
GetLocalizationTextLogic:MakeLocalizeDataText -- Generates localized data text based on text key and handles formatting
GetLocalizationTextLogic:IsReferKey -- Checks if given string is a reference key and returns boolean value
GetLocalizationTextLogic:GetReferKeyText -- Returns actual text value for reference key (player name, store name, etc.)
GetLocalizationTextLogic:CallToastByLocalizationKey -- Displays toast message using localization key
GetLocalizationTextLogic:RequestSetLocalizedTextServer -- Requests server to set localized text and constructs supported locale list
GetLocalizationTextLogic:SetLocalizedTextServer -- Sets localized text data and player's current locale ID on server
GetLocalizationTextLogic:GetLocalizedTextServer -- Returns localized text for specific locale ID and key on server
LocalizedTextServer:GetText -- Returns localized text for specified locale ID
TextManager:GetText -- Returns input string as-is
TextManager:GetSmartText -- Returns smart formatted text using one argument
TextManager:GetSmartText2 -- Returns smart formatted text using two arguments
TextManager:GetSmartText3 -- Returns smart formatted text using three arguments
TextManager:GetSmartText4 -- Returns smart formatted text using four arguments
TextManager:GetHexCode -- Returns hex color code for color name
LocalizedTextComponent:OnBeginPlay -- Sets font size if auto setting is enabled when component starts
LocalizedTextComponent:SetFontSize -- Adjusts text component font size based on current locale
LocalizedTextInputComponent:OnBeginPlay -- Sets character limit if auto setting is enabled when component starts
LocalizedTextInputComponent:SetCharacterLimit -- Adjusts text input component character limit based on current locale
MainMenuBtnData:Load -- Loads menu button information from data table and sets in properties
MainMenuBtnData:ReturnCategoryRUID -- Returns corresponding category icon RUID based on category number
MainMenuDataSetLogic:OnBeginPlay -- Loads main menu dataset when logic starts
MainMenuDataSetLogic:LoadDataSet -- Reads main menu button data from CSV and stores in table
MainMenuDataSetLogic:GetMenuBtnData -- Queries and returns main menu button data by ID
MainMenuDataSetLogic:ClearMenuBtnChild -- Disables click guide UI for all menu buttons
MainMenuDataSetLogic:SetClickHereOnMenuBtn -- Creates and sets click guide arrow UI for specific menu button
MainMenuRedDotManager:OnBeginPlay -- Finds and stores all menu button red dot UIs in array when logic starts
MainMenuRedDotManager:SetMenuBtnRedDot -- Checks red dot status for all menu buttons and determines main menu button red dot display
MainMenuRedDotManager:EnableTrialRedDot -- Sets trial menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableShopRedDot -- Sets shop menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableUpgradeRedDot -- Sets upgrade menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableAchievementRedDot -- Sets achievement menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableIngreGachaRedDot -- Sets ingredient gacha menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableEmploymentRedDot -- Sets employment menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableTrainingRedDot -- Sets training menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableAutoTrainingRedDot -- Sets auto training menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableEmployeeManageRedDot -- Sets employee management menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableRecipeRedDot -- Sets recipe menu button red dot by comparing player's upgrade slot count with set recipe count
MainMenuRedDotManager:EnableVIPOrderRedDot -- Sets VIP order menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableIngreBunCollectionRedDot -- Sets ingredient-bun collection menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableChuchuCollectionRedDot -- Sets ChuChu collection menu button red dot display status and updates main menu red dot
MainMenuRedDotManager:EnableRankingRedDot -- Sets ranking menu button red dot display status and updates main menu red dot
SelectDropDownLogic:SetSelected -- Sets visual style based on dropdown item selection status
SelectDropDownLogic:SetIconInfo -- Sets dropdown item icon image
SelectDropDownLogic:SetTextInfo -- Sets dropdown item text
SelectDropDownLogic:RefreshSelected -- Sets only item with specified key among dropdown items to selected status
TooltipService:OpenTooltip -- Opens basic tooltip, sets text, and sets as current tooltip
TooltipService:CloseTooltip -- Closes tooltip and initializes related state
TooltipService:OpenTooltipWithPadding -- Opens tooltip for item descriptions positioned with padding for display
TooltipService:ShowHUDMoneyBarToolTip -- Displays tooltip dedicated to HUD money bar
TooltipService:HandleScreenTouchEvent -- Closes open tooltip when screen touch event occurs
TooltipService:HandleMouseScrollEvent -- Closes tooltip when mouse scroll event occurs if scrolling is in use
UIButtonTypeA:SetText -- Sets text to be displayed on button
UIButtonTypeA:SetEnable -- Sets button enable status to control Disabled overlay
UIButtonTypeA:OnBeginPlay -- References button entities and connects events during component initialization
UIButtonTypeA:OnClickButton -- Processes button click events and calls external callback functions
UIButtonTypeA:OnButtonStateChange -- Processes button state change events and calls external callback functions
UICurrencyToolTipComponent:OnBeginPlay -- Finds tooltip entity during component initialization and sets data
UICurrencyToolTipComponent:SetData -- Sets tooltip data based on item ID and updates text
UICurrencyToolTipComponent:HandleButtonClickEvent -- Checks tooltip data when button is clicked and displays tooltip
UIEntityService:PlayUISpriteAnim -- Plays UI sprite animation for specified time and automatically deactivates
UIEntityService:GetOrCreateEntityOfModel -- Finds or creates new entity by model name and index and returns
UIEntityService:PlayMoveBounceTween -- Plays bounce tween animation that moves entity to random position
UIEntityService:MakeStarIconForTasteScore -- Creates star icons based on taste score and applies tween effects
UIEntityService:TweenAndFade -- Moves entity to specified position while simultaneously applying fade in/out effects
UIEntityService:GetOrCreateClonedEntityByName -- Finds entity by name or clones original to create new one and returns
UIEntityService:PlayPopFadeTween -- Plays tween animation that pops up to random position and fades out
UIEntityService:SetDimWithIcon -- Sets entity Dim effect, icon Dim, and text color
UIEntityService:PlayMoneyPopFade -- Creates coin icons based on amount and applies pop-fade effects
UIEntityService:PlayUIOpenAnim -- Plays UI entity open animation with delay time
UIEntityService:ClearUIOpenAnim -- Stops entity UI open animation and clears related data
UIGaugeBar:SetGauge -- Sets gauge current value and refreshes UI
UIGaugeBar:OnBeginPlay -- Finds and sets references to gauge-related entities during component initialization
UIGaugeBar:SetMaxValue -- Sets gauge maximum value
UIGaugeBar:SetTextFormat -- Sets format string to be used for gauge text
UIGaugeBar:Refresh -- Updates gauge visual display and text based on current value
UIGaugeBar:SetText -- Directly sets gauge text
UIGroupManager:IsOnUI -- Checks if any UI group is activated and returns result
UIGroupManager:IsOnLobby -- Checks if in lobby state (includes event check option)
UIGroupManager:ClearAllUI -- Sequentially closes and cleans up all open UIs
UIGroupManager:EnableMoneyBarGroup -- Function to set money bar group enable status
UIGroupManager:EnableBackToLobbyBtn -- Function to set back to lobby button enable status
UIGroupManager:OnBeginPlay -- Function executed during UI group manager initialization
UIGroupManager:IsEnableOpenPopUp -- Function to check if popup can be opened
UIGroupManager:EnableRecipeGroup -- Function to set recipe group enable status
UIGroupManager:EnableRewardGroup -- Function to set reward group enable status
UIGroupManager:EnableAchievementGroup -- Function to set achievement group enable status
UIGroupManager:EnableEventGroup -- Function to set event group enable status
UIGroupManager:EnableManagementGroup -- Function to set management group enable status
UIGroupManager:EnableTrialGroup -- Function to set trial group enable status
UIGroupManager:EnableRecipeSetGroup -- Function to set recipe set group enable status
UIGroupManager:EnableUpgradeGroup -- Function to set upgrade group enable status
UIGroupManager:EnableVIPOrderGroup -- Function to set VIP order group enable status
UIGroupManager:EnableStoreRankingGroup -- Function to set store ranking group enable status
UIGroupManager:EnableStoreInfoGroup -- Function to set store info group enable status
UIGroupManager:EnableTutorialGroup -- Function to set tutorial group enable status
UIGroupManager:SetEnableMainMenuPanel -- Function to set main menu panel enable status
UIGroupManager:EnableReputationRewardGroup -- Function to set reputation reward group enable status
UIGroupManager:EnableStageInfoGroup -- Function to set stage info group enable status
UIGroupManager:EnableToastLobbyGroup -- Function to set toast lobby group enable status
UIGroupManager:EnableIngreBunCollectionGroup -- Function to set ingredient-bun collection group enable status
UIGroupManager:EnableChuchuCollectionGroup -- Function to set ChuChu collection group enable status
UIGroupManager:EnableStageClearRewardGroup -- Function to set stage clear reward group enable status
UIGroupManager:EnableSpecialShopGroup -- Function to set special shop group enable status
UIGroupManager:EnableStagePassGroup -- Function to set stage pass group enable status
UIGroupManager:EnableSelectChuchuInCollection -- Function to set ChuChu selection UI enable status in collection
UIGroupManager:EnableBadgeGroup -- Function to set badge group enable status
UIGroupManager:EnablePiggyBankGroup -- Function to set piggy bank group enable status
UIGroupManager:EnableBoosterPackGroup -- Function to set booster pack group enable status
UIGroupManager:EnableStageLoadingGroup -- Function to set stage loading group enable status
UIGroupManager:EnableLobbyHUDGroup -- Function to set lobby HUD group enable status
UIGroupManager:EnableExchangeSettingGroup -- Function to set exchange setting group enable status
UIGroupManager:EnableExchangeGroup -- Function to set exchange group enable status
UIGroupManager:EnableDiaInfoGroup -- Function to set diamond info group enable status
UIImageAlign:OnBeginPlay -- Sets sprite and transform component references during component initialization
UIImageAlign:SetCharId -- Sets image size based on character ID (S: 400x400, T: 180x180, N: 400x400)
UIImageAlign:UpdateCanvas -- Parses RUID string to set image and adjusts scale and position based on animation type
UIImageSizeFit:Apply -- Adjusts image size to match text height and sets text
UIImageSizeFit:OnBeginPlay -- Stores original padding values during component initialization
UIImageSizeFit:Show -- Shows image for 1 second then automatically deactivates
UIItemRewardService:OnBeginPlay -- Stores original background size and initializes reward list when logic starts
UIItemRewardService:SetItemRewardUI -- Sets item reward UI and displays with animation
UIItemRewardService:AddItemToRewardQueue -- Adds items to reward queue for later batch display
UIItemRewardService:RequestSetQueueToUI -- Displays queued reward items in UI and clears queue
UIItemRewardService:CloseUI -- Closes reward UI, cleans up related data, and displays reputation reward if available
UIItemRewardService:SetReputationRewardUI -- Sets and displays reputation reward UI
UIItemRewardService:CloseReputationRewardUI -- Closes reputation reward UI and cleans up related data
UIItemRewardService:SetCloseUICallback -- Sets UI close callback function
UIItemRewardService:SetSideMenuRewardUI -- Sets side menu reward UI
UIItemRewardService:EndAnim -- Ends reward animation and activates UI
UIItemRewardService:OpenAnim -- Plays reward UI opening animation and returns duration
UIItemRewardService:DrawSeperatedList -- Draws reward item list as separated list
UIItemRewardService:ClearSeperatedList -- Clears separated reward list
UIItemRewardService:HandleButtonClickEvent -- Handles reward UI touch or close button click events
UIItemRewardService:HandleButtonClickEvent2 -- Handles reputation reward UI touch or close button click events
UIItemRewardSlot:SetItem -- Sets slot with item ID and count
UIItemRewardSlot:OnBeginPlay -- Initializes UI components on game start
UIItemRewardSlot:OnClickItem -- Processes item click events
UIItemRewardSlot:SetIngredient -- Sets slot with ingredient ID and count
UIItemRewardSlot:SetEmptySlot -- Sets slot to empty state
UIItemRewardSlot:ResetItemRUID -- Resets item RUID
UIItemSlot:SetItem -- Receives item ID and count to set slot icon and text
UIItemSlot:OnBeginPlay -- Finds icon, count text, and description entities during component initialization and connects click events
UIItemSlot:OnClickItem -- Checks if description should be shown when item is clicked and displays description UI
UIPopup:Open -- Opens confirm/cancel popup, sets message and callback functions, then starts animation
UIPopup:OnClickOk -- Closes popup when OK button is clicked and executes set OK callback function
UIPopup:OnClickCancel -- Closes popup when cancel button is clicked and executes set cancel callback function
UIPopup:Close -- Closes popup
UIPopup:StartTween -- Starts popup open/close tween animation
UIPopup:ResetPopup -- Resets popup content and callback functions
UIPopup:DisconnectButtonClickEvents -- Disconnects button click event connections
UIPopupOK:Open -- Opens OK popup and sets message and callback function
UIPopupOK:OnClickOk -- Closes popup and executes callback function when OK button is clicked
UIPopupOK:Close -- Closes popup and disconnects event connections
UIPopupOK:StartTween -- Starts popup open/close tween animation
UIPopupPurchase:Open -- Opens purchase popup and sets price and callback function
UIPopupPurchase:OnClickOk -- Closes popup and executes callback function when OK button is clicked
UIPopupPurchase:Close -- Closes popup and disconnects event connections
UIPopupPurchase:StartTween -- Starts popup open/close tween animation
UIPopupPurchase:HandleButtonClickEvent -- Handles button click events
UIRewardLogText:Init -- Finds icon entity and sets reference
UIRewardLogText:RefreshAndStartTween -- Sets reward log text and icon and starts tween animation
UIScreenLogic:GetWidth -- Calculates and returns screen width
UIScreenLogic:GetHeight -- Calculates and returns screen height
UIScreenLogic:GetResolution -- Returns current screen resolution as Vector2
UIScreenLogic:GetRatioX -- Calculates X-axis ratio from reference resolution and converts to actual screen width
UIScreenLogic:GetRatioY -- Calculates Y-axis ratio from reference resolution and converts to actual screen height
UIScreenLogic:GetPosition -- Converts absolute coordinates to relative coordinates (0~1)
UIScreenLogic:GetPositionFromTouchPoint -- Converts touch point to UI coordinate system and returns as Vector3
UIToast:ShowMessage -- Displays toast message and starts tween animation
UIToast:StartTween -- Starts toast message fade in/out tween animation
UIToast:OnEndPlay -- Cleans up running timers when logic ends
UIToastLobby:OnBeginPlay -- Stores original position of message entity when logic starts
UIToastLobby:ShowMessage -- Displays lobby toast message and starts tween animation
UIToastLobby:StartTween -- Starts lobby toast position movement with fade in/out tween
UIToastLobby:OnEndPlay -- Cleans up running timers when logic ends
UIToggleTypeA:SetText -- Sets toggle button text
UIToggleTypeA:SetSelect -- Changes image based on toggle button selection state
UIToggleTypeA:OnBeginPlay -- Finds UI elements and connects button events during component initialization
UIToggleTypeA:OnClickButton -- Confirms index when button is clicked then calls external callback function
UIToggleTypeA:SetIndex -- Sets toggle button index number
UIToggleTypeA:SetTextColor -- Sets toggle button text color
UIToggleTypeA:SetTextOutLine -- Sets toggle button text outline
SubscriptionData:Load -- Loads subscription service data from CSV table
SubscriptionService:IngreBoxService -- Updates player's ingredient box subscription service status
SubscriptionService:UpdateHUDSubscriptionInfo -- Updates and displays subscription service information in HUD
SubscriptionService:RefreshSlot -- Refreshes subscription service slot item information and remaining count
SubscriptionService:OnBeginPlay -- Disables subscription info tooltip on game start
UISubscriptionProgressSlot:OnBeginPlay -- Initializes UI components
UISubscriptionProgressSlot:Refresh -- Displays subscription item progress status in UI
UISubscriptionProgressSlot:Disable -- Shows inactive display when subscription service expires
UIUpgradeDetail:Init -- Initializes upgrade detail UI components
UIUpgradeDetail:Refresh -- Updates selected upgrade type detail information in UI
UIUpgradeDetail:SetDescEntity -- Sets upgrade help data to UI entity
UIUpgradeDetail:RefreshEmpty -- Updates UI to empty state when no upgrade is selected
UIUpgradeDetail:RefreshCostTooltip -- Displays original cost and discount effect in upgrade cost tooltip
UIUpgradeListSlot:Init -- Initializes upgrade list slot UI components
UIUpgradeListSlot:Refresh -- Updates upgrade slot UI to match current state
UIUpgradeListSlot:HandleButtonClickEvent -- Selects corresponding upgrade when upgrade slot is clicked
UIUpgradePanel:OnBeginPlay -- Initializes upgrade panel and connects tab button events
UIUpgradePanel:Open -- Opens upgrade panel and selects specific upgrade
UIUpgradePanel:Close -- Closes upgrade panel
UIUpgradePanel:Refresh -- Updates upgrade list of selected tab
UIUpgradePanel:SetSelectTab -- Sets selected tab and updates UI
UIUpgradePanel:OnSelectTab -- Changes UI style when tab is selected and sets guide button
UIUpgradePanel:ReturnTabName -- Returns localized tab name for tab index
UIUpgradePanel:OnSelectSlot -- Selects upgrade slot and updates detail information
UIUpgradePanel:ReturnTabIconRUID -- Returns icon RUID for tab index
UIUpgradePanel:SetGuidePageBtn -- Sets guide page button according to selected tab
UIUpgradePanel:SetTabRedDot -- Shows red dot when tab has upgradeable items
UIUpgradePanel:ResetScroll -- Resets scroll position to selected upgrade item
UIUpgradePanel:HandleButtonClickEvent2 -- Closes upgrade panel when close button is clicked
UIUpgradePanel:HandleButtonClickEvent3 -- Processes upgrade panel open button click
UpgradeDataSetLogic:OnBeginPlay -- Loads upgrade dataset on game start
UpgradeDataSetLogic:LoadDataSet -- Loads upgrade type data and subscription data from CSV
UpgradeDataSetLogic:ReturnValueOfTypeLevel -- Returns effect value for specific upgrade type and level
UpgradeDataSetLogic:ReturnMaxLevelValueOfType -- Returns effect value at maximum level for upgrade type
UpgradeDataSetLogic:ReturnCurrentPlayerValue -- Returns effect value at player's current upgrade level
UpgradeDataSetLogic:ReturnTabDatas -- Returns upgrade list data for tab ID
UpgradeDataSetLogic:CanUpgrade -- Checks if player can perform the upgrade
UpgradeDataSetLogic:IsConditionSatisfied -- Checks if upgrade conditions are satisfied
UpgradeDataSetLogic:ReturnMaxUpgradeLevelAvailable -- Returns effect value of maximum level player can upgrade to
UpgradeDataSetLogic:GetData -- Returns upgrade type data by upgrade type ID
UpgradeDataSetLogic:GetLevelData -- Returns level data by upgrade type and level
UpgradeDataSetLogic:ReturnConditionText -- Returns upgrade conditions as localized text
UpgradeDataSetLogic:ReturnCurrentPlayerLevel -- Returns player's current upgrade level
UpgradeDataSetLogic:RequestCloseUpgradeUI -- Closes upgrade UI and related UIs together
UpgradeDataSetLogic:ReturnGuidePageIdByTabIndex -- Returns guide page ID for tab index
UpgradeDataSetLogic:MakeUpgradeReport -- Generates report message when upgrade is completed
UpgradeDataSetLogic:ReturnReportParamValue -- Converts report parameter strings to actual values
UpgradeDataSetLogic:MakeSubscriptionExpireReport -- Generates report message when subscription service expires
UpgradeDataSetLogic:GetSubscriptionData -- Returns subscription data by subscription ID
UpgradeDataSetLogic:CalcBurgerPriceFromTrainingUpgradeLevel -- Calculates burger price based on training upgrade level
UpgradeHelpData:Load -- Loads upgrade help information from CSV data
UpgradeLevelData:Load -- Loads upgrade level information from CSV row data
UpgradeLevelData:GetHelpData -- Returns upgrade help data
UpgradeLevelData:GetUpgradeCost -- Calculates upgrade cost reflecting player's stage and strategy effects
UpgradeLevelData:GetConditionValue -- Returns upgrade condition value according to stage
UpgradeLevelData:GetUpgradeValue -- Returns upgrade effect value reflecting strategy effects
UpgradeTypeData:Load -- Loads upgrade type information from CSV data table
UpgradeTypeData:GetMaxLevel -- Returns maximum upgrade level according to player's stage
UpgradeTypeData:IsUpgradeConditionSatisfied -- Checks if upgrade unlock conditions are satisfied
UpgradeTypeData:SetUpgradeConditionSatisfied -- Forcibly satisfies upgrade unlock conditions
CustomAnimation:OnBeginPlay -- Initializes animation and performs auto-play on game start
CustomAnimation:OnUpdate -- Updates animation time and state every frame
CustomAnimation:Play -- Starts animation playback
CustomAnimation:PingPong -- Calculates ping-pong animation time (repeats back and forth)
CustomAnimation:Repeat -- Calculates loop animation time (considering loop delay)
CustomAnimation:ChangeAnimationClip -- Changes animation clip and plays new one
CustomAnimation:InitClipData -- Initializes animation clip data and sets callback function
CustomAnimation:Stop -- Stops animation
CustomAnimationLogic:OnBeginPlay -- Performs initialization work on game start
CustomAnimationLogic:InterpolateKeyframes -- Calculates interpolated value for given time based on keyframe data
CustomAnimationLogic:ApplyAnimation -- Applies animation data to match current time
CustomAnimationLogic:GetClip -- Gets animation clip data or loads from cache
NaviNodeEditorLogic:Function1 -- Saves navigation node information of selected stage to dataset
NaviNodeEditorLogic:HandleButtonClickEditorEvent -- Processes data save button click event
NaviNodeEditorLogic:HandleButtonClickEditorEvent2 -- Auto-generates navigation nodes in grid format
LobbySpawnPositionLogic:OnBeginPlay -- Loads all spawn position data on game start
LobbySpawnPositionLogic:LoadRowColDataSet -- Loads row-column structured dataset to table
LobbySpawnPositionLogic:LoadRowDataSet -- Loads row-only structured dataset to table
LobbySpawnPositionLogic:LoadKitchenAppDataSet -- Loads dataset to table based on kitchen appliance type and index
LobbySpawnPositionLogic:LoadExpansionTileGroupDataSet -- Loads expansion tile group data in 3D structure
LobbySpawnPositionLogic:ResetCustomerWaitSeatGroup -- Updates specific position of customer waiting seat group
LobbySpawnPositionLogic:ResetEmployeeUseKitchenAppPosGroup -- Updates position where employee uses kitchen appliances
LobbySpawnPositionLogic:ResetDisplayOffset -- Updates display offset position
SpawnPosEditorLogic:CustomerWaitSeatGroup -- Saves customer waiting seat group position information to dataset
SpawnPosEditorLogic:CustomerExitTempGroup -- Saves customer temporary exit group position information to dataset
SpawnPosEditorLogic:CustomerEnterGroup -- Saves customer entrance group position information to dataset
SpawnPosEditorLogic:CustomerBeforeEnterGroup -- Saves customer pre-entrance waiting group position information to dataset
SpawnPosEditorLogic:EmployeeUseKitchenAppPosGroup -- Saves position information where employee uses kitchen appliances to dataset
SpawnPosEditorLogic:DisplayOffset -- Saves display offset position information to dataset
SpawnPosEditorLogic:ExpansionTileGroup -- Saves expansion tile group position information to dataset
SpawnPosEditorLogic:HandleButtonClickEditorEvent -- Processes editor button click events
LogStorageLogic:LogValue -- Server-only method to store specific player values as logs
EmployeeMoveScript:InitForAstar -- Initializes for A* algorithm and sets path update functions
EmployeeMoveScript:OnUpdate -- Processes employee movement logic every frame
EmployeeMoveScript:ChangeTarget -- Changes target position and sets destination according to employee type
EmployeeMoveScript:InitGraph -- Initializes navigation graph and constructs node data for pathfinding
EmployeeMoveScript:MoveByAstar -- Processes path-based movement using A* algorithm
EmployeeMoveScript:MoveByLinear -- Processes movement to target point in straight path
EmployeeMoveScript:MoveByDir -- Processes actual movement according to direction vector and sets character direction
EmployeeMoveScript:CheckArrival -- Checks arrival at target point by calculating distance
EmployeeMoveScript:MoveFinished -- Sets final position when movement is completed and sends movement complete event
EmployeeMoveScript:ChangeRendererLookDirection -- Processes sprite flip according to character's left/right direction
EmployeeMoveScript:HandleKeyDownEvent -- Processes navigation link visualization with debug keyboard input
EmployeeMoveScript:HandleEmployeeMoveChangedEvent -- Processes employee movement state change events and updates target position
EmployeeMoveScript:HandleRefreshPathEvent -- Processes graph re-initialization when pathfinder requests path update
PathFinder:OnBeginPlay -- Initializes pathfinder and sets A* algorithm functions
PathFinder:distance -- Calculates and returns distance between two points
PathFinder:path -- Calculates path from start to goal using A* algorithm
PathFinder:InitNodes -- Initializes navigation node data for specific level and loads map data
RecycleScrollView:OnBeginPlay -- Initializes scrollview: adds mask and touch components, sets items
RecycleScrollView:Initialize -- Initial scrollview setup: sets view bounds and refreshes
RecycleScrollView:GetOrCreateItem -- Gets item at specified index or creates new one
RecycleScrollView:SetTotalCount -- Sets total item count and refreshes
RecycleScrollView:OnScroll -- Processes vertical or horizontal movement according to scroll direction
RecycleScrollView:MoveVertical -- Vertical scroll movement: updates cell positions and processes recycling
RecycleScrollView:MoveHorizontal -- Horizontal scroll movement: updates cell positions and processes recycling
RecycleScrollView:Refresh -- Refreshes entire scrollview: recalculates item positions and displays on screen
RecycleScrollView:CalculateOffset -- Calculates offset to prevent going beyond boundaries during scroll movement
RecycleScrollView:CanScroll -- Determines scroll availability based on content size
RecycleScrollView:SetItem -- Sets item prefab to use in scrollview
RecycleScrollView:SetViewBounds -- Sets visible area bounds of scrollview
RecycleScrollView:UpdateCell -- Updates scroll cell data and calls callback function
RecycleScrollView:OnMapLeave -- Cleans up scrollview state when leaving map
RecycleScrollView:Clear -- Initializes all scrollview state variables
RecycleScrollView:SetContentRectSize -- Sets content area size and updates scroll state
RecycleScrollView:OnDrag -- Processes scroll movement according to drag input and updates scrollbars
RecycleScrollView:ChangedScroll -- Updates scrollbars when scroll state changes
RecycleScrollView:GetStartOffset -- Calculates start offset according to alignment type
RecycleScrollView:ScrollToIndex_Horizontal -- Scrolls to specified index in horizontal scroll
RecycleScrollView:HandleUITouchBeginDragEvent -- Processes touch drag start event
RecycleScrollView:HandleUITouchEndDragEvent -- Processes touch drag end event
RecycleScrollView:HandleUITouchDragEvent -- Processes touch drag event
RecycleScrollView:HandleUITouchEnterEvent -- Processes touch area enter event
RecycleScrollView:HandleUITouchExitEvent -- Processes touch area exit event
RecycleScrollView:HandleMouseScrollEvent -- Processes mouse scroll event
RecycleTest:Function1 -- Updates scrollview cell item text to current index
RecycleTest:OnBeginPlay -- Initializes scrollview and sets test data
RecycleTest:HandleKeyDownEvent -- Executes scrollview test functions with keyboard input
ScrollBar:SetScrollNormalizedPosition -- Sets scrollbar normalized position and applies to scrollview
ScrollBar:CalcNormalizedPosition -- Calculates normalized position value based on current scrollbar handle position
ScrollBar:SetScrollBar -- Connects to scrollview and sets scrollbar size and position
ScrollBar:SetScrollPosition -- Updates scrollbar handle position according to scroll direction
ScrollBar:Clear -- Initializes scrollbar state
ScrollBar:OnMapLeave -- Cleans up scrollbar state when leaving map
ScrollBar:HandleUITouchBeginDragEvent -- Stores initial touch position when scrollbar drag starts
ScrollBar:HandleUITouchDragEvent -- Processes position update during scrollbar drag
ScrollBar:HandleUITouchEndDragEvent -- Releases drag state when scrollbar drag ends
ScrollItem:Reset -- Initializes scroll item index values
ScrollItem:Init -- Initializes scroll item with actual index, current index, and entity
ScrollMathLogic:GetTouchPoint -- Converts touch point to reference resolution and returns normalized coordinates
OptimizeMobileMapResource:OnBeginPlay -- Sets sprite with mobile-optimized map resources and adjusts size
OptimizeMobileResource:OnBeginPlay -- Sets sprite GUI renderer with mobile-optimized image resources
ResourceLoadLogic:PreLoadResources -- Receives resource ID array and performs asynchronous preloading
ResourceLoadLogic:UnloadResources -- Removes cache for specified resources and unloads unused resources
ResourceLoadLogic:AvatarResourcesLoad -- Loads avatar resources for current stage
ResourceLoadLogic:AvatarResourcesUnload -- Unloads avatar resources for current stage
ResourceLoadLogic:OnBeginPlay -- Initializes mobile resource table and loads basic resources on game start
ResourceLoadLogic:OptimizeMobileResource -- Converts to optimized resource ID on mobile platform
ResourceLoadLogic:OptimizeMobileSize -- Returns size multiplier on mobile platform, returns 1 on PC
ResourceLoadLogic:DialogAvatarRuids -- Collects and returns avatar resource IDs for specified stage
BMShopResourcePreloadLogic:OnBeginPlay -- Initializes shop resource preload logic
PlayerPrivateShop:OpenShopGroup -- Opens shop group and requests system reset if needed
PlayerPrivateShop:CloseShopGroup -- Closes open shop group
PlayerPrivateShop:IsNeccesarySystemReset -- Checks if shop needs system reset based on time
PlayerPrivateShop:RequestSystemResetShop -- Processes system shop reset request
PlayerPrivateShop:UpdateShop -- Updates shop product list and sets reset time
PlayerPrivateShop:RequestResetShopByMoney -- Processes shop reset request with money
PlayerPrivateShop:BuyProduct -- Processes product purchase and validates
PlayerPrivateShop:CanBuyProduct -- Checks product purchasability with various conditions
PlayerPrivateShop:OnSyncProperty -- Processes UI refresh when sync property changes
PlayerPrivateShop:SaveToDB -- Saves private shop data to DB
PlayerPrivateShop:LoadFromDB -- Adds private shop to key list for loading from DB
PlayerPrivateShop:OnLoadedDataFromDB -- Parses and applies private shop data loaded from DB
PlayerPrivateShop:GetBuyMaxCountFromQuantity -- Calculates and returns maximum purchasable quantity of product
PlayerPrivateShop:GetNextSystemResetTime -- Calculates and returns next system reset time
PlayerPrivateShop:BuyProductLog -- Records product purchase success log
PlayerPrivateShop:CancelBuyProductLog -- Records product purchase failure log
PlayerPrivateShop:CanBuyFromCondition -- Checks if product purchase conditions are satisfied
PlayerPrivateShop:FailMessageToServer -- Sends failure message to server for log recording
ShopData:LoadFrom -- Loads shop basic information from dataset
ShopDataLogic:LoadProductData -- Loads shop product dataset and categorizes by shop
ShopDataLogic:LoadShopData -- Loads shop basic dataset and categorizes by group
ShopDataLogic:GetShopProductData -- Returns shop product data by product ID
ShopDataLogic:GetShopData -- Returns shop data by shop ID
ShopDataLogic:OnBeginPlay -- Loads shop-related data on game start
ShopDataLogic:PickProductsByShopId -- Selects products based on random probability according to shop ID
ShopDataLogic:GetShopIdsByShopGroup -- Returns list of shop IDs belonging to shop group
ShopDataLogic:GetProductIdsByShopId -- Returns list of product IDs belonging to shop ID
ShopDataLogic:CheckCanOpenShop -- Checks conditions if player can open the shop
ShopDataLogic:CheckProductUnlock -- Checks if player has unlocked the product
ShopProductData:LoadFrom -- Loads shop product information from dataset
UIShop:OnBeginPlay -- Initializes UI components and sets event connections
UIShop:Open -- Opens shop group and displays accessible shops
UIShop:Close -- Closes shop UI and cleans up related popups
UIShop:ClearData -- Initializes shop menu and product data
UIShop:GetOrCreateMenuRenderer -- Gets shop menu renderer or creates new one
UIShop:GetOrCreateProductRenderer -- Gets product renderer or creates new one
UIShop:ClearProductRenderer -- Deactivates product renderers to hide them
UIShop:OnShopSelected -- Loads selected shop's products and updates UI
UIShop:RefreshShop -- Refreshes shop UI to reflect latest state
UIShop:OnResetedShop -- Processes UI refresh when shop is reset
UIShop:RefreshProducts -- Refreshes and displays selected shop's product list
UIShop:RefreshResetPrice -- Calculates shop reset price and displays in UI
UIShop:DisplayRemainResetTime -- Calculates and displays remaining reset time
UIShop:OnUpdate -- Checks reset time every frame and requests automatic reset if needed
UIShop:OnResetButtonClicked -- Requests shop reset with money when reset button is clicked
UIShop:RefreshSubscriptionInfo -- Refreshes subscription product information and displays in UI
UIShop:HandleButtonClickEvent -- Processes general shop open button click event
UIShop:HandleButtonClickEvent2 -- Processes employee upgrade shop open button click event
UIShop:HandleButtonClickEvent3 -- Processes subscription shop open button click event
UIShop:HandleButtonClickEvent4 -- Processes fourth general shop open button click event
UIShopMenuRenderer:Init -- Initializes menu renderer with shop ID
UIShopMenuRenderer:OnBeginPlay -- Initializes UI components and sets child entity references
UIShopMenuRenderer:OnUpdateBallonSprite -- Updates menu background sprite based on selection state
UIShopMenuRenderer:OnUpdateTextColor -- Updates menu text color based on selection state
UIShopMenuRenderer:OnUpdateIconSprite -- Updates menu icon transparency based on selection state
UIShopMenuRenderer:InitUI -- Initializes shop menu UI elements
UIShopMenuRenderer:SetColorAndRuidForSpecialShop -- Sets color and resource ID for special shop
UIShopMenuRenderer:HandleButtonClickEvent -- Processes shop selection event when menu button is clicked
UIShopProductRenderer:Init -- Initializes product renderer UI with product ID
UIShopProductRenderer:RefreshUI -- Refreshes product UI elements to reflect latest state
UIShopProductRenderer:OnBeginPlay -- Initializes UI components and sets child entity references
UIShopProductRenderer:RefreshPriceText -- Updates product price text and currency icon
UIShopProductRenderer:InitSpecialShopItem -- Initializes UI as special shop product
UIShopProductRenderer:SetBlockComponent -- Sets product purchase block component enable/disable
UIShopProductRenderer:UpdatePriceTextColor -- Updates price text color by comparing with owned funds
UIShopProductRenderer:HandleButtonClickEvent -- Processes purchase popup open event when product is clicked
UIShopPurchasePopup:OnBeginPlay -- Initializes UI components and sets event connections
UIShopPurchasePopup:Popup -- Opens general shop product purchase popup and displays product information
UIShopPurchasePopup:PopDown -- Closes purchase popup with animation processing
UIShopPurchasePopup:OnClickBuyButton -- Processes according to general/special shop when purchase button is clicked
UIShopPurchasePopup:OnClickCancelButton -- Closes popup when cancel button is clicked
UIShopPurchasePopup:UpdateText -- Updates general shop purchase popup text and price
UIShopPurchasePopup:OnModifyButtonClicked -- Changes purchase quantity when quantity adjustment button is clicked and updates UI
UIShopPurchasePopup:PurchaseProcess -- Executes general shop product purchase processing
UIShopPurchasePopup:Popup_SpecialShop -- Opens special shop product purchase popup and displays product information
UIShopPurchasePopup:UpdateText_SpecialShop -- Updates special shop purchase popup text and price
UIShopPurchasePopup:PurchaseProcess_SpecialShop -- Executes special shop product purchase processing
UIShopPurchasePopup:SpecialShopPurchasePriceCheck -- Checks special shop product purchase price and currency limits
UIStagePassBackgroundRenderer:ResetResourcesBackgroundByGroupId -- Sets stage pass background resources according to group ID
UIStagePassBackgroundRenderer:OnBeginPlay -- Initializes stage pass background resource data
BMDropDownLogic:HandleButtonClickEvent2 -- Processes special shop open button click event
BMDropDownLogic:HandleButtonClickEvent3 -- Processes stage pass open button click event
BMDropDownLogic:HandleButtonClickEvent -- Processes booster pack open button click event
PaidLogic:OnBeginPlay -- Sets purchase callback on server
PaidLogic:PurchaseCallback -- Processes and validates world shop purchase callback
PaidLogic:NotifyPurchaseToClient -- Notifies client of purchase completion and updates UI
PaidLogic:OnPurchaseCountChanged -- Notifies client when purchase count changes
PaidLogic:RequestPurchaseWorldShopProduct_SpecialShop -- Processes special shop world shop product purchase request
PaidLogic:RequestPurchaseDiamondProduct_SpecialShop -- Processes special shop diamond product purchase request
PaidLogic:PromptPurchase -- Displays world shop purchase prompt
PaidLogic:GivePurchaseItem -- Gives purchased items to player
PaidLogic:SendPurchaseResult -- Displays purchase result in reward UI
PaidLogic:RequestPurchaseEmployeeEquip -- Processes employee equipment purchase request and distribution
PaidLogic:RequestUpgradeEmployeeEquip -- Processes employee equipment upgrade request and probability calculation
PaidLogic:NotifyPurchaseEmployeeEquipToClient -- Notifies client of employee equipment purchase completion and updates UI
PaidLogic:NotifyUpgradeEmployeeEquipToClient -- Notifies client of employee equipment upgrade result
PaidLogic:UpgradeProcess -- Calculates upgrade probability and sets random seed
PaidLogic:CommonLog -- Common log output (empty)
PaidLogic:EmployeeEquipUpgradeSimulator1 -- Employee equipment upgrade simulator 1 (tests specified level acquisition)
PaidLogic:EmployeeEquipUpgradeSimulator2 -- Employee equipment upgrade simulator 2 (calculates total level cost)
PaidLogic:RequestPurchaseWorldShopProduct_StagePass -- Processes stage pass world shop product purchase request
PaidLogic:PurchaseCallback_SpecialShop -- Processes and validates special shop purchase callback
PaidLogic:PurchaseCallback_StagePass -- Processes stage pass purchase callback and updates data
PaidLogic:PurchaseProcessByShopType -- Branches and executes purchase processing according to shop type
PaidLogic:RequestGetReward_StagePass -- Processes stage pass reward claim request
PaidLogic:RequestGetPurchaseReward_StagePass -- Processes stage pass purchase reward claim request
PaidLogic:SendItemOverMaxCountPopup -- Displays item max count exceeded notification popup
PaidLogic:AddEarnings_PiggyBank -- Adds piggy bank earnings and saves data
PaidLogic:RequestReceiveReward_PiggyBank -- Processes piggy bank reward claim request
PaidLogic:RequestPurchaseWorldShopProduct_PiggyBank -- Processes piggy bank world shop product purchase request
PaidLogic:PurchaseCallback_PiggyBank -- Processes piggy bank purchase callback and validates level
PaidLogic:RequestPurchase_BoosterPack -- Processes booster pack purchase request and validation
PurchaseLogLogic:PurchaseSuccessLog -- Records purchase success log
PurchaseLogLogic:PurchaseSuccessLog_SpecialShop_WorldCoin -- Records special shop world coin purchase success log
PurchaseLogLogic:PurchaseSuccessLog_SpecialShop_Diamond -- Records special shop diamond purchase success log
PurchaseLogLogic:PurchaseSuccessLog_StagePass -- Records stage pass purchase success log
PurchaseLogLogic:PurchaseSuccessLog_PiggyBank -- Records piggy bank purchase success log
PurchaseLogLogic:PurchaseSuccessLog_BoosterPack -- Records booster pack purchase success log
PurchaseLogLogic:PurchaseFailLog -- Records purchase failure log
PurchaseLogLogic:PurchaseFailLog_InvalidEntity -- Records purchase failure log due to invalid entity
PurchaseLogLogic:PurchaseFailLog_FailOnPrompt -- Records purchase prompt failure log
PurchaseLogLogic:PurchaseFailLog_InvalidProductId -- Records purchase failure log due to invalid product ID
PurchaseLogLogic:PurchaseFailLog_UnauthorizedPiggyBank -- Records piggy bank unauthorized purchase attempt failure log
PurchaseLogLogic:PurchaseFailLog_UnauthorizedBoosterPack -- Records booster pack unauthorized purchase attempt failure log
PurchaseLogLogic:PurchaseFailLog_DiamondLack -- Records purchase failure log due to diamond shortage
PurchaseLogLogic:PurchaseFailLog_SpecialShop_AddStorageFail -- Records special shop inventory addition failure log
PurchaseLogLogic:StagePassCompleteLog -- Records stage pass reward claim completion log
PurchaseLogLogic:PiggyBankLevelUpRewardLog -- Records piggy bank level up reward log
PurchaseLogLogic:PiggyBankFlowLog -- Records piggy bank point flow log
PurchaseLogLogic:StorageFlowLog -- Records inventory flow log
PurchaseLogLogic:AllLoggingForTest -- All logging for testing
PurchaseLogLogic:CheckCanTimeFlowsLog -- Records client time flow validation log
UIPurchasePopupLogic:OpenPurchaseConfirmPopup_Immediately -- Opens purchase confirmation popup immediately
UIPurchasePopupLogic:OpenWithdrawalNoticePopup -- Opens withdrawal notice popup
UIPurchasePopupLogic:OpenOverMaxCountPopup -- Opens max count exceeded notification popup
UIPurchasePopupLogic:OpenNoRefunablePurchasePopup -- Opens non-refundable purchase popup
UIPurchasePopupLogic:OnClose -- Processes popup close event
UIPurchasePopupLogic:OnOk -- Processes popup OK event
BoosterPackData:LoadFrom -- Loads booster pack data from dataset
BoosterPackDataLogic:OnBeginPlay -- Loads booster pack data on game start
BoosterPackDataLogic:LoadBoosterPackDataSet -- Loads booster pack dataset and stores in table
BoosterPackDataLogic:GetBoosterPackData -- Queries booster pack data by stage ID
UIBoosterPack:Open -- Opens and initializes booster pack UI
UIBoosterPack:Close -- Closes booster pack UI and executes callback
UIBoosterPack:OnUpdateBoosterPackButtonExpose -- Updates booster pack button exposure state
UIBoosterPack:TitleAnimation -- Executes title animation
UIBoosterPack:OpenAndRegisterPiggyBankOpenCallback -- Opens booster pack and registers callback to open piggy bank when closed
UIBoosterPack:HandleButtonClickEvent2 -- Processes booster pack button click event from shop
UIBoosterPack:HandleButtonClickEvent -- Processes booster pack close button click event
UIBoosterPack:HandlePlayerManagementChangedEvent -- Updates booster pack button when player management state changes
UIBoosterPack:HandlePlayerBoosterPackPurchaseChangedEvent -- Updates button when player booster pack purchase state changes
UIBoosterPack:HandlePlayerPurchaseCountChangedEvent -- Updates button when player purchase count changes
UIBoosterPackRenderer:OnBeginPlay -- Initializes booster pack renderer UI components
UIBoosterPackRenderer:Init -- Initializes booster pack slot and sets data
UIBoosterPackRenderer:OnClickPurchaseButton -- Processes booster pack purchase button click event
UIBoosterPackRenderer:ResetPurchaseButton -- Updates purchase button state and display
UIBoosterPackRenderer:GetBoosterPackPurchased -- Checks if booster pack for that stage was purchased
UIBoosterPackRenderer:HandlePlayerBoosterPackPurchaseChangedEvent -- Updates button when player booster pack purchase state changes
UIBoosterPackRenderer:HandlePlayerPurchaseCountChangedEvent -- Updates premium booster pack button when player purchase count changes
EmployeeEquipUpgradeDataLogic:OnBeginPlay -- Loads employee equipment upgrade data on game start
EmployeeEquipUpgradeDataLogic:LoadEmployeeEquipUpgradeDataSet -- Loads employee equipment upgrade dataset and stores in table
EmployeeEquipUpgradeDataLogic:GetEmployeeEquipUpgrageData -- Queries upgrade data according to equipment level
UIEmployeeEquipShop:OnPurchaseEquipCompleted -- Processes when employee equipment purchase is completed
UIEmployeeEquipShop:OnClickBuyEqiup -- Processes employee equipment purchase button click event
UIEmployeeEquipShop:OnClickGotoShop -- Opens item purchase popup by moving to shop
UIEmployeeEquipShop:OpenGotoShopPopup -- Opens shop move confirmation popup
UIEmployeeEquipShop:OnClickUpgradeEquip -- Processes employee equipment upgrade button click event
UIEmployeeEquipShop:OnUpgradeEquipCompleted -- Processes when employee equipment upgrade is completed and displays effects
UIEmployeeEquipShop:HandleButtonClickEvent -- Processes employee equipment purchase button click event
UIEmployeeEquipShop:HandleButtonClickEvent2 -- Processes employee equipment upgrade button click event
EmployeeEquipUpgradeData:LoadFrom -- Loads employee equipment upgrade data from dataset
PiggyBankBtn:OnBeginPlay -- Initializes piggy bank button gauge and text components
PiggyBankBtn:HandlePlayerPiggyBankPointChangedEvent -- Updates gauge and text when player piggy bank points change
PiggyBankDataLogic:OnBeginPlay -- Loads level data and reward data when piggy bank data logic initializes
PiggyBankDataLogic:LoadPiggyBankLevelDataSet -- Loads piggy bank level data from CSV file and stores in table
PiggyBankDataLogic:LoadPiggyBankLevelUpRewardDataSet -- Loads piggy bank level up reward data from CSV file and stores in table
PiggyBankDataLogic:GetPiggyBankLevelData -- Returns piggy bank level data for level
PiggyBankDataLogic:GetPiggyBankLevelDataByProductId -- Returns piggy bank level data for product ID
PiggyBankDataLogic:GetPiggyBankRewardData -- Returns piggy bank reward data for slot ID
PiggyBankLevelData:LoadFrom -- Loads all properties of piggy bank level data from CSV data row
PiggyBankLevelUpRewardData:LoadFrom -- Loads all properties of piggy bank level up reward data from CSV data row
UIPiggyBank:OnBeginPlay -- Initializes piggy bank UI and sets scrollview and button entities
UIPiggyBank:Init -- Initializes all piggy bank UI elements to match player data
UIPiggyBank:Close -- Closes piggy bank UI group by deactivating
UIPiggyBank:Open -- Opens piggy bank UI group by activating and initializing
UIPiggyBank:InitBottomSection -- Dynamically generates and initializes piggy bank level up reward section
UIPiggyBank:ResetGaugeFillSprite -- Adjusts gauge fill sprite size according to current points
UIPiggyBank:OnUpdatePoint -- Updates background image, text, and gauge when points change
UIPiggyBank:OnUpdateLevel -- Updates all level-related UI elements when level changes
UIPiggyBank:ResetMidSectionUI -- Sets middle section UI according to current level based on max level reached status
UIPiggyBank:ResetRedDot -- Checks for claimable rewards and sets red dot display status
UIPiggyBank:ResetMaxPointTextPositionByGauge -- Adjusts max point text position according to gauge width
UIPiggyBank:ResetDiscountRate -- Sets discount rate text display status and content according to level
UIPiggyBank:ResetPolicyText -- Sets policy description text display status and content according to level
UIPiggyBank:HandleButtonClickEvent -- Plays close sound and closes UI when close button is clicked
UIPiggyBank:HandleButtonClickEvent2 -- Opens UI when piggy bank open button is clicked
UIPiggyBank:HandleButtonClickEvent3 -- Opens UI when piggy bank open button is clicked
UIPiggyBank:HandleButtonClickEvent4 -- Checks if points are full and processes purchase when piggy bank purchase button is clicked
UIPiggyBank:HandlePlayerPiggyBankPointChangedEvent -- Updates UI when player piggy bank points change
UIPiggyBank:HandlePlayerPiggyBankLevelChangedEvent -- Updates UI or only red dot when player piggy bank level changes
UIPiggyBank:HandlePlayerPiggyBankRewardReceivedChangedEvent -- Updates red dot status when player piggy bank reward claim state changes
UIPiggyBank:HandleButtonClickEvent5 -- Opens withdrawal notice popup when refund-related button is clicked
UIPiggyBank:HandlePlayerNowStageChangedEvent -- Sets piggy bank button activation status when player current stage changes
UIPiggyBankLevelUpRewardSlot:OnBeginPlay -- Initializes piggy bank level up reward slot UI components and connects click event
UIPiggyBankLevelUpRewardSlot:Init -- Initializes UI with reward data for slot ID
UIPiggyBankLevelUpRewardSlot:ResetUIChangedByPlayerData -- Updates slot status and UI according to player data
UIPiggyBankLevelUpRewardSlot:HandlePlayerPiggyBankLevelChangedEvent -- Updates slot UI when player piggy bank level changes
UIPiggyBankLevelUpRewardSlot:HandlePlayerPiggyBankRewardReceivedChangedEvent -- Updates slot UI when player piggy bank reward claim state changes
SpecialShopDataLogic:OnBeginPlay -- Loads special shop dataset on game start
SpecialShopDataLogic:LoadAllDataSet -- Loads all special shop related datasets on client
SpecialShopDataLogic:LoadSpecialShopDataSet -- Loads special shop basic information dataset
SpecialShopDataLogic:LoadSpecialShopProductDataSet -- Loads special shop product dataset and categorizes by shop
SpecialShopDataLogic:LoadSpecialShopProductModelDataSet -- Loads special shop product UI model dataset on client
SpecialShopDataLogic:HasRemainingStock -- Checks if product has remaining purchasable stock
SpecialShopDataLogic:FilterSpecialProductDataByCondition -- Filters and returns special shop product data matching conditions
SpecialShopDataLogic:IsCurrenyWorldCoin -- Checks if product is purchased with world coins
SpecialShopDataLogic:AbnormalLog -- Records logs for abnormal situations
SpecialShopDataLogic:CommonLog -- Records general log messages
UIItemDetailSlot:OnBeginPlay -- Initializes UI components and sets child entity references
UIItemDetailSlot:Init -- Initializes item detail slot and displays icon and count
UIItemDetailSlot:HandleButtonClickEvent -- Displays item description tooltip when slot is clicked
UISpecialShop:Open -- Opens special shop UI and sorts and displays shop menu and products
UISpecialShop:Close -- Closes special shop UI and related popups
UISpecialShop:ClearData -- Initializes shop menu and product data
UISpecialShop:ClearProductRenderer -- Deactivates product renderers to hide from screen
UISpecialShop:GetOrCreateMenuRenderer -- Gets shop menu renderer or creates new one
UISpecialShop:OnShopSelected -- Loads selected shop's products and updates UI
UISpecialShop:GetProductsByUserPurchaseCount -- Filters products to display according to user purchase count
UISpecialShop:HasRemainingProduct -- Checks if shop has remaining purchasable products
UISpecialShop:OpenPurchasePopup -- Opens purchase popup for specific item ID
UISpecialShop:OnUpdateCallback -- Updates product renderer to display product information
UISpecialShop:HandleButtonClickEvent -- Processes special shop open button click event
UISpecialShop:HandleButtonClickEvent2 -- Processes special shop close button click event
UISpecialShop:HandleButtonClickEvent3 -- Processes withdrawal notice popup open button click event
UISpecialShop:HandleButtonClickEvent4 -- Processes second special shop open button click event
UISpecialShop:HandleButtonClickEvent5 -- Processes second withdrawal notice popup open button click event
UISpecialShopProduct:OnBeginPlay -- Initializes UI components and sets child entity references
UISpecialShopProduct:Init -- Initializes special shop product UI and sets according to data
UISpecialShopProduct:SetUINextLevelProduct -- Updates UI as next level product
UISpecialShopProduct:SetUIBlock -- Sets product UI to blocked or active state
UISpecialShopProduct:ResetProductPurhaseState -- Resets UI state according to product purchase status
UISpecialShopProduct:OpenPurchaseCheckPopup -- Opens purchase confirmation popup and processes according to product type
UISpecialShopProduct:OnClickPurchaseButton -- Plays sound and opens popup when purchase button is clicked
UISpecialShopProduct:ResetEntitiesByBlockUI -- Resets related UI elements according to block UI state
UISpecialShopProduct:HandleButtonClickEvent -- Processes according to package or general product when product is clicked
UISpecialShopProduct:HandlePlayerDiamondChangedEvent -- Updates price text color when player diamond changes
SpecialShopData:LoadFrom -- Loads special shop data from dataset and sets to properties
SpecialShopProductData:LoadFrom -- Loads special shop product data from dataset and sets to properties
SpecialShopProductModelData:LoadFrom -- Loads special shop product model UI display information from dataset
StagePassDataLogic:OnBeginPlay -- Function to load all stage pass datasets on game start
StagePassDataLogic:LoadStagePassGroupDataSet -- Function to load and initialize stage pass group data from CSV
StagePassDataLogic:LoadStagePassProductDataSet -- Function to load and initialize stage pass product data from CSV
StagePassDataLogic:LoadStagePassLevelDataSet -- Function to load and initialize stage pass level data from CSV
StagePassDataLogic:LoadStagePassRewardDataSet -- Function to load and initialize stage pass reward data from CSV
StagePassDataLogic:IsWorldCoinProduct -- Function to check if the product is a world coin product
StagePassDataLogic:IsPassProductPurchased -- Function to check if user has purchased the pass product
StagePassDataLogic:CanReceiveReward -- Function to check if user can receive the reward
StagePassDataLogic:GetStagePassProductData -- Function to return stage pass product data by product ID
UIStagePass:OnBeginPlay -- Function executed during stage pass UI initialization
UIStagePass:Open -- Function to open and initialize stage pass UI
UIStagePass:Close -- Function to close stage pass UI
UIStagePass:ResetPassGroupTab -- Function to reset pass group tab
UIStagePass:ResetUIsByGroupTab -- Function to reset UI according to group tab
UIStagePass:ResetPassLevelBar -- Function to reset pass level bar
UIStagePass:GetOrCreatGroupTabRenderer -- Function to get or create group tab renderer
UIStagePass:HandlePurchaseCountChangedEvent -- Function to process purchase count change event
UIStagePass:GetOrCreatePassLevelRenderer -- Function to get or create pass level renderer
UIStagePass:OnChangedSelectedGroup -- Function to process when selected group changes
UIStagePass:DisableGroupEntity -- Function to disable group entity
UIStagePass:DisableLevelEntity -- Function to disable level entity
UIStagePass:AddEnableReward -- Function to add reward activation
UIStagePass:RemoveEnableReward -- Function to remove reward activation
UIStagePass:ResetPassProductButton -- Function to reset pass product button
UIStagePass:RegisterRecycleScrollLayoutCallback -- Function to register recycle scroll layout callback
UIStagePass:OnClickPurchasePassProductButton -- Function to process when pass product purchase button is clicked
UIStagePass:SetScrollToRewardSlotId -- Function to set scroll to reward slot ID
UIStagePass:GetEnableRewards -- Function to get enabled reward list
UIStagePass:ResetRedDot -- Function to reset red dot display
UIStagePass:HasTotalRewards -- Function to check if there are total rewards
UIStagePass:ResetGroupTabRedDot -- Function to reset group tab red dot
UIStagePass:HasReward -- Function to check if there are rewards
UIStagePass:HasPurchaseReward -- Function to check if there are purchase rewards
UIStagePass:HandleButtonClickEvent -- Handler to process close button click event
UIStagePass:HandleButtonClickEvent2 -- Handler to process stage pass open button click event
UIStagePass:HandleButtonClickEvent3 -- Handler to process get all rewards button click event
UIStagePass:HandleButtonClickEvent4 -- Handler to process first product purchase button click event
UIStagePass:HandleButtonClickEvent5 -- Handler to process second product purchase button click event
UIStagePass:HandlePlayerStagePassRewardReceivedChangedEvent -- Handler to process player stage pass reward received status change event
UIStagePass:HandlePlayerStagePassPurchaseRewardReceivedChangedEvent -- Handler to process player stage pass purchase reward received status change event
UIStagePass:HandleplayerStageProgressChangedEvent -- Handler to process player stage progress change event
UIStagePassGroup:ResetUIActivated -- Function to reset UI to activated state
UIStagePassGroup:ResetUIDeactivated -- Function to reset UI to deactivated state
UIStagePassGroup:OnBeginPlay -- Function to initialize red dot UI component on game start
UIStagePassGroup:HandleButtonClickEvent -- Handler to process button click event
UIStagePassLevel:OnBeginPlay -- Function to initialize UI components on game start
UIStagePassLevel:Init -- Function to initialize UI with stage pass level data
UIStagePassLevel:SetUILevelByRewardStatus -- Function to set level UI according to reward status
UIStagePassLevel:SetUIRewards -- Function to set reward UI
UIStagePassLevel:SetUILevelByProgress -- Function to set level UI according to progress
UIStagePassPageButton:OnBeginPlay -- Function to initialize UI component on game start
UIStagePassPageButton:Init -- Function to initialize page button with reward slot ID
UIStagePassPageButton:HandleButtonClickEvent -- Handler to process button click event
UIStagePassProduct:OnBeginPlay -- Function to initialize UI components on game start
UIStagePassProduct:Init -- Function to initialize UI with stage pass product data
UIStagePassProduct:OnRewardInfoButtonClick -- Function to process when reward info button is clicked
UIStagePassProduct:OnClickPurchaseButton -- Function to process when purchase button is clicked
UIStagePassProduct:OnOkCallback -- Purchase confirmation callback function
UIStagePassProduct:HandleButtonClickEvent -- Handler to process button click event
UIStagePassPurchaseReward:OnBeginPlay -- Function to initialize UI component on game start
UIStagePassPurchaseReward:Init -- Function to initialize purchase reward with product ID
UIStagePassPurchaseReward:HandleButtonClickEvent -- Handler to process button click event
UIStagePassPurchaseReward:HandlePlayerStagePassPurchaseRewardReceivedChangedEvent -- Handler to process player stage pass purchase reward received change event
StagePassGroupData:LoadFrom -- Loads stage pass group data from dataset
StagePassLevelData:LoadFrom -- Loads stage pass level data from dataset
StagePassProductData:LoadFrom -- Loads stage pass product data from dataset
StagePassRewardData:LoadFrom -- Loads stage pass reward data from dataset
Extend_UIRewardInfoSpecialShop:Init -- Initializes reward info UI for special shop products
Extend_UIRewardInfoSpecialShop:SetPolicyText -- Sets policy guidance text according to product type
Extend_UIRewardInfoStagePass:Init -- Initializes reward info UI for stage pass products
UIRewardInfo:ConnectEntities -- Connects UI entities and sets references
UIRewardInfo:OnBeginPlay -- Initializes UI and sets event connections
UIRewardInfo:OnClickCloseButton -- Processes reward info popup close button
UIRewardInfo:OnClickPurchaseButton -- Processes purchase button click in reward info
UIRewardItem:OnBeginPlay -- Initializes UI components and sets child entity references
UIRewardItem:Init -- Initializes stage pass reward item UI
UIRewardItem:SetUIByRewardStatus -- Updates UI appearance according to reward status
UIRewardItem:HandleButtonClickEvent -- Receives reward or displays tooltip when reward item is clicked
UIRewardItem:HandlePlayerStagePassRewardReceivedChangedEvent -- Updates UI when player stage pass reward received status changes
UIRewardSumSlot:OnBeginPlay -- Initializes UI components and connects events
UIRewardSumSlot:Init -- Initializes reward summary slot and displays item information
TitleEmployee:OnBeginPlay -- Sets random employee and burger stack to display on title screen
TitleEmployee:MoveStart -- Starts animation where employee moves across screen
TitleManager:OnMapEnter -- Initializes and activates UI when entering title map
TitleManager:ReadyForEnterToWorld -- Prepares to enter world and determines next map
TitleManager:PassCheckServer -- Checks intro viewing status and sets button state
TitleManager:SetButtonAfterCheckPass -- Sets button state according to pass check result
TitleManager:OpenTitleUI -- Activates title UI and preloads resources
TitleManager:ResetData -- Initializes player data and processes expulsion
TitleManager:RequestResetDataFromClient -- Processes data initialization request from client
TitleManager:ShowFade -- Moves to next map with fade effect
TitleManager:MoveToNextMap -- Sets destination path according to map name and teleports
TitleManager:SetDataFixButton -- Enables/disables data fix button
TitleManager:SetDataResetButton -- Enables/disables data reset button
TitleManager:HandleKeyDownEvent -- Handler to process key input events
UITitle:TitleUIOn -- Activates title UI and starts decoration animation
UITitle:TitleUIOff -- Deactivates title UI and cleans up timers
UITitle:ToggleResetPopup -- Shows/hides data reset popup and initializes input field
UITitle:SetButtonScroll -- Sets game start button according to pass check result
UITitle:OnGameStartButton -- Processes intro/lobby entry when game start button is clicked
UITitle:OnClickDataReset -- Verifies input and processes when data reset button is clicked
UITitle:OnClickGoToTitleButton -- Processes go to title button click
UITitle:OnClickInfoButton -- Displays info popup when info button is clicked
UITitle:ToggleInfoPopup -- Shows/hides info popup
UITitle:CloseAllPopup -- Closes all popups
UITitle:EnableFixDataButton -- Sets data fix button enable status
UITitle:SpawnDeco -- Spawns decorative employees on title screen and plays movement animation
UITitle:ToggelToastAlpha -- Graphics settings toast alpha blinking animation
UITitle:TweenDecoCharacter -- Title character left-right movement animation
UITitle:HandleButtonClickEvent3 -- Processes game start button click event
UITitle:HandleButtonClickEvent4 -- Processes data reset button click event
UITitle:HandleButtonClickEvent5 -- Processes reset popup close button click event
UITitle:HandleButtonClickEvent8 -- Processes go to title confirmation button click event
UITitle:HandleButtonClickEvent9 -- Processes info button click event
UITitle:HandleButtonClickEvent10 -- Processes info popup close button click event
TweenCurveLogic:GetTweenValue -- Calculates keyframe-based tween values (supports Bezier curves)
TweenCurveLogic:BezierInterpolation -- Calculates Bezier curve interpolation
TweenCurveLogic:GetTweenEnumByString -- Returns EaseType enumeration value by string
UIAnimation:OnBeginPlay -- Initializes UI animation clips based on CSV data
UIAnimation:OnUpdate -- Updates animation every frame and processes tweening
UIAnimation:Play -- Starts animation playback
UIAnimation:UpdateNextFrame -- Updates UI properties with next frame data
UIAnimation:TweenNextFrame -- Processes tweening between previous and next frames
UITweenAlpha:OnBeginPlay -- Initializes alpha tween and sets auto-play
UITweenAlpha:OnUpdate -- Calculates and applies alpha value every frame
UITweenAlpha:Play -- Starts alpha tween playback
UITweenAlpha:PoingPonng -- Calculates ping-pong loop (repeats back and forth)
UITweenAlpha:Repeat -- Calculates regular loop (repeats)
UITweenAlpha:Stop -- Stops alpha tween
UITweenCansvasGroupAlpha:OnBeginPlay -- Initializes canvas group alpha tween
UITweenCansvasGroupAlpha:OnUpdate -- Updates canvas group alpha value every frame
UITweenCansvasGroupAlpha:Play -- Starts canvas group alpha tween playback
UITweenCansvasGroupAlpha:PoingPonng -- Calculates ping-pong loop
UITweenCansvasGroupAlpha:Repeat -- Calculates regular loop
UITweenCansvasGroupAlpha:Stop -- Stops canvas group alpha tween
UITweenClick:OnBeginPlay -- Initializes button click tween and handles special cases
UITweenClick:Pressed -- Plays scale-down animation when button is pressed
UITweenClick:Released -- Plays restore to original size animation when button is released
UITweenClick:HandleButtonClickEvent -- Handler to process button click events
UITweenClick:HandleButtonStateChangeEvent -- Handler to process button state change events
UITweenConfetti:OnBeginPlay -- Initializes confetti effect tween
UITweenConfetti:OnUpdate -- Updates confetti position and alpha every frame
UITweenConfetti:Play -- Starts confetti animation playback
UITweenConfetti:PoingPonng -- Calculates ping-pong loop
UITweenConfetti:Repeat -- Calculates regular loop
UITweenConfetti:Stop -- Stops confetti animation and returns to pool
UITweenMoveBounce:StartTween -- Starts tween to move to target position with bounce effect
UITweenMoveBounce:OnUpdate -- Updates position every frame
UITweenMoveFade:StartTween -- Starts tween with movement and fade effect according to direction
UITweenMoveFade:OnUpdate -- Updates position and alpha every frame
UITweenPop:StartPop -- Starts tween to appear with popup effect
UITweenPop:OnUpdate -- Updates world position every frame
UITweenPop:StartMoveToTarget -- Moves to target position then processes fade out
UITweenPopFade:StartTween -- Starts tween combining popup effect with fade
UITweenPopFade:OnUpdate -- Updates position every frame
UITweenPopFade:StartFade -- Starts fade out effect
UITweenPosition:OnBeginPlay -- Initializes position tween and sets auto-play
UITweenPosition:OnUpdate -- Calculates and applies position value every frame
UITweenPosition:Play -- Starts position tween playback
UITweenPosition:PoingPonng -- Calculates ping-pong loop
UITweenPosition:Repeat -- Calculates regular loop
UITweenPosition:Stop -- Stops position tween
UITweenRotate:OnBeginPlay -- Initializes rotation tween and sets auto-play
UITweenRotate:OnUpdate -- Calculates and applies rotation value every frame
UITweenRotate:Play -- Starts rotation tween playback
UITweenRotate:PoingPonng -- Calculates ping-pong loop
UITweenRotate:Repeat -- Calculates regular loop
UITweenRotate:Stop -- Stops rotation tween
UITweenScale:OnBeginPlay -- Initializes scale tween and sets auto-play
UITweenScale:OnUpdate -- Calculates and applies scale value every frame
UITweenScale:Play -- Starts scale tween playback
UITweenScale:PoingPonng -- Calculates ping-pong loop
UITweenScale:Repeat -- Calculates regular loop
UITweenScale:Stop -- Stops scale tween
UITweenTextColor:OnBeginPlay -- Initializes text color tween and sets auto-play
UITweenTextColor:OnUpdate -- Updates text color and outline every frame
UITweenTextColor:Play -- Starts text color tween playback
UITweenTextColor:PoingPonng -- Calculates ping-pong loop
UITweenTextColor:Repeat -- Calculates regular loop
UITweenTextColor:Stop -- Stops text color tween and restores to initial color
UITweenTextScale:OnBeginPlay -- Initializes text scale tween and sets auto-play
UITweenTextScale:OnUpdate -- Calculates and applies text scale value every frame
UITweenTextScale:Play -- Starts text scale tween playback
UITweenTextScale:PoingPonng -- Calculates ping-pong loop
UITweenTextScale:Repeat -- Calculates regular loop
UITweenTextScale:Stop -- Stops text scale tween
