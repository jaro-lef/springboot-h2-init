kolejność wykonywania przy starcie aplikacji:
	resources: schema.sql
	resources: data.sql
	encje: tworzenie tabel z encji np. Student
		jeśli będzie spring.jpa.hibernate.ddl-auto=create to nadpisze tą ze schema.sql
		jeśli będzie spring.jpa.hibernate.ddl-auto=update to poprawi istniejącą ze schema.sql wg encji
		
		
tutorial do rozbudowania obecnego: https://www.bezkoder.com/spring-boot-jpa-h2-example