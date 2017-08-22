# IIBCrypto
Hi Folks. The jars attached here has been tested against Broker 10.0.0.7, But I do not see any reason it should not work with the latest fix pack. 

Steps
1. Upload the jars in the Jars/Toolkit/plugins folder in "C:\Program Files\IBM\IIB\10.0.0.6\tools\dropins". The "10.0.0.6" it would change according to your broker. 
2. Add the Jars/Runtime/*.jars to the broker lil path. For this you need to run a command
   mqsichangebroker <BROKER_NAME> -i <Path to the folder where you put the jars file on your machine>
   Make sure the broker is stopped when you run this command. 
   
3. Now you are ready to test your flow. 
4. Attaching the a message flow project zip for reference. 

