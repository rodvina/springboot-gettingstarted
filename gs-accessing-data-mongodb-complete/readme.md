## SpringBoot 101

#####Commands
- Build using gradle

		gradle build
		
- Run SpringBoot app for a spring profile based on application.yml in src/main/resources

		java -jar build/libs/gs-accessing-data-mongodb-0.1.0.jar --spring.profiles.active=dev
		
or using gradle via bootRun task

		bootRun {
        	systemProperties = System.properties
		}

		gradle -Dspring.profiles.active=dev bootRun
		
or Run SpringBoot App from eclipse	