# AI
AI for termux running locally
## how to install?
do all of these commands one by one also view this in code and no wrap
pkg update && pkg upgrade
pkg install proot-distro
proot-distro install debian
proot-distro login debian
curl -fsSL https://ollama.com/install.sh | sh
ollama serve
in a new session now
proot-distro login debian
ollama pull llama2-uncensored
to run
do
proot-distro login debian
ollama run llama2-uncensored
if its having error about
ollama not runing then
ollama serve
this will start ollama
after doing this start a new session and 
then just do previous command
