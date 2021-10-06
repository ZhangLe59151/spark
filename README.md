# spark

start cluster:  
 - docker-compose up -d  

check cluster:  
 - docker-compose ps  

Ports:  
 - 50070：HDFSwebUI的端口号  
 - 9000：非高可用访问数rpc端口  
 - 8080：sparkwebUI的端口号  
 - 8081：worker的webUI的端口号  
 - 7077：spark基于standalone的提交任务的端口号  

spark & hadoop的webUI:  
 - HDFSwebUI: http://IP:50070    
 - sparkwebUI: http://IP:8080  
