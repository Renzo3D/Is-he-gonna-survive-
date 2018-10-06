# Is-he-gonna-survive-

This is a kata 8 and here are the instructions:


A hero is on his way to the castle to complete his mission. However, he's been told that the castle is surrounded with a couple of 

powerful dragons! each dragon takes 2 bullets to be defeated, our hero has no idea how many bullets he should carry.. Assuming he's gonna

grab a specific given number of bullets and move forward to fight another specific given number of dragons, will he survive?

Return True if yes, False otherwise :)



This the faster Kata I have ever done. Took me less than a minute to complete it. 

Explanation:

Lets focus on the important matter.

we need TWO bullets per DRAGON. 

In order for the hero to survive he needs two or more number of bullets per number of dragons.

With this gold in mind.

if you say 4 dragons, the hero needs AT LEAST 8 bullets.

so if you have 'X' dragons, the hero will need at  '2X'bullets (at least)

here is the logic into code. 



function hero(bullets, dragons){

  if (bullets >= dragons*2)
  
  
  return true
  
  
  else
  
  
  return false

  or 

  return bullets >= dragons*2 ? true : false ; 
}






