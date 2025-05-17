## 1. Install Tmux

To install tmux on Termius:

```bash
sudo apt update
sudo apt install tmux -y
```

## 2. Start a new tmux session

```bash
tmux new -s gensyn
```
- This opens a new persistent terminal session named gensyn

Now you can run your gensyn command to run your node.... !

## 3. Detach the session
Press: 
` Ctrl + B, then press D `

## 4. Reattach anytime later 
to re-enter the tmux session: 

```
tmux attach -t gensyn
```

### BONUS: See all tmux sessions

```
tmux ls
```
