# Setup
blade gw initbundle </br >

</br >
Copy and paste: </br >
jdbc.default.driverClassName=org.mariadb.jdbc.Driver
jdbc.default.password=liferay
jdbc.default.url=jdbc:mariadb://localhost/lportal?useUnicode=true&characterEncoding=UTF-8&useFastDateParsing=false
jdbc.default.username=root

# Command to create soy portlet

blade create -t soy-portlet -p com.liferay.docs.soyportlet -c MySoyPortlet my-soy-portlet-project
