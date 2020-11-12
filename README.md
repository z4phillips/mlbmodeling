# mlbmodeling

  Since sports betting has started to be legalized all over the United States, I have noticed a recent trend in casinos paying people to create this naritive that making stupid bets is a "cool" thing to do. A friend of mine recently said he was going to bet on a "tails" coin flip result at -110. Personally, I think casinos have been preying on addicted gamblers for far too long. With bets being able to be made on a variety of apps faster than ever, I think it is time to use statistics to gain an edge on the house and make a profit. I am well aware that casinos are on the lookout for bettors with an "advantage". Just as casinos back off card counters, I am not sure how much I would be able to profit from this project. However, profit is not what drives me. Money would simply be the cherry on top. I am excited to use my skill set to dive into the sports world I grew up loving. I think getting backed off from bets is almost a end goal of this project. If any casino sees my statistical findings as a "threat" to their greedy empire, I have won.  
  The goal of this project is to use statistics to model certain events in baseball. I have always been a huge fan of sports and a very competitive person myself. Part of my motivation for this project came from reading: "Trading Bases: How a Wall Street Trader Made a Fortune Betting on Baseball" by Joe Peta. Peta used very simple statistical insights to beat the house and make a profit. I beleive a combination of the statistically proven baseball ideas Peta used combined with my modeling background will allow me to beat the house as well. The models will be built in R because that is what I use to model on a daily basis and am most comfortable with. 

Target Variables:
  1) Win/Loss - As stated in the book, this is the most logical target variable because the bettors and the teams they are betting on have the same goal in mind. Due to the bernoulli distribution of a win or loss variable, a logit link will be used to model this variable. There are no ties in baseball! 
  
 Other Possible Target Variables:
  As stated above, I am a bit skeptical of betting on things where the teams and I do not have the same exact goals in mind. Managers do not care whether their team wins by ten runs or only one run. This was a main insight made by Peta that I agree with. Watching and playing sports my entire life, I know teams like to "relax" a bit when they have a comfortable lead. With this being said, I will explore two other models after I am satisfied with my moneyline model.
   1) Total Runs - Poisson ~ log link
 2) Spread - Gaussian ~ identity link 
 
 *I'm just guessing on the link functions of these two at the moment, but these two are the most logical to be based on the data analysis I have done leading up to the creation of these models.
 
 Long term: I am going to focus on the modeling process first because that is what I know, but there are many different places this project could take me after the modeling is completed. I am very interested in automation of this process which would make bets for me. Going to need to really improve my programming skills outside of R for something like this to be a reality in the future. 
   

