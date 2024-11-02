# TextDiffuser_Demo
**This is a docker version of [TextDiffuser](https://github.com/microsoft/unilm/tree/master/textdiffuser).**  
**We suggest you deploy this docker with WSL2 on Windows10(or higher version).**  
  
1. First, you should download all the parts of textdiffuser.tar, then move them to WSL. and combine them:    
```cat textdiffuser-part-* > textdiffuser.tar```
2. Import the tar file:  
```docker load -i textdiffuser.tar```
3. Run it:  
```docker start textdiffuser(or CONTAINER_ID)``` 
4. Access interface with your browser through:  
```127.0.0.1:7860```  

Before you run it, this docker need to run on GPU, so make sure that you have have nvidia-docker2 installed.


