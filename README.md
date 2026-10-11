# sayitaintfauxweb

### Publishing 
In osilabs.com home dir there is a checkout called sayitaintfauxweb

```sh
cd ~/sayitaintfauxweb
git pull
cd ~/sayitaintfauxweb/bin
bash ./publish-osi.sh
```

### Agents

#### Creation prompt for GitHub Agents using VSCode Agent Tool:
```code
Create an agent that will orchestrates subagents to update make updates to the webpage here at https://sayitaintfaux.com/index.html. It will make the changes that I request to the local file called website/index.html. A validation subagent will make sure the page has a list of shows to present along with pictures and the logo at the top after my updates are made. A design review subagent will think about what can be done to make the page look more modern and make a suggestion on what to do. After the design subagent is done it will go to a publish subagent that will say what it would do to publish the change but will not actually do so.
```