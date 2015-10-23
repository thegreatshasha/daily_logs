What we are trying to learn is not what to in a particular state but an optimal action value function. 
A = {1,K} represents K possible actions set
xt = 

state = {state is all possible x * all possible a}
state = permutation(x,y)

stateI+1 = stateI()+xnew,action_taken, can think of state as sequence of paths in this case

Q(s,a) is a markov decision process which corresponding to a state n action tells us the expected return we will be getting until termination
Q(s,a) = maxpi(E(R/s,a,pi))

Bellman equation: Nothing but reward the maxium performer. Basically we try some shit out according to our probability distribution. If it gives a better score, for the previous Q state, the value should be this one * Y + reward

pi is yourw decision making policy, think of it as a table telling what to do in each of each current

since the set of possible states and possible actions is huge, problem becomes intractable unless we approximate Q

important to note that this is a finite decision process

s is not just a sequence of states, it's a sequence of states and actions corresponding to them

Forget about neural network for now. What is the eqn in tabular state?
Q(s,a) = E(r+Y.Q(s',a')) where a' belongs to 

Intution behind algo:

Tabular method
Try out an action randomly, see Q(s,a), if r+gamme*Q'() is greater, that means Q(s,a) = r + gamma*Q'(s,a)
For each state you tryout actions according to weights of the neural network.

Q learning can be represented graphically through a decision tree.
Neural network takes as input both states and actions.
Feed s', a' to the neural network. Neural network should take both (x,a) as input. Compute Q values for each of the actions
very simple example would be to simply add up rewards 
Basically best path is the one with the maximum sum.


