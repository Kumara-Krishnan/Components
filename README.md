Prerequisites:
- Download and copy nuget.exe to C:\Program Files\NuGet - https://dist.nuget.org/win-x86-commandline/latest/nuget.exe
![image](https://user-images.githubusercontent.com/5687650/169728420-7b7ba15e-e452-4fe5-830b-4368455bd41c.png)
- Set 'C:\Program Files\NuGet' in 'path' system environment variable.
![image](https://user-images.githubusercontent.com/5687650/169728517-00f19f31-5206-452f-926a-0d75c39a5fea.png)
- Open 'cmd' and type 'nuget' it should print help info.
![image](https://user-images.githubusercontent.com/5687650/169728289-414b1198-6f79-4d2b-b97b-391d479347df.png)
- Add local nuget cache in VS. Tools-> NuGet Package Manager -> Package Manager Settings -> Package Sources -> Add new.
![image](https://user-images.githubusercontent.com/5687650/169728638-e90c7166-28ed-490e-ad00-891c03757cbf.png)
- That's all. You're ready to go!


After cloning the repo, Open the solution in VS and set Release/x64 config. After building the solution you'll find the nuget package created in bin folder.
![image](https://user-images.githubusercontent.com/5687650/169727889-79469f20-f6fd-4864-baa7-b7fc5bcac904.png)
Copy the nuget package and paste it in your local nuget cache folder.
![image](https://user-images.githubusercontent.com/5687650/169727971-5436dec5-144f-4ef6-b3e0-bf35204931f5.png)
