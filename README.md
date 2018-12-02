# Project 9 - Honeypot

Time spent: 15 hours spent in total

  **Which Honeypot(s) you deployed**
  
The Deploy tab in the MHN server gives you an option to choose different kind of honeypots. Then, according to the differnt honeypots chosen, different scripts and deploy command could be generated in the server. Then, different virtual machines could be used to deploy individual honeypots. Logging in into individual instance of the virtual machines, honeypots can be deployed using the deploy command from the server. I created eight different honeypots since that was the limit for the GPU of the google cloud server:
      - wordpot
      - Dionea/ Dionea with HTTP
      - snort
      - suricata
      - p0f
      - elastichoney
   
Each of these have been created with separate scripts from MHN server.
  
  
  **Any issues you encountered**
  
 A lot of the time passes on setting up the MHN server. It does mention on the instructions that the main server runs on port 80; however, it is mentioned that the port should opened in the google cloud server. So, it took me hours to figure out the issue since i was trying to debug the problems with different scenarios.
  
  **A summary of the data collected: number of attacks, number of malware samples, etc.**

 GIF walkthroug demostrarion of the Attacks:
  <img src="https://github.com/Ankit-Shrestha/Week9-Honeypot/blob/master/attacks_mhn.gif" width="800">
  
  **Number of malware samples**
  
  <img src="https://github.com/Ankit-Shrestha/Week9-Honeypot/blob/master/malware_samples.gif" width="800">
  
  **Any unresolved questions raised by the data collected**
</br>
 None.
 
 
  **Additionally, include a json export of the data you collected in the repository.**
 
 JSON file has been uploaded. 
  