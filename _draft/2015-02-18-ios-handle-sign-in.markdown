# Handling sign in flow in iOS with 2 storyboards

Many app requires users to sign in to start using. This is one of the strategy to solve this problem. 
Below are possible flows depending on the state.

1. New user
    a. Show Sign in / Sign up 
    b. User signs up
    c. Sign in and show signed in state
2. Existing user who's not signed in
    a. Show Sign in
    b. User sigins in
    c. Show signed in state
3. Signed in user returning to the app
    a. Show signed in state
    
