Instructions :

Step1: Fork & clone the git repository : git clone url

Step2: Install & start the docker desktop

Step3: Go to cloned directory : cd Infy_P3_OnlineContentContextualization/

Step4: Build the docker image : docker build -t summarizer-api .

Step5: Run a container image instance : docker run -p 5000:5000 summarizer-api

Step6: Open a browser & type http://0.0.0.0:5000/

Step7: Test some sample URLs like below. URLs should be publicly scrapable.

https://www.barrons.com/articles/ibm-is-a-growth-stock-again-thanks-to-red-hat-acquisition-51565025034 

https://www.moneycontrol.com/news/business/infosys-sets-up-cyber-defence-centre-in-bucharest-4259681.html?classic=true

https://www.cips.org/en/supply-management/news/2019/august/extra-brexit-border-funding-not-enough/

Step8: Finally stop the container instance : 
run docker ps & get the container id   
docker stop container id
