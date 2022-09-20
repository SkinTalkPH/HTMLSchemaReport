# How to: Import the HTML Schema Report plugin on MySQL Workbench 8.x.x CE
Posted by Lance Delariarte on September 20, 2022; 6:55 p.m.

## Prerequisites
- It's assumed that you downloaded the `.msi` installer and installed in your machine. If not, download [here](https://dev.mysql.com/downloads/workbench/).
- It's assumed that you have your `.sql` file with you, ready to import on Workbench.

## Part (1/2): Import an SQL script

### Step 1
Open the MySQL Workbench application. In my case, I have MySQL Workbench 8.0 CE installed on my machine.

![image](https://user-images.githubusercontent.com/58999917/191227780-7d4610ef-d65f-4120-9402-5639dabdd8d5.png)

### Step 2
Click `File` > `New Model` or press `Ctrl + N` to create a New Model.

![image](https://user-images.githubusercontent.com/58999917/191235199-3dffcb19-1b76-4bcc-97d9-ada4a7facca3.png)

### Step 3
A `MySQL Model` tab should be opened. Click `File` > `Import` > `Reverse Engineer Create Script...`.

![image](https://user-images.githubusercontent.com/58999917/191235635-7bb123f5-19cc-4d37-a048-523bdaa36e65.png)

### Step 4
On the Reverse Engineer SQL Script Screen, press the `meatballs` or `...` menu to select an SQL script file.

Press the `Execute` button to continue.

![image](https://user-images.githubusercontent.com/58999917/191236278-ccd98a12-9d62-43e7-bf50-cd4dd52d94a8.png)

### Step 5
One the impost is finished, `Reverse Engineer SQL script` and `Verify Results` should be checked. Click `Next` to continue.

![image](https://user-images.githubusercontent.com/58999917/191236945-78c8e452-2a7d-4e69-b917-0cf21138052a.png)

### Step 6
Click `Finish`.

![image](https://user-images.githubusercontent.com/58999917/191237365-4c0f521f-8288-4e36-b5a1-04bbd3b9255f.png)

## Part (2/2): Install the plugin

### Step 1
Click `Scripting` > `Install Plugin/Module...`.

![image](https://user-images.githubusercontent.com/58999917/191237656-78050bfe-07fa-4352-8022-22e9a3fa3ac8.png)

### Step 2
Locate the `HTMLSchemaReport-WMB8.py` file, select it.

![image](https://user-images.githubusercontent.com/58999917/191237904-6545946b-c7de-4ec2-b97e-717c68d69e1b.png)

### Step 3
Click `OK` button and restart MySQL Workbench.

![image](https://user-images.githubusercontent.com/58999917/191238338-5f304b86-5a25-47e1-b353-659af913ea65.png)

### Step 4
Click the SQL that you imported. You may delete the `mydb` to avoid confusion.

![image](https://user-images.githubusercontent.com/58999917/191238804-44073701-3338-456a-be60-621a6e130dc1.png)

### Step 5
Click `Tools` > `Catalog` > `HTML Format database schema report`

![image](https://user-images.githubusercontent.com/58999917/191239065-d8e15106-01cb-4077-abae-713d658c83ce.png)

### Step 6
Create a name for your file, and click `Save` to continue.

![image](https://user-images.githubusercontent.com/58999917/191239502-d447f2c7-304f-4fd2-8b87-df27ee1a64a1.png)

### Step 7
Open the HTML file that you generated.

![image](https://user-images.githubusercontent.com/58999917/191239941-4c5ae4e4-e0ff-4f3f-978b-a5b567942bf9.png)
