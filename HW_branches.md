1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

 `$ git clone git@github.com:ItGroupAlex/branch.git` - clone peros.  
 `$ git branch Postman` - create branch Postman   
 `$ git branch Jmeter` - create branch Jmeter   
 `$ git branch CheckLists` - create branch CheckLists   
 `$ git branch BagReports` - create branch BagReports   
 `$ git branch SQL` - create branch SQL   
 `$ git branch Charles` - create branch Charles   
 `$ git branch MobileTesting` - create branch MobileTesting   

2. Запушить все ветки на внешний репозиторий

`$ git push -u origin Postman`  
`$ git push -u origin Jmeter`  
`$ git push -u origin CheckLists`  
`$ git push -u origin BagReports`  
`$ git push -u origin SQL`  
`$ git push -u origin Charles`  
`$ git push -u origin MobileTesting`  

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

`$ git checkout bagreports` - move to branch "BagReports"  
`$ touch bug_report.json` - create file  
`$ vim bug_report.json`   - redact file  

5. Запушить структуру багрепорта на внешний репозиторий

`$ git add .`  
`$ git commit -m "Create json"`
`$ git push`

7. Вмержить ветку Bag Reports в Main


9. Запушить main на внешний репозиторий.
10. В ветке CheckLists набросать структуру чек листа.
11. Запушить структуру на внешний репозиторий
12. На внешнем репозитории сделать Pull Request ветки CheckLists в main
13. Синхронизировать Внешнюю и Локальную ветки Main
