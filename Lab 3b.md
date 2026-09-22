# Lab 3b
Reflection:

Create somecode.ph
<img width="1680" height="794" alt="image" src="https://github.com/user-attachments/assets/e8e053e5-2259-46a8-8139-28bb4a9889a5" />
Save the given code in a text editor
<img width="1758" height="458" alt="image" src="https://github.com/user-attachments/assets/3f11fb7d-7d2d-4053-b748-1b844e091860" />
Save the code -> give everyone rights to read/write/execute the file -> execute ./somecode.sh to see it works
<img width="620" height="80" alt="image" src="https://github.com/user-attachments/assets/b18ee109-0c68-4775-bc8f-4efc913e07ad" />
Edit the file and change the variables
<img width="322" height="130" alt="image" src="https://github.com/user-attachments/assets/f99fa38a-296d-4d17-9a0c-7a6320e72889" />
add the additional calculations (add, subtract, multiply, divide)
<img width="306" height="258" alt="image" src="https://github.com/user-attachments/assets/597ab623-b35b-4431-a810-3620d705e670" />
<img width="296" height="206" alt="image" src="https://github.com/user-attachments/assets/cb5e5496-668c-42a2-aba9-375058d96891" />
<img width="282" height="214" alt="image" src="https://github.com/user-attachments/assets/42c83fdc-23ce-44f2-87a3-dc888f596a71" />
<img width="312" height="220" alt="image" src="https://github.com/user-attachments/assets/48e5b9a0-00db-4df7-ac4b-1c47ae6437bc" />
The original just printed $i each loop (0 through 9), with no running total.
This version adds a sum variable, initialized to 0 before the loop.
Inside the loop, sum=$((sum+i)) adds the current i to the running total on each pass.
echo $sum now prints the running total instead of just i.
After the loop ends, echo "Total: $sum" prints the final result.
<img width="1748" height="374" alt="image" src="https://github.com/user-attachments/assets/aad22fdf-6638-4020-98af-d2ff2b0d0af8" />
create files to backup
<img width="898" height="420" alt="image" src="https://github.com/user-attachments/assets/a797cc18-8aab-4533-983a-c159f01ac550" />
conduct basic backup script
<img width="910" height="422" alt="image" src="https://github.com/user-attachments/assets/4c9bb9d7-68c7-4789-a016-05647c293b6b" />
insert code inside content
<img width="1262" height="430" alt="image" src="https://github.com/user-attachments/assets/b7016783-ae7e-49b3-8698-c36f5d2653c3" />
<img width="872" height="492" alt="image" src="https://github.com/user-attachments/assets/9654422c-2979-42f6-b071-4b6642a7a1ca" />
make it system wide
<img width="1102" height="308" alt="image" src="https://github.com/user-attachments/assets/e8c52088-6a35-4040-9145-59eb606f570a" />
Edit /usr/bin/testscript by adding zipping with a dated filename
<img width="882" height="84" alt="image" src="https://github.com/user-attachments/assets/45417661-eb10-40b7-8f4d-af972f7a9f69" />
<img width="1272" height="356" alt="image" src="https://github.com/user-attachments/assets/ef2f838a-9835-4d18-bef9-537ec9b77668" />
test -> schedule it with cron
<img width="846" height="590" alt="image" src="https://github.com/user-attachments/assets/9ad19776-02e3-459b-885b-25751795a62b" />
add a line to run it every hour on the 9th minute (as per lab). Note: Cron runs as root and doesn't assume your working directory, which is why the script above uses full paths (/home/ubuntu/...) rather than relative ones — that's the "sticky issue" the lab warns about.
<img width="1976" height="1028" alt="image" src="https://github.com/user-attachments/assets/45795a68-d701-41bc-9639-a83f945de3fe" />
Export the backup to the cloud: require VM and cloud server to SSH into
<img width="1106" height="40" alt="image" src="https://github.com/user-attachments/assets/8957f3dd-8832-4d45-9a1e-04b6c812ebfb" />
<img width="1324" height="184" alt="image" src="https://github.com/user-attachments/assets/2d22398b-d4f7-4055-8918-ac59c824d822" />
<img width="1080" height="138" alt="image" src="https://github.com/user-attachments/assets/5312dba3-e533-47b2-996d-3afd84dd5708" />
<img width="1276" height="428" alt="image" src="https://github.com/user-attachments/assets/8a949390-d69f-43cd-82fb-20927638722f" />

