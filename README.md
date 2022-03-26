# store-config-files
	store-config-files

# test url
	http://localhost:9999/config/prod	
	http://localhost:9999/config/dev	
	
	
# 
	org.springframework.cloud.config.server.environment.NoSuchLabelException: No such label: master	
	
	
# master branch create


# 설정파일 사용 단계
	0. git - 설정파일 세팅
	1. 서버 구동 - 설정파일명 세팅
	2. 클라이언트 구동 ( actuator 설치필요) - 설정파일이 변경시 actuator/refresh  해야함
	3. 설정파일이 변경시 actuator/refresh  해야함
		- post http://localhost:8088/actuator/refresh
		git 설정 파일 텍스트 refresh