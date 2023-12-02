# Lab Report 4  
## 1. Login  
![Image](Login.png)  
Explanation: I logged in to ieng6 with my username. It did not prompt for a password since I had set up the ssh keys.  
Typed in: `ssh cs15lfa23ez@ieng6.ucsd.edu`  
Keys Pressed: <kbd>Enter</kbd>  
## 2. Clone with SSH URL  
![Image](Clone.png)  
Explanation: I first forked the lab7 repo on the GitHub website. Then I used the SSH URL to clone it.    
Typed in: `git clone` followed by SSH URL  
Keys Pressed: <kbd>Enter</kbd>  
## 3. Tests  
![Image](Tests.png)  
Explanation: I run the tests using the command `bash test.sh`. There seems to be an error in `ListExamples.java` with `merge`.    
Typed in: `bash test.sh`  
Keys Pressed: <kbd><Enter></kbd>  
## 4. Edit Code  
![Image](vim_open.png)  
![Image](vim_opened.png)  
Explanation: To start edit ListExamples.java, I used the command `vim ListExamples.java`.
Typed in: `vim ListExamples.java`  
Keys Pressed: <kbd>Enter</kbd>  
  ![Image](fix_error.png)  
Explanation: To find merge, I type the command `/merge` into vim, which helps me find the merge method. I use the down arrow key to scroll down. I see the comment `//change index1 below to index2 to fix the test`. I press `i` to go into insert mode. I move my cursor using the keys to right after the `1` on `index1`, press `delete` on my keyboard, and then type `2` so it now says `index2`. I press `esc` so it goes back into normal mode. I type `:wq` so I can save the file I just edited and exit vim.  
Search String: `/merge`  
Keys pressed:  <kbd>/merge</kbd> <kbd>i</kbd> <kbd>↓</kbd> <kbd>→</kbd> <kbd>delete</kbd> <kbd>2</kbd> <kbd>esc</kbd> <kbd>:wq!</kbd> <kbd>Enter</kbd>  
Deletion: ```1```  

## 5. New Tests  
![Image](fixed_tests.png)  
Explanation: After the edit, all the tests were passed.    
Typed in: `bash test.sh`  
Keys Pressed: <kbd>Enter</kbd>  

## 6. Git Push  
![Image](gitpush.png)  
![Image](github_web.png)  
Explanation:  I used the command `git add` so it can add the changes I made to the local server. I then ran `git commit -m` so I could save all the changes I made with `git add` and be ready for a path; `-m` is for a message to be shown of what edits I made. I used `git push` to push the changes made to the remote repository.  
Typed in: `git add ListExamples.java`  
Keys Pressed: <kbd>Enter</kbd>  
Typed in: `git commit -m "Fixed test errors"`  
Keys Pressed: <kbd>Enter</kbd>  
Typed in: `git push`  
Keys Pressed: <kbd>Enter</kbd>  
