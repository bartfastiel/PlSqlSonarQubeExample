# PlSqlSonarQubeExample
Example project of a minimal setup to analyze PL/SQL code

## Helpful links

- Plugin marketing documentation: https://www.sonarsource.com/why-us/products/languages/plsql.html
- Plugin technical documentation and download: http://dist.sonarsource.com/reports/coverage/rules/plsql_rules_coverage.html
- Rule overview: http://dist.sonarsource.com/reports/coverage/rules/plsql_rules_coverage.html
- Current findings in open-source projects (cloud service): https://sonarqube.com/issues#languages=plsql

## Step-by-step

1. download https://sonarsource.bintray.com/Distribution/sonarqube/sonarqube-6.2.zip
2. unzip sonarqube-6.2.zip
3. download https://sonarsource.bintray.com/Distribution/sonar-scanner-cli/sonar-scanner-2.8.zip
4. unzip sonar-scanner-2.8.zip
5. download http://sonarsource.bintray.com/CommercialDistribution/sonar-plsql-plugin/sonar-plsql-plugin-2.8.jar
6. copy sonar-plsql-plugin-2.8.jar into sonarqube-6.2/extensions/plugins
7. get your PL/SQL-plugin licence key from SonarSource
8. run sonarqube-6.2/start.sh
9. go to http://localhost:9000/settings/licenses, "Update", paste licence key
10. download https://github.com/bartfastiel/PlSqlSonarQubeExample/archive/master.zip
11. unzip master.zip
12. cd PlSqlSonarQubeExample-master
13. run sonar-scanner-2.8/bin/sonar-scanner
14. go to http://localhost:9000/dashboard?id=PlSqlSonarQubeExample

