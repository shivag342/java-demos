Requirements

<spring.version>4.0.5.RELEASE</spring.version>
  <hibernate.version>4.3.5.Final</hibernate.version>
  <log4j.version>1.2.17</log4j.version>
  <jdk.version>1.6 or 1.7</jdk.version>

webserver apache tomcat 1.6 or 1.7 

#database table

CREATE TABLE  "REGISTER_USER" 
   (	"USERID" NUMBER NOT NULL ENABLE, 
	"FIRSTNAME" VARCHAR2(45), 
	"LASTNAME" VARCHAR2(45), 
	"AGE" NUMBER, 
	"GENDER" VARCHAR2(6), 
	"USERNAME" VARCHAR2(40), 
	"PASSWORD" VARCHAR2(30)
   )
/
