Gensyn Solution Fix 



SPECS :- CLOUD VPS PRESET N2 32GB RAM (WITH 150GB STORAGE)


Required Commands :

Gensyn Automated
1st
Install / Deploy :
curl https://raw.githubusercontent.com/imysryasir/Gsnyn-1-Click-Solutions/refs/heads/main/gensyn_setup.sh | bash

2nd
Solution / Fix :
curl https://raw.githubusercontent.com/imysryasir/Gsnyn-1-Click-Solutions/refs/heads/main/fixgensyn.sh | bash

3rd
TRANSFER SWERM.PEM FILE NOW(NEW USERS SKIP THIS STEP)



4th
START THE NODE

screen -S gensyn

cd rl-swarm

python3 -m venv .venv
source .venv/bin/activate


./run_rl_swarm.sh

SELECT - Y(YES)

RECOMMENDED PARAMETERS = A - 7

LOGIN CLOUDFLARE IN TERMIUS NEW PAGE

cloudflared tunnel --url http://localhost:3000

AFTER LOGIN SELECT HUGGING FACE = N(NO)

NOW ENJOY 😸😃