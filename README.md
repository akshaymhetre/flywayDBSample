# flywayDBSample
Flyway db example

All migration scripts will be in resources/db/migration folder. 
The file name consists of the following parts:
* Prefix: V for versioned (configurable), U for undo (configurable) and R for repeatable migrations (configurable)
* Version: Version with dots or underscores separate as many parts as you like (Not for repeatable migrations)
* Separator: __ (two underscores) (configurable)
* Description: Underscores or spaces separate the words
* Suffix: .sql (configurable)


#Type command mvn flyway:migrate to exceute newly added scripts
