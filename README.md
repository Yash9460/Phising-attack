# Phising-attack
How to do Advance Phishing Attacks using Kali Linux
# What is phishing attack?
Phishing is a type of cyber-attack in which a hacker sends a fake email with a phishing link, which led you to a phishing website and asks you to log in, and if you accepted the bait and logged in then your credentials will be sent to the attacker.

Now the question is what is phishing email? , what is phishing link?

So to answer these questions let me introduce you to a tool called Zphisher.

ZPhisher is an advanced phishing tool-kit it is an upgraded version of Shellphish. It have the main source code from Shellphish but ZPhisher have some upgrade and have removed some unnecessary codes from Shellphish. It is devloped by HTR-Tech. It is the all-in-one phishing framework in 2020.

# How to do phishing?

Now we’re going to see how to do the attacks in ZPhisher.

## For Linux
     1. First, we need to install the tool from Github.
     2. For installing the tool go to the Github repository of the ZPhisher.
     3. Fire up your terminal and write the following commands.
   git clone https://github.com/htr-tech/zphisher
   
  - The screenshot of the preceding command if following:
                  
![Phishing](https://user-images.githubusercontent.com/73324896/117911244-12fc6b80-b2fb-11eb-8194-7eab2da03b8e.png)

    4. Then we need to go inside the zphisher directory using cd command:
  cd zphisher
    
    5. Here we need to give executable permission to the bash script by using following command:
  sudo chmod +x zphisher.sh
  
  - The screenshot is following.
  
  ![Phising1](https://user-images.githubusercontent.com/73324896/117911590-b0579f80-b2fb-11eb-9a49-e2930092c0e6.png)
  
    6. Now we are ready to run it. We can run it by using following command:
  bash zphisher
  
  - Then this bash script lead us to the main menu of the ZPhisher tool as shown in following screenshot:
 
 ![Phishing2](https://user-images.githubusercontent.com/73324896/117912157-98cce680-b2fc-11eb-8d88-488df4bd298d.png)
 
    7. Here everything is very clear. 
  - For an example we choose 1 for Facebook and press enter.

 ![Phishing3](https://user-images.githubusercontent.com/73324896/117912459-34f6ed80-b2fd-11eb-9a45-b89a2a2783dd.png)
 
  - Here we can choose whatever we think easy to trick our victim. For an example we choose 3 for a "Fake Security Login Page".
 
 ![Phishing4](https://user-images.githubusercontent.com/73324896/117912626-74253e80-b2fd-11eb-8670-a95879b128f2.png)
  
  - Now we can choose our port forwarding option. Here  we choose 2 for ngrok.io. Then we wait for some seconds untill our link generated.
  
 ![Phishing5](https://user-images.githubusercontent.com/73324896/117912781-bd758e00-b2fd-11eb-915a-72ab91a37c2e.png)
    
 In the above screenshot we can see our link created on ngrok. Now we can send this link to our victim by SMS or mail or by any other way With some catchy social engineering technique.
    
  - If our victim opens it then he/she will see something like following screenshots:
 
 ![Phishing6](https://user-images.githubusercontent.com/73324896/117912957-16452680-b2fe-11eb-8558-ac27fa65cb38.jpg)
                                      On Desktop

 ![Phishing7](https://user-images.githubusercontent.com/73324896/117913037-4096e400-b2fe-11eb-84fd-73e1e0334345.jpg)
                                      On Mobile Device
                                      
  - If our victim inputs the username and password then,
  
  ![Phishing8](https://user-images.githubusercontent.com/73324896/117913161-789e2700-b2fe-11eb-8236-f949cdf604fb.png)
                                           BINGO!
   
             We got the credentials of our victim. Now it can be used to login victim's Facebook account.   
             
             
## For Smartphone

- You can do this attack from your smartphone too you just have to install the termux app and follow the same steps as for Linux. Just a little change for smartphone always turn on your mobile hotspot before performing this attack .

# NOW COMES THE ADVANCE PART
  
  Now day’s normal links may make the victim suspicious about the website.

So to deal with this issue we are going to learn few steps to make our link looks more trusting.

So to do this we are going to use a link shortener like bit.ly.

Just paste your link on the bit.ly link shortener and your link will look more trusting.

Now let’s assume the person you want to phish is aware of these phishing processes. Now we have to make our link look more secure. How to hide our phishing link?, Let’s see

Now we are going to mask our link with a fake link that will look legit

To do this we are going to use a tool called maskphish which is created by jaykali and is an open-source tool in Github.

# Installation

    1. Fire up your terminal and write the following commands.
 git clone https://github.com/jaykali/maskphish
 
    2. Then type to get into maskphish directory.
 cd maskphish

    3. Then type
 bash maskphish.sh
 
    4. This will run your tool. Now paste your link there and make your custom link with some social engineering elements and then send it to the victim.
   
- Now your screen will look like this.
 
 ![phishing9](https://user-images.githubusercontent.com/73324896/117914270-9ec4c680-b300-11eb-978d-a85ea6f78672.png)
 
- Now that we have learned how to do phishing and how to mask links let’s see how to prevent phishing.

# How to prevent phishing?

    1. Never click any link that you don’t trust.
    2. Never open any email from an untrusted source.
    3. Always verify where the link is taking you if you hover your mouse over the link it will show the real link behind the mask one.
    4. Be aware of these phishing techniques.
    5. Always be updated on the latest phishing trend following.

                                     
   



  
    
