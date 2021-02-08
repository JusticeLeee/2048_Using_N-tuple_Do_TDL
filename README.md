# 2048_Using_N-tuple_Do_TDL

## Definition 
```
alpha is "learning rate"
TD-error  = (reward + after_state's value) - value
TD-target = (reward + after_state's value)
```

## This is my CGI_Lab first Project , need to complete 5 TODO function.

* class pattern :: estimate
* class pattern :: update
* class pattern :: indexof
* class learing :: select_best_move
* class learing :: update_episode
```
Using 4 6-tuple & their isomophism as feature 
# feature  = 4 * 8 =32  
And the Temporal Difference Learning Formula 
V[s] = V[s] + alpha * error
```

## Note 
```
in main : the vector::<state>path's last one state is terminal it is invalid , we don't need it .
Thus you need add a code "path.popback()" to remove the terminal state when you do class learing :: update_episode.
```

