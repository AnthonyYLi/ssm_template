�������ssm��ܵ�ģ���ṩʹ��

�������ð�װSpringMVC+Spring+Mybatis

Maven����ssm_template����Ŀ
������Լ��ֶ�������
New �C> project->Maven Project->ѡ����Ŀ·��->ѡ��maven-archetype-webapp->����Group id��artifact idȻ����ɴ���

�Ƽ�ֱ�ӵ��룺
File->import->Existing Maven Projects->ѡ����Ŀ·�����ɣ�maven���Զ�����build�������Ļ���

�ṹ˵��
ssm_template         				----------------------------��ĿĿ¼
	src/main/resources 				---------------------------�����ļ����Ŀ¼
		config.properties			---------------------------db�������ļ���Ϣ
		log4j.properties	 		---------------------------��־��Ϣ
spring-mvc.xml						---------------------------springmvc�����ļ�
		spring-mybatis.xml			---------------------------spring��mybatis�����������ļ�
		spring.xml					----------------------------spring�������ļ�
	src/main/java					----------------------------�߼�����
		ssm.controller				----------------------------�����䲿�ִ���
		ssm.dao						----------------------------���Ͷ���
		ssm.mapper					----------------------------����db��ӿ�
ssm.mapper.imp						-----------------------------����db��mybatisӳ��
ssm.service							----------------------------ҵ���߼���ӿ�
ssm.service.imp						----------------------------ҵ�����ʵ�ֽӿ�
	src/test/java
src								
	main
		webapp						---------------------------������Դ�ļ���
			views					---------------------------��̬��ԴĿ¼
			web.xml					--------------------------webapp������Ϣ
target								---------------------------maven����ļ�
pom.xml								---------------------------maven����.jar������Ϣ

��Ŀ�����������������������ģ��ٸ���tomcat����־ȥ���٣��ܷ���Ϳ��Դ����������ǰ���������spring��mybatis�Ѿ��������۵Ļ���!

