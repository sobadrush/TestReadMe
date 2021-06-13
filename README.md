# TestReadMe

## 2

### 3

#### 4

___

# 使用技術
1. SpringBoot
2. SpringBoot Data Jpa
3. Spring MVC
4. Sqlite
5. Log4j2
6. Apache Httpclient

# 測試流程
1. 執行 **SpringBootCurrentpriceApplication** ， 啟動SpringBoot專案
2. 測試[幣別維護]後端 CurrencyRepository : 至 CurrencyRepositoryTest.java 執行 junit測試
3. 測試[幣別API] : 至 CurrencyTypeMaintainTest.java 執行 junit測試
4. 測試[CoinDeskApi] : 至 CoinDeskApiControllerTest.java 執行 junit測試
5. 測試[新資料轉換API] : 至 CurrencyTypeControllerTest.java 執行 junit測試
6. 若使用Sqlite: 使用任一Client軟體開啟**MySqliteDB.db**後確認資料
7. 若使用H2 DB:   ![H2 in memory](../main/h2-memory.png)
