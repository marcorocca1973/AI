# First Sample Descrition
In this sample you find a PowerPlatform Unmanaged solution called ChatGPT_1_0_0_2.zip

This solution contains
1) A Power Virtual Agents that call a Power Automate
2) A Power Automate that using "Call HTTP" action call OpenAI API for Q&I feature

## Prerequisites
To use this sample you need
1) A PowerPlatform environment with Dataverse
2) A free trial for Power Automate and Power Virtual Agents
3) An OpenAI API Key https://beta.openai.com/account/api-keys


## Install ChatGPT_1_0_0_2.zip Solution

1) Open your PowerPlatform Environment where you want to install the solution
![image](https://user-images.githubusercontent.com/22641502/214571190-9a9547a0-5630-4d3b-b6aa-6a875bc486c8.png)

Click on "New Solution" and select the zip file

![image](https://user-images.githubusercontent.com/22641502/214571941-6d6c6edb-fa1d-49c5-abb1-2f87d3f11c58.png)

Leave all default setting and press "Next" button

2) The solution have an environment variable to manage the OpenAI API Key
During the setup you can add the correct value of this variable
![image](https://user-images.githubusercontent.com/22641502/214573596-8a735e5b-117b-4b02-8601-91c94d8956f6.png)

<img width="515" alt="image" src="https://user-images.githubusercontent.com/22641502/214573755-ae8c0e4f-5fc1-4bc1-9e7d-2a8e83582cdb.png">

### Remember to insert the key in the format "Bearer <<OpenAI API Key>>

Press "Next" button

3) Wait that the solution is imported
![image](https://user-images.githubusercontent.com/22641502/214574104-f16c2ff0-4609-4144-b2c8-0c95e69d5065.png)

![image](https://user-images.githubusercontent.com/22641502/214574154-903e1f6d-c1e6-442b-8e63-92b4b4f7d011.png)

5) Check if the variable have the correct value
In the solution view find the object "OpenAIAPIKey" and Edit the value

![image](https://user-images.githubusercontent.com/22641502/214574439-318bdebf-6cc8-4902-aecd-26eec73bf5fc.png)

If it is empty click on "Add Existing" and insert the correct value

## Use this sample
This is the Power Automate...

![image](https://user-images.githubusercontent.com/22641502/214575061-9d83244b-6aec-4fa5-a410-b22db7cb93ce.png)

When you start to use the Chat Bot you could see this message if you don't have a trial activated

![image](https://user-images.githubusercontent.com/22641502/214575259-06a6b22d-aeea-446c-9eea-d58c6dc7318d.png)

You are ready to start your chatbot

![image](https://user-images.githubusercontent.com/22641502/214575367-6b5795b5-cd2f-4d15-b348-c40443901336.png)

![image](https://user-images.githubusercontent.com/22641502/214575412-854b6e01-bdae-40a0-9f42-ecb3e5c917de.png)

![image](https://user-images.githubusercontent.com/22641502/214575449-520a0b0d-c6e7-4afd-ac10-28a338da0806.png)


