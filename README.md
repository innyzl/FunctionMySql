# for Mysql;

# create;
CREATE TABLE `_text` (
  `ID` int(11) NOT NULL AUTO_INCREMENT,
  `DATA` text
  PRIMARY KEY (`ID`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=utf8;

# data;
`ID` : 5
`DATA` : [{"ID":"3292"},{"ID":"278"},{"ID":"2410"},{"ID":"368"},{"ID":"3094"},{"ID":"2980"},{"ID":"2904"},{"ID":"2914"}]

`ID` : 6
`DATA` : [{"ID":"3291"},{"ID":"279"},{"ID":"2110"},{"ID":"1368"},{"ID":"3194"},{"ID":"1980"},{"ID":"1904"},{"ID":"1914"}]

# query;
SELECT * FROM `TABLENAME` WHERE `TABLENAME.COLUMN` REGEXP '[[:<:]]2410[[:>:]]' LIMIT 1;

# reult;

ID : 5
