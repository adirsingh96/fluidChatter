# fluidChatter

This is just a fun side project which aims to provide a chat ui 

that can integrate with some of the top LLM's. I will be trying to 

implement feature which I wish existed in chatGPT.

______________________________________________________________________________

How to run?

commands:

git clone https://github.com/adirsingh96/fluidChatter.git

cd fluidChatter

cd backend 

create a new file name .env and add:

OPEN_AI_SECRET=                                     (get it from openAI)
OPEN_AI_ORGANIZATION_ID=                            (get it from openAI)
MONGODB_URL=                                        (get it from mongoDB)
JWT_SECRET=                                         (put any random value, for example: iu2yroiurhyqityvy)
COOKIE_SECRET=                                      (put any random value like : hutfyrijfrv3yirtirt3wyt)    

save the file
______________________________________________________________________________

make sure you are in the backend directory and run

npm install
nvm install 18
nvm use 18

npm run dev

_________________________________________________________________________________

open another termimal and get into frontend directory and run 

npm install
nvm install 18
nvm use 18

npm run dev

fuildChatter will start running on  http://localhost:5173/



