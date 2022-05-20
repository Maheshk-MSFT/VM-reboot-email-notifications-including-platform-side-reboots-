# VM-reboot-email-notifications-including-platform-side-reboots-
VM-reboot-email-notifications - including host platform events causing any reboots 

1. Login to Azure Portal, search for "Service Health" in the top search bar 
2. From the "Service Health" blade, select > Resource health > click + Add resource health alert

![image](https://user-images.githubusercontent.com/61469290/169466561-3c3146a0-5a6e-486e-b315-e862f00c5c08.png)

3. Create Resource Health alert rule... 
![image](https://user-images.githubusercontent.com/61469290/169467017-3bf26a29-e175-4850-97c2-7a8fa7a25fc1.png)

4. Define "Alert condition' 
![image](https://user-images.githubusercontent.com/61469290/169467545-4ca80747-b8e9-4c61-b069-f409e74c41f2.png)

5. Select Actions > Action group name 
if you do not have one, create a new action group. Let say, 'Devops Action group' which containers your devops team and so on. You can have as many groups you want and map 
the interested parties. For an example, AKS issues might be interesting to your Infra team so it goes like that. 

![image](https://user-images.githubusercontent.com/61469290/169468035-3f8c52c6-fee4-4440-adcc-e78023b7d037.png)

![image](https://user-images.githubusercontent.com/61469290/169468869-ec9bc386-558f-4c1d-83af-7c8ad4cac658.png)

Allow to create the rule, 
![image](https://user-images.githubusercontent.com/61469290/169469317-90764c1a-6ab3-4eaf-8ebf-8c24a801e0d2.png)

SAMPLE EMAIL ALERT

![image](https://user-images.githubusercontent.com/61469290/169471185-0420c650-e2ae-41db-a217-944fb60e5cff.png)

SAMPLE SMS ALERT

![image](https://user-images.githubusercontent.com/61469290/169471745-9ed6fdb7-b98d-4e1c-8652-e04dafbe9f6e.png)

For demo purpose, I had selected all the events to see the responsiveness. Suggest to set alert to be triggered on selective set of an event so that you can attend 
instead feeling overwhelmed. 
